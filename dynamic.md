# 动态规划

## 从记忆化搜索到递推，入门DP问题

> 三类基础题
> 1. 爬楼梯
> 2. 打家劫舍
> 3. 最大子数组和
>    延申：最小子数组和，循环数组的最大子数组和

题单
- [1191. K 次串联后最大子数组之和 难度1748](https://leetcode.cn/problems/k-concatenation-maximum-sum/description/)

## 网格图（二维）DP问题

主要题型
> 1. 网格图中，计算从左上角到右下角的最大（小）路径和
> 2. 

## 线性DP问题

概念介绍
> LCS：Longest Common Subsequence, 最长公共子序列
> 
> LIS：Longest Increasing Subsequence, 最长递增子序列

题单
- [将字符串翻转到单调递增](https://leetcode.cn/problems/flip-string-to-monotone-increasing/)
- [1713. 得到子序列的最少操作次数](https://leetcode.cn/problems/minimum-operations-to-make-a-subsequence/description/)
-  LCS和LIS问题，https://mp.weixin.qq.com/s?__biz=MzU4NDE3MTEyMA==&mid=2247487814&idx=1&sn=e33023c2d474ff75af83eda1c4d01892


其他线性DP问题
- [3202. 找出有效子序列的最大长度 II](https://leetcode.cn/problems/find-the-maximum-length-of-valid-subsequence-ii/description/)

## 区间DP问题

概念介绍：区间 DP从数组的左右两端不断缩短，求解关于某段下标区间的最优值。 一般定义f[i][j] 表示下标区间 [i,j] 的最优值。

题单
- [516. 最长回文子序列](https://leetcode.cn/problems/longest-palindromic-subsequence/description/)
- [877. 石子游戏](https://leetcode.cn/problems/stone-game/description/)
- [1312. 让字符串成为回文串的最少插入次数](https://leetcode.cn/problems/minimum-insertion-steps-to-make-a-string-palindrome/description/)
