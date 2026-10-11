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
