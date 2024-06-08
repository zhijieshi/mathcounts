# Inequality Questions

## Set 1

Assume $a$ and $b$ are real numbers. $a > 0$, $b > 0$, and $ab = 1$.

### Q1 
Prove the following inequality.

$$ \frac{1}{\sqrt{1+a}} + \frac{1}{\sqrt{1+b}} \leq \sqrt{2} $$

### Q2 
Prove the following inequality.

$$ \frac{1}{\sqrt{(1+a)(1+2b)}} \leq \sqrt{2} - 1 $$

### Q3 
Prove the following inequality.

$$ \frac{1}{\sqrt{1+a}} + \frac{1}{\sqrt{1+2b}} \leq 2\sqrt{\sqrt{2}-1} $$

### Q4
Prove the following inequality.

$$ \frac{1}{\sqrt{1+a}} + \frac{1}{\sqrt{1+3b}} \leq \sqrt{2(\sqrt{3}-1)} $$

### Q5
Prove the following inequality.

$$ \frac{1}{\sqrt{1+a}} + \frac{1}{\sqrt{1+4b}} \leq \sqrt{\frac{4}{3}} $$

### Q6
Prove the following inequality.

$$ \frac{1}{\sqrt{1+a}} + \frac{1}{\sqrt{1+kb}} \leq \sqrt{\frac{k}{k-1}} $$

where $k \geq 4 $.

## Set 1 Hints

### Q1 

Because $ab = 1$, we have $(1+a)(1+b) = 1+a+b+ab = a + b + 2 = (1+a) + (1+b)$.

Square the left hand side. 

$$ \frac{1}{1+a} + \frac{2}{\sqrt{1+a}\sqrt{1+b}} + \frac{1}{1+b} $$

$$ = \frac{(1+a)+(1+b)}{(1+a)(1+b)} + \frac{2}{\sqrt{1+a}\sqrt{1+b}} $$

$$ = 1 + \frac{2}{\sqrt{1+a}\sqrt{1+b}} $$

$$ = 1 + \frac{2\sqrt{1+a}\sqrt{1+b}}{(1+a)(1+b)} $$

$$ = 1 + \frac{2\sqrt{(1+a)(1+b)}}{(1+a)+(1+b)} $$

$$ = 1 + \frac{\sqrt{(1+a)(1+b)}}{\frac{(1+a)+(1+b)}{2}} $$

$$ \le 1 + 1 = 2 $$

We apply AM-GM on the second term in the $\le$ step.

Since the both sides are non-negative, we can take the square root on both sides and obtain the original inequality.

We can also show the second term is less than 1 as follows.

$$ \frac{2}{\sqrt{1+a}\sqrt{1+b}} = \frac{2}{\sqrt{1+a+b+ab}} $$

$$ = \frac{2}{\sqrt{a+b+2}} \le \frac{2}{\sqrt{2\sqrt{ab}+2}} = \frac{2}{\sqrt{2+2}} = 1$$

### Q2

Start from the LHS. Note that $ab = 1$.

$$ \frac{1}{\sqrt{(1+a)(1+2b)}} = \frac{1}{\sqrt{1 + 2b + a + 2ab}} = \frac{1}{\sqrt{a + \frac{2}{a} + 3}} $$

Apply AM-GM on the two terms that have $a$. 

$$ \frac{1}{\sqrt{a + \frac{2}{a} + 3}} \le \frac{1}{\sqrt{2\sqrt{a\cdot\frac{2}{a}} + 3}} 
= \frac{1}{\sqrt{2\sqrt{2} + 3}} = \frac{1}{\sqrt{2} + 1} = \sqrt{2} - 1 $$

It can be generalized. For $k \ge 2$, 

$$ \frac{1}{\sqrt{(1+a)(1+kb)}} \leq \frac{1}{\sqrt{k} + 1} \quad $$

### Q3

Square both sides. 

$$ LHS^2 = \frac{1}{1+a} + \frac{2}{\sqrt{1+a}\sqrt{1+2b}} + \frac{1}{1+2b}$$

$$ = \frac{(1+a)+(1+2b)}{(1+a)(1+2b)} + \frac{2}{\sqrt{1+a}\sqrt{1+2b}} $$

$$ = \frac{(1+a)+(2ab+2b) - 1}{(1+a)(1+2b)} + \frac{2}{\sqrt{1+a}\sqrt{1+2b}} $$

$$ = 1 - \frac{1}{(1+a)(1+2b)} + \frac{2}{\sqrt{1+a}\sqrt{1+2b}} $$

$$ = 2 - \left( \frac{1}{(1+a)(1+2b)} - \frac{2}{\sqrt{1+a}\sqrt{1+2b}} + 1 \right)$$

$$ = 2 - \left( 1 - \frac{1}{\sqrt{1+a}\sqrt{1+2b}} \right)^2$$

To maximize the expression, we need to minimize the square and then we need to maximize the second term in the parentheses. We know its max value from Q2. 
Therefore,

$$ LHS^2 \le 2 - \left( 1 - (\sqrt{2} - 1) \right)^2 = 2 - ( 2 - \sqrt{2})^2 = 4 (\sqrt{2} - 1)$$

### Q4

Square both sides. 

$$ LHS^2 = \frac{1}{1+a} + \frac{2}{\sqrt{1+a}\sqrt{1+3b}} + \frac{1}{1+3b}$$

$$ = \frac{(1+a)+(1+3b)}{(1+a)(1+3b)} + \frac{2}{\sqrt{1+a}\sqrt{1+3b}} $$

$$ = \frac{(1+a)+(3ab+3b) - 2}{(1+a)(1+3b)} + \frac{2}{\sqrt{1+a}\sqrt{1+3b}} $$

$$ = 1 - \frac{2}{(1+a)(1+3b)} + \frac{2}{\sqrt{1+a}\sqrt{1+3b}} $$

$$ = 1 + \frac{1}{2} - \left( \frac{2}{(1+a)(1+3b)} - \frac{2}{\sqrt{1+a}\sqrt{1+3b}} + \frac{1}{2} \right)$$

$$ = \frac{3}{2} - \left( \frac{\sqrt{2}}{2} - \frac{\sqrt{2}}{\sqrt{1+a}\sqrt{1+3b}} \right)^2$$

$$ = \frac{3}{2} - 2 \left( \frac{1}{2} - \frac{1}{\sqrt{1+a}\sqrt{1+3b}} \right)^2$$

To maximize the expression, we need to minimize the square and then we need to maximize the second term in the parentheses. Its max value, according to Q2, is 

$$ \frac{1}{\sqrt{3} + 1} = \frac{\sqrt{3}-1}{2}$$

Therefore, 

$$ LHS^2 \le \frac{3}{2} - 2 \left( \frac{1}{2} - \frac{\sqrt{3}-1}{2} \right)^2 = \frac{3}{2} - \frac{1}{2} ( 2 - \sqrt{3})^2 = \frac{3}{2} - \frac{1}{2} ( 7 - 4 \sqrt{3}) = 2 \sqrt{3} - 2$$

### Q5

Square both sides. 

$$ LHS^2 = \frac{1}{1+a} + \frac{2}{\sqrt{1+a}\sqrt{1+4b}} + \frac{1}{1+4b}$$

$$ = \frac{(1+a)+(1+4b)}{(1+a)(1+4b)} + \frac{2}{\sqrt{1+a}\sqrt{1+4b}} $$

$$ = \frac{(1+a)+(4ab+4b) - 3}{(1+a)(1+4b)} + \frac{2}{\sqrt{1+a}\sqrt{1+4b}} $$

$$ = 1 - \frac{3}{(1+a)(1+4b)} + \frac{2}{\sqrt{1+a}\sqrt{1+4b}} $$

$$ = 1 + \frac{1}{3} - \left( \frac{3}{(1+a)(1+4b)} - \frac{2}{\sqrt{1+a}\sqrt{1+4b}} + \frac{1}{3} \right)$$

$$ = \frac{4}{3} - \left( \frac{\sqrt{3}}{3} - \frac{\sqrt{3}}{\sqrt{1+a}\sqrt{1+4b}} \right)^2$$

$$ = \frac{4}{3} - 3 \left( \frac{1}{3} - \frac{1}{\sqrt{1+a}\sqrt{1+4b}} \right)^2$$

To maximize the expression, we need to minimize the square and then we need to maximize the second term in the parentheses. Its max value, according to Q2, is 

$$ \frac{1}{\sqrt{4} + 1} = 1/3$$

Therefore, 

$$ LHS^2 \le \frac{4}{3} $$

### Q6

Similar to Q5.
