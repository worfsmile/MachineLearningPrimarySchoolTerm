3D Studengt Splatting and Scooping 贝叶斯网络，高斯分布(不可观测)获得数据

$P(D, \mu, \sigma)$

$P(\mu, \sigma|D)$



1. 线性空间

   1. 八条
   2. 欧氏空间
   3. 坐标系
   4. 子空间
      1. 维度关系
         1. 降维
         2. 升维
      2. 仿射空间
         1. 不必要0向量
         2. 支撑点

2. 矩阵

   1. $[Ax]_i = \sum^m_{j=1}A_{ij}x_j$

3. 线性变换

   1. $f(x+y) = f(x) + f(y)$

   2. $f(\alpha x) = \alpha f(x)$

   3. $$
      \begin{matrix}
      A_{11} A_{12}\\
      ...\\
      A_{n1} A_{n2}
      \end{matrix}
      ·
      \begin{matrix}
      x_{1}\\x_{2}
      \end{matrix}
      =
      \begin{matrix}
      A_{11} x_1\\
      ...\\
      A_{n1} x_1
      \end{matrix}
      +
      \begin{matrix}
      A_{12} x_2\\
      ...\\
      A_{n2} x_2
      \end{matrix}
      $$

   4. 函数点乘，和向量点乘

   5. $A(B(x))$

      1. $$
         [Cx]_i = \sum^m_{j=1}C_{ij}x_j\\
         = \sum^{m}_{ik}\sum^{n}_{kj}A_{ik}B_{kj}x_j
         $$

4. null space

   1. 变换为0
   2. $\{x|AX=0\}$

5. 矩阵的秩

   1. $rank(AB)\leq min(rank(A), rank(B))$
   2. 零空间的秩+对应矩阵的行或列秩=行数或列数
   3. 正交补

6. 最大列和，频谱

7. 相似度和距离

8. 测度，一定能比较

   1. 正定性
   2. 对称性
   3. 线性
   4. 三角不等式

9. 内积和正交

   1. 正交矩阵

   2. 投影

      1. 正交投影

      2. $$
         \underset{\lambda}{argmin}||x-B\lambda||
         $$

10. 数值上意义相同的解在现实上不一样$Ax = b$

11. Determinants (体积)

    1. $det(I)=1$
    2. $det(\alpha A) = \alpha^{n}det(A)$

12. 共轭梯度下降

13. 不满秩

14. 对称正定阵

15. 