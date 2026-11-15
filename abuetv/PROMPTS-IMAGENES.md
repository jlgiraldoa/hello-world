# Prompts para las imágenes de "¿Qué le gusta ver?"

Doce imágenes, una por tema, con un estilo común. Los prompts van en inglés porque las IA de imágenes responden mejor así.

## Especificaciones
- **Personas:** adultos latinoamericanos de 25 a 50 años, de distintos tonos de piel. **No se representan personas mayores.**
- **Tamaño:** 1080 × 1170 px (proporción 25:27). En Midjourney agregue `--ar 25:27 --style raw`.
- **Formato:** WebP o JPG, menos de 250 KB.
- **Composición:** lo importante en los dos tercios de arriba; el tercio inferior tranquilo y algo más oscuro, porque ahí va el texto del tema.
- **Nombre del archivo:** el código del tema (por ejemplo `boleros.webp`), en la carpeta `abuetv/img/temas/`.
- **Cómo integrarlas:** en `abuetv/index.html`, agregue la ruta en `const PHOTOS={}`, por ejemplo `boleros:"img/temas/boleros.webp"`. Si un tema no tiene ruta, se sigue viendo el emoji.

## Cómo armar cada prompt
Pegue: **tema** + línea en blanco + `Style:` + **estilo** + línea en blanco + **evitar**.

### Estilo elegido: ilustración cálida
```
Warm editorial illustration with a soft gouache texture, gentle natural light, muted harmonious palette of deep teal (#0F766E), warm sand (#EADBB8), cream and soft terracotta accents. Simple, uncluttered composition: the main subject sits in the upper two thirds and the bottom third stays calm and slightly darker so a text label can sit on top. When people appear, they are Latin American adults roughly 25 to 50 years old, with diverse skin tones (mestizo, Afro-Latino, Indigenous, white), shown warm, natural and joyful. Vertical 25:27 format, 1080x1170 px.
```

### Estilo alternativo: foto
```
Warm documentary photograph, soft window light, shallow depth of field, natural slightly muted colors with teal and warm sand tones, candid and natural, Latin American adults roughly 25 to 50 years old with diverse skin tones. Main subject in the upper two thirds, calm darker bottom third for a text label. Vertical 25:27 format, 1080x1170 px.
```

### Evitar (va al final de cada prompt)
```
Avoid: elderly or gray-haired people; any text, letters, words, numbers, signs, logos, brand names, watermarks; distorted hands, extra fingers, deformed faces; harsh shadows, neon or oversaturated colors, childish cartoon style, stock-photo grins, clutter, gloomy mood.
```

## Los 12 temas

| Archivo | Tema | Qué muestra | Prompt del tema |
|---|---|---|---|
| `boleros.webp` | Boleros y baladas | Pareja de unos 30 años bailando lento en la sala | A couple in their thirties slow-dancing cheek to cheek in a cozy living room at dusk, a vintage wooden radio and an acoustic guitar on a side table, a warm lamp glow. |
| `rancheras.webp` | Rancheras y mariachi | Mariachis jóvenes en la plaza al atardecer | A small group of young adult mariachi musicians in a colonial town plaza at golden hour, trumpet, violin and guitarrón, colorful papel picado garlands overhead without any lettering, festive and warm. |
| `tropical.webp` | Salsa, cumbia y merengue | Mujer de unos 30 años bailando en un patio colorido | A joyful woman in her thirties dancing in a colorful courtyard, her wide skirt swirling, a man playing maracas nearby, tropical plants and warm afternoon light. |
| `tango.webp` | Tango y folclor | Pareja de unos 40 años bailando tango, bandoneón y poncho | A couple in their forties dancing tango in a softly lit neighborhood café, a bandoneon resting on a wooden chair in the foreground, a hand-woven Andean poncho draped over the chair back. |
| `cocina.webp` | Cocina de la abuela | Manos adultas preparando tamales | Close view of adult hands wrapping tamales in corn husks on a rustic wooden table, clay pots, a bowl of masa, gentle steam rising, morning light from a kitchen window. |
| `fe.webp` | Fe y oración | Rosario en manos adultas junto a la ventana | Adult hands gently holding a wooden rosary near a sunlit window, a lit candle and a small vase of white flowers, a colonial church bell tower softly blurred outside. |
| `plantas.webp` | Plantas y jardín | Hombre de unos 30 años regando geranios y sábila | A man in his thirties watering red geraniums and aloe vera in terracotta pots on a sunny balcony, a straw hat, green leaves and morning sunlight. |
| `animales.webp` | Animales | Colibrí en flores y perro junto a una mujer que lee | A hummingbird hovering at bright red flowers in a garden, while a calm, friendly dog rests beside a woman in her thirties reading on a garden bench. |
| `viajes.webp` | Paseos por Latinoamérica | Calle colonial de colores con montañas | A colorful colonial street with flower-filled balconies and cobblestones, green Andean mountains in the distance, golden hour light, a young couple walking arm in arm. |
| `recuerdos.webp` | Recuerdos de antes | Radio antigua, fotos sepia y tocadiscos (sin personas) | A still life of a vintage radio, a record player with a vinyl record, sepia family photographs in old frames and a lace tablecloth, nostalgic warm light, no people. |
| `humor.webp` | Humor sano | Dos amigos de unos 30 años riendo en una banca | Two friends in their thirties laughing heartily together on a park bench under a shady tree, one gently touching the other's arm, warm afternoon light. |
| `ejercicio.webp` | Ejercicio suave | Mujer de unos 40 años estirándose sentada en una silla | A woman in her forties doing gentle seated stretches on a sturdy chair in a bright, airy room, arms raised calmly, a potted plant and a glass of water nearby. |

**Consejo:** genere 2 o 3 versiones por tema y elija las 12 que se vean más parecidas entre sí en luz y colores. Una sola imagen fuera de estilo se nota mucho en la cuadrícula.
