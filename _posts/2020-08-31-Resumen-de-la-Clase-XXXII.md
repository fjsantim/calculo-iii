---
title: Resumen de la Clase XXXII
---

### Resumen de la clase del 31 de agosto (Teorema de Heine-Borel)

Esta clase se centró en la prueba de uno de los teoremas más importantes de la topología de $$\mathbb{R}^n$$. En las últimas prácticas  entendimos la definición un conjunto compacto como aquel en el que toda cubierta abierta de este conjunto tiene una subcubierta finita. Ahora entenderemos la compacidad en términos de otras propiedades, como las propiedades de ser abierto o cerrado, y acotado o no acotado. Para ello debemos repasar algunos teoremas que nos serán útiles.

> Teorema de los intervalos anidados
>
> Si pensamos por un momento en el conjunto $$\mathbb{R}$$, podemos definir una sucesión de intervalos $$I_n=[a_n,b_n] \ \ \forall n \in \mathbb{N}$$ tal que cada uno esté contenido en el anterior, es decir, que $$I_n \subset I_{n+1}$$. Una consecuencia de esto es que el supremo de todos los $$a_n$$ y el ínfimo de todos los $$b_n$$ coinciden (llamémosle $$\alpha$$), cumpliendo la propiedad de que $$a_n \leq \alpha \leq b_n \ \ \forall n\in \mathbb{N}$$. Esto nos indica, que $$\cap_{k=1}^\infty I_k \neq \emptyset$$.

> Definición de celda
>
> Podemos generalizar la definición de los intervalos cerrados y acotados del teorema anterior a espacios $$\mathbb{R}^n$$. Por ejemplo, en $$\mathbb{R}^2 = \mathbb{R} \times \mathbb{R}$$, podemos formar productos de intervalos $$I = [a_{1},b_{1}] \times [a_{2},b_{2}] $$, de manera que en el plano, se ven como rectángulos con vértices determinados por los límites de estos intervalos. En general, en $$\mathbb{R}^n$$ se tiene $$I= [a_{1},b_{1}] \times [a_{2},b_{2}]\times ... \times [a_{n},b_{n}]$$. Esto nos permite pensar, por ejemplo, en una sucesión $$I_k$$ de celdas de la forma $$I_k =[a_{k1},b_{k1}] \times [a_{k2},b_{k2}]\times ... \times [a_{kn},b_{kn}] $$.  

#### Generalización del teorema de intervalos anidados

Podemos ahora generalizar el primer teorema a celdas en $$\mathbb{R}^n$$, de manera que para toda sucesión de celdas anidadas $$I_n$$, se tiene $$\cap_{k=1}^\infty I_k \neq \emptyset$$. La demostración de este enunciado se deduce naturalmente del teorema de intervalos anidados, debido que ahora tendremos $$n$$ sucesiones de números $$a_{kn}$$ y $$b_kn$$. Al final, estas sucesiones convergen a un número que pertenece a todas las celdas, demostrando el teorema.

#### Compacidad de celdas en $$\mathbb{R}^n$$

Otro resultado que será de utilidad para lo que queremos demostrar, es el hecho de que toda celda de $$\mathbb{R}^n$$ cumple la propiedad de ser un conjunto compacto. La demostración de esta afirmación (que ejemplificaremos en $$\mathbb{R}^2$$ sin perdida de generalidad) consiste de tres pasos. En el primer paso, nos fijamos en que la distancia entre cualesquiera dos puntos de un rectángulo es siempre menor que la diagonal del rectángulo. En el segundo paso, definimos un conjunto de subceldas de la celda original, formadas al tomar un punto intermedio en cada intervalo y dividir la celda en dos. Este procedimiento se conoce como $$bisecci\acute{o}n$$. Finalmente, suponemos que para una cubierta abierta de la celda no existe una cubierta finita, llegando a una contradicción, gracias a la elección de una cubierta mediante estas subceldas.

Teorema de Heine-Borel

El enunciado final que queríamos probar al inicio es el siguiente. Dado un subconjunto de $$\mathbb{R}^n$$, se tiene que es compacto si y sólo si este es cerrado y acotado. La prueba de este teorema se sigue de las propiedades anteriores, construyendo una subcubierta finita a partir de un conjunto de celdas anidadas, y usando la propiedad de que todo conjunto acotado puede contenerse en una bola de radio finito.
