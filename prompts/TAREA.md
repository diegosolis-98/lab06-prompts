# Tarea: Mi prompt profesional

## Funcionalidad elegida

chatGPT

## Version 1: prompt basico 
Realiza un programa de registro de clientes.

- Qué cambia: Es una instrucción general sin mucho detalle.

- Por qué: Es el punto de partida.

- Qué mejoró: Se obtiene una propuesta.
## Version 2
Actúa como desarrollador Java. Crea un programa de registro de clientes utilizando una clase Cliente con los atributos codigo, nombre, apellido y telefono. Incluye un menú por consola para registrar y mostrar clientes.

- Qué cambia: Añadí el rol, el lenguaje, los atributos y las funciones.

- Por qué: Para definir mejor los requisitos.

- Qué mejoró: La respuesta presenta una estructura más organizada y funcionalidades concretas.
## Version 3: prompt final
Actúa como desarrollador Java. Crea un programa de registro de clientes para una pequeña tienda.

Utiliza una clase Cliente con los atributos codigo, nombre y telefono. Implementa un menú por consola que permita registrar, mostrar y buscar clientes por código.

Ejemplo: Si el usuario selecciona la opción 1, podrá registrar un cliente; con la opción 2, visualizar el registro; con la opción 3, busqueda por código.

Presenta primero la estructura de la clase, luego el código completo y una breve explicación.

Restricción: No utilices librerías externas y utiliza ArrayList para almacenar y generar la lista de los clientes.

- Qué cambia: Añadí contexto, ejemplos, formato y restricciones.

- Por qué: Para precisar el resultado esperado.

- Qué mejoró: La respuesta es más completa, clara y precisa a lo esperado.
## Componentes del prompt final 
| Componente | Identificación |
|---|---|
| Rol | Desarrollador Java. |
| Instrucción | Crear un programa de registro de clientes. |
| Contexto | Sistema para una pequeña tienda. |
| Ejemplos | Uso de las opciones del menú. |
| Formato | Estructura, código y explicación. |
## Evaluacion del resultado
| Criterio | V1 | V2 | V3 |
|---|:---:|:---:|:---:|
| Define el lenguaje de programación. | No | Sí | Sí |
| Especifica los atributos del cliente. | No | Sí | Sí |
| Define las funcionalidades del programa. | No | Sí | Sí |
| Indica el formato y las restricciones. | No | No | Sí |
## Errores que evite
- Ser demasiado general: Especifiqué el lenguaje, los atributos y las funcionalidades requeridas.

- No indicar un formato: Definí cómo debe organizarse la respuesta: estructura de la clase, código y su explicación.
