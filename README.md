# Portafolio · Nicolás Texeira Rovira

Web personal con mi CV. Un solo `index.html`, sin dependencias ni build.

## Publicarlo con GitHub Pages

1. Crea un repo nuevo en GitHub. Si lo llamas `TU_USUARIO.github.io`, la web quedará en `https://TU_USUARIO.github.io`. Con cualquier otro nombre quedará en `https://TU_USUARIO.github.io/NOMBRE_DEL_REPO`.
2. Sube estos archivos a la raíz del repo: `index.html`, `cv.pdf` y este `README.md` (botón **Add file → Upload files**).
3. Ve a **Settings → Pages**, en *Source* elige **Deploy from a branch**, rama `main`, carpeta `/ (root)`, y guarda.
4. En uno o dos minutos la web estará online en la dirección que te muestra esa misma página.

## Personalizar

- **GitHub y proyectos:** abre `index.html`, busca `const GITHUB_USER = "";` y pon tu usuario entre las comillas. Aparecerá el botón de GitHub y una sección *Proyectos* con tus 6 repos públicos más recientes, que se actualiza sola.
- **Actualizar el CV:** sustituye `cv.pdf` por la versión nueva con el mismo nombre.
- **Colores:** están al principio del `<style>`, en `:root` (`--ink` es el fondo y `--teal` el acento).
