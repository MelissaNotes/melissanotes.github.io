# 2.5 Exercise (P128-P131)

## 6

### 题目

For each matrix A and ordered basis $\beta$, find $[L_A]_ \beta$. Also, find an invertible matrix $Q$ such that $[L_A]_ \beta = Q^{-1}AQ$

(a) $A = \begin{pmatrix}
1 & 3 \\
1 & 1 \\
\end{pmatrix}$ and $\beta = \left\{\begin{pmatrix}
1 \\
1 \\
\end{pmatrix},\begin{pmatrix}
1 \\
2 \\
\end{pmatrix}\right\}$

(b) $A = \begin{pmatrix}
1 & 2 \\
2 & 1 \\
\end{pmatrix}$ and $\beta = \left\{\begin{pmatrix}
1 \\
1 \\
\end{pmatrix},\begin{pmatrix}
1 \\
-1 \\
\end{pmatrix}\right\}$

(c\) $A = \begin{pmatrix}
1 & 1 & -1 \\
2 & 0 & 1 \\
1 & 1 & 0 \\
\end{pmatrix}$ and $\beta = \left\{\begin{pmatrix}
1 \\
1 \\
1 \\
\end{pmatrix},\begin{pmatrix}
1 \\
0 \\
1 \\
\end{pmatrix},\begin{pmatrix}
1 \\
1 \\
2 \\
\end{pmatrix}\right\}$

(d) $A = \begin{pmatrix}
13 & 1 & 4 \\
1 & 13 & 4 \\
4 & 4 & 10 \\
\end{pmatrix}$ and $\beta = \left\{\begin{pmatrix}
1 \\
1 \\
-2 \\
\end{pmatrix},\begin{pmatrix}
1 \\
-1 \\
0 \\
\end{pmatrix},\begin{pmatrix}
1 \\
1 \\
1 \\
\end{pmatrix}\right\}$

### 解答

> 这道题每一问分成两部分，其中第一部分是计算 $L_A$ 第二部分是计算一个新的矩阵 $Q$。首先看第一部分。

Let $\alpha$ be the standard basis (of $\mathbb{F}^2$ or $\mathbb{F}^3$).

$$
\alpha = \left\{\begin{pmatrix}
1 \\
0 \\
\end{pmatrix},\begin{pmatrix}
0 \\
1 \\
\end{pmatrix}\right\} \\
or \\
\alpha = \left\{\begin{pmatrix}
1 \\
0 \\
0 \\
\end{pmatrix},\begin{pmatrix}
0 \\
1 \\
0 \\
\end{pmatrix},\begin{pmatrix}
0 \\
0 \\
1 \\
\end{pmatrix}\right\}
$$

We have that $A = [L_A]_ \alpha$

> 这个是来源于 Theorem 2.15 (P105), 这个定理是这么说的：

> Theorem 2.15. 如果 $A$ 是一个 $m\times n$ 在 $F$ 上的 `Matrix`。那么 `left-multiplication transformation` $L_A:F^n \rightarrow F^m$ 是 `Linear` 的。同时，如果我们还有一个 $m \times n$ 的另一个 `Matrix` $B$。然后 $\beta$ 和 $\gamma$ 分别是 $F^n$ 和 $F^m$ 的 `standard ordered bases`，则有如下性质:    
> (a) $[L_A]_ \beta^\gamma = A$     
> (b) $L_A = L_B$ if and only if $A = B$     
> (c\) $L_{A+B} = L_A + L_B$ and $L_{\alpha A} = \alpha L_A$ for all $\alpha \in F$     
> (d) If $T: F^n \rightarrow F^m$ is linear, then there exists a unique $m \times n$ matrix $C$ such that $T = l_C. In fact, $C = [T]_ \beta^\gamma$     
> (e) If $E$ is an $n \times p$ matrix, then $L_AE = L_A L_E$    
> (f) If $m=n$, then $L_{I_{n}} = I_{F^n}$     

> 所以，有一个重点就是：`一个矩阵 A 和 left-multiplication 的关系`，在这里，只有我们确定了 `standard basis` 我们才能说 `A 和 L_A 相等`，也就是这个定理的 `(a)`。

hence $[L_A]_ \beta = [I]_ \alpha ^\beta [L_A]_ \alpha [I]_ \beta ^\alpha$. So now we can calculate $[L_A]_ \beta$ and $Q = [I]_ \beta ^\alpha$ and $Q^{-1} = [I]_ \alpha ^\beta$

> 这里是关键，其中要用到 Theorem .23 (P124)，这个定理是这么说的:      
> $T$ 是一个 `finite-dimensional vector space` $V$ 的 `linear operator`，并且 $\beta$ 和 $\beta'$ 是两个 $V$ 的 `ordered bases`。假设一个 `Matrix` $Q$ 是 `change of coordinate matrix` 这个 `Matrix` 是从 $\beta'$-coordinates 到 $\beta$-coordinates。那么就有如下公式成立：
> $$ [T]_ {\beta'} = Q^{-1}[T]_ {\beta}Q $$

> 这个定理的意义在于，我们不是知道一个 `T` 在两个 `basis` 下的矩阵么？那么这两个矩阵是什么关系呢？就是找到以这两个 `basis` 为基底的两个坐标系的变换矩阵`(change of coordinate matrix)`，就能求出两个 `T` 的数学关系。

由于 $[I]_ \beta^\alpha$ 是以 $\beta$ 为 `basis` 的 `Matrix` 所以不太好求，我们先求 $[I]_ \alpha^\beta$

$$ [I]_ \beta^\alpha =  不好求$$

$$ [I]_ \alpha^\beta =  好求$$

而 $[I]_ \alpha^\beta$ 就是 $\left\{\begin{pmatrix}
1 \\
1 \\
\end{pmatrix},\begin{pmatrix}
1 \\
2 \\
\end{pmatrix}\right\}$ 用 $\alpha$ 表示的 `Matrix`，因为 $\alpha$ 就是 `standard basis`，所以：

$$
[I]_ \alpha^\beta = \begin{pmatrix}
1 & 1 \\
1 & 2 \\
\end{pmatrix}
$$

而 $[I]_ \beta^\alpha$ 就是这个的 `invertible matrix` 所以算一下：

$$[I]_ \beta^\alpha = \begin{pmatrix}
2 & -1 \\
-1 & 1 \\
\end{pmatrix}
$$

所以

$$\displaystyle
[L_A]_ \beta = [I]_ \alpha ^\beta [L_A]_ \alpha [I]_ \beta ^\alpha $$

$$\displaystyle[L_A]_ \beta = \begin{pmatrix}
2 & -1 \\
-1 & 1 \\
\end{pmatrix} \begin{pmatrix}
1 & 3 \\
1 & 1 \\
\end{pmatrix} \begin{pmatrix}
1 & 1 \\
1 & 2 \\
\end{pmatrix} $$

$$\displaystyle[L_A]_ \beta = \begin{pmatrix}
6 & 11 \\
-2 & -4 \\
\end{pmatrix}
$$
