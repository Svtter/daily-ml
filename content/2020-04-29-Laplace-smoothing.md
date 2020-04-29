Title: Laplace-smoothing
Date: 2020-04-28 22:52
Category: Review
Tags: probability



<!-- write your content here. -->

拉普拉斯平滑，是一种用于处理0概率问题平滑方法。
通过对每个分量+1来计算概率。
例如，某个词语K，在不同类中的观测数量分别是0，10，20，概率为0，$\frac{1}{3}$，$\frac{2}{3}$，对这三个量
进行laplace-smoothing后，结果应该是 $\frac{1}{30+3}$, $\frac{11}{30+3}$, $\frac{21}{30+3}$。