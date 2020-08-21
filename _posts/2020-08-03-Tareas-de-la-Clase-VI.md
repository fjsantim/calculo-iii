---
title: Tareas de la clase VI
---

No estoy seguro de que día dejaron esto pero lo dejaron c:

### Propiedades del producto de las Matrices cuadradas

Sean las Matrices $$A_{n,n},B_{n,n}$$ ambas matrices de $$n\times n$$ con entradas en $$\mathbb{R}$$, donde

$$A_{mn}=\begin{pmatrix}
a_{1,1}& a_{1,2}&a_{1,3}&\dots &a_{1,n}\\
a_{2,1}& a_{2,2}&a_{3,3}&\cdots &a_{2,n}\\
\vdots & \vdots & \vdots & \ddots & \vdots \\
a_{n,1}& a_{n,2}&a_{n,3}& \cdots &a_{n,n}
\end{pmatrix}$$

$$B_{nn}=\begin{pmatrix}
b_{1,1}& b_{1,2}&b_{1,3}& \cdots &b_{1,n}\\
b_{2,1}& b_{2,2}&b_{3,3}& \cdots &b_{2,n}\\
\vdots & \vdots & \vdots & \ddots & \vdots \\
b_{n,1}& b_{n,2}&b_{n,3}&\cdots &b_{n,n}
\end{pmatrix}$$

La multiplicación de matrices se define como:

$$\begin{split}
A_{nn}B_{nn} &= \begin{pmatrix}
a_{1,1}& a_{1,2}&a_{1,3}&\cdots &a_{1,n}\\
a_{2,1}& a_{2,2}&a_{3,3}&\cdots &a_{2,n}\\
\vdots & \vdots & \vdots & \ddots & \vdots \\
a_{n,1}& a_{n,2}&a_{n,3}&\cdots&a_{n,n}
\end{pmatrix} \cdot \begin{pmatrix}
b_{1,1}& b_{1,2}&b_{1,3}&\cdots &b_{1,n}\\
b_{2,1}& b_{2,2}&b_{3,3}&\cdots &b_{2,n}\\
\vdots & \vdots & \vdots & \ddots & \vdots \\
b_{n,1}& b_{n,2}&b_{n,3}&\cdots &b_{n,n}
\end{pmatrix} \\
&= \begin{pmatrix}
c_{1,1}& c_{1,2}&c_{1,3}&\cdots &c_{1,n}\\
c_{2,1}& c_{2,2}&c_{3,3}&\cdots &c_{2,n}\\
\vdots & \vdots & \vdots & \ddots & \vdots \\
c_{n,1}& c_{n,2}&c_{n,3}&\cdots &c_{n,n}
\end{pmatrix}=C_{mn}
\end{split}$$

Donde cada $$c_{ij}$$ con $$1\leq i\leq n$$ ,$$1\leq j\leq n$$ es igual a:

$$c_{ij}=a_{i1}b_{1j}+a_{i2}b_{2j}+...+a_{in}b_{nj}$$

luego sea

$$c_{ij}=\sum_{k=1}^{n}a_{ik}b_{kj}$$

Sus propiedades:

$$\textrm{Sean }A,B\textrm{Matrices con entradas en los reales entonces:}\ AB\in \textrm{ (clausura)}$$

$$\textrm{ No es Conmutativa }AB\neq BA$$

Asociativa respecto a la multiplicación matricial

$$(AB)C=A(BC)$$

Distributividad

$$A(B+C)=AB+AC$$

$$(A+B)C=AC+BC$$

Matriz Identidad $$I$$

$$AI=IA$$

Donde

$$I=(x)_{ij} ,x=1, \textrm{ si  } i=j; x=0, \textrm{ si } i\neq j$$

