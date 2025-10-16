# Changelog

Todas las versiones siguen el formato [SemVer].

## [v1.0.0] - 2025-10-16
### 🆕 Añadido
- **Prompt maestro — 100+ técnicas XSS + IA**: motor generador de payloads XSS con **110+ técnicas** modernas y legacy para laboratorio.
- **Modos de aplicación**:
  - `apply_mode=simple` → 1 técnica por variante.
  - `apply_mode=combo` → mezcla 2–4 técnicas por variante.
  - `apply_mode=chaos` → elección aleatoria entre todas por variante.
- **Inputs configurables**:
  - `payloads` (uno o lista), `seed` (reproducibilidad),
  - `variants_per_payload`, `x9_list` (IDs de técnicas),
  - `combo_flags`: `#*`, `#**`, `#a`,
  - `modo_validación`: `estricto` (default) | `relajado`.
- **Catálogo de técnicas (x9_técnicas_xss)**:
  - 90+ técnicas **[OK]** vigentes en navegadores actuales.
  - 20 técnicas **[LEGACY]** históricas para referencia.
- **Reglas duras**: no romper sintaxis HTML/JS, balanceo de delimitadores, preservar primitivas (alert/onerror/…), sin invisibles disruptivos, no alterar nombres críticos.
- **Validación estricta (A–E)**:
  - A: Sintaxis intacta
  - B: Balanceo correcto
  - C: Primitiva ejecuta
  - D: Técnicas ∈ `x9_list`
  - E: Sin invisibles disruptivos
- **Formato de salida mínimo**: solo lista de payloads (uno por línea), sin metadatos.

### ✨ Cambiado
- N/A — primera versión.

### 🐞 Corregido
- N/A — primera versión.

### 📌 Notas
- Pensado para **entornos de laboratorio** y programas con autorización.
- Ejemplo de invocación:
  - `payloads: <img src=x onerror=alert(1)>`
  - `seed: 1337`
  - `variants_per_payload: 30`
  - `x9_list: #1,#4,#10,#12,#18,#25,#33,#48`
  - `apply_mode: combo`
  - `combo_flags: #a,#**`
  - `modo_validación: estricto`
