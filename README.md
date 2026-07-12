# Glossy Glow Studio — sitio web

Sitio estático (HTML/CSS/JS, sin build) para **Glossy Glow Studio** — estudio de belleza en
Xalapa: alaciados orgánicos libres de vapores tóxicos, rutinas curly, tratamientos capilares y nails.

Diseño premium dark + dorado, **mobile-first**, con un tour 3D en el banner que avanza
por el estudio mientras haces scroll. Construido siguiendo los principios de UX/UI
"Aurora UI" de NEXO Core (mobile first, accesibilidad AA, `prefers-reduced-motion`,
microanimaciones discretas). No requiere backend ni Supabase: es 100% vista al cliente.

## Estructura

```
index.html
_headers              # cabeceras de seguridad y caché (Cloudflare Pages)
assets/
  css/styles.css
  js/main.js
  img/                # logo SVG + fotos reales del salón
```

## Desarrollo local

Abre `index.html` en el navegador, o sirve la carpeta:

```bash
npx serve .
```

## Deploy en Cloudflare Pages

1. Sube este repositorio a GitHub.
2. En Cloudflare Pages → **Create project** → conecta el repo.
3. Build settings:
   - **Framework preset:** None
   - **Build command:** *(vacío)*
   - **Build output directory:** `/`
4. Deploy. Cada `git push` a `main` redeploya automáticamente.

## Contacto del negocio

- WhatsApp (previa cita, solo por WhatsApp): 228 235 3941 — [wa.me/522282353941](https://wa.me/522282353941)
- Instagram: [@glossyglowstudio.mx](https://instagram.com/glossyglowstudio.mx)
- Facebook: Glossy Glow Studio
- Av. Araucarias, Xalapa-Enríquez, Ver.
- Horario: Lun–Sáb · 10:00–19:00
