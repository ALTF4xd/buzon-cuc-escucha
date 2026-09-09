# Evidencias - Fase 1: Entorno local e inicialización de Git

**Proyecto:** Buzón CUC Escucha
**Asignatura:** Buenas Prácticas de Desarrollo de Software
**Docente:** Ing. Lorena Redondo G.
**Fecha de inicio:** 9 de septiembre de 2026
**Ubicación local:** `C:\Users\luis\Desktop\Skills\materiales\buenas-practicas-desarrollo\buzon-cuc-escucha`

## Alcance de esta fase

Esta primera fase deja creada la estructura local del micrositio, sus archivos base, el repositorio Git y el registro verificable de las acciones realizadas. La configuración de identidad y el primer commit dependen de contar con un correo institucional confirmado para no registrar datos incorrectos en el historial público.

## Registro cronológico

| Paso | Acción realizada | Comando o medio empleado | Resultado |
| --- | --- | --- | --- |
| 1 | Se identificó la carpeta oficial de materiales de la asignatura. | Exploración de `materiales/buenas-practicas-desarrollo`. | Se confirmó que no existía un proyecto previo con este nombre. |
| 2 | Se creó la carpeta raíz del proyecto. | `mkdir buzon-cuc-escucha` | Carpeta raíz creada dentro de los materiales de la asignatura. |
| 3 | Se crearon los directorios requeridos. | `mkdir css js img` | Estructura base lista para HTML, estilos, JavaScript e imágenes. |
| 4 | Se incorporaron los archivos iniciales. | Edición de `index.html`, `css/styles.css`, `js/app.js` y `README.md`. | Micrositio base con formulario semántico y estilos responsivos. |
| 5 | Se creó este registro de evidencias. | Edición de `EVIDENCIAS_FASE_1.md`. | Bitácora incluida dentro del repositorio para mantener trazabilidad. |
| 6 | Se inicializó el repositorio local. | `git init` | Repositorio vacío creado en la carpeta del proyecto. |
| 7 | Se estableció la rama principal. | `git branch -M main` | Rama principal nombrada como `main`. |
| 8 | Se verificó el estado inicial. | `git status --short` | Cinco elementos sin seguimiento antes de staging. |
| 9 | Se agregaron los archivos al área de preparación. | `git add .` | Cinco elementos preparados para el commit inicial. |
| 10 | Se configuró la identidad de Git para este repositorio. | `git config --local user.name` y `git config --local user.email` | Commit firmado localmente como `Luis_Jimenez`; la configuración global no fue modificada. |
| 11 | Se creó el commit inicial. | `git commit -m "feat: inicializar estructura y maquetacion base del buzon CUC"` | Commit raíz `d07311f` creado en `main`. |

## Estructura resultante

```text
buzon-cuc-escucha/
├── css/
│   └── styles.css
├── img/
├── js/
│   └── app.js
├── EVIDENCIAS_FASE_1.md
├── index.html
└── README.md
```

## Evidencia de Git registrada

```bash
$ git init
Initialized empty Git repository in C:/Users/luis/Desktop/Skills/materiales/buenas-practicas-desarrollo/buzon-cuc-escucha/.git/

$ git branch -M main

$ git status --short
?? EVIDENCIAS_FASE_1.md
?? README.md
?? css/
?? index.html
?? js/

$ git add .

$ git status --short
A  EVIDENCIAS_FASE_1.md
A  README.md
A  css/styles.css
A  index.html
A  js/app.js
```

Git informó que los archivos de texto podrían normalizarse de LF a CRLF en Windows. Es una advertencia habitual de finales de línea, no un error de preparación ni de contenido.

## Evidencia del commit inicial

La identidad de Git quedó configurada de forma local para este repositorio y se creó el primer commit:

```bash
git config --local user.name "Luis_Jimenez"
git config --local user.email "lj245956@gmail.com"

git commit -m "feat: inicializar estructura y maquetacion base del buzon CUC"
[main (root-commit) d07311f] feat: inicializar estructura y maquetacion base del buzon CUC
 5 files changed, 376 insertions(+)

git log --oneline
d07311f feat: inicializar estructura y maquetacion base del buzon CUC
```

Después del commit, `git status --short` no mostró archivos pendientes.

## Capturas requeridas por la rúbrica

- Captura 1.1: creación de carpetas, archivos, `git init` y `git branch -M main`.
- Captura 1.2: archivos sin seguimiento antes de `git add .` y en staging después del comando.
- Captura 1.3: commit inicial y salida de `git log --oneline`.

Las capturas nativas de Git Bash deben tomarse durante la ejecución para incorporarlas posteriormente al PDF final de Moodle.
