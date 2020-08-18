---
title: Resumen de la Clase III
---

## Apuntes de la clase del 29 de julio de 2020

Topología Básica de $$\mathbb{R}^n$$

Empezaremos definiendo la metrica en el espacio vectorial $$\mathbb{R}^n$$ para que así podamos definir los conceptos de bolas abiertas y cerradas.

> **Definición**
> Cualquier función $$\textbf{d}:\mathbb{R}^n \times\mathbb{R}\rightarrow\mathbb{R}$$ tal que para cualesquiera $$x,y,z$$ $$\in\mathbb{R}^n$$ se satisfacen las siguientes condiciones:
> 
> 1. $$d(x,y)\geq 0$$ y $$d(x,x)=0$$
>
> 2. $$d(x,y)=d(y,x)$$
>
> 3. $$d(x,y)=d(x,z)+d(z,y)$$
>
> 4. $$d(x,y)=0 \rightarrow x=y$$

Se le llama métrica o distancia en $$\mathbb{R}^n$$

> **Definición**
> Sea p un punto en $$\mathbb{R}^n$$ definimos la bola abierta con centro en $$p$$ y radio $$r>0$$ como el conjunto $$B_r(p) =\{ x \in \mathbb{R}^n : d(x,p)<r\}$$.
> Por otro lado definimos la bola cerrada con centro en p y radio r$$\geq 0$$ como el conjunto $$\overline{B_r(p)} =\lbrace x \in \mathbb{R}^n : d(x,p)<r\rbrace$$.

La Topología es un área de las matemáticas muy importante que se interesa por conceptos como proximidad, continuidad, conectividad (o conexidad), compacidad, y muchos otros más. Para abordarlos de manera precisa, primero es necesario definir un cierto tipo de conjuntos (que en Topología se les conoce como los conjuntos abiertos)[Páez, p.16].

> **Definición** 
>
> Decimos que un conjunto $$\mathbb{V}\subseteq\mathbb{R}^n$$ es abierto $$\iff$$ para cada punto *p*$$\in\mathbb{V}$$ $$\exists r>0$$ tal que $$B_r(p)\subset\mathbb{V}$$.

> **Definición**
>
> Decimos que un conjunto $$\mathbb{F}\subseteq\mathbb{R}^n$$ es cerrado $$\iff$$ su complemento es abierto, es decir, si $$\mathbb{R}^n\setminus F$$ es abierto.

> **Proposición**
>
> Toda bola abierta $$B_r(p)$$ en $$\mathbb{R}^n$$ es un conjunto abierto.

> __Prueba:__
> 
> Por demostrar: $$\forall x\in\mathbb{B}_r(p)$$ $$\exists\delta>0$$ tal que $$B_\delta (x)\subset B_r (p)\\$$
> sea $$x\in B_r (p)\hspace{2cm}$$
> Pd.$$\exists\delta>0$$ tal que $$B_\delta (x)\subset B_r (p)\\$$
> sea $$\delta = r-d(x,p)\\$$
> sea $$y\in B_\delta (x)\hspace{2cm}$$ Pd.$$y\in B_r (p)\\$$
> como $$y\in\mathbb{B}_\delta (x)$$ $$\Longrightarrow d(x,y)<\delta = r-d(x,p)$$ $$\Longrightarrow d(x,y)+d(x,p)< r\\$$
> $$\Longrightarrow d(y,x)+d(x,p)<r \Longrightarrow d(y,p)<r\\$$
> $$\therefore y\in\mathbb{B}_r (p).\\ \blacksquare$$

> __Proposición__
>
> a) Si $$A$$ y $$B$$ son subconjuntos abiertos en $$\mathbb{R}^n \Longrightarrow A \cup B$$ y $$A \cap B$$ también lo son.
>
> b) Si $$A$$ y $$B$$ son subconjuntos cerrados en $$\mathbb{R}^n \Longrightarrow A \cup B$$ y $$A\cap B$$ también lo son.

> Prueba a):
>
> Para la unión:
>
> Sea x$$\in A\cup B$$ como x$$\in A \cup B \implies$$ $$x\in A$$ ó $$x\in B$$
>
> 1. Si $$x\in A$$ y como $$A$$ es abierto $$\implies \exists$$ r>0 tal que $$B_r (x)\subset A\\$$
   $$\implies B_r (x)\subset A\cup B$$
   $$\therefore A \cup B$$ es abierto.
>
> 2. Si $$x\in B$$ y como $$B$$ es abierto $$\implies \exists r>0$$ tal que $$B_r (x)\subset B\\$$
   $$\implies B_r (x)\subset B\cup A $$ $$\implies B_r (x)\subset A\cup B$$
   $$\therefore A \cup B$$ es abierto.$$\\$$
>
> $$\therefore$$ de 1 y 2 podemos concluir que $$\mathbb{A}\cup\mathbb{B}$$ es abierto.$$\\$$
   
> Para la intersección:
>
> sea $$x \in A\cap B \implies$$ $$x \in A$$ y $$x\in B$$
> como $$x\in A$$ y $$A$$ es abierto $$\implies \exists r_1>0$$ tal que $$B_{r_1}(x)\subset A \\$$
> como $$x\in B$$ y $$B$$ es abierto $$\implies \exists r_2>0$$ tal que $$B_{r_2}(x)\subset B \\$$
> sea $$r=min\{r_1,r_2\}$$ Así $$B_r (x)\subset B_{r_1}(x)\subset A$$ y $$B_r (x)\subset B_{r_2}(x)\subset B \implies B_r (x)\subset A \cap B \\$$
> $$\therefore A \cap B$$ es abierto. $$\\$$

> Dem b):
>
> La demostración de este inciso se encuentra en el apartado de tareas. $$\\$$
> $$\blacksquare \\$$

Ahora daremos la definición de punto interior y punto de adherencia, esto nos permitirá dar definiciones alternas de conjuntos cerrados y abiertos.$$\\$$

> __Definición:__ Sea $$A$$ un subconjunto de $$\mathbb{R}^n$$
>
> a. Un punto $$p\in A$$ es un punto interior de $$A$$. Si existe una bola abierta $$B_r (p)$$, donde $$B_r (p) \subset A$$.
>
> b. Un punto $$p\in\mathbb{R}^n$$ es punto de adherencia de $$A$$ si para toda bola abierta $$B_r (p)$$ tiene puntos de $$A$$ es decir $$B_r (p)\cap A \neq\emptyset$$.

> __Observación 1:__ Al conjunto de todos los puntos interiores de un conjunto se le llama interior del conjunto, y se denota como:
> $$\mathring{A}$$ = $$\{x\in A$$: $$\exists$$ $$B_r(p)\subset A\}.\\$$

> __Observación 2:__ Al conjunto de todos los puntos adherentes de $$A$$ se le llama la adherencia o cerradura de $$A$$ y se denota de la siguiente manera: $$\overline{A}. \\$$

> __Ejemplos:__
>
> 1. Si $$A=[3,5]$$ $$\Longrightarrow\mathring{A}=(3,5)$$ y $$\overline{A}=[3,5]$$
>
> 2. Si $$A=\{1/n : n\in\mathbb{N}\}\Longrightarrow\mathring{A}=\emptyset$$ y $$\overline{A}=\mathbb{A}\cup\{0\}\\$$
