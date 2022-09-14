# Algoritmos2_tp_pila
El trabajo a realizar es el de una implementación de pila dinámica que contenga datos genéricos.

Las pruebas deberán verificar que:

Se pueda crear una Pila vacía, y esta se comporta como tal.
Se puedan apilar elementos, que al desapilarlos se mantenga el invariante de pila (que esta es LIFO). Probar con elementos diferentes, y ver que salgan en el orden deseado.

Prueba de volumen: Se pueden apilar muchos elementos (1000, 10000 elementos, o el volumen que corresponda): hacer crecer la pila, y desapilar elementos hasta que esté vacía, comprobando que siempre cumpla el invariante. Recordar no apilar siempre lo mismo, validar que se cumpla siempre que el tope de la pila sea el correcto paso a paso, y que el nuevo tope después de cada desapilar también sea el correcto.

Condición de borde: comprobar que al desapilar hasta que está vacía hace que la pila se comporte como recién creada.

Condición de borde: las acciones de desapilar y ver_tope en una pila recién creada son inválidas.

Condición de borde: la acción de esta_vacía en una pila recién creada es verdadero.

Condición de borde: las acciones de desapilar y ver_tope en una pila a la que se le apiló y desapiló hasta estar vacía son inválidas.

Probar apilar diferentes tipos de datos: probar con una pila de enteros, con una pila de cadenas,etc…
