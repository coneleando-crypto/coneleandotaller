# Tu página web a la altura de tus clases — Landing

Landing page del taller en vivo para profes de ELE, parte de **ConELEando**.

Vende el taller "Tu página web a la altura de tus clases": 2 horas en vivo, con acompañamiento de un desarrollador, para que profes de español con experiencia construyan su propia página web.

## Cómo está armada

Es un único archivo, `index.html`, sin dependencias externas más que las fuentes de Google Fonts. La foto de portada está incrustada dentro del mismo archivo (en base64), así que no hay carpetas de imágenes sueltas que se puedan perder al subir o mover el sitio.

## Antes de publicar

Hay que reemplazar el placeholder `TU-LINK-AQUI` por el link real de reserva. Aparece **dos veces** en el código:

- Botón "Reservar mi cupo — $20" (hero, arriba de la página)
- Botón "Reservar mi cupo ahora" (CTA final, sección morada oscura)

Búscalo con `Ctrl+F` / `Cmd+F` en el editor y reemplázalo en ambos lugares.

## Cómo publicarla

### Opción 1 — GitHub Pages (esta, si el repo ya está en GitHub)
1. Ve a **Settings → Pages** del repositorio.
2. En "Build and deployment" → "Source", elige **Deploy from a branch**.
3. Branch: **main**, carpeta **/ (root)** → **Save**.
4. En 1-10 minutos, el sitio queda disponible en `https://tu-usuario.github.io/nombre-del-repo/`.

### Opción 2 — Netlify Drop (más rápido, sin cuenta)
1. Ve a [app.netlify.com/drop](https://app.netlify.com/drop).
2. Arrastra el archivo `index.html`.
3. En segundos te da un link tipo `algo-al-azar.netlify.app`.
4. **Importante:** si no reclamas el sitio (`/claim`, registro gratis) en 24 horas, Netlify lo borra.

## Actualizar contenido

Edita `index.html` directamente:
- Desde GitHub: ícono de lápiz sobre el archivo → editar → **Commit changes**.
- En local: cualquier editor de texto plano (VS Code, Notepad, TextEdit en modo texto plano) → guardar → volver a subir/hacer commit.

Los cambios tardan un par de minutos en verse reflejados en el link publicado.

## Identidad de marca usada

**Colores**
| Uso | Color | Hex |
|---|---|---|
| Fondo base | papel | `#FFFDF5` |
| Títulos / acento principal | violeta | `#7F4AA4` |
| Fondos oscuros (CTA final) | violeta oscuro | `#4B2A63` |
| Texto de cuerpo | negro | `#1A1A1A` |
| Acentos secundarios, subrayados | azul | `#38B6FF` |
| Acento sobre fondo oscuro únicamente | amarillo | `#FBEE0F` |

**Tipografías**
- Fraunces — títulos
- Caveat — notas manuscritas
- Public Sans — cuerpo de texto
- IBM Plex Mono — etiquetas y micro-textos

## Créditos

Foto: Lorena, fundadora de ConELEando y de You en Español.
