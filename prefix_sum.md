# 前缀和

## 差分数组

### 概念

**一维差分数组**

背景：假设给你一个数组 nums ，先对区间 [a,b] 中每个元素加 3 ，再对区间 [c,d] 每个元素减 5 …… ，这样非常频繁的区间修改，常规的做法可以一个个计算。
但是，频繁对数组的一段区间进行增加或减去同一个值，如果一个个去操作，效率会很差。

所以我们可以使用差分数组，**差分数组就是原始数组相邻元素之间的差**。

差分数组d[n]定义：d[i] = nums[i] - nums[i-1], 其中d[0] = nums[0]。
以下图为例

![alt text](image/prefix1.png)

我们可以看到，原数组就是差分数组的前缀和。

```cpp
nums[0] = d[0];
nums[3] = d[0] + d[1] + d[2] + d[3];
```

有了差分数组，如果对区间 [a,b] 每个元素加 3 ，不需要在一个个操作，只需要在两端修改即可，如下图所示。

```cpp
d[a] += 3;
d[b+1] -= 3;
```
![alt text](image/prefix2.png)


### 题单
- [2536. 子矩阵元素加 1](https://leetcode.cn/problems/increment-submatrices-by-one/description/)
- [304. 二维区域和检索 - 矩阵不可变](https://leetcode.cn/problems/range-sum-query-2d-immutable/description/)
- [2132. 用邮票贴满网格图](https://leetcode.cn/problems/stamping-the-grid/description/)
