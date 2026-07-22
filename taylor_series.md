# <a name="taylor-series"></a> Taylor Series of $\tan(x)$

When you want to build the Taylor Series of the tangens function, you will get into trouble at higher derivatives, the first derivative
is just $\tan'(x)=1/(cos²(x))$ but from the second derivative on it gets more and more complicated. So we need a new method to calculate it.

Fortunately we can simplify the whole thing by using some formulas.

First we write the sine in terms of tangens and cosine:

$$ \sin(x) = \tan(x) \cos(x) $$

We know that 

$$ \sin^{(n)} = \sin(x + n \frac{\pi}{2})$$

We need also the formula for the product rule of higher derivatives (so-called Leibniz rule):

$$ (fg)^{(n)} = \sum^{n}_{k=0} { n \choose k } f^{(n-k)}g^{(k)} $$

analogous to the binomial sum.

Bringing this all together we get:

$$ \sin(x + n \frac{pi}{2}) = \tan^{(n)}(x)\cos(x) - { n \choose 1} tan^{(n-1)}\sin(x) - { n \choose 2} \tan^{(n-2)}\cos(x) + {n \choose 3} \tan^{(n-3)}\sin(x) + { n \choose 4} \tan^{(n-1)}cos(x) - {n \choose 5}\tan^{(n-5)}sin(x) - \ldots$$
