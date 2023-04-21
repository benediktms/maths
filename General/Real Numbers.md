Real numbers can be divided into 3 different kinds:
- Natural numbers: any integer that is $<0$, e.g. $1,2,3,4,\cdots$
- Integers: any natural number as well as their negative counterparts and $0$, e.g. $-3,-2,-1,0,1,2,3$
- Rational numbers: fractions or ratios of integers, they are expressed as $$r = \frac mn$$ where $m$ and $n$ are integers and $n \neq 0$, e.g: $\frac 37, 0.16$. Division by $0$ is ruled out, so $\frac 30$ or $\frac 00$ is undefined.
- Irrational numbers: A number that cannot be expressed as a ratio of integers such as $\sqrt 2$ or $\pi$

The set of all real numbers can be denoted as $\mathbb R$. Every real number has a decimal representation. If the number is rational the  decimal is repeating, e.g. $$\frac23=0.6666\cdots=0.\overline6$$
$$\frac{157}{495}=0.317171717\cdots=0.3\overline{17}$$

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

## Addition and Subtraction
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

### Using the LCD to add fractions
If we need to evaluate the following:
$$\frac {5}{36} + \frac{7}{120}$$
We factor the denominators into their prime factors: $36=2^2\cdot3^2$ and $120=2^3\cdot3\cdot5$
We can then find the LCD by forming the product of all the prime factors that occur in these factorizations, using the highest power of each prime factor. In the above example, this would be:
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