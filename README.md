# Analisis-de-algoritmos

TAREA RESUMEN DE LOS SIGUIENTES TEMAS 
## I BIMESTRE
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


##  CLASE SEMANA 6

### 3.1 Estructuras de control

Las estructuras de control son componentes esenciales en todo algoritmo, ya que definen el flujo lógico que sigue un conjunto de instrucciones para resolver un problema. Existen tres tipos principales: la estructura secuencial, donde las instrucciones se ejecutan en el orden en que están escritas; la estructura condicional o de decisión, que permite ejecutar ciertos bloques de código solo si se cumple una condición (por ejemplo, mediante sentencias if, else if y else); y la estructura repetitiva o iterativa, que permite ejecutar instrucciones múltiples veces, como en los bucles while, for o repeat-until. Estas estructuras posibilitan que un algoritmo se adapte a diferentes situaciones y datos de entrada. Gracias a ellas, se logra que los algoritmos no sean rígidos, sino dinámicos y eficientes. Además, permiten implementar soluciones complejas a partir de decisiones simples, mejorando la legibilidad y mantenimiento del código. El correcto uso de estas estructuras evita errores lógicos y redundancias. Son fundamentales tanto para la comprensión como para la construcción de algoritmos eficientes y reutilizables.

![image](https://github.com/user-attachments/assets/e1e4e482-a194-4a2a-9d3a-9afeee879457)


##  CLASE SEMANA 7

### 3.2. Análisis del caso medio

El análisis del caso medio estima el rendimiento promedio de un algoritmo considerando todas las posibles entradas bajo una distribución de probabilidad definida. A diferencia del caso peor, que examina el escenario más desfavorable, el caso medio ofrece una visión más realista del comportamiento habitual del algoritmo. Es útil para evaluar el desempeño práctico en situaciones típicas. Este análisis es más complejo, ya que depende de suposiciones sobre los datos. Sin embargo, proporciona una medida valiosa cuando se desea optimizar algoritmos para uso frecuente.

![image](https://github.com/user-attachments/assets/13fe7fd9-5ee0-4846-8aa5-d17313c54b40)


### 3.3. Análisis amortizado

El análisis amortizado permite evaluar el costo promedio por operación en una secuencia de operaciones, incluso si algunas son costosas individualmente. Se utiliza cuando ciertas operaciones ocasionales tienen un alto costo, pero su efecto se distribuye entre muchas operaciones baratas. Este análisis se aplica en estructuras como arreglos dinámicos, pilas con doble capacidad o tablas hash. Las técnicas comunes son el método agregado, el método contable y el método potencial. Es clave para demostrar eficiencia a largo plazo en algoritmos dinámicos o adaptativos.

![image](https://github.com/user-attachments/assets/a99c2565-275b-4c08-8250-102cafea3fd7)


### 3.4. Recurrencias

Las recurrencias son ecuaciones que expresan el tiempo de ejecución de algoritmos recursivos en función de su tamaño de entrada. Son fundamentales para analizar algoritmos que se dividen en subproblemas, como en el paradigma divide y vencerás. Se resuelven con métodos como la sustitución, el árbol de recurrencia y el teorema maestro. Permiten estimar con precisión el crecimiento de funciones complejas. Comprenderlas es esencial para determinar la eficiencia de algoritmos recursivos y predecir su comportamiento asintótico.

![image](https://github.com/user-attachments/assets/c0a9c541-f02b-4566-981d-2b5f16192e00)


## II BIMESTRE
## CLASE SEMANA 1

### 4. Algoritmos voraces

<img width="504" height="504" alt="image" src="https://github.com/user-attachments/assets/7eec16ac-d3db-4a28-ad7a-840725ef9219" />

### 4.1 Caracteristicas 

### Eficiencia
Son algoritmos rápidos y eficientes tanto en tiempo como en implementación.

### Simplicidad
Son fáciles de implementar debido a su estructura clara y directa.

### Heurística local
Se basan en una heurística que toma decisiones óptimas a corto plazo, sin preocuparse por las consecuencias globales.

### Aplicación a optimización
Son útiles para problemas de optimización, como encontrar el mínimo, máximo o mejor resultado posible bajo ciertas condiciones.

### No siempre garantizan la mejor solución
Aunque muchas veces encuentran buenas soluciones, no garantizan obtener la solución óptima global en todos los casos.

### No aplicables a todos los problemas
No todos los problemas pueden resolverse con un enfoque voraz, especialmente si la solución óptima global requiere considerar combinaciones más complejas.

### Dependen de la función de selección
El éxito de un algoritmo voraz depende de cómo se defina la función de selección, es decir, el criterio para elegir la mejor opción en cada paso.

### GRAFOS

<img width="355" height="235" alt="image" src="https://github.com/user-attachments/assets/6a92e5c9-0189-4e2d-a442-4338d2a8fc44" />

### ¿Qué es un grafo?
Un grafo es una estructura matemática usada para modelar relaciones entre objetos. Está compuesto por:
Un conjunto de vértices (nodos)
Un conjunto de aristas (o arcos) que representan conexiones entre pares de vértices

### Tipos de grafos
### 4.2 Grafos no dirigidos
Las aristas no tienen dirección, es decir, la conexión entre dos nodos es bidireccional.

Se representan como pares no ordenados: {u, v}

Se usan en problemas como:

Redes de comunicación

Sistemas eléctricos

Caminos de menor costo entre puntos

📌 Ejemplos de uso:
Redes de carreteras de doble vía

Redes eléctricas

Redes sociales (cuando la relación es mutua)

Sistemas de comunicación entre computadoras

📌 Aplicaciones:
Construcción de árboles de recubrimiento mínimo usando algoritmos como Kruskal o Prim

Determinación de componentes conexas

Detección de ciclos o caminos simples

<img width="285" height="281" alt="image" src="https://github.com/user-attachments/assets/027d7eff-3fdd-4e59-8d48-3a32b153eab2" />

### Árbol de recubrimiento mínimo (MST)

Es un subconjunto de aristas que conecta todos los vértices del grafo sin ciclos y con el menor costo total posible.

El costo total se calcula como la suma de los pesos de las aristas del árbol.

Solo aplica a grafos no dirigidos, conectados y ponderados.

📌 Aplicaciones:
Planeamiento de redes eléctricas, telecomunicaciones, rutas de distribución, etc.

<img width="300" height="242" alt="image" src="https://github.com/user-attachments/assets/aa244349-e88f-4032-af91-1fd2aa1a6bed" />

### Problemas clásicos en grafos vistos en la unidad
Problema del árbol de recubrimiento mínimo

Algoritmos: Kruskal, Prim

Objetivo: conectar todos los nodos al menor costo sin formar ciclos

Problema de caminos mínimos

Algoritmo: Dijkstra

Objetivo: encontrar el camino más corto desde un nodo fuente a los demás

🔹 Algoritmos voraces aplicados a grafos
Kruskal y Prim son algoritmos voraces que resuelven el problema del árbol de recubrimiento mínimo

Dijkstra es un algoritmo voraz que encuentra caminos más cortos en grafos dirigidos y ponderados (no incluido en detalle en estas diapositivas, pero está relacionado)

### CLASE SEMANA 2
### 4.3 Grafos dirigidos
📌 Definición:
Un grafo dirigido (también llamado digráfo) es aquel en el que cada arista tiene una dirección, es decir, conecta un nodo de origen con un nodo de destino.

Se representa como 

𝐺 = (𝑉,𝐴), donde:

V es el conjunto de vértices

𝐴 ⊆ 𝑉 × 𝑉 es el conjunto de arcos dirigidos

Cada arco se denota como:

(𝑢,𝑣) donde 𝑢 → 𝑣

Esto indica que se puede ir de u a v, pero no necesariamente de v a u.

📌 Propiedades:

Los arcos tienen sentido de dirección

No necesariamente es simétrico: puede existir (u, v) sin que exista (v, u)

Son ideales para representar relaciones unidireccionales

📌 Ejemplos de uso:

Flujos de tráfico en calles de un solo sentido

Procesos o tareas que dependen unas de otras (gráficos de precedencia)

Representación de redes de datos (paquetes que solo van en un sentido)

Diagramas de flujo, autómatas, redes de dependencias

📌 Aplicaciones:

Algoritmos de caminos más cortos como Dijkstra y Bellman-Ford

Análisis de componentes fuertemente conexas

Detección de ciclos y ordenamientos topológicos

Representación de jerarquías y relaciones asimétricas

<img width="285" height="281" alt="image" src="https://github.com/user-attachments/assets/5130661b-05c2-4135-84fd-d3593d259f3d" />

<img width="883" height="427" alt="image" src="https://github.com/user-attachments/assets/f2d1aebc-2241-415a-834e-d7f53721a1fd" />


### CLASE SEMANA 3
### 5. Algoritmos Divide y Vencerás

¿Qué es la estrategia divide y vencerás?

Divide y vencerás es una técnica de diseño algorítmico que consiste en resolver un problema complejo dividiéndolo en subproblemas más simples, resolviendo recursivamente esos subproblemas y luego combinando las soluciones para obtener el resultado final.

📌 Etapas del enfoque

Dividir el problema en partes más pequeñas del mismo tipo.

Resolver cada subproblema (generalmente de forma recursiva).

Combinar las soluciones parciales para construir la solución del problema original.

Características 

Se basa en recursión.

Cada división reduce el tamaño del problema original, lo que permite alcanzar un caso base simple.

La eficiencia depende del número de divisiones y del costo de combinar resultados.

Es aplicable cuando un problema puede partirse en subproblemas independientes.

💡 Ventajas
Favorece la eficiencia y claridad en la solución.

En muchos casos mejora la complejidad algorítmica (por ejemplo, de O(n^2) a O(n log n)).

Permite resolver problemas grandes con soluciones estructuradas y repetibles.

<img width="912" height="509" alt="image" src="https://github.com/user-attachments/assets/482e9a57-2c9b-4379-aedc-50bf8c545dd4" />

Aplicaciones comunes

Ordenamiento eficiente de datos

Búsqueda optimizada en estructuras ordenadas

Procesamiento de imágenes y señales

Algoritmos numéricos (matrices, exponenciación, etc.)

Análisis estructural de datos grandes

Ejemplo: Merge Sort

Dado el arreglo:
[54, 26, 93, 17, 77, 31, 44, 55, 20]

División:
→ [54, 26, 93, 17] y [77, 31, 44, 55, 20]

Resolución recursiva:
→ [17, 26, 54, 93] y [20, 31, 44, 55, 77]

Combinación final:
→ [17, 20, 26, 31, 44, 54, 55, 77, 93]


### 5.1 Búsqueda binaria
Definición general
La búsqueda binaria es un algoritmo basado en la técnica divide y vencerás, utilizado para buscar un elemento en un arreglo ordenado. En cada paso, compara el elemento a buscar con el elemento medio del arreglo y descarta la mitad donde no puede estar el valor.

Representación de la condición de búsqueda:

El algoritmo busca una posición i tal que:

1 ≤ 𝑖 ≤ 𝑛 + 1

𝑇[𝑖 − 1]  < 𝑥 ≤ 𝑇 [𝑖]

Esto indica que el valor buscado x está entre dos elementos consecutivos del arreglo T, y que la búsqueda se basa en comparar contra esos extremos.

Complejidad del algoritmo
Las diapositivas indican que la búsqueda binaria tiene una eficiencia de:

Θ(log 𝑚)

Esto significa que el tiempo de ejecución crece logarítmicamente con el tamaño del arreglo. Es decir, a medida que el tamaño del arreglo se duplica, solo se agrega una comparación adicional al proceso.

Comparación implícita 
A diferencia de un algoritmo de búsqueda lineal (cuya complejidad es Θ (𝑛)), la búsqueda binaria es mucho más eficiente en arreglos grandes, ya que reduce a la mitad el espacio de búsqueda en cada paso.

Este comportamiento es posible solo si el arreglo está ordenado previamente.

Requisitos importantes

El arreglo debe estar ordenado.
Si no lo está, no se cumple y el algoritmo produce resultados incorrectos.

<img width="323" height="331" alt="image" src="https://github.com/user-attachments/assets/f52a94ba-33c5-4914-839e-fb19a21d4c4f" />


### CLASE SEMANA 4
### 5.2 Ordenación 

La ordenación por fusión o Merge Sort es un algoritmo de ordenamiento que utiliza la estrategia de divide y vencerás. Consiste en dividir el arreglo en partes más pequeñas, ordenarlas y luego fusionarlas en un solo arreglo ordenado.

Funcionamiento

Se divide el arreglo original en dos mitades.

Se aplican llamadas recursivas a OrdenarPorFusion sobre cada mitad.

Se fusionan las mitades ordenadas en un solo arreglo final.

Ejemplo mostrado en las diapositivas

Arreglo original:

54 26 93 17 77 31 44 55 20

Proceso:

Dividir: [54 26 93 17] y [77 31 44 55 20]

Ordenar recursivamente:

[54 26 93 17] → [17 26 54 93]

[77 31 44 55 20] → [20 31 44 55 77]

Fusionar:

Resultado final: [17 20 26 31 44 54 55 77 93]

📐 Complejidad
El algoritmo tiene la siguiente función de recurrencia:

<img width="367" height="97" alt="image" src="https://github.com/user-attachments/assets/ab464104-fec1-4cc1-917c-95f9bdc18bdb" />

Donde:

Separar el arreglo en dos mitades toma tiempo lineal.

Fusionar dos mitades ordenadas también toma tiempo lineal.

Por tanto, el tiempo de ejecución total es: 𝑡(𝑛) ∈ Θ(𝑛 log 𝑛)


### CLASE SEMANA 5
### 5.3 Mediana

La búsqueda de la mediana es un problema que puede abordarse con la estrategia de divide y vencerás, similar a los algoritmos de ordenación y búsqueda vistos previamente.

¿Qué es la mediana?

La mediana es el elemento que ocupa la posición central de un conjunto ordenado de datos. Si el número de elementos es impar, la mediana es el valor del medio. Si es par, se puede tomar el promedio de los dos valores centrales (aunque esta parte no se detalla en las diapositivas).

Enfoque general mostrado en las diapositivas

Se busca dividir el conjunto en subconjuntos para localizar eficientemente el elemento que corresponde a la posición mediana.

Esto se puede hacer mediante una estrategia de partición, similar a la usada en QuickSort, donde se elige un pivote para separar el conjunto en menores y mayores.

Relación con divide y vencerás

La búsqueda de la mediana se puede resolver más eficientemente si se aplican técnicas de división del conjunto, permitiendo reducir el problema a un subconjunto más pequeño que contenga la posición deseada.

Complejidad

Aunque no se presenta una fórmula explícita en las diapositivas, el uso de divide y vencerás para encontrar la mediana puede llevar a una complejidad mejor que ordenar completamente el arreglo, especialmente si no se requiere la lista ordenada completa.

Aplicación

El algoritmo es útil cuando se necesita:

Conocer el valor central sin ordenar todos los elementos

Seleccionar el k-ésimo menor en un conjunto (mediana es el caso particular con 𝑘 = 𝑛/2)

### 5.4. Multiplicación de matrices

La multiplicación de matrices es una operación fundamental en álgebra lineal y se puede optimizar utilizando la técnica de divide y vencerás, especialmente para grandes matrices.

Definición de la multiplicación de matrices

Para dos matrices 𝐴 y 𝐵, el producto 𝐶 = 𝐴 × 𝐵 se define como:

<img width="244" height="86" alt="image" src="https://github.com/user-attachments/assets/cb9a3aca-bd25-43db-947d-c0075820af18" />

Donde 𝐶 𝑖,𝑗 representa el elemento en la fila 𝑖 y columna 𝑗 de la matriz resultante.

Esta operación tiene complejidad clásica de:

Θ(n^3)

Técnica divide y vencerás

Las diapositivas muestran cómo se puede aplicar la técnica de divide y vencerás a la multiplicación de matrices, dividiendo las matrices grandes en submatrices más pequeñas. Esta técnica permite mejorar la eficiencia, especialmente cuando se usa el algoritmo de Strassen.

Algoritmo de Strassen

Se basa en dividir las matrices en submatrices de tamaño 𝑛/2 × 𝑛/2.

En lugar de realizar 8 multiplicaciones como en el método clásico, Strassen logra realizar la operación usando solo 7 multiplicaciones.

Esto reduce la complejidad y mejora el rendimiento para matrices de gran tamaño.

<img width="1067" height="207" alt="image" src="https://github.com/user-attachments/assets/1ab9bcd7-4963-4c3e-8e1f-0f0e388bac24" />


### CLASE SEMANA 6
### 6. Algoritmos probabilistas

¿Qué son?

Los algoritmos probabilistas son aquellos que incorporan aleatoriedad en su proceso de decisión. A diferencia de los algoritmos deterministas (que siempre producen la misma salida para una entrada dada), los algoritmos probabilistas pueden producir resultados distintos en diferentes ejecuciones, aun usando la misma entrada.

Motivación 

Se plantea una situación con múltiples opciones de acción y resultados inciertos.

Elegir aleatoriamente (por ejemplo, lanzando una moneda) puede generar mejores resultados esperados que una decisión determinista.

Ejemplo:

Si eliges aleatoriamente entre dos caminos para encontrar un tesoro, puedes obtener un beneficio promedio mejor que esperando una respuesta segura o aceptando un trato desfavorable.

Valor esperado: 
𝑥 −7.5𝑦

Características clave

Decisiones aleatorias:

El algoritmo puede usar azar para elegir entre diferentes acciones.

No siempre analiza todas las opciones posibles.

Variabilidad en la solución:

Una misma entrada puede generar soluciones distintas en distintas ejecuciones.

Tolerancia al error:

Puede dar resultados incorrectos, siempre que la probabilidad de error sea pequeña.

Permite repetir la ejecución:

Si el resultado no es satisfactorio, el algoritmo puede reiniciarse para obtener otra solución.

Evaluación más compleja:

El análisis del tiempo de ejecución y de la corrección es más difícil que en los algoritmos deterministas.

<img width="882" height="336" alt="image" src="https://github.com/user-attachments/assets/cd1a22cb-582d-4622-89d0-1b43d6cd443e" />

### 6.1. Tiempo esperado

¿Qué es el tiempo esperado?

El tiempo esperado es una medida del rendimiento de un algoritmo probabilista. Representa el tiempo medio que tarda un algoritmo en ejecutarse sobre una entrada fija, considerando todas las decisiones aleatorias que el algoritmo puede tomar durante su ejecución.

<img width="976" height="419" alt="image" src="https://github.com/user-attachments/assets/c33c5265-7641-41e8-b696-81c8a7bf0042" />

Interpretación

En un algoritmo determinista, el análisis de eficiencia se basa en todas las posibles entradas del mismo tamaño.

En un algoritmo probabilista, el análisis se basa en una entrada específica, pero promedia sobre las decisiones aleatorias que pueden ocurrir durante la ejecución.

Aplicación 

Se usa para:

Evaluar el rendimiento esperado de algoritmos aleatorizados.

Analizar algoritmos que tienen varias ejecuciones posibles incluso con los mismos datos de entrada.

Estimar cuánto tarda, en promedio, un algoritmo en producir una respuesta cuando toma decisiones al azar.

Algo importante

El tiempo esperado no garantiza el peor caso, pero sí proporciona una expectativa razonable del comportamiento del algoritmo.

Se puede usar junto con técnicas como la repetición para aumentar la confiabilidad del resultado (si el algoritmo tiene probabilidad de fallar o no terminar).

### 6.2. Algoritmos numéricos

¿Qué son?

Los algoritmos numéricos son aquellos que se usan para resolver problemas matemáticos que requieren cálculos con números reales o enteros, y muchas veces son utilizados en contextos como simulaciones, estadísticas, y análisis numérico. En el contexto de los algoritmos probabilistas, estos algoritmos hacen uso de valores aleatorios generados computacionalmente para representar situaciones reales.

Generación de números pseudoaleatorios

Los algoritmos numéricos probabilistas dependen de la generación de números pseudoaleatorios, que no son completamente aleatorios, sino generados mediante fórmulas deterministas.

Método más común: Generador lineal congruencial

Este generador produce una secuencia de números pseudoaleatorios a partir de una fórmula:

<img width="325" height="51" alt="image" src="https://github.com/user-attachments/assets/e023a9e7-94b2-4e46-a5b7-8320df7effd0" />

Donde:

𝑋0 es la semilla (valor inicial),

𝑎, 𝑐, y 𝑚son constantes enteras que definen el comportamiento del generador.

Si se eligen bien estos parámetros, el generador puede producir secuencias largas sin repetición aparente.

Propósito

Los números pseudoaleatorios se usan para:

Simulaciones de procesos aleatorios (por ejemplo, lanzamiento de dados, comportamiento del clima).

Pruebas estadísticas.

Algoritmos de Monte Carlo.

Juegos, gráficas y entornos virtuales.

Importante
Aunque son generados de forma determinista, simulan el comportamiento aleatorio de manera suficientemente buena para muchos propósitos.

No deben usarse en contextos que requieren seguridad criptográfica (para eso se usan generadores criptográficamente seguros, que no se tratan en estas diapositivas).


### CLASE SEMANA 7
### 6.3. Algoritmos de Monte Carlo

¿Qué son?

Los algoritmos de Monte Carlo son una clase de algoritmos probabilistas que hacen uso de números aleatorios para obtener una solución aproximada a un problema. Pueden fallar con baja probabilidad, pero ofrecen una respuesta rápida y útil en la mayoría de los casos.

Características principales

Pueden equivocarse

La solución que entregan puede no ser la correcta, pero hay una alta probabilidad de que sí lo sea.

Control del error

La probabilidad de error se puede hacer tan pequeña como se desee repitiendo el algoritmo varias veces.

No garantiza exactitud al 100%, pero:

Proporciona soluciones rápidas.

Son útiles cuando un algoritmo determinista sería muy costoso o complejo.

Basado en simulación aleatoria

Los resultados se generan a partir de ensayos repetidos con valores pseudoaleatorios, lo que permite estimar un valor o tomar una decisión.

Ejemplos comunes:

Estimación del valor de π:

Se simulan lanzamientos aleatorios de puntos en un cuadrado y se mide cuántos caen dentro de un círculo inscrito.

Integración numérica

Resolución de problemas combinatorios complejos, como conteo de caminos o estimaciones estadísticas.

¿Por qué usar Monte Carlo?

Son útiles cuando:

No se conoce una solución exacta.

El cálculo determinista es muy costoso.

Se permite un margen de error pequeño.

<img width="512" height="205" alt="image" src="https://github.com/user-attachments/assets/e7a219b2-195a-4057-a7bb-74b788796518" />


### CLASE SEMANA 8

Tuvimos clase vimos muchos ejemplos como por ejemplo este:

<img width="1336" height="554" alt="image" src="https://github.com/user-attachments/assets/d03bf5a0-dbc2-4a31-8644-a0ef6ee43d38" />

y nos mando a subir todo los talleresy deberes de la materia, que están subidos en este mismo repositorio en la carpeta TALLERES Segundo Bimestre.
