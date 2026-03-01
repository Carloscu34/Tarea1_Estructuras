<img width="1079" height="317" alt="Captura de pantalla 2026-02-28 205712" src="https://github.com/user-attachments/assets/1e6d9a8b-c730-4fa0-8f14-d1ebe35afb8f" />
ANÁLISIS DE COMPLEJIDAD TEÓRICA
ARREGLO ORDENADO: el proceso de ordenamiento tiene una complejidad de O(n log n) esto significa que el tiempo de ordenamiento crece de manera proporcional a n log n conforme aumenta la cantidad de elementos.
La busqueda binaria funciona dividiendo el conjunto de datos a la mitad en cada paso, reduciendo progresivamente el espacio de búsqueda.
Para el caso de 10,000,000: log2(10,000,000)≈23.

TABLA HASH: la tabla hash utiliza una función hash para calcular directamente la posición donde debe encontrarse un elemento. Gracias a esto no es necesario recorrer ni dividir el conjunto de datos.
O(1) esto significa que el tiempo de búsqueda es constante y no depende directamente del numero de elementos almacenados.


Por lo tanto, la tabla hash es más eficiente en términos de tiempo de búsqueda, especialmente cuando el volumen de datos es muy grande.
