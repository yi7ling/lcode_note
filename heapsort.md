# 堆排序
概念：（英语：Heapsort）是指利用堆这种数据结构所设计的一种排序算法。堆是一个近似完全二叉树的结构，并同时满足堆的性质：即子节点的键值或索引总是小于（或者大于）它的父节点。

C++中对应的堆结构体：

```cpp
priority_queue<int, vector<int>, greater<int>>
```

题单：
- [2208. 将数组和减半的最少操作次数](https://leetcode.cn/problems/minimum-operations-to-halve-array-sum/description/)
 > 思考：如何解决浮点数产生的误差

- [2406. 将区间分为最少组数](https://leetcode.cn/problems/divide-intervals-into-minimum-number-of-groups/description/) 也可前缀和
