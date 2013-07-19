````
alias: Solution
````

The general equation of a circle with centre $(a,b)$ and radius $r$ is $(x - a)^2 + (y - b)^2 = r^2$.

Since the centre lies on the line $2y = x$, we have that $2b = a$.

Since the point $(14,2)$ lies on the circle, we can substitute this and $2b = a$ into our general equation to get $$(14 - 2b)^2 + (2 - b)^2 = r^2. \quad (\ast)$$

We also know that the $x$-axis just touches the circle, so we find their intersection by substituting $y = 0$ into our equation:

$$(x - a)^2 + b^2 = r^2$$
$$\Rightarrow x^2 - 2ax + (a^2 + b^2 - r^2) = 0.$$

This is a quadratic in $x$, and it only has one solution since we know that the $x$-axis is a tangent to the circle. So the discriminant $B^2 - 4AC$ is equal to zero:

$$4a^2 - 4(a^2 + b^2 - r^2) = 0$$
$$\Rightarrow b^2 = r^2.$$

<div class="chalk span4 pull-right">
There is also a neat way of reaching $|b|=r$ geometrically: the centre is $(a,b)$, and the $x$-axis is a tangent, so it will touch the circle directly below (or above) the centre, at $(a,0)$ (because any tangent of a circle is perpendicular to a radius of that circle). Then the distance from this point to the centre is $|b|$, but this is also the radial distance, so $|b| = r$.
</div>

Now we can substitute this into $(\ast)$ and solve for $b$:

$(14 - 2b)^2 + (2 - b)^2 = b^2$

$\Rightarrow 196 - 56b + 4b^2 + 4 - 4b + b^2 = b^2$

$\Rightarrow 4b^2 - 60b + 200 = 0$

$\Rightarrow b^2 - 15b + 50 = 0$

$\Rightarrow (b - 5)(b - 10) = 0$

$\Rightarrow b = 5$ or $b = 10$.

Finally, using $2b = a$ and $b^2 = r^2$, we have that the two possible solutions are

$$b = 5, a = 10, r = 5$$ $$b = 10, a = 20, r = 10$$

and so the equations of the two circles are

$$(x - 10)^2 + (y - 5)^2 = 25$$ and $$(x - 20)^2 + (y - 10)^2 = 100.$$


<div class="chalk">
For the second part of the question, we give two methods. The first uses direct substitution to find where the line intersects the two circles. The second uses the fact that the tangent to the circle will be perpendicular to the radius at that point, and avoids having to deal with quadratics.
</div>

##Method 1

For the first circle, expanding and substituting $x = \frac{3}{4}y$ we have

$x^2 - 20x + y^2 - 10y + 100 = 0$ and $x = \frac{3}{4}y$

$\Rightarrow \frac{9}{16}y^2 - 15y + y^2 - 10y + 100 = 0$

$\Rightarrow \frac{25}{16}y^2 - 25y + 100 = 0$

$\Rightarrow y^2 - 16y + 64 = 0$

$\Rightarrow (y - 8)^2 = 0$

$\Rightarrow y = 8$.

Now we can use $x = \frac{3}{4}y$ to find that $x = 6$.

This has a single solution, as expected, and so the line is a tangent to the circle.

Similarly for the second circle:

$x^2 - 40x + y^2 - 20y + 400 = 0$ and $x = \frac{3}{4}y$

$\Rightarrow \frac{9}{16}y^2 - 30y + y^2 - 20y + 400 = 0$

$\Rightarrow \frac{25}{16}y^2 - 50y + 400 = 0$

$\Rightarrow y^2 - 32y + 196 = 0$

$\Rightarrow (y - 16)^2 = 0$

$\Rightarrow y = 16$.

Again we can use $x = \frac{3}{4}y$ to find the corresponding value of $x$; this time $x = 12$.

So the line is also a tangent to this circle, and hence it is a common tangent to both of them.


##Method 2

The tangent line is $3y = 4x$, that is $y = \frac{4}{3}x$. The radius that passes through the intersection point will be perpendicular to this, so will have gradient $\frac{-3}{4}$. So the general equation of the line will be $y = \frac{-3}{4}x + c$.

The centre of the first circle lies on the line, so substituting $(10,5)$ into the general equation gives
$$5 = \frac{-3}{4} \times 10 = c$$
$$\Rightarrow c = \frac{25}{2}.$$
So the radial line has equation $$y = \frac{-3}{4}x + \frac{25}{2}.$$

Then the point at which the radial line and the tangent intersect satisfies

$3y = 4x$ and $y = \frac{-3}{4}x + \frac{25}{2}$

$\Rightarrow \frac{-9}{4}x + \frac{75}{2} = 4x$

$\Rightarrow -9x + 150 = 16x$

$\Rightarrow 25x = 150$

$\Rightarrow x = 6$, $y = 8$

This is indeed a point on the circle: $(6 - 10)^2 + (8 - 5)^2 = 4^2 + 3^2 = 25$. Hence the line $3y = 4x$ intersects the radial line at a point on the circle, and so is a tangent line.

Using the same method for the second circle, we find that the intersection point is $(12,16)$ and so the line is also a tangent to this circle.
