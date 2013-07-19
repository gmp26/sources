````
alias: Solution
````
<div class="chalk">
For the line to 'touch' the circle there must be exactly one point of intersection between them---the line must be a tangent to the circle. 
</div>

To find the points of intersection of the line and circle we need to solve their equations for $x$ and $y$.

Substituting $y = mx + c$ into $x^2 + y^2 = 25$ gives $$x^2 + (mx+c)^2 = 25$$ $$\iff (1+m^2)x^2 + 2mcx + c^2 - 25 = 0.$$ This is a quadratic equation in $x$ and has discriminant $$(2mc)^2 - 4 (1+m^2) (c^2-25) = 4 (25 (1+m^2) - c^2).$$

If $c^2 = 25(1+m^2)$ then the discriminant is $0$. This tells us that there is exactly one value of $x$ which satisfies this quadratic and hence the simultaneous equations. Since $y = mx + c$ is a linear equation in $x$, this corresponds to exactly one value of $y$. Therefore the line and circle intersect at exactly one point.

* * *

<div class="chalk">
We can save some time by using the first part of the question to solve the next part.
</div>

We want to find straight lines of the form $y=mx+c$ which go through the the point $(2,11)$ and are tangents to the circle.

Substituting the coordinates $(2,11)$ into $y=mx+c$ gives $11 = 2m + c$ and from the first part we must have $c^2 = 25(1+m^2)$.

Now we have simultaneous equations for $m$ and $c$ which we can solve.

Substituting for $c$ gives $$(11-2m)^2 = 25(1+m^2),$$ which rearranges to give $$21m^2 + 44m - 96 = 0 $$ $$\iff (3m-4) (7m+24) = 0 .$$
So $m = \frac{4}{3}$ or $m = - \frac{24}{7}$.

If $m = \frac{4}{3}$, then $c = 11 - 2 \frac{4}{3} = \frac{25}{3}$, and if $m = - \frac{24}{7}$ then $c = 11 - 2 \frac{(-24)}{7} = \frac{125}{7}$.

So the two tangents are $$y= \frac{4}{3} x + \frac{25}{3$$ and $$y= - \frac{24}{7} x + \frac{125}{7}.$$
