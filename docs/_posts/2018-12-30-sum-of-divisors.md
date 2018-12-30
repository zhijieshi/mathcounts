---
layout: post
title:  "Sum of divisors of an integer"
usemath: true
tag: counting
---

What is the sum of all positive whole-number divisors of 720?

<details markdown="1"><summary markdown="span">Solutions</summary>

## Solutions

### Step 1

Find all the prime numbers in 720. 720 should be the prodcut of all the numbers you will have found.

$$ 
720 = 72 \times 10 = 8 \times 9 \times 2 \times 5 = 2^4 \times 3^2 \times 5.
$$

### Step 2
We calculate a number for each prime factor. 

For 2, we calculate:

$$ 
1 + 2^1 + 2^2 + 2^3 + 2^4 = 31.
$$

You may have noticed that this is the sum of first 5 terms in a geometric
sequence. The sequence starts from 1. Multiplying a term by 2 (the prime factor
wer are considering now) gives us the next term. The last term we include is
$$ 2^4 $$, which is what we found in Step 1.

For 3, we calculate:

$$ 
1 + 3^1 + 3^2 = 13.
$$

Similarly, this is the sum of first 3 terms of a geometric squence. 
The last term $$ 3^2 $$ is what we found in Step 1.

For 5, we calculate:

$$ 
1 + 5^1 = 6.
$$

### Step 3
Now we multiply together the three numbers we have calculated in Step 2:

$$ 
31 \times 13 \times 6 = 2418.
$$

The sum of all positive whole-number divisors of 720 is 2418.

## Discussions

As we have learned in problems of counting the number of divisors, any integer
$$ n $$ that is grater than 1 (staring from 2) can be reprsented with a prodcut
of prime factors, like  

$$
n = p_1 ^ {e_1} \times p_2 ^ {e_2} \times p_3 ^ {e_3} \ldots 
$$

where $$ p_1, p_2, p_3, \ldots $$ are distinct prime numbers and $$ e_1, e_2, e_3, \ldots $$ are
their exponents. And there is only one (unique) way to do that.  

The sum of all divisors of $$ n $$ can be calculated as:

$$
(1 + p_1 + p_1^2 + \ldots + p_1^{e_1}) \cdot
(1 + p_2 + p_2^2 + \ldots + p_2^{e_2}) \cdot
(1 + p_3 + p_3^2 + \ldots + p_3^{e_3}) \ldots
$$

Although the proof is not simple, [here is a more detailed explanation](https://www.math.upenn.edu/~deturck/m170/wk3/lecture/sumdiv.html). 

Also, the formula for calculating the sum of first $$ n $$ terms of a geometric sequence 
can be handy if a prime factor has a large exponent.  

$$
(1 + p + p^2 + \ldots + p^{n}) = \frac{p^{n+1} - 1}{p - 1}.
$$

## Solve similar problems

Can you quickly sovle similar problems? 

* What is the sum of all positive whole-number divisors of 1,000?

* What is the sum of all positive whole-number divisors of $$ 2^{16} - 1 $$ ?

</details>

