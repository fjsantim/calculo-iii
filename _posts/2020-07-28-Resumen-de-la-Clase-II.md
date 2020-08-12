---
title: Resumen de la Clase II
---

## Apuntes de la clase del 28 de julio de 2020

### Vectores
Un vector $$\vec{v}$$, está determinado por dos puntos, un punto inicial __$$P$$__ y un punto final __$$Q$$__. Donde 
$$\vec{v} = \vec{\textbf{PQ}}$$

Las propiedades que determinan a un vector son: __magnitud, dirección y sentido__.
La magnitud de $$\vec{v}$$ se denota como $$\|v\|$$ y es la distancia de __$$P$$__ a __$$Q$$__. 
Donde  $$\textbf{P}= (a_{1},b_{1},c_{1})$$ y $$ \textbf{Q}= (a_{2},b_{2},c_{2})$$. Dicha distancia se calcula como:

$$\|v\|= \|\vec{\textbf{PQ}}\| = \sqrt{(a_{2}-a_{1})^2+(b_{2}-b_{1})^2+(c_{2}-c_{1})^2}$$


__Componentes de un vector en $$\mathbb{R}^2$$__

Los componentes del vector $$\textbf{v}= \vec{\textbf{PQ}}$$, donde $$\textbf{P}=(a_{1},b_{1})$$ y $$\textbf{Q}=(a_{2},b_{2})$$ son las cantidades:

$$a=a_{2} - a_{1}$$

$$b=b_{2}-b_{2}$$

__Terminología__

* Dos vectores, $$\vec{v}$$ y $$\vec{w}$$ son paralelos si las rectas a través de $$\vec{v}$$ y $$\vec{w}$$ son paralelas. Los vectores paralelos tienen misma dirección y pueden tener sentidos contrarios.

* Un vector $$\vec{v}$$ experimemta una translación cuando es movido para comenzar en un nuevo punto sin cambiar su magnitud o dirección. El vector resultante tiene la misma longitud y dirección pero diferente punto inicial.

* Dos vectore $$\vec{v}$$ y $$\vec{w}$$ son equivalentes si:
	+ Uno es una traslación del otro.
	+ Son equivalentes sí y sólo sí tienen los mismos componentes. 

	Los vectores equivalentes tienen la misma magnitud y dirección, pero pueden iniciar en puntos diferentes.

* La magnitud del vector $$ \vec{v}= \langle a,b \rangle$$ en términos de sus componentes es:

	$$\|v\|=\|\vec{PQ}\|= \sqrt{a^{2}+b^{2}}$$

* El __vector nulo__ es el vector $$\vec{0}=\langle 0,0 \rangle$$ de dirección cero. Es el único que no tiene dirección. 

### Operanciones con vectores

* La suma de varios vectores $\vec{v_{1}}, \vec{v_{2}},...,\vec{v_{n}}$ se representa como:

	$$\vec{v}= \vec{v_{1}}+ \vec{v_{2}}+...+\vec{v_{n}}$$

En el caso de la mutiplicación por escalares, el término escalar se refiere a un número real. Si $$\lambda$$ es un escalar y $$\vec{v}$$ es un vector no nulo, el múltiplo escalar $$\lambda  \vec{v}$$

* $$\lambda \vec{v}$$  tiene la magnitud $$\mid\lambda\mid \mid\vec{v}\mid$$
   
* Tiene el mismo sentido que $$\vec{v}$$ si $$\lambda>0$$

* Tiene el sentido contrario a $$\vec{v}$$ si $$\lambda<0$$

* Un vector $$\vec{w}$$ es paralelo a $$\vec{v}$$ sí y sólo sí $$\vec{w}=\lambda \vec{v}$$

* $$\vec{v}+\vec{w} = \langle a+c, b+d \rangle$$

* $$\vec{v}-\vec{w} = \langle a-c, b-d \rangle$$

* $$\lambda \vec{v} = \langle \lambda a, \lambda b\rangle$$

* $$\vec{v} +0= 0+ \vec{v} = \vec{v}$$

### Propiedades

* Ley conmutativa: $$\vec{v} + \vec{w}= \vec{w}+ \vec{v}$$

* Ley asociativa: $$\vec{u}+ (\vec{v}+ \vec{w})= (\vec{u}+ \vec{v}) + \vec{w}$$

* Ley distributiva para escalares: $$\lambda (\vec{v}+\vec{w}) = \lambda \vec{v}+\lambda \vec{w}$$

### Combinaciones lineales

Una combinación lineal de vectores $$\vec{v}$$ y $$\vec{w}$$ es un vector $$r \vec{v} + s \vec{w}$$, donde $$r$$ y $$s$$ son escalares.

### Vector unitario

* Tienen magnitud 1

* Sus componentes son $$\vec{u}=\langle \cos{(\theta)}, \sin{(\theta)}\rangle$$ Donde $$\theta$$ es el ángulo entre el eje __$$x$$__ y el vector.

* Los unitarios en dirección de los ejes __$$x$$__ y __$$y$$__ se denotan como: $$\hat{i}=\langle 1,0\rangle$$, $$\hat{j}=\langle0,1\rangle$$ (__Vectores canónicos__)

> __Nota:__ Cada vector en el plano es una combinación lineal de $$\hat{i}$$ y $\hat{j}$: $$\vec{v}= \langle a,b\rangle = a \hat{i} + b \hat{j}$$

### Producto punto

El producto punto $$\vec{v} \cdot \vec{w}$$ de dos vetores $$\vec{v}= \langle v_{1},v_{2},v_{3}\rangle$$ y $$\vec{w}= \langle w_{1},w_{2},w_{3}\rangle$$ se define como:

$$\vec{v} \cdot \vec{w} = v_{1} w_{1} + v_{2} w_{2} +v_{3} w_{3}$$

__Propiedades del producto punto__

* $$0\cdot\vec{v}= \vec{v}\cdot 0= 0$$

* $$\vec{v} \cdot \vec{w}=\vec{w} \cdot \vec{v}$$

* $$(\lambda \vec{v})\cdot \vec{w}= \vec{v}\cdot(\lambda \vec{w}) = \lambda (\vec{v} \cdot \vec{w})$$

* $$\vec{u} \cdot (\vec{v} + \vec{w})= \vec{u}\cdot\vec{v} + \vec{u} \cdot \vec{w}$$

* $$(\vec{v}+\vec{w})\cdot \vec{u}= \vec{v} \cdot \vec{u}+ \vec{w}\cdot\vec{u}$$

* $$\vec{v}\cdot\vec{v}=  v_{1} v_{1} + v_{2} v_{2} + v_{3} v_{3} = v_{1}^{2} + v_{2}^2 + v_{3}^2 = \|\vec{v}\|^2$$

### Producto cruz

El producto cruz de los vectores $$\vec{v}=\langle v_{1},v_{2},v_{3}\rangle$$ y $$\vec{w}=\langle w_{1},w_{2},w_{3}\rangle$$ es el vector 

$$\begin{split}\vec{v}\times \vec{w} =& \begin{vmatrix}
\hat{i} & \hat{j} & \hat{k} \\
v_{1}&v_{2}&v_{3} \\
w_{1}&w_{2}&w_{3} \\
\end{vmatrix} \\
=& \begin{vmatrix}
v_{2} & v_{3} \\
w_{2} & w_{3} \\
\end{vmatrix}
\hat{i} - \begin{vmatrix}
v_{1} & v_{3} \\
w_{1} & w_{3} \\
\end{vmatrix} \hat{j}
+\begin{vmatrix}
v_{1} & v_{2} \\
w_{1} & w_{2} \\
\end{vmatrix}\hat{k}\\
= & \hat{i}(v_2 w_3 - v_3 w_2) + \hat{j}(v_3 w_1 - v_1 w_3)
\end{split}
$$

\textbf{Rectas en el espacio}

\end{center} En $R^3$ se usa un vector de dirección $\vec{v}=<a,b,c>$ para determinar la dirección de una recta. \\ Dado que hay muchas rectas con la dirección de $\vec{v}$ es necesario un punto para especificar una única recta. \\

\emph{Ecuaciones de una recta:}
La recta \textit{L} que pasa por $P_{0}= (x_{0},y_{0},z_{0})$ en dirección de $\vec{v}=<a,b,c>$ está dada por: 
\begin{itemize}
\item{Forma vectorial $r(t)$ de \textit{L}: }
\end{itemize}
$r(t)=r_{0}+tv=<x_{0},y_{0},z_{0}>+t<a,b,c>(5)$ donde $r_{0}=<x_{0},y_{0},z_{0}>$\\
\begin{itemize}
\item{Ecuaciones paremétricas de L:}
\end{itemize}
$x(t)=x_{0}+at, y(t)=y_{0}+bt, z(t))= z_{0} +ct$

\begin{center}
\textbf{Planos}
\end{center}
El vector normal n es un vector perpendicular al plano P.
Para determinar a P, basta con identificar un punto en él y
conocer su vector normal.\\

\textbf{Ecuaciones del plano:}
El plano que pasa por $P_{0}=( x_{0},y_{0},z_{0})$ con vector normal $n= <a,b,c>$ satisface:
\begin{itemize}
\item{Forma vectorial: $ n*<x,y,z>=d$ donde $d=ax_{0}+by_{0}+cz_{0}$}
\end{itemize}
\begin{itemize}
\item{Forma escalar: $a(x-x_{0})+b(y-y_{0})+c(z-z_{0})=0$ \\ $ax+by+cz=d$}
\end{itemize}
Los planos coordenados en $R^3$ se definen como el conjunto de puntos donde alguna de las
coordenadas es cero.\\

La intersección del plano P con un plano coordenado es llamada traza.





\end{document}
