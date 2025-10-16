# Política de seguridad

## 🧠 Resumen
**Prompt de 100 técnicas XSS + IA** es un recurso educativo/ofensivo para **laboratorio**.  
No ejecuta código ni interactúa con sistemas; guía la generación de variantes de payloads con fines de prueba ética.

---

## 🔐 Principios de seguridad
- **Uso ético y legal**: solo en entornos controlados o programas de bug bounty con permiso explícito.
- **Contenido seguro**: no incluye exploits activos ni automatiza ataques en targets reales.
- **Privacidad**: no almacenar ni publicar payloads sensibles; usar datos anónimos.
- **Reproducibilidad**: usar `seed` para auditorías y trazabilidad de pruebas.

---

## ✅ Buenas prácticas
- Validar variantes en **labs aislados** antes de cualquier uso real.
- Respetar **alcances** y normas de cada programa.
- Documentar resultados (qué técnicas pasan/fallan y por qué).
- Evitar **invisibles/BIDI** en tokens productivos y mantener balanceo estricto.

---

## 🐛 Reporte de problemas
Si detectás comportamientos inseguros o inconsistencias:
1) No publiques detalles sensibles en issues públicos.  
2) Contactá al mantenedor (GitHub/Discord).  
3) Incluí: payload base, `x9_list`, `apply_mode`, `combo_flags`, `seed`, resultado esperado/obtenido.

---

## 🛡️ Alcance

| Área                         | Estado                 |
|-----------------------------|------------------------|
| Backend / API               | ❌ No aplica           |
| Ejecución de código         | ❌ No incluida         |
| Payloads activos            | ❌ No incluidos        |
| Guía/plantilla de uso       | ✅ Incluida            |
| Datos sensibles             | ❌ No almacenar        |

---

## ⚠️ Descargo
Recurso para **fines educativos y de investigación**.  
El uso indebido puede ser ilegal. El autor no se responsabiliza por acciones no autorizadas derivadas del uso de esta plantilla.

---

**“No dispares un payload… libera un enjambre.”**
