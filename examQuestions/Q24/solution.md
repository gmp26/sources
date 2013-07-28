````
alias: Solution
````

(i) We have
$$a^3 = 9c^3 - 3b^3 = 3(3c^3 - b^3),$$
so $a^3$ is a multiple of $3$. Note that if $3$ divides a product $rs$, then $3$ must divide either $r$ or $s$, as $3$ is prime. Therefore, since $a^3 = a.a.a$, and $3$ divides $a^3$, it follows that $3$ must divide one of the factors, that is, $3$ must divide $a$.

	Now we can write $a = 3d$, where $d$ is an integer. Therefore we have  
$$(3d)^3 + 3b^3 = 9c^3,$$
which, on dividing by $3$, gives
$$9d^3 + b^3 = 3c^3.$$

	By the same argument, as  
$$b^3 = 3(c^3 - 3d^3),$$
it follows that $b^3$, and hence also $b$, is divisible by $3$.

	We repeat the same trick, writing $b = 3e$, where $e$ is an integer, so that  
$$9d^3 + (3e)^3 = 3c^3.$$

	We again divide by $3$ to get  
$$3d^3 + 9e^3 = c^3,$$
so that $c^3$, and hence also $c$, is divisible by $3$.

	We then write $c = 3f$, where $f$ is an integer, giving  
$$3d^3 + 9e^3 = (3f)^3.$$

	Finally, we divide this equation by $3$ to get  
$$d^3 + 3e^3 = 9f^3.$$

	Note that this is the same equation that we started with, so if $a$, $b$, $c$ are integers which satisfy the equation, then so are $d = \frac{a}{3}$, $e = \frac{b}{3}$ and $f = \frac{c}{3}$. We can repeat this process indefinitely, so that for any $n$, the numbers $\frac{a}{3^n}$, $\frac{b}{3^n}$ and $\frac{c}{3^n}$ are also integers which satisfy the equation. But if $\frac{a}{3^n}$ is an integer for all $n \ge 0$, we must have $a = 0$, and similarly for $b$ and $c$.  

	Therefore the only integer solution is $a = b = c = 0$.  

(ii) We are interested in the equation $$p^4 + 2q^4 = 5r^4.$$
    We consider the final digit of fourth powers:


    --------------------------
    $a$      $a^4$    $2a^4$ 
    -------- -------- --------
    $0$      $0$      $0$

    $1$      $1$      $2$

    $2$      $6$      $2$  

    $3$      $1$      $2$

    $4$      $6$      $2$

    $5$      $5$      $0$

    $6$      $6$      $2$

    $7$      $1$      $2$

    $8$      $6$      $2$

    $9$      $1$      $2$
    ------------------------- 



    So the last digits of fourth powers are all either $0$, $1$, $5$ or $6$, and the last digits of twice fourth powers are all either $0$ or $2$.

    Also, $5r^4$ is a multiple of $5$, so it must end in a $0$ or a $5$.

    Therefore, if $2q^4$ ends in $0$ (which happens exactly when $q$ is a multiple of $5$), the possibilities for the final digit of $p^4 + 2q^4$ are  

    $$(0 \mbox{ or } 1 \mbox{ or } 5 \mbox{ or } 6)+ 0 = 0 \mbox{ or } 1 \mbox{ or } 5 \mbox{ or } 6,$$

    so it can equal $5r^4$ (which ends in $0$ or $5$) only if $p^4$ ends in $0$ or $5$, which is exactly when $p$ is a multiple of $5$.

    Similarly, if $2q^4$ ends in $2$ (so $q$ is not a multiple of $5$), the possibilities for the final digit of $p^4 + 2q^4$ are

    $$(0 \mbox{ or } 1 \mbox{ or } 5 \mbox{ or } 6)+ 2 = 2 \mbox{ or } 3 \mbox{ or } 7 \mbox{ or } 8,$$

    so it can't be equal to $5r^4$ (which ends in $0$ or $5$).

    Therefore, if $p^4 + 2q^4 = 5r^4$, we must have $p$ and $q$ both being multiples of $5$.

    Now as in part (i), we write $p = 5a$ and $q = 5b$, where $a$ and $b$ are both integers, to get  
  $$(5a)^4 + 2(5b)^4 = 5r^4.$$

    Dividing both sides by $5$ gives  
    $$5^3a^4 + 2.5^3b^4 = r^4,$$  
    where we are using dot to mean multiplication, so as before, $r^4$ must be a multiple of $5$ as the left hand side is $5(5^2a^4 + 2.5^2b^4)$. Thus, since $5$ is prime, $r$ itself must be divisible by $5$. Then writing $r = 5c$ gives  
    $$5^3a^4 + 2.5^3b^4 = (5c)^4,$$  
    which yields  
    $$a^4 + 2b^4 = 5c^4$$  
    on dividing by $5^3$.  

    So once again, if $p$, $q$, $r$ give an integer solution to the equation, then so do $a = \frac{p}{5}$, $b = \frac{q}{5}$ and $c = \frac{r}{5}$. Repeating this, so are $\frac{p}{5^n}$, $\frac{q}{5^n}$, $\frac{r}{5^n}$ for any integer $n \geq 0$, and as before, this shows that the only integer solution is $p = q = r = 0$.

    <!--(Again, the same argument as before shows that this is also the only rational solution.)-->
  
This type of argument is sometimes known as _infinite descent_.
