# 矩阵论复习

- [矩阵论复习](#矩阵论复习)
- [1. 相似变换](#1-相似变换)
	- [1.1. Jordan（若当）标准型（考填空题）](#11-jordan若当标准型考填空题)
	- [1.2. Hamiltion-Cayley（哈密顿－凯莱）定理](#12-hamiltion-cayley哈密顿凯莱定理)
	- [1.3. 向量的内积(内积空间)](#13-向量的内积内积空间)
- [2. 范数理论](#2-范数理论)
	- [2.1. 向量范数](#21-向量范数)
	- [2.2. 矩阵范数（考大题）](#22-矩阵范数考大题)
		- [2.2.1. 导出范数](#221-导出范数)
		- [2.2.2. 范数具体算法（考填空题）](#222-范数具体算法考填空题)
	- [2.3. 范数应用-谱半径、条件数](#23-范数应用-谱半径条件数)
		- [2.3.1. 谱半径：（考填空题）](#231-谱半径考填空题)
		- [2.3.2. 条件数：](#232-条件数)
- [3. 矩阵分析](#3-矩阵分析)
	- [3.1. 矩阵序列](#31-矩阵序列)
	- [3.2. 矩阵级数](#32-矩阵级数)
	- [3.3. 矩阵函数](#33-矩阵函数)
		- [3.3.1. **矩阵函数**的**矩阵幂级数**展开式 （考填空题）](#331-矩阵函数的矩阵幂级数展开式-考填空题)
		- [3.3.2. 矩阵函数数值计算（考大题）](#332-矩阵函数数值计算考大题)
			- [3.3.2.1. 利用hamiltion-cayley定理](#3321-利用hamiltion-cayley定理)
			- [3.3.2.2. 利用相似对角阵](#3322-利用相似对角阵)
			- [3.3.2.3. 利用若当标准型（填空题）](#3323-利用若当标准型填空题)
			- [3.3.2.4. ★待定系数法（考大题）](#3324-待定系数法考大题)
		- [3.3.3. 矩阵函数的性质](#333-矩阵函数的性质)
	- [3.4. 矩阵微积分](#34-矩阵微积分)
		- [3.4.1. 函数矩阵的微分和积分](#341-函数矩阵的微分和积分)
		- [3.4.2. 数量函数对矩阵变量的导数](#342-数量函数对矩阵变量的导数)
		- [3.4.3. 矩阵值函数对矩阵变量的导数](#343-矩阵值函数对矩阵变量的导数)
	- [3.5. 应用：求解 一阶线性常系数微分方程组。（考大题）](#35-应用求解-一阶线性常系数微分方程组考大题)
- [4. 矩阵分解](#4-矩阵分解)
	- [4.1. QR分解（考大题）](#41-qr分解考大题)
	- [4.2. Hermite标准形](#42-hermite标准形)
	- [4.3. 满秩分解](#43-满秩分解)
- [5. 特征值的估计与表示](#5-特征值的估计与表示)
	- [5.1. 特征值界的估计](#51-特征值界的估计)
	- [5.2. 盖尔圆－**Gerschgorin定理**（考大题）](#52-盖尔圆gerschgorin定理考大题)
	- [5.3. Hermite矩阵特征值的表示](#53-hermite矩阵特征值的表示)
- [6. 广义逆矩阵](#6-广义逆矩阵)
	- [6.1. Moore-Penrose逆,定义](#61-moore-penrose逆定义)
	- [6.2. {1}逆](#62-1逆)
	- [6.3. $A^+$在解线性方程组中的应用（考大题）](#63-a在解线性方程组中的应用考大题)
- [7. 矩阵的直积](#7-矩阵的直积)
	- [7.1. 直积：](#71-直积)
	- [7.2. 拉直：](#72-拉直)
	- [7.3. Lyapunov李亚谱诺夫问题$AX+XB=F$。（考大题）](#73-lyapunov李亚谱诺夫问题axxbf考大题)
- [8. 线性空间](#8-线性空间)
	- [8.1. 数域与映射](#81-数域与映射)
	- [8.2. 线性空间的定义与基本性质](#82-线性空间的定义与基本性质)
	- [8.3. 基、维数与坐标](#83-基维数与坐标)
		- [8.3.1. 基与维数](#831-基与维数)
		- [8.3.2. 坐标](#832-坐标)
		- [8.3.3. ★基变换与坐标变换公式。（考大题）](#833-基变换与坐标变换公式考大题)
	- [8.4. 线性子空间](#84-线性子空间)
		- [8.4.1. 子空间的交$\cap$、和$+$、直和$\oplus$（考大题）](#841-子空间的交cap和直和oplus考大题)
	- [8.5. 线性变换](#85-线性变换)
		- [8.5.1. 线性变换的值域与核（考大题）](#851-线性变换的值域与核考大题)
	- [8.6. 线性变换的矩阵表示](#86-线性变换的矩阵表示)
		- [8.6.1. ★线性变换矩阵的化简（考大题）](#861-线性变换矩阵的化简考大题)
	- [8.7. 欧式空间(内积空间)](#87-欧式空间内积空间)
		- [8.7.1. 欧氏空间的概念](#871-欧氏空间的概念)
		- [8.7.2. 标准正交基](#872-标准正交基)
	- [8.8. 正交变换、对称变换、投影变换](#88-正交变换对称变换投影变换)
		- [8.8.1. 正交变换](#881-正交变换)
		- [8.8.2. 对称变换](#882-对称变换)
		- [8.8.3. 投影变换](#883-投影变换)
<!-- # 1. 矩阵论 -->
#  1. 相似变换
$$Ax =  \lambda x，\lambda：特征值，x：特征向量$$
ps:根据统计，往年考试中，特征值分布在$[-4,4]$之间，且$0,1,2,3$出现的最多。有时特征多项式是三次多项式，还是挺难拆的 ，直接猜即可。
*  定理1.1: 设$\lambda_i$是$A\in C^{m *n}$特征值的$r_i$重特征值（称$r_i$为特征值$\lambda_i$的**代数重数**），对应$\lambda_i$有$s_i$个特征向量（称$s_i$为特征值$\lambda_i$的**几何重数**），则$1 \leq s_i \leq r_i$。
ps：求若当标准型里，$s_i$即是若当块的个数。$s_i＝n-rank(\lambda I-A)=rank(null(A-\lambda I))$
虽然有时特征向量的个数<特征值的个数。其实还有**广义特征向量**。
* 定理1.2：矩阵A的特征值多项式、矩阵A的多项式相关。自己看书去吧。
## 1.1. Jordan（若当）标准型（考填空题）
* 求法：
  - 方法一：特征向量法（考填空题）
  - 法二：初等变换法（Smith标准型）
  - 法三：行列式因子法。（ps：不会不会，大D1，小D3啥的）

*  定理 1.12：对于$r_i$阶Jordan 块:

$$\boldsymbol{J}_{i}=\left(\begin{array}{cccc}
\lambda_{i} & 1 & & \\
& \lambda_{i} & \ddots & \\
& & \ddots & 1 \\
& & & \lambda_{i}
\end{array}\right)_{r_{i} \times r_{i}}$$


其$k$次幂为。（每一行均是()二项式展开。）（考填空题）


$$
\boldsymbol{J}_{i}^{k}=\left(\begin{array}{ccccc}
\lambda_{i}^{k} & \mathrm{C}_{k}^{1} \lambda_{i}^{k-1} & \mathrm{C}_{k}^{2} \lambda_{i}^{k-2} & \cdots & \mathrm{C}_{k}^{r_{i}-1} \lambda_{i}^{k-r_{i}+1} \\
& \lambda_{i}^{k} & \mathrm{C}_{k}^{1} \lambda_{i}^{k-1} & \cdots & \mathrm{C}_{k}^{r_{i}-2} \lambda_{i}^{k-r_{i}+2} \\
& & & \ddots & \vdots \\
& & & \ddots & \mathrm{C}_{k}^{1} \lambda_{i}^{k-1} \\
& & & & \lambda_{i}^{k}
\end{array}\right)
$$

* 求解一阶线性常系数微分方程组。
!!!
## 1.2. Hamiltion-Cayley（哈密顿－凯莱）定理
矩阵是其特征多项式的根。
- 最小多项式:$m_A(\lambda)$:\
设矩阵$A\in C^{n\times n}$，在A的零化多项式中，次数最低的首一多项式称为最小多项式。
  - 相似矩阵有相同的最小多项式
  - $$m_A(\lambda)=(\lambda-\lambda_1)^{m_1}(\lambda-\lambda_2)^{m_2}\cdots(\lambda-\lambda_n)^{m_n}$$
  - 其中$m_i$是$A$的Jordan标准型$J$中含$\lambda_i$的Jordan块的最高阶数。
## 1.3. 向量的内积(内积空间)
也叫点积。x、y是实向量时：
$$(x,y)=x \cdot y= \sum_{k=i}^n  x_i y_i$$
x、y是复向量时：对于y要**共轭**。
$$(x,y)=x \cdot y= \sum_{k=i}^n  x_i \bar y_i$$
* 复向量x,y内积的交换率$(x,y)=\overline{(y,x)}$、数乘$(\lambda x,y)=\lambda (x,y),(x,\lambda y)=\bar \lambda (x,y)$、分配率、非负性
* 两个重要不等式
	* 三角不等式
	对于所有向量u，有
	$$|| u+v|| \leq ||u|| + ||v||$$
	* Cauchy－Schwarz、柯西－施瓦茨不等式
	$(x,y)(y,x)=|(x,y)|^2 \leq (x,x)(y,y)$ 
	也即
	$$|<u,v>| \leq  ||u|| \cdot ||v|| $$
	证法：v的模 $\leq$ v在**u生成的子空间W**上的**投影**的模。(线性代数及其应用 P379)
	 两向量的**和的模**小于**模的和**。
对向量x和y应用该不等式得
$$(\sum_{k=i}^n  |x_i| |y_i|)^2 \leq (\sum_{k=i}^n  |x_i|^2)(\sum_{k=i}^n  |y_i|^2) $$
* Schmidt（格拉姆－施密特）正交化方法。
…

# 2. 范数理论
## 2.1. 向量范数
1. 非负性
2. 齐次性(数乘)
3. 满足三角不等式

## 2.2. 矩阵范数（考大题）
1. 非负性
2. 齐次性(数乘)
3. 满足三角不等式
4. 相容性：对任意矩阵$A,B\in C^{m*n}$，都有$||AB||\leq||A||*||B||$
5. 矩阵范数m与某一向量范数v的相容性：$||Ax||_v\leq||A||_m||x||_v$
eg:
### 2.2.1. 导出范数
- 定理2.9 已知$C^n$上的向量范数$\|\cdot\|_v$，对任意$A\in C^{n\times n}$，规定
$$
\|\boldsymbol{A}\|=\max _{x \neq 0} \frac{\|\boldsymbol{A} \boldsymbol{x}\|_{\mathrm{v}}}{\|\boldsymbol{x}\|_{\mathrm{v}}}\left(\|\boldsymbol{A}\|=\max _{\|\boldsymbol{x}\|_{\mathrm{v}}=1}\|\boldsymbol{A} \boldsymbol{x}\|_{\mathrm{v}}\right)
$$
则$\|\cdot\|_v$是与该向量范数相容的矩阵范数，且$\|I\|=1$。


### 2.2.2. 范数具体算法（考填空题）

| 向量范数                                       | 矩阵范数（从属）            | 矩阵范数（推导、$\|I_n\|==1$）            |
| ---------------------------------------------- | --------------------------- | ----------------------------------------- |
| 1范数：$\|x\|_1=\sum_{k=1}^n\|x_k\|$           | m1范数,=模的和              | 1范数、列和最大                           |
| 2、F范数：$\|x\|_F=\sqrt{\sum_{k=1}^n\|x_k\|}$ | F范数， ＝$\sqrt{tr(A^HA)}$ | 2范数、谱范数 = $\sqrt{A^HA的最大特征值}$ |
| $\infty$范数：$\|x\|_1=\max_{k=1}^n\|x_k\|$    | M范数,＝max(m,n)*模最大值   | 无穷范数、行和范数                        |

- G范数、几何平均范数：
$$
\| \boldsymbol{A}\|_{G}=\sqrt{m n} \cdot \max _{i, j}\left|a_{i j}\right|
$$
## 2.3. 范数应用-谱半径、条件数
### 2.3.1. 谱半径：（考填空题）
* 最大的特征值。
* 当A是正规矩阵时，$\rho(A)=\|A\|_2$
* 当谱半径小于1时，可用迭代法求线性方程的解。——《数值分析》
* 谱半径小于任一矩阵范数。$\rho(A) \le \|A\|$ 
### 2.3.2. 条件数： 
* $cond(A)＝\|A\|*\|A^{-1}\|$
* 条件数大时，称A对于解线性方程组是病态的。受扰动后误差很大。条件数小时，是良态。（hillbert矩阵，特别病态。可做检测。）

# 3. 矩阵分析
## 3.1. 矩阵序列
- 矩阵序列定义
矩阵序列就是$n*m$个数列
- 收敛性定义
$$\lim_{k\to\infty}A^{(k)}=A ,或,  A^{(k)}\to A(k\to \infty)$$
- ★收敛判断方法
   $$\lim_{k\to\infty} \|A^{(k)}- A\|=0,其中\|*\|是任意一种矩阵范数$$
- 收敛性质
  - $\lim_{k\to \infty}(\alpha A^{(k)}+\beta B^{(k)})=\alpha A+\beta B$，这个是交换律和结合律吗？2333
  - 数乘
  - 可逆
- 收敛矩阵的定义：在矩阵序列中，最常见的是一个方阵的幂构成的序列。
$$设A\in C^{n\times n},\lim_{k\to\infty}A^{(k)}=\mathbf{0}$$
- ★收敛矩阵的判断方法
	1. 谱半径$\rho(A)<1$
	2. 任一矩阵范数<1
## 3.2. 矩阵级数
- 矩阵级数定义：无穷矩阵序列的和
$$\sum_{k=0}^{\infty}A^{(k)} =  A^{(0)} + A^{(1)} + ... +A^{(k)} + ... $$

称下式为部分和
$$S^{(N)}=\sum_{k=0}^{n}A^{(k)}$$

- 收敛性定义：
部分和构成一个矩阵序列${S^{(N)}}$，如果其收敛且有极限$\mathbf{S}$，即$\lim_{k\to\infty}S^{(k)}=\mathbf{S}$
则矩阵级数收敛，而且有和$\mathbf{S}$.而且
$$\mathbf{S} =\sum_{k=0}^{\infty}A^{(k)}$$
- 收敛矩阵判断方法。

- 绝对收敛，其部分绝对值的和收敛。
- 矩阵幂级数
$$S=\sum_{k=1}^{\infty}a_kA^k$$
- ★幂级数收敛性判断方法（同时研究$n^2$个数项级数的敛散性太麻烦，考虑到矩阵幂级数是复变量$z$的幂级数的推广……）

设复变量幂级数$S=\sum_{k=1}^{\infty}a_k z^k$的收敛半径为$r$，$A\in  C^{n\times n}$,则
  1. 当$\rho(A)<r$时，矩阵幂级数 绝对收敛。
  2. 当$\rho(A)>r$时，矩阵幂级数 发散。
- ★**Neumann级数**的收敛

设 $A\in C^{n\times n}$,矩阵幂级数$S=\sum_{k=1}^{\infty}A^k$（称为Neumann级数），收敛的充要条件是$\rho(A)<r$，且收敛时，其和为$(I-A)^{-1}$

## 3.3. 矩阵函数
- （矩阵函数是以矩阵为变量，且取值为矩阵的一类函数）
- 函数的幂级数展开式-定义：设幂级数$\sum_{k=1}^{\infty}a_k z^k$的收敛半径为$r$，且当$|z|<r$时，幂级数收敛于函数$f(z)$，即
$$f(z)=\sum_{k=1}^{\infty}a_k z^k, (|z|<r)$$
  - 函数的幂级数展开式：
$$
\begin{array}{l}
\mathrm{e}^{z}=\sum_{k=0}^{+\infty} \frac{z^{k}}{k !} & (r=+\infty) \\
\sin z=\sum_{k=0}^{+\infty} \frac{(-1)^{k}}{(2 k+1) !} z^{2 k+1} & (r=+\infty) \\
\cos z=\sum_{k=0}^{+\infty} \frac{(-1)^{k}}{(2 k) !} z^{2 k} & (r=+\infty) \\
(1-z)^{-1}=\sum_{k=0}^{+\infty} z^{k}  \quad & (r=1) \\
\ln (1+z)=\sum_{k=0}^{+\infty} \frac{(-1)^{k}}{k+1} z^{k+1} & (r=1)
\end{array}
$$
### 3.3.1. **矩阵函数**的**矩阵幂级数**展开式 （考填空题）
- 定义：设幂级数$\sum_{k=1}^{\infty}a_k z^k$的收敛半径为$r$，如果矩阵$A\in C^{n\times n}$且满足$\rho(A)<r$，则称收敛的矩阵幂级数$\sum_{k=1}^{\infty}a_k A^k$的和为**矩阵函数**，记为$f(A)$，即
$$f(A)=\sum_{k=1}^{\infty}a_k A^k, (\rho(A)<r)$$
  - 矩阵函数如下： 
$$
\begin{array}{l}
\mathrm{e}^{A}=\sum_{k=0}^{+\infty} \frac{A^{k}}{k !} & (r=+\infty) \\
\sin A=\sum_{k=0}^{+\infty} \frac{(-1)^{k}}{(2 k+1) !} A^{2 k+1} & (r=+\infty) \\
\cos A=\sum_{k=0}^{+\infty} \frac{(-1)^{k}}{(2 k) !} A^{2 k} & (r=+\infty) \\
(1-A)^{-1}=\sum_{k=0}^{+\infty} A^{k}  \quad & (r=1) \\
\ln (1+A)=\sum_{k=0}^{+\infty} \frac{(-1)^{k}}{k+1} A^{k+1} & (r=1)
\end{array}
$$
称$e^A,sinA,cosA$为矩阵指数函数、矩阵正弦函数、矩阵余弦函数。\
如果把矩阵函数$f(A)$的变元$A$变成$At$，其中$t$为参数，则得到含参数的矩阵函数。
$$f(At)=\sum_{k=1}^{\infty}a_k (At)^k, (\rho(A)<r)$$
### 3.3.2. 矩阵函数数值计算（考大题）
#### 3.3.2.1. 利用hamiltion-cayley定理
（快速求$A^n$）
#### 3.3.2.2. 利用相似对角阵
$$f(\mathbf{A}t)=\mathbf{P}(f(\lambda_1t),f(\lambda_2t),\cdots,f(\lambda_nt))\mathbf{P}^{-1}$$
#### 3.3.2.3. 利用若当标准型（填空题）
$$
f(\mathbf{J}_it)=\left. \left(\begin{array}{cccc}
f(\lambda) & \frac{t}{1!} f^{\prime}(\lambda) & \cdots & \frac{t^{r_{i}-1}}{\left(r_{i}-1\right) !} f^{\left(r_{i}-1\right)}(\lambda) \\
& f(\lambda) & \ddots & \vdots \\
& & \ddots & \frac{t}{1 !} f^{\prime}(\lambda) \\
& & & f(\lambda)
\end{array}\right)\right|_{\lambda=\lambda_{i} t}
$$
$$
f(\mathbf{A}t)=\mathbf{P}
\left(\begin{array}{cccc}
f(\mathbf{J}_st) & & \\
 & \ddots & \\
& & f(\mathbf{J}_st)
\end{array}\right)
\mathbf{P}^{-1}
$$
#### 3.3.2.4. ★待定系数法（考大题）
1. 求矩阵$A$的特征多项式
2. 设$r(\lambda)=b_{n-1}\lambda^{n-1}+\cdots+b_{1}\lambda+b_0$
，根据下式（哈密顿凯莱定理，每个特征值的$n-1$阶导数相同)（其中$l=0,1,\cdots,r^i-1.i=1,2,\cdots,s$），可以计算各个$b_i$的值
$$对于f(At),\qquad r^{(l)}(\lambda_i)=t^lf^{(l)}(\lambda_it)$$
$$对于f(A),\qquad r^{(l)}(\lambda_i)=f^{(l)}(\lambda_i)$$
3. 计算$f(A)=r(A)=b_{n-1}A^{n-1}+\cdots+b_{1}A+b_0I$

ps：如果求得矩阵A的最小多项式，且其次数低于A的特征多项式的次数，则可以简化计算。
### 3.3.3. 矩阵函数的性质
常用的矩阵函数$e^A,sinA,cosA$，它们有些性质与普通函数相同，但是由于矩阵乘法不满足交换律，所以有一些不同。
……

## 3.4. 矩阵微积分
- （函数矩阵：以函数为元素的矩阵）
### 3.4.1. 函数矩阵的微分和积分
定义：有$n\times m$个函数都是以$t$为变量的函数。记为$a_{ij}(t)，其中(i=1,2,\cdots,m;j=1,2,\cdots,n)$。排列成矩阵$A(t)=(a_{ij})_{m\times n}$。若$t\in [a,b]$，则称$A(t)$是**定义在$[a,b]$上**的。

ps：只是$n\times m$个函数，排列成矩阵的样子。

若每个$a_{ij}(t)$都在定义域上连续、可微分、可积分，则称相应的函数矩阵是连续、可微分、可积分的。规定其导数、积分分别为：
$$导数:A'(t)=(a_{ij}'(t))_{m\times n}\qquad  积分:\int_{a}^{b}A(t) \mathrm{~d}t=(\int_{a}^{b}a(t) \mathrm{~d}t)_{m\times n}$$
- e.g.1:求矩阵函数
$$
\boldsymbol{A}(t)=\left(\begin{array}{ccc}
\sin t & \cos t & t \\
2^{t} & \mathrm{e}^{t} & t^{2} \\
0 & 1 & t^{3}
\end{array}\right) 
$$
的导数。\
解：
$$
\frac{\mathrm{d}}{\mathrm{d} t} \boldsymbol{A}(t)=\left(\begin{array}{ccc}
\cos t & -\sin t & 1 \\
2^{t} \ln 2 & \mathrm{e}^{t} & 2 t \\
0 & 0 & 3 t^{2}
\end{array}\right)
$$
- e.g.2:设A是可逆矩阵，则$\int_{0}^{1} \mathrm{e}^{A t}\mathrm{~d} t = ?$\
解：
$$
\begin{aligned}
\int_{0}^{1} \mathrm{e}^{A t} \mathrm{~d} t &=A^{-1} \int_{0}^{1} A \mathrm{e}^{A t} \mathrm{~d} t=A^{-1} \int_{0}^{1} \frac{\mathrm{d}}{\mathrm{d} t} \mathrm{e}^{A t} \mathrm{~d} t \\
&=A^{-1}\left(\mathrm{e}^{A t}\right)_{0}^{1}=A^{-1}\left(\mathrm{e}^{A}-I\right)
\end{aligned}
$$
ps:对于积分还是有点愣。。
- tips:
	- $e^0=1,e^{\mathbf{0}}=I$.是单位向量。而不是1。
	- $(e^{\lambda t})'=te^{\lambda t}$。此处是对$\lambda$求导，而不是对t求导。
### 3.4.2. 数量函数对矩阵变量的导数
定义：是$m\times n$个，自变量各不相同的函数，组成的矩阵$f(\mathbf{X})$。其变量是一个矩阵$\mathbf{X}=(x_{ij})_{m\times n}$

特别地，数量函数对**向量变量**的导数，即为**梯度向量**，记为$gradf$
- e.g.1：已知$f(x)=a^Tx=x^Ta$,其中$a=(a_1,a_2,\cdots,a_n)^T$是已知向量。$x=(x_1,x_2,\cdots,x_n)^T$是向量变量，求$\frac{df}{dx}$

解：$f(x)=a^Tx=a_1x_1+a_2x_2+\cdots+a_nx_n$

因为$\frac{\partial f}{\partial x_{1}}=a_i (i=1,2,\cdots,n)$

所以
$$
\frac{\mathrm{d} f}{\mathrm{~d} \boldsymbol{x}}=\left(\frac{\partial f}{\partial x_{1}}, \cdots, \frac{\partial f}{\partial x_{n}}\right)^{\mathrm{T}}=\left(a_{1}, \cdots, a_{n}\right)^{\mathrm{T}}=\boldsymbol{a}
$$

- e.g.2:已知
$$
\boldsymbol{X}=\left(\begin{array}{lll}
t_{1} & t_{2} & t_{3} \\
t_{4} & t_{5} & t_{6}
\end{array}\right), f(\boldsymbol{X})=t_{1} t_{6}+t_{2} t_{5}+t_{3} t_{4}
$$
求$\frac{\mathrm{d} f}{\mathrm{~d} X}$

解：
$$
\frac{\mathrm{d} f}{\mathrm{~d} X}=\left(\begin{array}{lll}
\frac{\partial f}{\partial t_{1}} & \frac{\partial f}{\partial t_{2}} & \frac{\partial f}{\partial t_{3}} \\
\frac{\partial f}{\partial t_{4}} & \frac{\partial f}{\partial t_{5}} & \frac{\partial f}{\partial t_{6}}
\end{array}\right)=\left(\begin{array}{lll}
t_{6} & t_{5} & t_{4} \\
t_{3} & t_{2} & t_{1}
\end{array}\right)
$$
### 3.4.3. 矩阵值函数对矩阵变量的导数
其结果为$(ms)\times (nt)$阶矩阵。

作为特殊情形，这一定义包括了向量值函数对于向量变量的导数，向量值函数对于矩阵变量的导数，矩阵值函数对于向量变量的导数等等。


## 3.5. 应用：求解 一阶线性常系数微分方程组。（考大题）
- 问题定义：
  
满足初始条件
$$x_i(t_0)=c_i \qquad (i=1,2,\cdots,n)$$
记
$$
\begin{array}{c}
\boldsymbol{A}=\left(a_{i j}\right)_{n \times n}, \quad \boldsymbol{c}=\left(c_{1}, c_{2}, \cdots, c_{n}\right)^{\mathrm{T}} \\
\boldsymbol{x}(t)=\left(x_{1}(t), x_{2}(t), \cdots, x_{n}(t)\right)^{\mathrm{T}}, \quad f(t)=\left(f_{1}(t), f_{2}(t), \cdots, f_{n}(t)\right)^{\mathrm{T}}
\end{array}
$$
则微分方程组可写为
$$
\left\{\begin{array}{l}
\frac{\mathrm{d} \boldsymbol{x}(t)}{\mathrm{d} t}=\boldsymbol{A} \boldsymbol{x}(t)+\boldsymbol{f}(t) \\
\boldsymbol{x}\left(t_{0}\right)=\boldsymbol{c}
\end{array}\right.
$$

- 解法：
因为
$$
\begin{aligned}
\frac{\mathrm{d}}{\mathrm{d} t}\left(\mathrm{e}^{-\boldsymbol{A} \boldsymbol{t}} \boldsymbol{x}(t)\right) &=\mathrm{e}^{-\boldsymbol{A}t}(-\boldsymbol{A}) \boldsymbol{x}(t)+\mathrm{e}^{-\boldsymbol{A}t} \frac{\mathrm{d} \boldsymbol{x}(t)}{\mathrm{d} t} \\
&=\mathrm{e}^{-\boldsymbol{A}t}\left(\frac{\mathrm{d} \boldsymbol{x}(t)}{\mathrm{d} t}-\boldsymbol{A} \boldsymbol{x}(t)\right)=\mathrm{e}^{-\boldsymbol{A}t} \boldsymbol{f}(t)
\end{aligned}
$$
将上式两边在$[t_0,t]$上积分，得到
$$
\int_{t_{0}}^{t} \frac{\mathrm{d}}{\mathrm{d} \tau}\left(\mathrm{e}^{-A \tau} \boldsymbol{x}(\tau)\right) \mathrm{d} \tau=\int_{t_{0}}^{t} \mathrm{e}^{-\mathrm{Ar}} \boldsymbol{f}(\tau) \mathrm{d} \tau 
$$
即
$$
\mathrm{e}^{-\boldsymbol{A} \boldsymbol{t}} \boldsymbol{x}(t)-\mathrm{e}^{-\boldsymbol{A}t_{0}} \boldsymbol{x}\left(t_{0}\right)=\int_{t_{0}}^{t} \mathrm{e}^{-A \tau} \boldsymbol{f}(\tau) \mathrm{d} \tau
$$
于是微分方程组的解为：
$$
\boldsymbol{x}(t)=\mathrm{e}^{\boldsymbol{A}\left(t-t_{0}\right)} \boldsymbol{c}+\mathrm{e}^{\boldsymbol{A}t} \int_{t_{0}}^{t} \mathrm{e}^{-\boldsymbol{A} \tau} \boldsymbol{f}(\tau) \mathrm{d} \tau
$$
ps:一般，考试中$e^{-A\tau}b(\tau)=常数向量$，在常数上求积分比较简单，不然还要分布积分就恶心🤮了。
# 4. 矩阵分解
## 4.1. QR分解（考大题）
* household 变换－初等反射阵
$H=I-2uu^H,u\in C^n是单位向量$
e.g:
使得$x=(1,2,2)^T$与$e_1$同方向。
取$a=\|x\|_2=3$，计算
$$u=\frac{x-ae_1}{\|x-ae_1\|_2} =  \frac{1}{\sqrt3}(-1,1,1)^T$$
于是$H=I-2uu^T$.

* Givens变换－初等旋转阵
平面解析几何中，顺时针旋转$\theta$ 的变换为
ps:所有正交基的变换，放在一起。可得变换矩阵
x轴单位向量
$$x:(1,0)^T\to x':(cos\theta,-sin\theta)^T,$$
y轴单位向量
$$y:(0,1)^T\to y':(sin\theta,cos\theta)^T$$
$$concatenate(x',  y') \to
\left(\begin{array}{cccc}
cos\theta & sin\theta \\
-sin\theta & cos\theta
\end{array} \right)
$$
$$
\boldsymbol{T}_{pq}=\left(\begin{array}{cccc}
1 &  & & & & & \\
 & \ddots &  &  & & &  \\
 &  & \bar c & & \bar s & &\\
  &  & & \ddots& & & \\
   &  & -s & & c & &\\
    &  & & & & \ddots &  \\
  &  & & & & & 1 \\
 \end{array}\right)_{r_{i} \times r_{i}}
$$
e.g 4.5:用Givens变换使得下列向量与$e_1$同方向。
(1) $x=(1,2,2)^T$
取
$$c_1=\frac{x_1}{\sqrt{x_1^2+x_2^2}}=1/\sqrt5, s_1=\frac{x_2}{\sqrt{x_1^2+x_2^2}}=2/\sqrt5$$
则$T_{12}$
	* 求QR分解方法。
$$A=QR$$
$A\in C^{n*n}$，$Q$：n阶酉矩阵，$R$：n阶上三角矩阵
		- 法1： Household矩阵
将矩阵A 按列分块为$A=(a_1,a_2,...,a_n)$，存在$H_1$，使得，$H_1a_1=a_1e_1$，于是
$$H_1A=\left(\begin{array}{cccc}
a_1 & * & ... & * \\
0 & & & \\
\vdots & & B_{n-1} & \\
0 &&&
\end{array}\right)
$$
其中$B_{n-1}\, C^{(n-1)(n-1)}$。再将B按列分块，取$\bar H_2$，使得$\bar H_2b_2=a_2e_2$.则
$$H_2 = 
\left(\begin{array}{cccc}
1 & 0^T\\
0 & \bar H^T
\end{array}\right)$$
依次类推，第n－1步后。$H_{n-1}***H_2H_1A=R$
	- 法1：givens矩阵法
$$T_{n-1,n} \dots T_{2n}\dots T_{23},T_{1n}\dots T_{12} A=R$$
则，
$$Q=T_{12}^H \dots T_{1n}^H,T_{23}^H \dots T_{2n}^H,T_{n-1,n}^H$$

## 4.2. Hermite标准形
(ps：满秩分解，预备知识。)\
对于$A\in C_r^{m*n}$
* Hermite标准形：行阶梯最简形$H$。
* 存在m阶初等行变换矩阵S。使得$S(A,I)=(H,S)$
* 存在n阶置换矩阵P(eg：$(e_1,e_3,e_2,e_4)$)。使得
$$SAP=
\left(\begin{array}{cccc}
I_r & K \\
0 & 0
\end{array}\right)
$$
## 4.3. 满秩分解
* 长方阵$A\in C_r^{m*n}$，存在$F\in C_r^{m*r}$和$A\in G_r^{r*n}$.使得
$$ A=FG$$
ps:满秩分解不唯一。
* 求法：用**列主元高斯消去法**[不然出现分数，求A+很麻烦]，做初等行变换，求$A$的Hermite形矩阵$H$。$H$的前$r$个非零行为$G$，$H$的$r$列**主元列**对应的$A$的列组合为$F$。（p113，定理4.18）



# 5. 特征值的估计与表示
## 5.1. 特征值界的估计
…
## 5.2. 盖尔圆－**Gerschgorin定理**（考大题）
设$A=(a_{ij})_{n*n}$，记
$$R_i = \sum_{j=1, j \neq i}^n |a_{ij}|$$
称复平面上的圆域
$$G_i = \{z| |z-a_{ij} \leq R_i, z \in \mathbb{C}|\} , (i=1,2,..,n)$$
为矩阵A的第i个盖尔圆。称$R_i$为其半径。
- 特征值的隔离
如果某一个$G_1$圆很小，其余圆很大，且重叠。可取$D=diag(2, 1,1,...,1)$。则$B=DAD^{-1}$。B的特征值，有可能被隔离开。
ps：
	- 是求逆$D^{-1}$，而不是转置$D^T$，刚好是$D$的倒数。
	- 第i行被放大，第i列被缩小
	- 实矩阵A的**复特征值**必成对共轭出现！
## 5.3. Hermite矩阵特征值的表示
将n阶Hermite矩阵的n个特征值从大到小排序为

$$\lambda_1 \geq \lambda_2 \geq \dots \geq \lambda_n$$
- Rayleigh商、瑞丽商：
$$R(X)=\frac{x^HAx}{x^Hx}$$
则$\lambda_1=max R(x), \lambda_n=minR(x)$
- 广义特征值
	- 广义特征值
A、B都是Hermite矩阵。B还是正定矩。若满足 $Ax=\lambda Bx$。则称$\lambda$为A相对于B的广义特征值。$x$为属于$\lambda$的广义特征向量。
	- 按B正交：$x^HBy=0$
	- 广义Rayleigh商。$R_B(x)=\frac{x^HAx}{x^HBx}$


# 6. 广义逆矩阵
## 6.1. Moore-Penrose逆,定义
设$A\in C^{m*n}$，若$X\in C^{n*m}$。满足下列四个Penrose方程。
	- $AXA=A$,
	- $XAX=X$,
	- $(AX)^H=AX$,
	- $(XA)^H=XA$
## 6.2. {1}逆
- 求法：初等行变换为Hermite行阶梯标准型 
$$SAP=
\left(\begin{array}{cccc}
I_r & K \\
0 & 0
\end{array}\right)
$$
则
$$A^{(1)}=S
\left(\begin{array}{cccc}
I_r & K \\
0 & L			
\end{array}\right)P, (L \in  C^{(n-r)*(m-r)},L任意 。L＝0时为A^{(1,2)})
$$
## 6.3. $A^+$在解线性方程组中的应用（考大题）
- 求法2：利用满秩分解
$A=FG$
$A^+=G^H(GG^H)^{-1}(F^HF)^{-1}F^H$
	- 在求解$Ax=b$中的应用：
	1. $Ax=b$有解 $\Leftrightarrow AA^+b=b$
	2. $x=A^+b+(I-A^+A)y (y\in C^n任意)$是相容方程组的**通解**，或是矛盾方程组的**全部最小二乘解**。
	(ps：当$A^+A=I$，即$rank(A)=n$时，解唯一)
	4. $x_0=A^+b$是相容方程组的**唯一极小范数解**，或是矛盾方程组的**唯一极小范数最小二乘解**

# 7. 矩阵的直积
## 7.1. 直积：
- 直积性质6：逆是正序的$(A\otimes B)^{-1}=A^{-1}\otimes B^{-1}$
- 性质7：
  - $A\otimes B$的全体特征值是$\lambda_i\mu_i$
  - $A\otimes I+I\otimes B^{-1}$的特征值是$\lambda_i+\mu_i$
		
e.g.:若
$$A=\left(\begin{array}{cccc}
1&2\\
3&4
\end{array}\right), B=(2,-1)$$
则
$$
\begin{array}{l}
\boldsymbol{A} \otimes \boldsymbol{B}=\left(\begin{array}{cc}
\boldsymbol{B} & 2 \boldsymbol{B} \\
3 \boldsymbol{B} & 4 \boldsymbol{B}
\end{array}\right)=\left(\begin{array}{llll}
2 & -1 & 4 & -2 \\
6 & -3 & 8 & -4
\end{array}\right) \\
\boldsymbol{B} \otimes \boldsymbol{A}=(2 \boldsymbol{A} \quad-\boldsymbol{A})=\left(\begin{array}{lrrr}
2 & 4 & -1 & -2 \\
6 & 8 & -3 & -4
\end{array}\right)
\end{array}
$$
## 7.2. 拉直：
e.g.:若
$$A=\left(\begin{array}{cccc}
1&2&3\\
4&5&6
\end{array}\right)$$
则 
$$\overrightarrow{A}=(1,2,3,4,5,6)^T$$

## 7.3. Lyapunov李亚谱诺夫问题$AX+XB=F$。（考大题）
拉直和直积的关系式：矩阵方程可转化为等价的线性方程组。 
$$
\overrightarrow{A X B}=\left(A \otimes B^{\mathrm{T}}\right) \overrightarrow{X}=\overrightarrow{F}
$$

e.g.:
解矩阵方程$AX+XB=F$,其中
$$
\boldsymbol{A}=\left(\begin{array}{rr}
1 & -1 \\
0 & 2
\end{array}\right), \boldsymbol{B}=\left(\begin{array}{rr}
-3 & 4 \\
1 & 0
\end{array}\right), \boldsymbol{F}=\left(\begin{array}{rr}
1 & 3 \\
-2 & 2
\end{array}\right) ;
$$
利用拉直和直积的关系式可得： 
$$
\Leftrightarrow
\left(\begin{array}{rrrr}
-2 & 1 & -1 & 0 \\
4 & 1 & 0 & -1 \\
0 & 0 & -1 & 1 \\
0 & 0 & 4 & 2
\end{array}\right)\left(\begin{array}{l}
x_{1} \\
x_{2} \\
x_{3} \\
x_{4}
\end{array}\right)=\left(\begin{array}{r}
1 \\
3 \\
-2 \\
2
\end{array}\right),
$$

# 8. 线性空间
## 8.1. 数域与映射
- 定义8.1:数域，设$K$是至少含一个非零数的数集。如果$K$中任意两个数 的和、差、积、商(除数不为0)任是$K$中的数，则称$K$是一个**数域**
	-  eg:有理数域(最小数域)、实数域、复数域是数域。 自然数集合不是数域 
- 定义8.2:映射，设$S$与$S'$ 是两个集合。如果按照某一规则$\sigma$，使得每个$\alpha\in S$都有一个确定 的元素$\beta\in S'$与之对应，则称$\sigma$为集合$S$到$S'$的 映射，记为 $\sigma:S\to S'$；$\alpha$和$\beta$的对应关系记为$\sigma(\alpha)=\beta$。
	- 在映射$\sigma$下，$\alpha,\beta,S,R(\sigma)\in S'$为原像，像，定义域，值域。
	- 单射(一对一的,eg:$x=\sqrt{y},✓;x^2=y,×$)，满射(映上的,$R(\sigma)=S'$)，双射(一一对应)。
## 8.2. 线性空间的定义与基本性质
- 定义8.4:线性空间的定义，设$V$是一个非空集合，$K$是一个数域，在$V$上的元素之间定义了名为"加法"的运算，在$K$和$V$的元素之间定义了名为"数乘"的运算。如果$V$对于这两种运算是封闭的，且满足下面八条运算律(设$\alpha,\beta,\gamma\in V,k,l\in K$)
	1. 加法交换律,$\alpha+\beta=\beta+\alpha$
	2. 加法结合律,$(\alpha+\beta)+\gamma=\alpha+(\beta+\gamma)$
	3. 存在**零元**$\theta$,使$\alpha+\theta=\alpha$
	4. 存在负元，
	5. $1\alpha=\alpha$
	6. 数乘结合律,$k(l\alpha)=(lk)\alpha$
	7. 数乘分配率,$(k+l)\alpha=k\alpha+l\alpha$
	8. 数因子分配率,$k(\alpha+\beta)=k\alpha+k\beta$
	- 则称$V$为数域$K$上的线性空间。线性空间的元素也称为向量。
ps:考试出题判断时。一般5，6，7不符合的多。
- 线性表示、线性相关、极大无关组。
## 8.3. 基、维数与坐标 
### 8.3.1. 基与维数
- 定义8.7在线性空间$V$中，如果存在$n$个元素$\alpha_1,\alpha_2,...,\alpha_n$满足：
	1. $\alpha_1,\alpha_2,...,\alpha_n$线性无关，
	2. $V$中任一元素都可由$\alpha_1,\alpha_2,...,\alpha_n$线性表示， 
	- 则称$a_1,a_2,...,a_n$是$V$的一个**基**，称n为$V$的维数，记为$dimV$,
	- 维数为$n$的线性空间称为**n维线性空间**，记为$V^n$,也称为**有限维线性空间**
	- 若对于预先指定的任何正整数$N$，在$V$中总能找到找到$N$个线性无关的元素，则称$V$为**无限维线性空间**
	- 如果$V$中没有线性无关的元素，则规定其维数为0。
### 8.3.2. 坐标
- 定义8.8:设$V$是数域$K$上的n维线性空间，$\alpha_1,\alpha_2,...,\alpha_n$是$V$的一个基，则V中任意元$a$可由基$\alpha_1,\alpha_2,...,\alpha_n$唯一线性表示为
$$\alpha=x_1\alpha_1+x_2\alpha_2+...+x_n\alpha_n,(x_1,x_2,...,x_n\in K).$$
称$x_1,x_2,...,x_n$为$\alpha$在基$\alpha_1,\alpha_2,...,\alpha_n$下的**坐标**，记为$(x_1,x_2,...,x_n)^T$。
  
### 8.3.3. ★基变换与坐标变换公式。（考大题）
- 定义8.9:设$V$是数域$K$上的n维线性空间，$\alpha_1,\alpha_2,...,\alpha_n$，和$\beta_1,\beta_2,...,\beta_n$是$V$的两个基，且表示为
$$
\left\{\begin{array}{c}
\boldsymbol{\beta}_{1}=c_{11} \boldsymbol{\alpha}_{1}+c_{21} \boldsymbol{\alpha}_{2}+\cdots+c_{n 1} \boldsymbol{\alpha}_{n} \\
\boldsymbol{\beta}_{2}=c_{12} \boldsymbol{\alpha}_{1}+c_{22} \boldsymbol{\alpha}_{2}+\cdots+c_{n 2} \boldsymbol{\alpha}_{n} \\
\ldots \ldots \ldots \ldots \\
\boldsymbol{\beta}_{n}=c_{1 n} \boldsymbol{\alpha}_{1}+c_{2 n} \boldsymbol{\alpha}_{2}+\cdots+c_{m} \boldsymbol{\alpha}_{n}
\end{array}\right.
$$
或者按矩阵乘法规则形式写成
$$
\left(\boldsymbol{\beta}_{1}, \boldsymbol{\beta}_{2}, \cdots, \boldsymbol{\beta}_{n}\right)=\left(\boldsymbol{\alpha}_{1}, \boldsymbol{\alpha}_{2}, \cdots, \boldsymbol{\alpha}_{n}\right)\left(\begin{array}{cccc}
c_{11} & c_{12} & \cdots & c_{1 n} \\
c_{21} & c_{22} & \cdots & c_{2 n} \\
\vdots & \vdots & & \vdots \\
c_{n 1} & c_{n 2} & \cdots & c_{m n}
\end{array}\right)
$$
则称矩阵$C=(c_{ij})_{n\times n}$为由基$\alpha_1,\alpha_2,...,\alpha_n$到$\beta_1,\beta_2,...,\beta_n$的过度矩阵，又称上述两个公式为**基变换公式**。
	- 定理8.2: 设由线性空间$V^n$的基$\alpha_1,\alpha_2,...,\alpha_n$到基$\beta_1,\beta_2,...,\beta_n$的过渡矩阵为$C$，又设$a\in V^n$在基$\alpha_1,\alpha_2,...,\alpha_n$的坐标为$x=(x_1,x_2,...,x_n)^T$，在基$\beta_1,\beta_2,...,\beta_n$的坐标为$y=(y_1,y_2,...,y_n)^T$,则
	1. $C$是可逆的。
	2. $x=Cy$或者$y=C^{-1}x$。为**坐标变换公式**

## 8.4. 线性子空间
- $V$的线性子空间$W$:包含零元，对于加法和数乘是风隔壁的。
- 生成子空间:由$V$中任取m个元素，线性组合而成的子空间。记作$span\{\alpha_1,\alpha_2,...,\alpha_n\}$。
	- 与矩阵$A$有关的四个空间。列空间(值域)，零空间(核)，行空间，左零空间。
### 8.4.1. 子空间的交$\cap$、和$+$、直和$\oplus$（考大题）
- 都是子空间。
- ★以下四个命题等价
	1. 和是直和
	2. 零元素的分解是唯一的，即由$\theta=\alpha_1+\alpha_2 \Rightarrow \alpha_1=\alpha_2=\theta$
	3. $W_1\cap W_2=\{\theta\}$.交集为空
	4. $dim(W_1+W_2)=dimW_1+dimW_2$

## 8.5. 线性变换
- 定义8.14:设$V$是数域$K$上的线性空间，$T$是$V$的一个变换。如果任意$\alpha,\beta\in V$和$k\in K$都有
$$T(\alpha+\beta)=T(\alpha)+T(\beta)，T(k\alpha)=kT(\alpha)$$
则称$T$是$V$的一个**线性变换**。
- 线性变换的乘积$ST(\alpha)=S(T(\alpha))$
- 线性变换是可逆的$T^{-1}$
### 8.5.1. 线性变换的值域与核（考大题）
## 8.6. 线性变换的矩阵表示
- 定义8.17 设$V$是数域$K$上的n维线性空间，$\alpha_1,\alpha_2,...,\alpha_n$是$V$的一个基，$T$是$V$的线性变换。基到像$\beta_1,\beta_2,...,\beta_n=T(\alpha_1),T(\alpha_2),...,T(\alpha_n)$可唯一地由基$\alpha_1,\alpha_2,...,\alpha_n$线性表示:
$$
\left\{\begin{array}{c}
\boldsymbol{\beta}_{1}=T(\alpha_1)=a_{11} \boldsymbol{\alpha}_{1}+a_{21} \boldsymbol{\alpha}_{2}+\cdots+a_{n 1} \boldsymbol{\alpha}_{n} \\
\boldsymbol{\beta}_{2}=T(\alpha_2)=a_{12} \boldsymbol{\alpha}_{1}+a_{22} \boldsymbol{\alpha}_{2}+\cdots+a_{n 2} \boldsymbol{\alpha}_{n} \\
\ldots \ldots \ldots \ldots \\
\boldsymbol{\beta}_{n}=T(\alpha_n)=a_{1 n} \boldsymbol{\alpha}_{1}+a_{2 n} \boldsymbol{\alpha}_{2}+\cdots+a_{m} \boldsymbol{\alpha}_{n}
\end{array}\right.
$$
则称矩阵$A=(a_{ij})_{n\times n}$为T**在基$\alpha_1,\alpha_2,...,\alpha_n$下的矩阵**。
- 定理8.13:线性空间在两组基下的矩阵分别是$A，B$，且基$\alpha_i\to \beta_i$的过渡矩阵为$P$，则$B=P^{-1}AP$。即同一个线性变换在不同基下的矩阵是相似的，且相似变换矩阵就是两个基之间的过渡矩阵。
- 定理8.14:设$T，S$为$V$的线性变换，且在基 $\alpha_1,\alpha_2,...,\alpha_n$下的矩阵分别为$A<B$
	1. $T+S$在基$\alpha_1,\alpha_2,...,\alpha_n$下的矩阵为$A+B$
	2. $kT$在基$\alpha_1,\alpha_2,...,\alpha_n$下的矩阵为$kT$
	3. $TS$  为 $AB$
	4. $rankT=rankA$
	5. $T可逆\Leftrightarrow A可逆$，$T^{-1}=A^{-1}$
	6. 坐标变换可有A求的。
### 8.6.1. ★线性变换矩阵的化简（考大题）
- 定义8.18:$T(\alpha)=\lambda\alpha$，线性变换的特征值、特征向量。eg:对于多项式空间的线性变换的特征值、特征向量。
- 定理8.15:设$T$是$V$的线性变换，则存在$V$的一个基使得$T$在该基下的矩阵为对角矩阵的条件是:
  1. $T$有$n$个线性无关的特征向量
  2. $T$有$n$个互异的特征值
  3. $T$由n个特征值，且每个重特征值的重数等于对应的特征向量的个数。
- ★不变子空间:定义8.19:设$T$**是数域$K$上线性空间$V$的一个线性变换**，$W$是$V$的一个子空间。如果$\forall \alpha\in W,T(\alpha)\in W$，则称$W$是线性变换$T$和线性空间$V$上的不变子空间。
## 8.7. 欧式空间(内积空间)
### 8.7.1. 欧氏空间的概念
- 定义8.20:在实数域$R$上的线性空间$V$，在其任意两个元素$\alpha,\beta$之间都有一个实数与之对应，记为$(\alpha,\beta)$，且它满足交换律、结合律、数乘、非负性。则 称实数$(\alpha,\beta)$为$\alpha和\beta$的内积(数量基、点积、长度)，定义了内积的实线性空间$V$称为欧几里得空间(欧氏空间)，也称为实内积空间。
	- 实向量空间$R^n$中的标准内积:$(\alpha,\beta)=ab^T$
		- 加权内积$(\alpha,\beta)=aAb^T$,其中$A$是n阶正定矩阵。
	- 实矩阵空间$R^{m\times n}$的标准内积:$(A,B)=\sum_{i=1}^m\sum_{j=1}^na_{ij}b_{ij}=tr(AB^T)$
    - ps:范数是对一个矩阵自身的度量，(可看作和其自身的内积?)，
    - 内积是两个矩阵之间的度量总体来说都是线性空间加结构，加范数就是赋范线性空间，加度量就是度量空间，加内积就是内积空间。实际上，内积可以诱导范数，范数可以诱导度量，所以内积是最强的，给一个线性空间赋内积就可以自动诱导出自然范数和自然度量。[范数空间，度量空间，内积空间有什么关系？](https://www.zhihu.com/question/28978098/answer/42885613)
  	![rEjfN8.png](https://s3.ax1x.com/2020/12/12/rEjfN8.png)
	-  实线性空间$C[a,b]$中的函数$f(t),g(t)$，定义其定积分为标准内积。
- 定义8.21:范数，对应欧氏空间$V$，范数:$\|a\|=\sqrt{(a,a)}$
	- 若$\|a\|=1$，则称其为单位元素
	- 定义$a,b$之间的夹角$\phi$为$\phi=arccos(\frac{(a,b)}{\|a\|\|b\|})$
	- 若$\phi=90°$，则称$a,b$垂直
- 定理8.16、17:在欧氏空间V上总满足，非负性，齐次性，三角不等式，勾股定理。Cauchy－Schwarz、柯西－施瓦茨不等式。
- 定义8.22 设$V$是$n$维欧式空间，$\alpha_1,\alpha_2,...,\alpha_n$是$V$的一个基。称n阶方阵
$$A=(a_{ij})_{n\times n},(其中a_{ij}=(\alpha_i,\alpha_j),(i,j=1,2,...,n))$$
为基$\alpha_1,\alpha_2,...,\alpha_n$的**度量矩阵**或Gram矩阵。
- 已知度量矩阵，可构造内积$(\alpha,\beta)=\alpha A_{Gram} \beta^T$
eg:协方差矩阵??

### 8.7.2. 标准正交基
(相对于其它基，有优越性)
- 正交子空间
## 8.8. 正交变换、对称变换、投影变换
### 8.8.1. 正交变换 
定理：设是$n$维欧氏空间$V$的线性变换，则下列结论等价：
1. $T$是正交变换；
2. $\|T(a)\|=\|a\|$，即保持元素内积、长度不变；
3. 若$y1，y2…，yn$是$V$的标准正交基，则$T(y1)，T(y2)，…，T(yn)$也是V的标准正交基
4. $T$在$V$的任一标准正交基下的矩阵为正交矩阵。

注意：正交变换在正交基下的矩阵才一定是正交的。在普通基下不一定是。

### 8.8.2. 对称变换
定义设V是欧氏空间，T是V的一个线性变换，如果T满足
$$(T(\alpha)，\beta)=(\alpha, T(\beta)\qquad\alpha,\beta\in V$$
则称T是V的对称变换。

### 8.8.3. 投影变换
- 定义：设$L$和$M$是$C^n$的子空间，且$C^n=L⊕M$。\
任意
$$x∈C^n唯一分解为x=y+z，其中y∈L,z∈M$$
称$y$为$x$沿着$M$到$L$的投影；将$x$变为沿着$M$到$L$的投影$y$的变换，称为沿着$M$到$L$的投影算子，记为$P_{L,M}$，即
$$P_{L,M}(x)=y$$
同理可定义沿着$L$到$M$的投影算子$P_{M,L}$

![rKYfDx.png](https://s3.ax1x.com/2020/12/15/rKYfDx.png)

- 推论：
  1. $X\in L \to P_{L,M}(x)=x$\
	$X\in M \to P_{L,M}(x)=0$	
  2. $R(P_{L,M})=L,\qquad N(P_{L,M})=M$
  3. $P_{L,M}$是线性变换

- 定义：投影矩阵：$\mathbf{P}_{L,M}$，即$P_{L,M}(x)=x\mathbf{P}_{L,M}$

- 幂等矩阵：$A^2=A,\qquad A \in C^{n\times n}$
  -  ps:对于幂等矩阵，有如下结论$R(I-A)=N(A)$
  -  充要条件：$幂等矩阵\Leftrightarrow 投影矩阵$
-  投影矩阵的求法：
   -  对于子空间$L=L(x_1,x_2),M=(y_1)$计算$X=(x_1,x_2),Y=(y_1)$
   -  $$P_{L,M}=(X,0)(X,Y)^{-1}$$

- 正交投影算子、矩阵
  - 正交投影矩阵P幂等的Hermite矩阵。
  - $$P_L=X(X^HX)^{-1}X^H$$
(有点像求$A^+$时，$F^+$的算法。)
- 应用：1920年， Moore由正交投影矩阵给出的比较抽象的广义逆矩阵概念 与 1955年Penrose更简洁实用的广义逆定义是一致的。
