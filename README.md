# Psicotuluz · Sitio web

Sitio web de presentación de **Psicotuluz** — psicoterapia online para mujeres
profesionales agotadas por la autoexigencia. Fundadora: Lic. Agustina Acuña.

## Contenido
- `index.html` — sitio completo (una sola página, sin dependencias de build).
- `assets/` — logo e íconos (favicon).

El logo del navbar y los favicons también van incrustados en el HTML, así que el
sitio funciona aunque la carpeta `assets/` no esté presente. Los archivos de
`assets/` se incluyen por si preferís enlazarlos externamente o reutilizarlos.

## Cómo verlo localmente
Abrí `index.html` en cualquier navegador (doble clic). No requiere servidor.

## Publicar con GitHub Pages
1. Subí estos archivos a un repositorio.
2. En el repo: **Settings → Pages**.
3. En *Source* elegí la rama `main` y la carpeta `/ (root)`.
4. Guardá. En unos minutos el sitio queda online en
   `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Pendientes antes de salir a producción
- **Dominio en SEO:** en el `<head>` las etiquetas usan `https://www.psicotuluz.com/`
  como ejemplo. Reemplazá por el dominio real (también en `og:image`).
- **Nombres de los testimonios en audio:** las 4 tarjetas de audio tienen
  `— Consultante` como marcador. Reemplazá por el nombre de cada persona
  (figura en el título de cada archivo de Drive).
- **Permisos de Drive:** cada audio se reproduce embebido solo si está como
  "cualquiera con el enlace puede ver".
- **Fotos del equipo:** los avatares y el retrato de Agustina están listos para
  imagen (buscá los comentarios `<!-- RETRATO -->` / `<!-- AVATAR -->` en el HTML).

---
Sitio desarrollado por **RGS · Rebel Grid Systems**.
