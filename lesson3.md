Calculus

导数

偏导数

Jaccobian矩阵
$R^n \rArr R^n$

Hessian矩阵
$R^n \rArr R$
$R^{n\times m} \rArr R$


正定
负定
求特征值

凸和非凸

凸函数和线性方程组唯一解

凸函数的等价定义
- $f(y) \geq f(x) + \nabla f(x)^T(y-x)$

严格凸

实对称矩阵

半正定
正定

$\underset{x}{max}\underset{y}{min} \phi(x,y) \leq \underset{x}{max}\underset{y}{min} \phi(x,y)$


#### SVM

- 原问题
 $$
    \underset{w,b}{min} ||w||^{2}\\
    s.t.\ y_i(w^{\top}x_i+b) \geq 1, i=1,2,...,m
 $$

- 拉格朗日对偶问题
 $$
    \underset{\alpha}{max}\sum_{i=1}^{m}\alpha_i-\frac{1}{2}\sum_{i,j=1}^{m}\alpha_i\alpha_jy_iy_j(x_i^T x_j) \\
    s.t.\ C \geq \alpha_i\geq 0, i=1,2,...,m \\
    \sum_{i=1}^{m}\alpha_iy_i=0
 $$

对x引入核函数, 一方面将x映射到高维空间, 另一方面加速计算
