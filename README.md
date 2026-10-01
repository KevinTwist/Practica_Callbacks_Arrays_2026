# 🎓 IFTS N° 11 – Tecnicatura Superior en Desarrollo de Software

* **Materia:** Desarrollo de Sistemas Web – BackEnd
* **Profesor:** Zammataro Gustavo
* **Práctica:** Funciones, Callbacks y Arrays

---

## 📋 Pautas Generales
* **A)** Generar un repositorio público en Github donde se subirá el código de la práctica.
* **B)** Ingresar como comentario en el código cada uno de los enunciados de los ejercicios.
* **C)** Inicializar un paquete con el comando `npm init`.

---

## 💻 Ejercicio 01 – Funciones y Arrays

1. Crear una función que reciba dos parámetros y retorne un valor.
2. Crear una función que se llame `calcularAreaCuadrado` que reciba un parámetro que sea el lado del cuadrado, calcule el área y la retorne.
3. Crear una función por declaración, puede hacer lo que quieras.
4. Crear una función lambda por expresión que se llame `autosuma`, recibe un parámetro que es un array de números y retorna la suma del total de los números (utilizar `forEach` para recorrer el array).
5. Crear una función flecha (*arrow function*) que reciba un nombre, el año de nacimiento, y retorne un string que diga: *“Hola [nombre] este año tenés o cumplís [número] años”*.
6. Crear una función lambda que se llame `inscribirAlumno`, que reciba un array de alumnos y un nombre, que agregue al alumno en la última posición del array.
7. Crear una función que se llame `buscador`, que reciba un array con nombres de alumnos y un nombre a buscar, y diga si encuentra el nombre en la lista.

---

## 🔄 Ejercicio 02 – Callbacks

1. Definir una función que se llame `Calculadora`, que reciba un array de números y una callback.
   * **A)** Pasarle por argumento una función arrow que realice la suma de los elementos del array.
   * **B)** Pasarle por argumento una función arrow que realice la resta de los elementos del array.
   * **C)** Pasarle por argumento una función arrow que realice la multiplicación de los elementos.

2. Definir una función llamada `agregarSiEstaEntreCeroYDiez`, que reciba un número y un array. La función debe validar si el número es mayor o igual a cero y menor o igual a 10; en caso favorable, debe agregarlo en la primera posición del array, caso contrario debe arrojar un error informando que el número es mayor o menor a lo establecido. Debe retornar el array con el resultado.

3. Definir una función similar a la del punto 2, pero que en vez de un número reciba un array con números y valide si cada uno de los elementos cumple con la condición de estar entre cero y diez. Debe retornar un array con los números que cumplan la función.

4. **¡Momento de creatividad!** – Definir una función que reciba tres parámetros (algo, y dos callbacks) que internamente las ejecute y realice algún procedimiento.

5. Realizar una función que se llame `validarIngreso`, que reciba una edad y una callback. Esta función debe validar por medio de un operador ternario si puede integrar o no (la condición es que sea mayor a 18 años). El resultado del operador ternario se debe pasar como argumento a la ejecución de la callback. *(Podés elegir qué hacer con la función callback que le vas a pasar por argumento a la función validarIngreso)*.

---

## 📦 Entrega
Realizar la entrega en el aula virtual enviando el link al repositorio público de GitHub donde se subió el código realizado.

> **Nota al pie:** Recordar las buenas prácticas de programación que fuimos viendo en clase. 💻✨
