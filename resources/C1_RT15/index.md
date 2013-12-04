````
title: Why are gradients important in the real world?
layout: resource
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

If you've ever had to walk up a steep hill, or been faced with descent down a slippery ski slope, then you know that gradients are important.  Suppose you are faced with a choice of walking up one of these two hills:

_[Pics of two hills, one with side $y=0.5x$ and one with $y=2x$.  Can't decide if they should be same length or same height when making a choice....]_

It's pretty clear which one most of us would choose.  We can tell just by looking that the hill on the right is much steeper than the hill on the left, and we all know from bitter experience that each step up its slope will be much harder work.  

The gradient of a line or, more generally, a curve plotted on an $xy$-axes tells us how the change in the $y$-value of the curve depends on the $x$-value.    Suppose I give you a graph of how the distance I've travelled varies with time:

_[Graph of $y=x$]_

The gradient of slope of a straight line is simply the ratio of its rise over run.  But the rise of this line is the distance travelled and the run is how much time has passed, so

$$\frac{rise}{run} = \frac{distance}{time}$$

which we all know is just my velocity. The gradient of a graph of distance versus time gives us the velocity.

Let's look at a slightly more interesting example and consider the graph of how the height of a ball you've thrown straight up in the air changes with time:

_[Graph of something like $y=10x-(9.8/2)x^2$]_

We can see that the gradient of this curve, a parabola, changes over time.  This represents how the velocity of our ball changes over time: it travels fastest (steepest positive gradient, sloping up from left to right) when it first leaves your hand, gradually slows down to almost a standstill at its highest point (a gradient of zero where it flattens out) and then speeds up as it falls back to Earth (reaching its the steepest negative gradient just as you catch it again, sloping down from left to right).

So we can plot how the velocity changes with time:

_[graph of $y=10-9.8x$]_

And the gradient of this straight line is:

$$\frac{rise}{run} = \frac{velocity}{time}$$

which we know is the acceleration.  So the gradient of the graph of velocity versus time gives us the acceleration, in this case, the acceleration due to gravity.

The gradient of any line or curve tells us the rate of change of one variable with another.  This is a vital concept in all mathematical sciences.  As well as the rate of change of distance with time (velocity), there is the rate of change of energy with time (aka power), the rate of change of chemical concentrations with time (the rate of the reaction), and the rate of change of debt owed with time (compound interest).  Any system that changes will be described using rates of change that can be visualised as gradients of mathematical functions.