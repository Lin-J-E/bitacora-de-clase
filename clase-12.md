# Lógica de Primer Orden

En esta clase introdujimos los predicados de [orden superior](http://wiki.uqbar.org/wiki/articles/orden-superior.html):
 - [not/1](http://wiki.uqbar.org/wiki/articles/paradigma-logico---negacion.html) para la negación
 - [forall/2](http://wiki.uqbar.org/wiki/articles/paradigma-logico---el-forall.html) para el cuantificador universal (para todo)

De esa forma cubrimos todo lo relacionado con existencia (no hace falta usar ningún predicado especial para esto), no existencia y para todo, que es lo que nos faltaba para poder trabajar con [lógica de primer orden](http://wiki.uqbar.org/wiki/articles/paradigma-logico---existe-vs-para-todo.html).

También vimos que ambos predicados tienen [problemas de inversibilidad](http://wiki.uqbar.org/wiki/articles/paradigma-logico---casos-de-no-inversibilidad.html), con lo cual hay que tomar ciertos recaudos al usarlos para que nuestros predicados sean [inversibles](http://wiki.uqbar.org/wiki/articles/paradigma-logico---inversibilidad.html). En general alcanza con que los parámetros de nuestros predicados lleguen unificados al consultar not/1 y forall/2, lo cual se logra consultando un predicado inversible previamente en nuestra regla que se encargue de unificar esas variables.

Pueden encontrar el código de esta clase [acá](https://github.com/pdep-mit/ejemplos-de-clase-prolog/blob/master/clase2.pl)

## Para profundizar y ejercitar

- De la [sección de apuntes](http://www.pdep.com.ar/material/apuntes): Módulo 4 de Lógico hasta sección 4 inclusive.
- De Mumuki pueden trabajar con las guías de negación y cuantificación y además las de inversibilidad (no vimos cómo hacer cuentas hasta ahora, vale saltear los ejercicios que lo requieran).

[< Clase anterior](https://github.com/pdep-mit/bitacora-de-clase/blob/master/clase-11.md) - [Clase siguiente >](https://github.com/pdep-mit/bitacora-de-clase/blob/master/clase-13.md)
