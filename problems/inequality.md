# Inequality Questions

## Set 1

Assume $a$ and $b$ are real numbers. $a > 0$, $b > 0$, and $ab = 1$.

### Q1 
Prove the following inequality.

$$ \frac{1}{\sqrt{1+a}} + \frac{1}{\sqrt{1+b}} \leq \sqrt{2} $$

### Q2 
Prove the following inequality.

$$ \frac{\sqrt{a}}{\sqrt{(a+1)(a+2)}} \leq \sqrt{2} - 1 $$

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

### Q2

Start from the LHS. 

$$ LHS = \frac{\sqrt{a}}{\sqrt{a^2+3a+2}} = \frac{1}{\sqrt{a + \frac{2}{a} + 3}} $$

Apply AM-GM on the two terms that have $a$. 

$$ \frac{1}{\sqrt{a + \frac{2}{a} + 3}} \le \frac{1}{\sqrt{2\sqrt{a\cdot\frac{2}{a}} + 3}}$$

Continue to simplify the RHS.

$$ RHS = \frac{1}{\sqrt{2\sqrt{2} + 3}} = \frac{1}{\sqrt{2} + 1} = \sqrt{2} - 1$$

### Q3

Square both sides. 

$$ LHS^2 = \frac{1}{1+a} + \frac{2}{\sqrt{1+a}\sqrt{1+2b}} + \frac{1}{1+2b}$$

$$ = \frac{(1+a)+(1+2b)}{(1+a)(1+2b)} + \frac{2}{\sqrt{1+a}\sqrt{1+2b}} $$

$$ = \frac{(1+a)+(2ab+2b) - 1}{(1+a)(1+2b)} + \frac{2}{\sqrt{1+a}\sqrt{1+2b}} $$

$$ = 1 - \frac{1}{(1+a)(1+2b)} + \frac{2}{\sqrt{1+a}\sqrt{1+2b}} $$

$$ = 2 - \left( \frac{1}{(1+a)(1+2b)} - \frac{2}{\sqrt{1+a}\sqrt{1+2b}} + 1 \right)$$

$$ = 2 - \left( 1 - \frac{1}{\sqrt{1+a}\sqrt{1+2b}} \right)^2$$

To maximize the expression, we need to minimize the square and then we need to maximize the second term in the parentheses. We know its max value from Q2. So the expression is 

$$ \le 2 - \left( 1 - (\sqrt{2} - 1) \right)^2 = 2 - ( 2 - \sqrt{2})^2 = 4 (\sqrt{2} - 1)$$

### Q4

Square both sides. 

$$ LHS^2 = \frac{1}{1+a} + \frac{2}{\sqrt{1+a}\sqrt{1+3b}} + \frac{1}{1+3b}$$

$$ = \frac{(1+a)+(1+3b)}{(1+a)(1+3b)} + \frac{2}{\sqrt{1+a}\sqrt{1+3b}} $$

$$ = \frac{(1+a)+(3ab+3b) - 2}{(1+a)(1+3b)} + \frac{2}{\sqrt{1+a}\sqrt{1+3b}} $$

$$ = 1 - \frac{2}{(1+a)(1+3b)} + \frac{2}{\sqrt{1+a}\sqrt{1+3b}} $$

$$ = 1 + \frac{1}{2} - \left( \frac{2}{(1+a)(1+3b)} - \frac{2}{\sqrt{1+a}\sqrt{1+3b}} + \frac{1}{2} \right)$$

$$ = \frac{3}{2} - \left( \frac{\sqrt{2}}{2} - \frac{\sqrt{2}}{\sqrt{1+a}\sqrt{1+3b}} \right)^2$$

$$ = \frac{3}{2} - 2 \left( \frac{1}{2} - \frac{1}{\sqrt{1+a}\sqrt{1+3b}} \right)^2$$

To maximize the expression, we need to minimize the square and then we need to maximize the second term in the parentheses. So the expression is 

$$ \le \frac{3}{2} - 2 \left( \frac{1}{2} - \frac{\sqrt{3}-1}{2} \right)^2 = \frac{3}{2} - \frac{1}{2} ( 2 - \sqrt{3})^2 = \frac{3}{2} - \frac{1}{2} ( 7 - 4 \sqrt{3}) = 2 \sqrt{3} - 2$$
