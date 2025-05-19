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


## CLASE SEMANA 4

### 2.1. Notación para el "orden de"

La notación del “orden de” o notación asintótica permite describir el crecimiento del tiempo de ejecución o uso de memoria de un algoritmo según el tamaño de su entrada. Las funciones se expresan en términos de su comportamiento para valores grandes de n, ignorando constantes y términos de menor orden. Las notaciones más comunes son O (mayor o igual), Ω (menor o igual) y Θ (igual), que permiten comparar la eficiencia relativa entre algoritmos. Esta notación es esencial para clasificar algoritmos independientemente del lenguaje o hardware en que se ejecuten. Gracias a ella, es posible prever el rendimiento de soluciones ante entradas grandes.

![image](https://github.com/user-attachments/assets/4fa56cb0-034b-4612-a101-403d32dbb27c)


##  CLASE SEMANA 5

### 2.2. Notación Omega

La notación Ω (Omega) se usa para expresar una cota inferior del tiempo de ejecución de un algoritmo, es decir, el mínimo tiempo garantizado que tomará el algoritmo en función del tamaño de entrada n. Si un algoritmo pertenece a Ω(g(n)), significa que no puede ser más rápido que g(n) en el mejor de los casos. Es útil para determinar cuán rápido puede ejecutarse un algoritmo idealmente. Aunque menos usada que la notación O, es clave para entender el límite de eficiencia inferior. También permite evaluar si un algoritmo es óptimo comparado con la mejor solución posible.

![image](https://github.com/user-attachments/assets/097f991f-f81c-4252-ba50-013a841e590d)


### 2.3. Notación Theta

La notación Θ (Theta) representa una cota ajustada, indicando que una función de complejidad crece a la misma velocidad que g(n) tanto en el mejor como en el peor caso. Si un algoritmo es Θ(g(n)), entonces su eficiencia está completamente descrita por g(n), sin desviaciones significativas hacia arriba o abajo. Esta notación es especialmente útil cuando el comportamiento del algoritmo es consistente. Es más precisa que O o Ω por separado, ya que marca el crecimiento exacto. Por ello, es la preferida cuando se puede demostrar esa equivalencia fuerte.

![image](https://github.com/user-attachments/assets/775817ca-32ac-40de-880a-d5acf47f444d)


### 2.4. Notación asintótica condicional

La notación asintótica condicional se utiliza cuando el análisis depende de suposiciones específicas sobre las entradas o condiciones del algoritmo. A diferencia de las notaciones generales, aquí se considera que ciertas condiciones deben cumplirse para que la función de complejidad estimada sea válida. Por ejemplo, el rendimiento promedio puede depender de una distribución uniforme de los datos. Esta notación permite análisis más realistas o precisos, aunque menos generales. Es útil para algoritmos cuyo comportamiento varía significativamente según el caso.

![image](https://github.com/user-attachments/assets/ab559518-8b12-4f9e-8418-c8816458600d) 


##  CLASE SEMANA 5

### 3.1 Estructuras de control

Las estructuras de control son componentes esenciales en todo algoritmo, ya que definen el flujo lógico que sigue un conjunto de instrucciones para resolver un problema. Existen tres tipos principales: la estructura secuencial, donde las instrucciones se ejecutan en el orden en que están escritas; la estructura condicional o de decisión, que permite ejecutar ciertos bloques de código solo si se cumple una condición (por ejemplo, mediante sentencias if, else if y else); y la estructura repetitiva o iterativa, que permite ejecutar instrucciones múltiples veces, como en los bucles while, for o repeat-until. Estas estructuras posibilitan que un algoritmo se adapte a diferentes situaciones y datos de entrada. Gracias a ellas, se logra que los algoritmos no sean rígidos, sino dinámicos y eficientes. Además, permiten implementar soluciones complejas a partir de decisiones simples, mejorando la legibilidad y mantenimiento del código. El correcto uso de estas estructuras evita errores lógicos y redundancias. Son fundamentales tanto para la comprensión como para la construcción de algoritmos eficientes y reutilizables.

![image](https://github.com/user-attachments/assets/e1e4e482-a194-4a2a-9d3a-9afeee879457)

