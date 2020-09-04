---
title: Resumen de la Clase XXVII
---

## Apuntes de la clase del 26 de agosto de 2020

En esta clase se introducirán los conceptos previos a compacidad

__Definición 1:__ Decimos que una cubierta abierta de un conjunto $$E\subset\mathbb{R}^n$$ es una colección o familia $$\{G_{\lambda}: \lambda\in\Lambda\}$$ de subconjuntos abiertos de $$\mathbb{R}^n$$ tales que $$E\subset\displaystyle\bigcup_{\lambda\in\Lambda}{G_{\lambda} }$$.

__Definición 2:__ Decimos que en un subconjunto K de $$\mathbb{R}^n$$ es compacto si toda cubierta abierta de K contiene una subcubierta finita. Es decir si $$\{G_{\lambda}: \lambda\in\Lambda\}$$ es una cubierta abierta de K $$\Longrightarrow$$ existe un número finito de indices $$\lambda_1 ,\dotsb ,\lambda_n$$  tal que K$$\subset G_{\lambda 1}\cup G_{\lambda 2}\dotsc \cup G_{\lambda n}.$$

__Definición 3:__ Decimos que un subconjunto K de $$\mathbb{R}^n$$ está acotado si existe una bola abierta $$B_r(\vec{0})$$ en $$\mathbb{R}^n$$ tal que $$K\subset B_r(\vec{0})$$

#### Teorema 1: 

Si $$K\subset\mathbb{R}^n$$ es un conjunto compacto $$\Longrightarrow$$ K es acotado.

__Demostración:__ 

Notemos que $$\mathscr{C}=\{B_r(\vec{0}): r\in\mathbb{N}\}$$ es una cubierta abierta de $$\mathbb{R}^n$$ y por lo tanto de K. Es decir, $$K\subset\displaystyle\bigcup_{r\in\mathbb{N}}B_r(\vec{0})$$ como K es compacto,
$$\mathscr{C}$$ tiene una subcubierta finita que cubre a K  digamos $$K\subset\displaystyle\bigcup_{i=1}^{m} B_{r_i}(\vec{0})$$ 
como las bolas son concentricas, se tiene que $$\displaystyle\bigcup_{i=1}^{m}B_{r_i}(\vec{0})=B_{r_m}(\vec{0}).$$
Donde $$r_m$$ es el máximo de los radios considerados. Es decir $$K\subset B_{r_m}(\vec{0})$$
lo que significa que K está acotado $$\blacksquare$$\\

#### Teorema 2:

Si $$K\subset\mathbb{R}^n$$ es un conjunto compacto $$\Longrightarrow$$ K es cerrado.

__Demostración:__

Demostraremos que el complemento de K es un conjunto abierto.
Sea $$\vec{p}\in K^c$$ un punto arbitrario 
Pd. $$\exists$$ una bola abierta $$B_r(\vec{p})\subset K^c$$
para cada punto $$\vec{x}\in K$$ sea $$r_{\vec{x}} = \frac{d(\vec{p},\vec{q})}{2}$$ de manera que $$B_{r_{\vec{x}}(\vec{x})}\cap B_{r_{\vec{x}}}(\vec{p})=\emptyset$$
Notemos que la familia de bolas abiertas $$\mathscr{F}=\{B_{r_{\vec{x}}}(\vec{x}): \vec{x}\in K\}$$
es una cubierta abierta de K , es decir, $$K\subset\displaystyle\bigcup_{\vec{x}\in K} B_{r_{\vec{x}}}(\vec{x})$$
como K es compacto, $$\mathscr{F}$$ tiene una subcubierta finita que cubre a K.
Es decir, existe un número finito de puntos $$x_1,\dotsb , x_n\in K$$ 
tales que $$K\subset\displaystyle\bigcup_{i=1}^{n}B_{r_{x_i}}(x_i)$$ Notemos que las
correspondientes bolas abiertas con centro en $$\vec{p},$$ $$B_{r_{x_i}}(\vec{p})$$ 
al ser concentricas y al ser un número finito, su intersección 
es la de menor radio, de modo que, si hacemos r=mín $$\{r_{x_1},\dotsb ,r_{x_n}\}$$
tenemos $$B_r(\vec{p})=\displaystyle\bigcap_{i=1}^{n}B_{r_{x_i}}(\vec{p})$$
como para cada $$i=1,\dotsb ,n$$ se tiene que:
$$B_{r_{x_i}}(x_i)\cap B_{r_{x_i}}(\vec{p})=\emptyset$$
y $$B_r(p)\subset B_{r_{x_i}}(\vec{p})\Longrightarrow$$ $$B_{r_{x_i}}\cap B_r (\vec{p})=\emptyset$$ $$\forall i=1,\dotsb ,n.$$
de manera $$(\displaystyle\bigcup_{i=1}^{n} B_{r_{x_i}}(x_i))\cap B_r (\vec{p})=\emptyset$$
como $$K\subset (\displaystyle\bigcup_{i=1}^{n} B_{r_{x_i}}(x_i))\Longrightarrow$$ $$K\cap B_r (\vec{p})=\emptyset$$ $$\therefore$$ $$B_r(\vec{p})\subset K^c$$ 
lo que prueba que $$\vec{p}$$ es un punto interior de $$K^c$$
$$\therefore$$ $$K^c$$ es abierto 
$$\therefore$$ $$K$$ es cerrado. $$\blacksquare$$


Del teorema 1 y 2 se tiene que si $$K\subset\mathbb{R}^n$$ es un conjunto compacto $$\Longrightarrow$$ K es cerrado y acotado en $$\mathbb{R}^n.$$\\

#### Teorema 3:

Sean $$C\subset\mathbb{R}^n$$ un conjunto compacto y $$K\subset C$$ cerrado $$\Longrightarrow$$ K es compacto.

__Demostración:__

Sea $$\mathscr{F}=\{V_\lambda : \lambda\in\Lambda\}$$ una cubierta abierta de K 
Primero notemos que la familia $$\mathscr{F}$$ no necesariamente 
es una cubierta de C, sin embargo, $$\{V_\lambda: \lambda\in\Lambda\}\cup K^c$$ 
si forma una cubierta abierta de C. Como C es compacto,
esta cubierta abierta tiene una subcubierta abierta finita de C
llamemos $$\gamma$$ a esta subcubierta finita y notemos que $$\gamma$$ cubre a K 
ahora si $$K^c$$ no es elemento de $$\gamma\Longrightarrow\gamma\subset\mathscr{F}$$ 
$$\therefore$$ K es compacto. Si $$K^c$$ es un elemento de $$\gamma\Longrightarrow$$ $$\gamma - K^c \subset\mathscr{F}$$
y sigue cubriendo a K. $$\therefore$$ K es compacto. $$\blacksquare$$
