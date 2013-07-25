````
alias: Solution
````

We require $a^2=2b^3$, so $2|a^2$. Since $2$ is prime, we must have $2|a$. Similarly, $a^2=3c^5$, so $3|a^2$ and because $3$ is prime we must have $3|a$.

Therefore, let $a=2^{\alpha_1}3^{\alpha_2}a_1$ where ${\alpha_1}$ and ${\alpha_2}$ are positive integers and $a_1$ is a positive integer coprime to $2$ and $3$.

When we substitute this representation of $a$ into the given equation we obtain $$2^{2\alpha_1}3^{2\alpha_2}a_1^2=2b^3=3c^5.$$

Now we see that $2^{2\alpha_1}|2b^3$, and because $\alpha_1$ is a positive integer there are at least two factors of $2$ in $2^{2\alpha_1}$. Therefore $b^3$ must be divisible by $2$, and because $2$ is prime, $2|b$. Also, $3^{2\alpha_2}|2b^3$, and because $3$ is prime we have $3|b$.

Similarly $2|c$ and $3|c$, so let $$b=2^{\beta_1}3^{\beta_2}b_1$$ and $$c=2^{\gamma_1}3^{\gamma_2}c_1$$ where $\beta_1$, $\beta_2$, $\gamma_1$ and $\gamma_2$ are positive integers and $b_1$ and $c_1$ are positive integers coprime to $2$ and $3$.

When we substitute these representations of $b$ and $c$ -along with the representation of $a$ we used earlier- into the given equation we obtain
$$2^{2\alpha_1}3^{2\alpha_2}a_1^2=2^{1+3\beta_1}3^{3\beta_2}b_1^3=2^{5\gamma_1}3^{1+5\gamma_2}c_1^5.$$

Since $3$, $a_1$, $b_1$ and $c_1$ are coprime to $2$ we must equate the powers of $2$, and similarly we must equate the powers of $3$.

So we must have $$2\alpha_1=1+3\beta_1=5\gamma_1$$ and $$2\alpha_2=3\beta_2=1+5\alpha_2.$$

Since $2\alpha_1=5\gamma_1$, we see that $5|2\alpha_1$ and because $2$ and $5$ are coprime we have $5|\alpha_1$. So let $\alpha_1=5k$ where $k$ is a positive integer. Then $\gamma_1=2k$ and $1+3\beta_1=10k$.
So $$\beta_1=\frac{10k-1}{3}=3k+\frac{k-1}{3}.$$

$\beta_1$ must be an integer, so we must have $\frac{k-1}{3}=n$ where $n$ is a non-negative integer (notice that we can have $n=0$).

So $k=3n+1$, and
$$\alpha_1=5(3n+1),$$ $$\beta_1=10n+3$$ and $$\gamma_1=2(3n+1).$$

Using a similar process for $2\alpha_2=3\beta_2=1+5\alpha_2$ shows that $$\alpha_2=3(5m+1),$$ $$\beta_2=2(5m+1)$$ and $$\gamma_2=6m+1$$ where $m$ is a non-negative integer.

Therefore all solutions are of the form $$a=2^{5(3n+1)}3^{3(5m+1)}a_1,$$ $$b=2^{10n+3}3^{2(5m+1)}b_1$$ and $$c=2^{2(3n+1)}3^{6m+1}c_1$$ where $n$ and $m$ are non-negative integers and $a_1$, $c_1$ and $b_1$ are positive integers coprime to $2$ and $3$.

To find the smallest possible solution we need to choose $a_1=b_1=c_1=1$ and $n=m=0$.

Then $$a=2^53^3,$$ $$b=2^33^2$$ and $$c=2^23.$$



What can we say about $a_1$, $b_1$ and $c_1$?

Putting our representations of $a$, $b$ and $c$ into the given equation and cancelling all factors of $2$ and $3$ shows that $$a_1^2=b_1^3=c_1^5.$$

If $a$ has a prime factor $p$ then we can see immediately that $p$ divides $b$ and $c$. Similarly all prime factors of $b$ and $c$ are prime factors of $a$, $b$ and $c$. So the prime factorisations of $a$, $b$ and $c$ use exactly the same primes.

Let $\alpha$, $\beta$ and $\gamma$ be the greatest positive integers such that $p^\alpha|a$, $p^\beta|b$ and $p^\gamma|c$. For example, $p^\alpha|a$ but $p^{\alpha+1}$ does not divide $a$.



Then equating powers of $p$ in the given equation show that $$2\alpha=3\beta=5\gamma.$$

This has solution $$\alpha=15r,$$ $$\beta=10r$$ and $$\gamma=6r$$ were $r$ is a positive integer.

Therefore we can let $$a_1=d^{15},$$ $$b_1=d^{10}$$ and $$c_1=d^6$$ where $d$ is any positive integer coprime to $2$ and $3$.

This gives the general solution $$a=2^{5(3n+1)}3^{3(5m+1)}d^{15},$$ $$b=2^{10n+3}3^{2(5m+1)}d^{10}$$ and $$c=2^{2(3n+1)}3^{6m+1}d^6$$ where $n$ and $m$ are any non-negative integers and $d$ is any positive integer coprime to $2$ and $3$.

Notice this can be rerranged to give $$a=2^53^3(2^n3^md)^{15},$$ $$b=2^33^2(2^n3^md)^{10}$$ and $$c=2^23(2^n3^md)^6$$ so it is easy to see where our smallest solution came from. 
