## Question 4: hexadecimal We usually write numbers in decimal form (or base 10), meaning numbers are composed using 10 different “digits." {0, 1, ...., 9} Sometimes though it is useful to write numbers hexadecimal or base 16. Now there are 16 distinct digits that can be used to form numbers: {0, 1, ...., 9, A, B, C, D, E, F} . So for example, a 3 digit hexadecimal number might be 2B8

## Part A: How many 2-digit hexadecimals are there in which the first digit is E or F? Explain your answer in terms of the additive principle (using either events or sets).
### There are 16 ways where the first digit of the 2-digit hexidecimal is E (E.g: E1, E2, EA) and 16 ways where the first digit can be F (E.g: F1, F2, FA), so we just add these two numbers: ***32***


### Part B: Explain why your answer to the previous part is correct in terms of the multiplicative principle (using either events or sets). Why do both the additive and multiplicative principles give you the same answer?

### Remember, that there are 16 combinations for the first digit, but this time know that there is 2 different digits. So we multiple 16 and 2, and get 32.

### This use of the multiplicative property is the same as the addiditive property because the steps are exactly the same!

### Part C: How many 3-digit hexadecimals start with a letter (A-F) and end with a numeral (0-9)? Explain.
### In this question, there are 6 different combinations for the first digit (A-F), 16 combinations for the second digit (0-F), and 10 combinations for the last digit (0-10). So then we just multiply: 
$$ 6 \times 16 \times 10 = 960$$

### Part D: How many 3-digit hexadecimals start with a letter (A-F) or end with a numeral (0-9) (or both)? Explain.

### To solve this equation behin with the combinations that the first digit has, which is 6 (the letters) and multiply that with the rest of teh combinations:

$$6 \times 16 \times 16  = 1536$$

### Do the same process but for the last digit:

 $$16 \times 16 \times 10 = 2560$$

### The issue is that now there is some overlap, and to remove that just remember to remove that overlap by:

$$10 \times 16 \times 6 = 960$$

### Finally, we add the 1536 and 2560, but then subtract the overlap of 960:

$$1536 + 2560 - 960 = 3136$$




## Question 10: How many positive integers less than 1000 are multiples of 3, 5, or 7? Explain your answer using the Principle of Inclusion/Exclusion.


### Note this is a VERY Similar to question to the Questino 9, and the steps are similar!

### Remember the property:

$$|A \cup B \cup C| = |A| + |B| + |C| - |A\cap B| - |A\cap C| - |B\cap C| + |A\cap B\cap C|$$


## 1. Find the floor multiples of 3, 5, 7:
$$999 \div 3 = 333$$
$$ 
999 \div 5 = 199
$$
$$ 
999 \div 7 = 142
$$

### 2. Find the floor mulltiples of the pairs:
 $$ 999 \div (3 \times 5) = 66$$
 $$ 999 \div (3 \times 7) = 47$$
 $$ 999 \div (5 \times 7 ) = 28$$

### 3. Find the floor multiples of all the numbers:
 $$ 999 \div (3 \times 5 \times 7) = 9$$

 So we just put it back in the formula!

$$ 333 + 199 + 142 - 66 - 47 - 28 + 9 = 542$$

## Thus the number of positive integers less than 1000 that are multiple of 3, 5, and 7 is: 542