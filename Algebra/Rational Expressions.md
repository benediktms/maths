A rational expression is a **fractional expression** where both the numerator and the denominator are [[Variables & Expressions#Polynomials|polynomials]].  This is an example of a rational expression:
$$\frac{x^3-x}{x^2-5x+6}$$
However this is not:
$$\frac{x}{\sqrt{x^2+1}}$$
because the denominator is a [[Radicals|radical]].

## Simplifying rational expressions

We can simplify rational expressions by [[Factoring|factoring]] the numerator and denominator and using the following property of fractions:
$$\frac{AC}{BC}=\frac AB$$
which allows us to **cancel** common factors.

>[!example]
>$$\begin{align}
>&\frac{x^2-1}{x^2+x-2}\\[2ex]
>=\space &\frac{(x-1)(x+1)}{(x-1)(x+2)}\space=\space \frac{\cancel{\color{red}{(x-1)}}(x+1)}{\cancel{\color{red}{(x-1)}}(x+2)}\\[2ex]
>=\space &\frac{x+1}{x+2}
>\end{align}$$
>Here we can cancel the common factors of the expression once we have factored it. The same rule applies when we divide the numerator and denominator. For example, given this expression:
>$$\frac{5(x-3)(2x+1)}{10(x-3)^2}$$
>We can divide the denominator and the numerator by $5$:
>$$\frac{(x-3)(2x+1)}{2(x-3)^2}$$
>Then can divide by $(x-3)$ to cancel out that part of the numerator (and reduce the exponent of the denominator by $1$):
>$$\frac{2x+1}{2(x-3)}$$

## Multiplying and Dividing Rational Expressions

For multiplying rational expressions, we do:
$$\frac AB\cdot\frac CD = \frac{AC}{BD}$$
> [!example]
> To multiply and simplify the following:
> $$\begin{align}\\
> &\frac{x^2+2x-3}{x^28x+16}\cdot\frac{3x+12}{x-1}\\[2ex]
> &=\frac{(x-1)(x+3)}{(x+4)^2}\cdot \frac{3(x+4)}{x-1}\\[2ex]
> &=\frac{3({\color{red}{x-1}})(x+3)({\color{teal}{x+4}})}{({\color{red}{x-1}})({\color{teal}{x+4}})^2}\\[2ex]
> &=\frac{3(x+3)}{x+4}
> \end{align}$$

When dividing rational expressions, we use the following property:
$$\frac AB \div \frac CD = \frac AB \cdot \frac DC$$
After that we follow the same process as for multiplication.

> [!example]
> Let's look at a slightly more complicated example that looks at various mathematical  concepts to factor and simplify the following:
> $$\begin{align}
> &\frac{x+3}{4x^2-9} \cdot \frac{x^2+7x+12}{2x^2+7x-15}\\[2ex]
> &=\frac{x+3}{(2x+3)(2x-3)} \cdot \frac{2x(x+5)-3(x+5)}{(x+5)(2x-3)}\\[2ex]
> &= \frac{({\color{red}{x+3}})(x+5)({\color{teal}{2x-3}})}{({\color{teal}{2x-3}})(2x+3)(x+4)({\color{red}{x+3}})}\\[2ex]
> &=\frac{x+5}{(2x+3)(x+4)}
> \end{align}$$
> In the above example we factor $2x^2+7x-15$. After we factor, the expression we can see that both terms have the binomial $(x+5)$ in common, which we can factor out, resulting in $(x+5)(2x-3)$. After that, we can continue factoring the initial expression.

## Adding and Subtracting Rational Expressions

When adding or subtracting rational expressions, we follow the following property:
$$\frac AC + \frac BC = \frac{A+B}{C}$$
We can then use any common denominator, but it's usually best to use the **least common denominator (LCD)**.