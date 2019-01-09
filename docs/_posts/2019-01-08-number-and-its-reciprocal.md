---
layout: post
title:  "A Number and Its Reciprocal"
usemath: true
tag: counting
---

If a number $$ x $$ plus its reciprocal is equal to 4, what is the absolute
difference between $$ x $$ and its reciprocal? Express the answer in simplest
radical form. 

<details markdown="1"><summary markdown="span">Solutions</summary>

## Solutions

First, we rewrite the problem with math equations. The question is 

If  $$ x + \frac{1}{x} = 4 $$, what is $$ \lvert x - \frac{1}{x} \rvert $$ ?  

We will show two methods to solve the problem. 

### Method 1

We rewrite the absolute value with square and sqaure root. 

$$ \lvert x - \frac{1}{x} \rvert  = \sqrt{ (x - \frac{1}{x})^2 } 
= \sqrt{ x^2 - 2 + \frac{1}{x^2} }
= \sqrt{ x^2 + \frac{1}{x^2} - 2}.
$$ 

Next, we find the value of $$ x^2 + \frac{1}{x^2} $$ from the given equation.

Starting from $$ x + \frac{1}{x} = 4 $$, we square both sides of the
equation and expand the sqaure of the binomial.

$$ x + \frac{1}{x} = 4 $$

Squaring both sides, we get

$$ (x + \frac{1}{x})^2 = 4^2 $$

Expanding the left side, we get

$$ x^2 + 2 + \frac{1}{x^2} = 16 $$

Subtracting 2 from both sides, we have

$$ x^2 + \frac{1}{x^2} = 14. $$

Therefore, 

$$ \lvert x - \frac{1}{x} \rvert
= \sqrt{ x^2 + \frac{1}{x^2} - 2}
= \sqrt{ 14 - 2} = \sqrt{12} = 2\sqrt{3}.
$$ 

So the answer is $$ 2\sqrt{3} $$.

### Method 2

Since $$ x + \frac{1}{x} = 4 $$, we can try to the equation.

Multiplying both sides by $$ x $$, we have

$$ x^2 + 1 = 4x $$

Subtracting $$ 4x $$ from both sides, we have

$$ x^2 - 4x + 1 = 0 $$

Solving for $$ x $$, we have $$ x = 2 + \sqrt{3} $$ or $$ x = 2 - \sqrt{3}.$$

Both values of $$ x $$ should lead to the same answer. Let us try $$ 2 + \sqrt{3} $$ first.

$$ \lvert x - \frac{1}{x} \rvert 
= (2 + \sqrt{3}) - \frac{1}{ (2 + \sqrt{3}) }
= \frac{ (2 + \sqrt{3})^2 - 1 }{2 + \sqrt{3}}
= \frac{ 2^2 + 4\sqrt{3} + 3 - 1}{2 + \sqrt{3}}
= \frac{ 6 + 4\sqrt{3}}{2 + \sqrt{3}}
$$

The difficulty here is to remove the square root at the bottom. Below is one
way to do it.

$$ \begin{align}
\lvert x - \frac{1}{x} \rvert & = \frac{ 6 + 4\sqrt{3}}{2 + \sqrt{3}} \\
& = \frac{ (6 + 4\sqrt{3})(2 - \sqrt{3})}{(2 + \sqrt{3})(2 - \sqrt{3})}) \\
& = \frac{ 12 - 6\sqrt{3} + 8\sqrt{3} - 4(\sqrt{3})^2}{2^2 - (\sqrt{3})^2} \\
& = \frac{ 12 + 2\sqrt{3} - 12}{4 - 3} \\
& = \frac{ 2\sqrt{3} }{1} \\
& = 2\sqrt{3}
\end{align}
$$   

If you try $$ x = 2 - \sqrt{3}$$, you will get $$ 2\sqrt{3} $$, too. 

## Discussions

In method 1, the key is to notice that both the square of $$ x + \frac{1}{x} $$
and the square of $$ x - \frac{1}{x} $$ have $$ x^2 + \frac{1}{x^2} $$. BTW, the
absolute difference of the two squares is always 4.  

$$ (x + \frac{1}{x})^2 - (x - \frac{1}{x})^2 = 
(x^2 + 2 + \frac{1}{x^2}) - (x^2 - 2 + \frac{1}{x^2}) = 4. $$ 

In method 2, the key is to remove the square root from the denominator. Also, you may
have noticed that the reciprocal of $$ 2 + \sqrt{3} $$ is $$ 2 - \sqrt{3} $$ 
because their prodcut is 1. 

$$ (2 + \sqrt{3})(2 - \sqrt{3}) = 2^2 - \sqrt{3}^2 = 4 - 3 = 1. $$ 

It may be easy to see in the following equations:

$$ 2 + \sqrt{3} = \frac{1}{2 - \sqrt{3}}, $$

or

$$ 2 - \sqrt{3} = \frac{1}{2 + \sqrt{3}}. $$

</details>

