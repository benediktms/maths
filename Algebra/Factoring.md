Factorisation is the opposite of expansion. It's the process of breaking an expression into smaller pieces. We can use the [[Real Numbers#Distributive Property|Distributive Property]] for both these use cases. We factor a complex expression as a product of simpler expressions.

For example, in the following expression:
$$x^2-4=(x-2)(x+2)$$

We can say that $x-2$ and $x+2$ are factors of $x^2-4$

## Factoring Trinomials

When factoring a trinomial in the form of $x^2+bx+c$ we note that
$$(x+r)(x+s)=x^2+(r+s)x +rs$$
so we need to choose numbers $r$ and $s$ so that $r+s=b$ and $rs=c$

## Common factors

The easiest way to factor an expression is when we have common terms. Therefore, when we need to factorise an expression, we need to find the greatest common factor of all the terms.

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
> 
> The greatest common factor of the three terms in the [[Variables & Expressions#Polynomials|polynomial]] is $2xy^2$.
> $$\begin{align}
> & 8x^4y^2+6x^3y^3-2xy^4 \\
> & = (2xy^2)(4x^3)+(2xy^2)(3x^2y)+(2xy^2(-y^2)\\
> & =2xy^2(4x^3+3x^2y-y^2)
> \end{align}$$

## Factoring out a common factor

When two terms have a common factor we can use the Distributive property to simplify the expression:
$$
\begin{align}
(2x+4)(x-3)-5(x-3) &=[(2x+4)-5](x-3)\\
&=(2x-1)(x-3)
\end{align}
$$

A lot of the time we will have to find common factors by trial and error. We should always try to find common factors of the **leading coefficient** and the **constant** of a polynomial, and then see how we can apply those factors to get the middle coefficient. Assuming that all numbers are integers, this should limit the possibilities.

If we have a situation where in a trinomial the leading coefficient $=1$ then we can simply try to find the factors of the product of the constant and the sum of the middle coefficient.

>[!example]
>$$\begin{align}
>& x^2+7x+12\\
>& = (x+3)(x+4)
>\end{align}$$
>The common factors in this expression that multiply to give the product $12$ and the sum $7$ are $3$ and $4$.

If the leading coefficient, $a\ne1$ then we must apply the following:
$$\begin{align}
ax^2+bx+c &= (px+r)(qx+s)\\
&=pqx^2+(ps+qr)+rs
\end{align}$$
Where we should try to find numbers $p$, $q$, $r$, and $s$ such that $pq=a$, $rs=c$, $ps+qr=b$

> [!example]
> $$6x^2+7x-5$$
> We can factor $6$ as $6\cdot1$ or $3\cdot2$ and can factor $-5$ as $-5\cdot1$ or $5\cdot(-1)$. With some trial and error, we can arrive at the following:
> $$6x^2+7x-5 = (3x+5)(2x-1)$$

## Factoring by grouping

Sometimes we will not have a common factor. In these scenarios, we must change the middle term to meet the requirements by substituting it for an expression that results in the same value, but that we can factor by.
$$3x^2-16x+5$$
This expression does not have any common factors, where the product equals $5$ and the sum equals $-16$. We can solve this by multiplying the leading coefficient by the constant term:
$$3\cdot5 =15$$
We can use this new number to find a common factor between $3$ and -$16$ and re-write our expression (of course, using the Distributive Property once more):
$$\begin{align}
& 3x^2-15x-x+5\\
&= 3x(x-5)-(x-5)\\
&= (3x-1)(x-5)
\end{align}$$

> [!note]
> Notice that on the second step, we can already see the common factor of $(x-5)$. This is a good indicator that we are on the right track. Additionally, the $-1$ comes from the $-(x-5)$ which is the same as $-1(x-5)$

## Recognizing the Form of an expression

Sometimes an expression can be drastically simplified if we can correctly recognize the form of an expression, even though it may appear more complex to begin with. Let's take a very basic trinomial:
$$x^2-2x-3$$
We can solve this through some very simple trial and error. However, if we take a slightly more complex expression:
$$(5a+1)^2-2(5a+1)-3$$
While this expression may look more complicated to begin with if we substitute $(5a+1)$ with $A$:
$$A^2-2A-3$$
We can see that this is essentially the same as the first expression we had and we can factor it as:
$$\begin{align}
(5a+1)^2-2(5a+1)-3&=[(5a+1)-3][(5a+1)+1]\\
&=(5a-2)(5a+2)
\end{align}$$

## Special Factoring Formulas

Some special algebraic formulas can be factored using the following formulas (notice that the first three are simply the [[Variables & Expressions#Special Product Formula|Special Product Formula]] written backwards):
> [!rule]
> $$\begin{align}
> 1. &\space A^2-B^2 = (A-B)(A+B) &\text{Difference of squares}\\
> 2. &\space A^2+2AB+B^2=(A+B)^2 &\text{Perfect square}\\
> 3. &\space A^2-2AB+B^2=(A-B)^2 &\text{Perfect square}\\
> 4. &\space A^3-B^3=(A-B)(A^2+AB+B^2) &\text{Difference of cubes}\\
> 5. &\space A^3+B^3=(A+B)(A^2-AB+B^2) &\text{Sum of cubes}\\
> \end{align}$$

