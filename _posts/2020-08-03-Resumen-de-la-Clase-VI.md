---
title: Resumen de la Clase VI
---

## Apuntes de la clase del 3 de agosto de 2020


La clase del 3 de agosto fue, en resuemen, una introducción a las funciones de $$\mathbb{R}^n$$ en $$\mathbb{R}^m$$, curvas
de nivel y trazas de esas funciones. Todo esto se desglosa a continuación:

### Funciones de $$\mathbb{R}^n$$ en $$\mathbb{R}^m$$

> La función $$f:D\subset\mathbb{R}^{n}\to\mathbb{R}^m$$ es una función compuesta por $$m$$ funciones
reales $$f_i$$ tal que cada $$f_{i}$$ sea una función $$f_{i}:D\subset\mathbb{R}^n\to\mathbb{R}$$ de modo que $$f$$ tenga $$m$$ coordenadas $$f_{i}$$ y:
>
> $$\displaystyle{f(\vec{x})=(f_{1}(\vec{x}), f_{2}(\vec{x})), \dots, f_{m}(\vec{x})))}$$
>
> O dicho de otra forma $$f_{i}$$ es una función que toma $$\vec{x}\in D$$ y lo "envía" a algún valor en $$\mathbb{R}$$, después estos valores son cada
coordenada de un vector en $$\mathbb{R}^m$$.

En clase vimos un ejemplo de funciones componentes $$f_{i}$$ y sus dominios $$D\subset\mathbb{R}^2$$, mismos que se deja a continuación la función $$f_{3}$$:

> La función $$f_{3}(x,y)=x\ln(y^{2}-x)$$ tiene sentido solo si $$y^{2}-x > 0$$. Entonces su dominio es $$C=\lbrace (x,y):x<y^2 \rbrace\subset\mathbb{R}^2$$. El dominio se muestra a continuación

![]({{"img/c-6/1.png" | prepend: site.baseurl }}){:height="90%" width="90%"}

### Gráfica de una función

> La gráfica de $$f:D\subset\mathbb{R}^{n}\to\mathbb{R}$$ es el subconjunto:
>
> $$\displaystyle{\lbrace(x_{1}, x_{2}, \dots, x_{n}, f(x_{1}, x_{2}, \dots, x_{n}))\in\mathbb{R}^{n+1} \mid (x_{1}, x_{2}, \dots, x_{n})\in U \rbrace}$$

### Curvas de nivel

> Dada $$f:D\subset\mathbb{R}^{2}\to\mathbb{R}$$. La curva de nivel $$c\in\mathbb{R}$$ es el conjunto:
>
> $$\displaystyle{N_{c}=\lbrace(x,y)\in U \mid f(x,y)= c \rbrace \subset\mathbb{R}^{2}}$$

Esto es funciones igualadas a una constante en los reales. Por ejemplo se dejan algunas curvas de nivel de la función $$f:D\subset\mathbb{R}^{2}\to\mathbb{R}$$ dada por $$\displaystyle{f(x,y)=\frac{x^4 + y^4}{2x+y}}$$

![]({{"img/c-6/2.png" | prepend: site.baseurl }}){:height="90%" width="90%"}

### Traza

> Las trazas de una función son curvas en el espacio obtenidas por la intersección de su gráfica con planos paralelos a los coordenados.
>
> + La traza que resulta de la intersección de la función $$f(x,y)$$ con el plano $$x=c$$ es el conjunto de puntos:
>
> $$\displaystyle{\lbrace(c,y,f(c,y)) \rbrace\subset\mathbb{R}^3}$$
>
> + La traza que resulta de la intersección de la función $$f(x,y)$$ con el plano $$y=c$$ es el conjunto de puntos:
>
> $$\displaystyle{\lbrace(x,c,f(x,c)) \rbrace\subset\mathbb{R}^3}$$
>
> + La traza que resulta de la intersección de la función $$f(x,y)$$ con el plano $$z=c$$ es el conjunto de puntos:

$$\displaystyle{\lbrace(x,y,f(x,y)=c) \rbrace\subset\mathbb{R}^3}$$

### Superficies de nivel

> Dada $$f:U\subset\mathbb{R}^{3}\to\mathbb{R}$$. La superficie de nivel $$c\in\mathbb{R}$$ es el conjunto:
> 
> $$\displaystyle{S_{c}=\lbrace(x,y,z)\in U \mid f(x,y,z)=c \rbrace \subset \mathbb{R}^{3}}$$

Y finalmente a continuación agrego un gráfico hecho en Geogebra que vimos en clase:

<iframe scrolling="no" title="Sin título" src="https://www.geogebra.org/material/iframe/id/bxujhdft/width/1366/height/652/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/false/rc/false/ld/false/sdz/false/ctl/false" width="683px" height="326px" style="border:0px;"> </iframe>
