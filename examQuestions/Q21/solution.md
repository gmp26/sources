````
alias: Solution
````

Expand the brackets to obtain $$(n+3)^3=n^3+9n^2+27n+27,$$ and $$(n-3)^3=n^3-9n^2+27n-27.$$

Then the equation simplifies to $$n^3-18n^2-54=0,$$ which can be rearranged to $$n^2(n-18)=54.$$ If $n$ is odd then $n^2$ and $n-18$ are odd, and so their product is odd. But this is a contradiction because we know that $n^2(n-18)=54$.  Therefore $n$ is even.

Alternatively we could argue as follows: if $n$ is odd then $n-3$ and $n+3$ are both even. Then $n^3$ is odd and $(n-3)^3$ and $(n+3)^3$ are both even. But then the left hand side of $(n-3)^3+n^3=(n+3)^3$ is odd whilst the right hand side is even, which is a contradiction. Therefore $n$ must be even.

From the rearrangement $n^2(n-18)=54$ we can see immediately, because $n$ is an integer, that $n^2$ is a factor of $54$.

If there is an integer $n$ which satisfies the equation then we know it must be even and $n^2$ must be a factor of $54$. The prime factorisation of $54$ is $54=2\times3^3$ and so the only square factor of $54$ is $3^2$. But $3$ is not even, so there is no such $n$.

Alternatively we could argue that because $n^2$ is always non-negative for integer values of $n$ and $n^2(n-18)=54$ we must have $n-18 > 0$, but $18^2>54$ so $n^2$ cannot be a factor of $54$.

* * *

We can use a very similar idea for the second part.

We have
$$(n+6)^3=n^3+18n^2+108n+216,$$ and $$(n-6)^3=n^3-18n^2+108n-216.$$

So the equation simplifies to $$n^3-36n^2-432=0,$$ which can be rearranged into $$n^2(n-36)=432.$$ If $n$ is odd then $n^2$ and $n-36$ are odd, and so their product is odd. But this is a contradiction because we know that $n^2(n-36)=432.$ Therefore $n$ is even.

We can also note that $n^2$ is a factor of $432$.

Since $n^2$ is always non-negative for integer values of $n$ we must have $n>36$, but $36^2>432$ so $n^2$ cannot be a factor of $432$. Therefore there is no such $n$.
