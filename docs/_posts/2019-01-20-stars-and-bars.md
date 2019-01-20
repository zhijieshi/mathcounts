---
layout: post
title:  "Stars and bars"
usemath: true
---

Prentice has five daughters and ten identical pens. In how many ways can the
pens be distributed among his daughters if two of them, Charlotte and Emily,
must get the same number of pens, and every daughter is not required to get a
pen?

<details markdown="1"><summary markdown="span">Solutions</summary>

Charlotte(C) and Emily(E) have the same number of pens and possible numbers of
pens they each can get is 0, 1, 2, 3, 4, or 5. Let us first consider the case
that C and E get 0 pens. Other cases are similar.

**C and E do not get pens**

In this case, C and E do not get pens (i.e., each gets 0 pens).  Ten remaining
pens are distributed among three other daughters. How many ways are there?

This is a variation of the [stars and bars
problem](https://en.wikipedia.org/wiki/Stars_and_bars_(combinatorics)).
Since a daughter does not have to get a pen (0 is allowed), according to Theorem two on the
page, the number of ways to distribute $$ n $$ indistinguishable pens among $$
d $$ daughters is 

$$ {n + d - 1 \choose d - 1}. $$

So there are $$ { 10 + 3 - 1 \choose 3 - 1} = { 12 \choose 2 } = 66 $$ ways.  

**List all cases**

Now we can consider all cases. This is summarized in the table. 

| Number of pens each C and E gets | Number of ways distributing remaining pens |
|:--------------------------------:|--------------------------------------------|
| 0 | $$ { 10 + 3 - 1 \choose 3 - 1} = { 12 \choose 2 } = \frac{12 \times 11}{2} = 66 $$ |
| 1 | $$ {  8 + 3 - 1 \choose 3 - 1} = { 10 \choose 2 } = \frac{10 \times  9}{2} = 45 $$ |
| 2 | $$ {  6 + 3 - 1 \choose 3 - 1} = {  8 \choose 2 } = \frac{ 8 \times  7}{2} = 28 $$ |
| 3 | $$ {  4 + 3 - 1 \choose 3 - 1} = {  6 \choose 2 } = \frac{ 6 \times  5}{2} = 15 $$ |
| 4 | $$ {  2 + 3 - 1 \choose 3 - 1} = {  4 \choose 2 } = \frac{ 4 \times  3}{2} =  6 $$ |
| 5 | $$ {  0 + 3 - 1 \choose 3 - 1} = {  2 \choose 2 } = \frac{ 2 \times  1}{2} =  1 $$ |

The answer is 66 + 45 + 28 + 15 + 6 + 1 = 161.

## Discussions

It seems you need to know the stars and bars problem to solve this problem. 

If everyone has to get at least one pen, use Theorem one, instead of Theroem
two, on [the page of stars and bars
problem](https://en.wikipedia.org/wiki/Stars_and_bars_(combinatorics)).

</details>

