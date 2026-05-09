# GanaderoAI — Landing Page

> **Smarter Livestock. Stronger Farms.**
> Plataforma inteligente de gestión ganadera. Multi-finca, multi-modelo, sin formularios.

Sitio web institucional y comercial de **GanaderoAI**, producto de [HenkanCX](https://henkancx.com) para el sector ganadero.

---

## 🌐 Stack

- HTML + CSS + JS vanilla, **single-file** (`index.html`)
- Tipografía: Inter (sustituto libre de Neue Haas Grotesk Display) + Source Sans 3 vía Google Fonts
- Logo SVG inline + archivo independiente (`logo-ganaderoia.svg`) para uso en otros contextos
- Sin build step, sin dependencias, sin frameworks

## 🎨 Identidad

| Token | Hex | Uso |
|---|---|---|
| Sage Field | `#6B7D5A` | Naturaleza, ECG, acentos rurales |
| Soil Dark | `#2C2416` | Texto, fondos oscuros, logo |
| Cloud | `#EEF0EB` | Fondos del app |
| Digital Blue | `#3A68A4` | Tagline secundario, datos |
| Harvest Amber | `#BF7A2A` | CTAs, alertas, warm accent |

Tipografía oficial: **Neue Haas Grotesk Display** (titulares) + **Source Sans 3** (cuerpo).
En este repo se usa **Inter** como sustituto libre — reemplazar por self-hosted Neue Haas cuando esté licenciada.

Taglines oficiales:
- `Smarter Livestock. Stronger Farms.`
- `Data. Decisions. Performance.`

## 🚀 Deploy

### Opción A — GitHub Pages (recomendado para landing estática)

```bash
# Settings → Pages → Source: Deploy from branch → main / root
```

Para usar dominio custom (`ganaderoai.com`):

1. Crear archivo `CNAME` en la raíz con contenido: `ganaderoai.com`
2. En el DNS del dominio, apuntar al IP de GitHub Pages o `henkancx.github.io`
3. En Settings → Pages → Custom domain → escribir `ganaderoai.com`

### Opción B — Vercel / Netlify

Drag & drop la carpeta o conectar el repo. Build command: ninguno. Output dir: `/`.

## 📁 Estructura

```
.
├── index.html              # Landing single-file
├── logo-ganaderoia.svg     # Logo oficial vectorial (asset)
├── README.md
└── .gitignore
```

## 🔄 Próximos pasos

- [ ] Reemplazar `logo-ganaderoia.svg` con la versión vectorial oficial del brand book (la actual es aproximación)
- [ ] Sustituir Inter por Neue Haas Grotesk Display self-hosted cuando esté licenciada
- [ ] Comprar `ganaderoai.com` y configurar DNS + CNAME
- [ ] Agregar OG image (1200×630) para sharing en redes
- [ ] Agregar formulario real (HubSpot / Zapier / Formspree) en lugar del `alert()` placeholder
- [ ] Sección de pricing cuando esté definida
- [ ] Versión `/en` para mercados internacionales

## 📞 Contacto

**HenkanCX**
Andrea Nava — info@henkancx.com — +507 6467 1392
Ciudad de Panamá

---

© 2026 GanaderoAI · Powered by [HenkanCX](https://henkancx.com)
