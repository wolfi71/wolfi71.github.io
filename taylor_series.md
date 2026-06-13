# <a name="taylor-series"></a> Taylor Series of $\tan(x)$

When you want to build the Taylor Series of the tangens function, you will get into trouble at higher derivatives, the first derivative
is just $\tan'(x)=1/(cos²(x))$ but from the second derivative on it gets more and more complicated. So we need a new method to calculate it.

Fortunately we can simplify the whole thing by using some formulas.

First we write the sine in terms of tangens and cosine:

$$ \sin(x) = \tan(x) \cos(x) $$

We know that 

$$ \sin^{(n)} = \sin(x + n \frac{\pi}{2})$$

We need also the formula for the product rule of higher derivatives (so-called Leibniz rule):

$$ (fg)^{(n)} = \sum^{n}_{k=0} \left( n \choose k \right) f^{(k)}g^{(n-k)} $$

analogous to the binomial sum
