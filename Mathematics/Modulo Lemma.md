##  A Small Modulo Lemma
### David Awad and Dylan Lesko


This is a small lemma that seemed to be true that came up while studying Modular arithmatic with a friend. It resulted from doing this simple homework question. 

Is this true? $$$4^{1536} - 9^{4824} mod 35 ≡ 0 $$$ 

How would you reason about this problem? 

Messing with this the last couple days it turns out there's an interesting pattern that begins to appear. 

Given that $$$7*5 = 35$$$. The way that you're supposed to solve this problem, is to use the fact that $$$ (7-1) * (5-1) = 24 $$$ and 1536 and 4824 are multiples of 24, that means they will both result in a remainder of 1.

$$ 4^{1536} (mod 35) ≡ 1 $$
$$ 9^{4825} (mod 35) ≡ 1 $$

So the solution then becomes: 

$$ 1 - 1 (mod 35) ≡ 0 $$

But this is really interesting, as it turns out you can do this for any set of numbers when using modulo. Let's make a generalization, to see if this is in fact a true property that we've used here. 

We've know that for some $$$n$$$ and $$$m$$$, $$$x$$$; that $$$x^{nm} \% nm  ≡  0$$$

What we're saying is that we can raise x to the power of (n-1)*(m-1) instead, and know that if we modulo by $$$nm$$, that the result will be 1. 


$$	\forall n \forall m  [ x^{(m)(n)} \% nm ≡ 0 ] $$


$$	\forall n \forall m  [ x^{(m-1)(n-1)} \% nm ≡ 1 ] $$


$$	\forall n \forall m  [ x^{m + n - 1} \% nm ≡ 1 ] $$





