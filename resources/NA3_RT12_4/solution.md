````
alias: Solution

````

The general term of this sequence is $n^5-n$. We can factorise this expression as follows, using the expression for the difference of two squares:  

$$n^5-n=n(n^4-1)$$  

$$=n(n^2-1)(n^2+1)$$  

$$=n(n-1)(n+1)(n^2+1).$$  

<br>
This expression is divisible by two: $n$ and $n+1$ are two consecutive integers, so one of them must be even and the other odd. Then, as $n^5-n$ is divisible by both $n$ and $n+1$, it has at least one even factor and must therefore be even (the product of an even integer and any other integer is always even).  

<br>

This expression is also divisible by three: $n-1$, $n$, and $n+1$ are three consecutive integers, so one of them must be a multiple of three. We can see this by considering the remainder left upon dividing $n$ by three: this can take only the values zero, one, and two. If it is zero, $n$ is a multiple of three. If it is one, $n-1$ is a multiple of three. If it is two, $n+1$ is a multiple of three.  

Similarly to above, as $n^5-n$ is divisible by $n-1$, $n$, and $n+1$, it must have a factor which is a multiple of three, and therefore be itself divisible by three.  

<br>

This expression is also divisible by five, although this is slightly tricker to show than in the previous two parts. Firstly, we consider the remainder left when we divide $n$ by five. This can take the values zero, one, two, three, and four.  

If this remainder is zero, then $n$ itself is divisible by five, and then so is $n^5-n$, as it is divisible by $n$.  

If this remainder is one, then $n-1$ is divisible by five, and then so is $n^5-n$, as it is divisible by $n-1$.  

If this remainder is two, then $n$ is two greater than a multiple of five - that is, we can write $n=5k+2$ for some unknown integer $k$. Then, 
$$n^2+1=(5k+2)^2+1$$  

$$=25k^2+20k+4+1$$  

$$=25k^2+20k+5$$  

$$=5(5k^2+4k+1).$$

As $k$ is an integer, $5k^2+4k+1$ is simply some other integer, and $n^2+1$ is a multiple of five. Then, so is $n^5-5$, as it is divisible by $n^2+1$.  

Similarly, if this remainder is three, then we can write $n=5m+3$, for some other integer m. Then,  

$$n^2+1=(5m+3)^2+1$$  

$$=25m^2+30m+10$$  

$$=5(5m^2+6m+2).$$

So again, $n^2+1$ is a multiple of five, meaning that $n^5-n$ is too.  

If this remainder is four, then $n+1$ is divisible by five, and then so is $n^5-n$, as it is divisible by $n+1$.  


<br>

We have shown that, for all $n$, $n^5-n$ is divisible by two, three, and five. This means that every term in the sequence is divisible by the lowest common multiple of two, three and five---in this case this is simply their product, $30$, as they have no common prime factors.  

So, $30$ divides every number in the sequence. This means that the largest integer which divides every term in the sequence must be at least $30$.  

Now, look at the second term in the sequence: $2^5-2$. This is equal to $30$, which obviously cannot be divided by any integers greater than itself. So, $30$ is the largest integer which divides every term in the sequence.
