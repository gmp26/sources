````
alias: Solution
````

If the equation of the line $AB$ is $y = mx + c$, then at the point $(0,b)$ we have $b = c$. So $$y = mx + b.$$ Then at $(a,0)$ we have $$0 = ma + b,$$ so $$m = \frac{-b}{a}.$$
<div class="chalk span4 pull-right">
Another way of obtaining this would be to think about the gradient of the line
(which is what $m$ represents) as "the change in $y$ over the change in $x$".
So we have
$$m = \frac{0-b}{a-0} = \frac{-b}{a}.$$
</div>
So the equation of the line AB is $$y = \frac{-b}{a}x + b.$$

This line has gradient $\frac{-b}{a}$, so the line $NP$, which is perpendicular to it, has gradient $\frac{a}{b}$. So $NP$ has equation $$y = \frac{a}{b}x + k$$
for some suitable $k$.  Now $NP$ passes through $P$, which has coordinates $(s,t)$. So $$t = \frac{as}{b} + k$$
$$\iff k = \frac{bt - as}{b}$$
So $NP$ has the equation $$y = \frac{a}{b}x + \frac{bt - as}{b}.$$

Now we know that $AB$ and $NP$ intersect at $N$, so to find the coordinates of $N$ we solve the simultaneous equations
$$y = \frac{-b}{a}x + b$$
and
$$y = \frac{a}{b}x + \frac{bt - as}{b}.$$

If we set them equal to each other we have
$$\frac{-b}{a}x + b = \frac{a}{b}x + \frac{bt - as}{b}$$
$$\iff b - \frac{bt - as}{b} = (\frac{a}{b} + \frac{b}{a})x$$
$$\iff b - \frac{bt - as}{b} = \frac{a^2 + b^2}{ab}x$$
$$\iff ab^2 - a(bt - as) = (a^2 + b^2)x$$

$$\iff x = \frac{ab^2 - a(bt - as)}{a^2 + b^2}.$$

Now we substitute this back into the equation for $AB$ to get the $y$-coordinate:
$$y = \frac{\frac{-b}{a}(ab^2 - a(bt - as))}{a^2 + b^2} + b$$
$$= \frac{-b^3 + b(bt - as) +a^2b + b^3}{a^2 + b^2}$$
$$= \frac{a^2b + b(bt - as)}{a^2 + b^2}$$
as required.

***

We now assume that 
$$\left(\frac{t - b}{s}\right)\left(\frac{t}{s - a}\right) = -1.$$

Note that this means that $s \neq 0$.

The points $X$ and $Y$ have coordinates $(s,0)$ and $(0,t)$ respectively, so by relabelling of the equation of $AB$ we have that the equation of the line $XY$ is
$$y = \frac{-t}{s}x + t.$$

Now $N$ lies on this line exactly when
$$\frac{a^2b + b(bt - as)}{a^2 + b^2} = -\frac{t}{s}\frac{ab^2 - a(bt - as)}{a^2 + b^2} + t$$
$$\iff a^2bs + bs(bt - as) = - ab^2t + at(bt - as) + st(a^2 + b^2)$$
$$\iff a^2bs + b^2st -abs^2 + ab^2t -abt^2 + a^2st = st(a^2 + b^2)$$
$$\iff a^2bs -abs^2 + ab^2t -abt^2 = 0$$
<div class="chalk span4 pull-right">
Here we can divide both sides by $a$ and $b$ since they are both positive---no danger of dividing by zero!
</div>
$$\iff as - s^2 + bt - t^2 = 0$$
$$\iff t^2 - bt = -(s^2 - as)$$
$$\iff t(t-b) = -s(s - a)$$
$$\iff \frac{t(t - b)}{s(s - a)} = -1$$
$$\iff \left(\frac{t - b}{s}\right)\left(\frac{t}{s - a}\right) = -1.$$

So, in particular, if

$$\left(\frac{t - b}{s}\right)\left(\frac{t}{s - a}\right) = -1$$

then $N$ lies on the line $XY$.

***

A geometrical interpretation of this result is that $\frac{t - b}{s}$ and $\frac{t}{s - a}$ are the gradients of $BP$ and $AP$ respectively. So if $BP$ and $AP$ are perpendicular, then $N$ lies on $XY$.
