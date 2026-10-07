# PinaTube — versión GitHub Pages (estática)

GitHub Pages **no corre PHP**, por eso esta versión es 100% HTML + JavaScript.
No hay panel admin: los videos se agregan editando `videos.json`.

## Cómo agregar un video
1. Sube el archivo `.mp4` a la carpeta `videos/` (y la miniatura si quieres).
2. Agrega una entrada en `videos.json`:
```json
{
  "title": "Mi video",
  "description": "Descripción (opcional)",
  "file": "videos/mi-video.mp4",
  "poster": "videos/mi-video.jpg"
}
```
3. Haz commit + push. Listo.

## Publicar en GitHub Pages
1. Crea un repo en GitHub y sube estos archivos.
2. Ve a **Settings → Pages** → Source: **Deploy from a branch** → Branch: **main** → **Save**.
3. Tu sitio quedará en `https://TU-USUARIO.github.io/TU-REPO/`.

## Límites
- Cada archivo en GitHub: máximo **100 MB** (tus videos de ~3-12 MB están bien).
- GitHub Pages: ~100 GB de transferencia al mes (de sobra para uso personal).
