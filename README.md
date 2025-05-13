Este programa en lenguaje C lee una matriz binaria (compuesta solo por ceros y unos) desde un archivo de texto, verifica que sea válida y calcula la secuencia más larga de 1s consecutivos en dirección diagonal (subiendo desde la esquina inferior derecha hasta la esquina superior izquierda, incluyendo continuidad entre diagonales). El programa primero valida que la matriz sea cuadrada, luego imprime su contenido y finalmente muestra el resultado encontrado. La función es_binario() asegura que los valores leídos en la matriz sean 0 o 1. La función leerMatrizDesdeArchivo() abre un archivo de texto para leer una matriz de tamaño arbitrario, validando que todos los valores sean binarios y que la matriz sea cuadrada. Para recorrer las diagonales de la matriz, la función encontrar_max_secuencia_diagonal_global() calcula la longitud máxima de secuencias de 1s consecutivos, usando una técnica de iteración sobre las diagonales de la matriz. Además, imprimirMatriz() se encarga de mostrar la matriz cargada en la consola para facilitar la verificación del contenido.

Para compilar y ejecutar el programa, se debe tener un archivo de entrada llamado "matriz.txt" (o cambiar el nombre en el código). A continuación se muestran tres ejemplos con distintas matrices.

Ejemplo 1

Archivo matriz1.txt:

1 0 1 0 0 1 1 1 1 1 0 1 0 1 1 1

Salida esperada:

Matriz leída desde el archivo: 1 0 1 0 0 1 1 1 1 1 0 1 0 1 1 1

La secuencia más larga de 1s consecutivos en dirección (↓↙) es: 4

Ejemplo 2

Archivo matriz2.txt:

0 1 0 0 1 1 1 0 0 1 1 1 0 0 1 0

Salida esperada:

Matriz leída desde el archivo: 0 1 0 0 1 1 1 0 0 1 1 1 0 0 1 0

La secuencia más larga de 1s consecutivos en dirección (↓↙) es: 3

Ejemplo 3

Archivo matriz3.txt:

1 1 0 0 1 1 1 0 1

Salida esperada:

Matriz leída desde el archivo: 1 1 0 0 1 1 1 0 1

La secuencia más larga de 1s consecutivos en dirección (↓↙) es: 2
