# Prompts para las imágenes de "¿Qué le gusta ver?"

Doce imágenes, una por tema, con un estilo común. Los prompts van en inglés porque las IA de imágenes responden mejor así.

## Especificaciones
- **Tamaño:** 1080 × 1170 px (proporción 25:27). En Midjourney agregue `--ar 25:27 --style raw`.
- **Formato:** WebP o JPG, menos de 250 KB.
- **Composición:** lo importante en los dos tercios de arriba; el tercio inferior tranquilo y algo más oscuro, porque ahí va el texto del tema.
- **Nombre del archivo:** el código del tema (por ejemplo `boleros.webp`), en la carpeta `abuetv/img/temas/`.
- **Cómo integrarlas:** en `abuetv/index.html`, agregue la ruta en `const PHOTOS={}`, por ejemplo `boleros:"img/temas/boleros.webp"`. Si un tema no tiene ruta, se sigue viendo el emoji.

## Cómo armar cada prompt
Pegue: **tema** + línea en blanco + `Style:` + **estilo** + línea en blanco + **evitar**.

### Estilo recomendado: ilustración cálida
```
Warm editorial illustration with a soft gouache texture, gentle natural light, muted harmonious palette of deep teal (#0F766E), warm sand (#EADBB8), cream and soft terracotta accents. Simple, uncluttered composition: the main subject sits in the upper two thirds and the bottom third stays calm and slightly darker so a text label can sit on top. Dignified, warm and joyful portrayal of Latin American older adults in their 70s, with diverse skin tones (mestizo, Afro-Latino, Indigenous, white). Vertical 25:27 format, 1080x1170 px.
```

### Estilo alternativo: foto
```
Warm documentary photograph, soft window light, shallow depth of field, natural slightly muted colors with teal and warm sand tones, candid and respectful, real Latin American older adults in their 70s with diverse skin tones. Main subject in the upper two thirds, calm darker bottom third for a text label. Vertical 25:27 format, 1080x1170 px.
```

### Evitar (va al final de cada prompt)
```
Avoid: any text, letters, words, numbers, signs, logos, brand names, watermarks; distorted hands, extra fingers, deformed faces; harsh shadows, neon or oversaturated colors, childish cartoon style, stock-photo grins, clutter, gloomy mood.
```

## Los 12 temas

| Archivo | Tema | Qué muestra | Prompt del tema |
|---|---|---|---|
| `boleros.webp` | Boleros y baladas | Pareja mayor bailando lento en la sala | An older couple slow-dancing cheek to cheek in a cozy living room at dusk, a vintage wooden radio and an acoustic guitar on a side table, a warm lamp glow. |
| `rancheras.webp` | Rancheras y mariachi | Mariachis en la plaza al atardecer | A small mariachi group in a colonial town plaza at golden hour, trumpet, violin and guitarrón, colorful papel picado garlands overhead without any lettering, an older man smiling and clapping in the foreground. |
| `tropical.webp` | Salsa, cumbia y merengue | Señora bailando feliz en un patio colorido | A joyful older woman dancing in a colorful courtyard, her wide skirt swirling, an older man playing maracas nearby, tropical plants and warm afternoon light. |
| `tango.webp` | Tango y folclor | Pareja de tango en un café, bandoneón y poncho | An older couple dancing tango in a softly lit neighborhood café, a bandoneon resting on a wooden chair in the foreground, a hand-woven Andean poncho draped over the chair back. |
| `cocina.webp` | Cocina de la abuela | Manos preparando tamales | Close view of an older woman's hands wrapping tamales in corn husks on a rustic wooden table, clay pots, a bowl of masa, gentle steam rising, morning light from a kitchen window. |
| `fe.webp` | Fe y oración | Rosario en manos mayores junto a la ventana | Older hands gently holding a wooden rosary near a sunlit window, a lit candle and a small vase of white flowers, a colonial church bell tower softly blurred outside. |
| `plantas.webp` | Plantas y jardín | Señor regando geranios y sábila | An older man watering red geraniums and aloe vera in terracotta pots on a sunny balcony, a straw hat, green leaves and morning sunlight. |
| `animales.webp` | Animales | Colibrí en flores y perro tranquilo | A hummingbird hovering at bright red flowers in a garden, while a calm, friendly dog rests at the feet of an older woman sitting on a garden bench. |
| `viajes.webp` | Paseos por Latinoamérica | Calle colonial de colores con montañas | A colorful colonial street with flower-filled balconies and cobblestones, green Andean mountains in the distance, golden hour light, an older couple walking arm in arm. |
| `recuerdos.webp` | Recuerdos de antes | Radio antigua, fotos sepia y tocadiscos | A still life of a vintage radio, a record player with a vinyl record, sepia family photographs in old frames and a lace tablecloth, nostalgic warm light. |
| `humor.webp` | Humor sano | Dos amigos riendo en una banca | Two older friends laughing heartily together on a park bench under a shady tree, one gently touching the other's arm, warm afternoon light. |
| `ejercicio.webp` | Ejercicio suave | Estiramientos suaves sentada en una silla | An older woman doing gentle seated stretches on a sturdy chair in a bright, airy room, arms raised calmly, a potted plant and a glass of water nearby. |

**Consejo:** genere 2 o 3 versiones por tema y elija las 12 que se vean más parecidas entre sí en luz y colores. Una sola imagen fuera de estilo se nota mucho en la cuadrícula.
