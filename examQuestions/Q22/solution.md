````
alias: Solution
````
Since $182^2=33124$ and $183^2=33489$, let $n=182$.

Since $184^2-33127=729=27^2$, let $m=2$.

<div class="chalk">
We might notice that we have a difference of two squares, which is often helpful for factorising something.
</div>
Therefore $184^2-27^2=33127$, so $33127=(184-27)\times(184+27)$, which implies that $33127=157\times211$.

* * *

If $(n+m)^2 - 33127$ is a perfect square, say $k^2$ where $k$ is an integer, then we have that $33127$ is a difference of two squares: $33127 = (n+m)^2 - k^2 = (n+m-k)(n+m+k)$.  So $n+m-k$ and $n+m+k$ must be factors of $33127$.

It is crucial to realise that $157$ and $211$ are both prime numbers, hence the only other factorisation of $33127$ is $33127=1\times33127$.

Therefore the possible factorisations of $33127$ are:
* $33127=1 \times 33127$,
* $33127=157 \times 211$,
* $33127=(-1) \times (-33127)$,
* $33127=(-157) \times (-211)$.

To find $m$ we must solve simultaneous equations of the form
$$n+m-k=a$$
$$n+m+k=b$$
where $a \times b=33127$.

Adding the two equations gives $2(n+m)=a+b$ and since $n=182$ we see that $m=\frac{a+b}{2}-182$, and so there are $4$ possible values for $m$:

$$m=\frac{33128}{2}-182=16382,$$
$$m=\frac{368}{2}-182=2,$$
$$m=\frac{-33128}{2}-182=16746,$$
$$m=\frac{-368}{2}-182=-366.$$

The question is based on the method of Fermat factorisation, which can sometimes be used effectively to factorise integers. Notice how we have factorised a number without ever dividing.
