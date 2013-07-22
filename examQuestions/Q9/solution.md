````
alias: Solution
````

We can find the expression for $p$ by calculating the equation of the line $SV$.

If the equation of the line $SV$ is $y = ax + c$, then at the points $(s,ms)$ and $(v,nv)$ we have

$ms = as + c$ and $nv = av + c$

$$\Rightarrow ms - nv = a(s - v)$$

$$\Rightarrow a = \frac{ms - nv}{s - v}.$$

<div class="chalk">
Another way of obtaining this would be to think about the gradient of the line (which is what $a$ represents) as "the change in $y$ over the change in $x$".  So we have
$$a = \frac{nv - ms}{v - s}.$$
</div>

The equation of the line $SV$ is now

$$y = \frac{ms - nv}{s - v}x + c.$$

Since we know that this goes through $S$, we have

$$ms = \frac{ms - nv}{s - v}s + c$$

$$\iff c = ms - \frac{ms - nv}{s - v}s.$$

So the equation of the line $SV$ is

$$y - ms = \frac{ms - nv}{s - v}(x - s).$$

This meets the line $y = 0$ at the point $(p,0)$, so we know that $p$ satisfies

$$-ms = \frac{ms - nv}{s - v}(p - s).$$

Then rearranging gives the required result for $p$: we have
$$p - s = \frac{ms(v-s)}{ms - nv}$$
$$\iff p = \frac{s(ms - nv) + ms(v-s)}{ms - nv}$$
$$\iff p = \frac{(m-n)sv}{ms - nv}.$$


Relabelling $p \mapsto q$, $s \mapsto u$ and $v \mapsto t$ gives the equivalent result for $q$:
$$q = \frac{(m - n)tu}{mt - nu}.$$

* * *

<div class="chalk span4 pull-right">
Note that we may divide by $1 + m^2$ because it is positive, and so we are certainly not dividing by $0$.
</div>

Since $S$ and $T$ lie on the circle, $s$ and $t$ are solutions of the equation
$$\lambda^2 + (m\lambda - c)^2 = r^2$$
$$\iff (1 + m^2)\lambda^2 - 2mc\lambda + (c^2 - r^2) = 0$$
$$\iff \lambda^2 - \frac{2mc}{1 + m^2}\lambda + \frac{c^2 - r^2}{1 + m^2} = 0.$$

<div class="chalk span4 pull-right">
If the roots of the quadratic equation $x^2 + wx + z = 0$ are $x = \alpha$ and $x = \beta$, then $\alpha + \beta = -w$ and $\alpha \beta = z$.  You can check this for yourself if you haven't met this useful idea before.
</div>

Then considering the sum and the product of the roots, we have that
$$st = \frac{c^2 - r^2}{1 + m^2}$$
and
$$s + t = \frac{2mc}{1 + m^2}.$$

* * *

Similarly, if $U$ and $V$ lie on the circle then by interchanging letters we have 
$$uv = \frac{c^2 - r^2}{1 + n^2}$$
and
$$u + v = \frac{2nc}{1 + n^2}.$$

Now, using our above values we have
$$p + q = \frac{(m - n)sv}{ms - nv} + \frac{(m-n)tu}{mt - nu}$$
$$= \frac{(m - n)}{(ms - nv)(mt - nu)}(stm(u + v) - nuv(s + t))$$
$$= \frac{(m - n)}{(ms - nv)(mt - nu)}\left(m \frac{c^2 - r^2}{m^2 + 1} \frac{2cn}{n^2 + 1} - n \frac{c^2 - r^2}{n^2 + 1} \frac{2cm}{m^2 + 1} \right) = 0.$$
using the sum and product results from above.
