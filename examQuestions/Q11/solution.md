````
alias: Solution
````

We find the points of intersection of the two ellipses by solving the simultaneous equations

$$(x + 2)^2 + 2y^2 = 18$$
and
$$9(x - 1)^2 + 16y^2 = 25.$$

We can eliminate $y$ by multiplying the first equation by $8$ and subtracting the second equation from it:

$$8(x + 2)^2 - 9(x - 1)^2 = 144 - 25$$

$$\iff x^2 - 50x + 96 = 0$$

$$\iff (x - 2)(x - 48) = 0.$$

This gives the two $x$-values of the points of intersection as $2$ and $48$.

Taking $x = 2$ and substituting into the first simultaneous equation, we have
$$16 + 2y^2 = 18$$
$$\iff y^2 = 1$$
$$\iff y = \pm1.$$
Taking $x = 48$ gives $50^2 + 2y^2 = 18$ which has no (real) roots, since we will have $y^2$ equal to a negative number. Hence there are two points of intersection, at $(2,1)$ and $(2,-1)$ (it is easy to check that these points really do lie on both ellipses).


Say a circle through these points has centre $(p,q)$ and radius $R$. Then the equation of the circle is
$$(x - p)^2 + (y - q)^2 = R^2.$$
Setting $(x,y) = (2,1)$ and $(x,y) = (2,-1)$ gives two equations:

$$(2 - p)^2 + (1 - q)^2 = R^2$$
and
$$(2 - p)^2 + (-1 - q)^2 = R^2.$$

Subtracting the second from the first gives
$$(1 - q)^2 - (-1 - q)^2 = 0$$
$$\iff (1 - q)^2 = (1 + q)^2$$
$$\iff q = - q$$
$$\iff q = 0.$$

<:= style(chalk) :>
Note that it is clear anyway that the centre of the circle must lie on the $y$-axis.
<:= style() :>

Hence the equation of any circle passing through the intersections is
$$(x - p)^2 + y^2 = R^2.$$
This $R$ is the same for any point on the circle, so we can replace $R^2$ by $(x - p)^2 + y^2$ for any specific point $(x,y)$ on the circle, such as $(2, 1)$.  Thus
$$(x - p)^2 + y^2 = (2 - p)^2 + 1.$$
Relabelling $p$ as $a$ and simplifying gives
$$x^2 - 2ax + a^2 + y^2 = 5 - 4a + a^2$$
$$\iff x^2 - 2ax + y^2 = 5 - 4a$$
as required.
