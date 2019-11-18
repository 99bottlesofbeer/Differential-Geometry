# 1. Calculus on Euclidean Space

## 1.1 Euclidean Space

### 1.1 Definition

$\mathbb{R}^3$

a point

### 1.2 Definition

the natural coordinate functions $x_1,x_2,x_3$

### 1.3 Definition

differentiable real-valued function



## 1.2 Tangent Vectors

### 2.1 Definition

A tangent vector $v_p$ to $\mathbb{R}^3$

### 2.2 Definition

the tangent space of $\mathbb{R}^3$ at $p$

$T_p(\mathbb{R}^3)$

### 2.3 Definition

A vector field $V$ on $\mathbb{R}^3$ is a function $V(p)\in T_p(\mathbb{R}^3)$

### 2.4 Definition

the natural frame field $U_1, U_2, U_3$

$U_1(p)=(1,0,0)_p$

$U_2(p)=(0,1,0)_p$

$U_3(p)=(0,0,1)_p$

### 2.5 Lemma

If $V$ is a vector field on $\mathbb{R}^3$, there are unique real-valued functions $v_1,v_2,v_3$ on $\mathbb{R}^3$ such that

$V=v_1U_1+v_2U_2+v_3U_3$.



## 1.3 Directional Derivatives

### 3.1 Definition

the derivative of $f$ with respect to $v_p$

$v_p[f] = {d\over dt}(f(p+tv))|_{t=0}$

### 3.2 Lemma

$v_p=(v_1,v_2,v_3)_p$

$v_p[f]=\sum v_i{\partial f\over\partial x_i}(p)$

### 3.3 Theorem

- (1) $(av_p+bw_p)[f]=$
- (2) $v_p[af+bg]=$
- (3) $v_p[fg]=$

### Book

the operation of a vector field $V$ on a function $f$

result : the real-valued function $V[f]$ 

$V[f](p)=V(p)[f]$

### 3.4 Corollary

//

## 1.4 Curves in $\mathbb{R}^3$

### 4.1 Definition

a curve

### 4.2 Example

(1) Straight line

(2) Helix

...

### 4.3 Definition

the velocity vector of $\alpha$ at $t$

### 4.4 Definition

a re-parametrization of $\alpha$ by $h$

### 4.5 Lemma

//

### 4.6 Lemma

$\alpha'(t)[f]={d(f(\alpha))\over dt}(t)$

### Book

regular curve



## 1.5 1-Forms

### 5.1 Definition

a 1-form on $\mathbb{R}^3$

### 5.2 Definition

the differential of $f$

$df(v_p)=v_p[f]$

### 5.3 Example

(1) The differentials of the natural coordinate functions

(2) $f_1dx_1+f_2dx_2+f_3dx_3$

### 5.4 Lemma

$\phi$ is a 1-form on $\mathbb{R}^3$

the Euclidean coordinate functions of $\phi$

### 5.5 Corollary

$df=\sum{\partial f\over\partial x_i}dx_i$

### 5.6 Lemma

$d(fg)=gdf+fdg$

### 5.7 Lemma

$d(h(f))=h'(f)df$



## 1.6 Differential Forms

### Book

alternation rule: $dx_idx_j=-dx_jdx_i$



a wedge $\wedge$

### 6.1 Example

//

### 6.2 Lemma

If $\phi,\psi$ are 1-forms, then

$\phi\wedge\psi=-\psi\wedge\phi$

### 6.3 Definition

$\phi=\sum f_idx_i$ 1-form

$d\phi=\sum df_i\wedge dx_i$ 2-form

the exterior derivative of $\phi$

### 6.4 Theorem

//



## 1.7 Mappings

### 7.1 Definition

a mapping from $\mathbb{R}^n$ to $\mathbb{R}^m$

### 7.2 Definition

If $\alpha:I\to\mathbb{R}^n$ is a curve and $F:\mathbb{R}^n\to\mathbb{R}^m$ is a mapping, then $\beta=F(\alpha):I\to\mathbb{R}^m$ is called

the image of $\alpha$ under $F$.

### 7.3 Example

//

### 7.4 Definition

Let $F:\mathbb{R}^n\to\mathbb{R}^m$ be a mapping, $v_p\in T_p\mathbb{R}^n$.

Let $F_*(v_p)$ be the initial velocity of the curve $t\to F(p+tv_p)$.

$F*:T(\mathbb{R}^n)\to T(\mathbb{R}^m)$ is called the tangent map of $F$.

### 7.5 Proposition

$F=(f_1,f_2,...,f_m)$

$\Rightarrow$ $F_*(v_p)=(v_p[f_1],...,v_p[f_m])_{F(p)}$

### 7.6 Corollary

$F_{*p}:T_p(\mathbb{R}^n)\to T_{F(p)}(\mathbb{R}^m)$ is a linear transformation.

### 7.7 Corollary

$\beta=F(\alpha)$ is the image of a curve $\alpha$, then $\beta'=F_*(\alpha')$.

### 7.8 Corollary

//

### 7.9 Definition

A mapping $F$ is regular if at every point $p$ $F_{*p}$ is 1-1.

### 7.10 Theorem

Let $F:\mathbb{R}^n\to\mathbb{R}^n$ be a mapping. If $F_{*p}$ is 1-1 at a point $p$, there is an open set $U_p$ such that

$F_{U_p}$ is a diffeomorphism onto an open set $V$.





# 2. Frame Fields

## 2.1 Dot Product

### 1.1 Definition

$p\cdot q$

$\lVert p\rVert=(p\cdot p)^{1/2}$

### 1.2 Definition

$d(p,q)=\lVert p-q\rVert$

### 1.3 Definition

$v_p\cdot w_p=v\cdot w$

### 1.4 Definition

A set $\{e_1,e_2,e_3\}\subset T_p(\mathbb{R}^3)$ of mutually orthogonal unit vectors is called

a frame at the point $p$.

### 1.5 Theorem

Let $\{e_1,e_2,e_3\}$ be a frame at a point $p$, $v\in T_p(\mathbb{R}^3)$.

Then $v=(v\cdot e_1)e_1+(v\cdot e_2)e_2+(v\cdot e_3)e_3$.

### 1.6 Definition

Let $\{e_1,e_2,e_3\}$ be a frame at a point $p$, $v_p\in T_p(\mathbb{R}^3)$.

$e_1=(a_{11},a_{12},a_{13})_p$

$e_2=(a_{21},a_{22},a_{23})_p$

$e_3=(a_{31},a_{32},a_{33})_p$

$A=
\begin{pmatrix}
a_{11} & a_{12} & a_{13} \\
a_{11} & a_{12} & a_{13} \\
a_{11} & a_{12} & a_{13} \\
\end{pmatrix}$ is called the attitude matrix of the frame.

$A^TA=I$

### 1.7 Definition

$v\times w=
\begin{vmatrix}
U_1(p) & U_2(p) & U_3(p) \\ 
v_1 & v_2 & v_3 \\ 
w_2 & w_2 & w_3 \\
\end{vmatrix}$

### 1.8 Lemma

$\lVert v\times w\rVert^2=(v\cdot v)(w\cdot w)-(v\cdot w)^2$



## 2.2 Curves

### 2.1 Theorem

A regular curve has an unit speed re-parametrization.

### 2.2 Definition

A vector field $Y$ on curve $\alpha:I\to\mathbb{R}^3$ is a function on $I$.

$Y(t)\in T_{\alpha(t)}(\mathbb{R}^3)$

### Book

$\alpha'$ is a vector field on $\alpha$.

### 2.3 Lemma

- (1) A curve is constant iff its velocity is zero.
- (2) A non-constant curve is a straight line iff its acceleration is zero.
- (3) //

## 2.3 The Frenet Formulas

//





## 2.5 Covariant Derivatives

### 5.1 Definition

Let $W$ be a vector field on $\mathbb{R}^3$, and let $v\in T_p(\mathbb{R}^3)$.

Then the covariant derivative of $W$ with respect to $v$ is the tangent vector

$\nabla_vW=W(p+tv)'(0)\in T_p(\mathbb{R}^3)$.

### 5.2 Lemma

$W=\sum w_iU_i$

$\nabla_vW=\sum v[w_i]U_i(p)$

### 5.3 Theorem

- (1) $\nabla_{av+bw}Y=$
- (2) $\nabla_v(aY+bZ)=$
- (3) $\nabla_v(fY)=$
- (4) $v[Y\cdot Z]=$

### 5.4 Corollary

Let $V,W,Y,Z$ be vector fields.

- (1) $\nabla_{fV+gW}Y=$
- (2) $\nabla_v(aY+bZ)=$
- (3) $\nabla_V(fY)=$
- (4) $V[Y\cdot Z]=$



## 2.6 Frame Fields

### 6.1 Definition

Vector fields $E_1,E_2,E_3$ constitute a frame field

if $E_i\cdot E_j=\delta_{ij}$.

### 6.2 Example

- (1) The cylindrical frame field
- (2) The spherical frame field

### 6.3 Lemma

Let $E_1,E_2,E_3$ be a frame field.

- (1) If $V$ is a vector field, then $V=\sum f_iE_i$ where $f_i=V\cdot E_i$.
  $f_i$ are called the coordinate functions of $V$ with respect to $E_i$.
- (2) If $V=\sum f_iE_i$ and $W=\sum g_iE_i$, then $V\cdot W=\sum f_ig_i$.
  In particular, $\lVert V\rVert=(\sum f_i^2)^{1/2}$.



## 2.7 Connection Forms

Let $E_1,E_2,E_3$ be a frame field.

$\nabla_vE_1=c_{11}E_1(p)+c_{12}E_2(p)+c_{13}E_3(p)$

$\nabla_vE_2=c_{21}E_1(p)+c_{22}E_2(p)+c_{23}E_3(p)$

$\nabla_vE_3=c_{31}E_1(p)+c_{32}E_2(p)+c_{33}E_3(p)$



$c_{ij}=\omega_{ij}(v)=\nabla_vE_i\cdot E_j(p)$

### 7.1 Lemma

$\omega_{ij}$ is a 1-form. $\omega_{ij}=-\omega_{ji}$

### 7.2 Theorem

For any vector field $V$,

$\displaystyle
\nabla_VE_i=\sum_j\omega_{ij}(V)E_j$.

The connection equations of the frame field $E_1,E_2,E_3$.

### 7.3 Theorem

A is the attitude matrix and $\omega=(w_{ij})$.

$\omega=dA^TA$



## 2.8 The Structural Equations



# 3. Euclidean Geometry

## 3.1 Isometries of $\mathbb{R}^3$ 

### 1.1 Definition

An isometry of $\mathbb{R}^3$ is a mapping $F:\mathbb{R}^3\to\mathbb{R}^3$ such that

$d(F(p),F(q))=d(p,q)$ for all $p,q$.

### 1.2 Example

- (1) Translations
- (2) Rotations around a coordinate axis

### 1.3 Lemma

$F,G$ are isometries $\Rightarrow$ $GF$ is an isometry

### 1.4 Lemma

- (1) $S,T$ are translations $\Rightarrow$ $ST=TS$ is a translation
- (2) If $T$ is translation by $a$, then $T^{-1}$ is translation by $-a$.
- (3)  

### Book

An orthogonal transformation is a linear transformation $C:\mathbb{R}^3\to\mathbb{R}^3$ such that

$C(p)\cdot C(q)=p\cdot q$ for all $p,q$.

### 1.5 Lemma

An orthogonal transformation is an isometry.

### 1.6 Lemma

If $F$ is an isometry $F(0)=0$, then $F$ is an orthogonal transformation.

### 1.7 Theorem

If $F$ is an isometry, then there exist a unique translation $T$ and a unique orthogonal transformation $C$

such that $F=TC$.



## 3.2 The Tangent Map of an Isometry

### 2.1 Theorem

$F_*(v_p)=C(v)_{F(p)}$

### 2.2 Corollary

$F_*(v_p)\cdot F_*(w_p)=v\cdot w$

### 2.3 Theorem

For any two frames $\{e_1,e_2,e_3\}$ at $p$ and $\{f_1,f_2,f_3\}$ at $q$,

there exists a unique isometry $F$ such that $F_*(e_i)=f_i$.



## 3.3 Orientation

### Book

$e_1\cdot e_2\times e_3=det A=\pm 1$

$1$ : positively oriented (or right-handed)

$-1$ : negatively oriented (or left-handed)

### 3.1 Remark

- (1) The natural frame field is positively oriented.
- (2) A frame $e_1,e_2,e_3$ is positively oriented iff $e_1\times e_2=e_3$.
  Frenet frames are positively oriented.
- (3)

### Book

$\operatorname{sgn} F=\det C$

### 3.2 Lemma

$F_*(e_1)\cdot F_*(e_2)\times F_*(e_3)=(\operatorname{sgn}F)e_1\cdot e_2\times e_3$

### 3.3 Definition

An isometry $F$ is

orientation-preserving if $\operatorname{sgn}F=1$

orientation-reversing if $\operatorname{sgn}F=-1$

### 3.4 Example

- (1) Translations
- (2) Rotations
- (3) Reflections

### 3.5 Lemma

