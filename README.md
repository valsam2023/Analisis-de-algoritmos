# Analisis-de-algoritmos

TAREA RESUMEN DE LOS SIGUIENTES TEMAS 

## CLASE SEMANA 1

- Algoritmo:
Un algoritmo es una secuencia finita de pasos bien definidos que permiten resolver un problema específico. Su principal objetivo es transformar un conjunto de entradas en un conjunto de salidas de manera eficiente y precisa. Los algoritmos son fundamentales en la informática y en aplicaciones prácticas como el ordenamiento, la búsqueda, el cifrado y la optimización de recursos​.

![image](https://github.com/user-attachments/assets/7f64e68a-4cdd-45cb-babd-60201ff1be90)


- Algoritmia:
La algorítmica se refiere al estudio y diseño de algoritmos. Su importancia radica en optimizar el uso de recursos computacionales (tiempo y espacio). La algorítmica también se enfoca en el análisis de la eficiencia de los algoritmos, buscando mejorar su rendimiento para que puedan aplicarse de manera más efectiva en diversas áreas, como redes, análisis de datos y bioinformática​.

![image](https://github.com/user-attachments/assets/abdda994-3335-4ffc-baf4-6ca0908e225a)


- Tipos de Análisis:
El análisis de algoritmos es crucial para entender su comportamiento y eficiencia. Existen varios tipos de análisis:
Análisis en el mejor caso: Evalúa el rendimiento del algoritmo en la situación más favorable.
Análisis en el peor caso: Examina el peor escenario posible, donde el algoritmo tarda más tiempo en ejecutarse.
Análisis en el caso promedio: Calcula el tiempo promedio de ejecución bajo condiciones normales​.
Estos tres conceptos son fundamentales para entender cómo los algoritmos funcionan y cómo se pueden optimizar para mejorar su rendimiento en distintas aplicaciones.

![image](https://github.com/user-attachments/assets/58854b72-21c5-41b0-b0f2-0a674c6dbd44)


### .1. Algoritmia elementaL

Los algoritmos son procedimientos computacionales bien definidos que transforman entradas en salidas. Son fundamentales para resolver problemas en ciencias de la computación y tienen aplicaciones prácticas en áreas como búsqueda en internet, biología computacional, encriptación y rutas de navegación. Se consideran una tecnología tan importante como el hardware o los sistemas operativos. Un algoritmo se evalúa no solo por su corrección, sino también por su eficiencia, medida en tiempo y espacio. El análisis de algoritmos permite comparar distintas soluciones para un mismo problema y seleccionar la más óptima. Además, algunos algoritmos están diseñados para casos promedio, mientras que otros priorizan el peor caso. Estudiar algoritmos proporciona herramientas para resolver problemas no conocidos previamente.

### 1.1. Preliminares

Para diseñar y analizar algoritmos, se necesita una base matemática sólida. Esto incluye el entendimiento de funciones, sumatorias, conjuntos, relaciones y estructuras de datos básicas como listas y árboles. Los preliminares también abarcan temas como conteo, probabilidad y matrices, los cuales son esenciales para ciertos algoritmos. Esta preparación permite comprender la notación asintótica y los métodos de análisis de eficiencia. Las demostraciones matemáticas, especialmente por inducción, son comunes en la justificación formal de algoritmos. Esta sección proporciona un lenguaje común y herramientas teóricas para profundizar en capítulos posteriores.

### 1.1.1. Notación

La notación asintótica permite describir el comportamiento de algoritmos cuando el tamaño de entrada crece indefinidamente. Se usan símbolos para representar límites superior, exacto e inferior del tiempo de ejecución. Esto permite comparar algoritmos de forma abstracta, sin depender del lenguaje de programación o de la máquina utilizada. También se discuten otras funciones matemáticas frecuentes, como logaritmos y exponenciales. Esta notación es una herramienta clave para evaluar la escalabilidad y eficiencia.

### 1.1.2. Contradicción

El método de prueba por contradicción es una técnica lógica fundamental en matemáticas y algoritmia. Consiste en suponer que una afirmación es falsa y demostrar que esa suposición lleva a una contradicción lógica. Esto prueba que la afirmación original debe ser verdadera. Es muy utilizada en demostraciones de unicidad, imposibilidad o para validar propiedades de algoritmos. Este tipo de razonamiento es común cuando no se puede construir una prueba directa. También es una herramienta poderosa en teoría de números y análisis de estructuras algorítmicas.

### 1.1.3. Introducción matemática

Esta sección introduce los fundamentos matemáticos necesarios para el análisis riguroso de algoritmos. Se abordan pruebas formales, especialmente la inducción matemática, sumatorias, desigualdades y nociones básicas de teoría de conjuntos. También se exploran funciones comunes y propiedades algebraicas usadas para modelar y resolver problemas. La lógica matemática es clave para establecer propiedades de corrección y eficiencia. Esta base permite al lector entender demostraciones más avanzadas y formular soluciones propias con precisión.

### 1.1.4. Problemas

Los problemas en algoritmia plantean desafíos computacionales concretos que requieren modelarse adecuadamente para diseñar, analizar y seleccionar el algoritmo más eficiente

Ejemplo de problema:

Ordenar una lista de números de forma ascendente.

Entrada: [14, 13, 20, 16, 18]

Salida esperada: [13, 14, 16, 18, 20]

Este problema exige diseñar o seleccionar un algoritmo eficiente de ordenación, como inserción o merge sort

### Resolución usando el algoritmo de inserción (Insertion Sort):

Inicio con la lista:

[14, 13, 20, 16, 18]

Paso 1:
Comparo 13 con 14 → 13 es menor, así que lo inserto antes.

[13, 14, 20, 16, 18]

Paso 2:
Comparo 20 con 14 → 20 es mayor, no se mueve.

[13, 14, 20, 16, 18]

Paso 3:
Comparo 16 con 20 → 16 es menor, lo inserto antes de 20.

[13, 14, 16, 20, 18]

Paso 4:
Comparo 18 con 20 → 18 es menor, lo inserto antes de 20.

[13, 14, 16, 18, 20]  ordenada


## CLASE SEMANA 2

### 1.2. Eficiencia de los algoritmos

La eficiencia de un algoritmo se refiere a la relación entre los recursos consumidos (principalmente tiempo y memoria) y los resultados obtenidos. Un algoritmo eficiente debe minimizar el uso de estos recursos, especialmente cuando se trabaja con entradas de gran tamaño. Se analiza de manera empírica, midiendo tiempos de ejecución reales, y teóricamente, calculando funciones de complejidad. La elección de un algoritmo eficiente es crucial, ya que una mala elección puede hacer que un problema simple sea intratable en la práctica

![image](https://github.com/user-attachments/assets/95cd2b40-7ae4-4cd4-80fa-c1208fc676ef)


### 1.3. Caso medio

El análisis del caso medio evalúa el rendimiento promedio de un algoritmo considerando todas las entradas posibles bajo una distribución de probabilidad. A diferencia del peor caso, que solo contempla el escenario más desfavorable, el caso medio ofrece una visión más realista del comportamiento del algoritmo en la práctica. Sin embargo, calcularlo puede ser complicado si no se conoce la distribución exacta de las entradas. Este análisis es útil cuando los casos extremos son poco frecuentes y se busca eficiencia general​.

![image](https://github.com/user-attachments/assets/a2b8d4a0-e2f3-4151-ae06-09a0539a3629)


## CLASE SEMANA 3

### 1.4. Caso peor

El análisis del caso peor estudia el tiempo máximo que puede tardar un algoritmo considerando todas las entradas posibles. Este enfoque garantiza que el algoritmo no superará un cierto límite de tiempo, sin importar cuán desfavorable sea el escenario. Es fundamental en aplicaciones donde el rendimiento crítico debe asegurarse siempre, como en sistemas de tiempo real o financieros. Aunque puede ser más pesimista que el caso medio, proporciona una cota sólida de seguridad para la eficiencia.

![image](https://github.com/user-attachments/assets/3a556458-119e-48ac-a0d0-1cd9e1839cab)


### 1.5. Operación elemental

Una operación elemental es cualquier acción básica que realiza un algoritmo y que consume una cantidad constante de tiempo, como una suma, una asignación o una comparación. El conteo de operaciones elementales permite estimar el tiempo de ejecución en función del tamaño de entrada. En el análisis teórico, se asume que todas las operaciones básicas tienen el mismo costo, simplificando la medición de la eficiencia. Así se construyen funciones como T(n), donde n es el tamaño de la entrada​.

![image](https://github.com/user-attachments/assets/b78eb2f4-64b0-4a01-bd79-460416d6cb41)


## TALLER (Ejercicios en clase)

