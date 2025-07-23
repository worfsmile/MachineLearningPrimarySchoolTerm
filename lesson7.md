核方法

$$
\kappa(x^{i},x^{j})=\phi(x^{i})^T\phi(x^{j})
$$

核将低纬映射到高维
核方法将映射步骤略去

Represent Theorem

选核: $\Kappa$矩阵半正定

transformer
K V Q
KQ 向量线性组合 内积 相似度


聚类
给两个点, 两个点相似度
给一个点, 和其它点哪个更相似

数据压缩

定义数学语言
$\{\rho^{i[j]}\}^{k}_{i=1}$ which defines whether point i is in cluster j or not.

$\mu^[j] = \frac{\sum^{n}_{i=1}\rho^{i[j]}\vec{x}^{i}}{\sum^{n}_{i=1}\rho^{i[j]}}$

初值迭代
