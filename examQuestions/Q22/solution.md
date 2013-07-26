````
alias: Solution
````
Since $182^2=33124$ and $183^2=33489$, let $n=182$.

Since $184^2-33127=729=27^2$, let $m=2$.

<div class="chalk span4 pull-right">
We might notice that we have a difference of two squares, which is often helpful for factorising something.
</div>
Therefore $184^2-27^2=33127$, so $33127=(184-27)\times(184+27)$, which implies that $33127=157\times211.$

* * *

If $(n+m)^2 - 33127$ is a perfect square, say $k^2$ where $k$ is an integer, then we have that $33127$ is a difference of two squares: $33127 = (n+m)^2 - k^2 = (n+m-k)(n+m+k)$.  So $n+m-k$ and $n+m+k$ must be factors of $33127$.

It is crucial to realise that $157$ and $211$ are both prime numbers, hence the only other factorisation of $33127$ is $33127=1\times33127$.

<div class="chalk">
In fact, $33127$ has four other factors, the negatives of the factors that we have found so far.  You might like to consider whether they contribute anything helpful.
</div>

Therefore $33127=(16564-16563)\times(16564+16563)=16564^2-16563^2$, so $m=16382$.

The question is based on the method of Fermat factorisation, which can sometimes be used effectively to factorise integers. Notice how we have factorised a number without ever dividing.
