# Mi portafolio

Portafolio personal de **José Santos Aguilar Cruz**, hecho con HTML y CSS puro
(sin frameworks ni dependencias). Se publica como sitio estático en Vercel.

## Archivos

| Archivo | Para qué sirve |
| --- | --- |
| `index.html` | Contenido y estructura de la página |
| `style.css` | Colores, tipografía y diseño responsive |
| `README.md` | Este archivo |

## Cómo verlo en tu computadora

1. Abre la carpeta `mi-portafolio` en VS Code (`Archivo → Abrir carpeta`).
2. Haz doble clic en `index.html`, o clic derecho → **Reveal in File Explorer** →
   abrir con el navegador.
3. Opcional: instala la extensión **Live Server** y pulsa "Go Live" para ver los
   cambios al instante.

## Qué editar

- **Nombre, rol y ubicación:** en `index.html`, dentro de `<header class="portada">`.
- **Foto:** guarda tu imagen en `assets/foto.jpg` y sigue el comentario que está
  junto al `<div class="avatar">`.
- **Sobre mí, habilidades y proyectos:** cada bloque tiene un comentario
  `✏️ EDITA`.
- **Colores:** variables al inicio de `style.css` (`--color-acento`, etc.).

## Subir cambios (flujo continuo)

Cada vez que edites algo:

```bash
git status                  # ver qué cambió
git add .                   # preparar todos los cambios
git commit -m "Describe tu cambio"
git push                    # subir a GitHub (Vercel redespliega solo)
```

En VS Code puedes hacer lo mismo desde el panel **Source Control**:
`+` (Stage All) → mensaje → `✓ Commit` → **Sync Changes**.

## Publicarlo en internet (GitHub + Vercel)

1. **GitHub:** en VS Code, panel **Source Control** → menú `...` →
   **Publish Branch** → inicia sesión → nombre del repo `mi-portafolio` →
   **Public**.
2. **Vercel:** entra a <https://vercel.com>, **Sign Up → Continue with GitHub**
   y elige el plan **Hobby**.
3. **Add New → Project** → importa `mi-portafolio` → **Deploy**.
4. Vercel te da una URL tipo `https://mi-portafolio-tu-usuario.vercel.app`.
   Puedes cambiarla en **Settings → Domains**.

Desde ese momento, cada `git push` a `main` publica los cambios
automáticamente.
