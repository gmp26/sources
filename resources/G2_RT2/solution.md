````
alias: Solution
````

1. There are many ways of tackling this problem.  Here is just one of those ways.

    We recall that $y=mx+c$ describes a unique straight line. Therefore, any equation involving $x$ and $y$ which can be rearranged into that form describes a straight line.

    a. The equation $4x-2y=6$ can be rearranged to give $y=2x-3$, so it describes a unique straight line.

    b. We note that $y=2$ is of the form $y=mx+c$ with $m=0$ and $c=2$, so it also describes a straight line.

    c. <div class="chalk">
    The idea is that for any two (distinct) points there is always a unique straight line going through both points. Can you see why?
    </div>
    The straight line going through the two points $(1,2)$ and $(0,-1)$ must have $$m = \frac{2-(-1)}{1-0}=3.$$ By substituting $x=0$ and $y=-1$ into $y=3x+c$ we obtain $c=-1$. Hence, the unique straight line passing through $(1,2)$ and $(0,-1)$ has equation $y=3x-1$.
    
    d. The equation $y=4x$ is of the above form and so describes a straight line.

    e. This also describes a straight line and in fact, we obtain the same straight line as in part a because both lines are described by the same equation.

    f. <div class="chalk">
    An alternative way to describe a straight line is using vectors: by specifying a fixed point and a direction vector we are uniquely describing the straight line that passes through the given fixed point in the direction of the vector.
    </div>
    The equation of the straight line described by the point and the direction vector given must have $m=2/1=2$ and $c=-3$. (The latter can be obtained by substituting $x=y=3$ into $y=2x+c$.) Note that $y=2x-3$ is the same equation as in parts a and e.

    g. The original equation can be rearranged to give $y=\frac{1}{7}x$, so this also describes a straight line (passing through the origin).

    h. From part c, recall that for any two distinct points there is a unique straight line passing through both points. Therefore, three points describe a straight line only if the third point lies on the straight line passing through the first two points. The equation of the straight line through $(-1,-4)$ and $(3,7)$ is $y=\frac{11}{4}x - \frac{5}{4}$. However, $x=y=8$ does not satisfy this equation. Thus, the three points do not lie on the same straight line.
    <div class="chalk">
    In fact, the three points given describe three different straight lines: the one through $(-1,-4)$ and $(3,7)$, the one through $(-1,-4)$ and $(8,8)$, and the one through $(3,7)$ and $(8,8)$.
    </div>

    i. This can be rearranged to give $y=3x+16$ and so it also describes a straight line.

    j. We repeat what we did in part h and this time all three points lie on the straight line with equation $y=2x-3$.

    k. <div class="chalk">
    You might argue that $y=x^2+2$ is the equation of a parabola and so it cannot describe a straight line. But are you really convinced by this? Below, we make this idea into a rigorous argument.
    </div>
    The parabola described by $y=x^2+2$ passes through the points $(-1,3)$, $(0,2)$ and $(1,3)$. However, whereas the first and third points lie on the straight line with equation $y=3$ the second one does not. So, the equation $y=x^2+2$ cannot describe a straight line.

    l. The equation $y^2=x^2$ can be rearranged to give $(x-y)(x+y) = 0$, so it describes the two straight lines $y=x$ and $y=-x$.

    m. Rearranging the given equation yields $y=\frac{1}{14}x+\frac{2}{7}$, so it describes a straight line.

    n. The approach is similar to what we did in part k. It is possible to find three points that satisfy $xy = 1$ but do not lie on the same straight line (for example, $(1,1)$, $\left(2,\frac{1}{2}\right)$, $\left(\frac{1}{2},2\right)$), showing that $xy = 1$ is not a straight line.

    o. We note that $y^2-4xy+4x^2=(y-2x)^2$, so the equation given does indeed describe a straight line---the straight line with equation $y=2x$.

2. In question 1, we encountered three different descriptions of a straight line.

    * For any real values $m$ and $c$ the equation $y=mx+c$ describes a straight line. More generally, the equation of any straight line in the $x$-$y$ plane can be rearranged into the form $ax+by=c$.
    <div class="chalk">
    The advantage of the latter form is that it includes straight lines which are parallel to the $y$-axis, e.g. $x=4$.
    </div>

    * A straight line can be described uniquely by specifying two distinct points through which the line passes.

    * Alternatively, it also suffices to specify one point and a direction vector to describe a unique straight line such as in part 1f.

    Of course, there are other ways to describe a unique straight line. For instance, instead of finding the unique straight line passing through two given points, we could instead consider the set of points equidistant to these two points. It turns out that this is again a straight line.

3. <div class="chalk">
In question 1, we rearranged all the equations that described a straight line into the form $y=mx+c$. This now makes it a lot easier to decide which equations describe the same straight line.
</div>
Going back to our results from question 1, we see that parts a, e, f and j all describe the same straight line. We note that these four parts correspond to four different descriptions of the same straight line.

4. Let's consider the first two descriptions mentioned in the solution to question 2.

     If we are given the equation $ax+by=c$ of a straight line then we can easily find two distinct points which lie on this line: just pick two distinct values for $x$ and compute the corresponding $y$-values.

     Conversely, if we are given two arbitrary points $(x_1,y_1)$ and $(x_2,y_2)$ then we can obtain the equation of the straight line going through both points in the following way. If we have $x_1=x_2$ then the straight line is described by the equation $x=x_1$. Otherwise, the gradient of the straight line through both points must be $m=(y_2-y_1)/(x_2-x_1)$ and the value of $c$ can be computed by substituting $x=x_1$ and $y=y_1$ into $y=mx+c$.

5. Which of the above descriptions is more useful than another always depends on the context you are working in.

     For instance, as remarked earlier, one disadvantage of the description $y=mx+c$ is that it does not include straight lines parallel to the $y$-axis. On the other hand, contrary to the description by the equation $ax+by=c$ or by just specifying two points, you can easily read off the gradient and the $y$-intercept of the corresponding straight line from $y=mx+c$.
