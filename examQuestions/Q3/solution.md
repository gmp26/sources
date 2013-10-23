````
alias: Solution
````


<:= style(chalk) :>
We can think about solving the first part of this problem in two ways. The first involves thinking about the algebraic equation of a circle.
<:= style() :>

###Method 1

The general equation of a circle with radius $r$ and centre $(a,b)$ is $(x-a)^2 + (y-b)^2 = r^2$.

Substituting $(x,y) = (2,0)$, $(x,y) = (8,0)$ and $(x,y) = (10,4)$ into this equation for a circle, we get three simultaneous equations in $a$, $b$ and $r$:

$$(2-a)^2 + b^2 = r^2$$

and

$$(8-a)^2 + b^2 = r^2$$

and

$$(10-a)^2 + (4-b)^2 = r^2.$$
  
Taking the first equation away from the second, and expanding, we find the value of a:

$$(8-a)^2 - (2-a)^2 = 0 \iff 64 - 16a + a^2 = 4 - 4a + a^2 \iff 60 = 12a \iff a = 5.$$

Substituting $a=5$ into the second and third equations, we get

$$9 + b^2 = r^2$$ and $$25 + (4-b)^2 = r^2.$$
  
Taking the first equation away from the second, and expanding, we find the value of $b$:

$$25 + (4-b)^2 - 9 - b^2 = 0 \iff 25 + 16 - 8b + b^2 - 9 - b^2 = 0 \iff 32 = 8b \iff b = 4.$$

Now, substituting $b=4$ into the equation $25 + (4-b)^2 = r^2$ from above, we get:

$$25 = r^2$$.

This is true if, and only if, $r = 5$.

<:= style(chalk) :>
We know that $r$ must be 5 rather than $-5$ as the radius of a circle must be positive.
<:= style() :>

So the equation of this circle is $(x-5)^2 + (y-4)^2 = 25$. 

###Method 2
  
<:= style(chalk) :>
The second way of looking at this problem involves thinking about the circle geometrically.
<:= style() :>

Given any three points, we can think of a triangle with these points as its vertices. It is a fact that there is a unique circle passing through these three points, whose centre is the _circumcentre_ of the triangle we just described---that is, the intersection of the perpendicular bisectors of the three sides.

Our three points are $A=(2,0)$, $B=(8,0)$, and $C=(10,4)$. The line segment between $(2,0)$ and $(8,0)$ is part of the $x$-axis, with midpoint $\left(\frac{2+8}{2},\frac{0+0}{2}\right)=(5,0)$. So the perpendicular bisector of the side $AB$ is the line $x=5$.

The line segment between $(8,0)$ and $(10,4)$ has gradient $\frac{4}{2}=2$ and midpoint $\left(\frac{8+10}{2},\frac{0+4}{2}\right)=(9,2)$. So the perpendicular bisector of side $BC$ is the line with gradient $\frac{-1}{2}$ and passing through the point $(9,2)$.  Substituting this information into the general equation for a line $y=mx+c$, we find that the perpendicular bisector of side BC is the line $y=\frac{-1}{2}x+\frac{13}{2}$.

<:= style(chalk) :>
We could also calculate the perpendicular bisector of side $CA$, which turns out to be the line $y=-2x+14$.

But we don't need to do this, because we are using the standard fact that the three perpendicular bisectors of the sides of a triangle meet at a single point.  You could check that this is true in this specific case if you wanted.
<:= style() :>

Substituting $x=5$ into $y=\frac{-1}{2}x + \frac{13}{2}$, we get the equation $y=-\frac{5}{2}+\frac{13}{2}$ which is true if and only if $y=4$. So these two perpendicular bisectors intersect at the point $(5,4)$, making this the centre of the circle.

Now, it is easy to find the radius of the circle---simply find the distance between the centre and one of the points given.

The distance between $A=(2,0)$ and $(5,4)$ is $\sqrt{(2-5)^2+(0-4)^2}=\sqrt{25}=5$.

So the circle passing through these three points has centre $(5,4)$ and radius $5$. This means that it has equation
$$(x-5)^2 + (y-4)^2 = 25.$$




***

On the $y$-axis, we know that $x=0$.

Substituting $x=0$ into the equation for this circle, we get:
$25 + (y-4)^2 = 25 \iff (y-4)^2 = 0$.

This equation has only one solution, $y=4$, so the circle touches the $y$-axis.

<:= style(chalk) :>
Setting $x=0$ in the equation for the circle gives an equation in $y$. If $y=d$ is a solution to this equation, then the circle intersects the $y$-axis at $(0,d)$. If this equation only has one solution, then the circle meets the $y$-axis at only one point, and therefore the $y$-axis must be a tangent to the circle.
<:= style() :>

***

Any line passing through the origin that is not the $y$-axis must have equation $y=mx$ for some real number $m$. We want to find an $m$ such that $y=mx$ and $(x-5)^2+(y-4)^2=25$ intersect at exactly one point---then $y=mx$ will be a tangent to the circle passing through the origin.
  
Substituting $y=mx$ into $(x-5)^2+(y-4)^2=25$ and expanding, we get a quadratic equation in $x$ with coefficients in $m$:

$$(x-5)^2 + (mx-4)^2 = 25$$

$$\iff x^2 - 10x + 25 + m^2x^2 - 8mx + 16 = 25$$

$$\iff (m^2 +1)x^2 + (-10 - 8m)x+16 = 0.$$

For $y=mx$ to be a tangent to the circle, we must have only one root to this quadratic equation---that is, its discriminant must be zero.

<:= style(chalk) :>
The discriminant of a quadratic equation $ax^2+bx+c = 0$ is $b^2-4ac$. The discriminant equals zero if, and only if, the equation has a repeated root.
<:= style() :>

Now
  
$$(-10-8m)^2 - 4(m^2+1)(16) = 0$$

$$\iff 100+160m+64m^2-64(m^2+1)=0$$

$$\iff 100+160m+64m^2-64m^2-64=0$$

$$\iff 160m+36=0$$

$$\iff m=\frac{-9}{40}.$$

So $y=\frac{-9}{40}x$ is the equation of this tangent.

