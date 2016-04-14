# css-counter
Make a game only with HTML and CSS

> body { counter-reset: game; }

Inicializamos a 0 la variable 'game' dentro del ambito de 'body'.

> .total-count::after { content: counter(game); }

Mostramos el valor de la variable 'game' dentro de 'total-count'.

> .inner-check::checked { counter-increment: game 20; }

Si este elemento existe. Es decir el input 'inner-check' esta en modo 'checked' incrementará la variable game en 20.
