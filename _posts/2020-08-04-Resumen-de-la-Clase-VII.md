---
title: Resumen de la Clase VII
---

## Apuntes de la clase del 4 de agosto de 2020

La clase del día 4 de agosto comenzamos viendo ejemplos de las superficies de nivel de las funciones:

* Sea $$f: \mathbb{R}^3 \to \mathbb{R}$$ dada por $$f(x,y,z)=x^2 + (y-2)^2 -1$$, graficar las curvas de nivel $$0$$, $$1$$ y $$-1$$.

* Sea $$f: \mathbb{R}^3 \to \mathbb{R}$$ dada por $$f(x,y,z) = x^2 +y^2 - z^2$$, graficar las curvas de nivel $$0$$, $$1$$ y $$-1$$.

	+ Para $$c=-1$$, $$S_1 =\lbrace (x,y,z)\mid x^2 + y^2 -z^2 =-1\rbrace$$

	+ Para $$c=0$$, $$S_1 =\lbrace (x,y,z)\mid x^2 + y^2 -z^2 =0\rbrace$$

	+ Para $$c=1$$, $$S_1 =\lbrace (x,y,z)\mid x^2 + y^2 -z^2 =1\rbrace$$
	
![]({{"img/c-7/1.png" | prepend: site.baseurl }}){:height="90%" width="90%"}

### Funciones de $$\mathbb{R}$$ en $$\mathbb{R}^n$$

> La función:
>
> $$\gamma(t)=(\gamma_1(t),\gamma_2(t),\dots,\gamma_n(t))$$
>
> para la cual cada $$\gamma_i(t)$$ es una función $$\gamma_i : I\subset\mathbb{R}\to\mathbb{R}$$ es una _función vectorial_ que "vive" en $$\mathbb{R}^n$$.

* La gráfica de $$\gamma(t)$$ es una curva $$\Gamma$$ en $$\mathbb{R}$$.

* $$\gamma$$ es llamada la parametrización o trayectoria de la curva $$\Gamma$$.

Se anexa el ejemplo 3: gráfica de la curva con parametrización $$\gamma(t)=(\cos{(t)},\sin{(t)},t)$$ con $$t\in\mathbb{R}$$. Cabe destacar que la curva parece "envolver"
al cilindro de radio $$1$$ centrado en el eje $$z$$, mismo que se representa en la siguiente figura con color rojo y a $$\gamma$$ con color negro.

![]({{"img/c-7/2.png" | prepend: site.baseurl }}){:height="100%" width="100%"}

### Matrices

> Una matriz es un arreglo bidimensional que contiene $$m$$ renglones y $$n$$ columnas y cada elemento de ella es un número real. Al conjunto de todas las matrices de
$$m\times n$$ con entradas en $$\mathbb{R}$$ se le denota como: $$M_{m\times n}(\mathbb{R})$$.

$$\left(\begin{array}{ccccc}
a_{11} & a_{12} & a_{13} & \cdots & a_{1n}\\
a_{21} & a_{22} & a_{23} & \cdots & a_{2n}\\
\vdots & \vdots & \vdots & \ddots & \vdots\\
a_{m1} & a_{m2} & a_{m3} & \cdots & a_{mn}
\end{array}\right)$$

También se puede representar en su forma compacta:

$$A=(a_{ij})_{1\leq i \leq m, 1\leq j \leq n} $$

Cada renglon o fila de una matriz se puede representar como un vector fila o columna:

* El i-ésimo renglón (o fila):

$$\vec{a}_i = (a_{i1},a_{i2},\dots,a_{in})$$

* La j-ésima columna:

$$\vec{a}_j = \begin{pmatrix}a_{1j}\\
a_{2j}\\
\vdots\\
a_{nj}
\end{pmatrix}$$

### Operaciones con matrices:

* __Suma__; sean dos matrices $$A$$ y $$B$$ de $$m\times n$$:

$$\begin{split}
A + B =& \left(\begin{array}{ccccc}
a_{11} & a_{12} & \cdots & a_{1n}\\
a_{21} & a_{22} & \cdots & a_{2n}\\
\vdots & \vdots & \ddots & \vdots\\
a_{m1} & a_{m2} & \cdots & a_{mn}
\end{array}\right) + \left(\begin{array}{ccccc}
b_{11} & b_{12} & \cdots & b_{1n}\\
b_{21} & b_{22} & \cdots & b_{2n}\\
\vdots & \vdots & \ddots & \vdots\\
b_{m1} & b_{m2} & \cdots & b_{mn}
\end{array}\right) \\

=& \left(\begin{array}{ccccc}
a_{11} + b_{11} & a_{12} + b_{12} & \cdots & a_{1n} + b_{1n} \\
a_{21} + b_{21} & a_{22} + b_{22} & \cdots & a_{2n} + b_{2n} \\
\vdots & \vdots & \ddots & \vdots\\
a_{m1} + b_{m1} & a_{m2} + b_{m2} & \cdots & a_{mn} + b_{mn} 
\end{array}\right)
\end{split}$$

Es importante recordar que las matrices $$A$$ y $$B$$ deben ser del mismo tamaño $$m\times n$$ para poder ser suamdas.

* __Multiplicación por escalares__; sean una matriz de $$m\times n$$ y un escalar $$\lambda\in\mathbb{R}$$:

$$\begin{split}
A\lambda = \lambda A =& \lambda \left(\begin{array}{ccccc}
a_{11} & a_{12} & \cdots & a_{1n}\\
a_{21} & a_{22} & \cdots & a_{2n}\\
\vdots & \vdots & \ddots & \vdots\\
a_{m1} & a_{m2} & \cdots & a_{mn}
\end{array}\right) \\
=& \left(\begin{array}{ccccc}
a_{11} & a_{12} & \cdots & a_{1n}\\
a_{21} & a_{22} & \cdots & a_{2n}\\
\vdots & \vdots & \ddots & \vdots\\
a_{m1} & a_{m2} & \cdots & a_{mn}
\end{array}\right) \lambda \\
=& \left(\begin{array}{ccccc}
\lambda a_{11} & \lambda a_{12} & \cdots & \lambda a_{1n}\\
\lambda a_{21} & \lambda a_{22} & \cdots & \lambda a_{2n}\\
\vdots & \vdots & \ddots & \vdots\\
\lambda a_{m1} & \lambda a_{m2} & \cdots & \lambda a_{mn}
\end{array}\right)
\end{split}$$

* __Multiplicación de matrices__; sean dos matrices $$A\in M_{m\times n}(\mathbb{R})$$ y $$B\in M_{n\times p}(\mathbb{R})$$, definimos la multiplicación de matrices de la siguiente forma:

	$$AB=(c_{ij})_{1\leq i\leq m, 1\leq j\leq n}$$

	donde: $$c_{ij}=\sum a_{ik}b_{kj}$$
	
	Nota: es importante recalcar el orden en que se multiplican las matrices, pues en general $$AB\ne BA$$.

__Propiedades de las operaciones con matrices__

Dados $$A,B,C \in M_{m\times n}$$ y $$c,d \in \mathbb{R}$$ escalares:

* $$A+B=B+A$$

* $$c(A+B)=cA+cB$$

* $$(c+d)A=cA+dA$$

* $$(A+B)+C=A+(C+D)$$

* $$(cd)A=c(dA)$$

* $$A(BC)=(AB)C$$

* $$A(B+C)=AB+AC$$

* $$c(AB)=(cA)B=A(cB)$$

* $$AI=A$$

* $$IA=A$$

Donde $$I$$ es la matriz identidad $$I=(\delta_{ij})$$ donde $$\delta_{ij}$$ denota que las entradas $$i=j$$ tienen valor $$1$$ y las entradas $$i\ne j$$ valor $$0$$.

### Matriz transpuesta

> Sea $$A\in M_{m\times n}$$, $$A^T$$ es la __transpuesta__ de A y es el resultado de intercambiar los renglones y columnas de $$A$$.
>
> Si $$A=\begin{pmatrix}a_{11} & a_{12} & \cdots & a_{1n}\\a_{21} & a_{22} & \cdots & a_{2n}\\\vdots & \vdots & \ddots & \vdots\\a_{m1} & a_{m2} & \cdots & a_{mn}\end{pmatrix}$$, entonces $$A^T = \begin{pmatrix}a_{11} & a_{21} & \cdots & a_{m1}\\a_{12} & a_{22} & \cdots & a_{m2}\\\vdots & \vdots & \ddots & \vdots\\a_{1n} & a_{2n} & \cdots & a_{mm}\end{pmatrix}$$

__Propiedades de la matriz transpuesta__

* $$(A^{T})^{T}=A$$

* $$A^T + B^T = (A+B)^T$$

* $$(ABC)^T = C^T B^T A^T $$

### Matriz inversa

> Sea $$A\in M_{m\times n}$$, decimos que es invertible si existe $$A^{-1} \in M_{m\times n}$$, llamada la __inversa de $$A$$__	si:
>
> $$AA^{-1}=A^{-1}A=I$$

__Propiedades de la matriz inversa__

Sean $$A$$, $$B$$ y $$C$$ matrices invertibles:

* $$(A^{-1})^{-1}=A$$

* $$(AB)^{-1}=B^{-1}A^{-1}$$ 

* $$AC=AD\implies C=D$$

* $$AC=0$$ solo con $$A$$ invertible, $$C=0$$
	
