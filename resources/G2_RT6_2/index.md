````
layout: resource
clearance: 3
alias: Problem
weight: 1
title: Finding circles
keywords:
resourceType: RT6
stids1:
  - G2
  - E2
stids2:
pvids1:
pvids2:
  - PI1

````
If we specify two (distinct) points, is there necessarily a unique circle that passes through them?

What if we specify three (distinct) points?

Or four?  Or ...?

For the rest of the question, we'll say that $N$ is the number of points that specifies a unique circle (hopefully you now know what $N$ is).

* * *

Pick $N$ points.  Can you find the equation of the unique circle that passes through them?  How many ways can you find to do this?

When you have found your own way(s), you might like to consider some of ours.  We've just given some starting points.  Can you complete each of the following?  Which way(s) do you prefer, and why?  Will they always work?

<button type="button" class="btn btn-action" data-toggle="collapse" data-target="#A">
Approach A
</button>

<div id="A" class="collapse">
We want to find an equation of the form $(x - a)^2 + (y - b)^2 = r^2$, where $(a,b)$ is the (unknown) centre of the circle and $r$ is the (unknown) radius.  We have some points that lie on the circle, so we can use these to get some simultaneous equations...
</div>

<button type="button" class="btn btn-action" data-toggle="collapse" data-target="#B">
Approach B
</button>

<div id="B" class="collapse">
The centre of the circle must be the same distance from all the points.  So it must lie on the perpendicular bisector of each line segment joining two points.  So we could find some perpendicular bisectors and find where they intersect...
</div>

<button type="button" class="btn btn-action" data-toggle="collapse" data-target="#C">
Approach C
</button>

<div id="C" class="collapse">
If we have two non-parallel chords in a circle, then their perpendicular bisectors intersect at the centre of the circle.  Perhaps we can use that...
</div>

<button type="button" class="btn btn-action" data-toggle="collapse" data-target="#D">
Approach D
</button>

<div id="D" class="collapse">
We know that the centre, say $(a,b)$, is at an equal distance from all points.  So we could write down the distances from $(a,b)$ to our known points, and then equate those...
</div> 
