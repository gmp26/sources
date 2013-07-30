````
title: LCM sudoku
layout: resource
source: NRICH
clearance: 3
keywords:
  - least common multiple
resourceType: RT12
stids1:
  - NA3
stids2:
pvids1:
pvids2:

````
<div class="row-fluid">
<iframe src="http://nrich.maths.org/content/id/6311/SudokuNov08v2.swf" style="width:600px; height:450px" class="nrich-embed"></iframe>
</div>

Like a standard sudoku, this sudoku variant has the basic rule that every row, every column and every $3 \times 3$ box in the grid contains the digits $1$ to $9$.  

The first step to solving this puzzle is to find the values of the unknown digits (all indicated by asterisks) in the cells of the $9 \times 9$ grid.  At the bottom and right side of the $9 \times 9$ grid are numbers, each of which is the least common multiple (LCM) of all the starred numbers in the row or column preceding it.  
<div class="chalk">
We define the _least common multiple_ of a set of numbers as the smallest number which is divisible by all of them.  For example, the least common multiple of $3$, $4$ and $8$ is $24$.
</div> 

In total 18 least common multiples are given as clues for solving the puzzle---one for each row and each column of the grid.  

After finding the values of all the unknown digits, the puzzle is solved as a traditional sudoku with the starred numbers as a starting point.
