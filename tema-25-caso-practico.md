# Tema 25 — Casos Prácticos

> **Título oficial**: Accesibilidad, diseño universal y usabilidad. Acceso y usabilidad de las tecnologías, productos y servicios relacionados con la sociedad de la información. Confidencialidad y disponibilidad de la información en puestos de usuario final. Conceptos de seguridad en el desarrollo de los sistemas.
>
> **Formato**: 3 casos prácticos sobre supuestos reales del Ayuntamiento de Madrid. Cada caso suma **10 puntos**.
> **Nivel**: C1 — Técnico Auxiliar TIC, Ayuntamiento de Madrid

Los tres casos recorren el servicio de referencia **cita previa y consulta de expedientes** (ver tema-25-contenido.md, «Convenciones»), uno por cada bloque del tema: el **Caso 1** trabaja la **accesibilidad y la usabilidad** del servicio público; el **Caso 2**, la **confidencialidad y la disponibilidad en el puesto** desde el que se tramita; y el **Caso 3**, la **seguridad en el desarrollo** de la aplicación que lo sostiene.

---

## Caso 1 — Auditoría de accesibilidad de la sede de cita previa

### Enunciado

El Ayuntamiento ha publicado un nuevo portal de **cita previa** para las Oficinas de Atención a la Ciudadanía. Tras varias quejas vecinales, se encarga una revisión y se detecta lo siguiente:

1. Las imágenes de los iconos de cada tipo de trámite tienen el atributo `alt` con el valor del nombre del fichero (`icono-01.png`, `icono-02.png`…).
2. El calendario de selección de día **solo puede manejarse con el ratón**: no responde a la navegación con teclado.
3. Los campos obligatorios se señalan **únicamente con el borde en rojo**.
4. El vídeo explicativo de cómo pedir cita no tiene subtítulos ni transcripción.
5. La sesión **caduca a los cinco minutos sin previo aviso** y sin posibilidad de prórroga, y el formulario se pierde.
6. El pie de página **no enlaza ninguna declaración de accesibilidad**.

El área gestora propone declarar el portal «plenamente conforme», ya que un analizador automático no ha devuelto errores.

### Cuestiones

**Cuestión 1 — Clasificación de los incumplimientos (3 puntos).** Asigne cada uno de los seis hallazgos al **principio POUR** de WCAG que vulnera e indique la pauta o el criterio afectado.

**Cuestión 2 — Nivel exigible y norma aplicable (2 puntos).** Indique qué nivel de conformidad es exigible al Ayuntamiento, en virtud de qué norma, y por qué en un pliego debe citarse la EN 301 549 y no solo WCAG.

**Cuestión 3 — La propuesta del área gestora (2 puntos).** Valore si puede declararse el portal «plenamente conforme» con el argumento expuesto y explique por qué.

**Cuestión 4 — Declaración y vía de reclamación (3 puntos).** Enumere el contenido mínimo de la declaración de accesibilidad e indique qué figura del organismo debe atender la queja de un vecino que no puede completar la cita con su lector de pantalla.

### Solución orientativa

- **C1**: (§2.1)

| # | Hallazgo | Principio POUR | Pauta / criterio |
|---|---|---|---|
| 1 | `alt` con el nombre del fichero | **Perceptible** | 1.1 Alternativas textuales (1.1.1, nivel A): la alternativa debe ser **equivalente**, no un relleno. Si el icono es decorativo, `alt=""`. |
| 2 | Calendario solo con ratón | **Operable** | 2.1 Accesible por teclado (2.1.1, nivel A): toda la funcionalidad debe poder usarse solo con teclado y sin trampas de foco. |
| 3 | Obligatorios solo en rojo | **Perceptible** | 1.4.1 Uso del color (nivel A); además 3.3.2 Etiquetas o instrucciones (nivel A) por la falta de indicación textual. |
| 4 | Vídeo sin subtítulos ni transcripción | **Perceptible** | 1.2 Medios tempodependientes (1.2.2 Subtítulos, nivel A; 1.2.3 alternativa o audiodescripción). |
| 5 | Sesión que caduca sin aviso ni prórroga | **Operable** | 2.2 Tiempo suficiente (2.2.1 Ajuste de tiempo, nivel A): debe poder desactivarse, ajustarse o prorrogarse. |
| 6 | Sin declaración de accesibilidad | *No es un criterio WCAG* | Es un incumplimiento **del art. 15 del RD 1112/2018**, no de WCAG: conviene señalar expresamente la distinción. |

- **C2**: (§2.2 y §2.3) El nivel exigible es **AA** de WCAG, impuesto por el **RD 1112/2018** por remisión a la norma **UNE-EN 301 549** en su versión vigente. En un pliego debe citarse la **EN 301 549** porque es la **norma armonizada** de referencia en la contratación pública y porque su alcance es mayor: además de incorporar los criterios A y AA de WCAG para la web (cap. 9), cubre documentos no web (cap. 10), software (cap. 11), hardware y terminales de autoservicio (cap. 8), comunicación bidireccional (cap. 6) y documentación y servicios de apoyo (cap. 12). Exigir «WCAG AA» a secas dejaría fuera esos capítulos.

- **C3**: (§2.4) **No.** Es incorrecto por dos motivos. Primero, de hecho: los seis hallazgos demuestran que **hay incumplimientos**, luego el grado real es como mucho **parcialmente conforme**. Segundo, de método: una **herramienta automática detecta solo una parte de los criterios** —no puede juzgar si un `alt` es equivalente, ni si el orden del foco es lógico, ni si un vídeo tiene subtítulos correctos—, por lo que no sostiene por sí sola ninguna declaración. La evaluación válida combina revisión automática, **revisión manual experta** y **prueba con tecnologías de apoyo**. Declarar un grado superior al real es, además, un incumplimiento autónomo, porque la declaración debe reflejar el método realmente empleado.

- **C4**: (§2.4) Contenido mínimo de la declaración, conforme al modelo de la **Decisión (UE) 2018/1523**: (a) **grado de cumplimiento** —plenamente, parcialmente o no conforme—; (b) **contenido no accesible**, distinguiendo si lo es por falta de conformidad, por **carga desproporcionada** motivada o por estar **fuera del ámbito** de aplicación; (c) **alternativas accesibles** ofrecidas y datos de contacto; (d) **fecha de preparación o última revisión y método** empleado (autoevaluación o evaluación por tercero); y (e) **mecanismo de comunicación y reclamación**, con su procedimiento y plazos. La declaración debe estar enlazada de forma **visible y accesible desde todas las páginas** y revisarse al menos anualmente. La queja del vecino la atiende la **unidad responsable de accesibilidad** que el **art. 16 del RD 1112/2018** obliga a designar en cada organismo.

### Criterios de evaluación

| Criterio | Puntos |
|---|---|
| Los seis hallazgos correctamente asignados a principio y pauta, distinguiendo el que no es de WCAG | 3 |
| Nivel AA identificado, norma correcta citada y justificación del uso de la EN 301 549 en el pliego | 2 |
| Rechazo razonado de la declaración «plenamente conforme», con los dos motivos (de hecho y de método) | 2 |
| Contenido mínimo de la declaración e identificación de la unidad responsable de accesibilidad | 3 |

---

## Caso 2 — Incidente en el puesto de una Oficina de Atención a la Ciudadanía

### Enunciado

En una Oficina de Atención a la Ciudadanía se producen, en la misma semana, tres sucesos:

1. Una empleada recibe un correo aparentemente remitido por el servicio informático municipal que le pide «revalidar su cuenta» en un enlace. Introduce su usuario y contraseña. Al día siguiente se detecta actividad de esa cuenta a las 03:40 desde una dirección extranjera.
2. Un inspector sufre el **robo del portátil** de trabajo, que contenía descargados en el disco local los expedientes de licencias del distrito. El equipo estaba apagado y su disco iba **cifrado con cifrado de disco completo**.
3. Un puesto queda infectado por un **ransomware** que cifra la unidad de red compartida del área. La última copia de seguridad se hizo hace 26 horas y nunca se ha realizado una prueba de restauración.

Adicionalmente, la revisión posterior constata que todos los usuarios de la oficina son **administradores locales** de su equipo, que se usa una **cuenta genérica** («oac-mostrador») en los puestos de atención, y que las pantallas están orientadas hacia el mostrador de público.

### Cuestiones

**Cuestión 1 — Análisis del primer suceso (2,5 puntos).** Identifique el tipo de ataque, la dimensión de seguridad comprometida y **dos medidas** que lo habrían neutralizado, indicando cuál de ellas es la más eficaz y por qué.

**Cuestión 2 — El portátil robado (2,5 puntos).** Determine qué dimensiones de seguridad se ven afectadas, si se ha producido una brecha de confidencialidad de datos personales y qué actuaciones procede realizar. Señale además el problema de fondo que el incidente revela.

**Cuestión 3 — El ransomware (3 puntos).** Calcule el RPO efectivo del incidente, valore la política de copias, indique qué debe verificarse antes de dar el servicio por recuperado y explique por qué disponer de copias **no** exime de tratar el suceso como posible brecha de datos personales.

**Cuestión 4 — Deficiencias estructurales (2 puntos).** Enumere las tres deficiencias detectadas en la revisión, indique qué principio o medida vulnera cada una y proponga su corrección.

### Solución orientativa

- **C1**: (§3.1, §3.2.1) Es un ataque de **phishing** (ingeniería social) que ha derivado en el **robo de credenciales** y en un acceso no autorizado. Dimensiones comprometidas: **autenticidad** (un tercero se autentica como la empleada), **confidencialidad** (accede a información que no le corresponde) y **trazabilidad** (las actuaciones se imputan a una persona que no las hizo). Dos medidas: (a) **autenticación multifactor**, preferentemente **resistente al phishing** (FIDO2/WebAuthn o certificado en tarjeta), y (b) **formación y concienciación** con simulaciones periódicas, más filtrado de correo y reescritura de enlaces. La más eficaz es la **MFA resistente al phishing**, porque su credencial está **ligada criptográficamente al dominio legítimo** y no puede entregarse a un sitio suplantado ni siquiera por un usuario engañado; la formación reduce la probabilidad, pero depende del acierto humano en cada correo. Actuación inmediata: revocar la sesión, cambiar la credencial, revisar los registros de acceso de esa cuenta y valorar si hubo acceso a datos personales.

- **C2**: (§3.1.2, §3.2.2) Se afecta con seguridad la **disponibilidad** (el inspector pierde su herramienta y los expedientes que solo estaban en local). La **confidencialidad**, en cambio, **no se compromete** si el cifrado de disco completo estaba correctamente implantado, el equipo estaba **apagado** y la clave no era accesible (custodiada por TPM y protegida por credencial robusta): la información resulta ininteligible para el tercero. Actuaciones: documentar el incidente internamente y valorar la notificación a la autoridad de control —el RGPD contempla que, cuando los datos son ininteligibles para terceros, puede no ser necesaria la comunicación a los interesados—; **revocar** credenciales y certificados alojados en el equipo; ordenar el **borrado remoto** si el sistema de gestión de dispositivos lo permite; y denunciar la sustracción. El problema de fondo que revela el incidente es que **había información única residiendo en el disco local**: el dato de trabajo debe vivir en el repositorio corporativo, siendo el disco caché y no archivo. Si el equipo hubiera sido sustraído **con la sesión iniciada**, o sin cifrado, sí habría compromiso de confidencialidad y procedería evaluar la notificación en **72 horas** y la comunicación a los afectados si el riesgo fuera alto.

- **C3**: (§3.1.2, §3.3.1, §3.3.2) **RPO efectivo = 26 horas**: se pierde el trabajo de más de un día, lo que probablemente excede el RPO comprometido para un servicio de atención. La política de copias es **deficiente** por dos motivos independientes: la **frecuencia** no cubre el RPO necesario y, sobre todo, **nunca se ha probado la restauración**, de modo que la copia es una hipótesis, no una garantía; además debe verificarse que la copia estaba **fuera del alcance del atacante** (inmutable o desconectada), porque el ransomware moderno busca primero cifrar o borrar las copias. Antes de dar el servicio por recuperado hay que: **erradicar** el código malicioso y determinar el vector de entrada; **reconstruir** el puesto desde imagen limpia y no simplemente desinfectarlo; **restaurar** desde una copia anterior a la infección y **verificar la integridad** de lo restaurado; **rotar credenciales** que hayan podido quedar expuestas; y **revisar los registros** para acotar el alcance. Tener copias **no exime** de tratar el suceso como posible **brecha de datos personales** porque el ransomware actual practica **doble extorsión**: además de cifrar, **exfiltra** la información, de modo que puede haber compromiso de confidencialidad aunque la disponibilidad se recupere.

- **C4**: (§3.2.1, §3.1.1)

| Deficiencia | Qué vulnera | Corrección |
|---|---|---|
| Usuarios administradores locales | **Mínimo privilegio** (Saltzer y Schroeder; requisito mínimo del ENS) | Retirar el privilegio administrativo de la cuenta ordinaria; cuentas administrativas **separadas y nominativas**, no usadas para navegar ni leer correo. |
| Cuenta genérica compartida «oac-mostrador» | **Trazabilidad** (dimensión del ENS) e imputabilidad | Cuentas **nominativas** para todo el personal; si el puesto es compartido, sesión individual con credencial propia. |
| Pantallas orientadas al público | **Confidencialidad**: espionaje visual | Reorientar los monitores, instalar **filtros de privacidad** y aplicar bloqueo automático de sesión por inactividad y manual al ausentarse. |

### Criterios de evaluación

| Criterio | Puntos |
|---|---|
| Phishing identificado, dimensiones afectadas y dos medidas con justificación de la más eficaz | 2,5 |
| Análisis correcto del portátil cifrado, con la distinción entre disponibilidad y confidencialidad y el problema de fondo del dato residente | 2,5 |
| RPO calculado, crítica de la política de copias, pasos de recuperación y razonamiento de la doble extorsión | 3 |
| Las tres deficiencias con el principio vulnerado y su corrección | 2 |

---

## Caso 3 — Contratación y verificación del desarrollo de la aplicación

### Enunciado

El Ayuntamiento licita el desarrollo de la **nueva aplicación de cita previa y consulta de expedientes**, que tratará datos personales de la ciudadanía y se integrará con el sistema de identidad (Cl@ve y certificado electrónico). En la primera auditoría del producto entregado se detecta que:

1. La consulta de un expediente se realiza con la dirección `/expedientes/ver?id=48213` y **no se comprueba en el servidor** si el expediente pertenece al usuario autenticado.
2. El buscador construye la consulta a la base de datos **concatenando** el texto introducido por el usuario.
3. Ante un error, la aplicación devuelve al navegador la **traza completa** de la excepción, con la versión del gestor de base de datos y la ruta del servidor.
4. La aplicación arrastra una biblioteca de terceros con una **vulnerabilidad crítica publicada**, y el proveedor no dispone de inventario de dependencias.
5. El *token* de sesión (JWT) se guarda en el almacenamiento local del navegador y **no tiene fecha de caducidad**.

### Cuestiones

**Cuestión 1 — Clasificación de los cinco hallazgos (3 puntos).** Asigne cada hallazgo a su categoría del **OWASP Top 10:2021** y a la categoría **STRIDE** correspondiente.

**Cuestión 2 — Corrección técnica (3 puntos).** Proponga la corrección concreta de los hallazgos 1, 2 y 5, indicando en cada caso por qué la solución «evidente» pero insuficiente no sirve.

**Cuestión 3 — Requisitos que debieron figurar en el pliego (2 puntos).** Indique **cuatro** exigencias de seguridad que debieron formar parte del contrato para prevenir esta situación, e identifique el catálogo de OWASP idóneo para redactarlas.

**Cuestión 4 — Verificación y cadena de suministro (2 puntos).** Explique qué técnicas de análisis habrían detectado cada tipo de hallazgo y qué debe implantar el proveedor para responder con rapidez a la publicación de una vulnerabilidad en una dependencia.

### Solución orientativa

- **C1**: (§4.1.2, §4.3.1)

| # | Hallazgo | OWASP Top 10:2021 | STRIDE |
|---|---|---|---|
| 1 | Sin comprobación de propiedad del expediente (IDOR) | **A01** Pérdida de control de acceso | **E** — Elevación de privilegios |
| 2 | Consulta construida por concatenación | **A03** Inyección | **T** — Manipulación (y, según el caso, **I**) |
| 3 | Traza completa devuelta al navegador | **A05** Configuración de seguridad defectuosa | **I** — Revelación de información |
| 4 | Biblioteca vulnerable sin inventario | **A06** Componentes vulnerables y desactualizados (con vertiente de **A08** en cuanto a integridad de la cadena de suministro) | **T** — Manipulación |
| 5 | JWT sin caducidad en almacenamiento local | **A07** Fallos de identificación y autenticación | **S** — Suplantación |

- **C2**: (§4.2.2, §4.2.3)
  - **Hallazgo 1**: la corrección es **comprobar la autorización en el servidor, en cada petición**, verificando que el expediente solicitado pertenece al usuario autenticado, denegando por defecto y **registrando** el intento fallido. Lo insuficiente sería **ocultar el enlace en el menú** o cifrar el identificador: ocultar en el cliente no es autorizar, y un identificador opaco sigue siendo válido si se obtiene por otra vía (es seguridad por oscuridad). Usar identificadores no predecibles (UUID) es una medida **complementaria**, para dificultar la enumeración masiva.
  - **Hallazgo 2**: la corrección es usar **consultas parametrizadas** (sentencias preparadas), de modo que la consulta se compile con marcadores y los valores viajen aparte sin poder alterar la estructura. Lo insuficiente sería **escapar comillas** o filtrar palabras reservadas: las listas negras siempre quedan incompletas y el escapado manual depende del motor. Como defensa en profundidad, el usuario con el que la aplicación se conecta a la base de datos debe tener **permisos mínimos**.
  - **Hallazgo 5**: el *token* debe tener **vida corta** con caducidad (`exp`) validada, acompañarse de un **token de refresco revocable en el servidor** con rotación, y almacenarse preferentemente en una **cookie `HttpOnly` + `Secure` + `SameSite`** en lugar del almacenamiento local, complementada con protección **CSRF**. Debe además rechazarse el algoritmo `none` y validarse firma, emisor y audiencia. Lo insuficiente sería **alargar la vida del token** o confiar en que el cliente lo borre al cerrar sesión: un JWT es **autocontenido y no revocable por sí mismo**.

- **C3**: (§4.1.1, §4.1.2) Cuatro exigencias contractuales, entre otras posibles: (a) **conformidad con el nivel aplicable de OWASP ASVS**, verificable en la recepción; (b) **modelado de amenazas** documentado en la fase de diseño y actualizado ante cambios relevantes; (c) **SAST y SCA automáticos en cada confirmación** del repositorio, con puertas de calidad que detengan el despliegue por encima de un umbral de severidad, más **DAST** sobre preproducción; (d) **prueba de penetración por un tercero independiente** antes de la puesta en producción y tras cada cambio mayor, con plan de corrección y verificación. Cabe añadir la entrega de un **SBOM** actualizado, el compromiso de plazos de corrección por severidad y la prohibición de usar datos reales en entornos no productivos. El catálogo idóneo para redactarlas es **OWASP ASVS**, porque es un **catálogo de requisitos verificables** del producto, mientras que el Top 10 es un documento de concienciación y SAMM mide la madurez del proceso del proveedor.

- **C4**: (§4.3.2, §4.3.3) Detección por técnica: el **SAST** habría señalado la concatenación del hallazgo 2 y, posiblemente, el manejo del *token*; el **DAST** habría detectado la traza expuesta del hallazgo 3 y la configuración de la sesión del hallazgo 5; el **SCA** habría identificado inmediatamente la dependencia vulnerable del hallazgo 4; y el hallazgo 1 —fallo de **autorización**— solo lo detectan de forma fiable la **revisión manual de código** y la **prueba de penetración**, porque ninguna herramienta automática entiende la lógica de negocio ni sabe qué expediente corresponde a qué persona. Para responder con rapidez a una vulnerabilidad publicada, el proveedor debe implantar: **SBOM** en formato normalizado (SPDX o CycloneDX) mantenido en cada versión, **SCA continuo** integrado en la construcción, **fijación de versiones y verificación de integridad** de los artefactos mediante repositorio interno y firma, una **política de actualización** que distinga la corrección de seguridad de la evolutiva y la priorice por severidad (**CVSS**) y explotación activa, y un procedimiento de **respuesta a vulnerabilidades** con plazos comprometidos y verificación posterior de la corrección.

### Criterios de evaluación

| Criterio | Puntos |
|---|---|
| Los cinco hallazgos correctamente clasificados en OWASP Top 10 y en STRIDE | 3 |
| Correcciones técnicas correctas de los hallazgos 1, 2 y 5, con la crítica de la solución insuficiente en cada caso | 3 |
| Cuatro exigencias contractuales pertinentes y ASVS identificado como catálogo idóneo | 2 |
| Técnicas de detección asignadas por hallazgo, con la salvedad del fallo de autorización, y medidas de cadena de suministro | 2 |
