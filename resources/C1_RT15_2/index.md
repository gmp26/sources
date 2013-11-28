````
title: Why are gradients important in mathematics?
clearance: 0
resourceType: RT15
stids1:
  - C1
stids2:
pvids1:
pvids2:
````

<:= style(chalk) :>
Issues:

* Is this too long?  Should it be broken up into smaller snippets?

* Is the level ok?  Is the tone ok?

* Pictures!
<:= style() :>

Describe this graph:

_[Graph of $y=x^2$]_

You might say something like: "The $y$ value goes to infinity as you go further to the left or right."  You  might say: "It passes through the origin, the point $(0,0)$.""  But I am almost certain that you will say something along the lines of: "It has a minimum value.""

Similarly if you saw this graph:

_[Graph of $y=x(x+1)(x-1)$]_
 
I can be pretty sure that you'd comment that it has a small hill (called a _local maximum_) and a small ditch (called a _local minimum_), as well as heading off to positive and negative infinity.

These maxima and minima are defining features of these graphs.  A graph having a maximum or minimum, whether it dominates the whole graph as in the top example or just a local area, as in the second, tells you a great deal about the overall shape of the graph. _[Not sure what details to put in here as not sure what parts of curve sketching they will have covered?]_  Alternatively, locating these turning points are key if you want to maximise (or minimise) the curve's value.  

A maximum of a function can only occur if the gradient of the curve changes from positive to negative, creating a hilltop in the graph. (The same goes for a minimum, where the gradient changes from negative to positive, creating a ditch in the graph.)  For any smooth graph (that is, it doesn’t have any gaps or spikes), this can only happen by the curve flattening out, and the point where the gradient is precisely zero is where the maximum occurs. _[Not sure if we can mention the intermediate value theorem here]_

_[close up of top of $y=-x^2$ or local maximum in $y=x^3$ showing tangents with decreasing slope, and horizontal tangent at maximum.]_

Even if a point where the gradient is zero isn't a maximum or a minimum, it is always a place where something interesting happens.  For example in this graph

_[graph of $y=x^3$]_

as we move from left to right, the gradient flattens out from positive, to zero at the origin, and then becomes positive again, getting progressively steeper.  The flat point in the curve in this example is called _a point of inflection_.

The other thing a gradient might tell you is where something strange might occur.  For example, consider the graph of tangent function:

_[graph of tangent function]_

There are points of inflection where the graph has a gradient of zero, at $x=0, \pi, -\pi, 2\pi, -2\pi,\dots$ etc.  But really, that is not where the excitement is.  Look at what happens as the graph approaches $x=\pi/2$ from the left.  The gradient gets steeper and steeper, closer and closer to vertically heading up to positive infinity.  While as it approaches $x=\pi/2$ from the right, it gets steeper and steeper, closer to vertically heading down to negative infinity.  This is because the line $x=\pi/2$ is a _vertical asymptote_ for the tangent function -_ the function is defined arbitrarily close to this line but is not defined for  $x$ exactly equal to $\pi/2$.  This is repeated all along the $x$-axis, with asymptotes for $x = \pi/2, -\pi/2, 3\pi/2, -3\pi/2, 5\pi/2, -5\pi/2, \dots$ and so on.

You might get a horizontal asymptote, such as for the graph $y=e^{-x}$, where the gradient of the graph flattens out but never quite become zero as $x$ heads off to infinity.

_[graph of $y=e^{-x}$]_

Or you might have an asymptote with some other gradient.  In this example the gradient of the graph approaches either $+1$ or $-1$, running ever closer to the asymptotes $y=x$ and $y=-x$.

_[graph of $x^2 - y^2 = 1$, with asymptotes $y=x$ and $y=-x$]_

The gradient of a graph is key to understanding the behaviour of the graph, and so the mathematical function it represents.  And these concepts extend far beyond the shapes of one dimensional curves.  We use the gradients to understand the shape of surfaces of any dimensions, to understand the curvature of mathematical spaces and to predict the behaviour of complex mathematical functions.