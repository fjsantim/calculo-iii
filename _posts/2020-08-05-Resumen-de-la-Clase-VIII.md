---
title: Resumen de la Clase VIII
---

## Apuntes de la clase del 5 de agosto de 2020

### Proposición. $$Fr(A)= Fr(\mathbb{R} - A)$$

__Demostración__: \\ 

$$ \subset $$
$$ Fr(A) = Fr(A^{c}) $$ 

Si $$ x \in Fr(A) \Rightarrow x \in \bar{A} \Rightarrow \forall B_{r}(x)\cap A \neq \varnothing  $$ y 
$$ x \in (\bar{A^c} )\Rightarrow \forall B_{r} (x) \cap A^c \neq \varnothing $$

Por lo tanto $$ x \in A^c $$

$$ \supset $$

Sea $$x \in Fr(A^c) \Rightarrow \forall B_{r} (x) \cap A^c \neq \varnothing $$ y 
$$ \forall B_{r} (x) \cap (A^c)^c \neq \varnothing $$ 
pero $$(A^c)^c = A$$   $$\therefore x \in Fr(A) $$

### Ejercicios

1. $$A=[a,b)$$

	$$A°=(a,b)$$, $$\bar{A}= [a,b]$$, $$Fr=\{a,b\}$$

2. $$A= \mathbb Q $$

	$$A°= \varnothing $$, $$ \bar{A}= \mathbb{R}$$, $$Fr(A)= \mathbb{R}$$

3. $$A= \varnothing$$

	$$A°= \varnothing$$, $$\bar{A}= \varnothing$$, $$Fr(A)= \varnothing$$ 

4. $$A= \{p \}$$ $$p$$ un punto

	$$A°= \varnothing$$, $$\bar{A}= \{ p \}$$, $$Fr(A)=\{p\}$$

5. $$A= \{ 1/n : n\in \mathbb N \}$$

	$$A°= \varnothing$$, $$ \bar{A}= A \cup \{0\}$$, $$Fr(A)= A \cup \{0\}$$

6. $$A= \{ [1,3)\times (0,4)\}$$

	$$A°= (1,3) \times (0,4)$$, $$\bar{A}= [1,3] \times [0,4]$$
	$$Fr(A)= ( \{3\} \times [0,4]) \cup( [1,3) \times \{0\}) \cup ( \{3\} \times [0,4]) \cup ([1,3] \times \{4\}$$

7. $$\{[1,5) \cup \{7\}\}$$

	$$A°=(1,5)$$, $$\bar{A}=[1,5] \cup \{7\}$$, $$Fr(A)= \{1,5,7\}$$

### Proposición. Para cualquier subconjunto A de $$\mathbb{R}^n$$ se tiene:

a) $$Fr(A)= \bar{A} - A°$$

b) $$\bar{A}= A° \cup Fr(A)$$

### Puntos de acumulación y conjunto derivado

Sea A un subconjunto de $$\mathbb{R}^n$$. Decimos que un punto _$$p$$_ es un punto de acumulación de $$A$$ si toda bola abierta con centro en _$$p$$_ tiene puntos de $$A$$ distintos de _$$p$$_. 

El conjunto de todos los puntos de acumulación de $$A$$ se le llama $$\textbf{conjunto derivado}$$ y se denota como $$A^a$$ o $$A^d$$.
