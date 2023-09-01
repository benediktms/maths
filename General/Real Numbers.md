Real numbers can be divided into 3 different kinds:
- Natural numbers $\Bbb{N}$: any number that is $<0$, e.g. $1,2,3,4,\cdots$ Note: Sometimes $0$ is considered a natural number
- Whole numbers $\Bbb{W}$: any $\Bbb{N}$ number that is not negative, e.g. $0,1,2,3\dots$
- Integers $\Bbb{Z}$: any $\Bbb{W}$ as well as their negative counterparts and $0$, e.g. $-3,-2,-1,0,1,2,3$
- Rational numbers/quotients $\Bbb{Q}$: fractions/ratios/quotients of integers, they are expressed as $$r = \frac mn$$ where $m$ and $n$ are integers and $n \neq 0$, e.g: $\frac 37, 0.16$. Division by $0$ is ruled out, so $\frac 30$ or $\frac 00$ is undefined.
- Irrational numbers (there is no dedicated set notation, but it can be expressed as $\Bbb{R}-\Bbb{Q}$): A number that cannot be expressed as a ratio of integers, such as $\sqrt 2$ or $\pi$
Real numbers $\Bbb{R}$: All numbers that are either rational or irrational or any number with a decimal expansion

These can be expressed like so:
$$
\Bbb{N} \subseteq \Bbb{W} \subseteq \Bbb{Z} \subseteq \Bbb{Q} \subseteq \Bbb{R}
$$

There are also Complex numbers $\Bbb{C}$ which are used with imaginary numbers $i$ and contain all of $\Bbb{R}$.

Where going from left to right, Natural numbers are a subset of Whole numbers, which in turn are a subset of Integers, etc.

Every real number has a decimal representation. If the number is rational the decimal is repeating, e.g. $$\frac23=0.6666\cdots=0.\overline6$$
$$\frac{157}{495}=0.317171717\cdots=0.3\overline{17}$$
### Closure Property

Real numbers $\Bbb{R}$ is considered a closed (the Closed Property) set (that is, performing any mathematical operation with two real numbers will result in another new number). Quotients $\Bbb{Q}$ for example are considered open sets, because it is the result of a mathematical operation can escape the set, for example $\frac{1}{2}+\frac{1}{2}=1$ which is a natural number $\Bbb{N}$. Another example would be $2-3=-1$ this is an example where the order matters (see [[Real Numbers#Commutative Properties|Commutative Property]]) because $3-2$ would still be within $\Bbb{N}$.

## Associative Properties

> [!rule]
> Associative properties are defined as the following: 
> - When we add three (or more) numbers, it does not matter which two numbers we add first
> - When we multiply three (or more) numbers, it does not matter which two numbers we multiply first
> 
> $$(a + b) + c = a + (b + c)$$
> $$(ab)c = a(bc)$$
> > [!example]
> > $$(2 + 4) + 7 = 2 + (4 + 7)$$
> > $$(3 \cdot 7) \cdot 5 = 3 \cdot (7 \cdot 5)$$

## Commutative Properties

> [!rule]
> The commutative properties are defined as following:
> - When we add two numbers, the order does not matter.
> - When we multiply two numbers, the order does not matter.
> 
> $$a + b = b + a$$
> $$ab = ba$$
> >[!example]
> >$$7 + 3 = 3 + 7$$
> >$$3 \cdot 5 = 5 \cdot 3$$

## Distributive Property
> [!rule]
> The distributive property can be defined as following:
> When multiplying the sum of two (or more) numbers, we get the same result as if we add the products of all the terms
> 
> $$a(b+c) = ab+bc$$
> $$(b+c)a = ab+ac$$
> >[!example]
> >$$2\cdot(3+5) = 2\cdot3 + 2\cdot5$$
> >$$(3+5)\cdot2 = 2\cdot3 + 2\cdot5$$

The distributive property is important because it describes how addition and multiplication interact with each other.

## Identity (Addition and Subtraction)
- $0$ is called the **additive identity** because $a+0=1$ for any real number
- Every real number has a negative $-a$ that satisfies $a+(-a)=0$
- Subtraction is defined as $a-b=a+(-b)$
>[!properties of negatives]
>1. $(-1)a=-a$
>2. $-(-a)=a$
>3. $(-a)b=a(-b)=-(ab)$
>4. $(-a)(-b)=ab$
>5. $-(a+b)=-a-b$
>6. $-(a-b)=b-a$

## Multiplication and Division
- $1$ is called the **multiplicative identity** because $a\cdot1=a$
- Every non-zero real number has an inverse $1/a$ that satisfies $a\cdot(1/a)$
- Division is defined as $a\div b =a\cdot \frac 1b$ where $b \neq0$
	- We can write $a\cdot(1/b)$ as $a/b$. We refer to this as the **quotient** of $a$ and $b$ or as the **fraction** $a$ over $b$.]: $a$ is the **numerator** and $b$ is the **denominator** (or **divisor**).

>[!properties of fractions]
>1. $\frac ab \cdot \frac cd = \frac{ac}{bd}$
>2. $\frac ab \div \frac cd = \frac ab \cdot \frac dc$
>3. $\frac ac + \frac bc = \frac{a+b}{c}$
>4. $\frac ab + \frac cd = \frac{ad+bc}{bd}$
>5. $\frac{ac}{bc} = \frac ab$
>6. $\text{If} \frac ab = \frac cd \text{, then } ad = bc$

When we add fractions, we don't usually use Property 4. Instead, we rewrite fractions so that they have the smallest common denominator (which is often smaller than the product of the denominators) and then use Property 3. This is also called the **least common denominator (LCD)**.

### Some definitions
For a fraction $\frac{a}{b}$,
- The **numerator** is the term above the line, $a$
- The **denominator** is the term below the line, $b$
- The **reciprocal** is the fraction you get from flipping the numerator and denominator, $\frac{b}{a}$

### Using the LCD to add fractions
If we need to evaluate the following:
$$\frac {5}{36} + \frac{7}{120}$$
We factor the denominators into their prime factors: $36=2^2\cdot3^2$ and $120=2^3\cdot3\cdot5$
We can then find the LCD by forming the product of all the prime factors that occur in these factorisations, using the highest power of each prime factor. In the above example, this would be:
$$2^3\cdot3^2\cdot5 =360$$
Therefore:
$$
\frac5{36}+\frac7{120}=
\frac
{5\cdot{\color{red}{10}}}
{36\cdot{\color{red}{10}}}+
\frac
{7\cdot{\color{red}{3}}}
{120\cdot{\color{red}{3}}}
$$
We multiply each fraction by the numbers needed so that we get the LCD as the denominator. Afterward we can simply add the fractions:
$$\frac{50}{360}+\frac{21}{360}=\frac{71}{360}$$
## Bow tie method
An alternative to adding and subtracting fraction is to use the bow tie method, which is expressed as follows:

If given the expression
$$
\frac{a}{b} \pm \frac{c}{d}
$$
We can re-write it as follows:
$$
\frac{ad \pm cd}{db}
$$

> [!example]
> $$
> \begin{align}
& \frac{1}{2}+\frac{3}{5} \\[2ex]
= &\frac{(5\cdot 1)+(3\cdot 2)}{5\cdot 2} = \frac{11}{10}
\end{align}
$$


