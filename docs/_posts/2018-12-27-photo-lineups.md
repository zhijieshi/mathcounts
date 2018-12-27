---
layout: post
title:  "Photo lineups"
usemath: true
tag: counting
---

Ten people of different heights line up for a photo. How many different ways
are there for them to line up in two rows of five people each so that each
person in the back row is taller than the one immediately in front? 
 
<details markdown="1"><summary markdown="span">Solutions</summary>

## Solutions

The following table shows how the ten people can line up for a photo.  *a*,
*b*, *c*, *d*, and *e* are in the back row while *v*, *w*, *x*, *y*, *z* are in
the front row. 

|  back row   | a | b | c | d | e |
|-------------|---|---|---|---|---|
|  front row  | v | w | x | y | z |

The constraint in this problem is each person in the back row is taller than
the one immediately in front. In other words, the person at *a* must be taller
than the one at *v*,  the person at *b* must be taller than the one at *w*, and
so on.  

If there is no constraint, there would be $$ 10! $$ ways. 

The $$ 10! $$ ways can be placed into two sets by comparing two persons
standing at *a* and *v*. 

* A lineup is in $$ S_a $$ if the person at *a* is taller than the one at *v*.  
* A lineup is In $$ S_v $$ if the person at *a* is shorter than the one at *v*.  

$$ S_a $$ has the same number of lineups as $$ S_b $$. For any lineup in
$$ S_a $$, swapping persons at *a* and *v* results in a lineup in $$ S_v $$.
The same is true for any lineups in $$ S_v $$. Swapping persons at *a* and *v* 
in a lineup in $$ S_v $$ changes it to a lineup in $$ S_a $$.

The correct lineups can only be in $$ S_a $$. We have removed half of the lineups.

$$ S_a $$ can be further divided into two sets by comparing two persons
standing at *b* and *w*. 

* A lineup is in $$ S_b $$ if the person at *b* is taller than the one at *w*.  
* A lineup is in $$ S_w $$ if the person at *b* is shorter than the one at *w*.  

The correct lineups can only be $$ S_b $$.

You can see now that every time we enforce the rule on one column, we remove
half of the (remaining) lineups. Since there are 5 columns (with 10 people), the
answer to the question is   

$$ 
\frac{10!}{2^5} = 113,400. 
$$

## Discussions

It is hard to solve this problem by enumarating possible cases.  

If there are more than two rows, the problem can be solved similarly. However,
the number of lineups is not divided by 2 for each column. For exammple, if
there are 3 rows, each column has 3 persons. Among all possible ways 3 people
can line up in that column, only one of the lineups is correct. If you do not
believe it, try to find the number of ways you can arrange three distinct numbers
in ascending order. 

## Solve similar problems

Can you sovle similar problems that have different numbers?

* How may ways can 12 people line up in 2 rows ? 

* How may ways can 9 people line up in 3 rows ? 

</details>

