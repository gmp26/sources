````
alias: Solution

````

The general term of this sequence is $n^5-n$. We can factorise this expression as follows, using the expression for the difference of two squares:  

$$n^5-n=n(n^4-1)$$  

$$=n(n^2-1)(n^2+1)$$  

$$=n(n-1)(n+1)(n^2+1).$$  

This expression is divisible by $2$.  That's because $n$ and $n+1$ are two consecutive integers, so one of them must be even and the other odd. Then, as $n^5-n$ is divisible by both $n$ and $n+1$, it has at least one even factor and must therefore be even (the product of an even integer and any other integer is always even).  

This expression is also divisible by $3$.  That's because $n-1$, $n$ and $n+1$ are three consecutive integers, so one of them must be a multiple of $3$. We can see this by considering the remainder left upon dividing $n$ by $3$: the only possible values are $0$, $1$, and $2$. If it is $0$, then $n$ is a multiple of $3$. If it is $3$, then $n-1$ is a multiple of $3$. If it is $2$, then $n+1$ is a multiple of $3$.  

Similarly to above, since $n^5-n$ is divisible by $n-1$, $n$, and $n+1$, it must have a factor which is a multiple of $3$, and therefore must itself be divisible by $3$.  

This expression is also divisible by $5$, although this is slightly tricker to show than in the previous two parts. Firstly, we consider the remainder left when we divide $n$ by $5$. This can take the values $0$, $1$, $2$, $3$, and $4$.  We'll consider the five cases separately.

* * *

#####Case 1
If this remainder is $0$, then $n$ itself is divisible by $5$, and then so is $n^5-n$, since it is divisible by $n$.  

#####Case 2
If this remainder is $1$, then $n-1$ is divisible by $5$, and then so is $n^5-n$, as it is divisible by $n-1$.  

#####Case 3
If this remainder is $2$, then $n$ is $2$ greater than a multiple of $5$.  That is, we can write $n=5k+2$ for some integer $k$. Then
$$n^2+1=(5k+2)^2+1$$  

$$=25k^2+20k+4+1$$  

$$=25k^2+20k+5$$  

$$=5(5k^2+4k+1).$$

As $k$ is an integer, $5k^2+4k+1$ is also an integer, and so $n^2+1$ is a multiple of $5$. Then so is $n^5-5$, as it is divisible by $n^2+1$.  

#####Case 4
Similarly, if this remainder is $3$, then we can write $n=5m+3$, for some integer $m$. Then  

$$n^2+1=(5m+3)^2+1$$  

$$=25m^2+30m+10$$  

$$=5(5m^2+6m+2).$$

So again, $n^2+1$ is a multiple of $5$, meaning that $n^5-n$ is too.  

#####Case 5
If the remainder is $4$, then $n+1$ is divisible by $5$, and then so is $n^5-n$, as it is divisible by $n+1$.  

* * *

We have shown that, for all $n$, $n^5-n$ is divisible by $2$, $3$, and $5$. This means that every term in the sequence is divisible by the lowest common multiple of $2$, $3$ and $5$.  In this case this is simply their product, $30$, as they have no common prime factors.  

So $30$ divides every number in the sequence. This means that the largest integer which divides every term in the sequence must be at least $30$.  

Now, look at the second term in the sequence: $2^5-2$. This is equal to $30$, which obviously is not divisible by any integers greater than itself. So, $30$ is the largest integer which divides every term in the sequence.
