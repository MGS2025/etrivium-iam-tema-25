# Tema 25 — Fuentes

> **Título oficial**: Accesibilidad, diseño universal y usabilidad. Acceso y usabilidad de las tecnologías, productos y servicios relacionados con la sociedad de la información. Confidencialidad y disponibilidad de la información en puestos de usuario final. Conceptos de seguridad en el desarrollo de los sistemas.
>
> **Criterio**: todo dato del contenido cita un **ID** inline (p. ej. `[WCAG22]`). Tier 1 = normas, estándares y textos legales canónicos (W3C, ISO/IEC, ETSI, NIST, MITRE, OWASP, IETF, BOE, DOUE). Tier 2 = guías metodológicas, catálogos de organismos de referencia y literatura fundacional, citadas para ilustrar sin atar el tema a un producto concreto. Tier 3 = marco institucional y del puesto (contexto, no contenido técnico puro).

---

## Tier 1 — Normas, estándares y textos legales

| ID | Referencia |
|---|---|
| `[WCAG22]` | W3C. *Web Content Accessibility Guidelines (WCAG) 2.2*, Recomendación W3C de 5 de octubre de 2023. w3.org/TR/WCAG22. Norma de referencia mundial de accesibilidad del contenido web: 4 principios (POUR), 13 pautas y criterios de conformidad en niveles A, AA y AAA. |
| `[WCAG21]` | W3C. *Web Content Accessibility Guidelines (WCAG) 2.1*, Recomendación W3C de 5 de junio de 2018. w3.org/TR/WCAG21. Versión incorporada por la norma armonizada europea vigente. |
| `[WCAG20]` | W3C. *Web Content Accessibility Guidelines (WCAG) 2.0*, Recomendación W3C de 11 de diciembre de 2008; adoptada como norma internacional **ISO/IEC 40500:2012**. |
| `[WAI-ARIA]` | W3C. *Accessible Rich Internet Applications (WAI-ARIA) 1.2* y *ARIA Authoring Practices Guide*. w3.org/TR/wai-aria-1.2. Semántica accesible (`role`, `aria-*`) para componentes de interfaz dinámicos. |
| `[ATAG20]` | W3C. *Authoring Tool Accessibility Guidelines (ATAG) 2.0*. w3.org/TR/ATAG20. Accesibilidad de las **herramientas de autor** (gestores de contenidos, editores). |
| `[UAAG20]` | W3C. *User Agent Accessibility Guidelines (UAAG) 2.0*. w3.org/TR/UAAG20. Accesibilidad de los **agentes de usuario** (navegadores, reproductores). |
| `[WCAG-EM]` | W3C WAI. *Website Accessibility Conformance Evaluation Methodology (WCAG-EM) 1.0*. w3.org/TR/WCAG-EM. Metodología de los cinco pasos para evaluar la conformidad de un sitio completo. |
| `[ACT-RULES]` | W3C. *Accessibility Conformance Testing (ACT) Rules Format 1.0* y catálogo de reglas ACT. w3.org/TR/act-rules-format. Base de la armonización entre herramientas automáticas de evaluación. |
| `[EN301549]` | ETSI/CEN/CENELEC. **EN 301 549** *Requisitos de accesibilidad para productos y servicios TIC* (v3.2.1, 2021). Norma armonizada europea de accesibilidad TIC; su capítulo 9 incorpora WCAG para web, el 10 para documentos y el 11 para software, con capítulos específicos de hardware (8), comunicación bidireccional (6) y contenidos audiovisuales (7). |
| `[ISO9241-11]` | ISO 9241-11:2018. *Ergonomics of human-system interaction — Part 11: Usability: Definitions and concepts*. Define usabilidad como **eficacia + eficiencia + satisfacción** en un contexto de uso específico. |
| `[ISO9241-110]` | ISO 9241-110:2020. *Part 110: Interaction principles*. Los siete principios de interacción (idoneidad para la tarea, carácter autodescriptivo, conformidad con las expectativas, aprendizaje, controlabilidad, robustez frente a errores de uso y compromiso del usuario). |
| `[ISO9241-210]` | ISO 9241-210:2019. *Part 210: Human-centred design for interactive systems*. Proceso iterativo de diseño centrado en el usuario en cuatro actividades. |
| `[ISO9241-171]` | ISO 9241-171:2008. *Part 171: Guidance on software accessibility*. Requisitos y recomendaciones de accesibilidad del software. |
| `[ISO25010]` | ISO/IEC 25010 (serie SQuaRE). *Modelo de calidad del producto software*: adecuación funcional, eficiencia de desempeño, compatibilidad, **usabilidad**, fiabilidad, **seguridad**, mantenibilidad y portabilidad, con sus subcaracterísticas. |
| `[ISO25000]` | ISO/IEC 25000 (SQuaRE). *Systems and software Quality Requirements and Evaluation*. Marco general de la familia: modelos de calidad (2501n), medición (2502n), requisitos (2503n) y evaluación (2504n). |
| `[ISO27001]` | UNE-EN ISO/IEC 27001. *Sistemas de gestión de la seguridad de la información — Requisitos*. Modelo de gestión basado en riesgos y mejora continua. |
| `[ISO27002]` | UNE-EN ISO/IEC 27002:2022. *Controles de seguridad de la información*. 93 controles en cuatro temas (organizativos, personas, físicos y tecnológicos); referencia directa de los controles del puesto de usuario. |
| `[ISO27034]` | ISO/IEC 27034. *Application security*. Marco de seguridad de aplicaciones a lo largo de su ciclo de vida. |
| `[ISO29119]` | ISO/IEC/IEEE 29119. *Software testing*. Marco de referencia de las pruebas de software, incluidas las de seguridad. |
| `[CDPD]` | Instrumento de Ratificación de la **Convención sobre los derechos de las personas con discapacidad** (Nueva York, 13 de diciembre de 2006). Define el **diseño universal** (art. 2) y obliga a garantizar la **accesibilidad** a los sistemas y tecnologías de la información (art. 9). |
| `[TRLGDPD]` | Real Decreto Legislativo 1/2013, de 29 de noviembre, texto refundido de la **Ley General de derechos de las personas con discapacidad y de su inclusión social**. Define *accesibilidad universal* y *diseño para todas las personas* (art. 2) y regula las condiciones básicas de accesibilidad. |
| `[DIR2016-2102]` | **Directiva (UE) 2016/2102** del Parlamento Europeo y del Consejo, de 26 de octubre de 2016, sobre la accesibilidad de los sitios web y aplicaciones para dispositivos móviles de los organismos del sector público. |
| `[RD1112-2018]` | **Real Decreto 1112/2018**, de 7 de septiembre, sobre accesibilidad de los sitios web y aplicaciones para dispositivos móviles del sector público. Transpone la Directiva 2016/2102: exige nivel **AA**, **declaración de accesibilidad**, mecanismo de comunicación y reclamación, y designa la **unidad responsable de accesibilidad** en cada organismo. |
| `[DEC2018-1523]` | **Decisión de Ejecución (UE) 2018/1523** de la Comisión, por la que se establece el **modelo de declaración de accesibilidad**. |
| `[DEC2018-1524]` | **Decisión de Ejecución (UE) 2018/1524** de la Comisión, por la que se establece la **metodología de seguimiento** y las disposiciones de presentación de informes de los Estados miembros. |
| `[DIR2019-882]` | **Directiva (UE) 2019/882** (*European Accessibility Act*, EAA), sobre los requisitos de accesibilidad de los productos y servicios. Extiende las exigencias de accesibilidad al **sector privado** (comercio electrónico, banca, transporte, libros electrónicos, servicios de comunicaciones). |
| `[LEY11-2023]` | **Ley 11/2023**, de 8 de mayo, de trasposición de Directivas de la Unión Europea, cuyo Libro I traspone la Directiva (UE) 2019/882 sobre requisitos de accesibilidad de los productos y servicios. |
| `[ENS]` | **Real Decreto 311/2022**, de 3 de mayo, por el que se regula el **Esquema Nacional de Seguridad**. Principios básicos, requisitos mínimos, categorización de sistemas (Básica/Media/Alta) y medidas del Anexo II (marco organizativo, marco operacional y medidas de protección). |
| `[ENI]` | **Real Decreto 4/2010**, de 8 de enero, por el que se regula el **Esquema Nacional de Interoperabilidad**, y sus Normas Técnicas de Interoperabilidad. |
| `[RGPD]` | **Reglamento (UE) 2016/679** (RGPD). Art. 5 (principios), **art. 25 (protección de datos desde el diseño y por defecto)**, art. 32 (seguridad del tratamiento), arts. 33-34 (notificación de brechas) y art. 35 (evaluación de impacto). |
| `[LOPDGDD]` | **Ley Orgánica 3/2018**, de 5 de diciembre, de Protección de Datos Personales y garantía de los derechos digitales. Título X: derechos digitales en el ámbito laboral (arts. 87-91: intimidad ante dispositivos digitales, videovigilancia, geolocalización y desconexión digital). |
| `[LPACAP]` | **Ley 39/2015**, de 1 de octubre, del Procedimiento Administrativo Común de las Administraciones Públicas. Derecho de relación electrónica y asistencia en el uso de medios electrónicos. |
| `[NIST-SSDF]` | NIST. *SP 800-218: Secure Software Development Framework (SSDF) v1.1*. Cuatro grupos de prácticas: preparar la organización (PO), proteger el software (PS), producir software bien asegurado (PW) y responder a las vulnerabilidades (RV). |
| `[NIST-800-63B]` | NIST. *SP 800-63B: Digital Identity Guidelines — Authentication and Lifecycle Management*. Niveles de garantía de autenticación (AAL1-AAL3), tipos de autenticador y recomendaciones sobre contraseñas. |
| `[NIST-800-111]` | NIST. *SP 800-111: Guide to Storage Encryption Technologies for End User Devices*. Cifrado de disco completo, de volumen y de fichero en el puesto de usuario. |
| `[NIST-800-88]` | NIST. *SP 800-88 Rev. 1: Guidelines for Media Sanitization*. Borrado seguro (*clear*, *purge*, *destroy*) de soportes al retirar un equipo. |
| `[NIST-CSF]` | NIST. *Cybersecurity Framework (CSF) 2.0*. Funciones Gobernar, Identificar, Proteger, Detectar, Responder y Recuperar. |
| `[CWE]` | MITRE. *Common Weakness Enumeration (CWE)* y **CWE Top 25 Most Dangerous Software Weaknesses**. Catálogo canónico de **debilidades** de software. cwe.mitre.org. |
| `[CVE]` | MITRE / NIST NVD. *Common Vulnerabilities and Exposures (CVE)* y *National Vulnerability Database*. Identificación única de **vulnerabilidades** concretas en productos concretos. |
| `[CVSS]` | FIRST. *Common Vulnerability Scoring System (CVSS)* v3.1 y v4.0. Métrica de severidad (0,0-10,0) con grupos base, temporal/de amenaza y ambiental. |
| `[CAPEC]` | MITRE. *Common Attack Pattern Enumeration and Classification*. Catálogo de patrones de ataque, complementario de CWE. |
| `[ATTACK]` | MITRE. *ATT&CK — Enterprise Matrix*. Base de conocimiento de tácticas y técnicas adversarias observadas, usada para orientar la defensa del puesto de usuario. |
| `[OWASP-TOP10]` | OWASP Foundation. *OWASP Top 10:2021* — los diez riesgos más críticos en aplicaciones web. owasp.org/Top10. |
| `[OWASP-ASVS]` | OWASP Foundation. *Application Security Verification Standard (ASVS)*. Catálogo de requisitos verificables de seguridad de aplicaciones, organizado en tres niveles de verificación. |
| `[OWASP-SAMM]` | OWASP Foundation. *Software Assurance Maturity Model (SAMM) 2.0*. Modelo de madurez del desarrollo seguro en cinco funciones de negocio (Gobierno, Diseño, Implementación, Verificación y Operaciones). |
| `[OWASP-PROACTIVE]` | OWASP Foundation. *Top 10 Proactive Controls*. Controles preventivos que un equipo de desarrollo debe incorporar por defecto. |
| `[OWASP-CHEAT]` | OWASP Foundation. *Cheat Sheet Series* (Input Validation, Session Management, Password Storage, Logging, XSS Prevention, SQL Injection Prevention…). cheatsheetseries.owasp.org. |
| `[RFC6749]` | IETF. *RFC 6749: The OAuth 2.0 Authorization Framework*. Delegación de autorización mediante *tokens* de acceso. |
| `[RFC7636]` | IETF. *RFC 7636: Proof Key for Code Exchange (PKCE)*. Protección del flujo de código de autorización en clientes públicos. |
| `[RFC7519]` | IETF. *RFC 7519: JSON Web Token (JWT)*. Formato de *token* autocontenido y firmado. |
| `[RFC8725]` | IETF. *RFC 8725: JSON Web Token Best Current Practices* (BCP 225). Prohíbe aceptar el algoritmo `none` y exige validar emisor, audiencia y caducidad. |
| `[RFC9700]` | IETF. *RFC 9700: Best Current Practice for OAuth 2.0 Security* (BCP 240). Consolida las recomendaciones de seguridad de OAuth 2.0. |
| `[RFC8446]` | IETF. *RFC 8446: The Transport Layer Security (TLS) Protocol Version 1.3*. Cifrado de las comunicaciones. |
| `[RFC6797]` | IETF. *RFC 6797: HTTP Strict Transport Security (HSTS)*. |
| `[WEBAUTHN]` | W3C. *Web Authentication (WebAuthn) Level 2/3* y FIDO Alliance, *FIDO2/CTAP*. Autenticación con criptografía de clave pública resistente a la suplantación de identidad (*phishing*). |
| `[FIPS197]` | NIST. *FIPS 197: Advanced Encryption Standard (AES)*. Algoritmo de cifrado simétrico de referencia. |

## Tier 2 — Guías metodológicas, catálogos y literatura fundacional

| ID | Referencia |
|---|---|
| `[NIELSEN]` | Nielsen, J. *10 Usability Heuristics for User Interface Design* (1994, revisadas). nngroup.com. Heurísticas de referencia para la evaluación experta de interfaces. |
| `[SHNEIDERMAN]` | Shneiderman, B. et al. *Designing the User Interface* — las **ocho reglas de oro** del diseño de interfaces. |
| `[NORMAN]` | Norman, D. A. *The Design of Everyday Things* (rev. 2013). Affordances, significantes, modelo conceptual y diseño centrado en la persona. |
| `[CUD]` | Center for Universal Design, North Carolina State University (Ronald L. Mace et al., 1997). *The Principles of Universal Design* — los **siete principios** del diseño universal. |
| `[UDL]` | CAST. *Universal Design for Learning (UDL) Guidelines*. Aplicación del diseño universal al ámbito del aprendizaje. |
| `[WAI]` | W3C Web Accessibility Initiative. *Introduction to Web Accessibility*, *Easy Checks*, *Evaluation Tools List*, *How to Meet WCAG (Quick Reference)*. w3.org/WAI. |
| `[SALTZER75]` | Saltzer, J. H. y Schroeder, M. D. *The Protection of Information in Computer Systems* (Proceedings of the IEEE, 1975). Los **ocho principios de diseño seguro** (mínimo privilegio, economía de mecanismo, valores por defecto seguros, mediación completa, diseño abierto, separación de privilegios, mínimo mecanismo común y aceptabilidad psicológica). |
| `[SHOSTACK]` | Shostack, A. *Threat Modeling: Designing for Security* (2014). Método de las cuatro preguntas y modelo **STRIDE**. |
| `[MS-SDL]` | Microsoft. *Security Development Lifecycle (SDL)* — prácticas de seguridad integradas en el ciclo de desarrollo; origen del modelo STRIDE. |
| `[BSIMM]` | Synopsys. *Building Security In Maturity Model (BSIMM)*. Modelo descriptivo de madurez basado en la observación de programas reales de seguridad en el desarrollo. |
| `[CCN-STIC]` | Centro Criptológico Nacional. *Guías CCN-STIC* de la serie 800 (implantación del ENS) y 500/600 (configuración segura de sistemas y aplicaciones). ccn-cert.cni.es. Referencia de bastionado en el sector público español. |
| `[CCN-ENS]` | Centro Criptológico Nacional. *CCN-STIC 803 (valoración de sistemas)*, *CCN-STIC 804 (guía de implantación del ENS)* y perfiles de cumplimiento específicos. |
| `[OBSERVATORIO]` | Ministerio para la Transformación Digital y de la Función Pública. *Observatorio de Accesibilidad Web* y *Guía de validación de accesibilidad web*. administracionelectronica.gob.es. Herramienta de seguimiento de la Administración española. |
| `[AEPD-GUIA]` | Agencia Española de Protección de Datos. *Guía de protección de datos por defecto* y *Guía de privacidad desde el diseño*. aepd.es. |
| `[SBOM]` | Linux Foundation *SPDX* y OWASP *CycloneDX*. Formatos normalizados de **lista de materiales de software (SBOM)** para inventariar dependencias. |
| `[SEMVER]` | *Semantic Versioning 2.0.0*. semver.org. Convenio de versionado usado en la gestión de dependencias. |
| `[EPUB-A11Y]` | W3C / DAISY. *EPUB Accessibility 1.1* y perfiles de documento accesible. Referencia para la accesibilidad de documentos publicados. |
| `[PDF-UA]` | ISO 14289-1 (**PDF/UA**). Formato de documento PDF accesible universalmente, exigido por el capítulo 10 de la EN 301 549. |

## Tier 3 — Marco institucional y del puesto (contexto)

| ID | Referencia |
|---|---|
| `[BOAM10032]` | BOAM 10.032 (23-dic-2025). Bases específicas TIC C1 Ayuntamiento de Madrid — temario oficial de la convocatoria. |
| `[PSI-MADRID]` | Política de Seguridad de la Información del Ayuntamiento de Madrid y normativa municipal de uso de los sistemas de información, cuyo establecimiento exige el art. 12 del ENS `[ENS]` a toda entidad del sector público. Marco del que cuelgan las normas concretas del puesto de usuario municipal. |
| `[MADRID-A11Y]` | Declaración de accesibilidad y unidad responsable de accesibilidad del Ayuntamiento de Madrid, publicadas conforme al art. 15 del RD 1112/2018 `[RD1112-2018]`. |
| `[LEYCAPITALIDAD]` | Ley 22/2006, de 4 de julio, de Capitalidad y de Régimen Especial de Madrid. Marco competencial del Ayuntamiento citado como contexto de los ejemplos. |

---

*Las referencias Tier 1 fijan el fundamento normativo y técnico del tema en sus tres bloques: para la accesibilidad y la usabilidad, las recomendaciones del W3C (WCAG, ARIA, ATAG, UAAG, WCAG-EM), las normas ISO de ergonomía y calidad (9241 y 25010) y la cadena jurídica que va de la Convención de la ONU al RD 1112/2018 y a la Ley 11/2023; para el puesto de usuario final, ISO/IEC 27002, el Esquema Nacional de Seguridad y las publicaciones especiales del NIST; y para el desarrollo seguro, el SSDF del NIST, los catálogos de MITRE (CWE, CVE, CAPEC, ATT&CK), los proyectos canónicos de OWASP (Top 10, ASVS, SAMM, Proactive Controls) y los RFC del IETF sobre OAuth 2.0, JWT y TLS. Tier 2 aporta la metodología y la literatura fundacional (Nielsen, Shneiderman, Norman, Saltzer y Schroeder, Shostack) y las guías del CCN y del Observatorio de Accesibilidad, que son las que un técnico del sector público español maneja en la práctica. Tier 3 sitúa el marco municipal de los ejemplos.*
