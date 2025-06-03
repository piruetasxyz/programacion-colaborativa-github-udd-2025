# 2025-06-04

Programación colaborativa en GitHub, sobre la administración de repositorios para organizaciones educacionales en GitHub.

Curso avanzado de 3 horas.

Para X estudiantes.

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

## Uso de forks para distribuir contenidos entre muchos usuarios

### Qué es un fork y cuál es la relación con el repositorio original

Un fork es una copia del repositorio original, que permite creditar y apuntar al repositorio original.

### Cómo múltiples personas pueden trabajar en forks distintos

El repositorio original no puede hacer cambios en el fork, y viceversa tampoco: el fork no puede hacer cambios en el repositorio original.

Forks apuntan al repositorio del cuál se originaron.

Pueden haber múltiples forks de un mismo repositorio, y cada fork puede tener múltiples branches.

### Cómo un admin puede administrar la complejidad de las redes de forks

Los admins de un repositorio pueden navegar los forks, revisar los cambios, proponer, aceptar o rechazar cambios.

En la práctica de Piruetas, los forks incluyen carpetas distintas para cada estudiante. Los estudiantes hacen un fork del repositorio compartido, y cada estudiante trabaja exclusivamente en su propia carpeta, para así evitar que existan conflictos de código.

## Uso de issues para discutir mejoras y errores en repositorios y código

Puedes crear templates de issues para reportar errores y mejoras, y para automatizar procesos.

estos templates se hacen en la carpeta especial '.github/ISSUE_TEMPLATE'.

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
