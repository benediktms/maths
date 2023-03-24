Factorization is the opposite of expansion. We can use the [[Distributive Property]] for both these use cases. We factor a complex expression as a product of simpler expressions.

For example in the following expression:
$$x^2-4=(x-2)(x+2)$$

We can say that $x-2$ and $x+2$ are factors of $x^2-4$

## Common factors

The easiest way to factor an expression is when we have common terms. Therefore, when we need to factorize an expression, we need to find the greatest common factor of all the terms.

When we multiply two numbers together, each number is called a **factor** of the product. When we add two numbers together, each number is called a **term** of the sum.
 
If a factor is common to each term of an expression we can factor it out. For example
$$ax+2ay$$
Each term contains the factor $a$ so we can write the expression as:
$$ax+2ay = a(x+2y)$$

> [!example]
> $$8x^4y^2+6x^3y^3-2xy^4$$
> - 8, 6 and -2 have the greatest common factor of 2
> - $x^4$,  $x^3$, and $x$ have the greatest common factor of $x$
> - $y^2$, $y^3$, and $y^4$ have the greatest common factor of $y$

The greatest common factor of the three terms in the [[Variables & Expressions#Polynomials|polynomial]] is $2xy^2$:
$$\begin{align}
& 8x^4y^2+6x^3y^3-2xy^4 \\
& = (2xy^2)(4x^3)+(2xy^2)(3x^2y)+(2xy^2(-y^2)\\
& =2xy^2(4x^3+3x^2y-y^2)
\end{align}$$

## Factoring out a common factor

When two terms have a common factor we can use the Distributive property so simplify the expression:
$$\begin{align}
(2x+4)(x-3)-5(x-3) &=[(2x+4)-5](x-3)\\
&=(2x-1)(x-3)
\end{align}$$

A lot of the time we will have to find common factors by trial and error. We should always try to find common factors in the first number and the last number of a polynomial, and then see how we can apply those factors to get the middle numbers. Assuming that all numbers are integers, this should limit the possibilities.

The mathematical formula for this is as follows, assuming $a\ne1$:
$$\begin{align}
ax^2+bx+c &= (px+r)(qx+s)\\
&=pqx^2+(ps+qr)+rs
\end{align}$$
Where we should try to find numbers $p$, $q$, $r$, and $s$ such that $pq=a$, $rs=c$, $ps+qr=b$.

> [!example]
> $$6x^2+7x-5$$
> We can factor $6$ as $6\cdot1$ or $3\cdot2$ and can factor $-5$ as $-5\cdot1$ or $5\cdot(-1)$. With some trial and error, we can arrive at the following:
> $$6x^2+7x-5 = (3x+5)(2x-1)$$

## Factoring by grouping

Sometimes we will not have a common factor. In these scenarios, we must change the middle term to meet the requirements by substituting it for an expression that results in the same value, but that we can factor by.
$$\begin{align}
3x^2-16x+5
\end{align}$$
This expression does not have any common factors, where the product equals $5$ and the sum equals $-16$. We can solve this by multiplying the leading **coefficient** by the constant term:
$$x\$$