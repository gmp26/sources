````
alias: Solution
````
<div class="chalk">
We need to find the line through $(h,k)$ that is perpendicular to the original line. We can then find the point where the two lines cross. The distance from this point to $(h,k)$ is the perpendicular distance. See Figure 1.
![Figure 1](Q15solutionfigure1.png)
</div>

If $\sin\alpha=0$, then $\cos\alpha=\pm1$ so the equation of the line is $x=\frac{p}{\cos\alpha}=p\cos\alpha$. Then the perpendicular distance is $$|h-p\cos\alpha|=|h\cos^2\alpha-p\cos\alpha +k\sin\alpha\cos\alpha|$$ $$=|\cos\alpha(h\cos\alpha-p +k\sin\alpha)|$$ $$=|h\cos\alpha-p +k\sin\alpha|$$ as required.

If $\cos\alpha = 0$, then $\sin\alpha = \pm 1$ so the equation of the line is $y = p \sin \alpha$.  Then the perpendicular distance is
$$|k - p \sin \alpha| = |k\sin^2 \alpha - p \sin \alpha + h \sin \alpha \cos \alpha|$$
$$= |\sin\alpha (h \cos\alpha - p + k \sin\alpha)|$$
$$= |h \cos\alpha - p + k \sin\alpha|$$
as required.

So now assume $\sin\alpha\not=0$ and $\cos\alpha \noteq 0$..

Rearranging the equation of the line into the form $y=mx+c$ gives $$y=-\frac{\cos\alpha}{\sin\alpha}x+\frac{p}{\sin\alpha}.$$

Lines perpendicular to this have gradient $\frac{\sin\alpha}{\cos\alpha}$ and we want to choose the line which goes through the point $(h,k)$. So we have the line $y=\frac{\sin\alpha}{\cos\alpha}x+c_1$ and by putting in the coordinates $(h,k)$ we get $c_1=k-\frac{\sin\alpha}{\cos\alpha}h$. Therefore the perpendicular line passing through $(h,k)$ is $$y=\frac{\sin\alpha}{\cos\alpha}x+\left(k-\frac{\sin\alpha}{\cos\alpha}h\right).$$

To find the point at which the two lines intersect, we equate our two expressions for $y$ to obtain $$-\frac{\cos\alpha}{\sin\alpha}x+\frac{p}{\sin\alpha}=\frac{\sin\alpha}{\cos\alpha}x + \left(k-\frac{\sin\alpha}{\cos\alpha}h\right)$$
and rearranging this gives 
$$\left(\frac{\sin\alpha}{\cos\alpha}+\frac{\cos\alpha}{\sin\alpha}\right)x=\frac{p}{\sin\alpha}-k+\frac{\sin\alpha}{\cos\alpha}h$$ 
$$\iff \frac{x}{\sin\alpha\cos\alpha}=\frac{p}{\sin\alpha}-k+\frac{\sin\alpha}{\cos\alpha}h$$
$$\iff x=p\cos\alpha-k\cos\alpha\sin\alpha+h\sin^2\alpha.$$

Substituting this value into either of the equations gives us the $y$ coordinate $$y=-\frac{\cos\alpha}{\sin\alpha}p\cos\alpha-k\cos\alpha\sin\alpha+h\sin^2\alpha+\frac{p}{\sin\alpha}$$ $$=-p\frac{\cos^2\alpha}{\sin\alpha}+k\cos^2\alpha-h\sin\alpha\cos\alpha+\frac{p}
{\sin\alpha}$$ $$=p\sin\alpha+k\cos^2\alpha-h\sin\alpha\cos\alpha.$$

The distance between two points $(x_1,y_1)$ and $(x_2,y_2)$ is $\sqrt{(x_2-x_1)^2+(y_2-y_1)^2}$, so the perpendicular distance $d$ between the two points $(h,k)$ and $(p \cos \alpha - k \cos \alpha \sin \alpha + h \sin^2 \alpha, p \sin \alpha + k \cos^2 \alpha - h \sin \alpha \cos \alpha)$ is $$d=\sqrt{(p\cos\alpha-k\cos\alpha\sin\alpha+h\sin^2\alpha-h)^2+(p\sin\alpha+k\cos^2\alpha-h\sin\alpha\cos\alpha-k)^2}$$
$$\iff d=\sqrt{(p\cos\alpha-k\cos\alpha\sin\alpha-h\cos^2\alpha)^2+(p\sin\alpha-k\sin^2\alpha-h\sin\alpha\cos\alpha)^2}$$
$$\iff d=\sqrt{\cos^2\alpha(p-k\sin\alpha-h\cos\alpha)^2+\sin^2\alpha(p-k\sin\alpha-h\cos\alpha)^2}$$ 
$$\iff d=\sqrt{(\cos^2+\sin^2\alpha)(p-k\sin\alpha-h\cos\alpha)^2}$$
$$\iff d=|p-k\sin\alpha-h\cos\alpha|.$$

So the perpendicular distance is the numerical value of $(h\cos\alpha+k\sin\alpha-p)$.

* * *

For the second part we need to find the points that are a distance of $5$ away from $(4,4)$ and have perpendicular distance $5$ from the line $3x-4y-28=0$.

We can use the formula for distance that we have just found. The line we have been given is not quite in the form we require since $3$ and $-4$ cannot be the values of $\cos\alpha$ or $\sin\alpha$ whatever the value of $\alpha$. We can scale the whole equation by a real number $k$: we multiply through to get $$3kx-4ky-28k = 0$$ and solve $$3k=\cos\alpha$$ and $$-4k=\sin\alpha$$ for $k$.

Since $\sin^2\alpha+\cos^2\alpha=1$ we see that $9k^2+16k^2=1$, so $k=\pm\frac{1}{5}$. Then we can write the line equivalently as $$\frac{3}{5}x-\frac{4}{5}y-\frac{28}{5}=0,$$ so $\cos\alpha=\frac{3}{5}$, $\sin\alpha=-\frac{4}{5}$ and $p=\frac{28}{5}$.

Let $(h,k)$ be the coordinates we are trying to find (we'll find two possible options for $(h,k)$).

Then, using the expression we found earlier, the perpendicular distance between $(h,k)$ and the given line is $$\left|\frac{3}{5}h-\frac{4}{5}k-\frac{28}{5}\right|.$$
Since the distance between $(h,k)$ and $(4,4)$ is $5$ we can see that $-1\leq h$ ,$k\leq9$.

Therefore $$-\frac{67}{5} \leq\frac{3}{5}h-\frac{4}{5}k-\frac{28}{5}\leq \frac{3}{5} $$

Since we want the numerical value of $(\frac{3}{5}h-\frac{4}{5}k-\frac{28}{5})$ to be $5$ and the interval $[-\frac{67}{5},\frac{3}{5}]$ includes $-5$ but not $5$, we must find $h$ and $k$ so that $$\frac{3}{5}h-\frac{4}{5}k-\frac{28}{5}=-5.$$

So $h=1+\frac{4}{3}k$.

Since the distance between $(h,k)$ and $(4,4)$ is $5$ we also know that $5=\sqrt{(h-4)^2+(k-4)^2}$ and substituting for $h$ we obtain $5=\sqrt{(\frac{4}{3}k-3)^2+(k-4)^2}$ which can be rearranged to give the quadratic $$25k^2-144k=0.$$

So $k=0$ or $k=\frac{144}{25}$.

Using $h=1+\frac{4}{3}k$ to find $h$ from $k$ gives us the two points $(1,0)$ and $\left(\frac{217}{25},\frac{144}{25}\right)$.
