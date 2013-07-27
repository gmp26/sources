````
alias: Solution
````
NEEDS CHECKING

Let  
$$f(x) = ax^3 - 6ax^2 + (12a + 12)x - (8a + 16)$$  
and  
$$g(x) = x^3.$$

To show that the curves $(\ast)$ and $(\ast\ast)$ **touch** at $(2,8)$, we need to show that both curves pass through $(2,8)$ and that the gradients of both curves are equal at this point.

Now  
$$f(2) = 8a - 24a + 2(12a + 12) - (8a + 16) = 8$$  
and  
$$g(2) = 8,$$  
so both curves pass through the point $(2,8)$.

Also  
$$f'(2) = 12a - 24a + (12a + 12) = 12$$  
and  
$$g'(2) = 12,$$  
so the curves have the same gradient at the point $(2,8)$.

Therefore the curves $(\ast)$ and $(\ast\ast)$ touch at $(2,8)$.

To find the other point of intersection, we set $f(x) = g(x)$ to get  
$$ax^3 - 6ax^2 + (12a + 12)x - (8a + 16) = x^3.$$
$$\implies (a - 1)x^3 - 6ax^2 + (12a + 12)x - (8a + 16) = 0$$ 
$$\implies (x - 2)[(a - 1)x^2 - (4a + 2)x + (4a + 8)] = 0$$
$$\implies (x - 2)^2[(a - 1)x - (2a + 4)] = 0$$  

So the other point of intersection has coordinates $(\frac{2a+4}{a-1},(\frac{2a+4}{a-1})^3)$.

We now need to sketch the graphs for different values of $a$.

(i) When $a = 2$, we have  
$$y = 2x^3 - 12x^2 + 36x - 32.$$  
From above, we have that the two graphs intersect at $(8,512)$ and touch at $(2,8)$.
Now differentiating gives  
$$\frac{dy}{dx} = 6x^2 - 24x + 36,$$  
so stationary points occur when  
$$6x^2 - 24x + 36 = 0.$$
$$\implies x^2 - 4x + 6 = 0$$
$$\implies (x - 2)^2 = -2$$  
This equation has no real solutions, so there are no stationary points when $a = 2$.  

	We also know that $(\ast)$ with $a = 2$ intersects the $y$ axis at $(0,-32)$.
	So when $a = 2$, the graphs have the following shape.  
	
![Figure1](figure1.png)

(ii) When $a = 1$, we have  
$$y = x^3 - 6x^2 + 24x - 24.$$  
The two graphs touch at $(2,8)$ but do not intersect because $\frac{2a+4}{a-1}$ is undefined when $a = 1$.  

	Differentiating gives  
$$\frac{dy}{dx} = 3x^2 - 12x + 24,$$  
so stationary points occur when  
$$3x^2 - 12x + 24 =0.$$
$$\implies x^2 - 4x + 8 = 0$$
$$\implies (x - 2)^2 = -4$$  
This equation has no real solutions, so there are no stationary points when $a = 1$.

	We also know that $(\ast)$ with $a = 1$ intersects the $y$ axis at $(0,-24)$. 
	So when $a=1$, the graphs have the following shape.  
	
![Figure 2](figure2.png)

(iii) When $a = -2$, we have  
$$y = -2x^3 + 12x^2 - 12x.$$  
The two graphs intersect at $(0,0)$ and touch at $(2,8)$. 
Differentiating gives  
$$\frac{dy}{dx} = -6x^2 + 24x - 12,$$  
so stationary points occur when  
$$-6x^2 + 24x - 12 = 0.$$
$$\implies x^2 - 4x + 2 = 0$$
$$\implies x = 2 \pm \sqrt{2}$$

	So there are stationary points at $x \approx 3.4$ and $x \approx 0.6$.

	So when $a=-2$, the graphs have the following shape.  

![Figure 3](figure3.png)
