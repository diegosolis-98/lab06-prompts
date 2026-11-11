# Bitacora de prompts

Laboratorio 06: Fundamentos de Ingenieria de Prompts. Herramienta de IA usada: (escribe aqui cual usaste) : chatGPT

## Ejercicio 2: Tokens y ventana de contexto
| Texto | Caracteres | Tokens |
|-------|------------|--------|
| Los estudiantes programan en Java. |36 |8 |
| The students program in Java. |31 | 7|
| desafortunadamente | 20| 5|
### Observaciones:
- En el paso 4 responde correctamente y sin problema el nombre y la herramienta usada.
- En el paso 5 responde lo mismo que en el paso anterior ya teniendo conocimiento lo escrito en el chat anterior.
## Ejercicio 3: Temperatura
| Temperatura | % de BiblioTec | Nombres en los 5 intentos |
|-------------|----------------|---------------------------|
|0|100| BiblioTec, BiblioTec, BiblioTec, BiblioTec, BiblioTec|
|0.5|65.3| BiblioTec, LibroYa, BiblioTec, LibroYa, PrestaLibro|
|1|44.5| PrestaLibro, NubeDeTinta, PrestaLibro, LibroYa, BiblioTec|
|1.8|32.2|LectoGo, PaginaLibre, LibroYa, LibroYa, NubeDeTinta|
- Al aumentar la temperatura las probabilidades se distribuye uniformemente por lo que aumenta la variedad de opciones.
- El simulador solo selecciona las opciones del arreglo. Por lo que, no genera texto nuevo sino utiliza probabilidades para elegir.
## Ejercicio 4: Prompt vago vs estructurado 
| Criterio | Prompt vago | Prompt estructurado |
|----------|-------------|---------------------|
| Menciona el objetivo del sistema | No|Sí |
| Menciona a los usuarios principales |No |Sí |
| Tiene exactamente 3 funcionalidades |No | Sí|
| Esta en 3 parrafos |No | Sí|
| Lo usaria en un informe real | Sí| Sí|

## Ejercicio 5: Anatomia de un prompt
| Componente | Texto de mi prompt |
|------------|--------------------|
| Rol | Actúa como desarrollador Java. |
| Instruccion | Crea un programa básico que se ejecute por consola.|
| Contexto |El programa debe permitir ingresar datos mediante el teclado y mostrar resultados. |
| Ejemplo | Por ejemplo, solicita el nombre del usuario y muestra un saludo.|
| Formato | Presenta el código Java completo y una breve explicación.|
- Rol: Define quién debe asumir la IA y desde qué perspectiva responderá.
- Instrucción: Indica la tarea específica que debe realizar.
- Contexto: Proporciona información adicional sobre lo que se necesita.
- Ejemplo: Muestra una referencia de cómo se espera que funcione el resultado.
- Formato: Establece cómo debe organizarse y presentarse la respuesta.
