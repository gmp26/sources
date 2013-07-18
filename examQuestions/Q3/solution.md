````
alias: Solution
````


<div class="chalk">
The general equation of a circle with radius $r$ and centre $(a,b)$ is $(x-a)^2 + (y-b)^2 = r^2$.
</div>

Substituting $(x,y) = (2,0)$, $(x,y) = (8,0)$ and $(x,y) = (10,4)$ into this equation for a circle, we get three simultaneous equations in $a$, $b$ and $r$:

1. $(2-a)^2 + b^2 = r^2$
2. $(8-a)^2 + b^2 = r^2$
3. $(10-a)^2 + (4-b)^2 = r^2$
  
Taking equation 1 away from equation 2, and expanding, we find the value of $a$:

$$(8-a)^2 - (2-a)^2 = 0$$
$$\iff 64 - 16a + a^2 = 4 - 4a + a^2$$
$$\iff 60 = 12a$$
$$\iff a = 5.$$  


Substituting $a=5$ into equations 2 and 3, we get:  

4. $9 + b^2 = r^2$
5. $25 + (4-b)^2 = r^2$  
  
Taking equation 4 away from equation 5, and expanding, we find the value of $b$:

$$25 + (4-b)^2 - 9 - b^2 = 0$$
$$ \iff 25 + 16 - 8b + b^2 - 9 - b^2 = 0$$
$$ \iff 32 = 8b$$
$$ \iff b = 4.$$

Substituting $b=4$ into equation 4, we get

6. $9 + 16 = r^2$

This is true if and only if $r^2 = 25$, that is, 
$r = 5$.

<div class="chalk">
We know that $r$ must be 5 rather than $-5$ as the radius of a circle must be positive.
</div>

So the equation of this circle is $(x-5)^2 + (y-4)^2 = 25$.  
  
***

The $y$-axis is the line $x=0$.

Substituting $x=0$ into the equation for this circle, we get
$25 + (y-4)^2 = 25 \iff (y-4)^2 = 0$.

This equation has only one solution, $y=4$, so the circle touches the $y$-axis.

<div class="chalk pull-right">
Setting $x=0$ in the equation for the circle gives an equation in $y$. If $y=d$ is a solution to this equation, then the circle intersects the $y$-axis at $(0,d)$. If this equation only has one solution, the $y$-axis meets the circle at exactly one point, and therefore must be a tangent to it.

</div>

***

Any line passing through the origin that is not the $y$-axis must have equation $y=mx$ for some real number $m$. We want to find an $m$ such that $y=mx$ and $(x-5)^2+(y-4)^2=25$ intersect at exactly one point---then $y=mx$ will be a tangent to the circle passing through the origin.  
  

Now $$(x-5)^2 + (mx-4)^2 = 25$$
$$\iff x^2 - 10x + 25 + m^2x^2 - 8mx + 16 = 25$$
$$\iff (m^2 +1)x^2 + (-10 - 8m)x+16 = 0$$.

<div class="chalk pull-right">
Substituting $y=mx$ into $(x-5)^2+(y-4)^2=25$ and expanding, we get a quadratic equation in $x$ with coefficients in $m$.
</div>

For $y=mx$ to be a tangent to the circle, we must have only one root to this quadratic equation---that is, its discriminant must be zero.  
  
Now $$(-10-8m)^2 - 4(m^2+1)(16) = 0$$
$$\iff 100+160m+64m^2-64(m^2+1)=0$$
$$\iff 100+160m+64m^2-64m^2-64=0$$
$$\iff 160m+36=0$$
$$\iff m=\frac{-9}{40}.$$

<div class="chalk pull-right">
The discriminant of a quadratic equation $ax^2+bx+c = 0$ is $b^2-4ac$. It equals zero if, and only if, the equation has a repeated root.
</div>

So $y=\frac{-9}{40}x$ is the equation of this tangent.

