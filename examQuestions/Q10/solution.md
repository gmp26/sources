````
alias: Solution
````

The result for $p$ can be found by calculating the equation of the line $SV$:

If the general equation of the line $SV$ is $y = ax + c$, then at the points $(s,ms)$ and $(v,nv)$ we have

$ms = as + c$ and $nv = av + c$

$\Rightarrow ms - nv = a(s - v)$

$\Rightarrow a = \frac{ms - nv}{s - v}$

$\Rightarrow y = \frac{ms - nv}{s - v}x + c$

$\Rightarrow ms = \frac{ms - nv}{s - v}s + c$

$\Rightarrow c = ms - \frac{ms - nv}{s - v}s$

$\Rightarrow y - ms = \frac{ms - nv}{s - v}(x - s)$

$\Rightarrow - ms = \frac{ms - nv}{s - v}(p - s)$.

Then rearranging gives the required result for $p$, and relabelling $p \rightarrow q$, $s \rightarrow u$ and $v \rightarrow t$ gives the equivalent result for q:
$$q = \frac{(m - n)ut}{mt - nu}.$$

As $S$ and $T$ lie on the circle, $s$ and $t$ are solutions of the equation
$$\lambda^2 + (m\lambda - c)^2 = r^2$$
$$\Rightarrow (1 + m^2)\lambda^2 - 2mc\lambda + (c^2 - r^2) = 0.$$
$$\Rightarrow \lambda^2 - \frac{2mc}{1 + m^2}\lambda + \frac{c^2 - r^2}{1 + m^2} = 0$$

Then considering the sum and the product of the roots, we have that
$st = \frac{c^2 - r^2}{1 + m^2}$, and $s + t = \frac{2mc}{1 + m^2}$.

<div class="chalk pull-right">
Here we use that a quadratic $ax^2 + bx + c = 0$ with roots $p$ and $q$ can be written as $0 = (x - p)(x - q) = x^2 -(p + q)x + pq$, so $pq = c$ and $p + q = -b$.
</div>

Similarly, by interchanging letters we have $uv = \frac{c^2 - r^2}{1 + n^2}$ and $u + v = \frac{2nc}{1 + n^2}$.

Now, using our above values we have
$$p + q = \frac{(m - n)sv}{ms - nv} + \frac{(m-n)tu}{mt - nu}$$
$$= \frac{(m - n)}{(ms - nv)(mt - nu)}(stm(u + v) - nuv(s + t)).$$

Finally, substituting the sum and product results gives the result.