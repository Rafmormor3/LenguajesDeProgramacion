# Lenguajes de Programacion
---
## ¿Qué son los Lenguajes de Programación?
Los _Lenguajes de Programación_ , simplemente, sonel conjunto de instrucciones que le proporcionamos a un ordenador para interactuar con ellos.
Los lenguajes de programación permiten a las computadoras procesar de forma rápida y eficientemente grandes y complejas cantidades de información.

Como por ejemplo, si le dieramos una gran lista de números aleatorios, gracias a los _Lenguajes de Programación_, podríamos ordenarla en cuestión de segundo, en cambio si lo hicieramos nosotros mismos nos llevaria más tiempo. 

![][imagen1]

---
Aunque existan múltiples _Lenguajes de Programación_, nosotros le vamos a mostrar y explicar los diferentes tipos atendiendo a la clasificación por **nivel de abstracción**, **forma de ejecucuión** y **paradigma:**

# -Nivel de Abstracción:

Es aquel nivel donde la computadora solo entiende **Código Binario**, es decir, con ceros y unos para interpretar una instrucción.

Podemos diferenciar 3 niveles:

## -Bajo Nivel:

Lenguaje que entiende directamente la computadora, por lo tanto, se utiliza solo 0 y 1. Las instrucciones son ejercidas directamente al hardware.

Entre ellos tenemos:

* **LENGUAJE DE MÁQUINA:** instrucciones formada por 0 y 1 que se ejecuta directamente en la _CPU_.

* **LENGUAJE ENSAMBLADOR:** deriva del lenguaje de máquina, sin embargo, utiliza letras y números para las instrucciones.


## -Medio Nivel:

Es aquel que permite una mayor abtracción, pero mantiene algunas características originales del nivel bajo. El lenguaje es mandado a un compilador que lo convierte a lenguaje de máquina.

En este nivel tenemos como ejemplo principal:

* **LENGUAJE _C_:** este puede acceder a registros del sistema y direcciones de memoria, todas propias de lenguajes de bajo nivel.


## -Alto Nivel:

Se caracterizan porque su estructura semántica es muy similar a la forma como escriben los humanos, lo que permite codificar los algoritmos de manera más natural, en lugar de codificarlos en el lenguaje binario de las máquinas, o a nivel de lenguaje ensamblador.

Algunos ejemplos de Lenguaje de Programación de Alto Nivel podría, ser:

* **JAVA:** es un lenguaje de programación orientado a objetos que es muy utilizado para el desarrollo de aplicaciones.

* **FORTRAN:** es un lenguaje de programación que está orientado y adaptado para aplicaciones numéricas y computación científica.

* **PYTHON:** es un lenguaje de programación de alto nivel, orientado a objetos, con una semántica dinámica integrada, principalmente para el desarrollo web y de aplicaciones informáticas.

---

# -Forma de Ejecución:

Los procesadores de los ordenadores son capaces de entender y actuar según lo indican programas escritos en lenguaje de máquina.

Todo programa puede ser ejecutado de 3 maneras:

## -Compilado:

Antes de poder utilizarse el programa debe utilizarse un traductor llamado **"Compilador"** que se encarga de traducir el programa original al programa equivalente ecrito en lenguaje de máquina.

Algunos ejemplos de **_Lenguajes Compilados_**:

* **HASKELL:** Los programas escritos en Haskell se representan siempre como funciones matemáticas, pero estas funciones nunca tienen efectos secundarios ni derivados.

* **C++:** es un lenguaje de programación que proviene de la extensión del lenguaje C para que pudiese manipular objetos.

* **COBOL:** un lenguaje de programación basado en el idioma inglés que lleva más de medio siglo sustentando todo tipo de operaciones como sistemas financieros, por ejemplo.


## -Interpretado:

Es aquel que el código fuente se ejecuta directamente, instrucción a instrucción, es decir, que el código no pasa por un proceso de compilación, sino que tenemos un programa llamado **intérprete** que lee la instrucción en tiempo real, y la ejecuta.

Como ejemplo de **_Lenguajes Interpretados_** tenemos:

* **MATLAB:** es un sistema de cómputo numérico que ofrece un entorno de desarrollo integrado con un lenguaje de programación propio.

* **PHP:** es un lenguaje de programación destinado a desarrollar aplicaciones para la web y crear páginas web, favoreciendo la conexión entre los servidores y la interfaz de usuario.


## -Virtuales:

Son lenguajes más portables que los lenguajes compilados puesto que el código que se genera tras la compilación es un código intermedio o bytecode. Este código puede ser a su vez interpretado por una máquina virtual instalada en cualquier equipo. 

El ejemplo de los **_Lenguajes Virtuales_** son:

* **JAVA** (anteriormente explicado)

---

# -Paradigma:

Un paradigma de programación es un estilo de programación de software. Se trata de un conjunto de métodos sistemáticos aplicables en todos los niveles del diseño de programas. Existen diferentes formas de diseñar un lenguaje de programación y varios modos de trabajar para obtener los resultados que necesitan los programadores.

Los lenguajes de programación adoptan uno o varios paradigmas en función del tipo de órdenes dadas para solucionar ese problema, incluso pueden ser multiparadigmas, como Python.

Existen 6 tipos de paradigmas:

## -Paradigmas Imperativos:

Consiste en ordenes concretas dadas por el programador para el correcto funcionamiento del programa.

El **paradigma imperativo** tambien tiene otros enfoques subordinados a este:

* **Programacion Estructurada:** el flujo de control es definido por condicionales y bucles.

* **Programacion Modular:** este tipo de lenguaje es utilizado para solucionar problemas mas complejos, dividiendo el programa en modulos para hacerlo mas manejable.

Entre los principales lenguajes que utilizan este paradigma nos encontramos a COBOL, C, C++.

## -Paradigmas Declarativos:

Este paradigma no definie algoritmos puesto que describe el problema en lugar de encontrar una solución al mismo. Utiliza el principio del razonamiento lógico para responder a preguntas o cuestiones consultadas.

Este paradigma, además se divide en dos:

* **Programación Lógica:** Prolog
* **Programación funcional:** Lisp, Scala, Java, Kotlin

## -Paradigmas Procedimentales:

Este tipo de paradigma se enfoca mas en una programacion logica y funcional, basandose en repetir en menor numero de expresiones, englobarlas en funciones y con llamada a estas en caso de ejecución.

## -Programacion orientada a objetos:

En este modelo de paradigma se construyen modelos de objetos que representan elementos del problema a resolver, que tienen características y funciones. Puede separar los componentes de un programa por lo que simplifica todos sus procesos, además disminuye los errores. Podemos definir un objeto como una estructura abstracta que, de manera más fiable, describe un posible objeto del mundo real y su relación con el resto del mundo que lo rodea a través de interfaces.

Ejemplos de lenguajes de programación orientados a objetos serían Java, Python o C#.

## -Paradigma lógico 

Este paradigma se basa en los conceptos de lógica matemática, se basa predicados que caracterizan o relacionan a los individuos involucrados y la deducción de las posibles respuestas a una determinada consulta.

## -Paradigma funcional

Se basa en un conjunto de funciones que pueden ser evaluadas para obtener un resultado. El paradigma funcional está basado en conceptos matematicos.
El resultado de este tipo de paradigma se obtiene sustituyendo esos argumentos en el cuerpo de la función respetando el nombre que se les dio a cada uno.











[imagen1]:https://piperlab.es/wp-content/uploads/2020/09/lenguajes-de-programacion.jpg
