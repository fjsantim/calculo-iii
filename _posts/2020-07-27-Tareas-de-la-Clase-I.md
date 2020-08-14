---
title: Tareas de la Clase I
---

## Tareas de la clase del 27 de julio de 2020

### Probar que $$ \mathbb{R}^{3} $$ es un espacio vectorial.

De la definición de espacio vectorial dada en clase, tomemos tres vectores 
$$ \vec{x}, \vec{y}, \vec{z} \in \mathbb{R}^{3} $$ tales que cada vector sea de la forma 
$$\vec{u}=(u_{1}, u_{2}, u_{3})$$ con cada entrada $$u_{i} \in \mathbb{R}$$ y escalares 
$$\alpha,\beta \in \mathbb{R}$$; verificamos entonces para los elementos de $$\mathbb{R}^{3}$$:

1. $$\vec{x} + \vec{y} = (x_{1}, x_{2}, x_{3}) + (y_{1}, y_{2}, y_{3}) = 
(x_{1} + y_{1}, x_{2} + y_{2}, x_{3} + y_{3})$$

	Dado que, si $$u_{i}=x_{i}+y_{i}$$ entonces $$(u_{1}, u_{2}, u_{3}) \in \mathbb{R}^{3}$$ y por tanto $$\vec{x} + \vec{y} \in \mathbb{R}^{3}$$

2. Considerando la propiedad conmutativa de los reales ($$a+b=b+a$$)

	$$\begin{split}
	\vec{x} + \vec{y} & = (x_{1}, x_{2}, x_{3}) + (y_{1}, y_{2}, y_{3}) \\
        	          & = (x_{1} + y_{1}, x_{2} + y_{2}, x_{3} + y_{3}) \\
                	  & = (y_{1} + x_{1}, y_{2} + x_{2}, y_{3} + x_{3}) \\
	                  & = (y_{1}, y_{2}, y_{3}) + (x_{1}, x_{2}, x_{3}) \\
        	          & = \vec{y} + \vec{x}
	\end{split}
	$$

3. Considerando ahora la propiedad distributiva de los reales $$(a+b)+c=a+(b+c)$$ verificamos que:

	$$\begin{split}
	(\vec{x} + \vec{y}) + \vec{z} & = \left((x_{1}, x_{2}, x_{3}) + (y_{1}, y_{2}, y_{3})\right) + (z_{1},z_{2}, z_{3}) \\
	                              & = (x_{1} + y_{1}, x_{2} + y_{2}, x_{3} + y_{3}) + (z_{1}, z_{2}, z_{3}) \\
	                              & = (x_{1} + y_{1} + z_{1}, x_{2} + y_{2} + z_{2}, x_{3} + y_{3} + z_{3}) \\
	                              & = (x_{1}, x_{2}, x_{3}) + (y_{1} + z_{1}, y_{2} + z_{2}, y_{3} + z_{3}) \\
	                              & = \vec{x} + (\vec{y} + \vec{z})
	\end{split}$$

4. Sea $$0_{\mathbb{R}^{3}}=\vec{0}=(0, 0, 0)$$, tenemos que 

	$$\vec{x}+\vec{0} = (x_{1}, x_{2}, x_{3}) + (0, 0, 0) = (x_{1}, x_{2}, x_{3}) = \vec{x}$$

5. Consideremos ahora el vector $$-\vec{x}$$ tal que $$-\vec{x}=(-x_{1}, -x_{2}, -x_{3})$$ siendo cada $$-x_{i}$$ el
inverso aditivo de $$x_{i}$$ ambos en $$\mathbb{R}$$. Entonces:

	$$\begin{split}
	\vec{x}+(-\vec{x}) & = (x_{1}, x_{2}, x_{3}) + (-x_{1}, -x_{2}, -x_{3}) \\
	                   & = (x_{1}-x_{1}, x_{3}-x_{2}, x_{3}-x_{3}) \\
	                   & = (0,0,0) = 0_{\mathbb{R}^{3}} 
	\end{split}$$
6. Sea ahora $$\alpha\vec{x} = \alpha(x_{1}, x_{2}, x_{3}) = (\alpha x_{1}, \alpha x_{2}, \alpha x_{3})$$ y el escalar $$\nu_{i}=\alpha x_{i}$$ de $$\mathbb{R}$$ 
como el vector $$\vec{\nu}=(\nu_{1}, \nu_{2}, \nu_{3}) \in \mathbb{R}^{3}$$ concluimos que $$\alpha\vec{x} \in \mathbb{R}^{3}$$.

7. Recordando la distrivutividad de la suma y el producto de los reales $$a(b+c)=ab+ac$$:

	$$\begin{split}
	\alpha\left(\vec{x}+\vec{y}\right) & = \alpha\left((x_{1},x_{2},x_{3})+(y_{1},y_{2},y_{3})\right) \\
	                                   & = \alpha\left((x_{1}+y_{1}),(x_{2}+y_{2}),(x_{3}+y_{3})\right)\\
	                                   & = \left(\alpha(x_{1}+y_{1}),\alpha(x_{2}+y_{2}),\alpha(x_{3}+y_{3})\right) \\
	                                   & = \left(\alpha x_{1}+\alpha y_{1},\alpha x_{2}+\alpha y_{2},\alpha x_{3}+\alpha y_{3}\right) \\
	                                   & = \left(\alpha x_{1},\alpha x_{2},\alpha x_{3}\right)+\left(\alpha y_{1},\alpha y_{2},\alpha y_{3}\right) \\
	                                   & = \alpha\left(x_{1},x_{2},x_{3}\right)+\alpha\left(y_{1},y_{2},y_{3}\right) \\
	                                   & = \alpha\vec{x} + \alpha\vec{y}
	\end{split}$$

8. Análogo a la propiedad anterior:

	$$\begin{split}
	\left(\alpha+\beta\right)\vec{x} & = \left(\alpha+\beta\right)\left(x_{1},x_{2},x_{3}\right) \\
	                                 & = \left((\alpha+\beta)x_{1},(\alpha+\beta)x_{2},(\alpha+\beta)x_{3}\right) \\
	                                 & = \left(\alpha x_{1}+\beta x_{1},\alpha x_{2}+\beta x_{2},\alpha x_{3}+\beta x_{3}\right) \\
	                                 & = \left(\alpha x_{1},\alpha x_{2},\alpha x_{3}\right)+\left(\beta x_{1},\beta x_{2},\beta x_{3}\right) \\
	                                 & = \alpha\left(x_{1},x_{2},x_{3}\right)+\beta\left(x_{1},x_{2},x_{3}\right) \\
	                                 & = \alpha\vec{x}+\beta\vec{x}
	\end{split}$$

9. Por la propiedad asociativa del  producto en los reales $$(ab)c=a(bc)$$, tenemos:

	$$\begin{split}
	\alpha\left(\beta\vec{x}\right) & = \alpha\left(\beta\left(x_{1},x_{2},x_{3}\right)\right) \\
	                                & = \alpha\left(\beta x_{1},\beta x_{2},\beta x_{3}\right) \\
	                                & = \left(\alpha\beta x_{1},\alpha\beta x_{2},\alpha\beta x_{3}\right) \\
	                                & = (\alpha\beta)\left(x_{1},x_{2},x_{3}\right) \\
	                                & = \left(\alpha\beta\right)\vec{x}
	\end{split}$$

10. Finalmente consideremos el escalar $$1 \in \mathbb{R}$$, dado que $$1\vec{x}=1\left(x_{1}, x_{2}, x_{3} \right)=\left(x_{1}, x_{2}, x_{3} \right)$$

	$$\therefore$$ dado que los elementos de $$\mathbb{R}^{3}$$ cumplen con todos los puntos de la definición de espacio vectorial, $$\mathbb{R}^{3}$$ es un espacio vectorial $$\blacksquare$$


### Teorema 2 (Propiedades del producto punto o escalar)

Consideremos los vectores $$\vec{u},\vec{v},\vec{w} \in \mathbb R^{n}$$ y $$\alpha \in \mathbb R$$ entonces:

1. $$\vec{v}\cdot \vec{0} =0$$

	__Prueba__: Sea $$\vec{v}=(v_{1}, v_{2},\dots, v_{n})$$ y sea $$\vec{0}=(0,0,\dots,0)$$, por la definición del producto escalar tenemos que:

	$$\begin{split}
	\vec{v}\cdot\vec{0} & = (v_{1}, v_{2},\dots, v_{n})\cdot(0,0,\dots,0) \\
                            & = v_{1}0 + v_{2}0 + \dots + v_{n}0 \\
                            & = 0 + 0 + \dots + 0 \\
                            & = 0 \blacksquare
	\end{split}$$
2. $$\vec{v}\cdot\vec{w} =\vec{w}\cdot\vec{v}$$
	
	__Prueba__: Sean $$\vec{v}=(v_{1}, v_{2},\dots, v_{n})$$ y $$\vec{w}=(w_{1}, w_{2},\dots, w_{n})$$, recordando la conmutatividad de la multiplicacion de los reales:

	$$\begin{split}
	\vec{v}\cdot\vec{w} & = (v_{1}, v_{2},\dots, v_{n})\cdot(w_{1}, w_{2},\dots, w_{n}) \\
	                    & = v_{1}w_{1} + v_{2}w_{2} + \dots + v_{n}w_{n} \\
	                    & = w_{1}v_{1} + w_{2}v_{2} + \dots + w_{n}v_{n} \\
	                    & = (w_{1}, w_{2},\dots, w_{n})\cdot(v_{1}, v_{2},\dots, v_{n}) \\
	                    & = \vec{w}\cdot\vec{v} \blacksquare
	\end{split}$$ 

3. $$\vec{u}\cdot(\vec{v}+\vec{w})=\vec{u}\cdot\vec{v}+\vec{u}\cdot\vec{w}$$

	__Prueba__: consideremos los vectores $$\vec{u}=(u_{1}, u_{2}, \dots, u_{n})$$, $$\vec{v}=(v_{1}, v_{2},\dots, v_{n})$$ y $$\vec{w}=(w_{1}, w_{2},\dots, w_{n})$$
	y la asociatividad del producto en los reales.
	
	$$\begin{split}
	\vec{u}\cdot(\vec{v}+\vec{w}) & = (u_{1}, u_{2}, \dots, u_{n})\cdot\left((v_{1}, v_{2},\dots, v_{n}) + (w_{1}, w_{2},\dots, w_{n})\right) \\
	                              & = (u_{1}, u_{2}, \dots, u_{n})\cdot(v_{1}+w_{1}, v_{2}+w_{2},\dots, v_{n}+w_{n}) \\
	                              & = u_{1}(v_{1}+w_{1}) + u_{2}(v_{2}+w_{2}) + \dots + u_{n}(v_{n}+w_{n}) \\
	                              & = u_{1}v_{1} +u_{1}w_{1} + u_{2}v_{2} +u_{2}w_{2} + \dots + u_{n}v_{n} +u_{n}w_{n} \\
	                              & = (u_{1}v_{1} + u_{2}v_{2} + \dots + u_{n}v_{n}) + (u_{1}w_{1} + u_{2}w_{2} + \dots + u_{n}w_{n}) \\
	                              & = (u_{1}, u_{2}, \dots, u_{n})\cdot(v_{1}, v_{2},\dots, v_{n}) + (u_{1}, u_{2}, \dots, u_{n})\cdot(w_{1}, w_{2},\dots, w_{n}) \\
	                              & = \vec{u}\cdot\vec{v} + \vec{u}\cdot\vec{w} \blacksquare
	\end{split}$$


4. $$(\alpha\vec{v})\vec{w}=\alpha(\vec{v}\cdot\vec{w})$$

	__Prueba__: como en la propiedad anterior

	$$\begin{split}
	(\alpha\vec{v})\cdot\vec{w} & = \left(\alpha(v_{1},v_{2},\dots,v_{n})\right)\cdot(w_{1},w_{2},\dots,w_{n}) \\
	                      & = (\alpha v_{1},\alpha v_{2},\dots,\alpha v_{n})\cdot(w_{1},w_{2},\dots,w_{n}) \\
	                      & = \alpha v_{1}w_{1} + \alpha v_{2}w_{2} + \dots + \alpha v_{n}w_{n} \\
	                      & = \alpha(v_{1}w_{1} + v_{2}w_{2} + \dots + v_{n}w_{n}) \\
	                      & = \alpha(\vec{v}\cdot\vec{w}) \blacksquare
	\end{split}$$

### Teorema 3



### Teorema 4

Los vectores $$\vec{v},\vec{w}\in\mathbb R^n$$ son ortogonales si y sólo si $$\vec{v}\cdot\vec{w}=0$$

__Prueba__:
Recordado que dos vectores son ortogonales si el producto escalar entre ellos es $$0$$, 
$$\vec{v}\cdot\vec{w}=0$$; y que el producto escalar de dos vectores puede definirse 
como $$\vec{v}\cdot\vec{w}=\|\vec{v}\|\|\vec{w}\|\cos{\theta}$$.

Del Teorema 3, el vector $$\vec{0}$$ tiene norma $$\|\vec{0}\|=0$$ si y solo si 
$$\vec{v}=\vec{0}$$, tenemos que $$\vec{v}\cdot\vec{0}=\vec{0}\cdot\vec{v}=0$$ 
entonces vale pedir que los dos vectores $$\vec{v},\vec{w}$$ sean diferentes del vector $$\vec{0}$$.

Siendo entonces que si $$\vec{v}$$ y $$\vec{w}$$ son ortogonales, el angulo entre ellos es de $$\theta=90^o$$ 
entonces $$\vec{v}\cdot\vec{w}=\|\vec{v}\|\|\vec{w}\|\cos{90^o}=\|\vec{v}\|\|\vec{w}\|0=0$$. 
Ahora supongamos que $$\vec{v}\cdot \vec{w}=0$$ entonces tenemos que $$\vec{v}\cdot\vec{w}=\|\vec{v}\|\|\vec{w}\|\cos{\theta} = 0$$ 
teniendo entonces que $$\|\vec{v}\|=0$$ o $$\|\vec{w}\|=0$$ o $$\cos{\theta}=0$$, quitando entonces el caso trivial de que uno o ambos vectores 
sean el vector $$\vec{0}$$, solo queda la opción $$\cos{\theta}=0$$ de modo que $$\theta=90^{o}$$ y entonces $$\vec{v}$$ y $$\vec{w}$$ son ortogonales. $$\blacksquare$$

### Propiedades del producto vectorial
Sean $$\vec{u},\vec{v}\in \mathbb{R}^3$$ y $$\alpha\in\mathbb{R}$$ para el producto vectorial se cumplen las siguientes propiedades:

1. $$\vec{u}\cdot(\vec{u}\times\vec{v}) = 0$$

	__Demostración:__

	$$\begin{align}
	\vec{u}\cdot (\vec{u}\times\vec{v}) &= (u_1,u_2,u_3)\cdot((u_1,u_2,u_3)\times(v_1,v_2,v_3))\\
	                                    &= (u_1,u_2,u_3)\cdot(u_2 v_3 - u_3 v_2, u_3 v_1 - u_1 v_3, u_1 v_2 - u_2 v_1)\\
	                                    &= u_1 (u_2 v_3 - u_3 v_2) + u_2 (u_3 v_1 - u_1 v_3) + u_3(u_1 v_2 - u_2 v_1)\\
	                                    &= u_1 u_2 v_3 - u_1 u_3 v_2 + u_2 u_3 v_1 - u_2 u_1 v_3 + u_3 u_1 v_2 - u_3 u_2 v_1 \\                                                     &= u_1 u_2 v_3 - u_1 u_3 v_2 + u_2 u_3 v_1 - u_1 u_2 v_3 + u_1 u_3 v_2 - u_2 u_3 v_1\\
	                                    &= 0 + 0 + 0 \\
	                                    &= 0.\\ 
	\end{align}$$

2. $$\vec{v}\cdot(\vec{u}\times\vec{v}) = 0$$ 

	__Demostración:__

	$$\begin{align}
	\vec{v}\cdot (\vec{u}\times\vec{v}) &= (v_1,v_2,v_3)\cdot((u_1,u_2,u_3)\times(v_1,v_2,v_3))\\
	                                    &= (v_1,v_2,v_3)\cdot(u_2 v_3 - u_3 v_2, u_3 v_1 - u_1 v_3, u_1 v_2 - u_2 v_1)\\
	                                    &= v_1 (u_2 v_3 - u_3 v_2) + v_2 (u_3 v_1 - u_1 v_3) + v_3(u_1 v_2 - u_2 v_1)\\
	                                    &= v_1 u_2 v_3 - v_1 u_3 v_2 + v_2 u_3 v_1 - v_2 u_1 v_3 + v_3 u_1 v_2 - v_3 u_2 v_1 \\                                                  &= v_1 u_2 v_3 - v_1 u_3 v_2 + v_2 u_3 v_1 - u_1 v_2 v_3 + u_1 v_3 v_2 - u_2 v_3 v_1\\
	                                    &= 0 + 0 + 0 \\
	                                    &= 0.\\
	\end{align}$$

3. $$\|\vec{u}\times\vec{v}\|^2 = \|\vec{u}\|^2 \|\vec{v}\|^2 - (\vec{u}\cdot\vec{v})^2$$ (igualdad de Lagrange)

	__Demostración:__

	$$\begin{align}
	\parallel\vec{u}\times\vec{v}\parallel^2 &= \parallel(u_1,u_2,u_3)\times(v_1,v_2,v_3)\parallel ^2 \\
	                                         &= \parallel(u_2 v_3 - u_3 v_2, u_3 v_1 - u_1 v_3, u_1 v_2 - u_2 v_1)\parallel^2 \\
	                                         &= [\sqrt{(u_2 v_3 - u_3 v_2)^2 + (u_3 v_1 - u_1 v_3)^2 + (u_1 v_2 - u_2 v_1)^2})]^2 \\
	                                         &= (u_2 v_3 - u_3 v_2)^2 + (u_3 v_1 - u_1 v_3)^2 + (u_1 v_2 - u_2 v_1)^2 \\
	                                         &= (u_2 v_3)^2 -2(u_2 v_3 u_3 v_2)+(u_3 v_2)^2 +(u_3 v_1)^2 -2(u_3 v_1 u_1 v_3)+(u_1 v_3)^2 + (u_1 v_2)^2 \\& -2(u_1 v_2 u_2 v_1)+(u_2 v_1)^2\\
	\end{align}$$

	Por otro lado

	$$\begin{align}
	\|\vec{u}\|^2 \|\vec{v}\|^2 - (\vec{u}\cdot\vec{v})^2 &= \left(\sqrt{u_1^2 + u_2^2 + u_3^2} \right)^2 \left(\sqrt{v_1^2 + v_2^2 + v_3^2}\right)^2 - (u_1,u_2,u_3)\cdot(v_1,v_2,v_3)\\
	                                                      &= (u_1^2 + u_2^2 + u_3^2)(v_1^2 + v_2^2 + v_3^2) - (u_1 v_1 + u_2 v_2 + u_3 v_3)^2\\
	                                                      &= u_1^2 v_1^2 + u_1^2 v_2^2 + u_1^2 v_3^2 + u_2^2 v_1^2 + u_2^2 v_2^2 + u_2^2 v_3^2 + u_3^2 v_1^2 + u_3^2 v_2^2 + u_3^2 v_3^2 \\& - (u_1^2 v_1^2 + u_1 v_1 u_2 v_2 + u_1 v_1 u_3 v_3 + u_2 v_2 u_1 v_1 + u_2^2 v_2^2 + u_2 v_2 u_3 v_3 + u_3 v_3 u_1 v_1 \\& + u_3 v_3 u_2 v_2 + u_3^2 v_3^2) \\
	                                                      &= u_1^2 v_1^2 + u_1^2 v_2^2 + u_1^2 v_3^2 + u_2^2 v_1^2 + u_2^2 v_2^2 + u_2^2 v_3^2 + u_3^2 v_1^2 + u_3^2 v_2^2 + u_3^2 v_3^2 - u_1^2 v_1^2 \\& - u_1 v_1 u_2 v_2 - u_1 v_1 u_3 v_3 - u_2 v_2 u_1 v_1 - u_2^2 v_2^2 - u_2 v_2 u_3 v_3 - u_3 v_3 u_1 v_1 - u_3 v_3 u_2 v_2 \\& - u_3^2 v_3^2 \\
	                                                      &= (u_1 v_2)^2 + (u_1 v_3)^2 + (u_2 v_1)^2 + (u_2 v_3)^2 + (u_3 v_1)^2 + (u_3 v_2)^2 - u_1 v_1 u_2 v_2 \\& - u_1 v_1 u_3 v_3 - u_2 v_2 u_1 v_1 - u_2 v_2 u_3 v_3 - u_3 v_3 u_1 v_1 - u_3 v_3 u_2 v_2 \\
	                                                      &= (u_1 v_2)^2 + (u_1 v_3)^2 + (u_2 v_1)^2 + (u_2 v_3)^2 + (u_3 v_1)^2 + (u_3 v_2)^2 - 2(u_1 v_1 u_2 v_2) \\& - 2(u_1 v_1 u_3 v_3) - 2(u_3 v_3 u_2 v_2) \\
	                                                      &= (u_2 v_3)^2 - 2(u_2 v_3 u_3 v_2) + (u_3 v_2)^2 + (u_3 v_1)^2 - 2(u_3 v_1 u_1 v_3) + (u_1 v_3)^2 + (u_1 v_2)^2 \\& - 2(u_1 v_2 u_2 v_1)+(u_2 v_1)^2.\\
	\end{align}$$
                                          
	Por lo tanto $$\|\vec{u}\times\vec{v}\|^2 = \|\vec{u}\|^2 \|\vec{v}\|^2 - (\vec{u}\cdot\vec{v})^2\blacksquare$$

4. $$\vec{u}\times\vec{v} = -(\vec{v}\times\vec{u})$$
	
	__Demostración:__ hecha en clase.

5. $$\vec{u}\times(\vec{v}+\vec{w})=\vec{u}\times\vec{v}+\vec{u}\times\vec{w}$$

	__Demostración:__ hecha en clase.

6. $$(\vec{u}+\vec{v})\times\vec{w}=\vec{u}\times\vec{w}+\vec{v}\times\vec{w}$$

	__Demostración:__ hecha en clase.

7. $$\alpha(\vec{u}\times\vec{v}) = (\alpha\vec{u})\times\vec{v} = \vec{u}\times(\alpha\vec{v})$$

	__Demostración:__

	$$\begin{align}
	\alpha(\vec{u}\times\vec{v})    &= \alpha((u_1,u_2,u_3)\times(v_1,v_2,v_3))\\
                                &= \alpha(u_2 v_3 - u_3 v_2, u_3 v_1 - u_1 v_3, u_1 v_2 - u_2 v_1)\\
                                &= (\alpha (u_2 v_3 - u_3 v_2), \alpha (u_3 v_1 - u_1 v_3), \alpha (u_1 v_2 - u_2 v_1))\\
                                &= (\alpha u_2 v_3 - \alpha u_3 v_2, \alpha u_3 v_1 - \alpha u_1 v_3, \alpha u_1 v_2 - \alpha u_2 v_1)\\
                                &= ((\alpha u_2)v_3 - (\alpha u_3)v_2,(\alpha u_3)v_1 - (\alpha u_1)v_3,(\alpha u_1)v_2 - (\alpha u_2)v_1)\\
                                &= (\alpha u_1,\alpha u_2, \alpha u_3)\times(v_1,v_2,v_3)\\
                                &= (\alpha(u_1,u_2,u_3))\times(v_1,v_2,v_3)\\
                                &= (\alpha\vec{u})\times\vec{v}\\
	\end{align}$$

	Por otro lado

	$$\begin{align}
	(\alpha\vec{u})\times\vec{v} &= (\alpha(u_1,u_2,u_3))\times(v_1,v_2,v_3)\\
                             &= (\alpha u_1,\alpha u_2,\alpha u_3)\times(v_1,v_2,v_3)\\
                             &= ((\alpha u_2)v_3 - (\alpha u_3)v_2,(\alpha u_3)v_1 - (\alpha u_1)v_3,(\alpha u_1)v_2 - (\alpha u_2)v_1)\\
                             &= (\alpha u_2 v_3 - \alpha u_3 v_2, \alpha u_3 v_1 - \alpha u_1 v_3, \alpha u_1 v_2 - \alpha u_2 v_1)\\
                             &= (u_2 \alpha v_3 - u_3 \alpha v_2, u_3 \alpha v_1 - u_1 \alpha v_3, u_1 \alpha v_2 - u_2 \alpha v_1)\\
                             &= (u_2(\alpha v_3) - u_3(\alpha v_2), u_3(\alpha v_1) - u_1(\alpha v_3),u_1(\alpha v_2)-u_2(\alpha v_1))\\
                             &= (u_1,u_2,u_3)\times(\alpha v_1,\alpha v_2,\alpha v_3)\\
                             &= (u_1,u_2,u_3)\times(\alpha(v_1,v_2,v_3))\\
                             &= \vec{u}\times(\alpha\vec{v}).\\
	\end{align}$$

	Por lo tanto se cumple que $$\alpha(\vec{u}\times\vec{v}) = (\alpha\vec{u})\times\vec{v} = \vec{u}\times(\alpha\vec{v})\blacksquare$$

8. $$\vec{u}\times\vec{0}=\vec{0}\times\vec{u}=\vec{0}$$

	__Demostración:__ hecha en clase.

9. $$\vec{u}\times\vec{u} = \vec{0}.\\$$
	__Demostración:__

	$$\begin{align}
	\vec{u}\times\vec{u} &= (u_1,u_2,u_3)\times(u_1,u_2,u_3)\\
                             &= (u_2 u_3 - u_2 u_3, u_1 u_3 - u_1 u_3, u_1 u_2 - u_1 u_2)\\
                             &= (0,0,0)\\
                             &= \vec{0}\blacksquare\\
\end{align}$$

