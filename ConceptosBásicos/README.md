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

# Variables y constantes

- Las variables son valores establecidos
- Las constantes son valores previamente definidos, el valor de una constante siempre sera el mismo

```javascript
{
  // Variables en JavaScript
  // let|var nombreVariable = valor

  let nombre = "Alberto";
  var nombre = "Alberto";
}
```
*let y var son diferentes formas de crear una varible, la diferencia entre estas dos maneras sera explicada posteriormente

```javascript
{
  // Constantes en JavaScript
  
  const PI = 3.1416;
}
```

- Importante:
	* Las variables no pueden contener espacios en sus nombres
	* Los nombres de las variables pueden iniciarl con una letra, signo $ o _
	* Los nombres de las variables no pueden iniciar con un numero
	* Existen nombres reservados que no puedes utilizar para llamar una variable, ya que estas palabras ya se encuentran asignadas a una funcion o caracteristica del lenguaje y usarlas podria traer errores en la ejecucion del codigo, ejemplo : let, var, const, etc.

- Operaciones matematicas
	* las operaciones aritmeticas deben realizarse con variables de tipo number
	* los operadores mas comunes son: suma (+). resta (-), multiplicacion (*), divicion (/) y modulo (%).
	* para operaciones adicionales se debe recurir a la libreria Math, ejemplo: Math.PI = 3.1415..., Math.pow(), Math.sqrt(), etc.  (para mas funciones de Math ir a [w3schools.com/js/js_math.asp](https://www.w3schools.com/js/js_math.asp) )

- Tipos de datos
	JavaScript es un lenguaje devilmente tipado, los tipos de datos son anotaciones que hacemos a nuestro programa para que el interprete use.
	en JavaScript existen 5 tipos de datos a los que llamamos "primitivos" estos son:

	1. string (cadena de caracteres ejemplo: var nombre = Alberto; )
	2. number (numero, ejemplo: var edad = 24; )
	3. boolean (boleano, ejemplo: var verdadero = true;)
	4. undefined ()
	5. symbol

	Tambien existe el tipo null, el cual analisaremos a fondo posteriormente.
	Los tipos de datos primitivos son "inmutables", lo que quiere decir que una ves que el interprete asigne un tipo de dato este no podra cambiar a no ser que se transforme el tipo de dato, estos pueden transformase con las siguientes funciones :
	* String()
	* Number()
	* Boolean()
	* Symbol()
	* BigInt()
	* parseInt()
	* parseFloat()

	ejemplo: 

```javascript
{
  // Transformacion de tipo de dato

  let number = "hola"; // inmutable, se crea la variable 'number' que al contener texto el interprete le asigna el tipo String
  number = 20; console.log(number) // console > "20" | este se mostrara en consola como una cadena de caracteres aunque se digite un numero ya que el interprete le asigno el tipo string previamente
  console.log((Number(number) // console > 20 | aqui convertira el valor de la variable number a un tipo Number gracias al uso de la funcion Number())
}
```
tambien existe el metodo toString() , este metodo especial representa el valor de los objetos a texto



