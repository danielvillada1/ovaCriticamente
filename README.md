# CríticaMente · OVA de pensamiento crítico

Objeto Virtual de Aprendizaje (OVA) interactivo para estudiantes de primer semestre de la **Universidad de Nariño**, desarrollado en el programa de **Licenciatura en Informática**.

Fases: Preguntar · Analizar · Verificar · Argumentar y Decidir · Reto final · Autoevaluación.

## Contenido del repositorio

| Archivo | Descripción |
|---|---|
| `index.html` | El OVA completo (HTML, CSS, JavaScript e ilustraciones SVG integradas en un solo archivo). |
| `.nojekyll` | Indica a GitHub Pages que sirva el sitio tal cual, sin procesarlo con Jekyll. |
| `.gitignore` | Archivos que Git debe ignorar. |
| `README.md` | Este documento. |

No necesita instalación ni compilación. Las ilustraciones son SVG dentro del propio `index.html`. Solo requiere internet para cargar las tipografías de Google Fonts y el video de introducción de YouTube.

## Cómo subirlo a GitHub

1. Crea un repositorio nuevo en <https://github.com/new> (por ejemplo `ova-criticamente`), sin README ni .gitignore.
2. Descomprime el ZIP y, desde la carpeta `ova-criticamente`, ejecuta:

```bash
git init
git add .
git commit -m "Primera versión del OVA CríticaMente"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/ova-criticamente.git
git push -u origin main
```

(Sin terminal: en el repositorio vacío elige **uploading an existing file** y arrastra todos los archivos, incluido `.nojekyll`.)

## Publicarlo con GitHub Pages

1. En el repositorio ve a **Settings → Pages**.
2. En **Build and deployment → Source** elige **Deploy from a branch**.
3. Selecciona la rama `main` y la carpeta `/ (root)`, y pulsa **Save**.
4. En uno o dos minutos estará disponible en `https://TU-USUARIO.github.io/ova-criticamente/`.

## Créditos

Creadores: Daniel Trejo Villada y Albert Jesús Vargas. Universidad de Nariño · Licenciatura en Informática. Fuentes e ilustraciones: ver el apartado *Referencias* dentro del OVA.
