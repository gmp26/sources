Draft suggestion for a Probability tube line

````
id: P1
title: What does it mean to find a probability when the outcomes are equally likely?
````

##Key Questions

1.  What do we mean by _trials_, _outcomes_, _sample space_ and _equally likely_?

1.  How can we find probabilities by counting suitable quantities?

1.  What does it mean for two events to be _complementary_, and how are their probabilities related?





````
id: P2
title: How do we count?
dependencies:
    - P1
````
##Key Questions

1.  How can we count the possibilities arising from a succession of choices?

1.  Does it matter whether we care about the order of our choices?

1.  How does the factorial notation work?

1.  What do we mean by _permutations_ and _combinations_?

_(Note during drafting: A3 depends on P2.  Should this station about counting be on the Probability line, or should it float around not being part of any tube line but linking with other stations?)_





````
id: P3
title: How can we find probabilities when the outcomes need not be equally likely?
dependencies:
    - P2
````

##Key Questions

1.  How can we find probabilities by counting suitable quantities?





````
id: P4
title: What outcome do we expect?
dependencies:
    - P3
````
##Key Questions

1.  What do we mean by _expectation_?

1.  How can we find the expectation of the number of successes in repeated trials?

1.  What is the relationship between probability and expectation?





````
id: P5
title: What if we are interested in two events?
dependencies:
    - P4
````
##Key Questions

1.  What representations can we use to help us understand the situation?

1.  How can we find the probabilities of both, exactly one or neither of the events happening?

1.  How can we find the probability of at least one of the events happening?





````
id: P6
title: How does one event influence another?
dependencies:
    - P5
````
##Key Questions

1.  What does it mean to talk about the probability of one event given another?

1.  What do we mean by _conditional probability_?

1.  What is Bayes' theorem, and why is it important?

1.  What does it mean for two events to be _independent_?





````
id: P7
title: What if we are interested in more than two events?
dependencies:
    - P6
````
##Key Questions

1.  What representations can we use to help us understand the situation?

1.  How can we find the probability of some subset of the events happening?

1.  What do we mean by the _union_ and _intersection_ of events?

1.  What is the _inclusion-exclusion principle_, and how is it useful?





````
id: P8
title: What is the function that counts heads in ten coin tosses?
dependencies:
    - P7
````
##Key Questions

1.  What is a _random variable_?

1.  What is an _indicator function_?

1.  What do we mean by the expectation, or mean, of a random variable?

1.  What do we mean by the variance of a random variable?

1.  How can we think about the probability of a tail event?

_(Note during drafting: this is all about discrete random variables.)_





````
id: P9
title: What happens if our coin is biased?
dependencies:
    - P8
    - A3
````
##Key Questions

1.  What does it mean to say that a random variable has the binomial distribution?

1.  What are some good examples of binomial random variables?

1.  What is the mean of a binomial random variable?

1.  What is the variance of a binomial random variable?

1.  What interesting features do binomial random variables have?

1.  How can we think about the probability of a tail event?

1.  How can we check the plausibility of a hypothesis?





````
id: P10
title: How many e-mails do we get in an hour?
dependencies:
    - P9
    - C11
````
##Key Questions

1.  What does it mean to say that a random variable has the Poisson distribution?

1.  What are some good examples of Poisson random variables?

1.  What is the mean of a Poisson random variable?

1.  What is the variance of a Poisson random variable?

1.  What interesting features do Poisson random variables have?

1.  How can we think about the probability of a tail event?

1.  How can we check the plausibility of a hypothesis?





````
id: P11
title: How many cereal packets will we buy until we collect our favourite toy?
dependencies:
    - P10
    - A8
````
##Key Questions

1.  What does it mean to say that a random variable has the geometric distribution?

1.  What are some good examples of geometric random variables?

1.  What is the mean of a geometric random variable?

1.  What is the variance of a geometric random variable?

1.  What interesting features do geometric random variables have?

1.  How can we think about the probability of a tail event?

1.  How can we check the plausibility of a hypothesis?





````
id: P12
title: Can we have continuous random variables?
dependencies:
    - P11
````
##Key Questions

1.  What is a continuous random variable?

1.  What do we mean by the expectation, or mean, of a continuous random variable?

1.  What do we mean by the variance of a continuous random variable?

1.  What is the normal distribution, and why is it important?

1.  What do we mean by the _standard_ normal distribution?

1.  What is the exponential distribution, and why is it important?

1.  How can we think about the probability of a tail event?

1.  How can we check the plausibility of a hypothesis?





````
id: P13
title: What if we have more than one random variable?
dependencies:
    - P12
````
##Key Questions

1.  What does it mean to say that expectation is linear?

1.  When is it true that $\Var(X+Y) = \Var(X) + \Var(Y)$?

1.  If we know the distributions of $X$ and $Y$, what can we say about the distribution of $X+Y$, $XY$ and other functions of $X$ and $Y$ (perhaps in some special cases)?