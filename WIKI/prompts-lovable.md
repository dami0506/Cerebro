# Prompts para Lovable

Cómo armo los prompts para que Lovable construya/adapte landings.

## Principio base
Copiar una página vieja (de otra oferta, ya con la estructura piedras — ver [[landing-ingles]]) dentro de un proyecto, y que Lovable **solo adapte el contenido nuevo** — NO reconstruya ni rediseñe. Prompt conciso, no gigante, pero muy claro en los puntos sensibles.

## Instrucciones típicas del prompt
1. Reemplazar todo el texto por el copy nuevo (mismas secciones, mismo orden; borrar las que no van).
2. Adaptar paleta de colores — siempre con **hex codes** (primario, secundario, fondos, botones, texto), temática de la oferta.
3. **Bonos:** adjunto imagen de referencia de estilo; Lovable genera una imagen nueva por bono basada 100% en ese estilo, con colores/contenido de la oferta nueva. Imagen completa arriba (nunca recortada, `object-fit: contain`), título + descripción debajo. **Apiladas** (NO grilla 2x2). Compactas, mobile. Una distinta por bono, nunca repetir.
4. Usar los archivos adjuntos **EXACTO** — NO generar reemplazos de videos/mockups/imágenes adjuntos (error recurrente).
5. Mover/ubicar media según corresponda.
6. Conversión por IP o moneda fija (ver [[pricing-y-ofertas]]).
7. Links de checkout (placeholder).
8. Mobile-first, botones una línea sin overflow.
9. **Performance:** cargar TODO de entrada (sin lazy-load / sin carga progresiva al scrollear), solo optimizar/comprimir para que vaya fluido.
10. Lista de **DO NOT** (no cambiar estructura, no agregar/quitar secciones, no reconstruir).

## Errores recurrentes de Lovable (prevenir explícitamente)
- Genera imágenes propias en vez de usar las adjuntas.
- Arma bonos en grilla en vez de apilados.
- Agrega secciones no pedidas.
- Contador con "horas" en vez de solo 10 min.
- Testimonios chicos en vez de carrusel grande.
- Videos horizontales cuando deben ir verticales.
- Poco contraste entre fondos de secciones.

## Manejo de videos/media (aprendido)
- **VSL (BCL)** (ver [[glosario]]): cuadro "Tap to listen" al cargar; al reproducir solo pausar/continuar y agrandar (fullscreen). Sin barra de progreso, volumen, velocidad, descarga, click derecho ni picture-in-picture. Autoplay+loop con sonido tras el tap, poster, preload.
- **B-roll sin voz** → autoplay silenciado + loop, sin controles.
- Se puede pedir: reproducir solo los primeros X s y loopear; velocidad x2; vertical/portrait para que se vea completo; bordes ligeramente redondeados en mockups.
- El mockup suele ir en hero (arriba) + dentro de la tarjeta de pricing (mismo archivo).

## Relacionado
- Qué estructura replica → [[landing-ingles]] · [[landing-latam]]
- De dónde salen videos/mockups → [[prompts-veo3]] · [[mockups-logos-banners]]
- Orden de entrega → [[flujo-de-trabajo]]
