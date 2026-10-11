# 📝 Changelog del Cerebro

Registro de qué procesó el bibliotecario y cuándo.

---

## 2026-10-11 — Material nuevo en RAW/prompts/ (10 archivos)

- Cargados en `RAW/prompts/` (colección de prompts de marketing): `_indice.md` +
  **9 prompts**: ads-storytelling-largos-publico-frio, angulos, angulos-manuales-launch-expert,
  comentarios-positivos-ig, crear-mockups, crear-upsells, ebook-con-claude, educar-chatgpt,
  escribir-sales-page.
- **Pendiente de procesar a WIKI.** Faltan **14 prompts** del índice (23 en total): guiones por
  nivel de conciencia / 7 pasos / 30s, variación winners, VSL OTO, testimonios Sora 2,
  meta-ads-primary-text, modelar-ofertas, imagenes-ads, one-shot-mockups, html-google-ai-studio,
  magic-patterns, optimizar-carga-web, generador-de-prompts-maestros.
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
