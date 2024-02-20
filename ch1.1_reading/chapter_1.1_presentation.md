


## Question 10: How many positive integers less than 1000 are multiples of 3, 5, or 7? Explain your answer using the Principle of Inclusion/Exclusion.


### Note this is a VERY Similar to question to the Questino 9, and the steps are similar!

### Remember the property:

### $$|A \cup B \cup C| = |A| + |B| + |C| - |A\cap B| - |A\cap C| - |B\cap C| + |A\cap B\cap C|$$


### 1. Find the floor multiples of 3, 5, 7:
$$ 999 \div 3 = 333$$
$$ 999 \div 5 = 199$$
$$ 999 \div 7 = 142$$

### 2. Find the floor mulltiples of the pairs:
$$ 999 \div (3 \times 5) = 66$$
$$ 999 \div (3 \times 7) = 47$$
$$ 999 \div (5 \times 7 ) = 28$$

### 3. Find the floor multiples of all the numbers:
$$ 999 \div (3 \times 5 \times 7) = 9$$

### So we just put it back in the formula!

$$ 333 + 199 + 142 - 66 - 47 - 28 + 9 = 542$$

## Thus the number of positive integers less than 1000 that are multiple of 3, 5, and 7 is: 542