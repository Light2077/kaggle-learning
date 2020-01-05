这周课程的大纲

# 常用免费机器学习竞赛资源

[智能钛机器学习平台 TI-ONE](https://cloud.tencent.com/product/tione)

[百度AI Studio](https://aistudio.baidu.com/aistudio/index)

# 二分类问题

## 什么是二分类

## 二分类评价指标

## 算法

- 逻辑回归
- svm
- 决策树
- 随机森林
- adaboost
- xgboost
- lightgbm
- catboost
- 朴素贝叶斯

# pandas入门

# 逻辑回归原理

## 易混概念

> **损失函数（Loss Function）**是定义在单个样本上的， 算的是一个样本的误差。
> **代价函数（Cost Function ）**是定义在训练集上的， 是**所有**样本误差的平均， 也就是损
> 失函数的平均。
> **目标函数（Object Function）**定义为： 最终需要优化的函数。 等于经验风险+结构风险
> （Cost Function + 正则化项： 保证不过拟合 L1,L2） 。  

## 线性回归

优点：

- 权重$W^T$ 是每个$x$的权重， 通过$W^T$的大小可以看出每个$x$的权重的大小， 可以判断因子的重要性。
- 有很好的解释性  

缺点

- 非线性数据拟合不好  

## 逻辑回归

优点：

- 容易理解和实现， 可以观测样本的概率分数
- 训练速度快
- 由于经过了 sigmoid 函数的映射， 对数据中小噪声的鲁棒性较好
- 不受多重共线性的影响(可通过正则化进行消除)  

缺点：

- 容易欠拟合
- 特征空间很大时效果不好
- 由于sigmoid 函数的特性， 接近 0/1 的两侧概率变化较平缓， 中间概率敏感，波动较大； 导致很多区间特征变量的变化对目标概率的影响没有区分度， 无法确定临界值 

# 字符型特征的处理

- LabelEncoder
- Onehot

# 交叉验证

- Kfold

# 二分类比赛快速实现

[「二分类算法」提供银行精准营销解决方案 ](https://www.kesci.com/home/competition/5c234c6626ba91002bfdfdd3)