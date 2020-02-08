# string.replace ()

Esta es una función incorporada en JavaScript que se usa para reemplazar una parte de la cadena dada con alguna otra cadena o una expresión regular. La cadena original permanecerá sin cambios.

**Sintaxis:**

```js
str.replace (A, B)
```

**Parámetros:** aquí el parámetro A es una expresión regular y B es una cadena que reemplazará el contenido de la cadena dada.

**Valores devueltos:** devuelve una nueva cadena con elementos reemplazados.

**Ejemplo:**

```js
var cadena = 'Hola Mundo'; 
var nuevaCadena = cadena.replace(/Mundo/, 'IbagueJs'); 
console.log(nuevaCadena);   
```

**Ejercicio:**

Genere una variable en la que guarde el numero uno en letras y haciendo uso de la funcion replace, reemplace este texto por el numero 1.