Laboratorio 06: Fundamentos de Ingenieria de Prompts. 
Herramienta de IA usada: (escribe aqui cual usaste)

En el mismo chat, la IA pudo responder correctamente que la aplicación se llama TiendaTec y que utiliza Java Swing, porque esa información estaba disponible dentro de la conversación.

En un chat nuevo, la IA no tenía inicialmente esa información porque la conversación anterior no formaba parte de su contexto.

## Ejercicio 2: Tokens y ventana de contexto
|              Texto                 | Caracteres | Tokens |
|	                                 |	          |	       |
| Los estudiantes programan en Java. |     34     |   7    |
| The students program in Java.      |     34     |   7    |
| desafortunadamente.                |     4      |   20   |
## Ejercicio 3: Temperatura

### Resultados del simulador

| Temperatura | % de BiblioTec | Nombres en los 5 intentos |
|---|---:|---|
| 0 | BiblioTec    100.0% ########################################
LibroYa        0.0% 
PrestaLibro    0.0% 
LectoGo        0.0% 
PaginaLibre    0.0% 
NubeDeTinta    0.0% |BiblioTec, BiblioTec, BiblioTec, BiblioTec, BiblioTec |
| 0.5 |BiblioTec     65.3% ##########################
LibroYa       24.0% ##########
PrestaLibro    8.8% ####
LectoGo        1.2% 
PaginaLibre    0.4% 
NubeDeTinta    0.2% | LibroYa, BiblioTec, BiblioTec, BiblioTec, BiblioTec |
| 1 |BiblioTec     44.5% ##################
LibroYa       27.0% ###########
PrestaLibro   16.4% #######
LectoGo        6.0% ##
PaginaLibre    3.7% #
NubeDeTinta    2.4% # |LibroYa, LibroYa, BiblioTec, LibroYa, LibroYa |
| 1.8 |BiblioTec     32.2% #############
LibroYa       24.4% ##########
PrestaLibro   18.5% #######
LectoGo       10.6% ####
PaginaLibre    8.0% ###
NubeDeTinta    6.4% ### |BiblioTec, PaginaLibre, LibroYa, BiblioTec, LibroYa || Criterio | Prompt vago | Prompt estructurado |
|---|---|---|
| Menciona el objetivo del sistema | | |
| Menciona los usuarios principales | | |
| Tiene exactamente 3 funcionalidades | | |
| Está en 3 párrafos | | |
| Lo usaría en un informe real | | |

## Ejercicio 4: Prompt vago vs estructurado 
| Criterio | Prompt vago | Prompt estructurado |
|---|---|---|
| Menciona el objetivo del sistema |Si |Si |
| Menciona los usuarios principales |No |Si |
| Tiene exactamente 3 funcionalidades |No |Si |
| Está en 3 párrafos |No |Si |
| Lo usaría en un informe real |No |Si |
## Ejercicio 5: Anatomia de un prompt
| Componente | Texto de mi prompt |
|	|	|
| Rol |Actua como desarrollador Java. |
| Instruccion |Crea un programa en Java... |
| Contexto |...para gestionar los productos de una tienda...  |
| Ejemplo |Usa este estilo para los metodos: getPrecio(), setPrecio(double precio).  |
| Formato |Explica primero la estructura de la clase y luego presenta el codigo Java.  |
## Ejercicio 6: Del prompt basico al profesional
| Criterio | Cumple |
|---|---|
| Está escrito en Java y usa Swing | Sí | No |
| Pide correo y contraseña | Sí | No |
| Explica el funcionamiento | Sí | No |
| El código está organizado en clases | Sí | No |
| Valida los datos ingresados | Sí | No |

```text
[PEGA AQUÍ TU PROMPT PROFESIONAL]

[PEGA AQUÍ LA MEJORA QUE ENVIASTE]
```