---
title: Resumen de la Clase XXIX
---

## Apuntes de la clase del 27 de agosto de 2020

En esta clase se verá la diferencia entre las derivadas parciales y las derivadas direccionales. Recordemos la definición de derivada direccional.

> Definición: Sea $$f:\mathbb{R}^n \rightarrow \mathbb{R}$$ (funciones escales), sea $$\vec{u}\in\mathbb{R}^n$$ , $$\vec{u}$$ un vector de dirección se define la derivada direccional como:
>
> $$D_{\vec{u}}f(\vec{x_0})=\lim\limits_{h \to 0}\frac{f(\vec{x_0}+h\vec{u})-f(\vec{x_0})}{h}$$, donde $$\parallel\vec{u}\parallel =1$$
>
> __Nota:__ Las derivadas parciales son un caso particular de las derivadas direccionales, porque aquí $$\vec{u}=e_i$$. Entonces $$D_{\vec{u}}f(\vec{x_0})=\lim\limits_{h \to 0}\frac{\vec{x_0}+h\vec{u}-f(\vec{x_0})}{h}.$$ y $$\frac{\partial f}{\partial x_i}=\lim\limits \frac{f(\vec{x_0}+he_i)-f(\vec{x_0})}{h}$$

__Ejemplo:__ Consideremos la función $$f(x,y)=xe^y$$ obtener el gradiente.

Primero obtengamos las parciales:

$$\frac{\partial f}{\partial x}=e^y$$

$$\frac{\partial f}{\partial y}=xe^y$$

$$\therefore \triangledown f=(e^y,xe^y)$$

Ahora si queremos evaluar el gradiente en un punto del dominio, digamos $$x_0=(0,0)$$ queda de la siguiente manera:

$$\triangledown f_{(0,0)}=(e^0,0e^0)=(1,0)$$  

Ahora notemos que es un vector unitario, recordemos que el gradiente nos muestra la dirección en la que crece más la función. Ahora si queremos calcular la derivada direccional en este punto nos queda como:

$$\begin{align}
D_{(1,0)}f &= \lim\limits_{h \to 0}\frac{f(\vec{x}+h\vec{u})-f(\vec{x})}{h}\\
                  &= \lim\limits_{h \to 0}\frac{f((x,y)+h(1,0))-f((x,y))}{h}\\
                  &= \lim\limits_{h \to 0}\frac{f(x+h,y+0)-f(x,y)}{h}\\
                  &= \lim\limits_{h \to 0}\frac{f(x+h,y)-f(x,y)}{h}\\
                  &=\lim\limits_{h \to 0}\frac{(x+h)e^y-xe^y}{h}\\
                  &=e^y \lim\limits_{h \to 0}\frac{x+h-x}{h}\\
                  &=e^y \lim\limits_{h \to 0} \frac{h}{h}\\
                  &=e^y \lim\limits_{h \to 0} 1 \\
                  &=e^y 1\\
                  &=e^y\\
                  &=\frac{\partial f}{\partial y}    
\end{align}$$

$$\therefore D_{(1,0)}f = \frac{\partial f}{\partial y}$$

Ahora si queremos calcular la derivada direccional de la función en la dirección del vector $$(3,1)$$.

Primero calculemos la norma de este vector $$\parallel (3,1)\parallel=\sqrt{3^2 + 1^2}=\sqrt{9+1}=\sqrt{10}$$. Notemos que no tiene norma uno por lo que lo haremos unitario y por lo tanto $$\vec{v}=\frac{(3,1)}{\parallel (3,1)\parallel}=(\frac{3}{\sqrt{10}},\frac{1}{\sqrt{10}}).$$

$$\begin{align}
D_{\vec{v}}f &= \lim\limits_{h \to 0} \frac{f(\vec{x}+h\vec{v})-f(\vec{x})}{h}\\
                     &= \lim\limits_{h \to 0} \frac{f((x,y)+h(\frac{3}{\sqrt{10}},\frac{1}{\sqrt{10}}))-f(x,y)}{h}\\
                     &= \lim\limits_{h \to 0} \frac{f(x+\frac{3h}{\sqrt{10}},y+\frac{h}{\sqrt{10}})-f(x,y)}{h}\\
                     &= \lim\limits_{h \to 0} \frac{(x+\frac{3h}{\sqrt{10}})e^{y+\frac{h}{\sqrt{10}}}-xe^y}{h}\\
                     &= \lim\limits_{h \to 0} \frac{(x+\frac{3h}{\sqrt{10}})e^{y}e^{\frac{h}{\sqrt{10}}}-xe^y}{h}\\
                     &=e^y\lim\limits_{h \to 0} \frac{(x+\frac{3h}{\sqrt{10}})e^{\frac{h}{\sqrt{10}}}-x}{h}\\
                     &=e^y\lim\limits_{h \to 0}\frac{xe^{\frac{h}{\sqrt{10}}}+\frac{3h}{\sqrt{10}}e^{\frac{h}{\sqrt{10}}}-x}{h}\\
                     &=e^y\lim\limits_{h \to 0} \frac{x(e^{\frac{h}{\sqrt{10}}}-1)+\frac{3h}{\sqrt{10}}e^{\frac{h}{\sqrt{10}}}}{h} \hspace{1cm}\text{aplicando L'Hopital} \\
                     &= e^y(\frac{x}{\sqrt{10}},3)                 
\end{align}$$

$$\therefore D_{\vec{v}}f=e^y(\frac{x}{\sqrt{10}},3)$$

veamos como se ve la gráfica de la función $$f(x,y)=xe^y$$:\\

![]({{"img/c-28/1.jpeg" | prepend: site.baseurl }}){:height="100%" width="100%"}

El recurso puede visitarse en [https://www.geogebra.org/3d/a2vvak6r](https://www.geogebra.org/3d/a2vvak6r).
