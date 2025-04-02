# AP-Experiment-7

## Dynamic Programming
Dynamic Programming (DP) is an optimization technique used to solve complex problems by breaking them into smaller overlapping subproblems, solving each subproblem only once, and storing the results to avoid redundant calculations. It is mainly applied to optimization problems where we need to find the minimum, maximum, shortest, or longest solution. https://www.enjoyalgorithms.com/blog/introduction-to-dynamic-programming

### Key Steps in DP Approach:
- Break the problem into smaller subproblems (like divide-and-conquer).
- Find the optimal solution for each subproblem.
- Store results of subproblems (memoization) to avoid recomputation.
- Reuse stored results to efficiently compute the final solution.

### Types of DP Approaches:
1. Top-Down (Memoization) – Uses recursion with caching to store intermediate results.
2. Bottom-Up (Tabulation) – Uses an iterative approach to build solutions from smaller subproblems.

### Example:
Find out the nth Fibonacci number. Fibonacci number of a position is equal to the summation of the previous two numbers Fibonacci. So Fibonacci of fib(n) is fib(n-1) + fib(n-1). 
Fibonacci of 6 is:
![image](https://github.com/user-attachments/assets/f039feec-5850-4411-9659-36695c41e08b)

Here we divide the problem into several subproblems and conquer the result of the subproblems and finally get the optimal solution. But there is a problem that is here we are calculating a subproblem more than once. Here we calculate fib(4) twice, fib(3) three-time, fib(2) five times, fib(1) three times. Instead of calculating more than once we will store the solution of the subproblem and will use it for the next time.

## DP vs. Greedy:
- DP finds all possible solutions and picks the optimal one.
- Greedy makes local optimal choices but doesn’t always guarantee the global optimum.
- DP is time-consuming compared to greedy algorithms but guarantees the optimal solution if it exists.

# 🔢 Dynamic Programming Problems

## Dynamic Programming (Basic Problems)

| Difficulty | Problem | Type | Link | Company |
|------------|---------|------|------|---------|
| Easy | Climbing Stairs | CW | [🔗 Link](https://leetcode.com/problems/climbing-stairs/) | Adobe |
| Easy | Best Time to Buy and Sell a Stock | CW | [🔗 Link](https://leetcode.com/problems/best-time-to-buy-and-sell-a-stock/) | Adobe |
| Easy | Maximum Subarray | CW | [🔗 Link](https://leetcode.com/problems/maximum-subarray/) | Uber |
| Easy | House Robber | HW | [🔗 Link](https://leetcode.com/problems/house-robber/) | Amazon |

##Dynamic Programming (Intermediate Problems)

| Difficulty | Problem | Type | Link | Company |
|------------|---------|------|------|---------|
| Medium | Jump Game | HW | [🔗 Link](https://leetcode.com/problems/jump-game/) | LinkedIn |
| Medium | Unique Paths | CW | [🔗 Link](https://leetcode.com/problems/unique-paths/) | Netflix |
| Medium | Coin Change | CW | [🔗 Link](https://leetcode.com/problems/coin-change/) | Netflix |
| Medium | Longest Increasing Subsequence | CW | [🔗 Link](https://leetcode.com/problems/longest-increasing-subsequence/) | Apple |

## Dynamic Programming (Advanced Problems)

| Difficulty | Problem | Type | Link | Company |
|------------|---------|------|------|---------|
| Hard | Maximum Product Subarray | HW | [🔗 Link](https://leetcode.com/problems/maximum-product-subarray/) | Adobe |
| Hard | Decode Ways | CW | [🔗 Link](https://leetcode.com/problems/decode-ways/) | Netflix |
| Hard | Best Time to Buy and Sell a Stock with Cooldown | CW | [🔗 Link](https://leetcode.com/problems/best-time-to-buy-and-sell-a-stock-with-cooldown/) | Twitter |

##  Dynamic Programming (More Challenges)

| Difficulty | Problem | Type | Link | Company |
|------------|---------|------|------|---------|
| Hard | Perfect Squares | HW | [🔗 Link](https://leetcode.com/problems/perfect-squares/) | Amazon |
| Hard | Word Break | CW | [🔗 Link](https://leetcode.com/problems/word-break/) | Adobe |
| Hard | Word Break 2 | CW | [🔗 Link](https://leetcode.com/problems/word-break-2/) | Adobe |

### 📌 **Legend**
- **CW**: **Classwork**
- **HW**: **Homework**
