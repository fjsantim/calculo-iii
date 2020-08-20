---
title: Resumen de la Clase XVI
---

## Apuntes de la clase del 17 de agosto de 2020

### Imagen Inversa

Durante la clase vimos la definición de imagen inversa y sus propiedades.

La imagen directa de una función $$f:X\to Y$$ esta definida como

$$f(A)=\{y\in Y: y=f(x) \textrm{ para alguna }x\in A\}$$

y la imagen inversa definida como:

$$f^{-1}(M)={x\in X: f(x)\in M}$$

Cumplen las siguientes proposiciones, en las que se esbozan algunas demostraciones.

+ Imagen Directa

	+ Si $$A\subset B$$, entonces $$f(A)\subset f(B)$$

	$$a\in f(A) \exists x\in A \textrm{ tal que } a=f(x) \textrm{ y como }$$

	$$A\subset B \implies x \in B \implies f(x)\in f(B)$$

	+ $$f(A\cup B)=f(A)\cup f(B)$$

	$$y\in f(A\cup B) \textrm{ entonces existe }x\in A\cup B \textrm{ tal que }y=f(x)$$

	$$x\in A\implies x\in A\implies f(x)\in f(A)\in f(A)\cup f(B)$$

	$$\textrm{ caso análogo para }x\in B$$

	+ $$f(A\cap B)\subset f(A)\cap f(B)$$

	$$y\in f(A \cap B) \textrm{ entonces existe }x\in A\cap B \textrm{ tal que }y=f(x)$$

	$$x\in A\cap B \implies x\in A \implies f(x)\in f(A) \textrm{ también }$$

	$$x\in A \cap B \implies x\in B\implies f(x)\in f(A)\implies f(x)\in f(A)\cap f(B)$$

	+ $$f(A\setminus B)\subset f(A)$$

	+ $$f(A)\setminus f(B) \subset f(A\setminus B)$$

+ Imagen Inversa

	+ Si $$F\subset G$$, entonces $$f^{-1}(F)\subset f^{-1}(G)$$

	+ $$f^{-1}(F\cup G)=f^{-1}(F)\cup f^{-1}(G)$$

	+ $$f^{-1}(F\cap G)= f^{-1}(F)\cup f^{-1}(G)$$

	+ $$f^{-1}(F \setminus G)=f^{-1}(F)\setminus f^{-1}(G)$$
