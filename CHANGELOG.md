# Changelog

Todos los cambios notables de este repositorio se documentan en este archivo.

El formato está basado en [Keep a Changelog](https://keepachangelog.com/es-ES/1.1.0/)
y este proyecto adhiere a [Versionado Semántico](https://semver.org/lang/es/).

## [Sin publicar]

### Añadido

- Carpeta `PROMPTs/` con la documentación de prompts del proyecto:
  - `PROMPTs/Creacion-Prompt.md`: prompt para crear una auditoría técnica de
    seguridad sobre un sitio web, reutilizando o creando los elementos
    necesarios (rules, rulesets, profile).
  - `PROMPTs/Refactorizacion.md`: prompt para refactorizar y agrupar los prompts
    del repositorio, ajustando las referencias internas.
  - `PROMPTs/Refactorizando-Repo-Nombre.md`: prompt para actualizar las
    referencias internas tras el renombrado del repositorio
    `IA.Prompting.Templates` a `IA.Prompts.Documentos` y su traslado a `/IA`.
- `CHANGELOG.md` para el registro de cambios del repositorio.
- Carpeta `Tareas/` con `Tareas/Mis-Tareas.md`, listado de tareas pendientes
  sobre la detección de derivación de agentes durante las etapas de SDD y de
  codeo.
- `PROMPTs/03-Crear-Analisis-Relevamientos/Crear-Analisis-Relevamientos.md`:
  prompt para analizar el tamaño de video y su visualización con VLC sobre un
  proyecto con múltiples versiones.
- Carpeta `Analisis/` (con `.gitkeep`) para alojar los análisis y relevamientos
  generados.
- `Analisis/Metologia-Base-Vectorial-Vs-IA-DB/Metologia-Base-Vectorial-Vs-IA-DB.md`
  (v1.0, 2026-09-13): análisis que compara la ia-db generada por
  `Iniciar-Indexado.md` con las bases vectoriales, los embeddings y el RAG;
  define los términos (modelo, ventana de contexto, token, embedding, arnés,
  índice simbólico), ubica la ia-db dentro del arnés, fija su finalidad, cuándo
  conviene cada enfoque, un modelo mixto e ideas abiertas.

### Cambiado

- Renombrado del repositorio de `IA.Prompts.Documentos` a
  `IA.Prompts.Documentacion`; se actualiza el título de `README.md`.
- Reorganización de `PROMPTs/` en subcarpetas numeradas por tipo de tarea:
  `Creacion-Prompt.md`, `Refactorizacion.md` y `Refactorizando-Repo-Nombre.md`
  pasan a `PROMPTs/01-Crear-Prompt/`, y se actualizan sus rutas de invocación al
  nuevo nombre del repositorio.
- `PROMPTs/Creacion-Prompt.md`, `PROMPTs/Refactorizacion.md` y
  `PROMPTs/Refactorizando-Repo-Nombre.md`: se añaden separadores `---` entre
  secciones para mejorar la legibilidad.
- `PROMPTs/Creacion-Prompt.md`: se anonimizan el dominio, las credenciales y las
  rutas de ejemplo (dominio, usuario y clave sustituidos por marcadores).
- `PROMPTs/Creacion-Prompt.md`, `PROMPTs/Refactorizacion.md` y
  `PROMPTs/Refactorizando-Repo-Nombre.md`: se añade una sección `Reglas` común
  que exige no inventar información y respaldar toda afirmación con evidencias
  verificables.

- `PROMPTs/03-Crear-Analisis-Relevamientos/` renumerada a
  `PROMPTs/02-Crear-Analisis-Relevamientos/`, sin cambios de contenido, para que
  la numeración de `PROMPTs/` quede contigua.

### Eliminado

- Carpeta `Tareas/` y su archivo `Tareas/Mis-Tareas.md`.

## [0.1.0] - 2026-07-16

### Añadido

- Commit inicial del repositorio.
- `README.md` con el título del proyecto.
- `.gitignore` inicial.
