
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
### linkedList 
> List linkedList = new LinkedList(); // LinkedList
### arrayList 
> List arrayList = new ArrayList(); // ArrayList
### vecList
>List vecList = new Vector(); // Vector
### stackList
> List stackList = new Stack(); //Stack

### Sintaxis recomendada
- List <String> lista_1 = new ArrayList<>(size);; // Esta forma es recomendable (Si se sabe el tamano de la lista es mejor asignarle un tamano)

- List <String> lista_2 = new LinkedList<>() // Esta forma es recomendable
		


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



