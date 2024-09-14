# Lab 1.06
## Introducción

Acabamos de aprender cómo usar entrada/salida en la consola y archivos, así que practiquemos un poco más.

<br>

## Requisitos

1. Haz un fork de este repositorio.
2. Clona este repositorio.
3. Añade a tu instructor y a los calificadores de la clase como colaboradores de tu repositorio. Si no estás seguro de quiénes son los calificadores de tu clase, pregunta a tu instructor o consulta la presentación del primer día.
4. En el repositorio, crea un proyecto de Java y añade el código para las siguientes tareas.

## Entrega

Una vez que termines la tarea, envía un enlace URL a tu repositorio o tu solicitud de extracción en el campo de abajo.

<br>

## Instrucciones

### Clases de Employee e Intern

1. Crea una clase `Employee` para representar un empleado de una empresa. La clase debe tener las propiedades `name`, `email`, `age`, `salary` y los getters y setters apropiados.
2. Crea una clase `Intern` que extienda de `Employee`. La clase `Intern` debe tener un límite de salario de 20000 (constante).
3. Implementa la validación en la clase `Intern` para garantizar que un interno no sea creado (o el salario actualizado) con un salario que exceda el valor máximo permitido.
4. Escriba un programa que cree 10 objetos `Employee` y muestre todas sus propiedades (nombre, correo electrónico, edad, salario) en un archivo llamado `employees.txt`.

<br>

### Consejos

- Asegúrate de considerar la relación entre las clases `Employee` e `Intern` al diseñar tu solución.
- Piensa en las diferentes propiedades y comportamientos que son aplicables tanto a los objetos `Employee` como a `Intern` y considera cómo puedes usar la herencia para evitar la duplicación de código.
- Usa los modificadores de acceso apropiados (por ejemplo, `private`, `protected`, `public`) para controlar la visibilidad de tus propiedades y métodos de clase.
- Asegúrate de manejar los casos límite y tratarlos adecuadamente (por ejemplo, ¿qué sucede si se crea un objeto `Intern` con un salario que supera el valor máximo permitido?).

<br>
