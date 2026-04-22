# HolaRSVP

Landing page estática para [holarsvp.ar](https://holarsvp.ar).

Servicio de confirmaciones de asistencia a eventos por WhatsApp.

## Stack

- HTML + CSS estático (sin build step)
- Hosteado en Cloudflare Pages
- DNS en Cloudflare
- Fuentes: Playfair Display + Inter (Google Fonts)

## Estructura

- `index.html` — landing principal
- `privacidad.html` — política de privacidad
- `terminos.html` — términos de uso
- `styles.css` — estilos compartidos

## Deploy

Cada push a `main` dispara un deploy automático en Cloudflare Pages.
