````
layout: resource
clearance: 1
title: Division game
keywords:
  - prime
  - divisibility
resourceType: RT5
stids1:
  - NA3*
stids2:
pvids1:
pvids2:
  - PI3
  - PI4
  - PI12
priors:
  - NA3_RT9

````

Here's a game for two players.

<div class="well">
Player 1: Choose a positive integer that is greater than $1$.  Call it $n$.

Player 2: Choose two positive integers, say $a$ and $b$, in such a way that $n$ divides the product $ab$ (that is, $ab$ is a multiple of $n$).

If $n$ divides $a$ or $n$ divides $b$, then Player 1 wins.

If $n$ divides neither $a$ nor $b$, then Player 2 wins.
</div>

1.  Play this game against a partner a few times, to get a feel for the rules.  You might want to swap so that you each experience being Player 1 and Player 2.  Can you find a winning strategy for Player 1?  Can you find a winning strategy for Player 2?

2.  Why does your strategy work?  Are you __sure__ that it works?  There are some hints below that might help you to structure your proof, but do try to come up with your own ideas before you look below.

    You should be really careful that you use only facts about primes and integers that you can prove for yourself.  Otherwise you run the risk of having a circular argument: you use some fact to prove your conjecture in this question, and then use the result in this question to prove that fact.

<div class="chalk">
Tip: here's some conventional notation that you might find useful while working on this problem.

If $a$ and $b$ are integers, then we might write $a \mid b$ (the symbol in the middle is a vertical line) to mean "$a$ divides $b$".  More formally, that tells us that there is some integer $c$ such that $b = ac$.  If you're reading $a \mid b$ out loud, then you should say "$a$ divides $b$".  

If it is not true that $a$ divides $b$, then we can write $a \not\mid b$ (that is, a vertical line with a little dash through it), and we'd read that as "$a$ does not divide $b$".

Be careful to get the symbols in the right order!  It is true that $3 \mid 12$, but it is definitely not true that $12 \mid 3$ (in fact, $12 \not\mid 3$).

On this page, we've written things out in words rather than using this notation, but you might like to use it in your own working.
</div> 

<button type="button" class="btn btn-action" data-toggle="collapse" data-target="#hint1">
Hint 1
</button>

<div id="hint1" class="collapse">
Before we can prove something, we need to formulate a precise statement of what it is that we are trying to prove.  So what statement are you trying to prove?
</div>

<button type="button" class="btn btn-action" data-toggle="collapse" data-target="#answer1">
Possible answer to hint 1
</button>

<div id="answer1" class="collapse">
Here's one statement that we might try to prove.

If $p$ is prime and $p$ divides $ab$, then $p$ divides $a$ or $p$ divides $b$.

(Note that 'or' in maths is _inclusive_, so you should read the conclusion above as "$p$ divides $a$ or $p$ divides $b$ or both".)

It might be that you have a more refined version of this.
</div>

<button type="button" class="btn btn-action" data-toggle="collapse" data-target="#hint2">
Hint 2
</button>

<div id="hint2" class="collapse">
We are trying to prove a result of the form

If $X$, then $Y$ or $Z$.

Do you have a strategy for proving such a result?  How might you set about it?
</div>

<button type="button" class="btn btn-action" data-toggle="collapse" data-target="#answer2">
Possible answer to hint 2
</button>

<div id="answer2" class="collapse">
Here's one possible approach.

We are allowed to assume statement $X$.

If statement $Y$ is true, then we are done: the result is true.

So we may assume that statement $Y$ is false, and then our job is to show that statement $Z$ is true.

In our case, that means that our strategy is to assume that $p$ is prime, that $p$ divides $ab$, and that $p$ does not divide $a$, and then to deduce that $p$ divides $b$.
</div>

<button type="button" class="btn btn-action" data-toggle="collapse" data-target="#hint3">
Hint 3
</button>

<div id="hint3" class="collapse">
If you're following the strategy suggested in the possible answer to hint 2 above, then you are making the extra assumption that $p$ does not divide $a$.  How can we use that information to help?
</div>

<button type="button" class="btn btn-action" data-toggle="collapse" data-target="#answer3">
Possible answer to hint 3
</button>

<div id="answer3" class="collapse">
We know that $p$ is prime and that $p$ does not divide $a$.  That tells us that the highest common factor of $a$ and $p$ is $1$ (that is, they are _coprime_).

The statement that two numbers have highest common factor $1$ can be quite a negative statement (they don't have any higher common factors), so can be quite difficult to work with.  But fortunately we have a way to turn that into a more positive statement: we know that if the highest common factor of two numbers is $1$, then we can write $1$ as a linear combination of them.  (You might have found this while working on [the open-ended investigation at this station](../NA3_RT9/index.html).)

So we know that there are integers $m$ and $n$ such that $am + pn = 1$.
</div>

<button type="button" class="btn btn-action" data-toggle="collapse" data-target="#hint4">
Hint 4
</button>

<div id="hint4" class="collapse">
We're almost there now.

How can we involve $b$?  We haven't yet used the assumption that $p$ divides $ab$.  How might we use that?
</div>

<button type="button" class="btn btn-action" data-toggle="collapse" data-target="#answer4">
Possible answer to hint 4
</button>

<div id="answer4" class="collapse">
We could multiply the equation $am + pn = 1$ (from the possible answer to hint 3) by $b$.  That would introduce a $b$ somewhere, and also gives us an $ab$, which should be useful.

Can you finish off the argument now?
</div>
