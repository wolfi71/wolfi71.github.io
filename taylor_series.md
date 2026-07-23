# <a name="taylor-series"></a> Taylor Series of $\tan(x)$

When you want to build the Taylor Series of the tangens function, you will get into trouble at higher derivatives, the first derivative
is just $\tan'(x)=1/(cos²(x))$ but from the second derivative on it gets more and more complicated. So we need a new method to calculate it.

Fortunately we can simplify the whole thing by using some formulas.

First we write the sine in terms of tangens and cosine:

$$ \sin(x) = \tan(x) \cos(x) $$

We know that 

$$ \sin^{(n)}(x) = \sin(x + n \frac{\pi}{2})$$

We need also the formula for the product rule of higher derivatives (so-called Leibniz rule):

$$ (fg)^{(n)} = \sum^{n}_{k=0} { n \choose k } f^{(n-k)}g^{(k)} $$

analogous to the binomial sum.

Bringing this all together we get:

$$ \sin(x + n \frac{pi}{2}) = \tan^{(n)}(x)\cos(x) - { n \choose 1} \tan^{(n-1)}\sin(x) - { n \choose 2} \tan^{(n-2)}\cos(x) + {n \choose 3} \tan^{(n-3)}\sin(x) + { n \choose 4} \tan^{(n-1)}cos(x) - {n \choose 5}\tan^{(n-5)}sin(x) - \ldots$$

Taking for $x = 0$, we get ($\sin(0) = 0$, $\cos(0) = 1$):

$$ \sin( n \frac{\pi}{2}) = \tan^{n}(0) - {n \choose 2} \tan^{(n-2)}(0) + {n \choose 4}\tan^{(n-4)}(0) - {n \choose 6}\tan^{(n-6)}(0) + \ldots $$

We see from the equation that even derivatives are zero at $x=0$.

Taking now $n=1$, we get $\tan^{\prime}(0) = 1$, 
