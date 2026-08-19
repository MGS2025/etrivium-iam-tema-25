# Tema 25 — Changelog

> **Título oficial**: Accesibilidad, diseño universal y usabilidad. Acceso y usabilidad de las tecnologías, productos y servicios relacionados con la sociedad de la información. Confidencialidad y disponibilidad de la información en puestos de usuario final. Conceptos de seguridad en el desarrollo de los sistemas.

---

## v1.0 — 2026-08-20 — Primera versión

**Estado**: pendiente de validación por María y Ana, y de revisión técnica del IAM (Jesús Cuadrado).

**Motivo**: desarrollo del Tema 25, dentro de la serie de temas técnicos generados desde cero, replicando la estructura y el formato de los Temas 1, 11 y 17-24 ya consolidados. Con este tema, el bloque técnico queda **completo y sin huecos de T11 a T25**.

### Alcance de la v1.0

| Entregable | Cantidad |
|---|---|
| Contenido teórico | ~21.500 palabras · 3 secciones (fieles al esqueleto oficial) con 33 epígrafes numerados, incluidos 2 de quinto nivel |
| Diagramas SVG inline | 14 (accesibles con `role`/`aria-label`, clases con sufijo único anti-colisión) |
| Banco de preguntas tipo test | 60 preguntas A/B/C con explicación y referencia, balanceadas **20/20/20** (verificado por el generador) |
| Casos prácticos | 3, uno por bloque del tema (auditoría de accesibilidad del portal de cita previa; incidente múltiple en el puesto de una Oficina de Atención a la Ciudadanía; contratación y verificación del desarrollo) · 10 puntos cada uno |
| Fuentes Tier 1 | 48 referencias canónicas (W3C, ISO/IEC, ETSI, NIST, MITRE, OWASP, IETF, BOE y DOUE) |

### Decisiones de generación

1. **Sin material de cliente**: solo el esqueleto `Test_Prompting/temas agosto/25.md`. Desarrollado desde fuentes canónicas —recomendaciones del W3C, normas ISO/IEC y ETSI, publicaciones especiales del NIST, catálogos de MITRE y OWASP, RFC del IETF y textos legales del BOE y del DOUE—, todas referenciadas.
2. **Estructura fiel al esqueleto oficial**: sus **3 secciones de primer nivel**, 8 epígrafes de segundo, 23 de tercero y **2 de cuarto** (3.2.3.1 y 3.2.3.2), sin añadir secciones nuevas. Es el primer tema de la serie que exige **cinco niveles de encabezado** en el HTML (`h2` a `h6` según la profundidad), para lo que se ha extendido el conversor de `build_t25.py` y añadido estilo propio de quinto nivel.
3. **El tema más extenso de la serie**: ~21.500 palabras medidas con `wc -w`, frente a las ~12.300 de T24, que era el máximo anterior. No es una desviación de criterio, sino consecuencia del enunciado: el temario reúne bajo un solo número **tres materias** que en otras convocatorias son temas independientes (accesibilidad y usabilidad; seguridad del puesto de usuario; seguridad en el desarrollo). Recortar cualquiera de ellas dejaría al opositor expuesto, porque el examen puede preguntar por las tres. La decisión de mantenerlo íntegro queda **abierta a validación** en el checklist.
4. **Reparto deliberado entre bloques**: aproximadamente 35 % accesibilidad y usabilidad, 30 % puesto de usuario final y 35 % desarrollo seguro, con 7 · 4 · 3 diagramas y 23 · 20 · 17 preguntas de test respectivamente.
5. **Caso de referencia único para todo el tema**: el **servicio municipal de cita previa y consulta de expedientes**, elegido porque encadena de forma natural los tres bloques —la aplicación pública debe ser accesible, el puesto desde el que se tramita debe proteger la información, y el software que lo sostiene debe haberse desarrollado con seguridad—. Planteado como **supuesto simplificado**, no como descripción de una aplicación municipal real concreta.
6. **Ejemplos de código reales en Java, Python, JavaScript, SQL y cabeceras HTTP** (mismo criterio que T21 con Java/Jakarta, T23 con HTML/JS/PHP y T24 con Kotlin/Swift/Dart): en codificación segura, la diferencia entre la construcción vulnerable y la correcta —concatenación frente a sentencia preparada, `innerHTML` frente a `textContent`— solo se aprecia en el lenguaje concreto. Cada fragmento contrasta explícitamente el antipatrón con su corrección.
7. **Núcleos conceptuales reforzados** por ser los que más rinden en examen y los que más se confunden: (a) accesibilidad / usabilidad / UX / diseño universal (D1); (b) dónde encaja cada pieza del tema en ISO/IEC 25010 (D3); (c) qué parte de WCAG es normativa (D4); (d) nivel frente a categoría en el ENS; (e) RPO frente a RTO (D11); (f) diferencial frente a incremental; (g) STRIDE y la propiedad que niega cada amenaza (D13); (h) CWE / CVE / CVSS y SAST / DAST / IAST / SCA (D14).
8. **Ampliaciones dentro de los epígrafes existentes** (decisión de generación, no del esqueleto): distinción entre brecha digital y barrera de accesibilidad; ATAG y UAAG junto a WCAG; los cinco requisitos de conformidad de WCAG; el Título X de la LOPDGDD sobre derechos digitales en el ámbito laboral; el borrado seguro de soportes; los modelos DAC/MAC/RBAC/ABAC; los casos de abuso como contrapartida de los casos de uso; y el cierre transversal que enlaza los tres bloques. Todas encajan en epígrafes previstos y cubren huecos que en examen se preguntan con frecuencia.
9. **Prudencia deliberada con dos datos**: (a) las medidas del **Anexo II del ENS** se citan por **grupo y nombre** (`op.acc`, `mp.eq`, `mp.si`, `mp.info`…) y no una a una con su numeración completa, salvo las de `mp.eq` sobre puesto despejado, bloqueo y equipos portátiles; (b) la referencia `[PSI-MADRID]` se formula como *el marco que el art. 12 del ENS exige a toda entidad del sector público*, **sin atribuir fecha ni denominación exacta** a la política municipal. Ambos puntos quedan marcados en el checklist para contraste con el IAM.
10. **Anti-colisión de SVG**: las clases CSS de cada diagrama llevan **sufijo numérico único** (`.t1`…`.t14`), evitando el fallo sistémico de estilos que se filtran de un SVG a otro al estar todos embebidos en la misma página (lección de T5).
11. **Distribución A/B/C fijada antes de redactar** y verificada con el generador (lección de T23 y T24): la secuencia de 60 letras se planificó de antemano con 20 de cada opción y `build_t25.py` confirma **20/20/20**.
12. **Cómputo de extensión medido, no estimado**: la cifra procede de `wc -w` sobre el `.md`, con el mismo criterio empleado en T24.

### Pendientes para QA / próxima iteración

- Validación de la **extensión** por María/Ana/IAM: mantener el tema íntegro, publicarlo dividido en tres partes navegables o recortar algún bloque.
- Contraste con el IAM de la **denominación exacta de la política de seguridad municipal** y de los datos publicados de la **declaración de accesibilidad y unidad responsable** del Ayuntamiento.
- Decidir si se detalla la **numeración completa de las medidas del Anexo II del ENS** aplicables al puesto de usuario.
- Decidir si se desarrolla el **OWASP Top 10:2021 riesgo a riesgo**, como hizo T23 para el ámbito web, o si basta el nivel actual dada esa cobertura previa.
- **Revisión de vigencia antes de cada convocatoria**: cifras de criterios de WCAG, versión armonizada de la EN 301 549 y edición vigente del OWASP Top 10 son los datos más sensibles a la obsolescencia.
- Verificación ortográfica con corrector es_ES (cuidado con los falsos positivos por términos técnicos en inglés: *phishing*, *ransomware*, *endpoint*, *hardening*, *token*, *sandbox*, *fuzzing*, *shift left*, *snapshot*, *backdoor*…).

### Origen

Generado el 2026-08-20 en el flujo de trabajo de eTrivium, replicando el patrón de los Temas 1 (v2.1), 11 (v3.2) y 17-24 (v1.0). `build_t25.py` y `_build_css.txt` persistidos en el repo.
