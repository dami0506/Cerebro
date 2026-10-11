# 📝 Changelog del Cerebro

Registro de qué procesó el bibliotecario y cuándo.

---

## 2026-10-11 — Carga directa de documentos a WIKI (tanda 1: 5 docs)

El usuario empezó a pasar documentos **ya procesados en formato WIKI** (frontmatter
`tema/actualizado/fuentes` + `[[enlaces]]`) para cargar directo en `WIKI/`. Cargados verbatim:
`angulos-publicitarios`, `aumento-de-aov`, `biblioteca-de-prompts`, `claude-con-meta-ads`,
`contingencia-de-cuentas`.

**⚠️ Cosas que hay que resolver (no toqué nada, solo lo registro):**

1. **Dos WIKIs en paralelo.** Esta tanda viene de un segundo cerebro previo mucho más completo
   y con otra convención de nombres. Se pisa temáticamente con lo que yo había construido desde
   `perfil-negocio.md`: `biblioteca-de-prompts` ↔ mi `prompts-lovable`; `angulos-publicitarios`
   ↔ mi `copy-y-guiones`; `aumento-de-aov` ↔ mi `pricing-y-ofertas`. **Habrá que decidir si los
   nuevos reemplazan/absorben a los míos o conviven.**
2. **Enlaces colgando.** Los docs apuntan a ~30 temas aún no cargados (guiones-de-video-ads,
   investigacion-de-mercado, metodo-v3, modelo-low-ticket, metricas-y-kpis, shopify-y-checkout,
   hooks, escalado-en-meta-ads, etc.). Presumiblemente llegan en próximas tandas.
3. **`fuentes:` apunta a rutas que no existen en este repo** (`RAW/formacion/lecciones/...`,
   `RAW/contexto-chatgpt.md`). Son referencias del cerebro de origen.
4. **"Santiago" es omnipresente** en estos docs ("Santiago presenta", "Santiago probó"). Pinta
   a ser el mentor/autor del método, no vos. Sigue pendiente confirmarlo.
5. **`contingencia-de-cuentas`** incluye prácticas (comprar perfiles/BMs, camuflar IP/fingerprint
   con Multilogin) que **violan los TOS de Meta**. El propio doc ya trae una "nota del bibliotecario"
   advirtiéndolo. Lo dejo como está porque es doc tuyo ya redactado, pero queda marcado.

**`index.md` NO reconstruido todavía:** espero a tener toda la tanda para rearmarlo de una, y
evitar un índice lleno de enlaces rotos. Pendiente.

## 2026-10-11 — Carga directa a WIKI (tanda 2: 5 docs)

Cargados verbatim: `creacion-de-productos-digitales`, `diagnostico-de-checkout`,
`disputas-y-reembolsos`, `email-y-automatizaciones`, `embudo-vsl-post-pago`.
Total importado del cerebro previo: **10 docs**. Siguen los mismos flags de la tanda 1
(dos wikis en paralelo, enlaces colgando a temas aún no cargados, rutas `fuentes:` externas,
"Santiago" omnipresente). `index.md` sigue sin reconstruir hasta cerrar la carga.

Nota: `disputas-y-reembolsos` menciona abrir "Claude Code desde la carpeta del segundo cerebro"
y automatizar respuestas a disputas de Stripe/MercadoPago cada 12 h — es parte del método descrito,
queda registrado.

## 2026-10-11 — Carga directa a WIKI (tanda 3: 5 docs)

Cargados verbatim: `escalado-en-meta-ads`, `estructuras-cbo`, `filosofia-de-marketing`,
`funnel-de-whatsapp`, `funnel-hacking`. Total importado del cerebro previo: **15 docs**.
Mismos flags. `index.md` sigue pendiente hasta cerrar la carga.

Nota: `funnel-hacking` describe cloaking con "Ghost Ads" (mostrar página señuelo a los
revisores de Meta / scrapers) y `estructuras-cbo`/`escalado` describen tácticas operativas de
Meta; el propio doc ya trae "nota del bibliotecario" avisando que el cloaking viola políticas de
Meta. Queda registrado tal cual vino.

## 2026-10-11 — Carga directa a WIKI (tanda 4: 4 docs + índice maestro)

Cargados verbatim: `guiones-de-video-ads`, `hooks`, `ia-en-el-flujo-de-trabajo`,
`imagenes-y-mockups`. Total de docs del cerebro previo: **19**.

**`index.md` REEMPLAZADO por el índice maestro** que mandó el usuario. Ese índice es ahora el
canónico y mapea **45 temas** del método completo (venta directa de productos digitales
low-ticket con Meta Ads). Resuelve la cuestión de "dos wikis": **gana el cerebro previo.**

**⚠️ DECISIÓN PENDIENTE — mis 12 archivos del `perfil-negocio.md` quedaron huérfanos.**
El índice maestro NO los lista: `identidad`, `estilo-comunicacion`, `copy-y-guiones`,
`landing-ingles` (estructura "piedras"), `landing-latam`, `prompts-lovable`, `prompts-veo3`,
`mockups-logos-banners`, `pricing-y-ofertas`, `flujo-de-trabajo`, `historial-ofertas`, `glosario`.
**No los borro:** contienen info ESPECÍFICA de Damián que el cerebro importado (método genérico
de "Santiago") NO cubre — voseo, estructura piedras, estructura LATAM, su stack Lovable/Shopify,
sus ofertas reales, sus precios. Al cerrar la carga hay que decidir cómo integrarlos (propuesta:
sección "Perfil propio" en el índice + fusionar lo que se solape). Por ahora quedan en `WIKI/`
pero fuera del índice maestro.

**Faltan por llegar ~26 temas** que el índice enlaza y aún no están cargados (modelo-low-ticket,
metodo-v3, metricas-y-kpis, testeo-de-creativos, investigacion-de-mercado, seleccion-y-modelado,
validacion-de-oferta, shopify-y-checkout, tracking-y-atribucion, pagina-de-ventas, quiz-funnel,
ugc-y-video-generativo, renovacion-de-creativos, psicologia-del-comprador, stack-de-herramientas,
internacionalizacion, llc-banca-y-fiscal, etc.).

## 2026-10-11 — Carga directa a WIKI (tanda 5: 5 docs)

Cargados verbatim: `internacionalizacion`, `investigacion-de-mercado`, `lectura-de-resultados`,
`llc-banca-y-fiscal`, `mentalidad-y-habitos`. Total del cerebro previo: **24 docs**.
Siguen faltando ~21 temas del índice maestro.

## 2026-10-11 — Carga directa a WIKI (tanda 6: 5 docs)

Cargados verbatim: `metodo-v3`, `metricas-y-kpis`, `modelo-low-ticket`, `nomenclatura-del-metodo`,
`optimizacion-de-roas`. Total del cerebro previo: **29 docs**. Faltan ~16 temas del índice.

## 2026-10-11 — Carga directa a WIKI (tanda 7: 5 docs)

Cargados verbatim: `organizacion-y-registro`, `pagina-de-ventas`, `problemas-de-cuentas-meta`,
`procesadores-de-pago`, `psicologia-del-comprador`. Total del cerebro previo: **34 docs**.
Faltan ~11 temas del índice.

## 2026-10-11 — Carga directa a WIKI (tanda 8: 5 docs)

Cargados verbatim: `quiz-funnel`, `renovacion-de-creativos`, `segmentos-de-mercado`,
`seleccion-y-modelado-de-oferta`, `setup-de-campanas`. Total del cerebro previo: **39 docs**.
Faltan ~6 temas del índice: `shopify-y-checkout`, `stack-de-herramientas`,
`subir-ads-con-metodo-catalogo`, `testeo-de-creativos`, `tracking-y-atribucion`,
`ugc-y-video-generativo`.

## 2026-10-11 — Carga directa a WIKI (tanda 9: 5 docs)

Cargados verbatim: `shopify-y-checkout`, `stack-de-herramientas`, `subir-ads-con-metodo-catalogo`,
`testeo-de-creativos`, `tracking-y-atribucion`. Total del cerebro previo: **44 docs**.
Falta **1 solo**: `ugc-y-video-generativo`.

## 2026-10-11 — Carga COMPLETA + verificación + reconciliación de huérfanos

**Tanda 10 (últimos 2 docs):** `ugc-y-video-generativo`, `validacion-de-oferta`. Con esto el
cerebro importado queda **completo: los 45 temas del índice maestro, todos con archivo.**

**Verificación automática (script):**
- Los 45 temas del índice maestro → **todos tienen archivo ✓**
- Wikilinks rotos en toda la WIKI → **ninguno ✓**
- Huérfanos → eran los 12 del `perfil-negocio.md`.

**Reconciliación de huérfanos (no destructiva):** agregué al `index.md` una sección
**"Perfil propio (Damián)"** que enlaza los 12 archivos y marca los solapamientos con el
método importado. Nada borrado, nada pisado. Re-verificado: **0 huérfanos, 0 links rotos.**

**WIKI total: 58 temas** (45 del método + 12 del perfil + index) + OUTPUTS vacío.

### DECISIÓN PENDIENTE para el usuario — fusiones de los solapamientos
El "Perfil propio" y el método tienen pares que convendría fusionar o decidir cuál manda:
- `copy-y-guiones` (perfil) ↔ `angulos-publicitarios` + `guiones-de-video-ads` (método)
- `mockups-logos-banners` (perfil) ↔ `imagenes-y-mockups` (método)
- `landing-ingles` + `landing-latam` (perfil, estructuras propias) ↔ `pagina-de-ventas` (método)
- `prompts-veo3` (perfil) ↔ `ugc-y-video-generativo` (método)
- `pricing-y-ofertas` (perfil) ↔ `aumento-de-aov` (método)
Propuesta del bibliotecario: mantener los del perfil como "cómo lo hace Damián en concreto" y
los del método como la teoría general, enlazados entre sí (ya lo están). Fusionar solo si el
usuario lo pide.

### Pendientes de siempre (sin resolver)
- Confirmar quién es **"Santiago"** (mentor/autor del método, todo el cerebro importado habla de él).
- Las `fuentes:` de los docs importados apuntan a rutas que **no existen en este repo**
  (`RAW/formacion/...`, `RAW/youtube/...`, `RAW/contexto-chatgpt.md`): si querés trazabilidad real,
  habría que cargar ese RAW de origen o aceptar que las fuentes son referencias externas.
- Flags de compliance ya anotados: `contingencia-de-cuentas` (comprar perfiles/BMs, Multilogin),
  `funnel-hacking` (cloaking "Ghost Ads"). Los docs ya traen nota del bibliotecario.

---

## 2026-10-11 — Colección de prompts COMPLETA en RAW/prompts/ (24 archivos)

- `RAW/prompts/` ya tiene el `_indice.md` + **los 23 prompts** que lista el índice. Colección completa.
- Añadidos en esta tanda: optimizar-carga-web-html, testimonios-sora-2,
  variacion-de-guiones-winners, vsl-oto-post-purchase.
- Inventario por categoría (según `_indice.md`):
  - **Guiones/video (7):** guiones-por-nivel-de-conciencia (5 de Schwartz), guiones-7-pasos,
    guiones-30-segundos, ads-storytelling-largos-publico-frio, variacion-de-guiones-winners,
    vsl-oto-post-purchase, testimonios-sora-2.
  - **Copy/ángulos (5):** angulos, angulos-manuales-launch-expert, meta-ads-primary-text,
    escribir-sales-page, comentarios-positivos-ig.
  - **Oferta/monetización (2):** modelar-ofertas, crear-upsells.
  - **Visual/producto (4):** imagenes-ads, crear-mockups, one-shot-mockups, ebook-con-claude.
  - **Web/desarrollo (3):** html-google-ai-studio, magic-patterns, optimizar-carga-web-html.
  - **Meta/uso del modelo (2):** generador-de-prompts-maestros, educar-chatgpt.
- **Pendiente de procesar a WIKI** (esperando "procesá RAW"). Candidato: tema nuevo
  `biblioteca-de-prompts` + ampliar copy-y-guiones, mockups-logos-banners, prompts-lovable,
  pricing-y-ofertas, flujo-de-trabajo.
- ⚠️ Nota: el `_indice.md` dice "prompts que **Santiago** usa" — confirmar si es error o es otra persona del equipo.

---

## 2026-10-11 — WIKI construida desde RAW

**Procesado:** `RAW/perfil-negocio.md` → 12 temas en `WIKI/`.

Temas creados: identidad, estilo-comunicacion, copy-y-guiones, landing-ingles,
landing-latam, prompts-lovable, prompts-veo3, mockups-logos-banners,
pricing-y-ofertas, flujo-de-trabajo, historial-ofertas, glosario.
`index.md` reconstruido con los 12 temas agrupados y enlazados con `[[wikilinks]]`.

### 🔗 Conexiones inesperadas encontradas
Cosas que en el RAW estaban separadas pero en realidad son la misma regla cruzando temas:

1. **La regla "nunca 50% OFF → te ahorrás $X" vive en 3 sitios a la vez.** Aparece como
   regla de *copy*, como regla de *landing inglés* y como *patrón de pricing*. No es una
   regla de copy: es una regla de negocio transversal. La enlacé cruzada entre
   [[copy-y-guiones]], [[pricing-y-ofertas]] y [[landing-ingles]].
2. **El idioma decide la mecánica de oferta, no solo el texto.** Combos multi-bundle ✅ en
   LATAM / ❌ en inglés no es un detalle de copy: cambia la estructura comercial entera
   (bundle vs. oferta única argumentada). Conecta [[copy-y-guiones]] ↔ [[landing-latam]] ↔
   [[pricing-y-ofertas]].
3. **El "mockup" es un único archivo que viaja por 4 temas.** Se genera en
   [[mockups-logos-banners]], pero el *mismo* archivo aparece en el hero y dentro de la
   tarjeta de pricing de [[landing-ingles]], y su colocación se instruye en
   [[prompts-lovable]]. No son tres mockups: es uno reutilizado.
4. **"Native" (fotos que parecen de celular) es el hilo que une guiones, landings y assets.**
   El mismo principio estético aparece en testimonios UGC de [[copy-y-guiones]], en las fotos
   de testimonios de [[landing-ingles]], y en la estética "iPhone quality / no cinematográfico"
   de [[prompts-veo3]]. Es una filosofía única ("que no parezca IA ni agencia"), no tres reglas.
5. **La "dignidad financiera femenina" + "no baneable" apuntan al mismo público y riesgo.**
   El ángulo ganador para mujeres emprendedoras y la regla de evitar claims de ganancias
   garantizadas son dos caras de lo mismo: vender aspiración fuerte sin cruzar la línea de
   Meta. Hoy están sueltas en [[copy-y-guiones]] → candidato claro al doc de compliance (gap #3).

### 🔍 Gaps detectados (los 3 mayores)
1. **Métricas / resultados reales** — todo el cerebro es "cómo produzco", nada de "qué funcionó"
   (ROAS, CPA, CTR, ganadoras vs. perdedoras por oferta).
2. **Checklist + prompts-template de lanzamiento** — el flujo está en prosa; falta un checklist
   reutilizable y los prompts exactos (Lovable/Veo3/mockup) listos para copiar y rellenar.
3. **Doc central de compliance / ad policy** — notas de "no baneable" dispersas, sin un lugar
   único con qué dispara bans en Meta y cómo evitarlo.

---

## 2026-10-10 — Configuración inicial

- Creada la estructura del segundo cerebro: `RAW/`, `WIKI/`, `OUTPUTS/`
- Creado `WIKI/index.md` (índice central, vacío a la espera de material)
- Creado `README.md` con el funcionamiento y las reglas
- `RAW/` vacío — pendiente el primer volcado de material

**Último procesado de RAW:** ninguno todavía.
