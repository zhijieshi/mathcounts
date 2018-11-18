# Problem

What is the mean of all three-digit positive integers whose digits are in the set {2, 0, 1, 9}?

<details><summary>Solutions</summary>

## Start by listing all numbers 

A straightfoward way is to list all possible 3-dgit numbers that have only digits 2, 0, 1, and 9. All the numbers are between 100 and 999.  

The hundreds digit can only be 2, 1, or 9. Let us start from 1.

| Hundreds | Tens | Units |
|----------|------|-------|
| 1 | 0 | 0|
| 1 | 0 | 1|
| 1 | 0 | 2|
| 1 | 0 | 9|
| 1 | 1 | 0|
| 1 | 1 | 1|
| 1 | 1 | 2|
| 1 | 1 | 9|
| 1 | 2 | 0|
| 1 | 2 | 1|
| 1 | 2 | 2|
| 1 | 2 | 9|
| 1 | 9 | 0|
| 1 | 9 | 1|
| 1 | 9 | 2|
| 1 | 9 | 9|

These are all 3-dgits numbers that start from 1. There are a total of 16 
numbers. 

You may continue to list all the numbers that start with 2, and all the numbers that start with 9. Each case gives you 16 numbers. And in total you will get 48 numbers. You can compute the sum and the divide it by 48 to get the mean.  

It will take a while even if you use a calculator. Is there a faster way?

</details>

