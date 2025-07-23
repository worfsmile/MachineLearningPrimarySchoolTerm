UCL Visual Computing Lab

光线穿过每一个点的"能量"

高斯泼洒将"能量"看作一个分布

高斯混合模型
$$
G~N(\mu, \Sigma)\\
P = \sum_{i=1}^K \pi_i G_i(\mu_i, \Sigma_i)\\
\sum_{i=1}^K \pi_i = 1\\
$$

拟合光场
(颜色, 位置, 协方差矩阵, 透明度)

权重加和

初始化一堆高斯
射线上加权

零散的图片标签构建3D

几何重建
机器人定位


高斯表达能力(给足够量的高斯可以表达任何分布)

优化过程
splatting

3D高斯2D有解析表达
优化过程, adaptive density

scooping

Langevin
Hamiltonian Monte Carlo

Deep Blending
Tanks
Temples
Mip-NeRF360

PSNR 信噪比
SSIM 结构相似度
LPIPS "人"感觉像不像

组件数量1.1M左右

抓反光点
