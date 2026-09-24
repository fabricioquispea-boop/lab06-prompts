# Tarea: Mi prompt profesional

## Funcionalidad elegida

CRUD de productos para una tienda utilizando Java Swing.

La funcionalidad permitirá registrar, consultar, modificar y eliminar productos.

## Version 1: Prompt básico

```text
Crea un programa para gestionar productos de una tienda.
```

### Qué cambié

En esta primera versión solamente indiqué la funcionalidad que quería realizar.

### Por qué

Quise comenzar con un prompt sencillo para observar qué información podía generar la IA sin darle muchos detalles.

### Qué mejoró en la respuesta

La IA pudo generar una propuesta inicial, pero la respuesta podía ser muy general porque no se especificó la tecnología, los datos de los productos ni el formato esperado.

---

## Version 2: Prompt mejorado

```text
Actua como desarrollador Java. Crea una aplicación de escritorio en Java Swing para gestionar productos de una tienda.

La clase Producto debe tener los atributos codigo, nombre, precio y stock.
La aplicación debe permitir registrar, consultar, modificar y eliminar productos.

Explica brevemente el funcionamiento y presenta el código organizado por clases.
```

### Qué cambié

Agregué un rol, la tecnología que se debe utilizar, el contexto del sistema, los atributos de la clase Producto y las operaciones que debe realizar.

### Por qué

Quería reducir las respuestas generales y proporcionar información suficiente para que la IA entendiera qué aplicación debía desarrollar.

### Qué mejoró en la respuesta

La respuesta quedó más relacionada con una aplicación real de gestión de productos y tuvo una estructura más clara.

---

## Version 3: Prompt final

```text
Actua como desarrollador Java especializado en aplicaciones de escritorio.

Crea una aplicación en Java Swing para gestionar los productos de una tienda. La aplicación debe permitir registrar, consultar, modificar y eliminar productos.

Utiliza una clase Producto con los atributos codigo, nombre, precio y stock. Los métodos de acceso deben utilizar un estilo como getPrecio() y setPrecio(double precio).

Ejemplo:
getPrecio()
setPrecio(double precio)

No uses librerías externas; utiliza únicamente las clases disponibles en Java y Swing. Valida que el precio y el stock no sean valores negativos.

Explica primero la estructura de la solución, después describe brevemente su funcionamiento y finalmente presenta el código Java organizado por clases.
```

### Qué cambié

Agregué los cinco componentes de un prompt efectivo: rol, instrucción, contexto, ejemplo y formato. También agregué restricciones y validaciones para controlar mejor el resultado.

### Por qué

El objetivo fue conseguir una respuesta más específica y útil, evitando que la IA tuviera que asumir información sobre el proyecto.

### Qué mejoró en la respuesta

El prompt final proporciona instrucciones más completas sobre la aplicación, establece las características de la clase Producto, indica un ejemplo del estilo de los métodos, limita el uso de librerías y especifica cómo debe presentarse la respuesta.

---

## Componentes del prompt final

| Componente | Texto del prompt |
|---|---|
| Rol | Actua como desarrollador Java especializado en aplicaciones de escritorio. |
| Instrucción | Crea una aplicación en Java Swing para gestionar los productos de una tienda. |
| Contexto | La aplicación debe permitir registrar, consultar, modificar y eliminar productos y utilizar una clase Producto con codigo, nombre, precio y stock. |
| Ejemplo | getPrecio() y setPrecio(double precio). |
| Formato | Explica primero la estructura, después el funcionamiento y finalmente presenta el código organizado por clases. |

## Restricción

La restricción utilizada fue:

```text
No uses librerías externas; utiliza únicamente las clases disponibles en Java y Swing.
```

También se agregó una validación para impedir que el precio y el stock sean valores negativos.

## Evaluación del resultado

| Criterio | Cumple |
|---|---|
| Está desarrollado en Java | Sí |
| Utiliza Java Swing | Sí |
| Utiliza la clase Producto | Sí |
| Contiene codigo, nombre, precio y stock | Sí |
| Permite registrar, consultar, modificar y eliminar productos | Sí |
| Incluye validaciones | Sí |
| Evita librerías externas | Sí |
| Presenta el código organizado por clases | Sí |

## Errores frecuentes y cómo los evité

### 1. Ser demasiado general

En la primera versión el prompt solamente indicaba que se debía crear un programa para gestionar productos. Para evitar este error, en las siguientes versiones agregué la tecnología, los atributos, las operaciones y las características específicas del sistema.

### 2. No indicar el formato

Para evitar este error indiqué explícitamente cómo debía presentarse la respuesta: primero explicar la estructura, después describir el funcionamiento y finalmente mostrar el código organizado por clases.

## Conclusión

La iteración permitió mejorar progresivamente el prompt. La primera versión era general, mientras que la segunda agregó información importante sobre el sistema. Finalmente, la tercera versión incorporó los cinco componentes de un prompt efectivo y restricciones específicas, obteniendo una instrucción más completa y precisa.