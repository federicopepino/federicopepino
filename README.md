## Federico Andrés Pepino

Fundador y director de cuatro medios sectoriales que se actualizan solos.

Córdoba, Argentina

> Un dato sin fuente es un rumor. Un dato sin orden es ruido.

---

### Medios en producción

| Medio | Sector | Sitio |
|---|---|---|
| **El Gran Energético** | Petróleo, gas y Vaca Muerta | [el-gran-energetico.pages.dev](https://el-gran-energetico.pages.dev) |
| **El Gran Minero** | Litio, cobre, oro, plata y RIGI | [el-gran-minero.pages.dev](https://el-gran-minero.pages.dev) |
| **El Gran Ganadero** | Granos, hacienda y remates | [el-gran-ganadero.pages.dev](https://el-gran-ganadero.pages.dev) |
| **La Cuenca Láctea** | Lechería argentina | [la-cuenca-lactea.pages.dev](https://la-cuenca-lactea.pages.dev) |

Cada portal agrega noticias del sector con enlace a la fuente original, precios de referencia, proyectos, normativa, directorio de empresas y foro.

### Cómo funcionan

```
fuentes oficiales y medios del sector
        │   Boletín Oficial · SIACAM · rigi.ar · SIGLeA
        ▼
GitHub Actions ── corre solo, varias veces por día
        │
        ▼
Cloudflare Pages · Functions · D1
        │
        ▼
4 portales · un mismo motor
```

### Stack

`React` `TypeScript` `Cloudflare Pages` `Cloudflare D1` `GitHub Actions` `n8n` `Claude Code`

Los portales están desarrollados con IA (Claude Code). El diseño, la dirección editorial y la operación son míos.

### Formación

- Licenciatura en Historia · UNC (en curso)
- Ingeniería en Computación · UNC (en curso)
- Certificación en automatización con n8n · UNC (2026)

### Contacto

[LinkedIn](https://www.linkedin.com/in/federicopepino/)
