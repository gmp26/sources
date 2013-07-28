````
alias: Solution
````

#####Claim

If the two numbers have a highest common factor greater than $1$, then dividing one by the other cannot give a remainder of $1$.

#####Proof
Let two numbers $a$ and $b$ (with $a > b$) have a hcf of $d$, which is larger than $1$.  We may assume that $a$ is not divisible by $b$ (otherwise it is not an interesting question). Then when we divide $a$ by $b$, we have $a = qb + r$ for some integers $q$ and $r$ with $1 \leq r < b$. Rearranging this gives $$r = a - qb.$$ But now the RHS is divisible by $d$, so $r$ must also be divisible by $d$. Hence the remainder is some multiple of $d$, and so must be greater than $1$.

***

#####Claim

If instead the hcf of the two numbers is $1$ (i.e. they are _coprime_), then there will always be a remainder of 1.

#####Proof

If $a$ and $b$ (with $a > b$) are coprime, then their lowest common multiple is $ab$.

The remainders of the numbers in the question, upon division by $b$, could be written $r_1$, $r_2$, ..., $r_{b - 1}$. We want to show that no two of these remainders are the same. If we suppose that two of them __are__ the same, then we can try to force a contradiction.

Suppose that $r_k$ and $r_l$ are the same, with $k < l$. Call this value of the remainder $R$. Then, for some $m$ and $n$, we have
$$ka = nb + R$$
and
$$la = mb + R$$
for some integers $m$ and $n$.

Now, since $R$ is the same in both cases, we can take away one from the other to get
$$la - ka = mb - nb$$
$$\iff (l - k)a = (m - n)b.$$

This means that $(l - k)a$ is divisible by $b$. However, $l - k$ is an integer value somewhere between $1$ and $b - 2$. We already know that $ab$ is the smallest multiple of $a$ that is divisible by $b$, so there is no possible value of $l - k$ that will make $(l - k)a$ divisible by $b$. This is a contradiction!

The conclusion is that no two of these remainders can be the same---they must all be different.

Since there are $b - 1$ remainders, which have to take one of the values $1, 2, ..., b - 1$, it follows that one of the remainders will be $1$, which is what we wanted to prove.
