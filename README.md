# card-number-verification
Se requiere crear una API REST que calcule el dígito verificador del DNI peruano. Utilizar para ello Java Spring Boot y aplicar conocimientos de arquitectura de software, programación funcional y reactiva (deseable).

La instrucción 7 estaba con trampa:
Al resultado anterior le sumamos 1, es decir 4 + 1 = 5 lo que significa que vamos a buscar la 5ta posición en la serie NUMERICA (por defecto) 6, 7, 8, 9, 0, 1, 1, 2, 3, 4, 5 ó la 5ta posición en la serie ALFABÉTICA (por defecto) K, A, B, C, D, E, F, G, H, I, J.
