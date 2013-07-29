````
alias: Solution
````

(i) Any factor of $3^2 \times 5^3$ must be of the form $3^r \times 5^s$ with $0
\leq r \leq 2$ and $0 \leq s \leq 3$.  This gives $3$ possible values for $r$
and $4$ for $s$, so there are $3 \times 4 = 12$ factors.  But two of these are
not _proper_ factors (namely $1$ and $3^2 \times 5^3$ itself), so there are $12 - 2 = 10$ proper factors.

    We could list these, if we wanted:

    * $3^0 \times 5^0 (= 1)$    (this is not a proper factor)

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

    * $3^2 \times 5^3 (= 1125)$ (this is not a proper factor).

    Now that we have done this and understood how to count the factors of $3^2 \times 5^3$, we can answer the second part: the number of proper factors of $3^m \times 5^n$ is $(m + 1)(n + 1) - 2$, as the power of $3$ in a factor can be $0$, $1$, ..., or $m$, and the power of $5$ can be $0$, $1$, ..., or $n$. So we require $(m + 1)(n + 1) - 2 = 10$, or equivalently $(m + 1)(n + 1) = 12$.

    $12$ can be factorised in the following ways:
    
    * $12=1\times12$,
    * $12=2\times6$,
    * $12=3\times4$,
    * $12=4\times3$,
    * $12=6\times2$ and
    * $12=12\times1$,

    which gives exactly six possible integers of the form $3^m \times 5^n$:
    $$3^0 \times 5^{11},   3^1 \times 5^5,   3^2 \times 5^3,   3^3 \times 5^2,   3^5 \times 5^1,   3^{11} \times 5^0.$$ 

    So there are $6$ possibilities in total. This means that there are $5$ other integers with the required properties.

***

(ii) Let $n=2^a \times 3^b \times 5^c \times 7^d \times ...$. The number of proper factors of $n$ is $(a+1)(b+1)(c+1)(d+1)...-2$ and we require this to be equal to $426$.

    That is, $$(a+1)(b+1)(c+1)(d+1)...=428.$$

    The prime factorisation of $428$ is $428=2^2 \times 107$.

    Therefore all the possible factorisations of $428$ are:
    * $428=1 \times 428$,
    * $428=2 \times 214$,
    * $428=2 \times 2 \times 107$ and
    * $428=4 \times 107.$

    We want to find the smallest possible $n$ so we must use the smallest primes and of these we must give the smallest primes the largest powers and the largest primes the smallest powers.

    Therefore we know that the smallest $n$ must be one of:
    * $2^{427}$,
    * $2^{213} \times 3$,
    * $2^{106} \times 3 \times 5$ and
    * $2^{106} \times 3^3$.

    The smallest of these is $2^{106} \times 3 \times 5$ because if we divide each solution by $2^{106}$ we obtain
    * $2^{321}$,
    * $2^{107} \times 3$,
    * $3 \times 5$ and
    * $3^3$,
    
    of which $3 \times 5$ is the smallest.

    Therefore $$N=2^{106} \times 3 \times 5.$$
