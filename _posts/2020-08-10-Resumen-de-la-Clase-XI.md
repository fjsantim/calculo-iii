---
title: Resumen de la Clase XI
---

## Apuntes de la clase del 10 de agosto de 2020

La clase fue acerca de límites y continuidad.

### Límites

> __Definición 1:__ sea $$f: \mathbb{R}^2 \to\mathbb{R}$$ una función definida en un conjunto abierto $$U\subset\mathbb{R}^2$$ excepto quizá en el punto $$(x_0, y_0) \in U$$. Entonces
>
> $$\displaystyle{\lim_{(x,y)\to (x_{0},y_{0})} f(x,y)=l}$$
>
> si y solo si para todo $$\varepsilon > 0$$, existe $$\delta >0$$ tal que, si $$0< \|(x,y)-(x_0 , y_0)\|< \delta$$, entonces $$\midf(x,y)-l\mid <\varepsilon$$.

> __Definición 2:__ Sea $$f: D\subset\mathbb{R}^2 \to \mathbb{R}$$ y $$(x_0 , y_0)$$ un punto de acumulación de $$D$$. Decimos que 
>
> $$\displaystyle{\lim_{(x,y)\to (x_{0},y_{0})} f(x,y)=l}$$
>
> si y sólo si para todo $$\varepsilon > 0$$, existe $$\delta > 0$$ tal que, si $$(x, y) \in D$$ y $$0 < \|(x, y) − (x_0 , y_0)\| < \delta$$, entonces $$\mid f(x,y) − l\mid < \varepsilon$$.

__Observación 1__ $$0 < \|(x, y) − (x_0 , y_0)\| < \delta$$ es equivalente a $$\displaystyle{0 < \sqrt{(x - x_0)^2 + (y - y_0)^2}<\delta}$$, siendo esta última parte una bola abierta sin el punto $$(x_0 , y_0$$, dicho punto es un punto de acumulación como lo solicita la __definición 2__. 

En la clase se vieron los siguientes ejemplos:

__Ejemplo 1:__ probar por la definición que $$\displaystyle{\lim_{(x,y)\to (2,3)} x=2}$$

__Ejemplo 2:__ probar por la definición que $$\displaystyle{\lim_{(x,y)\to (2,3)} y=3}$$

__Ejemplo 3:__ probar por la definición que $$\displaystyle{\lim_{(x,y)\to (0,0)} \frac{x^2 y}{x^2 + y^2}=0}$$

__Ejemplo 3:__ probar por la definición que $$\displaystyle{\lim_{(x,y)\to (0,0)} \frac{x^3}{x^2 + y^2}=0}$$

En este ejmplo analizando las trayectorias $$x=0, y=0$$ y $$y=x$$ se llegó a que el límite debe valer $$0$$, se procede con la demostración:

Queremos probar que para toda $$\varepsilon > 0$$, existe $$\delta > 0$$ tal que, si $$0 < \|(x, y) − (0,0)\| < \delta$$, entonces $$\displaystyle{\left| \frac{x^3}{x^2 + y^2} - 0 \right| < \varepsilon}$$
Es decir, si $$\displaystyle{0 < \sqrt{(x-0)^2 +(y-0)^2} < \delta}$$, entonces 
$$\displaystyle{\left| \frac{x^3}{x^2 + y^2} - 0 \right| < \varepsilon}$$. Notemos que, $$\displaystyle{\sqrt{(x-0)^2 +(y-0)^2} = \sqrt{x^2 +y^2}}$$ y que como $$0 <x^2 \leq x^2 + y^2$$ entonces $$\frac{1}{x^2 +y^2} \leq \frac{1}{x^2}$$. De manera que, bastaría hacer:

$$\displaystyle{\left| \frac{x^3}{x^2 + y^2} - 0 \right|=\left| \frac{x^3}{x^2 + y^2} \right|\leq\left|\frac{x^3}{x^2} \right|=\left|x\right|<\varepsilon}$$

Y como $$\displaystyle{\left| x \right| \leq \sqrt{x^2 + y^2}}$$, 
elegimos $$\delta=\varepsilon$$ y aseguramos que $$\displaystyle{\sqrt{x^2 + y^2} < \varepsilon}$$ y por transitividad
$$\displaystyle{\left| \frac{x^3}{x^2 + y^2} - 0 \right|<\varepsilon}\blacksquare$$

Finalmente en clase hicimos estos ejercicios:

__1.__ Demuestra si existe o no el límite en el punto indicado.
	
a) $$\displaystyle{\lim_{(x,y)\to (0,0)} \frac{x^2}{\sqrt{x^2 + y^2}}}$$

b) $$\displaystyle{\lim_{(x,y)\to (0,0)} \frac{y^2}{\sqrt{x^2 + y^2}}}$$

__2.__ Demuestra mediante la definición $$(\varepsilon − \delta)$$ que las siguientes funciones son continuas en $$(0,0)$$.

a) $$\begin{equation}
     f(x,y)= \left\{
               \begin{array}{ll}
                 \frac{x^2 - y^2}{\sqrt{x^2 + y^2}}, \hspace{0.5cm}(x,y)\ne(0,0) \\
                 \hspace{0.6cm} 0\hspace{0.6cm}, \hspace{0.5cm}(x,y)=(0,0)
               \end{array}
             \right.
   \end{equation}$$

b)         $$\begin{equation}
     f(x,y)= \left\{
               \begin{array}{ll}
                 \frac{x^4 - y^4}{x^2 + y^2}, \hspace{0.5cm}(x,y)\ne(0,0) \\
                 \hspace{0.45cm} 0\hspace{0.45cm}, \hspace{0.5cm}(x,y)=(0,0)
               \end{array}
             \right.
   \end{equation}$$

