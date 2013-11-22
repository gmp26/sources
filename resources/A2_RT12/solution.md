````
alias: Solution
weight: 3
````

<:= style(chalk) :>

We can think of $3 - 2$ as a difference of two squares, since $3 - 2 = \left(\sqrt{3}\right)^2 - \left(\sqrt{2}\right)^2$.

<:= style() :>

Let the sum we're interested in be $S$, so $$S = \frac{1}{\sqrt{1} + \sqrt{2}} + \frac{1}{\sqrt{2} + \sqrt{3}} + \frac{1}{\sqrt{3} + \sqrt{4}} + \dotsb + \frac{1}{\sqrt{15} + \sqrt{16}}.$$

Then $$S = \frac{\sqrt{2} - \sqrt{1}}{2 - 1} + \frac{\sqrt{3} - \sqrt{2}}{3 - 2} + \frac{\sqrt{4} - \sqrt{3}}{4 - 3} + \dotsb + \frac{\sqrt{16} - \sqrt{15}}{16 - 15}.$$

We can simplify the denominators very nicely, to get $$S = (-\sqrt{1} + \sqrt{2}) + (-\sqrt{2} + \sqrt{3}) + (-\sqrt{3} + \sqrt{4}) + \dotsb + (-\sqrt{15} + \sqrt{16}).$$

The sums on the right-hand side now telescope (lots of adjacent terms cancel), so we are just left with the first and last terms.

So $S = \sqrt{16} - \sqrt{1} = 4 - 1 = 3$.

* * *

We could construct a similar expression with sum $5$ by adding on extra terms up to $\frac{1}{\sqrt{25} + \sqrt{24}}$.

There are other possibilities too: if we construct a similar sum that evaluates to $8$, then the difference between this and $S$ will be $3$.  So we can do something similar even if we don't start with $\frac{1}{\sqrt{1} + \sqrt{2}}$.

* * *

We can construct many similar expressions that don't evaluate to integers.  One example would be $T = S - \frac{1}{\sqrt{15} + \sqrt{16}}$ (so just miss out the last term of $S$).  If we rationalise the denominators then we still get a telescoping sum, but this time $T = \sqrt{15} - \sqrt{1} = \sqrt{15} - 1$, which is not an integer.