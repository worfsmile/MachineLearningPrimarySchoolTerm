概率统计

- 估计模型参数

样本空间
事件空间
测量概率
    - $\mathbb{P}(E)\in \R$, $\mathbb{P}\geq 0$
    - $\sum \mathbb{P}(E) = 1$
    - $\mathbb{P}(\bigcup_{i=1}^n E_i) = \sum_{i=1}^n \mathbb{P}(E_i), E_i独立$


prior
posterior 
likelihood 模型产生观测数据的概率
evidence 观测

随机变量是事件到实数的映射

独立的联合高斯分布

同心圆 两个高斯分布协方差矩阵 $\alpha I$

$\mathbf{N}(c+B\mu, B\Sigma B^T)$

jensen不等式
markov不等式
切比雪夫不等式
Hoeffding不等式

机器学习
- frequentist $\frac{m}{n}$ maximization likelihood estimation

- Probability Approximation Correct
Hoeffding Inequality
$\mathbf{P}(|\bar{X}-\mathbf{E}[\bar{X}] | > t)$

- Bayesian
估计分布的参数是满足一个分布
$\mathbf{E}_{\Theta}[g(\Theta) | S] = \int_{\Theta'} g(\theta')p(\theta' | S)d\theta'$
考虑无数个分布模型结合起来的模型
包含先验和后验






