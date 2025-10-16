# Release Notes — v1.0.0 (2025-10-16)

## 🏹 Resumen
**Prompt de 100 técnicas XSS + IA**: generador automático que aplica **110+ técnicas** (modernas + legacy) para crear variantes ofensivas **funcionales** con validación estricta. Ideal para investigación, bypass de WAF, fuzzing avanzado y entrenamiento en laboratorio.

---

## 🧪 Problema que resuelve
Los entornos modernos (WAF, filtros, sanitizadores) bloquean payloads clásicos. Este prompt:
- Automatiza miles de variantes **válidas**.
- Mantiene ejecución y sintaxis del payload.
- Aumenta cobertura y descubre **bypasses reales** que herramientas básicas no ven.

---

## ⚙️ Qué aporta
- **Cobertura masiva**: catálogo curado de **110+ técnicas** ([OK] vigentes, [LEGACY] históricas).
- **Automatización total**: `variants_per_payload`, `seed` para reproducibilidad, `x9_list` para selección fina.
- **Modos de mezcla**: `simple`, `combo`, `chaos` + `combo_flags` (`#*`, `#**`, `#a`) para controlar entropía.
- **Validación estricta**: descarta variantes que rompan sintaxis o ejecución (reintentos hasta 3).

---

## 🧰 Inputs del usuario
- `payloads`: A) uno, B) lista (uno por línea)
- `seed` (opcional): reproducibilidad
- `variants_per_payload`: cantidad por payload
- `x9_list`: IDs de técnicas a aplicar (ej.: `#1,#4,#12,#18,#25,#48`)
- `apply_mode`: `simple` | `combo` | `chaos`
- `combo_flags` (opcional): `#*`, `#**`, `#a`
- `modo_validación`: `estricto` (default) | `relajado`

---

## 🧱 Reglas duras (extracto)
- No romper **sintaxis** HTML/JS.
- Mantener **balanceo** de paréntesis/comillas/corchetes.
- Preservar **primitivas** de ejecución (alert/onerror/…).
- Sin **invisibles/BIDI** disruptivos en tokens.
- No alterar **nombres críticos** (etiquetas/eventos).
- Si una técnica rompe ejecución → **descartar y regenerar** (máx. 3 intentos).

---

## ✅ Validación (modo estricto)
A) Sintaxis intacta · B) Balanceo correcto · C) Primitiva ejecuta · D) Técnica ∈ `x9_list` · E) Sin invisibles disruptivos.

---

## 🧪 Ejemplo rápido (laboratorio)
