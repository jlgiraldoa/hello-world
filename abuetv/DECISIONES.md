# AbueTV · Decisiones de producto y diseño

Registro de lo que ya decidimos juntos. Prototipo actual: `abuetv/index.html` (v0.8).

## Producto
- **Qué es:** videos, shorts y juegos tranquilos para adultos mayores (75+).
- **Público:** toda Latinoamérica, en español neutro latinoamericano.
- **Contenido:** catálogo propio con licencia. Se empieza con videos creados con IA, siempre marcados como "Hecho con IA". Más adelante se invitará a creadores de contenido.
- **Cuentas:** se puede ver sin cuenta; los gustos y guardados quedan en la memoria del teléfono. Crear una cuenta toma 3 pasos: nombre, país y temas de interés.
- **Temas de interés:** se eligen al estilo TikTok al entrar y se pueden cambiar en "Mis gustos".

## Experiencia
- **Nada se reproduce solo:** al terminar un video o un short, la persona elige qué ver después.
- **Letra grande fija:** no hay control de tamaño de letra.
- **Juegos:** sin reloj, sin "perdiste" y con mensajes amables. **Se quedan estos 4:**
  1. Encontrar parejas (memoria, niveles Fácil y Normal, con pista)
  2. Complete el refrán
  3. Preguntas de nuestra tierra (cultura latinoamericana)
  4. Lotería cantada (lee los números en voz alta)
- **Barra de abajo:** Videos · Shorts · Juegos · Guardados. "Mis gustos" va en el botón de arriba a la derecha.
- **Subir lista / Bajar lista:** botones siempre visibles. En Shorts cambian a "Short anterior" / "Siguiente short".

## Patrones de uso (v0.7, después de la revisión de diseño)
- **Una sola forma de salir:** botón rojo "← Salir" arriba a la izquierda, en el reproductor, Shorts, juegos y búsqueda por voz. Lleva de vuelta a la pantalla de donde se vino.
- **El video queda fijo arriba** mientras se baja a ver los controles o la lista "Siguiente para usted".
- **Tocar el video pausa o continúa**, igual en videos y en Shorts.
- **Avisos de 5,5 segundos**, que se cierran al tocarlos.
- **Mínimo 18 px** en todo texto de la app. Solo las etiquetas punteadas de prototipo son más pequeñas.
- **Inicio compacto:** filtros "Para usted", "Todo" y "Por tema", para que el primer video se vea entero sin bajar.
- **El país no avanza solo:** se marca y luego se toca "Continuar".

## Diseño
- **Nombre:** AbueTV. **Lema:** "Videos y juegos, con calma."
- **Logo:** "Tele de antes": televisor con antenas y un corazón en la pantalla, en verde azulado y arena (dibujado en `identidad.html`). Se usa en el ícono, la bienvenida, la barra superior y como "canal" en cada video.
- **Paleta "Sereno"** (fija): verde azulado `#0F766E` para la acción principal, arena para avisos suaves y rojo `#B42318` solo para salir o volver.
- **Estilo:** inspirado en YouTube (miniaturas grandes, lista "Siguiente para usted", Shorts verticales), con solo las funciones esenciales.
- Íconos de línea siempre acompañados de texto; textos en minúscula normal.

## Imágenes de temas
- **Primera versión:** se queda con las imágenes actuales del prototipo (emoji sobre fondos de color de cada tema). **Se cancelan las imágenes hechas con IA.**
- Los prompts quedan guardados en `PROMPTS-IMAGENES.md` por si se retoman más adelante.

## Descartado
- **Principio: no se manipulan celulares remotamente.** Nadie controla ni configura el teléfono de la persona desde otro aparato.
- **Manejo remoto por familiares:** nadie administra la app desde otro teléfono (ni modo cuidador ni elegir contenido a distancia). La persona usa AbueTV por su cuenta.

## Pendiente de decidir
- Cómo entra la persona a su cuenta en otro teléfono. Propuesta: código por SMS que llega al mismo teléfono y se llena solo; no implica control remoto. Por confirmar.
- Cómo se distinguen los creadores invitados del contenido hecho con IA.
- Duración máxima de los shorts y qué pasa al llegar al último ("Por hoy es todo").
- Registro suave de juego, por ejemplo "Esta semana jugó 5 veces", sin puntajes.
