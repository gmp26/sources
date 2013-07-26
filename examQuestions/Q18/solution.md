````
alias: Solution
````
###Method 1

Let $\frac{n}{100-n}=x$ where $x$ is an integer. Hence $n=100x-nx$.  

Adding $nx$ to both sides of the equation and factorising, we have $n(1+x)=100x$, giving $n=\frac{100x}{1+x}$.  

Now $x$ and $1+x$ can have no common factors greater than $1$. Therefore, as $n$ is an integer, $1+x$ must be some factor of $100$.  

Hence, $x+1$ can take any of the values $\pm1,\pm2,\pm4,\pm5,\pm10,\pm20,\pm25,\pm50,\pm100$. This gives $18$ different values for $x+1$. Each value of $x+1$ gives unique corresponding values of $x$ and $n$, so there are $18$ possible values of $n$ for which $\frac{n}{100-n}$ is an integer.

* * *

###Method 2

We see that $\frac{n}{100-n}$ is an integer if, and only if, $\frac{n}{n - 100}$ is an integer.  This, in turn, is true if, and only if, $\frac{n-100+100}{n-100} = 1 + \frac{100}{n-100}$ is an integer.

So the quantity in question is an integer if, and only if, $n - 100$ is a factor of $100$.  But $100 = 2^2 \times 5^2$, so $100$ has $(2+1)\times(2+1) = 9$ positive factors and so $18$ factors in total.  (The expression for the number of factors comes from the observation that any factor of $100$ must be of the form $2^a 5^b$, where $a$ is 0, 1 or 2 and $b$ is 0, 1 or 2.)
