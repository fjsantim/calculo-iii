---
title: "Resumen Clase 3"
author: "Equipo 6"
output: pdf_document
---

\begin{center}
Topología Básica de $\mathbb{R}^n$
\end{center}

Empezaremos definiendo la metrica en el espacio vectorial $\mathbb{R}^n$ para que así podamos definir los conceptos de bolas abiertas y cerradas.$\\$

**Definición**
Cualquier función *d*:$\mathbb{R}^n \times\mathbb{R}\rightarrow\mathbb{R}$ tal que para cualesquiera *x,y,z* $\in\mathbb{R}^n$ se satisfacen las siguientes condiciones:

1. $d(x,y)\geq 0$ y $d(x,x)=0$
2. $d(x,y)=d(y,x)$
3. $d(x,y)=d(x,z)+d(z,y)$
4. $d(x,y)=0 \Rightarrow x=y$

Se le llama métrica o distancia en $\mathbb{R}^n$

**Definición**
Sea p un punto en $\mathbb{R}^n$ definimos la bola abierta con centro en p y radio r>0 como el conjunto $\mathbb{B}_r(p) =\{ x \in \mathbb{R}^n : d(x,p)<r\}$.
Por otro lado definimos la bola cerrada con centro en p y radio r$\geq 0$ como el conjunto $\overline{\mathbb{B}_r(p)} =\{ x \in \mathbb{R}^n : d(x,p)<r\}.\\$

La Topología es un área de las matemáticas muy importante que se interesa por conceptos como proximidad, continuidad, conectividad (o conexidad), compacidad, y muchos otros más. Para abordarlos de manera precisa, primero es necesario definir un cierto tipo de conjuntos (que en Topología se les conoce como los conjuntos abiertos)[Páez, p.16].

**Definición** 
Decimos que un conjunto $\mathbb{V}\subseteq\mathbb{R}^n$ es abierto $\iff$ para cada punto *p*$\in\mathbb{V}$ $\exists r>0$ tal que $\mathbb{B}_r(p)\subset\mathbb{V}.\\$
**Definición**
Decimos que un conjunto $\mathbb{F}\subseteq\mathbb{R}^n$ es cerrado $\iff$ su complemento es abierto, es decir, si $\mathbb{R}^n\setminus F$ es abierto.

**Proposición**
Toda bola abierta $\mathbb{B}_r(p)$ en $\mathbb{R}^n$ es un conjunto abierto.

Dem:
$\\$Pd. $\forall x\in\mathbb{B}_r(p)$ $\exists\delta>0$ tal que $\mathbb{B}_\delta (x)\subset\mathbb{B}_r (p)\\$
sea $x\in\mathbb{B}_r (p)\hspace{2cm}$             Pd.$\exists\delta>0$ tal que $\mathbb{B}_\delta (x)\subset\mathbb{B}_r (p)\\$
sea $\delta = r-d(x,p)\\$
sea $y\in\mathbb{B}_\delta (x)\hspace{2cm}$ Pd.$y\in\mathbb{B}_r (p)\\$
como $y\in\mathbb{B}_\delta (x)$ $\Longrightarrow d(x,y)<\delta = r-d(x,p)$ $\Longrightarrow d(x,y)+d(x,p)< r\\$
$\Longrightarrow d(y,x)+d(x,p)<r \Longrightarrow d(y,p)<r\\$
$\therefore y\in\mathbb{B}_r (p).\\ \blacksquare$

**Proposición**$\\$
a) Si $\mathbb{A}$ y $\mathbb{B}$ son subconjuntos abiertos en $\mathbb{R}^n \Longrightarrow \mathbb{A}\cup\mathbb{B}$ y $\mathbb{A}\cap\mathbb{B}$ también lo son.$\\$
b) Si $\mathbb{A}$ y $\mathbb{B}$ son subconjuntos cerrados en $\mathbb{R}^n \Longrightarrow \mathbb{A}\cup\mathbb{B}$ y $\mathbb{A}\cap\mathbb{B}$ también lo son.$\\$

Dem a):$\\$
Para la unión: $\\$
sea x$\in\mathbb{A}\cup\mathbb{B}$ como x$\in\mathbb{A}\cup\mathbb{B}\Longrightarrow$ $x\in\mathbb{A}$ ó $x\in\mathbb{B}\\$

1. Si $x\in\mathbb{A}$ y como $\mathbb{A}$ es abierto $\Longrightarrow\exists$ r>0 tal que $\mathbb{B}_r (x)\subset\mathbb{A}\\$
   $\Longrightarrow\mathbb{B}_r (x)\subset\mathbb{A}\cup\mathbb{B}$
   $\therefore \mathbb{A}\cup\mathbb{B}$ es abierto.$\\$
2. Si $x\in\mathbb{B}$ y como $\mathbb{B}$ es abierto $\Longrightarrow\exists$ r>0 tal que $\mathbb{B}_r (x)\subset\mathbb{B}\\$
   $\Longrightarrow\mathbb{B}_r (x)\subset\mathbb{B}\cup\mathbb{A}$$\Longrightarrow\mathbb{B}_r (x)\subset\mathbb{A}\cup\mathbb{B}$
   $\therefore \mathbb{A}\cup\mathbb{B}$ es abierto.$\\$
  
$\therefore$ de 1 y 2 podemos concluir que $\mathbb{A}\cup\mathbb{B}$ es abierto.$\\$
   
Para la intersección:$\\$
sea x$\in\mathbb{A}\cap\mathbb{B}\Longrightarrow$ x$\in\mathbb{A}$ y x$x\in\mathbb{B}\\$
como x$\in\mathbb{A}$ y $\mathbb{A}$ es abierto $\Longrightarrow\exists r_1>0$ tal que $\mathbb{B}_{r_1}(x)\subset\mathbb{A}\\$
como x$\in\mathbb{B}$ y $\mathbb{B}$ es abierto $\Longrightarrow\exists r_2>0$ tal que $\mathbb{B}_{r_2}(x)\subset\mathbb{B}\\$
sea $r=min\{r_1,r_2\}$ Así $\mathbb{B}_r (x)\subset\mathbb{B}_{r_1}(x)\subset\mathbb{A}$ y $\mathbb{B}_r (x)\subset\mathbb{B}_{r_2}(x)\subset\mathbb{B}\Longrightarrow\mathbb{B}_r (x)\subset\mathbb{A}\cap\mathbb{B}\\$
$\therefore\mathbb{A}\cap\mathbb{B}$ es abierto. $\\$

Dem b):$\\$
La demostración de este inciso se encuentra en el apartado de tareas. $\\$
$\blacksquare \\$
Ahora daremos la definición de punto interior y punto de adherencia, esto nos permitirá dar definiciones alternas de conjuntos cerrados y abiertos.$\\$

**Definición:** Sea $\mathbb{A}$ un subconjunto de $\mathbb{R}^n\\$
a. Un punto p$\in\mathbb{A}$ es un punto interior de $\mathbb{A}.$ Si $\exists$ una bola abierta $\mathbb{B}_r (p)$, donde $\mathbb{B}_r (p) \subset\mathbb{A}.\\$
b. Un punto p$\in\mathbb{R}^n$ es punto de adherencia de $\mathbb{A}$ si $\forall$ bola abierta $\mathbb{B}_r (p)$ tiene puntos de $\mathbb{A}$ es decir $\mathbb{B}_r (p)\cap\mathbb{A}\neq\emptyset. \\$

**Observación 1** Al conjunto de todos los puntos interiores de un conjunto se le llama interior del conjunto, y se denota como:
$\mathring{A}$ = $\{x\in\mathbb{A}$: $\exists$ $\mathbb{B}_r(p)\subset\mathbb{A}\}.\\$
**Observación 2** Al conjunto de todos los puntos adherentes de $\mathbb{A}$ se le llama la adherencia o cerradura de $\mathbb{A}$ y se denota de la siguiente manera: $\overline{\mathbb{A}}. \\$

**Ejemplos:**$\\$
1. Si $\mathbb{A}=$[3,5] $\Longrightarrow\mathring{\mathbb{A}}$=(3,5) y $\overline{\mathbb{A}}=$[3,5]$\\$
2. Si $\mathbb{A}=\{1/n : n\in\mathbb{N}\}\Longrightarrow\mathring{\mathbb{A}}=\emptyset$ y $\overline{\mathbb{A}}=\mathbb{A}\cup\{0\}\\$






