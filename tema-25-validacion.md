# Tema 25 — Checklist de Validación

> **Título oficial**: Accesibilidad, diseño universal y usabilidad. Acceso y usabilidad de las tecnologías, productos y servicios relacionados con la sociedad de la información. Confidencialidad y disponibilidad de la información en puestos de usuario final. Conceptos de seguridad en el desarrollo de los sistemas.
> **Versión**: v1.0 — Pendiente validación
> **Fecha**: 2026-08-20
> **Revisores**: María y Ana (eTrivium) · revisión técnica IAM (Jesús Cuadrado)
> **Instrucciones**: marcar cada ítem. Los cambios no se guardan en la web (imprimir o exportar a PDF si se desea fijarlos).

---

## 1. Cobertura del temario oficial

- [ ] **Usabilidad y diseño universal**: principios de usabilidad y experiencia de usuario, fundamentos del diseño universal y diseño para todos, modelos de calidad ISO 9241 e ISO/IEC 25010 — §1
- [ ] **Acceso y usabilidad de las tecnologías de la sociedad de la información**: WCAG, requisitos TIC y EN 301 549, marco normativo en la Administración Pública, evaluación/auditoría/declaración — §2
- [ ] **Seguridad en el puesto de usuario final**: preservación de la confidencialidad y garantía de la disponibilidad — §3.1
- [ ] **Control de acceso y protección criptográfica**: autenticación y mínimo privilegio, cifrado de almacenamiento local y comunicaciones — §3.2
- [ ] **Seguridad operativa y prevención de pérdida de datos**: código malicioso en el endpoint, copias de seguridad y DLP, ENS en el puesto — §3.3
- [ ] **Ciclo de vida de desarrollo seguro**: modelos e integración, análisis de requisitos y modelado de amenazas — §4.1
- [ ] **Principios y prácticas de codificación segura**: diseño seguro y defensa en profundidad, validación y sanitización, sesiones/autenticación/autorización (con los dos apartados de cuarto nivel del esqueleto), registro y excepciones — §4.2
- [ ] **Vulnerabilidades y verificación**: catálogo OWASP, técnicas estáticas y dinámicas, bastionado y gestión de dependencias — §4.3

## 2. Contenido teórico

- [ ] El nivel de profundidad (3 secciones, 33 epígrafes, ~21.500 palabras) es adecuado para C1. **Este es, con diferencia, el tema más extenso de la serie técnica**: el enunciado oficial reúne tres materias que en otras convocatorias son temas independientes (accesibilidad, seguridad del puesto y desarrollo seguro). ¿Se mantiene la extensión o se recorta algún bloque?
- [ ] El **equilibrio entre los tres bloques** es el adecuado (aproximadamente 35 % accesibilidad y usabilidad, 30 % puesto de usuario, 35 % desarrollo seguro) o conviene reponderarlo
- [ ] Las distinciones nucleares quedan nítidas: **accesibilidad / usabilidad / UX / diseño universal**; **nivel** (dimensión) frente a **categoría** (sistema) en el ENS; **RPO** frente a **RTO**; **diferencial** frente a **incremental**; **CWE / CVE / CVSS**; **SAST / DAST / IAST / SCA**
- [ ] La decisión de usar **fragmentos de código reales** (Java, Python, JavaScript, SQL, cabeceras HTTP) en lugar de pseudocódigo es adecuada: en codificación segura la diferencia entre la construcción vulnerable y la correcta solo se aprecia en el lenguaje concreto
- [ ] Los datos numéricos de WCAG son correctos: **86 criterios en 2.2** (31 A + 24 AA + 31 AAA), 78 en 2.1, 61 en 2.0, **13 pautas**, contraste **4,5:1 / 3:1** en AA y **7:1 / 4,5:1** en AAA, objetivo mínimo **24 × 24 px CSS** (AA) y 44 × 44 (AAA)
- [ ] Las fechas y referencias normativas son correctas: WCAG 2.0 (dic-2008, ISO/IEC 40500:2012), 2.1 (jun-2018), **2.2 (5-oct-2023)**; Convención ONU 2006; RDL 1/2013; Directiva 2016/2102; **RD 1112/2018**; Decisiones (UE) 2018/1523 y 2018/1524; Directiva 2019/882 y **Ley 11/2023** (aplicación desde 28-jun-2025); plazos del RD 1112/2018 (23-sep-2019 / 23-sep-2020 / 23-jun-2021)
- [ ] **Codificación de las medidas del ENS**: el contenido cita los **grupos** del Anexo II del RD 311/2022 (`org`, `op.acc`, `op.exp`, `op.cont`, `op.mon`, `mp.eq`, `mp.si`, `mp.sw`, `mp.info`) y nombra las medidas, sin numerarlas una a una salvo `mp.eq` (puesto despejado, bloqueo de puesto, equipos portátiles). **Verificar la numeración exacta contra el Anexo II** si se decide detallarla en una versión posterior
- [ ] La frontera con los Temas 22 (cliente/servidor y servicios web), 23 (aplicaciones web), 24 (desarrollo móvil), 26 (backup como sistema), 27 (administración del SO), 32 (seguridad de sistemas y criptografía), 35 (HTTP/TLS), 36 (seguridad en redes y puesto de usuario desde la óptica de red) y 39 (ENS/ENI) está clara y sin duplicidades innecesarias
- [ ] Los ejemplos Ayto Madrid (cita previa y consulta de expedientes, Oficina de Atención a la Ciudadanía) son verosímiles y coherentes entre los tres bloques
- [ ] El **cierre transversal** («los tres bloques como un solo criterio de calidad») aporta valor pedagógico o resulta prescindible

## 3. Fuentes

- [ ] Todas las afirmaciones están respaldadas por fuente Tier 1 (W3C, ISO/IEC, ETSI, NIST, MITRE, OWASP, IETF, BOE/DOUE)
- [ ] Las referencias inline se corresponden con `tema-25-fuentes.md`
- [ ] La referencia `[PSI-MADRID]` está formulada como marco exigido por el art. 12 del ENS, **sin atribuir fecha ni denominación exacta** a la política municipal: confirmar con el IAM la denominación y la cita correctas antes de publicar
- [ ] La referencia `[MADRID-A11Y]` (declaración de accesibilidad y unidad responsable del Ayuntamiento) debe contrastarse con los datos publicados en el portal municipal

## 4. Test (60 preguntas)

- [ ] Cada pregunta tiene una sola respuesta correcta e inequívoca
- [ ] Los distractores (A/B/C) son plausibles
- [ ] La distribución de la opción correcta entre A/B/C está equilibrada (**verificada 20/20/20** por el generador)
- [ ] El reparto por bloques es razonable: usabilidad y diseño universal P1-P10, accesibilidad y marco normativo P11-P23, puesto de usuario P24-P43, desarrollo seguro P44-P60
- [ ] Las explicaciones y referencias de cada respuesta son correctas

## 5. Casos prácticos (3)

- [ ] Realistas y propios del Ayuntamiento (auditoría de accesibilidad del portal de cita previa; incidente múltiple en el puesto de una Oficina de Atención a la Ciudadanía; contratación y verificación del desarrollo)
- [ ] Soluciones orientativas técnicamente correctas
- [ ] La puntuación de cada caso suma 10 puntos
- [ ] Cada caso cubre un bloque distinto del tema, sin solapamiento

## 6. Diagramas (14 SVG)

- [ ] Cada diagrama es correcto y legible (también impreso en blanco y negro)
- [ ] Accesibilidad: todos tienen `role="img"` y `aria-label` descriptivo — **exigencia especialmente pertinente en este tema**, que trata precisamente de accesibilidad
- [ ] Sin desbordes de texto ni colisiones de estilo entre SVG (clases con sufijo único, QA de caja contenedora con render en navegador)
- [ ] El reparto es equilibrado: 7 diagramas para el bloque 1, 4 para el bloque 2 y 3 para el bloque 3

## 7. Referencias cruzadas a otros temas

- [ ] Validadas contra BOAM 10.032 (T18, T20, T22, T23, T24, T26, T27, T32, T35, T36, T39)
- [ ] Ninguna referencia cruzada cita un enunciado de tema incorrecto

## 8. Calidad editorial

- [ ] Ortografía verificada (tildes y ñ) — sin diacríticos perdidos, también dentro de los `aria-label` de los SVG
- [ ] Coherencia de versión (v1.0) en title, badges, banner y footer del `index.html`
- [ ] El `index.html` abre, navega entre las 8 pestañas y el motor de test funciona
- [ ] Las listas anidadas del Contenido se muestran con sus niveles (sin aplanar)
- [ ] El **quinto nivel de encabezado** (§4.2.3.1 y §4.2.3.2, exigido por el esqueleto oficial) se renderiza con estilo propio y diferenciado del cuarto
- [ ] Los bloques de código Java, Python, JavaScript, SQL y HTTP se muestran correctamente formateados, sin markdown crudo

---

## Observaciones abiertas

_(Espacio para anotaciones de María, Ana y la revisión IAM.)_

- **Extensión**: el tema duplica en palabras a la media de la serie técnica porque su enunciado oficial reúne tres materias. Conviene decidir si se mantiene como está, si se publica dividido en tres partes navegables o si se recorta alguno de los bloques. La recomendación de generación es **mantenerlo íntegro**, porque el examen puede preguntar por cualquiera de los tres.
- Pendiente confirmar si conviene desarrollar el **OWASP Top 10:2021 riesgo a riesgo** con el detalle con que lo hizo el Tema 23, o si el nivel actual —tabla con las diez categorías y desarrollo de las tres nuevas de 2021— es suficiente, dado que el Tema 23 ya lo cubre para el ámbito web.
- Pendiente confirmar con el IAM si interesa detallar la **numeración exacta de las medidas del Anexo II del ENS** aplicables al puesto, o si basta con los grupos y nombres actuales. El detalle numerado es más memorizable pero envejece con cada modificación normativa.
- **Vigencia**: los datos más sensibles a la obsolescencia son las cifras de criterios de WCAG (si se publicara WCAG 3.0 o una nueva versión 2.x), la versión armonizada de la EN 301 549 y la edición vigente del OWASP Top 10. Conviene fijar una revisión antes de cada convocatoria.
- Este tema comparte materia con los Temas 23, 24, 32, 36 y 39: si en el futuro se genera una **guía de solapamientos** del bloque técnico, este es uno de los nodos que más conexiones aporta.
