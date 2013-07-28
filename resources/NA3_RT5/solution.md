````
alias: Solution
````

(a) 

#####The highest power of $5$ dividing $20!$ 

We have $20! = 20 \times 19 \times 18 \times \dotsm \times 3 \times 2 \times 1$.  

Since $5$ is a prime number, we can just add the highest power of $5$ dividing each of the numbers $1$, $2$, $3$, ..., $20$. There are only four numbers in this range ($5$, $10$, $15$, $20$) that are divisible by $5^1$, and none of them is divisible by $5^2$. So the highest power of $5$ dividing $20!$ is $5^4$.  

* * *

#####Factors of $20!$  

The first thing we need to do is find the prime factorisation of $20!$. As $20!=20 \times 19 \times 18 \times \dotsm \times 3 \times 2 \times 1$, we can can do this by finding the prime factorisation of each of the numbers $2$, $3$, ..., $20$ (ignoring $1$ since it won't contribute any primes) and multiplying them together.  

------------------------------
 Number   Prime factorisation
-------- ---------------------
 $2$      $2$                

 $3$      $3$                

 $4$      $2^2$       

 $5$      $5$                

 $6$      $2 \times 3$       

 $7$      $7$                

 $8$      $2^3$              

 $9$      $3^2$       

 $10$     $2 \times 5$       

 $11$     $11$               

 $12$     $2^2 \times 3$     

 $13$     $13$              

 $14$     $2 \times 7$       

 $15$     $3 \times 5$       

 $16$     $2^4$              

 $17$     $17$                

 $18$     $2 \times 3^2$     

 $19$     $19$               
 
 $20$     $2^2 \times 5$     
------------------------------



Multiplying the prime factorisations in the right-hand column together and simplifying, we get  

$20!=2^{18} \times 3^8 \times 5^4 \times 7^2 \times 11 \times 13 \times 17 \times 19$.  

Now we can use this to calculate the number of divisors of $20!$. Each divisor will have a unique prime factorisation, which must be 'contained' within the prime factorisation of $20!$. Let $m$ be a divisor of $20!$. Then there are nineteen possible values for the highest power of $2$ dividing $m$ ($0$, $1$, ..., $18$). Similarly, there are nine possible values for the highest power of $3$ dividing $m$ ($0$, $1$, ..., $8$). Continuing in this way for all the prime factors of $20!$, we can calculate that there are $19 \times 9 \times 5 \times 3 \times 2 \times 2 \times 2 \times 2 = 41040$ divisors of $20!$.  

(b)

#####The highest power of $k$ that divides $500!$, where $k^t<500<k^{t+1}$

We can see that $\left[\frac{500}{k}\right]$ is the number of multiples of $k$ that are less than or equal to $500$. For example, if $k$ goes into $500$ "seven and a bit" times, this means that $k$, $2k$, ..., $7k$ are less than $500$ but $8k$ is greater than $500$.  

Similarly, $\left[\frac{500}{k^2}\right]$ is the number of multiples of $k^2$ that are less than or equal to $500$, and so on.  

Now, we can work out the highest power of $k$ that divides $500!$ by considering the number of multiples of $k$, $k^2$, ..., $k^t$ less than $500$.

We need to count all the multiples of $k$.  We need to count the multiples of $k^2$ twice, since they contribute $2$ to the exponent, but we have already counted them once in the multiples of $k$ so we need to count them just once more.  Similarly, we need to count the multiples of $k^3$ three times in total, but we have already counted them twice (once in the multiples of $k$ and once in the multiples of $k^2$), so we need to count them just once more.  And so on for the remaining powers.  So the highest power of $k$ that divides $500!$ has exponent

$$\left[\frac{500}{k}\right]+\left[\frac{500}{k^2}\right]+ \dotsb +\left[\frac{500}{k^t}\right]$$


(c)

#####Factors of $n!$  

We can generalise the above result beyond the case of $500!$.  The highest power of $k$ that divides $n!$, where $k^t < n < k^{t+1}$, is equal to $$\left[\frac{n}{k}\right] + \left[\frac{n}{k^2}\right] + \dotsb + \left[\frac{n}{k^t}\right],$$ by exactly the same reasoning as in (b).  

We can use this information to find the prime factorisation of $n!$. Let $p$ be the largest prime with $p\leq n$. Also, for any number $m$, let $t_m$ be the integer such that $m^{t_m} \leq n< m^{t_m+1}$.  

Using the information from part (b), we can then calculate the prime factorisation of $n!$: we have  

$$n! = 2^{\left(\left[\frac{n}{2}\right]+\left[\frac{n}{2^2}\right] + \dotsb +\left[\frac{n}{2^{t_2}}\right]\right)} \times 3^{\left(\left[\frac{n}{3}\right]+\left[\frac{n}{3^3}\right]+ \dotsb +\left[\frac{n}{3^{t_3}}\right]\right)} \times \dotsm \times p^{\left(\left[\frac{n}{p}\right] + \left[\frac{n}{p^2}\right] + \dotsb +\left[\frac{n}{p^{t_p}}\right]\right)}.$$  

Then we can use the same reasoning as in part (a) to calculate the number of factors of $n!$: we get

$$\left(1 + \left[\frac{n}{2}\right]+\left[\frac{n}{2^2}\right]+ \dotsb + \left[\frac{n}{2^{t_2}}\right]\right) \times \left(1 + \left[\frac{n}{3}\right] + \left[\frac{n}{3^2}\right] + \dotsb + \left[\frac{n}{3^{t_3}}\right]\right) \times \dotsm$$
$$ \times \left(1 + \left[\frac{n}{p}\right] + \left[\frac{n}{p^2}\right] + \dotsb +\left[\frac{n}{p^{t_p}}\right]\right).$$  

We can check that this expression works for the example of $20!$:

$$\left(1 + \left[\frac{20}{2}\right]+\left[\frac{20}{4}\right]+\left[\frac{20}{8}\right]+\left[\frac{20}{16}\right] \right) \times \left(1 + \left[\frac{20}{3}\right] + \left[\frac{20}{9}\right]\right) \times \left(1 + \left[\frac{20}{5}\right]\right) \times \left(1 + \left[\frac{20}{7}\right]\right) \times$$
$$ \left(1 + \left[\frac{20}{11}\right]\right) \times \left(1 + \left[\frac{20}{13}\right]\right) \times \left(1 + \left[\frac{20}{17}\right]\right) \times \left(1 + \left[\frac{20}{19}\right]\right)$$ 
$$= (10+5+2+1+1) \times (6+2+1) \times (4+1) \times (2+1) \times (1+1) \times (1+1) \times (1+1) \times (1+1)$$
$$=19 \times 9 \times 5 \times 3 \times 2 \times 2 \times 2 \times 2 = 41040.$$

This is the same answer as in part (a), suggesting that this formula works!
