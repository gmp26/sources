````
alias: Solution
````
<div class="chalk">
For the circles to touch, we must show that they intersect at only one point.
</div>

We have the equations of the two circles:  
$$x^2 + y^2 = 25 \qquad (1)$$  
and  
$$x^2 + y^2 - 24x - 18y + 125 = 0. \qquad (2)$$  

Substituting equation (1) into equation (2) gives  
$$25 - 24x - 18y + 125 = 0$$ 
$$\Rightarrow 24x + 18y = 150$$
$$\Rightarrow 4x + 3y = 25.$$  

<div class="chalk">
We have shown that if $(x,y)$ lies on both circles then it also lies on the line $4x + 3y = 25$.  Since $4x + 3y = 25$ is a straight line, there are infinitely many points $(x,y)$ that satisfy this equation. We need to show that there is only one point on this line that also lies on the two circles.
</div>

Rearrange $4x + 3y = 25$ to get  
$$x = \frac{1}{4}(25-3y)$$  
and substitute into equation (1):  
$$\left(\frac{1}{4}(25-3y)\right)^2 +y^2 = 25$$ 
$$\Rightarrow 25y^2 - 150y + 225 = 0$$
$$\Rightarrow y^2 - 6y + 9 = 0$$
$$\Rightarrow (y-3)^2 = 0$$
$$\Rightarrow y = 3.$$  

<div class="chalk">
The quadratic equation has a repeated root, so only has one solution. This means that the line $4x + 3y = 25$ and the circle $x^2 + y^2 = 25$ only touch at one point.  That is, there is only one point that lies on both the line $4x + 3y = 25$ and the circle $x^2 + y^2 = 25$.
</div>

We can find the corresponding $x$ value by setting $y = 3$ in the equation $4x + 3y = 25$:  
$$4x + 3(3) = 25$$
$$\Rightarrow x = 4.$$  

We can check that the point $(4,3)$ lies on the circle $x^2 + y^2 - 24x - 18y + 125 = 0$:  we have 
$$4^2 + 3^2 - 24(4) - 18(3) + 125 = 0.$$  

So the circles $x^2 + y^2 = 25$ and $x^2 + y^2 - 24x - 18y + 125 = 0$ touch only at the point $(4,3)$.
