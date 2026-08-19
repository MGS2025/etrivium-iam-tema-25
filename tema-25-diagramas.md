# Tema 25 — Catálogo de Diagramas

> **Título oficial**: Accesibilidad, diseño universal y usabilidad. Acceso y usabilidad de las tecnologías, productos y servicios relacionados con la sociedad de la información. Confidencialidad y disponibilidad de la información en puestos de usuario final. Conceptos de seguridad en el desarrollo de los sistemas.
>
> **Versión**: v1.0
> **Fecha**: 2026-08-20
> **Autor**: ETRIVIUM
> **Formato**: SVG inline (zero-dependencias, escalable, imprimible, accesible con role/aria-label)
> **Paleta**: Ayuntamiento de Madrid #0055a0 (primario) + #d13c3c (alertas) + #2d8659 (ventajas) + #e89822 (callouts)
> **Nota técnica**: las clases CSS de cada SVG llevan sufijo numérico único (`.t1`, `.h1`…) para evitar colisiones de estilos entre los 14 diagramas embebidos en la misma página.

---

## Índice de diagramas

| ID | Título | Sección | Tipo | Formato |
|---|---|---|---|---|
| D1 | Accesibilidad, usabilidad, UX y diseño universal: cómo se relacionan | §1.1 | Esquema conceptual | 680×330 |
| D2 | Los siete principios del diseño universal | §1.1.2 | Bloques | 680×340 |
| D3 | ISO 9241 e ISO/IEC 25010: qué mide cada norma | §1.1.3 | Comparativa | 680×370 |
| D4 | Los cuatro principios POUR y la estructura normativa de WCAG | §1.2.1 | Jerarquía | 680×360 |
| D5 | Niveles de conformidad y evolución de WCAG | §1.2.1 | Escalera + línea temporal | 680×346 |
| D6 | La cadena normativa de la accesibilidad: de la ONU al RD 1112/2018 | §1.2.3 | Flujo normativo | 680×370 |
| D7 | Evaluación, declaración y reclamación de accesibilidad | §1.2.4 | Flujo | 680×350 |
| D8 | Amenazas y controles en el puesto de usuario final | §2.1 | Matriz | 680×370 |
| D9 | Control de acceso: cuatro pasos y tres factores | §2.2.1 | Flujo + bloques | 680×350 |
| D10 | Cifrado en reposo y en tránsito en el puesto | §2.2.2 | Esquema | 680×330 |
| D11 | Copias de seguridad: tipos, regla 3-2-1 y RPO/RTO | §2.3.2 | Esquema temporal | 680×370 |
| D12 | El ciclo de vida de desarrollo seguro (SSDLC) | §3.1.1 | Flujo por fases | 680×350 |
| D13 | STRIDE: seis amenazas y la propiedad que niega cada una | §3.1.2 | Tabla visual | 680×350 |
| D14 | OWASP Top 10:2021 y técnicas de verificación | §3.3 | Bloques + comparativa | 680×414 |

---

## D1 · Accesibilidad, usabilidad, UX y diseño universal: cómo se relacionan

**Sección**: §1.1 — Usabilidad y diseño universal
**Propósito**: Fijar de un vistazo la diferencia entre los cuatro conceptos que el tema exige no confundir, y su encadenamiento lógico.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 680 330" role="img" aria-label="Relación entre diseño universal, accesibilidad, usabilidad y experiencia de usuario: el diseño universal es la estrategia, la accesibilidad el resultado exigible por ley, la usabilidad el grado de calidad de uso y la experiencia de usuario la vivencia completa; abajo se sitúa el ajuste razonable como medida individual y subsidiaria">
  <style>.t1{font:700 11.5px system-ui,sans-serif;fill:#fff}.s1{font:9.5px system-ui,sans-serif;fill:#fff}.h1{font:700 13px system-ui,sans-serif;fill:#0055a0}.k1{font:700 10px system-ui,sans-serif;fill:#0055a0}.d1{font:9.5px system-ui,sans-serif;fill:#333}</style>
  <text x="340" y="20" text-anchor="middle" class="h1">Cuatro conceptos que no deben confundirse</text>
  <rect x="20" y="34" width="152" height="86" rx="6" fill="#0055a0"/>
  <text x="96" y="54" text-anchor="middle" class="t1">DISEÑO UNIVERSAL</text>
  <text x="96" y="72" text-anchor="middle" class="s1">La ESTRATEGIA</text>
  <text x="96" y="90" text-anchor="middle" class="s1">Diseñar desde el origen</text>
  <text x="96" y="106" text-anchor="middle" class="s1">para todas las personas</text>
  <rect x="187" y="34" width="152" height="86" rx="6" fill="#2d8659"/>
  <text x="263" y="54" text-anchor="middle" class="t1">ACCESIBILIDAD</text>
  <text x="263" y="72" text-anchor="middle" class="s1">El RESULTADO exigible</text>
  <text x="263" y="90" text-anchor="middle" class="s1">Condición binaria:</text>
  <text x="263" y="106" text-anchor="middle" class="s1">se puede usar o no</text>
  <rect x="354" y="34" width="152" height="86" rx="6" fill="#e89822"/>
  <text x="430" y="54" text-anchor="middle" class="t1">USABILIDAD</text>
  <text x="430" y="72" text-anchor="middle" class="s1">El GRADO de calidad</text>
  <text x="430" y="90" text-anchor="middle" class="s1">Eficacia + eficiencia</text>
  <text x="430" y="106" text-anchor="middle" class="s1">+ satisfacción</text>
  <rect x="521" y="34" width="139" height="86" rx="6" fill="#888"/>
  <text x="590" y="54" text-anchor="middle" class="t1">EXPERIENCIA (UX)</text>
  <text x="590" y="72" text-anchor="middle" class="s1">La VIVENCIA completa</text>
  <text x="590" y="90" text-anchor="middle" class="s1">Antes, durante</text>
  <text x="590" y="106" text-anchor="middle" class="s1">y después del uso</text>
  <path d="M172 77 L187 77" stroke="#0055a0" stroke-width="2" marker-end="url(#a1)"/>
  <path d="M339 77 L354 77" stroke="#0055a0" stroke-width="2" marker-end="url(#a1)"/>
  <path d="M506 77 L521 77" stroke="#0055a0" stroke-width="2" marker-end="url(#a1)"/>
  <defs><marker id="a1" markerWidth="7" markerHeight="7" refX="6" refY="3" orient="auto"><path d="M0,0 L6,3 L0,6 z" fill="#0055a0"/></marker></defs>
  <text x="20" y="140" class="k1">¿EXIGIBLE POR LEY?</text>
  <rect x="20" y="146" width="152" height="26" rx="4" fill="#eef3f8"/><text x="96" y="163" text-anchor="middle" class="d1">Principio rector</text>
  <rect x="187" y="146" width="152" height="26" rx="4" fill="#2d8659"/><text x="263" y="163" text-anchor="middle" class="s1">SÍ — RD 1112/2018</text>
  <rect x="354" y="146" width="152" height="26" rx="4" fill="#eef3f8"/><text x="430" y="163" text-anchor="middle" class="d1">No (sí en pliegos)</text>
  <rect x="521" y="146" width="139" height="26" rx="4" fill="#eef3f8"/><text x="590" y="163" text-anchor="middle" class="d1">No</text>
  <line x1="20" y1="188" x2="660" y2="188" stroke="#ccc" stroke-width="1"/>
  <text x="340" y="208" text-anchor="middle" class="k1">Orden correcto de actuación</text>
  <rect x="40" y="220" width="170" height="42" rx="5" fill="#0055a0"/>
  <text x="125" y="238" text-anchor="middle" class="t1">1. DISEÑO UNIVERSAL</text>
  <text x="125" y="254" text-anchor="middle" class="s1">para todos, desde el origen</text>
  <rect x="255" y="220" width="170" height="42" rx="5" fill="#2d8659"/>
  <text x="340" y="238" text-anchor="middle" class="t1">2. TECNOLOGÍA DE APOYO</text>
  <text x="340" y="254" text-anchor="middle" class="s1">compatible con el diseño</text>
  <rect x="470" y="220" width="170" height="42" rx="5" fill="#e89822"/>
  <text x="555" y="238" text-anchor="middle" class="t1">3. AJUSTE RAZONABLE</text>
  <text x="555" y="254" text-anchor="middle" class="s1">individual y subsidiario</text>
  <path d="M210 241 L255 241" stroke="#0055a0" stroke-width="2" marker-end="url(#a1)"/>
  <path d="M425 241 L470 241" stroke="#0055a0" stroke-width="2" marker-end="url(#a1)"/>
  <rect x="70" y="274" width="540" height="32" rx="5" fill="none" stroke="#d13c3c" stroke-width="2"/>
  <text x="340" y="294" text-anchor="middle" style="font:700 10.5px system-ui;fill:#d13c3c">Nunca al revés: una web inaccesible «compensada» con teléfono NO cumple la norma</text>
  <text x="670" y="322" text-anchor="end" style="font:11px system-ui;fill:#666">[Fuente: CDPD; TRLGDPD; ISO9241-11; WAI]</text>
</svg>
```

---

## D2 · Los siete principios del diseño universal

**Sección**: §1.1.2 — Fundamentos del diseño universal y diseño para todos
**Propósito**: Memorizar los siete principios de 1997 con su traducción directa al software.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 680 340" role="img" aria-label="Los siete principios del diseño universal formulados por el Center for Universal Design en 1997: uso equitativo, flexibilidad de uso, uso simple e intuitivo, información perceptible, tolerancia al error, escaso esfuerzo físico y tamaño y espacio adecuados, cada uno con su traducción al diseño de software">
  <style>.t2{font:700 10.5px system-ui,sans-serif;fill:#fff}.s2{font:9px system-ui,sans-serif;fill:#fff}.h2{font:700 13px system-ui,sans-serif;fill:#0055a0}.k2{font:700 9.5px system-ui,sans-serif;fill:#0055a0}.d2{font:9px system-ui,sans-serif;fill:#333}</style>
  <text x="340" y="20" text-anchor="middle" class="h2">Los 7 principios del diseño universal (CUD, 1997)</text>
  <rect x="20" y="34" width="210" height="62" rx="5" fill="#0055a0"/>
  <text x="125" y="52" text-anchor="middle" class="t2">1 · USO EQUITATIVO</text>
  <text x="125" y="70" text-anchor="middle" class="s2">Útil para todos, sin segregar</text>
  <text x="125" y="86" text-anchor="middle" class="s2">→ un solo sitio, no versión aparte</text>
  <rect x="240" y="34" width="210" height="62" rx="5" fill="#0055a0"/>
  <text x="345" y="52" text-anchor="middle" class="t2">2 · FLEXIBILIDAD DE USO</text>
  <text x="345" y="70" text-anchor="middle" class="s2">Se adapta a preferencias</text>
  <text x="345" y="86" text-anchor="middle" class="s2">→ ratón, teclado, voz, táctil</text>
  <rect x="460" y="34" width="200" height="62" rx="5" fill="#0055a0"/>
  <text x="560" y="52" text-anchor="middle" class="t2">3 · SIMPLE E INTUITIVO</text>
  <text x="560" y="70" text-anchor="middle" class="s2">Fácil sin experiencia previa</text>
  <text x="560" y="86" text-anchor="middle" class="s2">→ lenguaje claro, sin jerga</text>
  <rect x="20" y="106" width="210" height="62" rx="5" fill="#2d8659"/>
  <text x="125" y="124" text-anchor="middle" class="t2">4 · INFORMACIÓN PERCEPTIBLE</text>
  <text x="125" y="142" text-anchor="middle" class="s2">Llega sea cual sea el sentido</text>
  <text x="125" y="158" text-anchor="middle" class="s2">→ nunca solo color; subtítulos</text>
  <rect x="240" y="106" width="210" height="62" rx="5" fill="#2d8659"/>
  <text x="345" y="124" text-anchor="middle" class="t2">5 · TOLERANCIA AL ERROR</text>
  <text x="345" y="142" text-anchor="middle" class="s2">Minimiza riesgo y consecuencia</text>
  <text x="345" y="158" text-anchor="middle" class="s2">→ confirmar, deshacer, conservar</text>
  <rect x="460" y="106" width="200" height="62" rx="5" fill="#2d8659"/>
  <text x="560" y="124" text-anchor="middle" class="t2">6 · ESCASO ESFUERZO FÍSICO</text>
  <text x="560" y="142" text-anchor="middle" class="s2">Uso cómodo y sin fatiga</text>
  <text x="560" y="158" text-anchor="middle" class="s2">→ sin gestos complejos</text>
  <rect x="130" y="178" width="420" height="52" rx="5" fill="#e89822"/>
  <text x="340" y="197" text-anchor="middle" class="t2">7 · TAMAÑO Y ESPACIO ADECUADOS PARA EL ACCESO Y EL USO</text>
  <text x="340" y="215" text-anchor="middle" class="s2">→ diseño adaptable, sin desplazamiento horizontal, zonas de pulsación suficientes</text>
  <line x1="20" y1="246" x2="660" y2="246" stroke="#ccc" stroke-width="1"/>
  <text x="20" y="266" class="k2">EL VOCABULARIO ESPAÑOL EQUIVALENTE (RDL 1/2013)</text>
  <rect x="20" y="274" width="205" height="40" rx="4" fill="#eef3f8"/>
  <text x="122" y="290" text-anchor="middle" class="d2">Accesibilidad universal</text>
  <text x="122" y="305" text-anchor="middle" class="d2">= la condición del resultado</text>
  <rect x="237" y="274" width="206" height="40" rx="4" fill="#eef3f8"/>
  <text x="340" y="290" text-anchor="middle" class="d2">Diseño para todas las personas</text>
  <text x="340" y="305" text-anchor="middle" class="d2">= la actividad de diseñar</text>
  <rect x="455" y="274" width="205" height="40" rx="4" fill="#eef3f8"/>
  <text x="557" y="290" text-anchor="middle" class="d2">Ajustes razonables</text>
  <text x="557" y="305" text-anchor="middle" class="d2">= medida individual</text>
  <text x="670" y="332" text-anchor="end" style="font:11px system-ui;fill:#666">[Fuente: CUD; TRLGDPD; CDPD]</text>
</svg>
```

---

## D3 · ISO 9241 e ISO/IEC 25010: qué mide cada norma

**Sección**: §1.1.3 — Modelos de calidad e ISO/IEC 9241 e ISO/IEC 25010
**Propósito**: Separar las dos familias de normas y localizar exactamente dónde encajan accesibilidad, disponibilidad y confidencialidad dentro del modelo de calidad del producto.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 680 370" role="img" aria-label="Comparativa entre la serie ISO 9241 de ergonomía, que mide el proceso y la interacción, y la familia ISO/IEC 25000 SQuaRE con su modelo ISO/IEC 25010, que mide el producto software; se destaca que accesibilidad es subcaracterística de usabilidad, disponibilidad lo es de fiabilidad y confidencialidad e integridad lo son de seguridad">
  <style>.t3{font:700 10.5px system-ui,sans-serif;fill:#fff}.s3{font:9px system-ui,sans-serif;fill:#fff}.h3{font:700 13px system-ui,sans-serif;fill:#0055a0}.k3{font:700 9.5px system-ui,sans-serif;fill:#0055a0}.d3{font:9px system-ui,sans-serif;fill:#333}</style>
  <text x="340" y="20" text-anchor="middle" class="h3">Dos familias de normas, dos objetos distintos</text>
  <rect x="20" y="32" width="315" height="30" rx="5" fill="#0055a0"/>
  <text x="177" y="52" text-anchor="middle" class="t3">ISO 9241 — ergonomía: mide PROCESO e INTERACCIÓN</text>
  <rect x="345" y="32" width="315" height="30" rx="5" fill="#2d8659"/>
  <text x="502" y="52" text-anchor="middle" class="t3">ISO/IEC 25000 (SQuaRE) — mide el PRODUCTO</text>
  <rect x="20" y="70" width="315" height="26" rx="4" fill="#eef3f8"/><text x="30" y="87" class="d3">9241-11 · Usabilidad: eficacia + eficiencia + satisfacción</text>
  <rect x="20" y="100" width="315" height="26" rx="4" fill="#eef3f8"/><text x="30" y="117" class="d3">9241-110 · Los 7 principios de interacción</text>
  <rect x="20" y="130" width="315" height="26" rx="4" fill="#eef3f8"/><text x="30" y="147" class="d3">9241-171 · Guía de accesibilidad del software</text>
  <rect x="20" y="160" width="315" height="26" rx="4" fill="#eef3f8"/><text x="30" y="177" class="d3">9241-210 · Diseño centrado en las personas (iterativo)</text>
  <rect x="345" y="70" width="315" height="26" rx="4" fill="#eef3f8"/><text x="355" y="87" class="d3">2501n · Modelos de calidad → ISO/IEC 25010</text>
  <rect x="345" y="100" width="315" height="26" rx="4" fill="#eef3f8"/><text x="355" y="117" class="d3">2502n medición · 2503n requisitos · 2504n evaluación</text>
  <rect x="345" y="130" width="315" height="56" rx="4" fill="#eef3f8"/>
  <text x="355" y="147" class="d3">Tres modelos: calidad del PRODUCTO (25010),</text>
  <text x="355" y="162" class="d3">calidad EN USO y calidad de los DATOS (25012)</text>
  <text x="355" y="178" class="d3">25040 · proceso de evaluación</text>
  <line x1="20" y1="198" x2="660" y2="198" stroke="#ccc" stroke-width="1"/>
  <text x="340" y="218" text-anchor="middle" class="k3">Las 8 características de ISO/IEC 25010 y dónde está cada pieza de este tema</text>
  <rect x="20" y="228" width="103" height="30" rx="4" fill="#888"/><text x="71" y="247" text-anchor="middle" class="s3">Adecuación func.</text>
  <rect x="129" y="228" width="103" height="30" rx="4" fill="#888"/><text x="180" y="247" text-anchor="middle" class="s3">Eficiencia desemp.</text>
  <rect x="238" y="228" width="103" height="30" rx="4" fill="#888"/><text x="289" y="247" text-anchor="middle" class="s3">Compatibilidad</text>
  <rect x="347" y="228" width="103" height="30" rx="4" fill="#e89822"/><text x="398" y="247" text-anchor="middle" class="s3">USABILIDAD</text>
  <rect x="456" y="228" width="103" height="30" rx="4" fill="#0055a0"/><text x="507" y="247" text-anchor="middle" class="s3">FIABILIDAD</text>
  <rect x="565" y="228" width="95" height="30" rx="4" fill="#d13c3c"/><text x="612" y="247" text-anchor="middle" class="s3">SEGURIDAD</text>
  <rect x="238" y="264" width="103" height="26" rx="4" fill="#888"/><text x="289" y="281" text-anchor="middle" class="s3">Mantenibilidad</text>
  <rect x="129" y="264" width="103" height="26" rx="4" fill="#888"/><text x="180" y="281" text-anchor="middle" class="s3">Portabilidad</text>
  <path d="M398 258 L398 296" stroke="#e89822" stroke-width="2"/>
  <path d="M507 258 L507 296" stroke="#0055a0" stroke-width="2"/>
  <path d="M612 258 L612 296" stroke="#d13c3c" stroke-width="2"/>
  <rect x="347" y="296" width="103" height="34" rx="4" fill="#fdf1de" stroke="#e89822"/>
  <text x="398" y="311" text-anchor="middle" class="d3">ACCESIBILIDAD</text>
  <text x="398" y="324" text-anchor="middle" class="d3">(subcaracterística)</text>
  <rect x="456" y="296" width="103" height="34" rx="4" fill="#e6eff7" stroke="#0055a0"/>
  <text x="507" y="311" text-anchor="middle" class="d3">DISPONIBILIDAD</text>
  <text x="507" y="324" text-anchor="middle" class="d3">(subcaracterística)</text>
  <rect x="565" y="296" width="95" height="34" rx="4" fill="#fbe9e9" stroke="#d13c3c"/>
  <text x="612" y="311" text-anchor="middle" class="d3">Confidencialidad</text>
  <text x="612" y="324" text-anchor="middle" class="d3">e integridad</text>
  <text x="30" y="316" class="k3">Las tres piezas que dan título</text>
  <text x="30" y="330" class="k3">a este tema están en 3 lugares distintos</text>
  <text x="670" y="360" text-anchor="end" style="font:11px system-ui;fill:#666">[Fuente: ISO9241-11; ISO9241-210; ISO25000; ISO25010]</text>
</svg>
```

---

## D4 · Los cuatro principios POUR y la estructura normativa de WCAG

**Sección**: §1.2.1 — Pautas de accesibilidad al contenido web WCAG
**Propósito**: Fijar la jerarquía principio → pauta → criterio → técnica, y qué parte de ella es normativa.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 680 360" role="img" aria-label="Estructura de WCAG: cuatro principios POUR (perceptible, operable, comprensible y robusto) con sus trece pautas, de las que cuelgan los criterios de conformidad verificables en niveles A, AA y AAA, y por debajo las técnicas, que son informativas y no normativas">
  <style>.t4{font:700 10.5px system-ui,sans-serif;fill:#fff}.s4{font:9px system-ui,sans-serif;fill:#fff}.h4{font:700 13px system-ui,sans-serif;fill:#0055a0}.k4{font:700 9.5px system-ui,sans-serif;fill:#0055a0}.d4{font:9px system-ui,sans-serif;fill:#333}</style>
  <text x="340" y="20" text-anchor="middle" class="h4">WCAG 2.2 — los 4 principios POUR y sus 13 pautas</text>
  <rect x="20" y="32" width="155" height="40" rx="5" fill="#0055a0"/>
  <text x="97" y="50" text-anchor="middle" class="t4">P · PERCEPTIBLE</text>
  <text x="97" y="65" text-anchor="middle" class="s4">Que se pueda percibir</text>
  <rect x="185" y="32" width="155" height="40" rx="5" fill="#2d8659"/>
  <text x="262" y="50" text-anchor="middle" class="t4">O · OPERABLE</text>
  <text x="262" y="65" text-anchor="middle" class="s4">Que se pueda manejar</text>
  <rect x="350" y="32" width="155" height="40" rx="5" fill="#e89822"/>
  <text x="427" y="50" text-anchor="middle" class="t4">C · COMPRENSIBLE</text>
  <text x="427" y="65" text-anchor="middle" class="s4">Que se entienda</text>
  <rect x="515" y="32" width="145" height="40" rx="5" fill="#888"/>
  <text x="587" y="50" text-anchor="middle" class="t4">R · ROBUSTO</text>
  <text x="587" y="65" text-anchor="middle" class="s4">Que lo lea la tecnología</text>
  <rect x="20" y="80" width="155" height="86" rx="4" fill="#e6eff7"/>
  <text x="28" y="96" class="d4">1.1 Alternativas textuales</text>
  <text x="28" y="112" class="d4">1.2 Medios tempodepend.</text>
  <text x="28" y="128" class="d4">1.3 Adaptable (semántica)</text>
  <text x="28" y="144" class="d4">1.4 Distinguible</text>
  <text x="28" y="160" class="d4">(contraste 4,5:1 · 200 %)</text>
  <rect x="185" y="80" width="155" height="86" rx="4" fill="#e6f2ec"/>
  <text x="193" y="96" class="d4">2.1 Accesible por teclado</text>
  <text x="193" y="112" class="d4">2.2 Tiempo suficiente</text>
  <text x="193" y="128" class="d4">2.3 Convulsiones</text>
  <text x="193" y="144" class="d4">2.4 Navegable (foco)</text>
  <text x="193" y="160" class="d4">2.5 Modalidades de entrada</text>
  <rect x="350" y="80" width="155" height="86" rx="4" fill="#fdf1de"/>
  <text x="358" y="96" class="d4">3.1 Legible (idioma)</text>
  <text x="358" y="112" class="d4">3.2 Predecible</text>
  <text x="358" y="128" class="d4">3.3 Entrada de datos</text>
  <text x="358" y="144" class="d4">asistida (errores,</text>
  <text x="358" y="160" class="d4">etiquetas, autenticación)</text>
  <rect x="515" y="80" width="145" height="86" rx="4" fill="#f0f0f0"/>
  <text x="523" y="96" class="d4">4.1 Compatible</text>
  <text x="523" y="112" class="d4">4.1.2 Nombre, función</text>
  <text x="523" y="128" class="d4">y valor (ARIA)</text>
  <text x="523" y="144" class="d4">4.1.3 Mensajes de</text>
  <text x="523" y="160" class="d4">estado</text>
  <line x1="20" y1="182" x2="660" y2="182" stroke="#ccc" stroke-width="1"/>
  <text x="340" y="202" text-anchor="middle" class="k4">La jerarquía normativa: qué obliga y qué solo orienta</text>
  <rect x="150" y="212" width="380" height="30" rx="5" fill="#0055a0"/>
  <text x="340" y="232" text-anchor="middle" class="t4">4 PRINCIPIOS  —  objetivos generales</text>
  <rect x="150" y="248" width="380" height="30" rx="5" fill="#3d7fb8"/>
  <text x="340" y="268" text-anchor="middle" class="t4">13 PAUTAS  —  NO verificables por sí solas</text>
  <rect x="150" y="284" width="380" height="34" rx="5" fill="#2d8659"/>
  <text x="340" y="299" text-anchor="middle" class="t4">86 CRITERIOS DE CONFORMIDAD  —  A / AA / AAA</text>
  <text x="340" y="313" text-anchor="middle" class="s4">VERIFICABLES · lo único NORMATIVO</text>
  <rect x="150" y="324" width="380" height="26" rx="5" fill="#f0f0f0" stroke="#888" stroke-dasharray="4 2"/>
  <text x="340" y="342" text-anchor="middle" class="d4">TÉCNICAS suficientes y consultivas + FALLOS  —  INFORMATIVAS</text>
  <text x="30" y="300" class="k4">Solo esta capa</text>
  <text x="30" y="314" class="k4">se audita y se</text>
  <text x="30" y="328" class="k4">declara</text>
  <text x="670" y="356" text-anchor="end" style="font:11px system-ui;fill:#666">[Fuente: WCAG22; WAI]</text>
</svg>
```

---

## D5 · Niveles de conformidad y evolución de WCAG

**Sección**: §1.2.1 — Pautas de accesibilidad al contenido web WCAG
**Propósito**: Fijar el carácter acumulativo de los niveles, el nivel legalmente exigible y las fechas y aportaciones de cada versión.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 680 346" role="img" aria-label="Niveles de conformidad de WCAG: el nivel A es la base, el nivel AA incluye A y es el exigido por ley en el sector público, y el nivel AAA no se recomienda exigir para sitios completos; debajo, la línea temporal de las versiones WCAG 1.0 de 1999, 2.0 de 2008, 2.1 de 2018 y 2.2 de octubre de 2023">
  <style>.t5{font:700 11px system-ui,sans-serif;fill:#fff}.s5{font:9px system-ui,sans-serif;fill:#fff}.h5{font:700 13px system-ui,sans-serif;fill:#0055a0}.k5{font:700 9.5px system-ui,sans-serif;fill:#0055a0}.d5{font:9px system-ui,sans-serif;fill:#333}</style>
  <text x="340" y="20" text-anchor="middle" class="h5">Niveles de conformidad: acumulativos, no alternativos</text>
  <rect x="60" y="120" width="150" height="40" rx="5" fill="#888"/>
  <text x="135" y="136" text-anchor="middle" class="t5">NIVEL A</text>
  <text x="135" y="152" text-anchor="middle" class="s5">31 criterios · mínimo</text>
  <rect x="230" y="90" width="190" height="70" rx="5" fill="#2d8659"/>
  <text x="325" y="110" text-anchor="middle" class="t5">NIVEL AA</text>
  <text x="325" y="128" text-anchor="middle" class="s5">= todos los A + 24 criterios AA</text>
  <text x="325" y="146" text-anchor="middle" class="s5">EXIGIDO POR LEY (sector público)</text>
  <rect x="440" y="60" width="190" height="100" rx="5" fill="#0055a0"/>
  <text x="535" y="82" text-anchor="middle" class="t5">NIVEL AAA</text>
  <text x="535" y="100" text-anchor="middle" class="s5">= A + AA + 31 criterios AAA</text>
  <text x="535" y="118" text-anchor="middle" class="s5">El W3C NO recomienda</text>
  <text x="535" y="136" text-anchor="middle" class="s5">exigirlo para sitios completos</text>
  <text x="340" y="180" text-anchor="middle" class="k5">Total WCAG 2.2: 86 criterios de conformidad (31 A + 24 AA + 31 AAA)</text>
  <line x1="20" y1="194" x2="660" y2="194" stroke="#ccc" stroke-width="1"/>
  <text x="340" y="214" text-anchor="middle" class="k5">Evolución de las versiones</text>
  <line x1="60" y1="250" x2="620" y2="250" stroke="#0055a0" stroke-width="2"/>
  <circle cx="90" cy="250" r="6" fill="#888"/>
  <text x="90" y="238" text-anchor="middle" class="d5">1999</text>
  <text x="90" y="270" text-anchor="middle" class="d5">WCAG 1.0</text>
  <text x="90" y="284" text-anchor="middle" class="d5">14 pautas</text>
  <circle cx="230" cy="250" r="6" fill="#0055a0"/>
  <text x="230" y="238" text-anchor="middle" class="d5">dic 2008</text>
  <text x="230" y="270" text-anchor="middle" class="d5">WCAG 2.0 · 61 criterios</text>
  <text x="230" y="284" text-anchor="middle" class="d5">= ISO/IEC 40500:2012</text>
  <circle cx="400" cy="250" r="6" fill="#2d8659"/>
  <text x="400" y="238" text-anchor="middle" class="d5">jun 2018</text>
  <text x="400" y="270" text-anchor="middle" class="d5">WCAG 2.1 · 78 criterios</text>
  <text x="400" y="284" text-anchor="middle" class="d5">móvil, baja visión, cognitiva</text>
  <circle cx="580" cy="250" r="7" fill="#e89822"/>
  <text x="580" y="238" text-anchor="middle" class="d5">5 oct 2023</text>
  <text x="580" y="270" text-anchor="middle" class="d5">WCAG 2.2 · 86 criterios</text>
  <text x="580" y="284" text-anchor="middle" class="d5">+9 nuevos · retira 4.1.1</text>
  <rect x="110" y="298" width="460" height="24" rx="5" fill="none" stroke="#0055a0" stroke-width="2"/>
  <text x="340" y="314" text-anchor="middle" style="font:700 10px system-ui;fill:#0055a0">Conformidad de PÁGINAS COMPLETAS y de PROCESOS COMPLETOS</text>
  <text x="670" y="340" text-anchor="end" style="font:11px system-ui;fill:#666">[Fuente: WCAG20; WCAG21; WCAG22]</text>
</svg>
```

---

## D6 · La cadena normativa de la accesibilidad: de la ONU al RD 1112/2018

**Sección**: §1.2.3 — Marco normativo en la Administración Pública
**Propósito**: Ordenar los cinco eslabones normativos y el contenido esencial del real decreto que obliga a un ayuntamiento.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 680 370" role="img" aria-label="Cadena normativa de la accesibilidad digital: Convención de la ONU de 2006, Real Decreto Legislativo 1/2013, Directiva europea 2016/2102, Real Decreto 1112/2018 que la transpone en España, y Directiva 2019/882 traspuesta por la Ley 11/2023 que extiende la accesibilidad al sector privado; se detallan las obligaciones del RD 1112/2018">
  <style>.t6{font:700 10.5px system-ui,sans-serif;fill:#fff}.s6{font:9px system-ui,sans-serif;fill:#fff}.h6{font:700 13px system-ui,sans-serif;fill:#0055a0}.k6{font:700 9.5px system-ui,sans-serif;fill:#0055a0}.d6{font:9px system-ui,sans-serif;fill:#333}</style>
  <text x="340" y="20" text-anchor="middle" class="h6">De la Convención de la ONU al deber de un ayuntamiento</text>
  <rect x="20" y="34" width="126" height="66" rx="5" fill="#888"/>
  <text x="83" y="52" text-anchor="middle" class="t6">2006 · ONU</text>
  <text x="83" y="70" text-anchor="middle" class="s6">Convención CDPD</text>
  <text x="83" y="85" text-anchor="middle" class="s6">art. 2 diseño universal</text>
  <text x="83" y="97" text-anchor="middle" class="s6">art. 9 acceso a las TIC</text>
  <rect x="154" y="34" width="126" height="66" rx="5" fill="#888"/>
  <text x="217" y="52" text-anchor="middle" class="t6">2013 · ESPAÑA</text>
  <text x="217" y="70" text-anchor="middle" class="s6">RDL 1/2013</text>
  <text x="217" y="85" text-anchor="middle" class="s6">accesibilidad universal,</text>
  <text x="217" y="97" text-anchor="middle" class="s6">diseño para todos</text>
  <rect x="288" y="34" width="126" height="66" rx="5" fill="#0055a0"/>
  <text x="351" y="52" text-anchor="middle" class="t6">2016 · UE</text>
  <text x="351" y="70" text-anchor="middle" class="s6">Directiva 2016/2102</text>
  <text x="351" y="85" text-anchor="middle" class="s6">webs y apps del</text>
  <text x="351" y="97" text-anchor="middle" class="s6">SECTOR PÚBLICO</text>
  <rect x="422" y="34" width="126" height="66" rx="5" fill="#2d8659"/>
  <text x="485" y="52" text-anchor="middle" class="t6">2018 · ESPAÑA</text>
  <text x="485" y="70" text-anchor="middle" class="s6">RD 1112/2018</text>
  <text x="485" y="85" text-anchor="middle" class="s6">transposición</text>
  <text x="485" y="97" text-anchor="middle" class="s6">→ nivel AA</text>
  <rect x="556" y="34" width="104" height="66" rx="5" fill="#e89822"/>
  <text x="608" y="52" text-anchor="middle" class="t6">2019/2023</text>
  <text x="608" y="70" text-anchor="middle" class="s6">Dir. 2019/882 (EAA)</text>
  <text x="608" y="85" text-anchor="middle" class="s6">Ley 11/2023</text>
  <text x="608" y="97" text-anchor="middle" class="s6">→ sector PRIVADO</text>
  <defs><marker id="a6" markerWidth="7" markerHeight="7" refX="6" refY="3" orient="auto"><path d="M0,0 L6,3 L0,6 z" fill="#0055a0"/></marker></defs>
  <path d="M146 67 L154 67" stroke="#0055a0" stroke-width="2" marker-end="url(#a6)"/>
  <path d="M280 67 L288 67" stroke="#0055a0" stroke-width="2" marker-end="url(#a6)"/>
  <path d="M414 67 L422 67" stroke="#0055a0" stroke-width="2" marker-end="url(#a6)"/>
  <path d="M548 67 L556 67" stroke="#0055a0" stroke-width="2" marker-end="url(#a6)"/>
  <line x1="20" y1="116" x2="660" y2="116" stroke="#ccc" stroke-width="1"/>
  <text x="340" y="136" text-anchor="middle" class="k6">Qué obliga exactamente el RD 1112/2018 a una entidad local</text>
  <rect x="20" y="148" width="208" height="50" rx="5" fill="#0055a0"/>
  <text x="124" y="166" text-anchor="middle" class="t6">REQUISITO TÉCNICO</text>
  <text x="124" y="183" text-anchor="middle" class="s6">UNE-EN 301 549 → WCAG nivel AA</text>
  <rect x="238" y="148" width="208" height="50" rx="5" fill="#0055a0"/>
  <text x="342" y="166" text-anchor="middle" class="t6">ÁMBITO</text>
  <text x="342" y="183" text-anchor="middle" class="s6">webs, intranets, extranets y apps</text>
  <rect x="456" y="148" width="204" height="50" rx="5" fill="#0055a0"/>
  <text x="558" y="166" text-anchor="middle" class="t6">UNIDAD RESPONSABLE</text>
  <text x="558" y="183" text-anchor="middle" class="s6">obligatoria en cada organismo</text>
  <rect x="20" y="206" width="208" height="50" rx="5" fill="#2d8659"/>
  <text x="124" y="224" text-anchor="middle" class="t6">DECLARACIÓN</text>
  <text x="124" y="241" text-anchor="middle" class="s6">modelo Decisión (UE) 2018/1523</text>
  <rect x="238" y="206" width="208" height="50" rx="5" fill="#2d8659"/>
  <text x="342" y="224" text-anchor="middle" class="t6">QUEJA Y RECLAMACIÓN</text>
  <text x="342" y="241" text-anchor="middle" class="s6">mecanismo accesible y con plazo</text>
  <rect x="456" y="206" width="204" height="50" rx="5" fill="#2d8659"/>
  <text x="558" y="224" text-anchor="middle" class="t6">SEGUIMIENTO E INFORME</text>
  <text x="558" y="241" text-anchor="middle" class="s6">Decisión (UE) 2018/1524</text>
  <rect x="20" y="266" width="320" height="58" rx="5" fill="#fbe9e9" stroke="#d13c3c"/>
  <text x="180" y="284" text-anchor="middle" style="font:700 10px system-ui;fill:#d13c3c">CARGA DESPROPORCIONADA (art. 7)</text>
  <text x="180" y="300" text-anchor="middle" class="d6">Motivada, declarada y con alternativa accesible</text>
  <text x="180" y="315" text-anchor="middle" class="d6">NUNCA por falta de prioridad, tiempo o conocimiento</text>
  <rect x="350" y="266" width="310" height="58" rx="5" fill="#eef3f8" stroke="#0055a0"/>
  <text x="505" y="284" text-anchor="middle" class="k6">PLAZOS (ya vencidos: exigencia plena)</text>
  <text x="505" y="300" text-anchor="middle" class="d6">Webs nuevas 23-sep-2019 · anteriores 23-sep-2020</text>
  <text x="505" y="315" text-anchor="middle" class="d6">Aplicaciones móviles: 23-jun-2021</text>
  <text x="670" y="346" text-anchor="end" style="font:11px system-ui;fill:#666">[Fuente: CDPD; TRLGDPD; DIR2016-2102; RD1112-2018; LEY11-2023]</text>
  <text x="670" y="362" text-anchor="end" style="font:11px system-ui;fill:#666">Norma técnica de referencia: EN301549</text>
</svg>
```

---

## D7 · Evaluación, declaración y reclamación de accesibilidad

**Sección**: §1.2.4 — Evaluación, auditoría y declaración de accesibilidad
**Propósito**: Encadenar los cinco pasos de WCAG-EM, los tres tipos de comprobación con su alcance real y el contenido obligatorio de la declaración.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 680 350" role="img" aria-label="Proceso de evaluación de accesibilidad: los cinco pasos de la metodología WCAG-EM, los tres tipos de comprobación (automática, manual experta y con usuarios) con la advertencia de que la automática solo detecta una parte de los criterios, y el contenido obligatorio de la declaración de accesibilidad">
  <style>.t7{font:700 10px system-ui,sans-serif;fill:#fff}.s7{font:9px system-ui,sans-serif;fill:#fff}.h7{font:700 13px system-ui,sans-serif;fill:#0055a0}.k7{font:700 9.5px system-ui,sans-serif;fill:#0055a0}.d7{font:9px system-ui,sans-serif;fill:#333}</style>
  <text x="340" y="20" text-anchor="middle" class="h7">De la evaluación a la declaración pública</text>
  <text x="20" y="40" class="k7">1 · METODOLOGÍA WCAG-EM — cinco pasos</text>
  <rect x="20" y="48" width="122" height="42" rx="5" fill="#0055a0"/>
  <text x="81" y="65" text-anchor="middle" class="t7">1 · ALCANCE</text>
  <text x="81" y="80" text-anchor="middle" class="s7">qué sitio y qué nivel</text>
  <rect x="150" y="48" width="122" height="42" rx="5" fill="#0055a0"/>
  <text x="211" y="65" text-anchor="middle" class="t7">2 · EXPLORAR</text>
  <text x="211" y="80" text-anchor="middle" class="s7">tipos de página</text>
  <rect x="280" y="48" width="122" height="42" rx="5" fill="#0055a0"/>
  <text x="341" y="65" text-anchor="middle" class="t7">3 · MUESTRA</text>
  <text x="341" y="80" text-anchor="middle" class="s7">y procesos completos</text>
  <rect x="410" y="48" width="122" height="42" rx="5" fill="#2d8659"/>
  <text x="471" y="65" text-anchor="middle" class="t7">4 · AUDITAR</text>
  <text x="471" y="80" text-anchor="middle" class="s7">criterio a criterio</text>
  <rect x="540" y="48" width="120" height="42" rx="5" fill="#2d8659"/>
  <text x="600" y="65" text-anchor="middle" class="t7">5 · INFORMAR</text>
  <text x="600" y="80" text-anchor="middle" class="s7">evidencias y plan</text>
  <text x="20" y="112" class="k7">2 · TRES TIPOS DE COMPROBACIÓN — ninguno basta por sí solo</text>
  <rect x="20" y="120" width="208" height="60" rx="5" fill="#e89822"/>
  <text x="124" y="138" text-anchor="middle" class="t7">AUTOMÁTICA</text>
  <text x="124" y="155" text-anchor="middle" class="s7">Rápida, repetible, en cada cambio</text>
  <text x="124" y="171" text-anchor="middle" class="s7">Solo detecta parte de los criterios</text>
  <rect x="238" y="120" width="208" height="60" rx="5" fill="#0055a0"/>
  <text x="342" y="138" text-anchor="middle" class="t7">MANUAL EXPERTA</text>
  <text x="342" y="155" text-anchor="middle" class="s7">Teclado, contraste, encabezados,</text>
  <text x="342" y="171" text-anchor="middle" class="s7">lector de pantalla</text>
  <rect x="456" y="120" width="204" height="60" rx="5" fill="#2d8659"/>
  <text x="558" y="138" text-anchor="middle" class="t7">CON USUARIOS REALES</text>
  <text x="558" y="155" text-anchor="middle" class="s7">No exigida por la norma,</text>
  <text x="558" y="171" text-anchor="middle" class="s7">insustituible en la práctica</text>
  <rect x="90" y="188" width="500" height="24" rx="5" fill="#fbe9e9" stroke="#d13c3c"/>
  <text x="340" y="204" text-anchor="middle" style="font:700 10px system-ui;fill:#d13c3c">Una web puede superar el 100 % de las pruebas automáticas y ser inaccesible</text>
  <text x="20" y="234" class="k7">3 · DECLARACIÓN DE ACCESIBILIDAD (obligatoria, modelo europeo, enlazada desde todas las páginas)</text>
  <rect x="20" y="242" width="155" height="52" rx="5" fill="#eef3f8" stroke="#0055a0"/>
  <text x="97" y="260" text-anchor="middle" class="d7">GRADO DE CUMPLIMIENTO</text>
  <text x="97" y="275" text-anchor="middle" class="d7">Plenamente / parcialmente</text>
  <text x="97" y="288" text-anchor="middle" class="d7">/ no conforme</text>
  <rect x="185" y="242" width="155" height="52" rx="5" fill="#eef3f8" stroke="#0055a0"/>
  <text x="262" y="260" text-anchor="middle" class="d7">CONTENIDO NO ACCESIBLE</text>
  <text x="262" y="275" text-anchor="middle" class="d7">Por falta de conformidad,</text>
  <text x="262" y="288" text-anchor="middle" class="d7">carga o fuera de ámbito</text>
  <rect x="350" y="242" width="155" height="52" rx="5" fill="#eef3f8" stroke="#0055a0"/>
  <text x="427" y="260" text-anchor="middle" class="d7">FECHA Y MÉTODO</text>
  <text x="427" y="275" text-anchor="middle" class="d7">Autoevaluación o</text>
  <text x="427" y="288" text-anchor="middle" class="d7">evaluación por tercero</text>
  <rect x="515" y="242" width="145" height="52" rx="5" fill="#fdf1de" stroke="#e89822"/>
  <text x="587" y="260" text-anchor="middle" class="d7">COMUNICACIÓN Y</text>
  <text x="587" y="275" text-anchor="middle" class="d7">RECLAMACIÓN</text>
  <text x="587" y="288" text-anchor="middle" class="d7">→ unidad responsable</text>
  <rect x="130" y="302" width="420" height="26" rx="5" fill="none" stroke="#0055a0" stroke-width="2"/>
  <text x="340" y="319" text-anchor="middle" style="font:700 10px system-ui;fill:#0055a0">Revisión al menos anual y ante todo cambio sustancial del sitio</text>
  <text x="670" y="344" text-anchor="end" style="font:11px system-ui;fill:#666">[Fuente: WCAG-EM; RD1112-2018; DEC2018-1523; OBSERVATORIO]</text>
</svg>
```

---

## D8 · Amenazas y controles en el puesto de usuario final

**Sección**: §2.1 — Seguridad en el puesto de usuario final
**Propósito**: Cruzar las cuatro familias de amenazas del puesto con los controles de las cuatro naturalezas de ISO/IEC 27002 y con las dimensiones de seguridad del ENS.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 680 370" role="img" aria-label="Amenazas del puesto de usuario final agrupadas en cuatro familias (ataques a la persona, código malicioso, fallos y descuidos, y amenazas físicas) frente a los cuatro tipos de control de ISO 27002 (organizativos, de personas, físicos y tecnológicos), con las cinco dimensiones de seguridad del Esquema Nacional de Seguridad">
  <style>.t8{font:700 10px system-ui,sans-serif;fill:#fff}.s8{font:9px system-ui,sans-serif;fill:#fff}.h8{font:700 13px system-ui,sans-serif;fill:#0055a0}.k8{font:700 9.5px system-ui,sans-serif;fill:#0055a0}.d8{font:9px system-ui,sans-serif;fill:#333}</style>
  <text x="340" y="20" text-anchor="middle" class="h8">El puesto de usuario: amenazas y controles</text>
  <text x="20" y="40" class="k8">AMENAZAS — cuatro familias</text>
  <rect x="20" y="48" width="155" height="66" rx="5" fill="#d13c3c"/>
  <text x="97" y="66" text-anchor="middle" class="t8">A LA PERSONA</text>
  <text x="97" y="83" text-anchor="middle" class="s8">Phishing, vishing,</text>
  <text x="97" y="97" text-anchor="middle" class="s8">smishing, fraude del CEO</text>
  <text x="97" y="110" text-anchor="middle" class="s8">→ no es un fallo técnico</text>
  <rect x="185" y="48" width="155" height="66" rx="5" fill="#d13c3c"/>
  <text x="262" y="66" text-anchor="middle" class="t8">CÓDIGO MALICIOSO</text>
  <text x="262" y="83" text-anchor="middle" class="s8">Ransomware, troyanos,</text>
  <text x="262" y="97" text-anchor="middle" class="s8">infostealers, gusanos</text>
  <text x="262" y="110" text-anchor="middle" class="s8">→ vía correo y web</text>
  <rect x="350" y="48" width="155" height="66" rx="5" fill="#e89822"/>
  <text x="427" y="66" text-anchor="middle" class="t8">FALLOS Y DESCUIDOS</text>
  <text x="427" y="83" text-anchor="middle" class="s8">Pérdida del equipo, envío</text>
  <text x="427" y="97" text-anchor="middle" class="s8">erróneo, nube personal</text>
  <text x="427" y="110" text-anchor="middle" class="s8">→ la causa más frecuente</text>
  <rect x="515" y="48" width="145" height="66" rx="5" fill="#e89822"/>
  <text x="587" y="66" text-anchor="middle" class="t8">FÍSICAS Y DEL ENTORNO</text>
  <text x="587" y="83" text-anchor="middle" class="s8">Espionaje visual,</text>
  <text x="587" y="97" text-anchor="middle" class="s8">impresora compartida,</text>
  <text x="587" y="110" text-anchor="middle" class="s8">retirada sin borrado</text>
  <text x="20" y="136" class="k8">CONTROLES — las cuatro naturalezas de ISO/IEC 27002:2022</text>
  <rect x="20" y="144" width="155" height="72" rx="5" fill="#0055a0"/>
  <text x="97" y="162" text-anchor="middle" class="t8">ORGANIZATIVOS</text>
  <text x="97" y="179" text-anchor="middle" class="s8">Política y normativa de uso</text>
  <text x="97" y="193" text-anchor="middle" class="s8">Clasificación de la información</text>
  <text x="97" y="207" text-anchor="middle" class="s8">Gestión de incidentes</text>
  <rect x="185" y="144" width="155" height="72" rx="5" fill="#0055a0"/>
  <text x="262" y="162" text-anchor="middle" class="t8">DE PERSONAS</text>
  <text x="262" y="179" text-anchor="middle" class="s8">Formación y concienciación</text>
  <text x="262" y="193" text-anchor="middle" class="s8">Deber de secreto</text>
  <text x="262" y="207" text-anchor="middle" class="s8">Notificación de incidentes</text>
  <rect x="350" y="144" width="155" height="72" rx="5" fill="#2d8659"/>
  <text x="427" y="162" text-anchor="middle" class="t8">FÍSICOS</text>
  <text x="427" y="179" text-anchor="middle" class="s8">Puesto despejado y bloqueo</text>
  <text x="427" y="193" text-anchor="middle" class="s8">Filtros de privacidad</text>
  <text x="427" y="207" text-anchor="middle" class="s8">Impresión segura y destrucción</text>
  <rect x="515" y="144" width="145" height="72" rx="5" fill="#2d8659"/>
  <text x="587" y="162" text-anchor="middle" class="t8">TECNOLÓGICOS</text>
  <text x="587" y="179" text-anchor="middle" class="s8">Mínimo privilegio y MFA</text>
  <text x="587" y="193" text-anchor="middle" class="s8">Cifrado · EDR · DLP</text>
  <text x="587" y="207" text-anchor="middle" class="s8">Copias y parcheo</text>
  <line x1="20" y1="230" x2="660" y2="230" stroke="#ccc" stroke-width="1"/>
  <text x="340" y="250" text-anchor="middle" class="k8">Lo que hay que proteger: las cinco dimensiones del ENS (D-I-C-A-T)</text>
  <rect x="20" y="260" width="122" height="44" rx="5" fill="#0055a0"/>
  <text x="81" y="278" text-anchor="middle" class="t8">DISPONIBILIDAD</text>
  <text x="81" y="294" text-anchor="middle" class="s8">¿está cuando hace falta?</text>
  <rect x="150" y="260" width="122" height="44" rx="5" fill="#0055a0"/>
  <text x="211" y="278" text-anchor="middle" class="t8">INTEGRIDAD</text>
  <text x="211" y="294" text-anchor="middle" class="s8">¿es el dato que era?</text>
  <rect x="280" y="260" width="122" height="44" rx="5" fill="#0055a0"/>
  <text x="341" y="278" text-anchor="middle" class="t8">CONFIDENCIALIDAD</text>
  <text x="341" y="294" text-anchor="middle" class="s8">¿accede solo quien debe?</text>
  <rect x="410" y="260" width="122" height="44" rx="5" fill="#e89822"/>
  <text x="471" y="278" text-anchor="middle" class="t8">AUTENTICIDAD</text>
  <text x="471" y="294" text-anchor="middle" class="s8">¿es quien dice ser?</text>
  <rect x="540" y="260" width="120" height="44" rx="5" fill="#e89822"/>
  <text x="600" y="278" text-anchor="middle" class="t8">TRAZABILIDAD</text>
  <text x="600" y="294" text-anchor="middle" class="s8">¿quién hizo qué?</text>
  <rect x="100" y="314" width="480" height="26" rx="5" fill="none" stroke="#0055a0" stroke-width="2"/>
  <text x="340" y="331" text-anchor="middle" style="font:700 10px system-ui;fill:#0055a0">Las tres primeras son la triada CID; autenticidad y trazabilidad las añade el ENS</text>
  <text x="670" y="362" text-anchor="end" style="font:11px system-ui;fill:#666">[Fuente: ISO27002; ENS; ATTACK]</text>
</svg>
```

---

## D9 · Control de acceso: cuatro pasos y tres factores

**Sección**: §2.2.1 — Autenticación de usuarios y principio de mínimo privilegio
**Propósito**: Separar identificación, autenticación, autorización y trazabilidad, y ordenar los factores y modelos de autorización.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 680 350" role="img" aria-label="Los cuatro pasos del control de acceso: identificación, autenticación, autorización y trazabilidad; los tres tipos de factor de autenticación (algo que se sabe, algo que se tiene y algo que se es) con su debilidad característica; y los cuatro modelos de autorización DAC, MAC, RBAC y ABAC, más el principio de mínimo privilegio">
  <style>.t9{font:700 10.5px system-ui,sans-serif;fill:#fff}.s9{font:9px system-ui,sans-serif;fill:#fff}.h9{font:700 13px system-ui,sans-serif;fill:#0055a0}.k9{font:700 9.5px system-ui,sans-serif;fill:#0055a0}.d9{font:9px system-ui,sans-serif;fill:#333}</style>
  <text x="340" y="20" text-anchor="middle" class="h9">Control de acceso: cuatro pasos que no deben confundirse</text>
  <rect x="20" y="34" width="145" height="48" rx="5" fill="#888"/>
  <text x="92" y="53" text-anchor="middle" class="t9">1 · IDENTIFICACIÓN</text>
  <text x="92" y="70" text-anchor="middle" class="s9">«Digo quién soy»</text>
  <rect x="185" y="34" width="145" height="48" rx="5" fill="#0055a0"/>
  <text x="257" y="53" text-anchor="middle" class="t9">2 · AUTENTICACIÓN</text>
  <text x="257" y="70" text-anchor="middle" class="s9">«Lo demuestro»</text>
  <rect x="350" y="34" width="145" height="48" rx="5" fill="#2d8659"/>
  <text x="422" y="53" text-anchor="middle" class="t9">3 · AUTORIZACIÓN</text>
  <text x="422" y="70" text-anchor="middle" class="s9">«Qué puedo hacer»</text>
  <rect x="515" y="34" width="145" height="48" rx="5" fill="#e89822"/>
  <text x="587" y="53" text-anchor="middle" class="t9">4 · TRAZABILIDAD</text>
  <text x="587" y="70" text-anchor="middle" class="s9">«Queda registrado»</text>
  <defs><marker id="a9" markerWidth="7" markerHeight="7" refX="6" refY="3" orient="auto"><path d="M0,0 L6,3 L0,6 z" fill="#0055a0"/></marker></defs>
  <path d="M165 58 L185 58" stroke="#0055a0" stroke-width="2" marker-end="url(#a9)"/>
  <path d="M330 58 L350 58" stroke="#0055a0" stroke-width="2" marker-end="url(#a9)"/>
  <path d="M495 58 L515 58" stroke="#0055a0" stroke-width="2" marker-end="url(#a9)"/>
  <text x="20" y="102" class="k9">LOS TRES TIPOS DE FACTOR — la MFA exige dos de NATURALEZA DISTINTA</text>
  <rect x="20" y="110" width="208" height="62" rx="5" fill="#0055a0"/>
  <text x="124" y="128" text-anchor="middle" class="t9">ALGO QUE SE SABE</text>
  <text x="124" y="145" text-anchor="middle" class="s9">Contraseña, PIN, frase de paso</text>
  <text x="124" y="163" text-anchor="middle" class="s9">Debilidad: phishing y reutilización</text>
  <rect x="238" y="110" width="208" height="62" rx="5" fill="#2d8659"/>
  <text x="342" y="128" text-anchor="middle" class="t9">ALGO QUE SE TIENE</text>
  <text x="342" y="145" text-anchor="middle" class="s9">Tarjeta, DNIe, FIDO2, código TOTP</text>
  <text x="342" y="163" text-anchor="middle" class="s9">Debilidad: pérdida o sustracción</text>
  <rect x="456" y="110" width="204" height="62" rx="5" fill="#e89822"/>
  <text x="558" y="128" text-anchor="middle" class="t9">ALGO QUE SE ES</text>
  <text x="558" y="145" text-anchor="middle" class="s9">Huella, rostro, iris, voz</text>
  <text x="558" y="163" text-anchor="middle" class="s9">Debilidad: NO es revocable</text>
  <rect x="70" y="180" width="540" height="24" rx="5" fill="#fbe9e9" stroke="#d13c3c"/>
  <text x="340" y="196" text-anchor="middle" style="font:700 10px system-ui;fill:#d13c3c">Contraseña + pregunta de seguridad NO es MFA: los dos son conocimiento</text>
  <text x="20" y="224" class="k9">MODELOS DE AUTORIZACIÓN</text>
  <rect x="20" y="232" width="155" height="46" rx="5" fill="#888"/>
  <text x="97" y="250" text-anchor="middle" class="t9">DAC · discrecional</text>
  <text x="97" y="266" text-anchor="middle" class="s9">decide el propietario</text>
  <rect x="185" y="232" width="155" height="46" rx="5" fill="#888"/>
  <text x="262" y="250" text-anchor="middle" class="t9">MAC · obligatorio</text>
  <text x="262" y="266" text-anchor="middle" class="s9">lo impone el sistema</text>
  <rect x="350" y="232" width="155" height="46" rx="5" fill="#2d8659"/>
  <text x="427" y="250" text-anchor="middle" class="t9">RBAC · por roles</text>
  <text x="427" y="266" text-anchor="middle" class="s9">estándar en la Administración</text>
  <rect x="515" y="232" width="145" height="46" rx="5" fill="#0055a0"/>
  <text x="587" y="250" text-anchor="middle" class="t9">ABAC · por atributos</text>
  <text x="587" y="266" text-anchor="middle" class="s9">base del zero trust</text>
  <rect x="20" y="288" width="640" height="44" rx="5" fill="#eef3f8" stroke="#0055a0" stroke-width="2"/>
  <text x="340" y="306" text-anchor="middle" style="font:700 10.5px system-ui;fill:#0055a0">MÍNIMO PRIVILEGIO + NECESIDAD DE CONOCER</text>
  <text x="340" y="324" text-anchor="middle" class="d9">El usuario NO es administrador local · cuenta administrativa separada · permisos por rol, revisados y retirados al cese</text>
  <text x="670" y="346" text-anchor="end" style="font:11px system-ui;fill:#666">[Fuente: NIST-800-63B; WEBAUTHN; SALTZER75; ENS]</text>
</svg>
```

---

## D10 · Cifrado en reposo y en tránsito en el puesto

**Sección**: §2.2.2 — Cifrado de almacenamiento local y comunicaciones
**Propósito**: Situar las tres granularidades del cifrado en reposo, los protocolos del cifrado en tránsito y, sobre todo, el límite real del cifrado de disco completo.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 680 330" role="img" aria-label="Cifrado en el puesto de usuario: en reposo con cifrado de disco completo, de volumen o de fichero, apoyado en el chip TPM; en tránsito con TLS 1.3, VPN, SSH, SFTP y LDAPS; y advertencia de que el cifrado de disco completo protege el equipo apagado pero no la sesión iniciada">
  <style>.t10{font:700 10.5px system-ui,sans-serif;fill:#fff}.s10{font:9px system-ui,sans-serif;fill:#fff}.h10{font:700 13px system-ui,sans-serif;fill:#0055a0}.k10{font:700 9.5px system-ui,sans-serif;fill:#0055a0}.d10{font:9px system-ui,sans-serif;fill:#333}</style>
  <text x="340" y="20" text-anchor="middle" class="h10">El cifrado: la última línea de defensa de la confidencialidad</text>
  <rect x="20" y="34" width="315" height="28" rx="5" fill="#0055a0"/>
  <text x="177" y="53" text-anchor="middle" class="t10">EN REPOSO — el dato guardado</text>
  <rect x="345" y="34" width="315" height="28" rx="5" fill="#2d8659"/>
  <text x="502" y="53" text-anchor="middle" class="t10">EN TRÁNSITO — el dato que viaja</text>
  <rect x="20" y="70" width="315" height="40" rx="4" fill="#e6eff7"/>
  <text x="30" y="87" class="d10"><tspan style="font-weight:700">Disco completo (FDE)</tspan> — todo el volumen, incluidos</text>
  <text x="30" y="103" class="d10">temporales, paginación e hibernación. Clave en TPM.</text>
  <rect x="20" y="114" width="315" height="34" rx="4" fill="#e6eff7"/>
  <text x="30" y="131" class="d10"><tspan style="font-weight:700">Volumen o contenedor</tspan> — un espacio delimitado</text>
  <text x="30" y="145" class="d10">dentro del disco para lo especialmente sensible.</text>
  <rect x="20" y="152" width="315" height="34" rx="4" fill="#e6eff7"/>
  <text x="30" y="169" class="d10"><tspan style="font-weight:700">Fichero</tspan> — protege el documento también CUANDO</text>
  <text x="30" y="183" class="d10">SALE del equipo (envío, USB, copia de seguridad).</text>
  <rect x="345" y="70" width="315" height="40" rx="4" fill="#e6f2ec"/>
  <text x="355" y="87" class="d10"><tspan style="font-weight:700">TLS 1.3</tspan> — web, correo y servicios: confidencialidad,</text>
  <text x="355" y="103" class="d10">integridad y autenticación del servidor. Con HSTS.</text>
  <rect x="345" y="114" width="315" height="34" rx="4" fill="#e6f2ec"/>
  <text x="355" y="131" class="d10"><tspan style="font-weight:700">VPN / zero trust</tspan> — teletrabajo, con MFA y</text>
  <text x="355" y="145" class="d10">comprobación del estado del dispositivo.</text>
  <rect x="345" y="152" width="315" height="34" rx="4" fill="#e6f2ec"/>
  <text x="355" y="169" class="d10"><tspan style="font-weight:700">Sustituir lo que va en claro</tspan> — SSH por Telnet,</text>
  <text x="355" y="183" class="d10">SFTP/FTPS por FTP, LDAPS por LDAP.</text>
  <line x1="20" y1="198" x2="660" y2="198" stroke="#ccc" stroke-width="1"/>
  <text x="340" y="216" text-anchor="middle" class="k10">El límite del cifrado de disco: qué protege y qué no</text>
  <rect x="20" y="226" width="310" height="56" rx="5" fill="#2d8659"/>
  <text x="175" y="246" text-anchor="middle" class="t10">SÍ PROTEGE</text>
  <text x="175" y="263" text-anchor="middle" class="s10">Equipo apagado · disco extraído</text>
  <text x="175" y="277" text-anchor="middle" class="s10">Portátil robado o perdido</text>
  <rect x="350" y="226" width="310" height="56" rx="5" fill="#d13c3c"/>
  <text x="505" y="246" text-anchor="middle" class="t10">NO PROTEGE</text>
  <text x="505" y="263" text-anchor="middle" class="s10">Sesión iniciada · código malicioso en ejecución</text>
  <text x="505" y="277" text-anchor="middle" class="s10">Usuario legítimo que exfiltra el dato</text>
  <rect x="60" y="290" width="560" height="26" rx="5" fill="none" stroke="#0055a0" stroke-width="2"/>
  <text x="340" y="307" text-anchor="middle" style="font:700 10px system-ui;fill:#0055a0">Sin custodia y recuperación de claves, la confidencialidad se convierte en pérdida de disponibilidad</text>
  <text x="670" y="326" text-anchor="end" style="font:11px system-ui;fill:#666">[Fuente: NIST-800-111; RFC8446; FIPS197; ENS]</text>
</svg>
```

---

## D11 · Copias de seguridad: tipos, regla 3-2-1 y RPO/RTO

**Sección**: §2.3.2 — Copias de seguridad y prevención de pérdida de datos
**Propósito**: Distinguir completa, diferencial e incremental por lo que copian y por lo que exige su restauración, y fijar RPO y RTO sobre la línea temporal del incidente.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 680 370" role="img" aria-label="Tipos de copia de seguridad: completa, diferencial que se mide desde la última completa y se restaura con dos piezas, e incremental que se mide desde la última copia de cualquier tipo y exige toda la cadena; regla 3-2-1 reforzada con copia inmutable; y línea temporal que sitúa el RPO antes del incidente y el RTO después">
  <style>.t11{font:700 10px system-ui,sans-serif;fill:#fff}.s11{font:9px system-ui,sans-serif;fill:#fff}.h11{font:700 13px system-ui,sans-serif;fill:#0055a0}.k11{font:700 9.5px system-ui,sans-serif;fill:#0055a0}.d11{font:9px system-ui,sans-serif;fill:#333}</style>
  <text x="340" y="20" text-anchor="middle" class="h11">Copias de seguridad: qué copia cada tipo y qué exige restaurar</text>
  <rect x="20" y="34" width="208" height="70" rx="5" fill="#0055a0"/>
  <text x="124" y="52" text-anchor="middle" class="t11">COMPLETA (full)</text>
  <text x="124" y="70" text-anchor="middle" class="s11">Copia: todos los datos</text>
  <text x="124" y="85" text-anchor="middle" class="s11">Restaura con: 1 pieza</text>
  <text x="124" y="99" text-anchor="middle" class="s11">Lenta y voluminosa</text>
  <rect x="238" y="34" width="208" height="70" rx="5" fill="#2d8659"/>
  <text x="342" y="52" text-anchor="middle" class="t11">DIFERENCIAL</text>
  <text x="342" y="70" text-anchor="middle" class="s11">Copia: desde la última COMPLETA</text>
  <text x="342" y="85" text-anchor="middle" class="s11">Restaura con: 2 piezas</text>
  <text x="342" y="99" text-anchor="middle" class="s11">Crece cada día</text>
  <rect x="456" y="34" width="204" height="70" rx="5" fill="#e89822"/>
  <text x="558" y="52" text-anchor="middle" class="t11">INCREMENTAL</text>
  <text x="558" y="70" text-anchor="middle" class="s11">Copia: desde la ÚLTIMA cualquiera</text>
  <text x="558" y="85" text-anchor="middle" class="s11">Restaura con: TODA la cadena</text>
  <text x="558" y="99" text-anchor="middle" class="s11">La más rápida de ejecutar</text>
  <rect x="60" y="112" width="560" height="24" rx="5" fill="#fbe9e9" stroke="#d13c3c"/>
  <text x="340" y="128" text-anchor="middle" style="font:700 10px system-ui;fill:#d13c3c">La instantánea (snapshot) NO es copia de seguridad: depende del mismo almacenamiento</text>
  <text x="20" y="156" class="k11">REGLA 3-2-1 REFORZADA</text>
  <rect x="20" y="164" width="120" height="46" rx="5" fill="#0055a0"/>
  <text x="80" y="182" text-anchor="middle" class="t11">3 COPIAS</text>
  <text x="80" y="199" text-anchor="middle" class="s11">de los datos</text>
  <rect x="150" y="164" width="120" height="46" rx="5" fill="#0055a0"/>
  <text x="210" y="182" text-anchor="middle" class="t11">2 SOPORTES</text>
  <text x="210" y="199" text-anchor="middle" class="s11">de tipo distinto</text>
  <rect x="280" y="164" width="120" height="46" rx="5" fill="#0055a0"/>
  <text x="340" y="182" text-anchor="middle" class="t11">1 FUERA</text>
  <text x="340" y="199" text-anchor="middle" class="s11">de las instalaciones</text>
  <rect x="410" y="164" width="120" height="46" rx="5" fill="#2d8659"/>
  <text x="470" y="182" text-anchor="middle" class="t11">1 INMUTABLE</text>
  <text x="470" y="199" text-anchor="middle" class="s11">o desconectada</text>
  <rect x="540" y="164" width="120" height="46" rx="5" fill="#e89822"/>
  <text x="600" y="182" text-anchor="middle" class="t11">0 ERRORES</text>
  <text x="600" y="199" text-anchor="middle" class="s11">tras verificación</text>
  <line x1="20" y1="226" x2="660" y2="226" stroke="#ccc" stroke-width="1"/>
  <text x="340" y="244" text-anchor="middle" class="k11">RPO y RTO sobre la línea temporal del incidente</text>
  <line x1="60" y1="290" x2="620" y2="290" stroke="#333" stroke-width="2"/>
  <line x1="340" y1="262" x2="340" y2="318" stroke="#d13c3c" stroke-width="3"/>
  <text x="340" y="256" text-anchor="middle" style="font:700 10px system-ui;fill:#d13c3c">INCIDENTE</text>
  <circle cx="180" cy="290" r="6" fill="#0055a0"/>
  <text x="180" y="278" text-anchor="middle" class="d11">última copia válida</text>
  <circle cx="500" cy="290" r="6" fill="#2d8659"/>
  <text x="500" y="278" text-anchor="middle" class="d11">servicio restablecido</text>
  <path d="M180 306 L340 306" stroke="#0055a0" stroke-width="2"/>
  <text x="248" y="320" text-anchor="middle" style="font:700 10px system-ui;fill:#0055a0">RPO — datos que puedo perder</text>
  <text x="248" y="333" text-anchor="middle" class="d11">→ define la FRECUENCIA de la copia</text>
  <path d="M340 306 L500 306" stroke="#2d8659" stroke-width="2"/>
  <text x="430" y="320" text-anchor="middle" style="font:700 10px system-ui;fill:#2d8659">RTO — tiempo sin servicio</text>
  <text x="430" y="333" text-anchor="middle" class="d11">→ define la CAPACIDAD de restaurar</text>
  <text x="60" y="352" style="font:700 10px system-ui;fill:#0055a0">Una copia que nunca se ha restaurado no es una copia: es una hipótesis</text>
  <text x="670" y="364" text-anchor="end" style="font:11px system-ui;fill:#666">[Fuente: ENS; ISO27002; NIST-CSF]</text>
</svg>
```

---

## D12 · El ciclo de vida de desarrollo seguro (SSDLC)

**Sección**: §3.1.1 — Modelos e integración de la seguridad en el desarrollo
**Propósito**: Ver la seguridad como actividad de todas las fases y situar los modelos de referencia según lo que aportan.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 680 350" role="img" aria-label="Ciclo de vida de desarrollo seguro: actividades de seguridad en las fases de requisitos, diseño, implementación, verificación, despliegue y operación, con el criterio de desplazamiento a la izquierda porque el coste de corregir crece con la fase; y los modelos de referencia Microsoft SDL, NIST SSDF, OWASP SAMM, BSIMM y OWASP ASVS">
  <style>.t12{font:700 10px system-ui,sans-serif;fill:#fff}.s12{font:8.5px system-ui,sans-serif;fill:#fff}.h12{font:700 13px system-ui,sans-serif;fill:#0055a0}.k12{font:700 9.5px system-ui,sans-serif;fill:#0055a0}.d12{font:9px system-ui,sans-serif;fill:#333}</style>
  <text x="340" y="20" text-anchor="middle" class="h12">SSDLC: la seguridad es actividad de TODAS las fases</text>
  <rect x="20" y="36" width="103" height="72" rx="5" fill="#0055a0"/>
  <text x="71" y="54" text-anchor="middle" class="t12">REQUISITOS</text>
  <text x="71" y="71" text-anchor="middle" class="s12">Requisitos de</text>
  <text x="71" y="84" text-anchor="middle" class="s12">seguridad (ASVS)</text>
  <text x="71" y="97" text-anchor="middle" class="s12">Clasificar datos</text>
  <rect x="129" y="36" width="103" height="72" rx="5" fill="#0055a0"/>
  <text x="180" y="54" text-anchor="middle" class="t12">DISEÑO</text>
  <text x="180" y="71" text-anchor="middle" class="s12">MODELADO DE</text>
  <text x="180" y="84" text-anchor="middle" class="s12">AMENAZAS</text>
  <text x="180" y="97" text-anchor="middle" class="s12">Privacidad desde diseño</text>
  <rect x="238" y="36" width="103" height="72" rx="5" fill="#2d8659"/>
  <text x="289" y="54" text-anchor="middle" class="t12">IMPLEMENTACIÓN</text>
  <text x="289" y="71" text-anchor="middle" class="s12">Codificación segura</text>
  <text x="289" y="84" text-anchor="middle" class="s12">SAST + revisión</text>
  <text x="289" y="97" text-anchor="middle" class="s12">entre pares</text>
  <rect x="347" y="36" width="103" height="72" rx="5" fill="#2d8659"/>
  <text x="398" y="54" text-anchor="middle" class="t12">VERIFICACIÓN</text>
  <text x="398" y="71" text-anchor="middle" class="s12">DAST · SCA</text>
  <text x="398" y="84" text-anchor="middle" class="s12">Fuzzing</text>
  <text x="398" y="97" text-anchor="middle" class="s12">Pentest</text>
  <rect x="456" y="36" width="103" height="72" rx="5" fill="#e89822"/>
  <text x="507" y="54" text-anchor="middle" class="t12">DESPLIEGUE</text>
  <text x="507" y="71" text-anchor="middle" class="s12">Bastionado</text>
  <text x="507" y="84" text-anchor="middle" class="s12">Gestión de secretos</text>
  <text x="507" y="97" text-anchor="middle" class="s12">Firma de artefactos</text>
  <rect x="565" y="36" width="95" height="72" rx="5" fill="#e89822"/>
  <text x="612" y="54" text-anchor="middle" class="t12">OPERACIÓN</text>
  <text x="612" y="71" text-anchor="middle" class="s12">Parcheo</text>
  <text x="612" y="84" text-anchor="middle" class="s12">Monitorización</text>
  <text x="612" y="97" text-anchor="middle" class="s12">Respuesta</text>
  <defs><marker id="a12" markerWidth="8" markerHeight="8" refX="7" refY="3.5" orient="auto"><path d="M0,0 L7,3.5 L0,7 z" fill="#d13c3c"/></marker></defs>
  <path d="M640 124 L40 124" stroke="#d13c3c" stroke-width="2" marker-end="url(#a12)"/>
  <text x="340" y="140" text-anchor="middle" style="font:700 10px system-ui;fill:#d13c3c">SHIFT LEFT — cuanto más tarde se detecta el defecto, más cuesta corregirlo</text>
  <line x1="20" y1="152" x2="660" y2="152" stroke="#ccc" stroke-width="1"/>
  <text x="20" y="172" class="k12">MODELOS DE REFERENCIA — qué aporta cada uno</text>
  <rect x="20" y="180" width="155" height="56" rx="5" fill="#0055a0"/>
  <text x="97" y="198" text-anchor="middle" class="t12">Microsoft SDL</text>
  <text x="97" y="215" text-anchor="middle" class="s12">El pionero (2004)</text>
  <text x="97" y="229" text-anchor="middle" class="s12">Origen de STRIDE</text>
  <rect x="185" y="180" width="155" height="56" rx="5" fill="#0055a0"/>
  <text x="262" y="198" text-anchor="middle" class="t12">NIST SSDF (800-218)</text>
  <text x="262" y="215" text-anchor="middle" class="s12">Marco de prácticas:</text>
  <text x="262" y="229" text-anchor="middle" class="s12">PO · PS · PW · RV</text>
  <rect x="350" y="180" width="155" height="56" rx="5" fill="#2d8659"/>
  <text x="427" y="198" text-anchor="middle" class="t12">OWASP SAMM</text>
  <text x="427" y="215" text-anchor="middle" class="s12">PRESCRIPTIVO · madurez</text>
  <text x="427" y="229" text-anchor="middle" class="s12">5 funciones · 3 niveles</text>
  <rect x="515" y="180" width="145" height="56" rx="5" fill="#888"/>
  <text x="587" y="198" text-anchor="middle" class="t12">BSIMM</text>
  <text x="587" y="215" text-anchor="middle" class="s12">DESCRIPTIVO</text>
  <text x="587" y="229" text-anchor="middle" class="s12">qué hacen otros</text>
  <rect x="130" y="246" width="420" height="44" rx="5" fill="#e89822"/>
  <text x="340" y="264" text-anchor="middle" class="t12">OWASP ASVS — catálogo de REQUISITOS VERIFICABLES del producto</text>
  <text x="340" y="281" text-anchor="middle" class="s12">3 niveles de verificación · la herramienta para redactar un pliego y auditar la entrega</text>
  <rect x="20" y="300" width="640" height="26" rx="5" fill="none" stroke="#0055a0" stroke-width="2"/>
  <text x="340" y="317" text-anchor="middle" style="font:700 10px system-ui;fill:#0055a0">SDL, SSDF, SAMM y BSIMM hablan del PROCESO · ASVS habla del PRODUCTO</text>
  <text x="670" y="344" text-anchor="end" style="font:11px system-ui;fill:#666">[Fuente: MS-SDL; NIST-SSDF; OWASP-SAMM; BSIMM; OWASP-ASVS]</text>
</svg>
```

---

## D13 · STRIDE: seis amenazas y la propiedad que niega cada una

**Sección**: §3.1.2 — Análisis de requisitos y modelado de amenazas
**Propósito**: Memorizar el emparejamiento amenaza-propiedad-contramedida y las cuatro preguntas del modelado.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 680 350" role="img" aria-label="Modelo STRIDE: suplantación niega la autenticidad, manipulación niega la integridad, repudio niega el no repudio, revelación de información niega la confidencialidad, denegación de servicio niega la disponibilidad y elevación de privilegios niega la autorización, con la contramedida típica de cada una; y las cuatro preguntas del modelado de amenazas">
  <style>.t13{font:700 10px system-ui,sans-serif;fill:#fff}.s13{font:9px system-ui,sans-serif;fill:#fff}.h13{font:700 13px system-ui,sans-serif;fill:#0055a0}.k13{font:700 9.5px system-ui,sans-serif;fill:#0055a0}.d13{font:9px system-ui,sans-serif;fill:#333}</style>
  <text x="340" y="20" text-anchor="middle" class="h13">STRIDE — cada amenaza niega una propiedad de seguridad</text>
  <text x="30" y="42" class="k13">AMENAZA</text>
  <text x="270" y="42" class="k13">PROPIEDAD QUE NIEGA</text>
  <text x="450" y="42" class="k13">CONTRAMEDIDA TÍPICA</text>
  <rect x="20" y="48" width="240" height="30" rx="4" fill="#0055a0"/>
  <text x="30" y="68" class="t13">S · Spoofing — suplantación</text>
  <rect x="266" y="48" width="160" height="30" rx="4" fill="#e6eff7"/>
  <text x="346" y="68" text-anchor="middle" class="d13">AUTENTICIDAD</text>
  <rect x="432" y="48" width="228" height="30" rx="4" fill="#eef3f8"/>
  <text x="442" y="68" class="d13">MFA, certificados, firma electrónica</text>
  <rect x="20" y="82" width="240" height="30" rx="4" fill="#0055a0"/>
  <text x="30" y="102" class="t13">T · Tampering — manipulación</text>
  <rect x="266" y="82" width="160" height="30" rx="4" fill="#e6eff7"/>
  <text x="346" y="102" text-anchor="middle" class="d13">INTEGRIDAD</text>
  <rect x="432" y="82" width="228" height="30" rx="4" fill="#eef3f8"/>
  <text x="442" y="102" class="d13">Resumen y firma, TLS, validación</text>
  <rect x="20" y="116" width="240" height="30" rx="4" fill="#2d8659"/>
  <text x="30" y="136" class="t13">R · Repudiation — repudio</text>
  <rect x="266" y="116" width="160" height="30" rx="4" fill="#e6f2ec"/>
  <text x="346" y="136" text-anchor="middle" class="d13">NO REPUDIO</text>
  <rect x="432" y="116" width="228" height="30" rx="4" fill="#eef3f8"/>
  <text x="442" y="136" class="d13">Registro íntegro y sellado de tiempo</text>
  <rect x="20" y="150" width="240" height="30" rx="4" fill="#2d8659"/>
  <text x="30" y="170" class="t13">I · Information disclosure</text>
  <rect x="266" y="150" width="160" height="30" rx="4" fill="#e6f2ec"/>
  <text x="346" y="170" text-anchor="middle" class="d13">CONFIDENCIALIDAD</text>
  <rect x="432" y="150" width="228" height="30" rx="4" fill="#eef3f8"/>
  <text x="442" y="170" class="d13">Cifrado, control de acceso, error genérico</text>
  <rect x="20" y="184" width="240" height="30" rx="4" fill="#e89822"/>
  <text x="30" y="204" class="t13">D · Denial of service</text>
  <rect x="266" y="184" width="160" height="30" rx="4" fill="#fdf1de"/>
  <text x="346" y="204" text-anchor="middle" class="d13">DISPONIBILIDAD</text>
  <rect x="432" y="184" width="228" height="30" rx="4" fill="#eef3f8"/>
  <text x="442" y="204" class="d13">Limitación de peticiones, cuotas</text>
  <rect x="20" y="218" width="240" height="30" rx="4" fill="#d13c3c"/>
  <text x="30" y="238" class="t13">E · Elevation of privilege</text>
  <rect x="266" y="218" width="160" height="30" rx="4" fill="#fbe9e9"/>
  <text x="346" y="238" text-anchor="middle" class="d13">AUTORIZACIÓN</text>
  <rect x="432" y="218" width="228" height="30" rx="4" fill="#eef3f8"/>
  <text x="442" y="238" class="d13">Mínimo privilegio, comprobar en servidor</text>
  <line x1="20" y1="260" x2="660" y2="260" stroke="#ccc" stroke-width="1"/>
  <text x="340" y="278" text-anchor="middle" class="k13">Las cuatro preguntas del modelado de amenazas</text>
  <rect x="20" y="288" width="155" height="34" rx="5" fill="#0055a0"/>
  <text x="97" y="309" text-anchor="middle" class="t13">1 · ¿En qué trabajamos?</text>
  <rect x="185" y="288" width="155" height="34" rx="5" fill="#0055a0"/>
  <text x="262" y="309" text-anchor="middle" class="t13">2 · ¿Qué puede salir mal?</text>
  <rect x="350" y="288" width="155" height="34" rx="5" fill="#2d8659"/>
  <text x="427" y="309" text-anchor="middle" class="t13">3 · ¿Qué hacemos?</text>
  <rect x="515" y="288" width="145" height="34" rx="5" fill="#2d8659"/>
  <text x="587" y="309" text-anchor="middle" class="t13">4 · ¿Ha bastado?</text>
  <text x="340" y="336" text-anchor="middle" class="d13">El paso 1 exige dibujar los LÍMITES DE CONFIANZA: es donde se concentran las amenazas</text>
  <text x="670" y="348" text-anchor="end" style="font:11px system-ui;fill:#666">[Fuente: SHOSTACK; MS-SDL]</text>
</svg>
```

---

## D14 · OWASP Top 10:2021 y técnicas de verificación

**Sección**: §3.3 — Vulnerabilidades y verificación de la seguridad
**Propósito**: Fijar las diez categorías de riesgo (señalando las tres nuevas de 2021) y contrastar las técnicas de verificación por lo que ve y por lo que no ve cada una.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 680 414" role="img" aria-label="OWASP Top 10 de 2021 con sus diez categorías, destacando que A01 es la pérdida de control de acceso y que A04 diseño inseguro, A08 fallos de integridad y A10 SSRF son nuevas en esa edición; y comparativa de las técnicas de verificación SAST, DAST, IAST, SCA, revisión manual y prueba de penetración indicando qué ve y qué no ve cada una">
  <style>.t14{font:700 9.5px system-ui,sans-serif;fill:#fff}.s14{font:8.5px system-ui,sans-serif;fill:#fff}.h14{font:700 13px system-ui,sans-serif;fill:#0055a0}.k14{font:700 9.5px system-ui,sans-serif;fill:#0055a0}.d14{font:9px system-ui,sans-serif;fill:#333}</style>
  <text x="340" y="20" text-anchor="middle" class="h14">OWASP Top 10:2021 — categorías de riesgo en aplicaciones web</text>
  <rect x="20" y="32" width="212" height="36" rx="4" fill="#d13c3c"/>
  <text x="30" y="47" class="t14">A01 · Pérdida de control de acceso</text>
  <text x="30" y="61" class="s14">IDOR, elevación de privilegios — la nº 1</text>
  <rect x="238" y="32" width="212" height="36" rx="4" fill="#0055a0"/>
  <text x="248" y="47" class="t14">A02 · Fallos criptográficos</text>
  <text x="248" y="61" class="s14">Sin cifrar, algoritmos obsoletos, claves</text>
  <rect x="456" y="32" width="204" height="36" rx="4" fill="#0055a0"/>
  <text x="466" y="47" class="t14">A03 · Inyección</text>
  <text x="466" y="61" class="s14">SQL, LDAP, mandatos y XSS</text>
  <rect x="20" y="72" width="212" height="36" rx="4" fill="#e89822"/>
  <text x="30" y="87" class="t14">A04 · Diseño inseguro (NUEVA)</text>
  <text x="30" y="101" class="s14">No se parchea: se rediseña</text>
  <rect x="238" y="72" width="212" height="36" rx="4" fill="#0055a0"/>
  <text x="248" y="87" class="t14">A05 · Configuración defectuosa</text>
  <text x="248" y="101" class="s14">Valores por defecto, errores expuestos</text>
  <rect x="456" y="72" width="204" height="36" rx="4" fill="#0055a0"/>
  <text x="466" y="87" class="t14">A06 · Componentes vulnerables</text>
  <text x="466" y="101" class="s14">Bibliotecas sin actualizar</text>
  <rect x="20" y="112" width="212" height="36" rx="4" fill="#0055a0"/>
  <text x="30" y="127" class="t14">A07 · Identificación y autenticación</text>
  <text x="30" y="141" class="s14">Sin MFA, fuerza bruta, sesión débil</text>
  <rect x="238" y="112" width="212" height="36" rx="4" fill="#e89822"/>
  <text x="248" y="127" class="t14">A08 · Integridad (NUEVA)</text>
  <text x="248" y="141" class="s14">Deserialización, cadena de suministro</text>
  <rect x="456" y="112" width="204" height="36" rx="4" fill="#0055a0"/>
  <text x="466" y="127" class="t14">A09 · Registro y monitorización</text>
  <text x="466" y="141" class="s14">El ataque pasa inadvertido</text>
  <rect x="238" y="152" width="212" height="34" rx="4" fill="#e89822"/>
  <text x="248" y="167" class="t14">A10 · SSRF (NUEVA)</text>
  <text x="248" y="180" class="s14">El servidor pide una URL del atacante</text>
  <rect x="20" y="152" width="212" height="34" rx="4" fill="#eef3f8"/>
  <text x="126" y="167" text-anchor="middle" class="d14">CWE = debilidades (tipos)</text>
  <text x="126" y="180" text-anchor="middle" class="d14">CVE = vulnerabilidades concretas</text>
  <rect x="456" y="152" width="204" height="34" rx="4" fill="#eef3f8"/>
  <text x="558" y="167" text-anchor="middle" class="d14">CVSS = severidad 0,0-10,0</text>
  <text x="558" y="180" text-anchor="middle" class="d14">crítica a partir de 9,0</text>
  <line x1="20" y1="198" x2="660" y2="198" stroke="#ccc" stroke-width="1"/>
  <text x="340" y="216" text-anchor="middle" class="k14">Técnicas de verificación: qué ve y qué no ve cada una</text>
  <text x="30" y="234" class="k14">TÉCNICA</text>
  <text x="200" y="234" class="k14">QUÉ VE BIEN</text>
  <text x="440" y="234" class="k14">SU PUNTO CIEGO</text>
  <rect x="20" y="240" width="160" height="28" rx="4" fill="#0055a0"/>
  <text x="30" y="258" class="t14">SAST — código sin ejecutar</text>
  <rect x="186" y="240" width="240" height="28" rx="4" fill="#e6eff7"/>
  <text x="196" y="258" class="d14">Inyección, secretos, criptografía</text>
  <rect x="432" y="240" width="228" height="28" rx="4" fill="#fbe9e9"/>
  <text x="442" y="258" class="d14">Entorno, lógica · falsos positivos</text>
  <rect x="20" y="272" width="160" height="28" rx="4" fill="#2d8659"/>
  <text x="30" y="290" class="t14">DAST — app en ejecución</text>
  <rect x="186" y="272" width="240" height="28" rx="4" fill="#e6f2ec"/>
  <text x="196" y="290" class="d14">Configuración, sesión, cabeceras</text>
  <rect x="432" y="272" width="228" height="28" rx="4" fill="#fbe9e9"/>
  <text x="442" y="290" class="d14">No ve el código · cobertura parcial</text>
  <rect x="20" y="304" width="160" height="28" rx="4" fill="#e89822"/>
  <text x="30" y="322" class="t14">IAST / SCA</text>
  <rect x="186" y="304" width="240" height="28" rx="4" fill="#fdf1de"/>
  <text x="196" y="322" class="d14">Precisión interna / dependencias</text>
  <rect x="432" y="304" width="228" height="28" rx="4" fill="#fbe9e9"/>
  <text x="442" y="322" class="d14">Exige instrumentar / no ve tu código</text>
  <rect x="20" y="336" width="160" height="28" rx="4" fill="#888"/>
  <text x="30" y="354" class="t14">Revisión manual · pentest</text>
  <rect x="186" y="336" width="240" height="28" rx="4" fill="#f0f0f0"/>
  <text x="196" y="354" class="d14">LÓGICA DE NEGOCIO y autorización</text>
  <rect x="432" y="336" width="228" height="28" rx="4" fill="#fbe9e9"/>
  <text x="442" y="354" class="d14">Cara · foto de un momento</text>
  <rect x="60" y="368" width="560" height="22" rx="5" fill="none" stroke="#d13c3c" stroke-width="2"/>
  <text x="340" y="383" text-anchor="middle" style="font:700 10px system-ui;fill:#d13c3c">Ninguna herramienta automática detecta fallos de lógica de negocio ni de autorización</text>
  <text x="670" y="410" text-anchor="end" style="font:11px system-ui;fill:#666">[Fuente: OWASP-TOP10; OWASP-ASVS; CWE; CVE; CVSS]</text>
</svg>
```

---

*Los 14 diagramas son autosuficientes: no dependen de fuentes tipográficas externas ni de imágenes, usan únicamente `system-ui` con reserva `sans-serif`, llevan `role="img"` y `aria-label` descriptivo para lectores de pantalla, y sus clases CSS están sufijadas con el número del diagrama para evitar colisiones de estilo al embeberlos todos en la misma página (lección del Tema 5).*
