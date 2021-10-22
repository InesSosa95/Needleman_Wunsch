# Needleman Wunsch
Implementación del algoritmo Needleman Wunsch.

Consideraciones:

 - La función `nw` utiliza los parámetros enumerados en el enunciado
 - La función `parseNucleotide(aNucleotide)` retorna el valor de la posición en la matriz `score_mtx`  para cada uno de los posibles valores para un nucleótido.
 - Ninguna de las funciones tiene *handling* para errores, Si se intenta procesa una cadena invalida, se rompe.
 - Contiene errores
 - La función `traceback()` tiene un costo muy elevado 

## Ejemplo de prueba

    nw('TATA', 'TCT', score_mtx, 0)
