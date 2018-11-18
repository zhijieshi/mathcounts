# Problem

What is the mean of all three-digit positive integers whose digits are in the set {2, 0, 1, 9}?

<details><summary>Solutions</summary>

## Start by listing all numbers 

A straightfoward way is to list all possible 3-dgit numbers that have digits 2, 0, 1, and 9 only, and then calcuate the mean of all the number. 

Since we should consider 3-digit numbers only, the hundreds digit cannot be 0. So all the numbers we list should start with 2, 1, or 9 and they are between 100 and 999.  

Let us start with numbers that have 1 as the hundreds digit. Note that a digit
can appear more than once. For example, 100 should be included because all the
digits in it, 1, 0, and 0, are in the set {2, 0, 1, 9}.

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

There are a total of 16 numbers that have 1 in hundreds place and all digits
are in the set.   Why? It is because there are four choices at the tens place
and four choices at the units place. 

You may continue to list similar the numbers that have 2 or 9 in the hundreds place. 
Each gives you 16 numbers. The pattern in the tens and units places are the same. 
In total you will have 48 3-digit numbers that all their digits are in the set 
{2, 0, 1, 9}. You can then compute their mean.  

However, it will take a while to add up 48 numbers, even if you use a
calculator. Is there a faster way?

## Find the mean

A faster way to find the mean of the 48 numbers is to find the digits in the
mean one by one. 

If you look carefully, you can see that 0, 1, 2, and 9 appear the same number
of times (four times) in the tens and units place. Therefore, the units digit
of the mean is the mean of 0, 1, 2, and 9. It should be 
$ (0+1+2+9) / 4 = 3 $. Think about why yourself.

The tens digit of the mean is the same because 0, 1, 2, and 9 appear the same
number of times. It should be 3. 

The hundreds digit of the mean is a little different becuase 0 is not there.
Each of 1, 2, and 9 appears 16 times. So the hundreds of digit of the mean is

$ ((1 + 2 + 9) * 16) / (3 * 26) =  (1 + 2 + 9) / 3 = 4 $.

Now, we have figured out all the digits in the mean. The answer is 433.

</details>

