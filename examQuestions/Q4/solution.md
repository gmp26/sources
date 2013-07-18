````
alias: Solution
````
<div class="chalk">
For the line to 'touch' the circle there must be exactly one point of intersection between them---the line must be a tangent to the circle. 
</div>

To find the points of intersection of the line and circle we need to solve their equations for $x$ and $y$.

Substituting $y=mx+c$ into $x^2+y^2=25$ gives $$x^2+(mx+c)^2=25$$, which rearranges to $$(1+m^2)x^2+2mcx+c^2-25=0.$$ For this quadratic equation to have exactly one solution for $x$ we need the discriminant to be $0$.

So we must have $$(2mc)^2-4(1+m^2)(c^2-25)=0.$$ Rearranging this gives $$c^2=25(1+m^2).$$

<div class="chalk">
We need to be careful here, we haven't actually finished this part. We have shown that IF the line touches the circle THEN $c^2=25(1+m^2)$ but we want to show the opposite, that IF $c^2=25(1+m^2)$ THEN the line touches the circle. To do this we can use what we have just done and work backwards.
</div>

If $$c^2=25(1+m^2),$$ then the polynomial $(1+m^2)x^2+2mcx+c^2-25=0$ has exactly one solution for $x$ and so there is exactly one value of $x$ which satifies the simultaneous equations $y=mx+c$ and $x^2+y^2=25$. Since $y$ is linear in $x$ there is exactly one value of $y$ for this $x$ and so there is exactly one point of intersection.

<div class="chalk">
We can save lots of algebra by using the first part of the question to solve the next part.
</div>

We want to find straight lines of the form $y=mx+c$ which go through the the point $(2,11)$ and are tangents to the circle.

So $11=2m+c$ and by the first part $c^2=25(1+m^2)$.

Now we have simultaneous equations for $m$ and $c$ which we can solve.

Substituting for $c$ gives $$(11-2m)^2=25(1+m^2)$$ which rearranges to give $$21m^2+44m-96=0$$, which becomes $$(3m-4)(7m+24)=0.

So $m=\frac{4}{3}$ or $m=\frac{-24}{7}$.

If $m=\frac{4}{3}$ then $c=11-2\frac{4}{3}=\frac{25}{3}$, and if
$m=\frac{-24}{7}$ then $c=11-2\frac{(-24)}{7}=\frac{125}{7}$.

So the two tangents are $$y=\frac{4}{3}x+\frac{25}{3}$$ and $$y=\frac{-24}{7}x+\frac{125}{7}.$$
