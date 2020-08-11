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

\\

\textbf{Componentes de un vector en $R^2$}\\ 
Los componentes del vector $\textbf{v}= \vec{PQ}$, donde $P=(a_{1},b_{1})$ y $Q=(a_{2},b_{2})$ son las cantidades:\\ \begin{center}
$a=a_{2} - a_{1}$\\$b=b_{2}-b_{2}$
\end{center}
\begin{itemize}
    \item{Dos vectores, \textbf{v} y \textbf{w} son paralelos si las rectas a través de \textbf{v} y \textbf{w} son paralelas. Los vectores paralelos tienen misma dirección y pueden tener sentidos contrarios.  }

\end{itemize}
\begin{itemize}
   \item{Un vector \textbf{v} experimemta una translación cuando es movido para comenzar en un nuevo punto sin cambiar su magnitud o dirección. El vector resultante tiene la misma longitud y dirección pero diferente punto inicial.}
\end{itemize}
\begin{itemize}
    \item{Dos vectore \textbf{v} y \textbf{w} son equivalentes si uno es una traslación del otro. 
Son euivalentes sí y sólo sí tienen los mismos componentes. \\ Lo vectores equivalentes tienen la misma magnitud y dirección, pero pueden iniciar en puntos diferentes. }
\end{itemize}
\begin{itemize}
   \item La magnitud del vector $ \vec{v}=<a,b> $ en términos de sus componentes es: \\ 
   \begin{center}
   $||v||=||\vec{PQ}||= \sqrt{a^{2}+b^{2}} $
   \end{center}
\end{itemize}

\begin{itemize}
   \item El \textbf{vector nulo} es el vector $\vec{0}=<0,0>$ de dirección cero. Es el único que no tiene dirección. 
\end{itemize}

\pagebreak

\begin{center}
\textbf{Operanciones con vectores}
\end{center}
 La suma de varios vectores $\vec{v_{1}}, \vec{v_{2}},...,\vec{v_{n}}$ se representa como:
\begin{center}
$\vec{v}= \vec{v_{1}}+ \vec{v_{2}}+...+\vec{v_{n}}$ 
\end{center}
El término escalar se refiere a un número real.\\ Si $\lambda$ es un escalar y $\vec{v}$ es un vector no nulo, el múltiplo escalar $\lambda  \vec{v}$

\begin{itemize}
   \item { $\lambda* \vec{v}$  tiene la magnitud $|\lambda| ||\vec{v}||$}
   
\end{itemize}

\begin{itemize}
  \item {Tiene el mismo sentido que $\vec{v}$ si $\lambda>0$}
\end{itemize}
\begin{itemize}
  \item { Tiene el sentido contrario a $\vec{v}$ si $\lambda<0$}
\end{itemize}
\begin{itemize}
   \item{Un vector $\vec{w}$ es paralelo a $\vec{v}$ sí y sólo sí $\vec{w}=\lambda \vec{v}$}
\end{itemize} Las operaciones se definen como:\\ Si $\vec{v}=<a,b>$ y $\vec{w}=<c,d>$ entonces \begin{itemize}
\item{$\vec{v}+\vec{w} = <a+c, b+d>$}
\end{itemize}
\begin{itemize}
\item{$\vec{v}-\vec{w} = <a-c, b-d>$}
\end{itemize}
\begin{itemize}
\item{$\lambda \vec{v} = <\lambda a, \lambda b>$}
\end{itemize}
\begin{itemize}
\item{$\vec{v} +0= 0+ \vec{v} = \vec{v}$}
\end{itemize}

\textbf{Propiedades}
\begin{itemize}
\item{ Ley conmutativa: $\vec{v} + \vec{w}= \vec{w}+ \vec{v}$ }
\end{itemize}
\begin{itemize}
\item{ Ley asociativa: $\vec{u}+ (\vec{v}+ \vec{w})= (\vec{u}+ \vec{v}) + \vec{w}$}
\end{itemize}
\begin{itemize}
\item{Ley distributiva para escalares: $\lambda (\vec{v}+\vec{w}) = \lambda \vec{v}+\lambda \vec{w}$ }
\end{itemize}
\begin{center}
\textbf{Combinaciones lineales}
\end{center}
Uma combinación lineal de vectores $\vec{v}$ y $\vec{w}$ es un vector $r \vec{v} + s \vec{w}$, donde r y s son escalares.\\

\textbf{Vector unitario}\\ \begin{itemize}
\item{Tienen magnitud 1}
\end{itemize}
\begin{itemize}
\item{Sus componentes son $\vec{u}=<\cos \theta, \sin \theta>$ Donde $\theta$ es el ángulo entre el eje \textit{x} y el vector}
\end{itemize}
\begin{itemize}
\item{Los unitarios en dirección de los ejes \textit{x} y \textit{y} se denotan como: \\$ \vec{i}=<1,0> , \vec{j}=<0,1>$ (\textbf{Vectores canónicos})}
\end{itemize}
\textbf{Nota}\\
Cada vector en el plano es una combinación lineal de $\vec{i}$ y $\vec{j}$: \\ $\vec{v}= <a,b>= a \textit{\textbf{i}} + b \textbf{\textit{j}}$
 \begin{center}
 \textbf{Producto punto}
 \end{center}
El producto punto $\vec{v} * \vec{w}$ de dos vetores $\vec{v}= <v_{1},v_{2},v_{3}>$ y $\vec{w}= <w_{1},w_{2},w_{3}>$ se define como:\\ \begin{center}
$\vec{v} * \vec{w} = v_{1} w_{1} + v_{2} w_{2} +v_{3} w_{3}$
\end{center}
Propiedades \\
\begin{itemize}
\item{ $0*\vec{v}= \vec{v}* 0= 0$}
\end{itemize}
\begin{itemize}
\item{$\vec{v} * \vec{w}=\vec{w} * \vec{v}$}
\end{itemize}
\begin{itemize}
\item{$(\lambda \vec{v})* \vec{w}= \vec{v}*(\lambda \vec{w}) = \lambda (\vec{v} * \vec{w})$}
\end{itemize}
\begin{itemize}
\item{$\vec{u} * (\vec{v} + \vec{w})= \vec{u}*\vec{v} + \vec{u} * \vec{w}$}
\end{itemize}
\begin{itemize}
\item{$(\vec{v}+\vec{w}* \vec{u}= \vec{v} * \vec{u}+ \vec{w}*\vec{u}$}
\end{itemize}
\begin{itemize}
\item{$\vec{v}*\vec{v}=  v_{1} v_{1} + v_{2} v_{2} + v_{3} v_{3} = v_{1}^{2} + v_{2}^2 + v_{3}^2 = ||\vec{v}||^2$}
\end{itemize}
\begin{center}
\textbf{Producto cruz}
\end{center}
El producto cruz de los vectores $\vec{v}=<v_{1},v_{2},v_{3}>$ y $\vec{w}=<w_{1},w_{2},w_{3}>$ es el vector\\ $$
\Vec{V}\times \Vec{W}=
\begin{vmatrix}
i&j&k \\
v_{1}&v_{2}&v_{3} \\
w_{1}&w_{2}&w_{3} \\
\end{vmatrix}
= \begin{vmatrix}
v_{2} & v_{3} \\
w_{2} & w_{3} \\
\end{vmatrix}
\textbf{i} - \begin{vmatrix}
v_{1} & v_{3} \\
w_{1} & w_{3} \\
\end{vmatrix} \textbf{j} +\begin{vmatrix}
v_{1} & v_{2} \\
w_{1} & w_{2} \\
\end{vmatrix}\textbf{k}
$$
\pagebreak
\begin{center}
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
