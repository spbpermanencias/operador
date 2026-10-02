# Operador – Citas (PWA)

Sube estos archivos a la RAÍZ del repo (todos al mismo nivel, sin carpetas):
`index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`, `.nojekyll`.
Settings → Pages → `main` → `/ (root)`.

- Usa el mismo Supabase de permanencias.html (SB_URL y SB_KEY ya vienen dentro de index.html).
- Solo entran usuarios cuyo rol tenga marcado "PWA del Operador" (o administradores).
- Muestra las citas del día sin tiempos: placa, operador, hora de cita, cantidad por BL y etapa.
- Si ya existe otra PWA en el mismo repo, usa un repo nuevo o una carpeta (por ejemplo `/operador/`): las rutas son relativas y funcionan igual.
