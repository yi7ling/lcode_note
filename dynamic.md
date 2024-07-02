# 动态规划

## 线性DP问题

概念介绍
> LCS：Longest Common Subsequence, 最长公共子序列
> 
> LIS：Longest Increasing Subsequence, 最长递增子序列

题单
- [将字符串翻转到单调递增](https://leetcode.cn/problems/flip-string-to-monotone-increasing/)
- [1713. 得到子序列的最少操作次数](https://leetcode.cn/problems/minimum-operations-to-make-a-subsequence/description/)
  > LCS和LIS问题，https://mp.weixin.qq.com/s?__biz=MzU4NDE3MTEyMA==&mid=2247487814&idx=1&sn=e33023c2d474ff75af83eda1c4d01892

## 区间DP问题

概念介绍：区间 DP从数组的左右两端不断缩短，求解关于某段下标区间的最优值。 一般定义f[i][j] 表示下标区间 [i,j] 的最优值。

题单
- [516. 最长回文子序列](https://leetcode.cn/problems/longest-palindromic-subsequence/description/)
