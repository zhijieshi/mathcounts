---
layout: post
title:  "Number of divisors of an integer"
usemath: true
tag: counting
---

How many positive whole-number divisors does 196 have? 

<details markdown="1"><summary markdown="span">Solutions</summary>

## Solutions

This is a common type of counting problems in MATHCOUNTS.

Find all the prime numbers in 196. 196 should be the prodcut of all the numbers you will have found.

$$ 
196 = 2 \times 98 = 2 \times 2 \times 49 = 2 \times 2 \times 7 \times 7
= 2^2 \times 7^2.
$$

A divior of 196 can only have 2 or 7 as its prime factors. If a number has other prime factors,
it cannot be a divisor of 196. For exmaple, 6 has a prime factor 3 and is not a divisor of 196.
We now calculate how many ways we can use 2 and 7 to build divisors of 196. 

Because the exponent of 2 is 2, there are 3 way's to include 2: do not include
2, include 2 once, or include 2 twice. You cannot include 2 more than twice. For example, 
if you include 2 three times, you will get a number that is a multiple of 8 and it is not 
a divisor of 196. 

The exponent of 7 happens to be 2, too. There are 3 way's to include 7: do not
include 7, include 7 once, or include 7 twice.

Therefore, 196 has $$ 3 \times 3 = 9 $$ positive divisors.

The following table shows all the divisors of 196 and the number of 2's and 7's in them.

|  2   |   7  | divisors |
|------|------|----------|
| 0 | 0 | $$ 2^0 \times 7^0 = 1   $$ |
| 0 | 1 | $$ 2^0 \times 7^1 = 7   $$ |
| 0 | 2 | $$ 2^0 \times 7^2 = 49  $$ |
| 1 | 0 | $$ 2^1 \times 7^0 = 2   $$ |
| 1 | 1 | $$ 2^1 \times 7^1 = 14  $$ |
| 1 | 2 | $$ 2^1 \times 7^2 = 98  $$ |
| 2 | 0 | $$ 2^2 \times 7^0 = 4   $$ |
| 2 | 1 | $$ 2^2 \times 7^1 = 28  $$ |
| 2 | 2 | $$ 2^2 \times 7^2 = 196 $$ |

## More advanced stuff

Any integer $$ n $$ that is grater than 1 (staring from 2) has a prime factor and 
$$ n $$ can be reprsented with a prodcut of prime factors, like  

$$
n = p_1 ^ {e_1} \times p_2 ^ {e_2} \times p_3 ^ {e_3} \ldots 
$$

where $$ p_1, p_2, p_3, \ldots $$ are distinct prime numbers and $$ e_1, e_2, e_3, \ldots $$ are
their exponents. And there is only one (unique) way to do that.  This is called
**unique factorization** of an integer and there is a theorem called **unique
factorization theorem**.

If a number $$ d $$ is a divisor of $$ n $$ and $$ d $$ is larger than 1, any
prime factor of $$ d $$ must be one of $$ p_1, p_2, p_3, \ldots $$. 

To find the number of positive divisors of $$ n $$, you just need to find out the number of ways you can 
pick prime numbers from the set of $$ p_1, p_2, p_3, \ldots $$, under the constraints that you can 
pick $$p_1$$ up to $$e_1$$ times, $$p_2$$ up to $$e_2$$ times, and so on. 

## Solve similar problems

Can you quickly sovle similar problems? 

* How many positive whole-number divisors does 24 have? 

* How many positive whole-number divisors does 1024 have? 

* How many positive whole-number divisors does 1080 have? 

</details>

