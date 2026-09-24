# Bitacora de prompts
 
Laboratorio 06: Fundamentos de Ingenieria de Prompts.
 
Herramienta de IA usada: (escribe aqui cual usaste)
 
## Ejercicio 2: Tokens y ventana de contexto
 | Texto | Caracteres | Tokens |
|-------|------------|--------|
| Los estudiantes programan en Java. | 35| 7|
| The students program in Java. |30 |6 |
| desafortunadamente | 18| 4|

Al preguntar a la IA respondio correctamente en el chat inicial, sin embargo, en el nuevo chat aparentemente tiene una función de memoria por lo que en el nuevo chat respondió correctamente, la IA es chatGPT.

## Ejercicio 3: Temperatura
| Temperatura | % de BiblioTec | Nombres en los 5 intentos |
|-------------|----------------|---------------------------|
| 0 | 100 | BiblioTec, BiblioTec, BiblioTec, BiblioTec, BiblioTec|
| 0.5 | 65.3 | BiblioTec, BiblioTec, BiblioTec, LibroYa, LibroYa|
| 1 | 44.5 | LibroYa, LibroYa, BiblioTec, BiblioTec, LibroYa|
| 1.8 | 32.2 | BiblioTec, LectoGo, LibroYa, BiblioTec, PaginaLibre|


Al subir la temperatura, el porcentaje del nombre favorito baja y se reparte entre las demás opciones, por lo que en cada ejecución puede salir un nombre distinto (incluso los menos probables, como LectoGo o NubeDeTinta).
## Ejercicio 4: Prompt vago vs estructurado
 | Criterio | Prompt vago | Prompt estructurado |
|----------|-------------|---------------------|
| Menciona el objetivo del sistema |si | si |
| Menciona a los usuarios principales | no|si |
| Tiene exactamente 3 funcionalidades | no|si |
| Esta en 3 parrafos | no|si |
| Lo usaria en un informe real |no |si |

## Ejercicio 5: Anatomia de un prompt
| Componente | Texto de mi prompt |
|------------|--------------------|
| Rol |Actua como desarrollador Java.  |
| Instruccion | Crea un programa en Java para gestionar los productos de una tienda. |
| Contexto | usando una clase Producto con los atributos codigo, nombre, precio y stock. |
| Ejemplo | Usa este estilo para los metodos: getPrecio(), setPrecio(double precio). |
| Formato | Explica primero la estructura de la clase y luego presenta el codigo Java.|

CAMBIOS POR NIVEL:

-Nivel1: La IA no crea ninguún programa y pregunta como se desea empezar

-Nivel2: Se crea el programa en crudo sin ninguna explicacion y sin comentarios

-Nivel3: Se crea un programa más largo y estructurado, además explica las funcionalidades

-Nivel4:  Crea un programa más estructurado y explica el contenido

-Nivel5: Da primero la estructura, genera el programa completamente ordenado y con comentarios, e incluye un ejemplo

 
## Ejercicio 6: Del prompt basico al profesional

| Qué revisar | Cumple (Sí / No)|
|------------|--------------------|
| ¿Está escrito en Java y usa Swing? |si |
| ¿Pide correo y contraseña?| si|
| ¿Explica el funcionamiento antes o después del código? |si |
| ¿El código está organizado en clases?| si|
| ¿Valida los datos que ingresa el usuario?| si|

```text
(Actua como desarrollador Java. Crea un ejemplo de login para una
aplicacion de escritorio utilizando Swing. El usuario debe ingresar
correo y contrasena. Explica brevemente el funcionamiento y presenta
el codigo organizado por clases.
Mejora el codigo anterior con estas restricciones: no uses librerias
externas, valida que el correo contenga @ y que la contrasena tenga
al menos 8 caracteres, y muestra los mensajes con JOptionPane.
)
```



