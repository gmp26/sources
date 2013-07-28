````
alias: Solution
````

(i) Any factor of $3^2 \times 5^3$ must be of the form $3^r \times 5^s$ with $0 \leq r \leq 2$ and $0 \leq s \leq 3$.  This gives $3$ possible values for $r$ and $4$ for $s$, so there are $3 \times 4 = 12$ factors.  But two of these are not _proper_ factors (namely $1$ and $3^2 \times 5^3$ itself), so there are $12 - 2 = 10$ proper factors.

    We could list these, if we wanted:

    * $3^0 \times 5^0 (= 1)$	(this is not a proper factor)

    * $3^0 \times 5^1 (= 5)$

    * $3^0 \times 5^2 (= 25)$

    * $3^0 \times 5^3 (= 125)$

    * $3^1 \times 5^0 (= 3)$

    * $3^1 \times 5^1 (= 15)$

    * $3^1 \times 5^2 (= 75)$

    * $3^1 \times 5^3 (= 375)$

    * $3^2 \times 5^0 (= 9)$

    * $3^2 \times 5^1 (= 45)$

    * $3^2 \times 5^2 (= 225)$

    * $3^2 \times 5^3 (= 1125)$	(this is not a proper factor).


***

  Now that we have done this and understood how to count the factors of $3^2 \times 5^3$, we can answer the second part: the number of proper factors of $3^a \times 5^b$ is $(a + 1)(b + 1) - 2$, as the power of $3$ in a factor can be $0$, $1$, ..., or $a$, and the power of $5$ can be $0$, $1$, ..., or $b$. So we require $(a + 1)(b + 1) - 2 = 10$, or $(a + 1)(b + 1) = 12$.

  UNFINISHED

  So there are $6$ possibilities in total. This means that there are $5$ other integers with the required properties.
