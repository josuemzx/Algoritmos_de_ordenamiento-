# Algoritmos de ordenamiento
Comparación del tiempo de procesamiento de Algoritmos de ordenamiento en Go, Python y C++.

Counting Sort, Merge Sort, Heap Sort y Quicksort


Conclusiones:

Para Counting Sort, se obtiene que el Tiempo de Procesamiento es menor en Goland, el costo
m´as alto en Python y la Desviaci´on Estandar es similar entre los lenguajes de programaci´on
C++ y Goland mientras que es mucho m´as alto en Python, lo que quiere decir que la dispersi´on
de datos es mayor en esta ´ultima.

Para Merge Sort se obtiene que el Tiempo de Procesamiento es menor en Goland, incluso menor
a C++, esto debido a que los programas en Go aprovechan mas f´acil el paralelismo disponible,
el tiempo fue mayor con Python. En cuanto a la Desviaci´on Estandar la dispersi´on es mayor en
Python y mucho menor en C++ y Goland.

Cada lenguaje hace optimizaciones diferentes por lo que no tardan lo mismo, es decir cuando
codificas en Python o Golang usando sus respectivas librerias realmente aprovechamos las optimizaciones 
que tienen en sus algoritmos internos para cada funcion, que pueden llamarse de la misma manera pero la 
implementacion optimiza algo del procesador.

C++ es el mas rapido en ejecutar codigo de maquina, pero el algoritmo puede hacer que incluso en
el caso de Python o Golan ejecutando mas instrucciones, el total de intrucciones ejecutadas para
procesar todo el conjunto de datos sea menor, aparentando ser mas rapido cuando solo es mas
eficiente, que es lo que sucedio en Golang nos dio menores tiempos al procesar los ordenamientos.


Para el Ordenamiento Rápido (QuickSort), se obtiene que el Tiempo de Procesamiento es menor
en el lenguaje Goland, y el costo más alto es el lenguaje C++. Y la Desviación Estandar es
similar entre los lenguajes de programación Python y Goland mientras que es mucho más alto
en el lenguaje C++, lo que quiere decir que la dispersión de datos es mayor en esta última. Y
esto puede suceder por tres razones, la primera razón es si se toma el peor caso, en donde el
pivote termina al extremo de la lista, por lo tanto el coste computacional sube a O (n2), la
segunda razón es la elección del pivote, esto quiere decir que si se toma a cualquier elemento
como pivote, dando así una elección a ciegas, donde siempre provoca que el algoritmo tenga un
orden de O (n2) y la tercera razón es la técnica de reposicionamiento en donde la idea principal
es ubicar los elementos menores y mayores al pivote, sin embargo se puede usar índices para
hacer el reposicionamiento de ambas sublistas simultáneamente.
