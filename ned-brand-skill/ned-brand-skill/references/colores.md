# NED — Paleta de colores extendida

## Colores principales

### Vino NED — `#7D1A3A`
- RGB: 125, 26, 58
- Uso: botones CTA, bordes de acento, top-borders en hover, sombras de color
- Variantes:
  - Oscuro: `#5A1129` (hover de botones primarios)
  - Transparente 20%: `#7D1A3A33` (sombras, glows)
  - Transparente 10%: `#7D1A3A1A` (fondos de badge)

### Fucsia NED — `#C2587A`
- RGB: 194, 88, 122
- Uso: íconos, links hover, subrayados, texto de acento, etiquetas activas
- Variantes:
  - Claro: `#D4789A` (hover states)
  - Transparente 27%: `#C2587A44` (bordes de badge, líneas sutiles)

### Rosado NED — `#F4D0DC`
- RGB: 244, 208, 220
- Uso: texto sobre fondos vino, badges claros, acento suave

---

## Grises (escala de grafito)

| Variable | Hex | RGB | Uso |
|----------|-----|-----|-----|
| Grafito profundo | `#1A1A1C` | 26, 26, 28 | Fondo principal |
| Grafito medio | `#2C2C2F` | 44, 44, 47 | Superficies secundarias, nav |
| Grafito claro | `#3E3E42` | 62, 62, 66 | Cards en hover, inputs |
| Borde | `#4A4A4F` | 74, 74, 79 | Bordes de cards, divisores |
| Texto brillante | `#F0ECE8` | 240, 236, 232 | Texto principal |
| Texto atenuado | `#9A9498` | 154, 148, 152 | Texto secundario |
| Texto tenue | `#5C5A5E` | 92, 90, 94 | Placeholders, hints |

---

## Combinaciones aprobadas

### Hero / portada oscura
- Fondo: `#1A1A1C`
- Título: `#F0ECE8` (Playfair Display)
- Acento de título: `#C2587A`
- Subtítulo: `#9A9498` (DM Sans 300)
- CTA button bg: `#7D1A3A` → hover `#C2587A`
- CTA button text: `#FFFFFF`

### Card de servicio
- Fondo: `#2C2C2F`
- Border: `1px solid #4A4A4F`
- Border top hover: `2px solid #7D1A3A`
- Título: `#F0ECE8` (DM Sans 500)
- Descripción: `#9A9498` (DM Sans 300)
- Tags: color `#C2587A`, border `#C2587A44`, bg transparente

### Tag / badge técnico
- Fondo: transparente o `#7D1A3A1A`
- Borde: `1px solid #C2587A44`
- Texto: `#C2587A` (DM Mono 400, uppercase, letter-spacing 0.08em)

### Sección alternada
- Par: fondo `#1A1A1C`
- Impar: fondo `#2C2C2F`

### Documento impreso (propuesta, contrato)
- Fondo: `#FFFFFF`
- Texto principal: `#1A1A1C`
- Acento / títulos de sección: `#7D1A3A`
- Subtítulos: `#C2587A`
- Bordes de tabla: `#E0E0E0`
- Header de tabla: bg `#7D1A3A`, texto `#FFFFFF`

---

## NO usar jamás

- ❌ Gradientes de colores (solo gradientes oscuros de fondo)
- ❌ Blanco puro `#FFFFFF` como fondo en piezas digitales
- ❌ Colores fuera de esta paleta sin aprobación
- ❌ Morado, azul eléctrico, verde neón — no pertenecen a NED
- ❌ Sombras grises genéricas — usar siempre `#7D1A3A33`
