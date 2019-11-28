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

A mapping $F$ is regular if $F_{*p}$ is 1-1 at every point $p$ .

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

Let $e_1,e_2,e_3$ be a frame at a point. $v=\sum v_ie_i$, $w=\sum w_ie_i$.

Then $v\times w=(e_1\cdot e_2\times e_3)
\begin{vmatrix}
e_1 & e_2 & e_3 \\
v_1 & v_2 & v_3 \\
w_1 & w_2 & w_2 \\
\end{vmatrix}$

### 3.6 Theorem

$v,w\in T_p\mathbb{R}^3$.

If $F$ is an isometry, then $F_*(v\times w)=(\operatorname{sgn}F)F_*(v)\times F_*(w)$.



## 3.4 Euclidean Geometry

### 4.1 Corollary

Let $Y$ be a vector field on a curve $\alpha$, and let $F$ be an isometry.

Then $\overline{Y}=F_*(Y)$ is a vector field on $\overline{\alpha}=F(\alpha)$, and $\overline{Y}'=F_*(Y')$.

### 4.2 Theorem

Let $\beta$ be a unit-speed curve with $\kappa>0$, and let $\overline{\beta}=F(\beta)$ be the image curve

under an isometry $F$.

//





# 4. Calculus on a Surface

### 1.1 Definition

A coordinate patch $x:D\to\mathbb{R}^3$ is a 1-1 regular mapping of an open set $D$ of $\mathbb{R}^2$.

### Book

A proper patch is a coordinate patch that the inverse is continuous.

### 1.2 Definition

A surface in $\mathbb{R}^3$ is a subset $M$ such that for each $p\in M$ there exists a proper patch in $M$ whose image contains a neighborhood of $p$ in $M$.

### 1.3 Example

- differentiable real-valued function on $\mathbb{R}^2$

### 1.4 Theorem

Let $g$ be a differentiable real-valued function on $\mathbb{R}^3$, $c\in\mathbb{R}$.

$M:g(x,y,z)=c$ is a surface if the differential $dg$ is not zero at any point of $M$.

### 1.5 Example

Surfaces of revolution.

### 1.6 Example

//



## 4.2 Patch Computations

### 2.1 Definition

If $\mathbf{x}:D\to\mathbb{R}^3$ is patch, for each point $(u_0,v_0)\in D$:

- (1) The velocity vector at $u_0$ of the $u$-parameter curve, $v=v_0$ is denoted by $\mathbf{x}_u(u_0,v_0)$
- (2) The velocity vector at $v_0$ of the $v$-parameter curve, $u=u_0$ is denoted by $\mathbf{x}_v(u_0,v_0)$

$\mathbf{x}_u(u_0,v_0),\mathbf{x}_v(u_0,v_0)$ are called the partial velocities of $\mathbf{x}$ at $(u_0,v_0)$.

### 2.2 Example

The geographical patch in the sphere.

### 2.3 Definition

A regular mapping $\mathbf{x}:D\to\mathbb{R}^3$ whose image lies in a surface $M$ is called

a parametrization of the region $\mathbf{x}(D)$ in $M$.

### 2.4 Example

Parametrization of a surface of revolution.

### 2.5 Example

Torus of revolution $T$.

### 2.6 Definition

A ruled surface

$x(u,v)=\beta(u)+v\delta(u)$.



## 4.3 Differentiable Functions and Tangent Vectors

### Book

For a function $F:\mathbb{R}^n\to M$, each patch $x$ in $M$ gives a coordinate expression $x^{-1}(F)$ for $F$.

$F$ is differentiable if all its coordinate expressions are differentiable.

### 3.1 Lemma

If $\alpha:I\to M$ is a curve whose image lies in $x(D)$ of a single patch $x$,

then there exists unique differentiable functions $a_1,a_2$ on $I$ such that

$\alpha(t)=x(a_1(t),a_2(t))$.

the coordinate functions of the curve $\alpha$ with respect to $x$.

### 3.2 Theorem

Let $M$ be a surface. If $F:\mathbb{R}^n\to\mathbb{R}^3$ is a mapping whose image lies in $M$,

then $F:\mathbb{R}^n\to M$ is differentiable.

### 3.3 Corollary

If $x,y$ are patches in $M$ whose images overlap, $x^{-1}y$ and $y^{-1}x$ are mappings.

### 3.4 Corollary

If $x,y$ are overlapping patches in $M$, then there exist unique differentiable functions $\overline{u},\overline{v}$

such that $y(u,v)=x(\overline{u}(u,v),\overline{v}(u,v))$.

### 3.5 Definition

Let $p\in M$. $v\in T_p\mathbb{R}^3$ is tangent to $M$ at $p$ if $v$ is a velocity of some curve in $M$.

### 3.6 Lemma

Let $p\in M$, and let $x$ be a patch such that $x(u_0,v_0)=p$. $v\in T_p\mathbb{R}^3$ is tangent to $M$

iff $v$ is a linear combination of $x_u(u_0,v_0)$ and $x_v(u_0,v_0)$.

### 3.7 Definition

A vector field $Z$ on $M$ is a function on $M$ such that $Z(p)\in T_p\mathbb{R}^3$.

A vector field $V$ is called a tangent vector field on $M$ if $V(p)\in T_pM$.

- a tangent vector field on $M$
- a normal vector field on $M$

### 3.8 Lemma

If $M:g=c$ is a surface in $\mathbb{R}^3$, then the gradient vector field $\nabla g=\sum{\partial g\over\partial x_i}U_i$ is a non-vanishing normal vector field on the entire surface $M$.

### 3.9 Example

$S:g=\sum {x_i}^2=r^2$

$\nabla g=\sum 2x_iU_i$

### 3.10 Definition

Let $v\in T_pM$, and let $f$ be a differentiable real-valued function on $M$.

The derivative $v[f]$ of $f$ with respect to $v$ is $({d\over dt})(f\alpha)(0)$ for all curves $\alpha$ in $M$ with initial velocity $v$.



## 4.4 Differential Forms on a Surface

### 4.1 Definition

A 2-form $\eta$ on $M$ is a real-valued function on $T(M)\times T(M)$ such that

(1) bi-linear

(2) $\eta(v,w)=-\eta(w,v)$

### 4.2 Lemma

$\eta(av+bw,cv+dw)=(ad-bc)\eta(v,w)$

### 4.3 Definition

If $\phi$ and $\psi$ are 1-forms on $M$, the wedge product $\phi\wedge\psi$ is the 2-form on $M$ such that

$(\phi\wedge\psi)(v,w)=\phi(v)\psi(w)-\phi(w)\psi(v)$.

### 4.4. Definition

Let $\phi$ be a 1-form on $M$. Then the exterior derivative $d\phi$ of $\phi$ is the 2-form such that

for any patch $\mathbf{x}$ in $M$, $d\phi(\mathbf{x}_u,\mathbf{x}_v)
=d_\mathbf{x}\phi(\mathbf{x}_u,\mathbf{x}_v)
={\partial\over\partial u}(\phi(\mathbf{x}_v))-{\partial\over\partial v}(\phi(\mathbf{x}_u))$.

### 4.5 Lemma

Let $\phi$ be a 1-form on $M$. If $\mathbf{x}$ and $\mathbf{y}$ are patches in $M$, then $d_\mathbf{x}\phi=d_\mathbf{y}\phi$ on the overlap.

### 4.6 Theorem

If $f$ is a real-valued function on $M$, then $d(df)=0$.

### 4.7 Example

$u_1=u$, $u_2=v$ : the natural coordinate functions

$U_1$, $U_2$ : the natural frame field

$f$ : function

$\phi$ : 1-form

$\eta$ : 2-form

(1) $\phi=f_1du_1+f_2du_2$, where $f_i=\phi(U_i)$.

(2) $\eta=gdu_1du_2$, where $g=\eta(U_1,U_2)$.

(3) $\psi=g_1du_1+g_2du_2$ $\Rightarrow$ $\phi\wedge\psi=(f_1g_2-f_2g_1)du_1du_2$

(4) $df={\partial\over\partial u_1}du_1+{\partial\over\partial u_2}du_2$.

(5) $d\phi=({\partial f_2\over\partial u_1}-{\partial f_1\over\partial u_2})du_1du_2$

### 4.8 Definition

A form $\phi$ is closed if its exterior derivative is zero.

$\phi$ is exact if it is the exterior derivative of some form.

### Book

Every exact form is closed.

## 4.5 Mapping of Surfaces

### 5.1 Definition

A function $F:M\to N$ is differentiable if for each patch $\mathbf{x}$ in $M$ and $\mathbf{y}$ in $N$

$\mathbf{y}^{-1}F\mathbf{x}$ is differentiable.

$F$ is then called a mapping of surfaces.

### 5.2 Example

//

### 5.3 Definition

Let $F:M\to N$ be a mapping of surfaces. The tangent map $F_*:T(M)\to T(N)$ of $F$.

If $\mathbf{v}$ is the initial velocity of $\alpha$ in $M$, then $F_*(\mathbf{v})$ is the initial velocity of $F(\alpha)$ in $N$.

### 5.4 Theorem

Let $F:M\to N$ be a mapping of surfaces, and suppose that $F_{*p}:T_p(M)\to T_{F(p)}(N)$

is a linear isomorphism at $p\in M$.

Then there exists a neighborhood $\mathcal{U}$ of $p$ in $M$ such that the restriction of $F$ to $\mathcal{U}$ is a diffeomorphism

onto a neighborhood $\mathcal{V}$ of $F(p)$ in $N$.

### 5.5 Example

(1) open rectangle is diffeomorphic to the entire plane.

(2) sphere minus one point is diffeomorphic to the entire plane.

(3) //

### 5.6 Definition

Let $F:M\to N$ be a mapping of surfaces.

(1) $\phi$ is a 1-form on $N$, let $F^*\phi$ be the 1-form on $M$ such that

$F^*\phi(\mathbf{v})=\phi(F_*\mathbf{v})$

(2) $\eta$ is a 2-form on $N$, let $F^*\eta$ be the 2-form on $M$ such that

$F^*\eta(\mathbf{v},\mathbf{w})=\eta(F_*\mathbf{v},F_*\mathbf{w})$

### Book

$F^*f=fF$

### 5.7 Theorem

Let $F:M\to N$ be a mapping of surfaces, and let $\xi$ and $\eta$ be forms on $N$.

(1) $F^*(\xi+\eta)=F^*(\xi)+F^*(\eta)$

(2) $F^*(\xi\wedge\eta)=F^*(\xi)\wedge F^*(\eta)$

(3) $F^*(d\xi)=d(F^*\xi)$



## 4.6 Integration of Forms

//



## 4.7 Topological Properties of Surfaces

//



## 4.8 Manifolds

//



# 5. Shape Operators

## 5.1 The Shape Operator of $M\in\mathbb{R}^3$

### Book

Let $Z$ be a vector field on $M$.

compute $\nabla_\mathbf{v} Z$

#### Method 1.

Let $\alpha$ be a curve in $M$ with $\alpha'(0)=\mathbf{v}$.

$\nabla_vZ=(Z(\alpha))'(0)$.

#### Method 2.

$Z=\sum z_iU_i$

$\nabla_vZ=\sum \mathbf{v}[z_i]U_i$



### 1.1 Definition

$p\in M$, $\mathbf{v}\in T_pM$

Let $S_p(\mathbf{v})=-\nabla_\mathbf{v}U$ where $U$ is a unit normal vector field on a neighborhood of $p$ in $M$.

$S_p$ is called the shape operator of $M$ at $p$ derived from $U$.



### 1.2 Lemma

For each $p\in M$, $S_p$ is linear operator

$S_p:T_pM\to T_pM$ on $T_pM$.



### 1.3 Example

//



### 1.4 Lemma

For each $p\in M$, $S_p$ is symmetric.

$S(\mathbf{v})\cdot\mathbf{w}=S(\mathbf{w})\cdot\mathbf{v}$





## 5.2 Normal Curvature

### 2.1 Lemma

$\alpha$ is a curve in $M$

$\alpha''\cdot U=S(\alpha')\cdot \alpha'$



### 2.2 Definition

Let $\mathbf{u}\in T_pM$ be a unit vector. 

Then $k(\mathbf{u})=S(\mathbf{u})\cdot\mathbf{u}$ is called the normal curvature of $M$ in the $\mathbf{u}$ direction.



### Book

Let $\alpha$ be a unit-speed curve in $M$ with $\alpha'(0)=\mathbf{u}$.

$k(\mathbf{u})=S(\mathbf{u})\cdot\mathbf{u}=\alpha''(0)\cdot U(p)=\kappa(0)N(0)\cdot U(p)=\kappa(0)cos\theta$

where $\theta$ is the angle between the principal normal $N(0)$ and the surface normal $U(p)$.



### 2.3 Definition

Let $p\in M$.

The maximum and minimum values of the normal curvature $k(\mathbf{u})$ are called

the principal curvature of $M$ at $p$, and are denoted by $k_1$ and $k_2$.

principal directions

principal vectors



### 2.4 Definition

$p\in M$ is umbilic if the normal curvature is constant.



### 2.5 Theorem

(1) If $p\in M$ is umbilic, then $S_p(\mathbf{v})=k\mathbf{v}$ ($k=k_1=k_2$).

(2) If $p\in M$ is non-umbilic, then there are exactly two principal directions, and these are orthogonal.

If $e_1$ and $e_2$ are principal vectors in these directions, then

$S(e_1)=k_1e_1$, $S(e_2)=k_2e_2$



### 2.6 Corollary

$\mathbf{u}=\cos(t)e_1+\sin(t)e_2$

$k(\mathbf{u})=k_1\cos^2(t)+k_2\sin^2(t)$





## 5.3 Gaussian Curvature

### 3.1 Definition

The Gaussian curvature of $M$ is the real-valued function $K$ on $M$ such that $K(p)=\det S_p$.

The mean curvature of $M$ is $H(p)=1/2\operatorname{trace}S_p$.



### 3.2 Lemma

$K=k_1k_2$, $H={1\over 2}(k_1+k_2)$



### 3.3 Remark

The sign of Gaussian curvature at $p$.

//



### 3.4 Lemma

If $\mathbf{v}, \mathbf{w}\in T_pM$ are linearly independent, then

$S(\mathbf{v})\times S(\mathbf{w})=K(p)(\mathbf{v}\times\mathbf{w})$

$S(\mathbf{v})\times\mathbf{w}+\mathbf{v}\times S(\mathbf{w})=2H(p)(\mathbf{v}\times\mathbf{w})$

### Book

If $V$ and $W$ are vector fields that are linearly independent at each point,

$S(V)\times S(W)=K(V\times W)$

$S(V)\times W+V\times S(W)=2H(V\times W)$ 



$\displaystyle
K={(S(V)\times S(W))\cdot(V\times W)\over(V\times W)\cdot(V\times W)}$

$\displaystyle
H={(S(V)\times W+V\times S(W))\cdot(V\times W)\over2(V\times W)\cdot(V\times W)}$



$K$ and $H$ are differentiable.



### 3.5 Corollary

$k_1,k_2=H\pm\sqrt{H^2-K}$



### 3.6 Definition

$M$ is flat if its Gaussian curvature is zero.

$M$ is minimal if its mean curvature is zero.





## 5.4 Computational Techniques

//