````
alias: Solution
````

Based on the two examples given, we guess
$$\frac{1}{N}=\frac{1}{N + 1} + \frac{1}{N(N+1)},$$
i.e. $a = N+1$ and $b=N(N+1)$. To justify this, it suffices to note that
$$\frac{1}{N + 1} + \frac{1}{N(N+1)} = \frac{N+1}{N(N + 1)} = \frac{1}{N}.$$
In this expression, we can choose $N$ to be an arbitrary integer greater than $1$. Since $N(N+1) > N+1$ if $N>1$, it follows that any unit fraction can be expressed as the sum of two distinct unit fractions.

* * *

In the following, we do not distinguish between
$$\frac{1}{N} = \frac{1}{a}+\frac{1}{b}\qquad\mbox{and}\qquad \frac{1}{N} = \frac{1}{b}+\frac{1}{a}$$
and without loss of generality we may assume $a\leq b$. If $N$ is prime then there are only two possible ways of factorising $N^2$, namely $N^2=N\times N$ and $N^2=1\times N^2$. Comparing this with
$$(a-N)(b-N)=N^2$$
gives $a-N=b-N=N$ in the first case and $a-N = 1$ and $b-N=N^2$ in the latter case. If we have $a-N=b-N=N$ then $a=b$ whereas $a-N = 1$ and $b-N=N^2$ yields $b=N(N+1)>N+1=a$. Therefore, there is indeed only one way of expressing $1/N$ as the sum of two **distinct** unit fractions.

* * *

For the last part, we want to prove that if $N>2$ is prime then we can uniquely write
$$\frac{2}{N}=\frac{1}{c}+\frac{1}{d}$$
with $c\not= d$. If we have such a way then
$$\frac{1}{N}=\frac{1}{2c} + \frac{1}{2d}$$
where both $2c$ and $2d$ are integers. On the other hand, since $N$ is a prime we already know that
$$\frac{1}{N}=\frac{1}{N + 1} + \frac{1}{N(N+1)}$$
is the unique way of expressing $1/N$ as the sum of two distinct unit fractions. Moreover, as $N$ is a prime greater than $2$ it must be odd and therefore, both $N+1$ and $N(N+1)$ are even. Thus, $(N+1)/2$ and $N(N+1)/2$ are integers and therefore, there is indeed a unique way of expressing $2/N$ as the sum of two distinct unit fractions, namely
$$\frac{2}{N}=\frac{1}{\frac{N+1}{2}}+\frac{1}{\frac{N(N+1)}{2}}.$$
