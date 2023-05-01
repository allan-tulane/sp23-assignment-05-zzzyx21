# CMPS 2200 Assignment 5
## Answers

**Name:**______Kyra Zhu___________________


Place all written answers from `assignment-05.md` here for easier grading.





- **1a.**
A greedy algorithm could be the largest denomination first and repeat. This greedy algorithm allows us to take as many coins as possible and it would go down to a lower denomiation if the denomination is not used. After several rounds of repetition, we can get the change. This is optimal since the optimal should take as many coins as possible. Suppose the optimal sequence of coins \(coin\) and \(coin_d\) is the coins' number of denomination \(2^i\), when more than 2 of the coin is taken, it will lead to a denomination of \(2^(i+1)\), which is contradict to the condition of being optimal.






- **1b.**
The work and span would be \(O(\log N)\). Since for each smaller coin, \(N\) is reduced by a factor of at least two, while the number of each coin with one multiplication for each denomination.



- **2a.**
If there are 1, 5, and 7 dollar denominations and given $10, a greedy algorithm would return the minimum number of 4 coins: 7,1,1,1. While, the minimum number would use only two coins: 5,5. Therefore, the greedy algorithm is not always optimal.




- **2b.**
The bottom up dynamic programming fills a table with denominations and powers of each denomination in its columns and rows. The work would be \(O(nk)\), where n is the length of the denomination set and k is the highest power for this exchange system. The span would be \(O(n)\), which is the longest path in DAG.




- **3c.**
- in main.py