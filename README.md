# 🧠 Cerebro — Tu Segundo Cerebro Personal

Sistema de conocimiento personal gestionado por un bibliotecario (Claude).
**Tú vuelcas material en `RAW/`. Yo lo organizo en `WIKI/`. Tú preguntas, yo respondo con contexto real.**

---

## Cómo funciona

```
Cerebro/
├── RAW/          ← TÚ escribes aquí (notas, ideas, volcados, lo que sea)
├── WIKI/         ← YO mantengo esto (NUNCA lo edites a mano)
│   ├── index.md  ← Mapa de todos los temas
│   └── *.md      ← Un archivo por tema, enlazados entre sí
├── OUTPUTS/      ← Respuestas importantes, guardadas con fecha
├── changelog.md  ← Qué procesé y cuándo
└── README.md     ← Esto
```

## Mi rol (el bibliotecario)

| # | Función | Qué hago |
|---|---------|----------|
| 1 | **LEER** | Leo `RAW/` cuando me lo pidas y lo proceso |
| 2 | **ORGANIZAR** | Creo y mantengo `WIKI/` (tú nunca editas WIKI a mano) |
| 3 | **RESPONDER** | Busco en `WIKI/` y `RAW/` antes de responder — contexto real, no genérico |
| 4 | **GUARDAR** | Las respuestas importantes van a `OUTPUTS/` con fecha, enlazadas desde el índice |
| 5 | **MEJORAR** | Detecto los 3 mayores huecos y te sugiero qué añadir |

## Cómo usarme

- **"Procesa RAW"** → leo todo lo nuevo en `RAW/` y actualizo la WIKI
- **"¿Qué sé sobre X?"** → busco en WIKI/RAW y respondo con tu contexto
- **"Guarda esto"** → lo archivo en `OUTPUTS/` con fecha
- **"¿Qué me falta?"** → te doy los 3 mayores gaps

## Regla de oro

👉 **Tú solo tocas `RAW/` y `OUTPUTS/` (si quieres). `WIKI/` es territorio del bibliotecario.**
