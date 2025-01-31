# 09 Desafío: hora de practicar
<p>Y vamos a poner en práctica nuestro conocimiento con otra lista de actividades (no obligatorias) para que practiques y refuerces aún más tu aprendizaje.</p>

## Desafíos finales:
1. Crea un programa que utilice console.log para mostrar un mensaje de bienvenida.
```javascript
  console.log('¡Bienvenido!');
```
2. Crea una variable llamada "nombre" y asígnale tu nombre. Luego, utiliza console.log para mostrar el mensaje "¡Hola, [tu nombre]!" en la consola del navegador.
```javascript
  let nombre = "Tonatiuh";
  console.log(`¡Hola, ${nombre}!`);
```
3. Crea una variable llamada "nombre" y asígnale tu nombre. Luego, utiliza alert para mostrar el mensaje "¡Hola, [tu nombre]!".
```javascript
  let nombre = "Tonatiuh";
  alert(`¡Hola, ${nombre}!`);
```
4. Utiliza prompt y haz la siguiente pregunta: ¿Cuál es el lenguaje de programación que más te gusta?. Luego, almacena la respuesta en una variable y muestra la respuesta en la consola del navegador.
```javascript
  let lenguaje = prompt('¿Cuál es el lenguaje de programación que más te gusta?');
  console.log(`El lenguaje de programación que mas te gusta es ${lenguaje}`);
```
5. Crea una variable llamada "valor1" y otra llamada "valor2", asignándoles valores numéricos de tu elección. Luego, realiza la suma de estos dos valores y almacena el resultado en una tercera variable llamada "resultado".
   Utiliza console.log para mostrar el mensaje "La suma de [valor1] y [valor2] es igual a [resultado]." en la consola.
```javascript
  let valor1 = 42;
  let valor2 = 10;
  resultado = valor1 + valor2;
  console.log(`la suma de ${valor1} y ${valor2} es igual a ${resultado}.`);
```
6. Crea una variable llamada "valor1" y otra llamada "valor2", asignándoles valores numéricos de tu elección. Luego, realiza la resta de estos dos valores y almacena el resultado en una tercera variable llamada "resultado".
   Utiliza console.log para mostrar el mensaje "La diferencia entre [valor1] y [valor2] es igual a [resultado]." en la consola.
```javascript
  let valor1 = 34;
  let valor2 = 21;
  resultado = valor1 - valor2;
  console.log(`la resta de ${valor1} y ${valor2} es igual a ${resultado}.`);
```
7. Pide al usuario que ingrese su edad con prompt. Con base en la edad ingresada, utiliza un if para verificar si la persona es mayor o menor de edad y muestra un mensaje apropiado en la consola.
```javascript
  let edadUsuario = prompt("ingrese su edad: ");
  (edadUsuario >= 18)? console.log("Eres mayor de edad") : console.log("Eres menor de edad"); 
```
8. Crea una variable "numero" y solicita un valor con prompt. Luego, verifica si es positivo, negativo o cero utilizando un if-else y muestra el mensaje correspondiente.
```javascript
   let numero = parseInt(prompt("Por favor, dijite un número"));
   if(numero == 0){
      console.log("El valor es cero");
   } else{
      (numero > 0)? console.log("El número es positivo") : console.log("El número es negativo");
   }
```
9. Utiliza un bucle while para mostrar los números del 1 al 10 en la consola.
```javascript
  let contador = 1;
  while(contador <= 10){
   console.log(contador++); 
  }
```
10. Crea una variable "nota" y asígnale un valor numérico. Utiliza un if-else para determinar si la nota es mayor o igual a 7 y muestra "Aprobado" o "Reprobado" en la consola.
```javascript
  let nota = 6;
  (nota >= 7)? console.log("Aprobado") :  console.log("Reprobado");
```
11. Utiliza Math.random para generar cualquier número aleatorio y muestra ese número en la consola.
   
