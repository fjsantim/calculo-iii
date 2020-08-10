---
title: Tareas de la Clase X
---

## Tareas de la clase del 7 de agosto de 2020

### Propiedad Arquimediana

Se verifica que $$\forall r>0$$ existe $$n\in \mathbb{N}$$ tal que  $$0<\frac{1}{2^n}<r$$.

Por la desigualdad de Bernoulli tenemos que $$2^n\geq1+2n\geq2n\geq n$$ para toda $$n\in\mathbb{N}$$, y por la propiedad arquimediana tenemos que
$$\forall r>0$$ existe $$n\in \mathbb{N}$$ con $$n>r$$ tal que $$0<\frac{1}{n}<r$$ entonces:
$$0<\frac{1}{2^n}\leq\frac{1}{1+2^n}\leq\frac{1}{2n}\leq\frac{1}{n}<r$$ 
$$0<\frac{1}{2^n}<r$$.

### Desigualdad de Bernoulli

$$(1+a)^n\geq1+na, a>0, n\in\mathbb N$$

Demostramos por inducción:

$$n=1$$
$$(1+a)^1=1+(1)a $$
$$n=2$$
$$(1+a)^2=1+2a+a^2\geq1+2a$$

Suponemos cierto para $$n=k$$
$$n=k+1$$

Por hipótesis tenemos que 
$$(1+a)^n\geq1+na$$

Entonces

$$(1+a)^n(1+a)\geq(1+na)(1+a)$$

$$(1+a)^{n+1}\geq[(1+na)+(a+na^2)]$$

$$(1+a)^{n+1}\geq[1+na+a+na^2]$$

$$(1+a)^{n+1}\geq[1+(n+1)a+na^2]\geq[1+(n+1)a]$$

$$(1+a)^{n+1}\geq1+(n+1)a$$
