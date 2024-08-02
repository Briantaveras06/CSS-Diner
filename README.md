# CSS-Diner
Muestra de lo que hace cada uno de los selectores en CSS Diner:

A
Selecciona todos los elementos <A>.

A
(Repetido del anterior, selecciona todos los elementos <A>).

#id
Selecciona el elemento con el id específico.

A B
Selecciona todos los elementos <B> que son descendientes de <A>.

#id A
Selecciona todos los elementos <A> que son descendientes del elemento con el id específico.

.classname
Selecciona todos los elementos con la clase classname.

A.className
Selecciona todos los elementos <A> que tienen la clase className.

Put your back into it!
Es una expresión de ánimo, generalmente no es un selector CSS. Es posible que sea una instrucción motivacional en el contexto del juego.

A, B
Selecciona todos los elementos <A> y todos los elementos <B>.

*
Selecciona todos los elementos.

A *
Selecciona todos los elementos que son descendientes de <A>.

A + B
Selecciona el elemento <B> que es inmediatamente adyacente al elemento <A>.

A ~ B
Selecciona todos los elementos <B> que son hermanos de <A> y están después de <A>.

A > B
Selecciona todos los elementos <B> que son hijos directos de <A>.

:first-child
Selecciona todos los elementos que son el primer hijo de su padre.

:only-child
Selecciona todos los elementos que no tienen hermanos.

:last-child
Selecciona todos los elementos que son el último hijo de su padre.

:nth-child(A)
Selecciona todos los elementos que son el n-ésimo hijo de su padre, donde A es el índice (1-based).

:nth-last-child(A)
Selecciona todos los elementos que son el n-ésimo hijo de su padre contado desde el final, donde A es el índice (1-based).

:first-of-type
Selecciona el primer elemento de su tipo (etiqueta) dentro de su padre.

:nth-of-type(A)
Selecciona el n-ésimo elemento de su tipo dentro de su padre, donde A es el índice (1-based).

:nth-of-type(An+B)
Selecciona los elementos de su tipo en posiciones que cumplen la fórmula An+B (donde n es un contador comenzando desde 0).

:only-of-type
Selecciona todos los elementos que no tienen hermanos del mismo tipo.

:last-of-type
Selecciona el último elemento de su tipo dentro de su padre.

:empty
Selecciona todos los elementos que no tienen hijos (ni elementos ni texto).

:not(X)
Selecciona todos los elementos que no son del tipo X.

[attribute]
Selecciona todos los elementos que tienen el atributo attribute.

A[attribute]
Selecciona todos los elementos <A> que tienen el atributo attribute.

[attribute="value"]
Selecciona todos los elementos que tienen el atributo attribute con el valor exacto value.

[attribute^="value"]
Selecciona todos los elementos que tienen un atributo attribute cuyo valor comienza con value.

[attribute$="value"]
Selecciona todos los elementos que tienen un atributo attribute cuyo valor termina con value.

[attribute="value"]*
Selecciona todos los elementos que tienen un atributo attribute cuyo valor contiene value en cualquier parte.
