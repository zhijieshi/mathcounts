---
layout: post
title:  "Multiplication table"
usemath: true
---

The following table is part of mutliplicatin table and some of the digits in
the product are replaced with question marks. For example, $$ x \cdot y = 7?2
$$. What is the sum of the four product numbers in this table?  

|      | y    | y + 1 |
|:----:|:----:|:-----:|
| x    | 7?2  | ??9   |
| x+1  | ?2?  | 8??   |

<details markdown="1"><summary markdown="span">Solutions</summary>

According to the table, we have four equations.

$$ \begin{align}
x \cdot y = 7?2 \\
x \cdot (y + 1) = ??9 \\
(x+1) \cdot y = ?2? \\
(x+1) \cdot (y + 1) = 8?? 
\end{align}$$

Looking at the first two equations, we can see $$ 7?2 + x = ??9 $$.

$$ \begin{align}
x \cdot y = 7?2 \\
x \cdot (y + 1) = x \cdot y + x = 7?2 + x = ??9 \\
\end{align}$$

Therefore, the unit digit of $$ x $$ must be 7.

Since $$ x \cdot y = 7?2 $$, the unit digit of $$ y $$ must be 6. 
Also, the unit digit of $$ x + 1 $$ must be 8, and that of $$ y + 1 $$ must be 7.

With the information about unit digits, we can find out the unit digit of all
the product numbers.

|      | y    | y + 1 |
|:----:|:----:|:-----:|
| x    | 7?2  | ??9   |
| x+1  | ?28  | 8?6   |

Now we focus on the following equation because there is only one digit missing and
we have clues about the hundred digit.

$$ (x+1) \cdot y = ?28 $$

The question mark in this equation is either 7 or 8. 
We try 8 here (you can try 7, but it does not work).
If the question mark is 8, we have

$$ (x+1) \cdot y = 828. $$

Now we need to find two integers. One of them has 8 at the unit place, the other
has 6 at the unit place, and their product is 828.

Let us find all prime factors of 828.

$$ 828 = 2 \times 2 \times 3 \times 3 \times 23. $$

One pair you may find is $$ x + 1 = 138 $$ and $$ y = 6 $$. However, they do
not work for ALL equations.

Another pair is $$ x + 1 = 18 $$ and $$ y = 46 $$. Voila! They work for all
equations. So, $$ x = 17 $$ and $$ y = 46 $$. 

|      | 46   | 47    |
|:----:|:----:|:-----:|
| 17   | 782  | 799   |
| 18   | 828  | 846   |

Finally, the answer is 782 + 799 +828 + 846 = 3255.

</details>

