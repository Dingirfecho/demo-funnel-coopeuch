# Demo animada · Funnel de reclutamiento

Página única (`index.html`), sin dependencias ni build. Solo usa Google Fonts por CDN (si no carga, cae a tipografías del sistema).

## Publicar en GitHub Pages
1. Crear un repositorio (recomendado: uno nuevo, p. ej. `demo-funnel`, o una carpeta `/demo-funnel` en el repo del sitio).
2. Subir `index.html` (y este README).
3. Settings → Pages → Source: `Deploy from a branch` → rama `main`, carpeta `/ (root)` → Save.
4. En 1–2 minutos queda en `https://<usuario>.github.io/<repo>/`.

## Notas
- Datos 100 % ficticios; no incluye el nombre del cliente. Repositorios públicos son públicos: no subir material del cliente.
- La página lleva `noindex`, pero la URL es accesible para quien la tenga. Para acceso restringido, usar repo privado (requiere plan que habilite Pages privadas) o compartir el archivo.
- Controles: espacio = pausa, ← → = etapas, botón de velocidad 1x/1.5x/2x.
- Parámetros de prueba: `?s=5&t=6000&pause=1` abre la etapa 5 en el segundo 6 pausada.
- Respaldo para la reunión: abrir el archivo local `index.html` en el navegador (funciona sin internet).
