# 2025-06-04

Programación colaborativa en GitHub, sobre la administración de repositorios para organizaciones educacionales en GitHub.

Curso avanzado de 3 horas.

Para 10 estudiantes.

## Contenido

* Uso de forks para distribuir contenidos entre muchos usuarios
  * Qué es un fork y cuál es la relación con el repositorio original
  * Cómo múltiples personas pueden trabajar en forks distintos
  * Cómo un admin puede administrar la complejidad de las redes de forks
* Uso de issues para discutir mejoras y errores en repositorios y código
  * Comunicación profesional y efectiva entre programadores y admins
  * Uso de lenguaje unívoco / no ambiguo para describir problemas y conflictos
  * Uso de issues para asignar roles y denunciar problemas en código
* Uso de pull requests (PR) para proponer cambios de código entre repositorios
  * Comunicación entre desarrolladores / estudiantes y admins / profesores
  * Historial de cambios en repositorios y atribuciones de autoría por PRs
  * Manejo de códigos y versiones en conflicto

## Asistentes

1. Darío
2. X
3. X
4. X
5. X
6. X
7. X
8. X
9. X
10. X

## Uso de forks para distribuir contenidos entre muchos usuarios

Antes de hablar de forks, hablemos de branches. Las branches son una forma de crear en el mismo repositorio una copia del código, para trabajar en paralelo.

Muchas veces estos forks son necesarios para que múltiples personas trabajen en subproyectos distintos y en paralelo, sin afectar el código de producción, que es el visible a los usuarios finales.

Para hacer una branch tienes que ser admin del repositorio, entonces generalmente

Los forks son una herramienta de GitHub que permite a los usuarios crear copias de un repositorio en sus cuentas, para así poder trabajar de forma independiente sin afectar el repositorio original de forma directa.

En proyectos grandes, generalmente hay una branch principal, que hoy en día se llama `main`, y una branch de desarrollo, que hoy en día se llama `develop`. Una práctica común es que la branch `main` no se edite directamente, sino que se hagan cambios y pruebas en la branch `develop`, y cuando estos se quieran publicar, se propaguen esos cambios a la branch `main`.

En nuestros ejemplos de hoy solamente aprenderemos que las branches existen, y que son una herramienta de GitHub útil, pero no profundizaremos en su uso. Eso sí, un error común actual de principiantes es crear branches sin querer, lo que haremos y repararemos hoy.

### Qué es un fork y cuál es la relación con el repositorio original

Un fork es una copia del repositorio original, en otra cuenta / de otro dueño, que permite creditar y apuntar al repositorio original.

Usos de forks:

* Múltiples personas trabajan en un mismo proyecto, pero cada uno tiene su propia copia del código, y no pueden propagar cambios entre repositorios, a no ser que lo hagan explícitamente.
* Hay un repositorio original, que está abandonado, y se quiere continuar el proyecto, pero no se tiene acceso al repositorio original. En este caso, puedes hacer un fork del repositorio original, y continuar el proyecto en el fork. De hecho muchos proyectos han partido así, como forks de un proyecto original, como Arduino que partió como un fork de Wiring.
* Hay una organización o un curso, y el equipo directivo o docente tiene un repositorio, y distribuye tareas a colaboradores o estudiantes, que trabajan en sus propios forks, y luego proponen cambios al repositorio original. Otra opción es que el equipo docente o directivo revise los forks de forma periódica, e integre los cambios de los forks al repositorio original, o los rechaza.

### Cómo múltiples personas pueden trabajar en forks distintos

El repositorio original no puede hacer cambios en el fork, y viceversa tampoco: el fork no puede hacer cambios en el repositorio original.

Forks apuntan al repositorio del cuál se originaron.

Pueden haber múltiples forks de un mismo repositorio, y cada fork puede tener múltiples branches.

### Cómo un admin puede administrar la complejidad de las redes de forks

Los admins de un repositorio pueden navegar los forks, revisar los cambios, proponer, aceptar o rechazar cambios.

En la práctica de Piruetas, los forks incluyen carpetas distintas para cada estudiante. Los estudiantes hacen un fork del repositorio compartido, y cada estudiante trabaja exclusivamente en su propia carpeta, para así evitar que existan conflictos de código. Revisar los repositorios de <https://github.com/disenoUDP> y sus redes de colaboración.

## Uso de issues para discutir mejoras y errores en repositorios y código

Puedes crear templates de issues para reportar errores y mejoras, y para automatizar procesos.

estos templates se hacen en la carpeta especial '.github/ISSUE_TEMPLATE'.

Un ejemplo de esto es lo creado en este repositorio, revisemos esa carpeta.

Ojo que un archivo en general tiene las siguientes secciones, de izquierda a derecha:

* nombre del archivo
* caracter punto
* extensión del archivo

Una práctica riesgosa que no recomendamos es incluir los siguientes caracteres prohibidos en nombres de archivos:

```python
# caracteres prohibidos en nombres de archivos
caracteresProhibidos = [
    '/', '\\', ':', '*', '?', '"', '<', '>', '|', '\n', '\r', '\t', 'á, é, í, ó, ú, ñ, ü, Á, É, Í, Ó, Ú, Ñ, Ü'
]
```

### Comunicación profesional y efectiva entre programadores y admins

etiquetar con arroba.

pedir ayuda a otras personas.

distribuir secciones de un repositorio entre admins.

### Uso de lenguaje unívoco / no ambiguo para describir problemas y conflictos

esto ocurre en este lugar, de micro a macro:

* en estas líneas
* en este archivo
* en este commit
* en esta branch
* en este repositorio

### Uso de issues para asignar roles y denunciar problemas en código

las issues pueden tener:

* etiquetas
* asignaciones a personas
* estar asociadas a proyectos
* ser el inicio de una discusión

## Uso de pull requests (PR) para proponer cambios de código entre repositorios

Las pull requests son una forma de proponer cambios entre branches y repositorios.

Se pueden proponer en un mismo repositorio entre branches, o entre forks.

### Comunicación entre desarrolladores / estudiantes y admins / profesores

Puedes crear Teams en una GitHub organization.

En una organización podemos tener

### Historial de cambios en repositorios y atribuciones de autoría por PRs

Coreografía de proponer cambios en una issue, y resolverla con una pull request.

### Manejo de códigos y versiones en conflicto

En Visual Studio code, puedes ver los conflictos de código y resolverlos.
