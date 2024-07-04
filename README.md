
## Table of Contents


- [Keywords](#keywords)
- [MERN](#mern)
- [JWT](#jwt)
- [Installation](#installation)
- [Deployment](#deployment)
# JAVA TOOLS

# Listas
## Que son las listas?
Las listas en Java, como hemos dicho, son estructuras de datos. Son fundamentales ya que pueden almacenar y organizar elementos de manera secuencia. Además, también ofrecen una mayor flexibilidad en la gestión de los datos, ya que pueden cambiar de tamaño de manera dinámica. Las listas en Java se implementan mediante interfaces como ‘List’ y también con clases concretas como ‘ArrayList’ y ‘LinkedList’.

Dentro de las listas en Java se pueden almacenar todo tipo de objetos. Esto permite la creación de listados heterogéneos. Además, lo que se guarda en este tipo de estructuras se ordena de una manera específica y cada uno de los elementos que componen la lista tiene su propio indicie. Como consecuencia, la manipulación de datos es más eficiente y posibilita que los programadores tengan una herramienta con la que poder gestionar la información en sus aplicaciones.
## ¿Para qué sirven las listas de Java?
Las listas son una de las estructuras de datos básicas en la programación Java y tienen una amplia gama de aplicaciones. Contienen elementos en un orden específico que pueden añadirse, modificarse, borrarse o consultarse. Los objetos de una Java List pueden pertenecer a distintas clases. Además, es posible almacenar elementos duplicados o nulos. Las listas Java admiten clases y métodos genéricos, lo que garantiza la seguridad de tipos.
## Los métodos de las listas de Java
Las listas de Java pertenecen a la interfaz collections y deben importarse desde el paquete java.util. Las clases de implementación incluyen Java ArrayList, LinkedList, Vector y Stack. Puedes declarar las distintas instancias de la lista de la siguiente manera:
### Primero se importa la libreria 
> import java.util.ArrayList;


### Sintaxis recomendada
![Screenshot 2024-07-04 140827](https://github.com/Santiago1054/Portafolio/assets/170820106/40c119b3-e5de-43c5-b667-c2dee944f94d)
# Otras formas		
### linkedList 
> List linkedList = new LinkedList(); // LinkedList
### arrayList 
> List arrayList = new ArrayList(); // ArrayList
### vecList
>List vecList = new Vector(); // Vector
### stackList
> List stackList = new Stack(); //Stack

Las listas se utilizan en aplicaciones de bases de datos para almacenar y acceder a grandes registros de consultas a bases de datos. En las interfaces gráficas de usuario, las listas Java suelen utilizarse para mostrar una lista de elementos, por ejemplo, las opciones de un menú desplegable o los distintos artículos de una tienda online.

Las listas de Java también son indispensables en algoritmos y estructuras de datos. Se utilizan en la implementación de algoritmos de ordenación, algoritmos de búsqueda o estructuras de pilas y colas. En aplicaciones de red, las listas pueden ayudar a facilitar la gestión de conexiones y sockets.
## Ventajas de utilizar listas
Estas son las ventajas más importantes respecto a usar listas en Java:

> - A diferencia de los arrays tradicionales, las listas en Java permiten cambiar el tamaño de forma dinámica. Esto facilita la gestión de conjuntos de datos variables.
> 
> - Las listas ofrecen a los programadores una forma eficiente de buscar elementos, que acaba influyendo en el rendimiento si lo comparamos con otro tipo de estructuras de datos.
> 
> - Las listas en Java incluyen métodos para agregar, eliminar y modificar elementos. Esto sirve para simplificar la manipulación de la información, ya que da una interfaz intuitiva para los programadores.
> 
Con este tipo de estructuras de datos, los programadores logran tener varios tipos de implementación, lo que da posibilidades variadas para distintos tipos de uso.

# Metodos 
# Métodos Básicos de la Clase Object
Estos métodos son heredados por todas las clases en Java:

- toString(): Devuelve una representación en cadena del objeto.
- equals(Object obj): Compara si dos objetos son iguales.
- hashCode(): Devuelve un código hash para el objeto.
- clone(): Crea y devuelve una copia del objeto.
- finalize(): Llamado por el recolector de basura cuando no hay más referencias al objeto.
# Métodos Estáticos en Clases Utilitarias
Algunas clases utilitarias en el paquete java.util y otros paquetes estándar de Java:

## Arrays:
- Arrays.sort(array): Ordena un array.
- Arrays.binarySearch(array, key): Busca un elemento en un array ordenado.
- Collections:
- Collections.sort(list): Ordena una lista.
- Collections.shuffle(list): Mezcla los elementos de una lista.
## Math:
- Math.max(a, b): Devuelve el máximo de dos números.
- Math.min(a, b): Devuelve el mínimo de dos números.
- Math.abs(a): Devuelve el valor absoluto de un número.
- Math.sqrt(a): Devuelve la raíz cuadrada de un número.
## ArrayList:
- add(element): Añade un elemento al final de la lista.
- get(index): Obtiene el elemento en la posición especificada.
- size(): Devuelve el número de elementos en la lista.
## String:
- length(): Devuelve la longitud de la cadena.
- substring(int beginIndex, int endIndex): Devuelve una nueva cadena que es un subconjunto de la cadena original.
  >String sub = str.substring(0, 2); // "He"
  >
 - toUpperCase(): Devuelve la cadena en mayúsculas.
 - toLowerCase(): Devuelve la cadena en minúsculas.
 - equals(String anotherString): Compara si dos cadenas son iguales.
 - contains(CharSequence s): Devuelve true si la cadena contiene la secuencia especificada.
 - indexOf(String str): Devuelve el índice de la primera aparición de la cadena especificada.
 - lastIndexOf(String str): Devuelve el índice de la última aparición de la cadena especificada.
 - replace(char oldChar, char newChar): Reemplaza todas las apariciones del carácter especificado.
 - trim(): Elimina los espacios en blanco iniciales y finales.
 - split(String regex): Divide la cadena en un array de cadenas.
   >String[] words = str.split(", "); // ["Hello", "world!"]
- startsWith(String prefix): Devuelve true si la cadena comienza con el prefijo especificado.
- endsWith(String suffix): Devuelve true si la cadena termina con el sufijo especificado.
- isEmpty(): Devuelve true si la longitud de la cadena es 0.
- matches(String regex): Indica si esta cadena coincide con la expresión regular dada.
- compareTo(String anotherString): Compara dos cadenas lexicográficamente.
- compareToIgnoreCase(String str): Compara dos cadenas lexicográficamente, ignorando las diferencias entre mayúsculas y minúsculas.
- concat(String str): Concatena la cadena especificada al final de esta cadena.
- valueOf(): Métodos estáticos que convierten diferentes tipos de datos en cadenas.
- codePointAt(int index): Devuelve el valor Unicode del carácter en el índice especificado.
- codePointBefore(int index): Devuelve el valor Unicode del carácter antes del índice especificado.
- codePointCount(int beginIndex, int endIndex): Devuelve el número de valores Unicode en la subcadena especificada.
- contentEquals(CharSequence cs): Compara esta cadena con la secuencia de caracteres especificada.
- getBytes(): Codifica esta cadena en una secuencia de bytes usando el conjunto de caracteres predeterminado de la plataforma.
  >byte[] bytes = str.getBytes(); // [72, 101, 108, 108, 111]
-  getBytes(Charset charset): Codifica esta cadena en una secuencia de bytes usando el conjunto de caracteres especificado.
   >byte[] bytesUTF8 = str.getBytes(StandardCharsets.UTF_8);
- getBytes(String charsetName): Codifica esta cadena en una secuencia de bytes usando el conjunto de caracteres especificado.
- getChars(int srcBegin, int srcEnd, char[] dst, int dstBegin): Copia los caracteres de la cadena en un array de caracteres.
- regionMatches(int toffset, String other, int ooffset, int len): Prueba si las subcadenas de esta cadena y la cadena especificada son iguales.
- regionMatches(boolean ignoreCase, int toffset, String other, int ooffset, int len): Prueba si las subcadenas de esta cadena y la cadena especificada son iguales, ignorando las diferencias entre mayúsculas y minúsculas.
- subSequence(int beginIndex, int endIndex): Devuelve una nueva secuencia de caracteres que es una subsecuencia de esta secuencia.
- toCharArray(): Convierte esta cadena en un nuevo array de caracteres.
- join(CharSequence delimiter, CharSequence... elements): Devuelve una nueva cadena que es la concatenación de los elementos, separados por el delimitador especificado.
- format(String format, Object... args): Devuelve una cadena formateada usando la cadena de formato especificada y los argumentos.
- repeat(int count): Devuelve una cadena cuya representación es la concatenación de esta cadena repetida el número de veces especificado.
- 
## Métodos de la Clase Math
- Math.max(a, b): Devuelve el mayor de los dos números.
- Math.min(a, b): Devuelve el menor de los dos números.
- Math.abs(a): Devuelve el valor absoluto de un número.
- Math.pow(a, b): Devuelve a elevado a la potencia de b.
- Math.sqrt(a): Devuelve la raíz cuadrada de un número.
- Math.random(): Devuelve un número aleatorio entre 0.0 y 1.0.
- sin(double a): Devuelve el seno trigonométrico de un ángulo especificado (en radianes).
 > double result = Math.sin(Math.PI / 2); // 1.0
- cos(double a): Devuelve el coseno trigonométrico de un ángulo especificado (en radianes).
  >double result = Math.cos(0); // 1.0
- tan(double a): Devuelve la tangente trigonométrica de un ángulo especificado (en radianes).
- asin(double a): Devuelve el arco seno de un valor; el resultado está en el rango de -pi/2 a pi/2.
- acos(double a): Devuelve el arco coseno de un valor; el resultado está en el rango de 0.0 a pi.
- atan(double a): Devuelve el arco tangente de un valor; el resultado está en el rango de -pi/2 a pi/2.
- atan2(double y, double x): Convierte las coordenadas rectangulares (x, y) en un ángulo polar.
- Math.hypot(double x, double y): Devuelve sqrt(x² + y²) sin desbordamiento ni pérdida intermedia de precisión.
- cbrt(double a): Devuelve la raíz cúbica de un valor.
- expm1(double x): Devuelve ex - 1.
- log1p(double x): Devuelve el logaritmo natural de la suma de un valor y 1.
- scalb(double d, int scaleFactor): Devuelve d × 2^scaleFactor calculado de forma precisa.
- nextAfter(double start, double direction): Devuelve el flotante más cercano en la dirección de un segundo valor.
- nextUp(double d): Devuelve el flotante más cercano mayor que d.
- nextDown(double d): Devuelve el flotante más cercano menor que d.
- rint(double a): Devuelve el entero más cercano como un valor de punto flotante.
- ulp(double d): Devuelve la magnitud del paso de incremento más pequeño entre dos valores de punto flotante adyacentes.
- floorDiv(int x, int y): Devuelve el cociente de la división de enteros, redondeado hacia abajo.
- floorMod(int x, int y): Devuelve el resto de la división de enteros, redondeado hacia abajo.
- copySign(double magnitude, double sign): Devuelve el primer argumento con el signo del segundo argumento.
- addExact(int x, int y): Devuelve la suma exacta de los argumentos, arrojando una excepción si el resultado desborda un valor int.
- subtractExact(int x, int y): Devuelve la diferencia exacta de los argumentos, arrojando una excepción si el resultado desborda un valor int.
- 
## Métodos de la Clase Arrays
- Arrays.toString(array): Devuelve una representación en cadena del array.
- Arrays.sort(array): Ordena el array en orden ascendente.
- Arrays.binarySearch(array, key): Busca el elemento especificado en el array ordenado y devuelve su índice.
- Arrays.copyOf(array, newLength): Copia el array original a un nuevo array con la longitud especificada.
## Métodos de la Clase Collections
- Collections.sort(list): Ordena la lista en orden ascendente.
- Collections.reverse(list): Invierte el orden de los elementos en la lista.
- Collections.shuffle(list): Mezcla los elementos de la lista de forma aleatoria.
- Collections.max(collection): Devuelve el elemento máximo de la colección.
- Collections.min(collection): Devuelve el elemento mínimo de la colección.
## Métodos de la Clase Files
- Files.readAllLines(path): Lee todas las líneas de un archivo y las devuelve como una lista de cadenas.
- Files.write(path, lines): Escribe las líneas especificadas en el archivo.
- Files.copy(source, target): Copia el archivo especificado.
- Files.move(source, target): Mueve el archivo especificado.



