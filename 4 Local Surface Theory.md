# 4 Local Surface Theory

## 4-1. Basic Definitions and Examples

### Definition

open

### Definition

a coordinate patch (or simple surface)

$\mathbf{x}:U\to\mathbb{R}^3$

1-1, ${\partial\mathbf{x}\over\partial u^1}\times{\partial\mathbf{x}\over\partial u^2}\neq0$ (regularity condition)

### Example 1.6

Let $f(u^1,u^2):U\to\mathbb{R}$ be a $C^k$ function.

$\mathbf{x}(u^1,u^2)=(u^1,u^2,f(u^1,u^2))$ is a $C^k$ simple surface.

The graph of a function

Monge patch

### Definition

a coordinate transformation

$f:V\to U$

1-1, onto, diffeomorphism

### Lemma 1.11

simple surface + coordinate transformation = simple surface

$\mathbf{y}=\mathbf{x}\circ f:V\to\mathbb{R}^3$

Proof)

$\displaystyle
{\partial\mathbf{y}\over\partial v^\alpha}
={\partial\mathbf{x}\over\partial u^1}{\partial f^1\over\partial v^\alpha}
+{\partial\mathbf{x}\over\partial u^2}{\partial f^2\over\partial v^\alpha}
=\sum{\partial\mathbf{x}\over\partial u^i}{\partial f^i\over\partial v^\alpha}$



$\displaystyle
{\partial\mathbf{y}\over\partial v^1}\times{\partial\mathbf{y}\over\partial v^2}
=(\sum{\partial\mathbf{x}\over\partial u^i}{\partial f^i\over\partial v^1})
\times(\sum{\partial\mathbf{x}\over\partial u^j}{\partial f^j\over\partial v^2})$

$\displaystyle
={\partial\mathbf{x}\over\partial u^1}{\partial f^1\over\partial v^1}
\times{\partial\mathbf{x}\over\partial u^2}{\partial f^2\over\partial v^2}
+{\partial\mathbf{x}\over\partial u^2}{\partial f^2\over\partial v^1}
\times{\partial\mathbf{x}\over\partial u^1}{\partial f^1\over\partial v^2}
$

$\displaystyle
={\partial\mathbf{x}\over\partial u^1}{\partial f^1\over\partial v^1}
\times{\partial\mathbf{x}\over\partial u^2}{\partial f^2\over\partial v^2}
-{\partial\mathbf{x}\over\partial u^1}{\partial f^1\over\partial v^2}
\times{\partial\mathbf{x}\over\partial u^2}{\partial f^2\over\partial v^1}$

$\displaystyle
=\det(J(f))
({\partial\mathbf{x}\over\partial u^1}\times{\partial\mathbf{x}\over\partial u^2})$



### Notation

$\mathbf{x}_1(a,b)={\partial x\over\partial u^1}(a,b)$, $\mathbf{x}_2(a,b)={\partial x\over\partial u^2}(a,b)$

### Definition

the tangent plane to a simple surface $\mathbf{x}$ at the point $P=\mathbf{x}(a,b)$

the unit normal to the surface at $P$ is $\displaystyle
\mathbf{n}(a,b)
={\mathbf{x}_1\times\mathbf{x}_2\over|\mathbf{x}_1\times\mathbf{x}_2|}$

### Proposition 1.13

(a) the tangent plane to $\mathbf{x}$ = the tangent plane to $\mathbf{y}$ 

(b) the normal to $\mathbf{x}$ = $\pm$ the normal to $\mathbf{y}$ 

### Definition

a tangent vector to $\mathbf{x}$

### Lemma 1.16

The set of all tangent vectors to $\mathbf{x}$ at $P$ is a vector space.

Proof)

If $\mathbf{X},\mathbf{Y}\in T_P\mathbf{x}$ and $P=\mathbf{x}(a,b)$,

then $\mathbf{X}=\alpha'(0)$, $\mathbf{Y}=\beta'(0)$ for some curves $\alpha,\beta$ in $\mathbf{x}(U)$ with $\alpha(0)=\beta(0)=P$.

$\alpha(t)=\mathbf{x}(\alpha^1(t),\alpha^2(t))$, $\beta(t)=\mathbf{x}(\beta^1(t),\beta^2(t))$

$\displaystyle
\mathbf{X}
={\partial\mathbf{x}\over\partial u^1}(\alpha^1)'(t)
+{\partial\mathbf{x}\over\partial u^2}(\alpha^2)'(t)$

$\displaystyle
\mathbf{Y}
={\partial\mathbf{x}\over\partial u^1}(\beta^1)'(t)
+{\partial\mathbf{x}\over\partial u^2}(\beta^2)'(t)$

Let $\gamma(t)=\mathbf{x}(\alpha^1(t)+\beta^1(t)-a,\alpha^2(t)+\beta^2(t)-b)$.

$\gamma(0)=P$

$\displaystyle
\gamma'(t)
={\partial\mathbf{x}\over\partial u^1}((\alpha^1)'(t)+(\beta^1)'(t))
+{\partial\mathbf{x}\over\partial u^2}((\alpha^2)'(t)+(\beta^2)'(t))$

$\gamma'(0)=\mathbf{X}+\mathbf{Y}$



Let $\eta(t)=\alpha(rt)$.

$\eta(0)=\alpha(0)=P$

$\eta'(0)=r\alpha'(0)=r\mathbf{X}$



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

### Book

If $f:\mathbb{R}^3\to\mathbb{R}$ is differentiable, $(f_x,f_y,f_z)\neq0$  $\forall P\in M=\{(x,y,z)\ |\ f(x,y,z)=0\}$,

then $M$ is a surface.



## 4-3. The First Fundamental Form and Arc Length

### Book

$\mathbf{X},\mathbf{Y}\in T_pM$

$\mathbf{X}=\sum X^i\mathbb{x}_i$ , $\mathbf{X}=\sum Y^j\mathbb{x}_j$

$\langle \mathbf{X},\mathbf{Y}\rangle
=\sum X^iY^j\langle\mathbf{x}_i,\mathbf{x}_j\rangle=\sum X^iY^jg_{ij}$



the metric coefficients

$g_{ij}(u^1,u^2)
=\langle\mathbf{x}_i(u^1,u^2),\mathbf{x}_j(u^1,u^2)\rangle$



### Definition

The tangent space of $M$ at $p$

$T_pM$

### Notation

$g=\det(g_{ij})$

### Book

$\alpha(t)$ a regular curve whose image is contained in that of $\mathbf{x}:U\to\mathbb{R}^3$.

$\alpha(t)=\mathbf{x}(\alpha^1(t),\alpha^2(t))$

the length of the segment

$\int_a^b|d\alpha/dt|dt$

$d\alpha/dt=\sum\mathbf{x}_id\alpha^i/dt$

$\displaystyle
|d\alpha/dt|
=\sqrt{\langle{d\alpha\over dt},{d\alpha\over dt}\rangle}
=\sqrt{\langle\sum\mathbf{x}_i{d\alpha^i\over dt},\sum\mathbf{x}_j{d\alpha^j\over dt}\rangle}
=\sqrt{\sum_{i,j}g_{ij}{d\alpha^i\over dt}{d\alpha^j\over dt}}$



### Lemma 3.4

(a) $g=|\mathbf{x}_1\times\mathbf{x}_2|^2$

(b) //

(c) //

### Book

$\mathbf{y}=\mathbf{x}\circ f$, $f(v^1,v^2)=(u^1(v^1,v^2),u^2(v^1,v^2))$

$\displaystyle
\mathbf{y}_\alpha={\partial\mathbf{y}\over\partial v^\alpha}$

$\displaystyle
\overline{g}_{\alpha\beta}
=\langle\mathbf{y}_\alpha,\mathbf{y}_\beta\rangle$



$\displaystyle
\mathbf{y}_\alpha
=\sum\mathbf{x}_i{\partial u^i\over\partial v^\alpha}$, similarly $\displaystyle
\mathbf{x}_i
=\sum\mathbf{y}_\alpha{\partial v^\alpha\over\partial u^i}$

$\displaystyle
g_{ij}=\langle\mathbf{x}_i,\mathbf{x}_j\rangle
=\sum_{\alpha\beta}
\langle\mathbf{y}_\alpha,\mathbf{y}_\beta\rangle
{\partial v^\alpha\over\partial u^i}{\partial v^\beta\over\partial u^j}$

$\displaystyle
=\sum_{\alpha\beta}
\overline{g}_{\alpha\beta}
{\partial v^\alpha\over\partial u^i}{\partial v^\beta\over\partial u^j}$



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



### Book

$\gamma(s)=\mathbf{x}(\gamma^1(s),\gamma^2(s))$

$\displaystyle
\mathbf{T}=\gamma'=\sum_i\mathbf{x}_i(\gamma^i)'$

$\displaystyle
{d\mathbf{\mathbf{x}_i}(\gamma^1,\gamma^2)\over ds}
=\mathbf{x}_{i1}(\gamma^1)'+\mathbf{x}_{i2}(\gamma^2)'
=\sum_j\mathbf{x}_{ij}(\gamma^j)'$

$\displaystyle
\gamma''=\sum_{i,j}\mathbf{x}_{ij}(\gamma^i)'(\gamma^j)'+\sum_i\mathbf{x}_i(\gamma^i)''$



### Definition

The normal curvature of $\gamma$ = $\kappa_n$

The geodesic curvature of $\gamma$ = $\kappa_g$

### Definition

The coefficients of the second fundamental form of $\mathbf{x}$

$L_{ij}=\langle\mathbf{x}_{ij},\mathbf{n}\rangle$

The Christoffel symbols

${\Gamma_{ij}}^k=\sum \langle\mathbf{x}_{ij},\mathbf{x}_l\rangle g^{lk}$

### Book

$\mathrm{II}(\mathbf{X},\mathbf{Y})=\sum_{i,j}L_{ij}X^iY^j$

### Proposition 4.2

(a) (Gauss's formulas)

$\mathbf{x}_{ij}=L_{ij}\mathbf{n}+\sum_k{\Gamma_{ij}}^k\mathbf{x}_k$

(b) //

### Proposition 4.3

$\Gamma$ is intrinsic.

${\Gamma_{ij}}^l={1\over2}\sum_kg^{kl}
(-{\partial g_{ij}\over\partial u_k}
+{\partial g_{jk}\over\partial u_i}
+{\partial g_{ki}\over\partial u_j})$



Proof)

### Book

An intrinsic concept is one which depends only on $g_{ij}$.



### Proposition 4.4

$\kappa_g$ is intrinsic.

Proof)

$\epsilon_{ij}=[\mathbf{n},\mathbf{x}_i,\mathbf{x}_j]$

$\epsilon_{11}=\epsilon_{22}=0$

$\epsilon_{12}=-\epsilon{21}=\sqrt{g}$

$\epsilon_{ij}$ is intrinsic.



$\kappa_g=\langle\kappa_g\mathbf{S},\mathbf{S}\rangle=[\kappa_g\mathbf{S},\mathbf{n},\mathbf{T}]$





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



## 4-6. Parallel Vector Fields Along A Curve And Parallelism

### Definition

A vector field along a curve

### Definition

A differentiable vector field





## 4-7. The Second Fundamental Form And The Weingarten Map

### Definition

The second fundamental form $\mathrm{II}$ on $M$ is the bilinear form on $T_PM$

$\mathrm{II}(\mathbf{X},\mathbf{Y})=\sum_{i,j}L_{ij}X^iY^j$

where $\mathbf{X}=\sum X^i\mathbf{x}_i,\mathbf{Y}=\sum Y^j\mathbf{x}_j$



### Proposition 7.1

(a) $\mathrm{II}$ is a symmetric bilinear form on $T_PM$

(b) if $\gamma$ is a unit speed curve with tangent $\mathbf{T}$, then $\kappa_n=\mathrm{II}(\mathbf{T},\mathbf{T})$

(c) if $\alpha$ and $\beta$ are regular curves with $\alpha(0)=\beta(0)$ and $\alpha'(0),\beta'(0)$ are dependent, then they have same normal curvature at $t=0$.



### Definiton

Let $f$ be a differentiable function  defined on a neighborhood of $P\in M$, $\mathbf{X}\in T_PM$.

Let $\alpha(t)$ be a curve on $M$ such that $\alpha(0)=P$ and $\alpha'(0)=\mathbf{X}$.

The directional derivative of $f$ in the direction $\mathbf{X}$ is

$\mathbf{X}f=(f\circ\alpha)'(0)$.



### Definition

The Weingarten map $\mathsf{L}:T_PM\to\mathbb{R}^3$

$\mathsf{L}(\mathbf{X})=-\mathbf{Xn}$



### Proposition 7.6

(a) $\mathsf{L}$ is a linear transformation $T_PM\to T_PM$.

(b) If $\mathsf{L}(\mathbf{x}_k)=\sum_l{L^l}_k\mathbf{x}_l$, then ${L^l}_k=\sum_iL_{ik}g^{il}$. 



### Lemma 7.10

$\mathbf{X},\mathbf{Y}\in T_PM$

$\mathrm{II}(\mathbf{X},\mathbf{Y})
=\langle\mathsf{L}(\mathbf{X}),\mathbf{Y}\rangle
=\langle\mathbf{X},\mathsf{L}(\mathbf{Y})\rangle$ 

Proof)

$\langle\mathbf{n},\mathbf{x}_j\rangle=0$

$\Rightarrow$ ${\partial\over\partial u^i}\langle\mathbf{n},\mathbf{x}_j\rangle=0$

$\Rightarrow$ $\langle-\mathsf{L}(\mathbf{x}_i),\mathbf{x}_j\rangle
+\langle\mathbf{n},\mathbf{x}_{ij}\rangle=0$

$\Rightarrow$ $\langle\mathsf{L}(\mathbf{x}_i),\mathbf{x}_j\rangle
=\langle\mathbf{n},\mathbf{x}_{ij}\rangle=L_{ij}$



$\mathbf{X}=\sum X^i\mathbf{x}_i$, $\mathbf{Y}=\sum Y^j\mathbf{x}_j$

$\mathrm{II}(\mathbf{X},\mathbf{Y})
=\langle\mathsf{L}(\mathbf{X}),\mathbf{Y}\rangle
=\langle\mathbf{X},\mathsf{L}(\mathbf{Y})\rangle
=\sum X^iY^jL_{ij}$ 



## 4.8 Principal, Gaussian, Mean, and Normal Curvatures

### Book

$f(\mathbf{X},\lambda)
=\mathrm{II}(\mathbf{X},\mathbf{X})-\lambda(\langle\mathbf{X},\mathbf{X}\rangle-1)$

$=\langle\mathsf{L}(\mathbf{X}),\mathbf{X}\rangle-\lambda\langle\mathbf{X},\mathbf{X}\rangle+\lambda$

$=\langle\mathsf{L}(\mathbf{X})-\lambda\mathbf{X},\mathbf{X}\rangle+\lambda$



$\mathbf{X}=\sum_j X^j\mathbf{x}_j$

$\mathsf{L}(\mathbf{X})
=\sum_j X^j\mathsf{L}(\mathbf{x}_j)
=\sum_j X^j\sum_i{L^i}_j\mathbf{x}_i
=\sum_{i,j}{L^i}_jX^j\mathbf{x}_i$

$\lambda\mathbf{X}
=\sum_j X^j\lambda\mathbf{x}_j
=\sum_j X^j\sum_i\lambda\delta_j^i\mathbf{x}_i
=\sum_{i,j}\lambda\delta_j^iX^j\mathbf{x}_i$



$\mathsf{L}(\mathbf{X})-\lambda\mathbf{X}
=\sum_i\sum_j({L^i}_j-\lambda\delta_j^i)X^j\mathbf{x}_i$



$\displaystyle
f(X^1,X^2,\lambda)
=\sum_{i,k}\sum_j({L^i}_j-\lambda\delta_j^i)X^jX^kg_{ik}
=\sum_{i,j,k}({L^i}_j-\lambda\delta_j^i)X^jX^kg_{ik}$

//??

### Lemma 8.1

Let $P\in M$ and $\lambda,\mathbf{X}$ be an eigenvalue-eigenvector pair for $\mathsf{L}$ at $P$.

Let $\mathbf{Y}$ be a unit vector in $T_PM$ such that $\langle\mathbf{X},\mathbf{Y}\rangle=0$.

Then $\mathbf{Y}$ is also an eigenvector.



### Proposition 8.2

At each point there are two orthogonal directions such that

the normal curvature takes its maximum and minimum in the directions.



### Definition

The principal curvatures of $M$ at $P$ are the eigenvalues of $\mathsf{L}$ there ($\kappa_1,\kappa_2$).

Corresponding unit vectors are called principal directions at $P$.



### Definition

The Gaussian curvature of $M$ at $P$ is $K=\kappa_1\kappa_2=\det\mathsf{L}$.

The mean curvature of $M$ at $P$ is $K=(\kappa_1+\kappa_2)/2
=(\operatorname{trace}\mathsf{L})/2$.



## 4.9 Riemann Curvature and Gauss's Theorema Egregium

### Definition

The Riemann curvature tensor 

$R_{ijk}^l=$



### Proposition 9.1

(a) Gauss's equations

(b) Codazzi-Mainardi equations



### Theorem 9.2 (Gauss's Theorema Egregium)

$K$ is intrinsic.



