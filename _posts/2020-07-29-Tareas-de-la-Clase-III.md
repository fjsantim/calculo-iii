---
title: Tareas de la clase III
---

## Tareas de la clase del 29 de julio de 2020

### ¿Qué significa que un conjunto no sea abierto?

Comenzamos recordando la definición de __conjunto abierto__:

> Definición: decimos que un conjunto $$V\subset\mathbb{R}^n$$ es abierto si y solo si para cada punto
$$p\in V$$, existe $$r>0$$ tal que $$B_{r}(p)\subset V$$

- Un enfoque intuitivo seria ver si hay una bola con centro en $$p\in V$$ que no esté dentro del conjunto $$V$$
sin importar el tamaño del radio $$r$$.

- Otra forma viene del cuantificador _para cada_, de este modo si hay al menos un punto $$x \in V$$
en el que no se cumpla la definición esto hace que el conjunto $$V$$ no sea abierto.

- Por otro lado pensemos en la negación de la definición:
	> Decimos que un conjunto $$V\subset\mathbb{R}^{n}$$ no es abierto si y solo si para algún punto 
	$$p\in V$$, no existe $$r>0$$ tal que $$B_{r}(p)\subset V$$.

### Toda bola cerrada en $$\mathbb{R}^n$$ es un conjunto cerrado.

_Demostración:_ Sea $$\vec{x_0}\hspace{1cm}$$ 

Pd. $$\{\mathbb{R}^n\backslash\overline{\mathbb{B}_r(\vec{x}_0)}\}$$ es un conjunto abierto

Sea $$\vec{x}\in\{\mathbb{R}^n\backslash\overline{\mathbb{B}_r(\vec{x}_0)}\}\hspace{1cm}$$ Pd. $$\exists\delta>0$$ tal que $$\mathbb{B}_\delta (\vec{x})\subset\{\mathbb{R}^n\backslash\overline{\mathbb{B}_r(\vec{x}_0)}\}$$
Sea $$\vec{y}\in\mathbb{B}_\delta (\vec{x})\hspace{1cm}$$ Pd. $$\vec{y}\in\{\mathbb{R}^n\backslash\overline{\mathbb{B}_r(\vec{x}_0)}\}$$
como $$\vec{x}\in\{\mathbb{R}^n\backslash\overline{\mathbb{B}_r(\vec{x}_0)}\}\Longrightarrow$$ $$\vec{x}\in\mathbb{R}^n$$ y $$\vec{x}\notin\overline{\mathbb{B}_r(\vec{x}_0)}\Longrightarrow$$ $$d(\vec{x},\vec{x}_0)>r$$

Si definimos $$\delta = d(\vec{x},\vec{x}_0)-r>0\Longrightarrow$$ $$r=d(\vec{x},\vec{x}_0)-\delta$$
como $$\vec{y}\in\mathbb{B}_\delta (\vec{x})\Longrightarrow$$ $$d(\vec{y},\vec{x})<\delta$$
veamos $$d(\vec{x},\vec{x}_0)\leqslant d(\vec{x},\vec{y})+d(\vec{y},\vec{x}_0) < \delta + d(\vec{y},\vec{x}_0)\Longrightarrow$$ 
$$d(\vec{x},\vec{x}_0)<\delta + d(\vec{y},\vec{x}_0)$$

$$\Longrightarrow$$ $$d(\vec{x},\vec{x}_0)-\delta < d(\vec{y},\vec{x}_0)$$ $$\Longrightarrow$$ $$r<d(\vec{y},\vec{x}_0)$$

$$\therefore$$ $$\vec{y}\notin\overline{\mathbb{B}_r(\vec{x}_0)}$$

$$\therefore$$ $$\vec{y}\in\mathbb{R}^n$$ y $$\vec{y}\notin\overline{\mathbb{B}_r(\vec{x}_0)}$$

$$\therefore$$ $$\vec{y}\in\{\mathbb{R}^n\backslash\overline{\mathbb{B}_r(\vec{x}_0)}\}$$

$$\therefore$$ $$\mathbb{B}_\delta (\vec{x})\subset\{\mathbb{R}^n\backslash\overline{\mathbb{B}_r(\vec{x}_0)}\}$$

$$\therefore$$ $$\{\mathbb{R}^n\backslash\overline{\mathbb{B}_r(\vec{x}_0)}\}$$ es un conjunto abierto

$$\therefore$$ $$\overline{\mathbb{B}_r(\vec{x}_0)}$$ es un conjunto cerrado.

### Verificación de los ejemplos de la diapositiva 9

1. El conjunto formado por un único punto es cerrado.
	
	Pensemos en el conjunto $$P={x}$$ y en su complemento $$P^{c}= \mathbb{R} \setminus P$$. Dado cualquier punto $$y\in P^{c}$$ si elegimos $$\displaystyle{r=\frac{d(x,y)}{2}}$$ siempre
	podemos tener una bola abierta $$B_{r}(y)$$ contenida en $$P^{c}$$ sin importar que tan pequeña sea la distancia
	entre $$x$$ y $$y$$. 
	Esto hace que $$P$$ sea un conjunto cerrado por la definición  de _conjunto cerrado_. 
	Esto mismo puede extenderse a $$\mathbb{R}^{n}$$ con el mismo razonamiento.

	![]({{"img/1.png" | prepend: site.baseurl }}){:height="100%" width="100%"}


2. El semiplano formado por el conjunto $$\pi = \{ (x,y)\in\mathbb{R}^{2}:y>0 \}$$ es un conjunto abierto.

	Pensemos en un punto $$q=(x,0)$$ y en algún punto perpendicular a él sobre una distancia $$y>0$$ en el eje $$y$$
	$$p=(x,y)$$. Basta pedir un radio $$\displaystyle{\frac{d(p,q)}{2}}$$ para tener una bola abierta con centro en $$p$$
	$$B_{r}(p)$$ que este completamente contenida en $$\pi$$ ($$B_{r}(p)\subset\pi$$); esto se ilustra en el gráfico de abajo. Esto, al igual que en el ejemplo anterior, sin importar que tan cerca esté la coordenada $$y$$ de $$p$$ del $$0$$ en $$y$$.
	De este modo, por la definición de conjunto abierto, el semiplano $$\pi$$ es un conjunto abierto. Esta situación se ilustra a continuación:

	![]({{"img/2.png" | prepend: site.baseurl }}){:height="100%" width="100%"}

3. Un intervalo [a,b] en $$\mathbb{R}$$ es un conjunto cerrado.

	Comencemos recordando la definición de conjunto cerrado: 
	
	> Decimos que un conjunto $$F\subset\mathbb{R}^{n}$$ es cerrado si y solo si su complemento es abierto.
	Es decir $$\mathbb{R}^{n}\setminus F$$ es abierto.

	Tomemos el complemento de $$[a,b]$$ como $$P^{c}=\mathbb{R}\setminus [a,b]$$. Primero tomemos un un punto $$x\in\mathbb{R}<a$$ y un punto $$y\in\mathbb{R}>b$$. Elegimos ahora
	$$\displaystyle{r_{1}=\frac{d(x,a)}{2}}$$ y $$\displaystyle{r_{2}=\frac{d(b,y)}{2}}$$ de modo que cualesquiera dos bolas abiertas $$B_{r_{1}}(x)$$ y $$B_{r_{2}}(y)$$ están ambas contenidas en $$\mathbb{R}$$.
	Esto es que el complemento de $$[a,b]$$ es abierto y por tanto $$[a,b]$$ es cerrado por definición de _conjunto cerrado_. Un diagrama se muestra a continuación:
	
	![]({{"img/3.png" | prepend: site.baseurl }}){:height="100%" width="100%"}	

4. El conjunto $$C=(-1,1)\times (-1,1)$$ es un conjunto abierto de $$\mathbb{R}^{2}$$.

	En este caso basta pedir una bola de radio $$r$$ con centro en cualquier punto $$p\in C$$ y asegurandonos que dicho radio sea la mitad de la distancia entre
	$$p$$ y cualquier borde del cuadrado que forma el conjuto $$C$$ como se muestra en la imagen de abajo.
	Esta es condición suficiente para ver que se cumple la definición y hace que $$C$$ sea un _conjunto abierto_.

	![]({{"img/4.png" | prepend: site.baseurl }}){:height="100%" width="100%"}


5. El conjunto vacío $$\emptyset$$ y $$\mathbb{R}^{n}$$ son abiertos y cerrados a la vez.

	Tenemos al conjunto vacío $$\emptyset$$, este conjunto por definición no contiene elementos y por tanto no tiene manera de verificar que es un _conjunto abierto_, por su parte cualquier
	bola abierta está contenidad en el conjunto $$\mathbb{R}^{n}$$, por tanto es un _conjunto abierto_. Más aún, dado que $$\emptyset$$ y $$\mathbb{R}^{n}$$ son complementos el uno del otro y como ambos son abiertos, concluimos que $$\emptyset$$ y $$\mathbb{R}^{n}$$ son
	ambos _conjuntos cerrados_. De este modo estos dos conjuntos $$\emptyset$$ y $$\mathbb{R}^{n}$$ son _abiertos_ y _cerrados_ a la vez.

### Proposición 2

1. Si $$A$$ y $$B$$ son conjuntos abiertos en $$\mathbb{R}^{n}$$, entonces $$A\cup B$$ y $$A\cap B$$ también lo son.
	
	__Prueba__ Hecha en clase.

2. Si $$A$$ y $$B$$ son conjuntos cerrados en $$\mathbb{R}^{n}$$, entonces $$A\cup B$$ y $$A\cap B$$ también lo son.
	
	__Prueba__ _Unión_:

	Consideremos primero las leyes de morgan:
	
	$$\begin{equation}
	(A\cup B)^{c}=A^{c}\cap B^{c}
	\quad\mathrm{y}\quad 
	(A\cap B)^{c}= A^{c}\cup B^{c}
	\end{equation}$$

	Como $$A$$ y $$B$$ son cerrados en claro que, por definición, $$A^{c}$$ y $$B^{c}$$ son abiertos, de este modo tenemos lo siguiente:
		
		
	+ Unión: como $$A$$ y $$B$$ son cerrados, entonces $$A^{c}$$ y $$B^{c}$$ son abiertos, del punto anterior:
	$$A^{c}\cap B^{c}=(A\cup B)^{c}$$ es abierto, en consecuencia $$A\cup B$$ es cerrado.

	__Intersección__

	+ Intersección: análogo al inciso anterior, $$A^{c}$$ y $$B^{c}$$ son abiertos, entonces $$A^{c}\cup B^{c}=(A\cap B)^{c}$$ es abierto,
	en consecuencia $$A\cap B$$ es cerrado.

### Probar que $$A$$ está contenido en $$B$$ sí y solo sí $$B$$ complemento está contenido en $$A$$ complemento.

Si $$A\subset B \iff B^c \subset A^c$$

_Demostración:_

$$\Longrightarrow$$

Supongamos que $$A\subset B$$

Pd. $$B^c \subset A^c$$

sea $$\vec{x}\in B^c$$ Pd. $$\vec{x}\in A^c$$
como $$A\subset B\Longrightarrow$$ $$\forall \vec{w}\in A$$ se tiene que $$\vec{w}\in B$$
como $$\vec{x}\in B^c \Longrightarrow$$ $$\vec{x}\notin B \Longrightarrow$$ $$\vec{x}\notin A \Longrightarrow$$ $$\vec{x}\in A^c$$

$$\therefore$$ $$B^c \subset A^c$$

$$\Leftarrow$$

Supongamos $$B^c \subset A^c$$ 

Pd.$$A \subset B$$
sea $$\vec{x}\in A $$ $$\vec{x}\in B$$
como $$B^c \subset A^c \Longrightarrow$$ $$\forall\vec{w}\in B^c$$ se tiene que $$\vec{w}\in A^c$$
como $$\vec{x}\in A \Longrightarrow$$ $$\vec{x}\notin A^c \Longrightarrow$$ $$\vec{x}\notin B^c \Longrightarrow \vec{x}º \in B$$
$$\therefore$$ $$A \subset B$$
