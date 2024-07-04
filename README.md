>![image](https://github.com/Santiago1054/Portafolio/assets/170820106/9e4b04e2-29fd-4a69-b666-24aa7506674d)

## Tabla contenido listas


- [LISTAS](#listas)
- [SINTAXIS](#sintaxis)
- [METODOS](#metodos)

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

# Sintaxis
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

  ## Tabla contenido String
- [LONGITUD](#longitud)
- [MODIFICAN](#modifican)
- [CONVERSORES](#conversores)
- [CONVERSORES](#conversores)
- [VALIDACION](#validacion)
- [REMPLAZAN](#remplazan)
- [BYTES](#bytes)
## String
## Longitud
>### str.length():
 - Devuelve la longitud de la cadena.
 >![image](https://github.com/Santiago1054/Portafolio/assets/170820106/2459bb06-edc2-40f8-a1f1-0157e575ee8f)
## Modifican
>### str.substring(int beginIndex, int endIndex):
 - Devuelve una nueva cadena que es un subconjunto de la cadena original.
 >![image](https://github.com/Santiago1054/Portafolio/assets/170820106/2a50f86a-6137-4fc7-86f0-7ea987220d0e)
>
>
## ___________________________________________________________________
> ### str. concat(String str): 
- Concatena la cadena especificada al final de esta cadena.
 >  ![image](https://github.com/Santiago1054/Portafolio/assets/170820106/e6d10e65-b82e-438e-880e-7a673fda946a)
>
 ## ___________________________________________________________________
> ###  str.valueOf():
 - Métodos estáticos que convierten diferentes tipos de datos en cadenas.
 > ![image](https://github.com/Santiago1054/Portafolio/assets/170820106/13d66e28-73f0-493b-8f99-904b822c6ff5) 
>###  str.codePointAt(int index):
- Devuelve el valor Unicode del carácter en el índice especificado.
 >  ![image](https://github.com/Santiago1054/Portafolio/assets/170820106/b49aa8c2-b68c-4ea3-8a40-149e235659d9)
>
## ___________________________________________________________________
> ###  str.codePointBefore(int index):
- Devuelve el valor Unicode del carácter antes del índice especificado.
 > ![image](https://github.com/Santiago1054/Portafolio/assets/170820106/f922b189-16ad-44d4-b18d-7db2e4271b24)
>
## ___________________________________________________________________
> ###  str.codePointCount(int beginIndex, int endIndex):
- Devuelve el número de valores Unicode en la subcadena especificada.
 >  ![image](https://github.com/Santiago1054/Portafolio/assets/170820106/f4a02235-d0b4-42ef-b1dc-104fd5e00745)
>
## ___________________________________________________________________
> ###  str.subSequence(int beginIndex, int endIndex):
- Devuelve una nueva secuencia de caracteres que es una subsecuencia de esta secuencia.
 >  ![image](https://github.com/Santiago1054/Portafolio/assets/170820106/360d9e7e-3d60-4bf6-aec4-4d8ba4044f13)
>
## ___________________________________________________________________
> ###  str.join(CharSequence delimiter, CharSequence... elements):
- Devuelve una nueva cadena que es la concatenación de los elementos, separados por el delimitador especificado.
 > ![image](https://github.com/Santiago1054/Portafolio/assets/170820106/8e7649ac-1b32-4ec3-9190-f9d04763c20c)
>
## ___________________________________________________________________
> ###  str.format(String format, Object... args):
- Devuelve una cadena formateada usando la cadena de formato especificada y los argumentos.
 > ![image](https://github.com/Santiago1054/Portafolio/assets/170820106/beb3d275-44c1-4a7a-abd8-22656403c8e0)
>
## ___________________________________________________________________
> ### str.repeat(int count):
- Devuelve una cadena cuya representación es la concatenación de esta cadena repetida el número de veces especificado
 >  ![image](https://github.com/Santiago1054/Portafolio/assets/170820106/f4609529-14fa-4253-ba05-562183a6f5f8)
>
## ___________________________________________________________________
## Conversores
  > ###  str.toUpperCase():
-  Devuelve la cadena en mayúsculas.
  >![image](https://github.com/Santiago1054/Portafolio/assets/170820106/ce88347b-0e9b-47c4-8955-105787bcfcb5)
     >
     ## ___________________________________________________________________
    > ###  str.toLowerCase():
- Devuelve la cadena en minúsculas.
    >![image](https://github.com/Santiago1054/Portafolio/assets/170820106/9978f817-1943-45dd-a6bb-13703602ab9e)
     >
     ## ___________________________________________________________________
  > ###  str.toCharArray():
- Convierte esta cadena en un nuevo array de caracteres.
  >![image](https://github.com/Santiago1054/Portafolio/assets/170820106/34e54ed7-ca52-441d-885b-4b385cae34b1)
     >
     ## ___________________________________________________________________
## Validacion
  > ###  str.equals(String anotherString):
- Compara si dos cadenas son iguales.
  > ![image](https://github.com/Santiago1054/Portafolio/assets/170820106/5de47a82-d9b3-4dfc-be7b-ee1920bde72e)
    > 
## ___________________________________________________________________
  > ###  str.contains(CharSequence s):
- Devuelve true si la cadena contiene la secuencia especificada.
  > ![image](https://github.com/Santiago1054/Portafolio/assets/170820106/8aacc63d-3a68-4c8a-a247-653f1d40e9b7)
>
 ## ___________________________________________________________________
  > ###  str.startsWith(String prefix):
- Devuelve true si la cadena comienza con el prefijo especificado.
  > ![image](https://github.com/Santiago1054/Portafolio/assets/170820106/c96d36f9-5b0d-4f0d-8770-0adbbc4a3af3)
> 
## ___________________________________________________________________
  > ###  str.endsWith(String suffix):
- Devuelve true si la cadena termina con el sufijo especificado.
  > ![image](https://github.com/Santiago1054/Portafolio/assets/170820106/95188933-8542-469e-8472-f3f88990296e)
>
## ___________________________________________________________________
  > ###  str.isEmpty():
 - Devuelve true si la longitud de la cadena es 0.
  >![image](https://github.com/Santiago1054/Portafolio/assets/170820106/59f79537-4e1c-41bf-8331-53a67da0e81c)
>
## ___________________________________________________________________
  > ###  str.matches(String regex):
- Indica si esta cadena coincide con la expresión regular dada.
  > ![image](https://github.com/Santiago1054/Portafolio/assets/170820106/1aff789e-6b55-4152-a836-c8a8b5bcb812)
> 
## ___________________________________________________________________
  > ###  str.compareTo(String anotherString):
- Compara dos cadenas lexicográficamente.
  > ![image](https://github.com/Santiago1054/Portafolio/assets/170820106/8cca2e60-27fc-4e60-9f30-b77206c92b84)
>
## ___________________________________________________________________
  > ###  str.compareToIgnoreCase(String str):
 - Compara dos cadenas lexicográficamente, ignorando las diferencias entre mayúsculas y minúsculas.
  >![image](https://github.com/Santiago1054/Portafolio/assets/170820106/96983527-ff40-459d-a2c8-d624b7b8cb0b)
>
## ___________________________________________________________________
  > ###  str.contentEquals(CharSequence cs):
 - Compara esta cadena con la secuencia de caracteres especificada.
  > ![image](https://github.com/Santiago1054/Portafolio/assets/170820106/dd44e6f5-1646-49d9-a9cf-56e7443fc63a)
> 
## ___________________________________________________________________
  > ###  str.regionMatches(int toffset, String other, int ooffset, int len):
-  Prueba si las subcadenas de esta cadena y la cadena especificada son iguales.
  >![image](https://github.com/Santiago1054/Portafolio/assets/170820106/28e33287-844c-45f9-b582-702a6bb4ad2f)
>
## ___________________________________________________________________
  > ###  str.regionMatches(boolean ignoreCase, int toffset, String other, int ooffset, int len):
-  Prueba si las subcadenas de esta cadena y la cadena especificada son iguales, ignorando las diferencias entre mayúsculas y minúsculas.
  > ![image](https://github.com/Santiago1054/Portafolio/assets/170820106/b6652a16-153a-4d57-af34-42dbd7ef30df)
>
## ___________________________________________________________________
## indices
  > ###  str.indexOf(String str):
- Devuelve el índice de la primera aparición de la cadena especificada.
  > ![image](https://github.com/Santiago1054/Portafolio/assets/170820106/86a30072-f9c3-489a-b473-1039a2d7f718)
   >
    ## ___________________________________________________________________ 
  > ###  str.lastIndexOf(String str):
- Devuelve el índice de la última aparición de la cadena especificada.
  >![image](https://github.com/Santiago1054/Portafolio/assets/170820106/05f8734c-46a7-4cc0-8cb9-fa36234b1d61)
   >
   ## ___________________________________________________________________
## Remplazan
  > ### str. replace(char oldChar, char newChar):
- Reemplaza todas las apariciones del carácter especificado.
  >![image](https://github.com/Santiago1054/Portafolio/assets/170820106/8a46d08e-6e9e-4cb5-9a0d-414290cc38ef)
>
## ___________________________________________________________________
  > ###  str.trim():
- Elimina los espacios en blanco iniciales y finales.
  >![image](https://github.com/Santiago1054/Portafolio/assets/170820106/33caedf0-c4da-4950-b148-868afbde2462)
   >
  ## ___________________________________________________________________
  > ###  str.split(String regex):
 - Divide la cadena en un array de cadenas.
  >![image](https://github.com/Santiago1054/Portafolio/assets/170820106/bda2e9be-5b62-4ab0-a013-8760a50206cc)
   >
 ## ___________________________________________________________________
## Bytes 
  > ###  str.getBytes():
-  Codifica esta cadena en una secuencia de bytes usando el conjunto de caracteres predeterminado de la plataforma.
  >![image](https://github.com/Santiago1054/Portafolio/assets/170820106/4bb5430b-4e82-4c67-9270-a18995019026)
  >
## ___________________________________________________________________
  > ###   str.getBytes(Charset charset):
-  Codifica esta cadena en una secuencia de bytes usando el conjunto de caracteres especificado.
  >![image](https://github.com/Santiago1054/Portafolio/assets/170820106/b1cab3f2-bfa0-41f9-996a-6cdbbdffaff5)
>
## ___________________________________________________________________
  > ###  str.getChars(int srcBegin, int srcEnd, char[] dst, int dstBegin):
-  Copia los caracteres de la cadena en un array de caracteres.
  > ![image](https://github.com/Santiago1054/Portafolio/assets/170820106/c958d7f6-2f30-45c0-b818-948f6af23b02)
  > 






  
## Math:
- Math.max(a, b): Devuelve el máximo de dos números.
- Math.min(a, b): Devuelve el mínimo de dos números.
- Math.abs(a): Devuelve el valor absoluto de un número.
- Math.sqrt(a): Devuelve la raíz cuadrada de un número.
## ArrayList:
- add(element): Añade un elemento al final de la lista.
- get(index): Obtiene el elemento en la posición especificada.
- size(): Devuelve el número de elementos en la lista.
- 

# Math
- Math.max(a, b): Devuelve el mayor de los dos números.
- Math.min(a, b): Devuelve el menor de los dos números.
- Math.abs(a): Devuelve el valor absoluto de un número.
- Math.pow(a, b): Devuelve a elevado a la potencia de b.
- Math.sqrt(a): Devuelve la raíz cuadrada de un número.
- Math.random(): Devuelve un número aleatorio entre 0.0 y 1.0.
- Math.sin(double a): Devuelve el seno trigonométrico de un ángulo especificado (en radianes).
 > double result = Math.sin(Math.PI / 2); // 1.0
- Math.cos(double a): Devuelve el coseno trigonométrico de un ángulo especificado (en radianes).
  >double result = Math.cos(0); // 1.0
- Math.tan(double a): Devuelve la tangente trigonométrica de un ángulo especificado (en radianes).
- Math.asin(double a): Devuelve el arco seno de un valor; el resultado está en el rango de -pi/2 a pi/2.
- Math.acos(double a): Devuelve el arco coseno de un valor; el resultado está en el rango de 0.0 a pi.
- Math.atan(double a): Devuelve el arco tangente de un valor; el resultado está en el rango de -pi/2 a pi/2.
- Math.atan2(double y, double x): Convierte las coordenadas rectangulares (x, y) en un ángulo polar.
- Math.hypot(double x, double y): Devuelve sqrt(x² + y²) sin desbordamiento ni pérdida intermedia de precisión.
- Math.cbrt(double a): Devuelve la raíz cúbica de un valor.
- Math.expm1(double x): Devuelve ex - 1.
- Math.log1p(double x): Devuelve el logaritmo natural de la suma de un valor y 1.
- Math.scalb(double d, int scaleFactor): Devuelve d × 2^scaleFactor calculado de forma precisa.
- Math.nextAfter(double start, double direction): Devuelve el flotante más cercano en la dirección de un segundo valor.
- Math.nextUp(double d): Devuelve el flotante más cercano mayor que d.
- Math.nextDown(double d): Devuelve el flotante más cercano menor que d.
- Math.ulp(double d): Devuelve la magnitud del paso de incremento más pequeño entre dos valores de punto flotante adyacentes.
- Math.floorDiv(int x, int y): Devuelve el cociente de la división de enteros, redondeado hacia abajo.
- Math.floorMod(int x, int y): Devuelve el resto de la división de enteros, redondeado hacia abajo.
- Math.copySign(double magnitude, double sign): Devuelve el primer argumento con el signo del segundo argumento.
- Math.addExact(int x, int y): Devuelve la suma exacta de los argumentos, arrojando una excepción si el resultado desborda un valor int.
- Math.subtractExact(int x, int y): Devuelve la diferencia exacta de los argumentos, arrojando una excepción si el resultado desborda un valor int.
- Math.multiplyExact(int x, int y): Devuelve el producto exacto de los argumentos, arrojando una excepción si el resultado desborda un valor int.
- Math.toIntExact(long value): Devuelve el valor int exacto de un argumento long, arrojando una excepción si el valor no cabe en un int.
- Math.incrementExact(int a): Devuelve el argumento incrementado por uno, arrojando una excepción si el resultado desborda un valor int.
- Math.log(double a): Devuelve el logaritmo natural (base e) de un valor doble.
- Math.log10(double a): Devuelve el logaritmo en base 10 de un valor doble.max(long a, long b): Devuelve el mayor de dos valores long.
    > long result = Math.max(100L, 200L); // 200
- Math.min(long a, long b): Devuelve el menor de dos valores long.
- Math.toDegrees(double angrad): Convierte un ángulo medido en radianes a un ángulo aproximadamente equivalente medido en grados.
- Math.toRadians(double angdeg): Convierte un ángulo medido en grados a un ángulo aproximadamente equivalente medido en radianes.
  
## Métodos de la Clase Arrays
- Arrays.toString(array): Devuelve una representación en cadena del array.
- Arrays.sort(array): Ordena el array en orden ascendente.
- Arrays.binarySearch(array, key): Busca el elemento especificado en el array ordenado y devuelve su índice.
- Arrays.copyOf(array, newLength): Copia el array original a un nuevo array con la longitud especificada.
- Arrays.equals(type[] a, type[] a2): Compara dos arreglos para determinar si son iguales.
- Arrays.fill(type[] a, type val): Asigna el valor especificado a cada elemento de un arreglo.
- Arrays.copyOf(type[] original, int newLength): Copia el arreglo especificado, truncándolo o rellenándolo con ceros si es necesario para obtener la longitud especificada.
- Arrays.copyOfRange(type[] original, int from, int to): Copia la porción del arreglo especificado, especificada por el rango inicial y final.
- Arrays.mismatch(type[] a, type[] b): Encuentra y devuelve el índice del primer elemento diferente entre dos arreglos, o -1 si son iguales.
- Arrays.setAll(type[] array, IntUnaryOperator generator): Establece todos los elementos de un arreglo usando un generador basado en el índice.
 > int[] array = new int[5]; Arrays.setAll(array, index -> index * 2); // Ahora array es {0, 2, 4, 6, 8}
- Arrays.deepEquals(Object[] a1, Object[] a2): Compara dos arreglos multidimensionales para determinar si son iguales.
- Arrays.deepToString(Object[] a): Devuelve una representación de cadena del arreglo multidimensional especificado.
- Arrays.parallelSort(type[] a): Ordena un arreglo en orden ascendente de manera
  
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



