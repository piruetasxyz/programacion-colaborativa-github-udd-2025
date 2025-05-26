# 2025-05-26

Programación colaborativa en GitHub, sobre los fundamentos de la programación colaborativa en repositorios.

Curso inicial de 3 horas.

Para X estudiantes.

## Contenido

* Repositorios en la nube para programación colaborativa
  * Historia del uso de git y terminologías sobre repositorios
  * Git en tu computador, GitHub en la nube
  * Alternativas al ecosistema GitHub, como GitLab y otras
* Lenguaje MarkDown para documentación técnica y bitácoras
  * Etiquetado con Markdown y comparación con HTML
  * Uso de Markdown en sabor GItHub (GFM) y sus addons
  * Uso de Markdown para documentación multimedia
* Deployment de páginas web alojadas en repositorios GitHub
  * Convertir un repositorio en una página web estática gratuita
  * Aumentar las posibilidades de Markdown con HTML
  * Aumentar las posibilidades de Markdown con CSS y con Jekyll
* Técnicas para alojar, versionar y programar de forma colaborativa
  * Versionamento semántico v0.0.1
  * Estrategias para colaborar entre estudiantes de un curso
  * Navegar historial de avances del curso para revisiones asíncronas

## Asistentes

## Repositorios en la nube para programación colaborativa

### Historia del uso de git y terminologías sobre repositorios

Git fue lanzado el año 2005 por Linus Torvalds <https://en.wikipedia.org/wiki/Git>.

Una carpeta con archivos, que usa el control de versiones de Git, le llamamos "repositorio" o "repo".

Un repositorio puede estar en tu computador, y/o en la nube.

Entonces la ecuación es

$$carpeta + git = repositorio$$

### Git en tu computador, GitHub en la nube

En tu computador, puedes instalar Git desde la web <https://git-scm.com/>.

Para computadores con sistemas MacOS, recomiendo instalar Git y cualquier otra herramiente de línea de comandos usando el gestor de paquetes Homebrew <https://brew.sh/>.

En este curso usaremos GitHub, que es un servicio de administración y hosting de repositorios hechos con Git, lanzada el año 2008, y ahora parte de Microsoft <https://en.wikipedia.org/wiki/GitHub>.

### Alternativas al ecosistema GitHub, como GitLab y otras

GitLab es otra plataforma de hosting de repositorios Git <https://en.wikipedia.org/wiki/GitLab>, también está Bitbucket <https://en.wikipedia.org/wiki/Bitbucket>.

El fablab de UChile está en GitLab <https://gitlab.com/fablab-u-de-chile>, y también el software Kicad <https://gitlab.com/kicad>.

En los 2000s y 2010s ganaron mucha popularidad otros sitos como SourceForge <https://en.wikipedia.org/wiki/SourceForge> y Google Code <https://en.wikipedia.org/wiki/Google_Developers>, pero ya no tienen la misma popularidad.

## Lenguaje MarkDown para documentación técnica y bitácoras

Markdown es un lenguaje ligero de etiquetado, que permite escribir texto "on the fly", que es directamente legible, y que se puede transpilar a otros formatos, como HTML <https://en.wikipedia.org/wiki/Markdown>.

En el 2017 GitHub lanzó su propia variante de Markdown, llamada GFM (GitHub Flavored Markdown) <https://github.github.com/gfm/>, que incluye extensiones para tablas, el anuncio aquí <https://github.blog/engineering/a-formal-spec-for-github-markdown/>

### Etiquetado con Markdown y comparación con HTML

```md
# ejemplo de Título
```

### Uso de Markdown en sabor GItHub (GFM) y sus addons

### Uso de Markdown para documentación multimedia

Para agregar imágenes:

Para agregar animaciones en formato .gif:

Para agregar videos:

## Deployment de páginas web alojadas en repositorios GitHub

En Settings -> GitHub Pages

### Convertir un repositorio en una página web estática gratuita

### Aumentar las posibilidades de Markdown con HTML

Agregar videos.

### Aumentar las posibilidades de Markdown con CSS y con Jekyll

CSS es un lenguaje de estilos.

Jekyll es un generador de sitios estáticos, hechos con el lenguaje Ruby.

## Técnicas para alojar, versionar y programar de forma colaborativa

### Versionamento semántico v0.0.1

Tenemos 3 distintos números en semver:

1. **Mayor**: Cambios incompatibles con versiones anteriores.
2. **Menor**: Cambios compatibles con versiones anteriores.
3. **Parche**: Cambios compatibles con versiones anteriores, pero que no cambian la API.

En piruetas, pensamos los números de derecha a izquierda:

- El tercer número (parche) lo aumentamos en 1 cuando encontrams un error, y lo resolvemos. Como publicamos frecuentemente borradores, estos van aumentando rápidamente este número.

- El segundo número (menor) lo aumentamos en 1 cuando lanzamos un conjunto de implementaciones o interfaces que aumntan el funcionamiento.

- El tercer número (mayor) lo aumentamos en 1 cuando lanzamos una versión importante, que rompe o cambia funcionamientos anteriores.

Cuando uno de los números sube en 1, resetea a 0 los que están a su derecha.

### Estrategias para colaborar entre estudiantes de un curso

Proponemos que exista un repo principal, y que cada estudiante tenga su propio fork de este repo.

Para evitar conflictos entre estudiantes, recomendamos que cada estudiante trabaje en su propio fork, y que tenga su propia carpeta de trabajo, para que no existan posibles conflictos entre estudiantes mientras colaboran en archivos.

### Navegar historial de avances del curso para revisiones asíncronas
