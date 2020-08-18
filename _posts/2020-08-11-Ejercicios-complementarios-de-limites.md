---
title: Ejercicios complementarios de límites
---

### Ejercicios 5-7.

Calcule el límite indicado.

> __5.__ $$\displaystyle{\lim_{(x,y)\to (0,0)} \frac{x^{2}y}{4x^2 -y}}$$

Verifiquemos las trayectorias $$x=0$$, $$y=0$$ y $$y=x$$:

+ Para $$x=0$$:

	$$\begin{split}
\lim_{(0,y)\to (0,0)} \frac{(0)^{2}y}{4(0)^2 -y} &= \lim_{(0,y)\to (0,0)} \frac{0}{-y} \\
&= \lim_{y \to 0} 0 \\
&= 0 \\
\end{split}
$$

+ Para $$y=0$$

	$$\begin{split}
\lim_{(x,0)\to (0,0)} \frac{x^{2} (0)}{4x^2 - 0} &= \lim_{(x,0)\to (0,0)} \frac{0}{4x^2} \\
&= \lim_{x \to 0} 0 \\
&= 0
\end{split}$$

+ Y para $$y=x$$

	$$\begin{split}
\lim_{(x,x)\to (0,0)} \frac{(x^2 )(x)}{4x^2 - x} &= \lim_{(x,x) \to (0,0)} \frac{x^3}{x(4x -1)} \\
&= \lim_{x \to  0} \frac{x^2}{4x -1}  \\
&= \frac{(0)^2}{4(0)-1} \\
&= 0
\end{split}$$

Concluyendo que $$\displaystyle{\lim_{(x,y)\to (0,0)} \frac{x^{2}y}{4x^2 -y} = 0}$$.


> __7.__ $$\displaystyle{\lim_{(x,y) \to (0,0)} \frac{\cos{xy}}{y^2 +1} }$$

Tomemos nuevamente las trayectorias $$x=0$$, $$y=0$$ y $$y=x$$

+ Para $$x=0$$:

	$$\begin{split}
\lim_{(0,y)\to (0,0)} \frac{\cos{[(0)(y)]}}{y^2 +1} &= \lim_{(0,y)\to (0,0)} \frac{1}{y^2 + 1} \\
&= \lim_{y \to 0} \frac{1}{y^2 +1} \\
&= \frac{1}{(0)^2 +1} \\
&= 1 \\
\end{split}$$

+ Para $$y=0$$:
	
	$$\begin{split}
\lim_{(x,0)\to (0,0)} \frac{\cos{[(x)(0)]}}{(0)^2 +1} &= \lim_{(x,0)\to (0,0)} \frac{1}{1} \\
&= \lim_{x \to (0)} 1 \\
&= 1
\end{split}$$

+ Para $$y=x$$:

	$$\begin{split}
\lim_{(x,x) \to (0,0)} \frac{\cos{[(x)(x)]}}{(x)^2 +1} &= \lim_{(x,x) \to (0,0)} \frac{\cos{x^2}}{x^2 +1} \\
&= \lim_{x \to 0} \frac{\cos{x^2}}{x^2 +1} \\
&= \frac{\cos{(0)}}{(0)^2 +1} \\
&= \frac{1}{1} \\
&= 1
\end{split}$$

Concluyendo que si el límite $$\displaystyle{\lim_{(x,y) \to (0,0)} \frac{\cos{xy}}{y^2 +1}}$$ existe debe ser $$1$$.

### Ejercicios 9-23. 

Demuestre que el límite indicado no existe.

> __9.__ $$\displaystyle{\lim_{(x,y) \to (0,0)} \frac{3x^2}{x^2 +y^2}}$$

Consideremos la trayectoria $$x=0$$:

$$\begin{split}
\lim_{(0,y) \to (0,0)} \frac{3(0)^2}{(0)^2 +y^2} &= \lim_{(0,y) \to (0,0)} \frac{0}{y^2} \\
&= \lim_{y \to 0} \frac{0}{y^2} \\
&= 0
\end{split}$$

Y ahora la trayectoria $$y=x$$:

$$\begin{split}
\lim_{(x,x) \to (0,0)} \frac{3x^2}{x^2 +(x)^2} &= \lim_{(x,y) \to (0,0)} \frac{3x^2}{2x^2} \\
&= \lim_{(x,x) \to (0,0)} \frac{3}{2} \\
&= \lim_{x \to 0} \frac{3}{2} \\
&= \frac{3}{2}
\end{split}$$

Y dado que si un límite existe éste debe ser único, concluimos que $$\displaystyle{\lim_{(x,y) \to (0,0)} \frac{3x^2}{x^2 +y^2}}$$ no existe.

> __11.__ $$\displaystyle{\lim_{(x,y) \to (0,0)} \frac{4xy}{3y^2 -x^2}}$$

Dada la trayectoria $$x=0$$:

$$\begin{split}
\lim_{(0,y) \to (0,0)} \frac{4(0)y}{3y^2 -(0)^2} &= \lim_{(x,y) \to (0,0)} \frac{0}{3y^2} \\
&= \lim_{y \to 0} \frac{0}{3y^2} \\
&= 0
\end{split}$$

Y la trayectoria $$y=x$$:

$$\begin{split}
\lim_{(x,x) \to (0,0)} \frac{4x(x)}{3(x)^2 -x^2} &= \lim_{(x,y) \to (0,0)} \frac{4x^2}{2x^2} \\
&= \lim_{x \to 0} 2 \\
&= 2
\end{split}$$

Nuevamente, los límites no coinciden para dos trayectorias distintas así que el límite no existe.

> __13.__ $$\displaystyle{\lim_{(x,y) \to (0,0)} \frac{2x^2 y}{x^4 +y^2}}$$

Llegados a este punto nos damos cuenta que si una función es de la forma $$\displaystyle{\frac{ax^n y^m}{g(x,y)}}$$ con $$a$$ alguna constante y $$g(x,y)$$ alguna función arbitraria $$g:D \subset \mathbb{R}^2 \to \mathbb{R}$$, al 
menos para las trayectorias $$x=0$$ y $$y=0$$ el límite parece valer $$0$$. 
Por lo que simplemente prosegimos con otra trayectoria, por ejemplo $$y=x^2 $$ y verificamos:

$$\begin{split}
\lim_{(x,x^2) \to (0,0)} \frac{2x^2 (x^2)}{x^4 +(x^2)^2} &= \lim_{(x,y) \to (0,0)} \frac{2x^4}{2x^4} \\
&= \lim_{(x,x^2) \to (0,0)} 1 \\
&= \lim_{x \to 0} 1 \\
&= 1
\end{split}$$

Lo que nos hace llegar a que si las trayectorias son $$x=0$$ o $$y=0$$ el límite vale $$0$$ y si la trayectoria es $$y=x^2$$ el límite vale $$1$$, de este modo por la unicidad del límite concluimos que este límite 
$$\displaystyle{\lim_{(x,y) \to (0,0)} \frac{2x^2 y}{x^4 +y^2}}$$ no existe.

> __15.__ $$\displaystyle{\lim_{(x,y) \to (0,0)} \frac{\sqrt[3]{x} y^2}{x+y^3}}$$

Muy parecido al ejercicio __13__, las trayectorias $$x=0$$ o $$y=0$$ nos llevan a que el límite vale $$0$$ pero si elegimos la trayectoria $$x=y^3$$:

$$\begin{split}
\lim_{(y^3 ,y) \to (0,0)} \frac{\sqrt[3]{(y^3)} y^2}{y^3 +y^3} =& \lim_{(y^3 ,y) \to (0,0)} \frac{y^3}{2y^3} \\
&= \lim_{(y^3,y) \to (0,0)} \frac{1}{2} \\
&= \lim_{y \to 0} \frac{1}{2} \\
&= \frac{1}{2}
\end{split}$$

Llegamos a que el límite _no es único_ y por tanto no existe.

> __17.__ $$\displaystyle{\lim_{(x,y) \to (0,0)} \frac{y\sin{x}}{x^2 +y^2}}$$



> __19.__ $$\displaystyle{\lim_{(x,y) \to (1,2)} \frac{xy - 2x -y +2}{x^2 -2x +y^2 -4y+5}}$$

> __21.__ $$\displaystyle{\lim_{(x,y,z) \to (0,0,0)} \frac{3x^2}{x^2 + y^2 + z^2}}$$

+ Tomemos la trayectoria $$x=0$$

	$$\begin{split}
\lim_{(0,y,z) \to (0,0,0)} \frac{3(0)^2}{(0)^2 + y^2 + z^2} &= \lim_{(0,y,z) \to (0,0,0)} \frac{0}{y^2 + z^2} \\
&= \lim_{(0,y,z) \to (0,0,0)} 0 \\
&= \lim_{(y,z) \to (0,0)} 0 \\
&= 0
\end{split}$$

+ Ahora, si hacemos $$\displaystyle{\frac{3x^2}{x^2 + y^2 + z^2} = }$$ $$\displaystyle{\frac{3}{1 + \frac{y^2}{x^2} + \frac{z^2}{x^2}}}$$, y tomamos la trayectoria $$y=0$$:

$$\begin{split}
\lim_{(x,0,z) \to (0,0,0)} \frac{3}{1 + \frac{y^2}{x^2} + \frac{z^2}{x^2}} &= \lim_{(x,0,z) \to (0,0,0)} \frac{3}{1 + \frac{(0)^2}{x^2} + \frac{(0)^2}{x^2}} \\
&= \lim_{(x,0,z) \to (0,0,0)} \frac{3}{1 + 0 + 0} \\
&= \lim_{(x,z) \to (0,0)} 3 \\
&= 3
\end{split}$$

Así que no se tiene la unicidad del límite y por tanto no existe.

> __23.__ $$\displaystyle{\lim_{(x,y,z) \to (0,0,0)} \frac{xyz}{x^3 +y^3 +z^3}}$$



### Ejercicios 25-29.

Demuestre que el límite indicado existe.

> __25.__ $$\displaystyle{\lim_{(x,y) \to (0,0)} \frac{xy^2}{x^2 + y^2}}$$

> __27.__ $$\displaystyle{\lim_{(x,y) \to (0,0)} \frac{2x^2 \sin{y}}{2x^2 +y^2}}$$

> __29.__ $$\displaystyle{\lim_{(x,y) \to (0,0)} \frac{x^3 +4x^2 +2y^2}{2x^2 +y^2}}$$