# Docs

Documentación técnica del proyecto. Sigue el estándar **Diátaxis** para
organización y nomenclatura: cada documento vive en **un solo modo**,
agrupado por la intención del lector, no por tema.

## Estándar Diátaxis (obligatorio para todo archivo en `**/docs/`)

| Modo | Carpeta | Pregunta que responde | Estilo |
|---|---|---|---|
| **Explanation** | `explanation/` | "¿Por qué es así?" | Discusión, decisiones, historia, trade-offs. |
| **How-to** | `how-to/` | "¿Cómo hago X?" | Pasos numerados, recetas, comandos. |
| **Reference** | `reference/` | "¿Qué es exactamente Y?" | Lookup puro, tablas, definiciones. Sin narrativa. |
| **Tutorial** | `tutorials/` | "¿Cómo aprendo?" | Learning paths guiados. |

### Reglas de nomenclatura y estilo

1. **Un modo por archivo.** Si un doc mezcla explanation + reference,
   partirlo. Cada archivo debe poder leerse sin leer los otros.
2. **Nombre estable, ruta explícita.** El nombre del archivo describe el tema
   en `kebab-case` sin prefijos redundantes (ej: `auth-flow.md`, no
   `explanation-auth.md`).
3. **Sin duplicación.** La referencia técnica (APIs, esquemas, tipos) vive en
   `reference/`, nunca duplicada dentro de guías prácticas o explicaciones.
4. **Orientación al lector:**
   - En `how-to/`: pasos numerados, reproducibles y orientados a un objetivo
     específico.
   - En `explanation/`: contexto conceptual, alternativas y decisiones de
     diseño (ADRs).
   - En `reference/`: información fáctica, exhaustiva y neutral.
   - En `tutorials/`: experiencia guiada de aprendizaje paso a paso para
     principiantes.
