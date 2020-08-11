---
title: Resumen de la Clase I
---

## Apuntes de la clase del 27 de julio de 2020

La primera clase fue principalmente conocer algunas definiciones, mismas que se listarán a continuación:


### Espacios y subespacios vectoriales

Empezaremos por definir las propiedades que deben cumplir los conjuntos no vacíos para que sean _espacios vectoriales_.

__Definición:__ Sea $$V$$ un conjunto distinto del vacío, en el cual están definidas dos operaciones(suma y producto por un escalar). Diremos que $$V$$ es un _espacio vectorial_ si satisface
 las siguientes propiedades: 

Sean $$\vec{u}$$, $$\vec{v}$$, $$\vec{w} \in V$$, sea $$\alpha$$, $$\beta \in \mathbb{R}$$

1. $$\vec{u} + \vec{v} \in V$$

2. $$\vec{u} + \vec{v} = \vec{v} + \vec{u}$$

3. $$\vec{u} + (\vec{v} + \vec{w}) = (\vec{u} + \vec{v}) + \vec{w}$$

4. Existe un vector nulo $$0_{V} \in V$$ tal que $$\vec{v} + \vec{0} = \vec{v}$$

5. Para cada  $$\vec{v} \in V$$ existe un opuesto $$-\vec{v}\in V$$ tal que $$\vec{v} + (-\vec{v}) = \vec{0_{V}}$$

6. $$\alpha\vec{v} \in V$$

7. $$\alpha(\vec{u} + \vec{v}) = \alpha\vec{u} + \alpha\vec{v}$$

8. $$(\alpha + \beta)\vec{v} = \alpha\vec{v} + \beta\vec{v}$$

9. $$\alpha(\beta\vec{v}) = (\alpha\beta)\vec{v}$$

10. $$1\vec{v} = \vec{v}$$

Y ahora la definición de los _subespacios vectoriales_:

**Definición:** Sea $$V$$ un espacio vectorial y $$U \subseteq V$$, se dice que $$U$$ es un 
_subespacio vectorial_ de $$V$$ si satisface las siguientes propiedades:

1. Si $$\vec{u}$$,$$\vec{v} \in U$$, entonces $$\vec{u}+\vec{v}\in U$$.

2. Si $$\lambda \in \mathbb{R}$$ y $$\vec{u} \in U$$ entonces $$\lambda\vec{u}\in U$$.

__Nota:__ Los subespacios vectoriales más "triviales" en cualquier espacio vectorial $$V$$ son: 
el mismo conjunto $$V$$ y el conjunto que contiene únicamente a $$0_{V}$$. Además, todo subconjunto
vectorial $$U$$ de $$V$$ debe cumplir que $$0_{V}\in U$$.

### Producto punto

__Definición:__ Consideremos los vectores $$\vec{v} = (v_1, v_2, \dots, v_n) \in \mathbb{R}^n$$ y $$\vec{w} = (w_1,w_2, \dots, w_n) \in \mathbb{R}^n$$.
El producto punto (o escalar) $$\vec{v}\cdot\vec{w}$$ se define de la siguiente manera: 

$$\vec{v}\cdot\vec{w} = v_{1}w_{1} + v_{2}w_{2} + \dots + v_{n}w_{n} \in \mathbb{R}$$

### Norma de un vector

La norma define la longitud de un vector desde el punto de vista de la geometría euclideana.

__Definición:__ Sea $$\vec{v}=(v_1, v_2, \dots, v_n) \in\mathbb{R}^n$$. La norma de $$\vec{v}$$ se denota como $$\|\vec{v}\|$$ y se define de la siguiente manera:

$$\displaystyle{\|\vec{v}\| = \sqrt{\vec{v}\cdot\vec{v}} = \sqrt{v_1^2 + v_2^2 + \dotsb + v_n^2}}$$

En el siguiente teorema se listan algunas propiedades de la norma:

__Teorema:__ Sean $$\vec{v}$$,$$\vec{w} \in \mathbb{R}^n$$ y $$\alpha \in \mathbb{R}$$. Entonces se cumple lo siguiente:

1. $$\|\vec{v}\| \geq{0}$$ y $$\|\vec{v}\| = 0$$ si y solo si $$\vec{v} = 0$$.

2. $$\|\alpha\vec{v}\| = \mid\alpha\mid\|\vec{v}\|$$

3. $$\|\vec{v}-\vec{w}\| = \|\vec{w}-\vec{v}\|$$

4. $$\|\vec{v} + \vec{w}\| \leq \|\vec{v}\| + \|\vec{w}\|$$  (_desigualdad triangular_)

5. $$\mid\vec{v}\cdot\vec{w}\mid \leq \|\vec{v}\|\|\vec{w}\|$$  (_desigualdad Cauchy Schwarz_)


### Producto cruz

__Definicion:__ Consideremos los vectores $$\vec{u} = (u_1, u_2, u_3)$$, $$\vec{v} = (v_1, v_2, v_3) \in \mathbb{R}^3$$. El _producto 
cruz_ $$\vec{u}\times\vec{v}$$ se define de la siguiente manera:


$$\begin{split}
\vec{u}\times\vec{v} & = \begin{vmatrix} 
                         \notag
                         \hat{i} & \hat{j} & \hat{k} \\
                         u_1 & u_2 & u_3 \\
                         v_1 & v_2 & v_3
                         \end{vmatrix} \\
                     & = (u_2v_3-u_3v_2)\hat{i}-(u_1v_3-u_3v_1)\hat{j}+(u_1v_2-u_2v_1)\hat{k}
\end{split}$$

A continuación unas propiedades:

__Proposición__ sean $$\vec{u}$$, $$\vec{v}$$, $$\vec{w} \in \mathbb{R}^3$$ se cumple que:

1. $$\vec{u}\cdot(\vec{u}\times\vec{v}) = 0$$

2. $$\vec{v}\cdot(\vec{u}\times\vec{v}) = 0$$

3. $$\|\vec{u}\times\vec{v}\|^2 = \|\vec{u}\|^2\|\vec{v}\|^2-(\vec{u}\cdot\vec{v})^2$$ (igualdad de Lagrange)

4. $$\vec{u}\times\vec{v} = -(\vec{v}\times\vec{u})$$

5. $$\vec{u}\times (\vec{v} + \vec{w}) = \vec{u}\times\vec{v} + \vec{u}\times\vec{w}$$

6. $$(\vec{u} +\vec{v})\times\vec{w} = \vec{u}\times\vec{w} + \vec{v}\times\vec{w}$$

7. $$\alpha (\vec{u}\times\vec{v}) = (\alpha\vec{u})\times\vec{v} = \vec{u}\times(\alpha\vec{v})$$

8. $$\vec{u}\times\vec{0} = \vec{0}\times\vec{u} = \vec{0}$$

9. $$\vec{u}\times\vec{u} = \vec{0}$$




