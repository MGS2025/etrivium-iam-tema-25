# Tema 25 — Índice

> **Título oficial**: Accesibilidad, diseño universal y usabilidad. Acceso y usabilidad de las tecnologías, productos y servicios relacionados con la sociedad de la información. Confidencialidad y disponibilidad de la información en puestos de usuario final. Conceptos de seguridad en el desarrollo de los sistemas.
>
> **Bloque**: Parte II — Técnico (Temas 11-40)
> **Nivel**: C1 — Técnico Auxiliar TIC, Ayuntamiento de Madrid

---

## Estructura del tema

1. **Accesibilidad, diseño universal y usabilidad**
   1.1. Usabilidad y diseño universal
   1.1.1. Principios de usabilidad y experiencia de usuario
   1.1.2. Fundamentos del diseño universal y diseño para todos
   1.1.3. Modelos de calidad e ISO/IEC 9241 e ISO/IEC 25010
   1.2. Acceso y usabilidad de las tecnologías, productos y servicios de la sociedad de la información
   1.2.1. Pautas de accesibilidad al contenido web WCAG
   1.2.2. Requisitos de accesibilidad TIC y norma EN 301 549
   1.2.3. Marco normativo en la Administración Pública
   1.2.4. Evaluación, auditoría y declaración de accesibilidad

2. **Confidencialidad y disponibilidad de la información en puestos de usuario final**
   2.1. Seguridad en el puesto de usuario final
   2.1.1. Preservación de la confidencialidad en puestos de usuario final
   2.1.2. Garantía de la disponibilidad de la información
   2.2. Control de acceso y protección criptográfica
   2.2.1. Autenticación de usuarios y principio de mínimo privilegio
   2.2.2. Cifrado de almacenamiento local y comunicaciones
   2.3. Seguridad operativa y prevención de pérdida de datos
   2.3.1. Protección frente a código malicioso en el endpoint
   2.3.2. Copias de seguridad y prevención de pérdida de datos
   2.3.3. Esquema Nacional de Seguridad en el puesto de usuario final

3. **Conceptos de seguridad en el desarrollo de los sistemas**
   3.1. Ciclo de vida de desarrollo seguro
   3.1.1. Modelos e integración de la seguridad en el desarrollo
   3.1.2. Análisis de requisitos y modelado de amenazas
   3.2. Principios y prácticas de codificación segura
   3.2.1. Principios de diseño seguro y defensa en profundidad
   3.2.2. Validación y sanitización de entradas y salidas
   3.2.3. Gestión segura de sesiones, autenticación y autorización
   3.2.4. Registro de auditoría y tratamiento de excepciones
   3.3. Vulnerabilidades y verificación de la seguridad
   3.3.1. Vulnerabilidades en el desarrollo de software y catálogo OWASP
   3.3.2. Análisis de seguridad mediante técnicas estáticas y dinámicas
   3.3.3. Bastionado de aplicaciones y gestión de dependencias

*Dentro del epígrafe 3.2.3 el contenido desarrolla dos apartados de cuarto nivel previstos en el esqueleto oficial: 3.2.3.1 «Mecanismos de autenticación y control de acceso en aplicaciones» y 3.2.3.2 «Manejo seguro de tokens y control de sesiones».*

---

## Conceptos clave para memorizar

| Concepto | Dato clave |
|---|---|
| Usabilidad (ISO 9241-11) | Grado en que un sistema permite a **usuarios concretos** alcanzar objetivos concretos con **eficacia, eficiencia y satisfacción** en un **contexto de uso** determinado: no es una propiedad absoluta del producto |
| Accesibilidad vs. usabilidad | La **accesibilidad** es una condición de partida (que se pueda usar, incluidas las personas con discapacidad); la **usabilidad**, un grado de calidad de ese uso. La accesibilidad es **exigible por ley**; la usabilidad, no |
| Diseño universal | Diseño de productos y entornos utilizables por **todas las personas**, en la mayor medida posible, **sin necesidad de adaptación ni diseño especializado** (definición del art. 2 de la Convención de la ONU). **7 principios** del Center for Universal Design (1997) |
| Diseño para todas las personas | Denominación española equivalente en el RDL 1/2013, junto a **accesibilidad universal** y a los **ajustes razonables** (medida individual y subsidiaria cuando el diseño universal no basta) |
| POUR | Los cuatro principios de WCAG: **P**erceptible, **O**perable, **C**omprensible (*Understandable*) y **R**obusto |
| Estructura de WCAG | 4 principios → **13 pautas** → **criterios de conformidad** (verificables, en niveles **A / AA / AAA**) → técnicas (suficientes y consultivas, **no normativas**) |
| Nivel exigido en el sector público | **AA** de WCAG (más los requisitos no-web de la EN 301 549). Lo fija la Directiva (UE) 2016/2102 y, en España, el **RD 1112/2018** |
| WCAG 2.2 | Recomendación W3C de **5 de octubre de 2023**; añade 9 criterios nuevos y **retira** el criterio 4.1.1 *Análisis sintáctico*. WCAG 2.0 es además la norma **ISO/IEC 40500:2012** |
| EN 301 549 | Norma **armonizada europea** de accesibilidad TIC: cubre web (cap. 9), documentos (cap. 10), software (cap. 11), hardware (cap. 8), comunicación bidireccional (cap. 6) y audiovisual (cap. 7). Es la referencia del RD 1112/2018 y de la contratación pública |
| Declaración de accesibilidad | Obligatoria, con modelo fijado por la **Decisión (UE) 2018/1523**; indica el grado de cumplimiento (**plenamente / parcialmente / no conforme**), el contenido no accesible, la fecha y método de evaluación y el **mecanismo de comunicación y reclamación** |
| Unidad responsable de accesibilidad | Figura que el **art. 16 del RD 1112/2018** obliga a designar en cada organismo del sector público; coordina, informa y responde las quejas |
| Triada CID | **Confidencialidad** (solo quien debe accede), **Integridad** (el dato no se altera indebidamente) y **Disponibilidad** (accesible cuando se necesita). El ENS añade **autenticidad** y **trazabilidad** |
| Mínimo privilegio | Cada usuario y proceso opera con los permisos **estrictamente necesarios** durante el **tiempo estrictamente necesario**: el usuario del puesto **no** debe ser administrador local |
| RPO / RTO | **RPO**: cuánta información se puede permitir perder (mide hacia atrás, define la frecuencia de la copia). **RTO**: cuánto se puede tardar en volver a funcionar (mide hacia delante, define la capacidad de restauración) |
| Regla 3-2-1 | **3** copias de los datos, en **2** soportes distintos, con **1** fuera de las instalaciones; en su versión reforzada, **1 inmutable o desconectada** frente al *ransomware*. Una copia no verificada mediante **prueba de restauración** no cuenta como copia |
| DLP | *Data Loss Prevention*: control que inspecciona el dato en uso, en tránsito y en reposo y **bloquea su salida** no autorizada (correo, USB, nube personal) |
| ENS — categorías | Un sistema se clasifica en categoría **Básica, Media o Alta** según el impacto en las cinco dimensiones (CIDAT); la categoría determina las medidas exigibles del Anexo II del RD 311/2022 |
| SSDLC / *shift left* | Integrar la seguridad **en todas las fases** del ciclo de vida y **cuanto antes**: corregir un defecto en requisitos cuesta órdenes de magnitud menos que corregirlo en producción |
| STRIDE | Modelo de amenazas de seis categorías: *Spoofing*, *Tampering*, *Repudiation*, *Information disclosure*, *Denial of service* y *Elevation of privilege*; cada una se contrarresta con una propiedad (autenticidad, integridad, no repudio, confidencialidad, disponibilidad y autorización) |
| Principios de Saltzer y Schroeder | Ocho principios de 1975 que siguen vigentes: mínimo privilegio, economía de mecanismo, valores por defecto seguros (*fail-safe defaults*), mediación completa, **diseño abierto** (la seguridad no reside en el secreto del diseño), separación de privilegios, mínimo mecanismo común y aceptabilidad psicológica |
| Validación de entradas | **Lista blanca** (aceptar solo lo previsto) mejor que lista negra; validación **siempre en el servidor** (la del cliente es solo usabilidad); **canonicalizar antes de validar** |
| Codificación de salida | La inyección se evita **separando código y datos**: consultas **parametrizadas** frente a SQLi y **codificación contextual** de la salida frente a XSS |
| Vulnerabilidad vs. debilidad | **CWE** cataloga **debilidades** (tipos de defecto, p. ej. CWE-79 XSS); **CVE** identifica **vulnerabilidades concretas** en productos concretos; **CVSS** puntúa su severidad de 0,0 a 10,0 |
| OWASP Top 10:2021 | A01 Control de acceso roto · A02 Fallos criptográficos · A03 Inyección · A04 Diseño inseguro · A05 Configuración de seguridad defectuosa · A06 Componentes vulnerables y desactualizados · A07 Fallos de identificación y autenticación · A08 Fallos de integridad de software y datos · A09 Fallos de registro y monitorización · A10 SSRF |
| SAST / DAST / IAST / SCA | **SAST**: analiza el código sin ejecutarlo (temprano, muchos falsos positivos). **DAST**: ataca la aplicación en ejecución (sin ver el código). **IAST**: instrumenta la aplicación y combina ambos. **SCA**: analiza las **dependencias** de terceros |
| SBOM | Lista de materiales de software (formatos **SPDX** y **CycloneDX**): inventario de componentes que permite saber en horas si una vulnerabilidad publicada afecta a la organización |

---

*Tiempo estimado de estudio: 15-17 horas*
*Extensión del contenido: ~21.500 palabras · 14 diagramas SVG embebidos*
