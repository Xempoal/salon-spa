# Aurora Salón — sitio web

Sitio estático (HTML/CSS/JS, sin build) para **Aurora Salón** — salón consciente en
Xalapa: balayage, efectos de color, corte, tratamientos capilares y extensiones.

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

- WhatsApp / Tel: 228 145 6070
- Instagram: [@aurorasalon](https://instagram.com/aurorasalon)
- Av. Murillo Vidal 312, Fracc. Pomona, 91040 Xalapa-Enríquez, Ver.
