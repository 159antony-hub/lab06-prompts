# Tarea: Mi prompt profesional
 
## Funcionalidad elegida
 ### Cálculo de notas 
## Version 1: prompt basico

Hazme un programa en Java que calcule notas.
 
## Version 2:
 Actúa como un desarrollador Java. Crea un programa que calcule el promedio 
final de un estudiante a partir de tres notas: prácticas, examen parcial y 
examen final, cada una con distinto peso. Valida que las notas estén entre 0 y 20.
## Version 3: prompt final
 Actúa como un desarrollador de software Java con experiencia en aplicaciones 
educativas.

Crea una clase Java llamada CalculadoraNotas que calcule el promedio final de 
un estudiante a partir de tres notas: prácticas (peso 30%), examen parcial 
(peso 30%) y examen final (peso 40%).

El programa debe validar que cada nota ingresada esté entre 0 y 20, y mostrar 
si el estudiante aprobó (promedio mayor o igual a 10.5) o desaprobó.

Por ejemplo, si las notas son 15, 12 y 18, el promedio se calcula como 
(15*0.3)+(12*0.3)+(18*0.4) = 15.3, y el resultado debe indicar "Aprobado".

Presenta el código organizado en una clase con comentarios explicando cada 
método, y al final una tabla en texto mostrando el detalle del cálculo 
(cada nota, su peso y su aporte al promedio).

Restricción: no uses librerías externas, solo Java estándar (java.util.Scanner 
está permitido para leer datos).
## Componentes del prompt final
 | Componente | Texto de mi prompt |
|------------|--------------------|
| Rol | Actúa como un desarrollador de software Java con experiencia en aplicaciones educativas.|
| Instruccion |Crea una clase Java llamada CalculadoraNotas que calcule el promedio final de un estudiante a partir de tres notas: prácticas (peso 30%), examen parcial (peso 30%) y examen final (peso 40%).
| Contexto |El programa debe validar que cada nota ingresada esté entre 0 y 20, y mostrar si el estudiante aprobó (promedio mayor o igual a 10.5) o desaprobó.
| Ejemplo |Por ejemplo, si las notas son 15, 12 y 18, el promedio se calcula como (15*0.3)+(12*0.3)+(18*0.4) = 15.3, y el resultado debe indicar "Aprobado".
| Formato |Presenta el código organizado en una clase con comentarios explicando cada método, y al final una tabla en texto mostrando el detalle del cálculo (cada nota, su peso y su aporte al promedio).

## Evaluacion del resultado
 CAMBIOS POR NIVEL:

-Nivel1: La IA crea un programa sencillo, con falta de información

-Nivel2: Explica un programa brevemente explicado y crea promeadios inventados, pero bien estructurado

-Nivel3: Se crea un programa más largo y estructurado, además explica las funcionalidades con un claro ejemplo
## Errores que evite

1. En la v1 no indiqué cuántas notas ni con qué pesos; en la v3 lo especifiqué con números exactos, así la IA no tiene que adivinar.
2. En la v1 y v2 no dije cómo debía verse la salida; en la v3 pedí explícitamente una tabla con el detalle del cálculo, y eso hizo que la respuesta fuera predecible.