---
layout: post
title:  "Differences of squares"
usemath: true
tag: counting
---

The number 2019 can be expressed as the difference of the squares of positivie integers *a* and *b*.
What is the sum of all the possible values of *a* and *b*?

<details markdown="1"><summary markdown="span">Solutions</summary>

## Solutions

Since $$ a^2 - b^2 = 2019 $$ and $$ a^2 - b^2 = (a+b)(a-b) $$, we have

$$ (a+b)(a-b) = 2019.$$

In addition, $$ a $$ and $$ b $$ are positivie integers, both $$ a+b $$ and $$
a - b $$ must be integers. Actually, both are positive and $$ a + b > a - b $$.

2019 has four factors: 1, 3, 673, and 2019. So there are only two pairs
of positive integers whose product is 2019.

Pair 1: 

$$ 2019 = 1 \times 2019. $$

In this case, 

$$ \begin{align}
a + b & = 2019 \\
a - b & =  1 
\end{align}$$

Solving for $$ a $$ and $$ b $$, we have $$ a = 1010 $$ and $$ b = 1009 $$.

Pair 2: 

$$ 2019 = 3 \times 673. $$

In this case, 

$$ \begin{align}
a + b & = 673 \\
a - b & =  3
\end{align}$$

Solving for $$ a $$ and $$ b $$, we have $$ a = 338 $$ and $$ b = 335 $$.

The sum all possible values of $$ a $$ and $$ b $$ is

$$ 1010 + 1009 + 338 + 335 = 2019 + 673 = 2692 $$

Now we can see that you do not really need to solve the equation systems to
find out $$ a + b $$. $$ a + b $$ is one of the equations in the system. For
pair 1, $$ a + b = 2019 $$ and for pair 2, $$ a + b = 673 $$. Be careful
though. You need to quickly check if both $$ a $$ and $$ b $$ are integers. 

## Discussions

An interesting fact one can learn from this problem is that any odd
integer is a difference of two perfect squares. 
For example: 

$$ 3 = 2^2 - 1^2 $$

$$ 5 = 3^2 - 2^2 $$

$$ 7 = 4^2 - 3^2 $$

$$ 9 = 5^2 - 4^2 $$

Can you find out pairs of perfect sqaures whose difference is 205? 

</details>

