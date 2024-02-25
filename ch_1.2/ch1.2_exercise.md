## 1.
A. Just complete $2^6 =  64$ - This is because there are 2 choices for each place of the original set, so it would be $2^6$

B. Do the equation $2^3 = 8$ - This is similar to first answer!

C. Since there are 8 subsets that do not contain an odd number from $2^3$ then we can substract the entire subset combinations by the even ones: $2^6 - 2^3 = 64 - 8 = 56$

D. Ther are $2^3$ that contain only even numbers, and there are $2^3$ that are only odd numbers. Then we subtract that from 40 to get 24 subsets.

### 2. 
A. Compute the $(^6_4) = 720/48  = 15$

B. 3 subsets from $(^3_1)$ whic his due to the fact that we chose the 3 remaining elemts of the set, and since it has to contain 1 even number the cardinality is 1 

C. 15 subsets because in the subsets with the cardinality of 4 must already have an odd number anyways

D. 3 subsets because there are 3 odd numbers in the set anyways, so the we can just to the same thing like in part b  - $(^3_1)$

#### 3. 
A. Very similar to the begining, because once again there is a yes/no options for each value so just $2^9 = 512$

B. We know that the total length is 9, and since we are looking for 5 elements, that will be our carindality so - $(^9_5) = 126$

C. The set is now 4 choices (4 even numbers) and we have to do the same yes/no analysis which would be $2^4 = 16$

D. Since everything is discrete, we can just do the addition of the length 9 and the even numbers in the set which are 2,4,6,8 so by doing that "binomial addition" we would get 256.

#### 4. 

A. Because the first substring would be 101, then there are 6 free elements which could be 0 or 1 so: $2^6 = 64$

B. Becaues the substring 101 has the weight of 2 - we know that there are 3 ones in the next 6 elements, and so we can just do the binomial coefficient $(^6_3) = 20$

C. We have to do the inclusion/exclusion principle: $|A \cup B| = |A| + |B| - |A\cap B|$ - BUT HOW?? - Well we know that there are 64 strings with start with 101, and to find the amt of strings that end with 11, we know there are 7 free slots so we jsut $2^7 = 128$. Then we combine the two, so 5 out of the 9 slots are taken up so it would be $2^4 = 16$. We then $128 + 64 - 16 = 176$!

D. So we know that that from part B it is 20 from doing the binomial coefficient. We do the same process to the bit string that end with 11, so it would be $(^7_3) = 35$. Again with the principle of exclusion/exclusion we have found our |A| and |B|. Since we need both 11 and 101, that means that there is only one spot for that additional weight of 1, so we do $(^4_1) = 4$. We then do $20 + 35 - 4 = 51$!

