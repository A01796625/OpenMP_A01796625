# OpenMP_A01796625

En este ejercicio se busca comparar la forma secuencial vs paralela de resolver un problema muy común: sumar dos arreglos A y B para obtener un tercer arreglo C, donde cada posición cumple:

C[i]=A[i]+B[i]C[i] = A[i] + B[i]C[i]=A[i]+B[i] 

Cuando el tamaño del arreglo es pequeño (como 10 elementos) el tiempo es prácticamente inmediato. Pero si los arreglos tienen miles o millones de elementos, la suma secuencial (uno por uno) puede tardar más.
La idea de la programación paralela es repartir el trabajo: que varios hilos (threads) calculen partes distintas del arreglo al mismo tiempo, aprovechando los procesadores multinúcleo.
