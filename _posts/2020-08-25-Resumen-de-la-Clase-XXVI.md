---
title: Resumen de la Clase XXVI
---

## Apuntes de la clase del 25 de agosto de 2020

En esta clase se vera  brevemente las derivadas parciales y las derivadas direccionales.

__Ejemplo:__ obtener por definición las derivadas parciales de la función $$f(x,y)=x^3y$$ también se deberá indicar cual es el gradiente de la función.

$$\begin{split}
\frac{\partial f}{\partial x} & = \lim\limits_{h \to 0} \frac{f(x+h,y)-f(x,y)}{h} \\
                                          & = \lim\limits_{h \to 0} \frac{(x+h)^3y-x^3y}{h} \\
                                          & = y \lim\limits_{h \to 0}\frac{(x+h)^3-x^3}{h} \\
                                          & = 3yx^2\\
\end{split}$$

$$\begin{split}
\frac{\partial f}{\partial y} & = \lim\limits_{h \to 0} \frac{f(x+h,y)-f(x,y)}{h} \\
                                          & = \lim\limits_{h \to 0} \frac{(x^3(y+h)-x^3y}{h} \\
                                          & = x^3\lim\limits_{h \to 0}\frac{y+h-y}{h}\\
                                          & = x^3
\end{split}$$

$$\therefore \triangledown f=(3yx^2,x^3)$$

Hay otra forma un poco más fácil de obtener las derivadas parciales de una función, esta forma consiste tomar como constantes aquellas variables respecto a las que no se va a derivar, de esta forma es como si deriváramos una función de variable real. Veamos algunos ejemplos.

__Ejemplo__: Calcula la derivada parcial y el gradiente de la función $$f(x,y)=xe^y$$

$$\begin{split}
\frac{\partial f}{\partial x} & = e^y             
\end{split}$$

$$\begin{split}
\frac{\partial f}{\partial y} & = xe^y \\
\end{split}$$

$$\therefore \triangledown f = (e^y,xe^y)$$

__Ejemplo:__ Calcula la derivada parcial y el gradiente de la función $$f(x,y)=xseny$$

$$\begin{split}
\frac{\partial f}{\partial x} & = seny           
\end{split}$$

$$\begin{split}
\frac{\partial f}{\partial y} & = xcosy         
\end{split}$$

$$\therefore \triangledown f= (seny,xcosy)$$

__Nota:__ es importante aclarar que la existencia de las derivadas parciales no garantiza la existencia de la derivada en general, esto es porque las derivadas parciales solo analizan el comportamiento de la función por las trayectorias de los ejes coordenados.

Bueno ahora si queremos ver como se comporta la función por diferentes trayectorias se introducirá el concepto de derivada direccional.

> __Definición:__ sea $$\vec{v}\in\mathbb{R}^n$$, donde $$\parallel\vec{v}=1$$ definimos la derivada direccional de la función f en el punto $$\vec{x_0}$$ en la dirección de $$\vec{v}$$ se define como: 
>
> $$D_{\vec{v}}(\vec{x_0})=\lim\limits_{t \to 0}\frac{ f(\vec{x_0}+t\vec{v})-f(\vec{x_0})}{t}$$
