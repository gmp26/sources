````
alias: Solution
````
The equation of a circle with centre $(a,b)$ and radius $r$ is $$(x-a)^2+(y-b)^2=r^2.$$ By completing the square, $$x^2+y^2+2gx+2fy+c=(x+g)^2-g^2+(y-f)^2-f^2+c$$ so the equation can be written as $$(x+g)^2+(y-f)^2=g^2+f^2+c$$ which is the equation of a circle with centre $(-g,-f)$ and radius $\sqrt{g^2+f^2-c}$.

<div class="chalk">
To begin the next part of the question we can use what we have already done to quickly put the next two equations into the normal form for a circle.
</div>

Call the first circle $A$ and the second circle $B$.

Circle $A$:
Using the form of the first part, $g=-10$,  $f=-8$,  $c=128$.
So $A$ is a circle with centre $(10,8)$ and radius $\sqrt{(-10)^2+(-8)^2-128}=\sqrt{36}=6$.

Circle $B$:
Divide the equation by $4$ to give $$x^2+y^2+4x-6y-\frac{29}{4}=0$$ which is of the same form as the first part.
Then $g=2$,  $f=-3$,  $c=-\frac{29}{4}$, so this is a circle with centre $(-2,3)$ and radius $\sqrt{2^2+(-3)^2+\frac{29}{4}}=\sqrt{\frac{81}{4}}=\frac{9}{2}$.

Because the $x$-coordinate of the centre of circle $A$ is $10$ and the radius is $6$, all points on the circle have $x$-coordinates in the range $4\leq x\leq16$.

Similarly, all points on circle $B$ have $x$-coordinates in the range $-\frac{13}{2}\leq x\leq\frac{5}{2}$.

But $\frac{5}{2} \leq 4$, so the two ranges of $x$ do not overlap, therefore the two circles lie entirely outside each other.


<div class="chalk pull-right">

The points with the shortest distance are the points lying on the line joining the two centres.

</div>
To find the length of the shortest distance between the two circles consider the diagram below.
![Figure 1](solutionfigure.png)

By Pythagoras' Theorem, the hypotenuse of the triangle is $\sqrt{12^2+5^2}=\sqrt{169}=13$.

Therefore the shortest distance between two points is $13-(6+\frac{9}{2})=\frac{5}{2}$.
