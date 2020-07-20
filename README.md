# DP-2

## Problem1(https://leetcode.com/problems/paint-house/)
A list of house and cost of paint is given. any two consecutive houses cnanot be with same color. Find minimum cost
to color the house.
Ex:

    house= [1,2,3]
    paint_cost= {red:3
          orange: 4
          yellow: 2}
    solution: min cost = 7

## Problem2 (https://leetcode.com/problems/coin-change-2/)

You are given coins of different denominations and a total amount of money. Write a function to compute the number of combinations that make up that amount. You may assume that you have infinite number of each kind of coin.

Example 1:

    Input: amount = 5, coins = [1, 2, 5]
    Output: 4
    Explanation: there are four ways to make up the amount:
    5=5
    5=2+2+1
    5=2+1+1+1
    5=1+1+1+1+1

Example 2:

    Input: amount = 3, coins = [2]
    Output: 0
    Explanation: the amount of 3 cannot be made up just with coins of 2.