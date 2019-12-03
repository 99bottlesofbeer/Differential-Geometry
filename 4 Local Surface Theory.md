# 4 Local Surface Theory

## 4-1. Basic Definitions and Examples

### Definition

open

### Definition

a coordinate patch (or simple surface)

$\mathbf{x}:U\to\mathbb{R}^3$

### Definition

a coordinate transformation

$f:V\to U$

### Lemma 1.11

simple surface + coordinate transformation = simple surface

$\mathbf{y}=\mathbf{x}\circ f:V\to\mathbb{R}^3$

### Notation

$\mathbf{x}_1(a,b)={\partial x\over\partial u^1}(a,b)$, $\mathbf{x}_2(a,b)={\partial x\over\partial u^2}(a,b)$

### Definition

the tangent plane to a simple surface $\mathbf{x}$ at the point $P=\mathbf{x}(a,b)$

the unit normal to the surface at $P$ is $\displaystyle
\mathbf{n}(a,b)
={\mathbf{x}_1\times\mathbf{x}_2\over|\mathbf{x}_1\times\mathbf{x}_2|}$

### Proposition 

(a) the tangent plane to $\mathbf{x}$ = the tangent plane to $\mathbf{y}$ 

(b) the normal to $\mathbf{x}$ = $\pm$ the normal to $\mathbf{y}$ 

### Definition

a tangent vector to $\mathbf{x}$

### Lemma 1.16

The set of all tangent vectors to $\mathbf{x}$ at $P$ is a vector space.

### Definition

The $u^1$-curve, $\alpha$, through $P$ = $\alpha(u^1)=\mathbf{x}(u^1,b)$

The $u^2$-curve, $\beta$, through $P$ = $\alpha(u^2)=\mathbf{x}(a,u^2)$

A parametric curve on $x$ is one of these.

### Proposition 1.18

//



## 4-2. Surfaces

### Definition

$M\subset\mathbb{R}^3$, $\epsilon>0$

The $\epsilon$-neighborhood of $P\in M$

### Definition

$g:M\to\mathbb{R}^2$ is continuous at $P$

### Definition

$\mathbf{x}:U\to\mathbb{R}^3$ is proper if $\mathbf{x}^{-1}:\mathbf{x}(U)\to U$ is continuous at each point.

### Definition

A surface $M$



## 4-3. The First Fundamental Form and Arc Length

### Book

$X,Y\in T_pM$

$X=\sum X^i\mathbb{x}_i$ , $Y=\sum Y^j\mathbb{x}_j$

$\mathbf{I}<X,Y>=\sum X^iY^j<\mathbf{x}_i,\mathbf{x}_j>=\sum X^iY^jg_{ij}$



$g_{ij}(u^1,u^2)
=<\mathbf{x}_i(u^1,u^2),\mathbf{x}_j(u^1,u^2)>$

### Definition

The tangent space of $M$ at $p$

$T_pM$

### Notation

$g=\det(g_{ij})$

### Lemma 3.4

(a) $g=|\mathbf{x}_1\times\mathbf{x}_2|^2$

(b) //

(c) //

### Definition

A linear functional on a real vector space $V$ is a linear function $\rho:V\to\mathbb{R}$.

### Book

The set of all linear functionals defined on $V$ forms a vector space.

The dual space of $V$

$V^*$

### Theorem 3.9

$\dim V=n$ $\Rightarrow$ $\dim V^*=n$

### 4-4. Normal Curvature, Geodesic Curvature, and Gauss's Formulas

### Notation

$\gamma(s)$ is a unit speed curve in the image of $\mathbf{x}$.

$\mathbf{x}_{ij}(a,b)={\partial^2\mathbf{x}\over\partial u^i\partial u^j}(a,b)$

$\mathbf{S}=n\times \mathbf{T}$

$\mathbf{S}$ is the intrinsic normal of $\gamma$

$\kappa(s)\mathbf{N}(s)=\mathbf{T}'(s)=\gamma''(s)=\kappa_n(s)\mathbf{n}(s)+\kappa_g(s)\mathbf{S}(s)$

### Definition

The normal curvature of $\gamma$ = $\kappa_n$

The geodesic curvature of $\gamma$ = $\kappa_g$

### Definition

The coefficients of the second fundamental form of $\mathbf{x}$

$L_{ij}=<\mathbf{x}_{ij},\mathbf{n}>$

The Christoffel symbols

${\Gamma_{ij}}^k=\sum <\mathbf{x}_{ij},\mathbf{x}_l>g^{lk}$

### Book

$\mathbf{II}(X,Y)=\sum_{i,j}L_{ij}X^iY^j$

### Proposition 4.2

(a) (Gauss's formulas)

$\mathbf{x}_{ij}=L_{ij}\mathbf{n}+\sum_k{\Gamma_{ij}}^k\mathbf{x}_k$

(b) //

### Proposition 4.3

$\Gamma$ is intrinsic.

//

### Proposition 4.4

$\kappa_g$ is intrinsic.



## 4-5. Geodesics

### Definition

A geodesic on a surface $M$ is a unit speed curve on $M$ with $\kappa_g=0$

측지선

### Proposition 5.1

A unit speed curve is geodesic iff $[n,T,T']=0$

### Proposition 5.2

//

### Proposition 5.3

A unit speed curve $\gamma$ is a geodesic iff $\gamma''$ is everywhere normal to the surface.

### Proposition 5.5

a surface of revolution

(a) every meridian is a geodesic

(b) //

### Theorem 5.7

$P\in M$, $X\in\mathbf{T}_PM$, $s_0\in\mathbb{R}$

there exists a unique geodesic $\gamma$ with $\gamma(s_0)=P$, $\gamma'(s_0)=X$

### Theorem 5.9

Let $\gamma$ be a unit speed curve in $M$. $P=\gamma(a)$, $Q=\gamma(b)$

If $\gamma$ is the shortest curve between $P$ and $Q$, then $\gamma$ is geodesic.

### Theorem 5.12

//



## 4.6 Parallel Vector Fields Along A Curve And Parallelism

### Definition

A vector field along a curve

### Definition

A differentiable vector field





