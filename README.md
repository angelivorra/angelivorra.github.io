# angelivorra.github.io

Sitio raíz del dominio GitHub Pages. Su única función hoy es:

1. Servir `/.well-known/assetlinks.json` para verificar la app Android (TWA)
   de ROBOTRACA (Digital Asset Links).
2. Redirigir la raíz a la app: `/robotraca/robotraca/`.

**IMPORTANTE:** tras subir el .aab a Google Play y activar Play App Signing,
añade el SHA-256 del *App signing key* de Play al array
`sha256_cert_fingerprints` de `.well-known/assetlinks.json`.
