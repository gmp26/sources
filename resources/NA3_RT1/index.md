````
layout: resource
clearance: 3
title: Picture this!
keywords:
  - Euclid's algorithm
  - highest common factor
resourceType: RT1
stids1:
  - NA3
stids2:
pvids1:
pvids2:
  - PI3
  - PI4
  - PI5

````

In this interactivity, you can specify two positive integers (whole numbers) and the computer will draw a corresponding diagram.

<:= style(well) :>
Experiment with a few examples, and then consider the questions that follow.
<:= style() :>

<: var animation = "animation/index.html" :>
<:= buttonLink(primary, "Full Screen Version", animation) :>

<:= iframe("See " + animation, animation, 300, 300) :>

<!--
<iframe src="animation/index.html" class="nrich-embed" style="width:300px;height:300px"></iframe>

_Interactivity reproduced from [Picture This!](http://nrich.maths.org/psum/picture-this/).  This will be tweaked to have a full screen version (in such a way that the numbers are still visible when displayed full screen).  We might also lose the option of a non-spiral version._

...done, though thumbnail version on first screen can be cropped with some
numbers, so full screen is preferable. -- gmp26
-->

<:= style(well) :>

* Given two positive integers, can you draw the corresponding diagram?
* Given a diagram, can you determine the corresponding pair of positive integers?

<:= style() :>


You should now have a good understanding of the relationship between the diagram and the pair of positive integers.  There are many questions that you might now ask yourself.

<:= style(well) :>
Investigate the questions that interest you.  You might want to make some conjectures and then try to prove (justify) them or to disprove them by finding counterexamples.
<:= style() :>


Then you can look at our list of questions below.

<:= toggle(1, "Question 1") :>
<:= collapsed(1) :>
What is the relationship between the side length of the smallest square in the diagram and the pair of positive integers?
<:= collapsed() :>

<:= toggle(2, "Question 2") :>
<:= collapsed(2) :>
How many steps (different colours) can we have?  Which pairs of integers give many steps and which give few?
<:= collapsed() :>

<:= toggle(3, "Question 3") :>
<:= collapsed(3) :>
How can we record the information from the diagram in the form of equations?

When might the diagram be more convenient?  When might the equations be more convenient?
<:= collapsed() :>

<:= toggle(4, "Question 4") :>
<:= collapsed(4) :>
What is the point of the process captured by this diagram?  What is it useful for?  When might it be more or less useful than our existing techniques?
<:= collapsed() :>
