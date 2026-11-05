# Premier Cosmetics — despliegue en Vercel

Sitio estático, sin build.

1. Sube esta carpeta a un repositorio de GitHub (o usa `npx vercel` dentro de la carpeta).
2. En Vercel: New Project → importa el repo → Framework Preset: **Other** → sin Build Command → Output Directory: `.`
3. Deploy. La raíz `/` abre `Premier Inicio.dc.html` (ver `vercel.json`).

Para reemplazar un video, sube el nuevo archivo con el mismo nombre en `assets/` y vuelve a desplegar.
