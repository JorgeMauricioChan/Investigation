# //Investigation//
*Algoritmos*. //Definición//

Un algoritmo se puede definir como una secuencia de instrucciones que representan un modelo de solución para determinado tipo de problemas. O bien como un conjunto de instrucciones que realizadas en orden conducen a obtener la solución de un problema.

Para realizar un programa es conveniente el diseño o definición previa del algoritmo. El diseño de algoritmos requiere creatividad y conocimientos profundos de la técnica de programación. 

Loa algoritmos son independientes de los lenguajes de programación. En cada problema el algoritmo puede escribirse y luego ejecutarse en un lenguaje diferente de programación. El algoritmo es la infraestructura de cualquier solución, escrita luego en cualquier lenguaje de programación.

Características de los algoritmos

•	Preciso. Definirse de manera  rigurosa, sin dar lugar a ambigüedades.
•	Definido. Si se sigue un algoritmo dos veces, se obtendrá el mismo resultado.
•	Finito. Debe terminar en algún momento.
•	Puede tener cero o más elementos de entrada.
•	Debe producir un resultado. Los datos de salida serán los resultados de efectuar las instrucciones.

Se concluye que un algoritmo debe ser suficiente para resolver el problema. Entre dos algoritmos que lleven a un mismo objetivo, siempre será preferible el más corto (se deberá analizar la optimización de tiempos y / o recursos).

Etapas para la solución de un problema por medio del computador

1.	Análisis del problema, definición y delimitación (macroalgoritmo). Considerar los datos de entrada, el proceso que debe realizar el computador y los datos de salida.
2.	Diseño y desarrollo del algoritmo (se utiliza pseudocódigo, escritura natural del algoritmo, diagramas de flujo, etc. )
3.	Prueba de escritorio. Seguimiento manual de los pasos descritos en el algoritmo. Se hace con valores bajos y tiene como fin detectar errores.
4.	Codificación. Selección de un lenguaje de programación y digitación del pseudocódigo haciendo uso de la sintaxis y estructura gramatical del lenguaje seleccionado.
 
5.	Compilación o interpretación del programa. El software elegido convierte las instrucciones escritas en el lenguaje a las comprendidas por el computador.
6.	Ejecución. El programa es ejecutado por la máquina para llegar a los resultados esperados.
7.	Depuración (debug). Operación de detectar, localizar y eliminar errores de mal funcionamiento del programa.
8.	Evaluación de resultados. Obtenidos los resultados se los evalúa para verificar si son correctos. (Un programa puede arrojar resultados incorrectos aún cuando su ejecución no muestra erorres).

Algoritmos cualitativos y algoritmos cuantitativos

Un algoritmo es cualitativo cuando en sus pasos o instrucciones no están involucrados cálculos numéricos. Las instrucciones para armar un aeromodelo, para desarrollar una actividad física o encontrar un tesoro, son ejemplos de algoritmos cualitativos.

Trate de diseñar el algoritmo para estos casos

•	Tomar mate
•	Utilizar una guía telefónica
•	Cocinar siguiendo una receta
•	Cambiar una llanta de automóvil
•	Buscar una palabra en el diccionario

Los algoritmos cuantitativos involucran cálculos numéricos. Ejemplos:
•	Solución de un factorial
•	Solución de una ecuación de segundo grado
•	Encontrar el mínimo común multiplicador.

Técnicas de representación

Para la representación de un algoritmo, antes de ser convertido a lenguaje de programación, se utilizan algunos métodos de representación escrita, gráfica o matemática. Los métodos más conocidos son:

•	Diagramación libre (Diagramas de flujo)
•	Diagramas Nassi-Shneiderman
•	Pseudocódigo
•	Lenguaje natural (español, inglés, etc.)
•	Fórmulas matemáticas

El lenguaje natural puede no ser suficientemente preciso, permitiendo ambigüedades, obteniendo una descripción no del todo satisfactoria. Las fórmulas, propias del lenguaje matemático, son un buen sistema de
 
representación, pero no suelen ser fáciles de convertir en programas. Por lo tanto, trataremos en este curso los tres primeros modelos.

Diagramas de flujo.

Es quizás la forma de representación más antigua. Algunos autores suelen llamarlos también como diagramas de lógica o flujogramas.



















*Pseudocódigo*


Es la técnica que permite expresar la solución de un problema mediante un algoritmo escrito en palabras normales de un idioma (por ejemplo, el español), utilizando palabras imperativas. Es común encontrar en pseudocódigo palabras como: Inicie, lea, imprima, sume, divida, calcule, finalice. No hay un léxico obligado para el pseudocódigo, pero con el uso frecuente se han establecido algunos estándares.
Differentiate control structures in the design and construction of an algorithm:- Selective structures- Repetitive structures- nested structures

Estructuras selectiva: La representación de una estructura que se hace que haga palabras en pseudocódigo (si, entonces, elseo bien en español si, entonces, si_no), con una figura geométrica en forma de rombo o bien bien triangulo en el interior de una caja rectangular
ESTRUCTURAE-A SIMPLE SIMPLE
Funciona de la siguiente manera: se una evalúa condición, de cierta ser efectúa una acción, de lo contrario, continúa con la ejecución normal del programa.
Su sintaxis es la siguiente:
Si(condición) Acción;
O también:
If(Condición)
Acción;
Donde:
Condición: Es una expresión lógica que es evaluada por el pícrico
Acción: es la Acción o Acciones que se hace el programa de resultar de la condición
ESTRUCTURASE-CLIC DOBLE DOBLE
sta estructura, se caracteriza por el hecho que ofrece dos caminos a seguir, dependiendo si al evaluar la condición resulta cierta o falsa. Su sintaxis es la siguiente:
if(Condición)
Acción 1;
Más
Acción 2;
estructura por el sistema múltiple MÚLTIPLE
Como su nombre lo indica, permite seleccionar entre caminos para llegar a la final. En este caso se pueden elegir un camino o acción a ejecutar de entre varios posibles que se debe de evaluar, selector de llamada.
Sintaxis:
interruptor (selector)
{
caso Etiqueta A:
Acción A;
romper;
caso Etiqueta B:
Acción B;
romper;
caso Etiqueta n:
Acción n;
romper;
Predeterminado:
  Excepción;
   romper;                                                                             }
En donde:
Selector: Variables, expresiones simples de tipo ordinal, (enteros y caracteres –int y char-)


Estructuras repetitivas: Las estructuras repetitivas se utilizan cuando se quiere que un conjunto de instrucciones se ejecuten un cierto número finito de veces, por ejemplo, escribir algo en pantalla cierta cantidad de veces, mover un objeto de un punto a otro cierta cantidad de pasos, o hacer una operación matemática cierta cantidad de veces. Se les llama bucle o ciclo a todo proceso que se repite cierto número de veces dentro de un pseudocódigo o un programa y las estructuras repetitivas nos permiten hacerlo de forma sencilla.
FOR (PARA)
Esta estructura ejecuta las acciones del cuerpo del bucle un número especificado de veces, y de modo automático controla el número de iteraciones o pasos.
 

WHILE (MIENTRAS)
Repite el cuerpo del bucle mientras se cumpla una determinada condición.
 
DO- WHILE (HACER MIENTRAS)
La estructura HACER MIENTRAS cumple la misma función que la estructura MIENTRAS. La diferencia está en que la estructura  MIENTRAS comprueba la condición al inicio y repetir lo hace al final. Es por ello que la estructura HACER MIENTRAS se ejecuta por lo menos una vez.




nested structures: Decimos que una estructura condicional es anidada cuando por la rama del verdadero o el falso de una estructura condicional hay otra estructura condicional.

Distinguish the types of computational data:- 

Numeric: Pueden ser números reales o enteros, dependiendo de lo necesario.

- Logic: es en computación aquel que puede representar valores de lógica binaria, esto es 2 valores, que normalmente representan falso o verdadero.  Se utiliza normalmente en la programación, estadística, electrónica, matemáticas (Álgebra booleana), etc.

 String : es aquel que pueden tomar por valor una secuencia de caracteres. En pseudocódigo, el valor de un dato de tipo cadena se puede representar entre comillas simples (') o dobles (").

Characters: Dígitos individuales que se pueden representar mediante datos numéricos (0-9), letras (a-z) u otros símbolos.

- Arrangements: el cual es capaz de almacenar una colección de datos del mismo tipo. Es la forma más simple de agrupar componentes de un mismo tipo y asociarles un número de orden de cada componente llamado índice.

ConstantsExplain the types of computational operations:Operators:- Arithmetic- Logic-: 
Operadores:- Aritmética: es aquella parte de las ciencias de la computación que diseña, analiza, implementa y aplica algoritmos algebraicos
- Lógica: es una disciplina que estudia la aplicación de la Lógica Formal para la representación computacional de argumentos, las técnicas de deducción automática o asistida por computadora, los fundamentos relacionados con validez y completez (completeness) de sistemas de proposiciones y, las aplicaciones de esas técnicas a las diferentes áreas de las Ciencias Computacionales en todas las etapas del desarrollo del software, es decir, especificación, diseño, construcción y verificación formal de programas.



















Define concepts and characteristics of algorithms
Differentiate control structures in the design and construction of an algorithm:- Selective structures- Repetitive structures- nested structures
Describe the types of algorithm representation:- Graph: Flow chart- Written: pseudocode ** 
Define the characteristics of the variables and constants
Distinguish the types of computational data:- Numeric- Logic- String and characters- Arrangements
Describe the representation of computational data:-Variables-ConstantsExplain the types of computational operations:Operators:- Arithmetic- Logic- RelationshipsOperands:-Variables-ConstantsExpressions:- Arithmetic- Logic





Definir conceptos y características de algoritmos Diferenciar estructuras de control en el diseño y construcción de un algoritmo: - Estructuras selectivas - Estructuras repetitivas - Estructuras anidadas Describir los tipos de representación del algoritmo: - Gráfico: Diagrama de flujo - Escrito: pseudocódigo ** Definir las características del variables y constantes Distinguir los tipos de datos computacionales: - Numérico- Lógica- Cadena y caracteres- Arreglos Describir la representación de datos computacionales: -Variables-Constantes Explicar los tipos de operaciones computacionales: Operadores: - Aritmética- Lógica- Relaciones Operandos: -Variables-Constantes Expresiones : - Lógica aritmética



