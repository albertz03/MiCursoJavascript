# Conceptos Básicos
- JavaScript es un lenguaje Interpretado
Esto quiere decir que se necesita de un "interprete" para ser ejecutado, la ejecucion de javascript es en cascada, por lo que el orden es de arriba a abajo.

- JavaScript es un lenguaje débilmente y dinamicamente tipado
tipado hace referencia al tipo de variables, esto separa a los lenguajes en tipados y no tipados.

por ejemplo, en Java se necesita especificar el "tipo" de dato

```java
{
  // JAVA
  int edad = 24;
}
```

```javascript
{
  // JavaScript
  let edad = 24; // Asigna tipo Number de forma automatica
  edad = 'cadena';
}
```
En JavaScript el interprete asignara de forma dinamica el tipo de dato, esto hasta que la linea sea ejecutada por el programa.

- JavaScript distingue entre mayúsculas y minúsculas
Cada que se asigne un numbre a algo dentro del codigo de JavaScript este notara la diferencia entre sus caracteres y sera sencible a mayúsculas y minúsculas.

ejemplo:

```javascript
{
  // Variables diferentes
  
  var nombre
  var Nombre
}
```
