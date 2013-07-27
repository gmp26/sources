````
alias: Solution
````

(i) We are told that $AP = 2BP$, which is the same as $(AP)^2 = 4(BP)^2$ (since distances are positive).

<div class="chalk">
We use the formula for the distance $d$ between two points $(x_1,y_1)$ and $(x_2,y_2)$, which is $d^2 = (x_2-x_1)^2 + (y_2-y_1)^2$.
</div>

So the above expression becomes

$(x - 5)^2 + (y - 16)^2 = 4((x + 4)^2 + (y - 4)^2)$

$\iff x^2 + y^2 - 10x - 32y + 281 = 4x^2 + 4y^2 + 32x - 32y + 128$

$\iff 3x^2 + 3y^2 + 42x - 153 = 0$

$\iff x^2 + y^2 + 14x - 51 = 0$

$\iff (x + 7)^2 - 49 + y^2 - 51 = 0$

$\iff (x + 7)^2 + y^2 = 100$.

This is the equation of a circle with centre $(-7,0)$ and radius $10$.

* * *

(ii) Using the same approach as in part (i), we have

$(QC)^2 = k^2 \times (QD)^2$

$\iff (x - a)^2 + y^2 = k^2(x - b)^2 + k^2y^2$

$\iff x^2 - 2ax + a^2 + y^2 = k^2 x^2 - 2bk^2 x + b^2 k^2 + k^2 y^2$

$\iff x^2(k^2 - 1) + y^2(k^2 - 1) + x(2a - 2b k^2) + (b^2 k^2 - a^2) = 0$.

If this locus is the same as the locus of $P$, then the ratios of the coefficients must be the same, so

$$\frac{2a - 2b k^2}{k^2 - 1} = 14$$ and $$\frac{b^2 k^2 - a^2}{k^2 - 1} = -51.$$

<div class="chalk">
Note that we cannot conclude that $k^2 - 1 = 1$, and must instead divide by it to make the coefficients of the $x^2$ and $y^2$ terms equal to 1.
</div>

The first of these gives
$$2a - 2b k^2 = 14k^2 - 14,$$
so
$$k^2 = \frac{a + 7}{b + 7}.$$

Similarly, the second rearranges to

$$b^2 k^2 - a^2 = -51k^2 + 51,$$
so
$$k^2 = \frac{a^2 + 51}{b^2 + 51}.$$

Thus 
$$\frac{a + 7}{b + 7} = \frac{a^2 + 51}{b^2 + 51}.$$

Now we can rearrange this to
$$(a + 7)(b^2 + 51) = (b + 7)(a^2 + 51)$$

$$\iff ab^2 + 7b^2 + 51a = a^2b + 7a^2 + 51b$$

$$\iff ab^2 - a^2b = 7(a^2 - b^2) + 51(b - a)$$

$$\iff ab(b - a) = 7(a - b)(a + b) + 51(b - a).$$

Since $a \neq b$, we may divide by $b-a$ to obtain

$$ab = 51 - 7(a + b).$$

That is,

$$ab + 7(a + b) = 51$$

$$\Rightarrow ab + 7(a + b) + 49 = 51 + 49$$

$$\Rightarrow (a + 7)(b + 7) = 100.$$
