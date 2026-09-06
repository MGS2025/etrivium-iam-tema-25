# Tema 25 — Test de Autoevaluación

> **Título**: Accesibilidad, diseño universal y usabilidad. Acceso y usabilidad de las tecnologías, productos y servicios relacionados con la sociedad de la información. Confidencialidad y disponibilidad de la información en puestos de usuario final. Conceptos de seguridad en el desarrollo de los sistemas.
> **Formato**: 60 preguntas tipo test A/B/C (formato oficial oposición)
> **Nivel**: C1 — Técnico Auxiliar TIC, Ayuntamiento de Madrid
> **Versión**: v1.0 — Pendiente validación
> **Fecha**: 2026-08-20
> **Fuentes**: ver tema-25-fuentes.md

---

## Instrucciones

- Cada pregunta tiene **3 opciones** (A, B, C). Solo una es correcta.
- Penalización en examen real: respuesta incorrecta descuenta **1/3** del valor de una correcta.
- Tiempo orientativo: 1 minuto por pregunta.
- Distribución: Usabilidad y diseño universal (P1-P10), Accesibilidad, WCAG y marco normativo (P11-P23), Puesto de usuario final (P24-P43), Desarrollo seguro (P44-P60).

---

### Pregunta 1

**Según la norma ISO 9241-11:2018, la usabilidad se define como el grado en que un sistema permite a usuarios específicos alcanzar objetivos específicos con:**

A) Eficacia, eficiencia y satisfacción en un contexto de uso específico
B) Accesibilidad, disponibilidad y confidencialidad
C) Corrección, completitud y pertinencia funcional

<details><summary>Respuesta</summary>

**Correcta: A) Eficacia, eficiencia y satisfacción en un contexto de uso específico** Los tres atributos van siempre acompañados de la referencia al contexto de uso: la usabilidad no es una propiedad absoluta del producto.

*Referencia: §1.1 [ISO9241-11]*
</details>

---

### Pregunta 2

**¿Cuál de estas afirmaciones describe correctamente la relación entre accesibilidad y usabilidad?**

A) Son sinónimos: un sitio accesible es siempre usable
B) La accesibilidad es una condición de partida exigible por ley; la usabilidad es un grado de calidad de uso no exigible con carácter general
C) La usabilidad es exigible por el RD 1112/2018 y la accesibilidad solo se recomienda

<details><summary>Respuesta</summary>

**Correcta: B) La accesibilidad es una condición de partida exigible por ley; la usabilidad es un grado de calidad de uso no exigible con carácter general** Un sitio puede cumplir WCAG AA y ser poco usable, y viceversa. Lo que el RD 1112/2018 impone es la accesibilidad, no la usabilidad.

*Referencia: §1 [RD1112-2018] [ISO9241-11]*
</details>

---

### Pregunta 3

**El diseño universal se define en la Convención de la ONU sobre los derechos de las personas con discapacidad como el diseño de productos y entornos utilizables por todas las personas:**

A) Siempre que se disponga de una versión alternativa accesible del producto
B) Mediante adaptaciones individuales realizadas a petición del interesado
C) En la mayor medida posible, sin necesidad de adaptación ni diseño especializado

<details><summary>Respuesta</summary>

**Correcta: C) En la mayor medida posible, sin necesidad de adaptación ni diseño especializado** Es la definición literal del artículo 2 de la Convención, recogida también por el RDL 1/2013 con la denominación «diseño para todas las personas».

*Referencia: §1.2 [CDPD] [TRLGDPD]*
</details>

---

### Pregunta 4

**Los ajustes razonables, en la normativa española de discapacidad:**

A) Sustituyen al diseño universal cuando este resulta costoso
B) Son medidas individualizadas y subsidiarias, que se aplican cuando el diseño universal no resuelve la situación de una persona concreta
C) Son obligatorios con independencia de que impongan una carga desproporcionada

<details><summary>Respuesta</summary>

**Correcta: B) Son medidas individualizadas y subsidiarias, que se aplican cuando el diseño universal no resuelve la situación de una persona concreta** La secuencia correcta es diseño universal, tecnología de apoyo compatible y, solo entonces, ajuste razonable; y estos no pueden imponer una carga desproporcionada.

*Referencia: §1.2 [TRLGDPD] [CDPD]*
</details>

---

### Pregunta 5

**¿Cuántos principios formuló el Center for Universal Design en 1997 y cuál de los siguientes es uno de ellos?**

A) Siete principios, entre ellos la tolerancia al error
B) Cuatro principios, entre ellos la robustez
C) Diez principios, entre ellos la visibilidad del estado del sistema

<details><summary>Respuesta</summary>

**Correcta: A) Siete principios, entre ellos la tolerancia al error** Los cuatro principios (POUR) corresponden a WCAG y las diez heurísticas a Nielsen; los siete principios del diseño universal son de Ronald L. Mace y su equipo.

*Referencia: §1.2 [CUD]*
</details>

---

### Pregunta 6

**En el modelo de calidad del producto software ISO/IEC 25010, la accesibilidad es:**

A) Una característica independiente, al mismo nivel que la fiabilidad
B) Una subcaracterística de la seguridad
C) Una subcaracterística de la usabilidad

<details><summary>Respuesta</summary>

**Correcta: C) Una subcaracterística de la usabilidad** En el mismo modelo, la disponibilidad es subcaracterística de la fiabilidad y la confidencialidad lo es de la seguridad: las tres piezas que dan título a este tema están en tres características distintas.

*Referencia: §1.3 [ISO25010]*
</details>

---

### Pregunta 7

**¿Qué distingue el objeto de la serie ISO 9241 del de la familia ISO/IEC 25000 (SQuaRE)?**

A) ISO 9241 regula la seguridad y SQuaRE la accesibilidad
B) Ambas miden lo mismo, pero SQuaRE es la versión europea
C) ISO 9241 es una norma de ergonomía centrada en el proceso y la interacción; SQuaRE mide la calidad del producto software

<details><summary>Respuesta</summary>

**Correcta: C) ISO 9241 es una norma de ergonomía centrada en el proceso y la interacción; SQuaRE mide la calidad del producto software** La usabilidad aparece en ambas familias, pero con perspectivas distintas: como resultado del contexto de uso en ISO 9241-11 y como característica medible del producto en ISO/IEC 25010.

*Referencia: §1.3 [ISO9241-11] [ISO25000]*
</details>

---

### Pregunta 8

**El diseño centrado en las personas de ISO 9241-210 exige que el proceso sea:**

A) Iterativo y con evaluación frente a los requisitos realizada con usuarios reales
B) Lineal, con una única evaluación de expertos al finalizar el desarrollo
C) Automatizado mediante herramientas de análisis de la interfaz

<details><summary>Respuesta</summary>

**Correcta: A) Iterativo y con evaluación frente a los requisitos realizada con usuarios reales** Sus cuatro actividades son comprender el contexto de uso, especificar requisitos, producir soluciones de diseño y evaluar frente a los requisitos, repitiendo el ciclo.

*Referencia: §1.1 [ISO9241-210]*
</details>

---

### Pregunta 9

**Un formulario municipal muestra un mensaje de error que dice únicamente «Error 0x8007». ¿Qué heurística de Nielsen se incumple de forma más evidente?**

A) Flexibilidad y eficiencia de uso
B) Ayuda a reconocer, diagnosticar y recuperarse de los errores
C) Diseño estético y minimalista

<details><summary>Respuesta</summary>

**Correcta: B) Ayuda a reconocer, diagnosticar y recuperarse de los errores** Los mensajes deben expresarse en lenguaje llano e indicar qué ha ocurrido y qué debe hacer la persona, no un código interno sin explicación.

*Referencia: §1.1 [NIELSEN]*
</details>

---

### Pregunta 10

**¿Qué método de evaluación de la usabilidad es una técnica de inspección que no requiere usuarios?**

A) La evaluación heurística
B) La prueba de usabilidad con pensamiento en voz alta
C) La prueba A/B en producción

<details><summary>Respuesta</summary>

**Correcta: A) La evaluación heurística** Es una inspección realizada por personas expertas contra un catálogo de heurísticas; las otras dos requieren usuarios reales interactuando con el sistema.

*Referencia: §1.1 [NIELSEN] [ISO9241-210]*
</details>

---

### Pregunta 11

**Los cuatro principios de WCAG (POUR) son:**

A) Perceptible, Operable, Compatible y Reutilizable
B) Portable, Ordenado, Comprensible y Rápido
C) Perceptible, Operable, Comprensible y Robusto

<details><summary>Respuesta</summary>

**Correcta: C) Perceptible, Operable, Comprensible y Robusto** De ellos cuelgan las 13 pautas y, de estas, los criterios de conformidad, que son lo único verificable y normativo.

*Referencia: §2.1 [WCAG22]*
</details>

---

### Pregunta 12

**Dentro de la estructura de WCAG 2.x, ¿qué elementos son normativos y verificables?**

A) Los principios y las pautas
B) Únicamente los criterios de conformidad
C) Las técnicas suficientes documentadas por el W3C

<details><summary>Respuesta</summary>

**Correcta: B) Únicamente los criterios de conformidad** Las pautas son objetivos generales y las técnicas son documentación informativa: se puede cumplir un criterio con una técnica no listada, siempre que sea comprobable.

*Referencia: §2.1 [WCAG22]*
</details>

---

### Pregunta 13

**¿Qué nivel de conformidad WCAG exige la normativa española para los sitios web del sector público?**

A) Nivel AA
B) Nivel A
C) Nivel AAA

<details><summary>Respuesta</summary>

**Correcta: A) Nivel AA** Lo impone el RD 1112/2018 por remisión a la norma UNE-EN 301 549. El propio W3C desaconseja exigir el nivel AAA para sitios completos porque no es alcanzable para todo tipo de contenido.

*Referencia: §2.1 [RD1112-2018] [WCAG22]*
</details>

---

### Pregunta 14

**¿Cuál de estas afirmaciones sobre WCAG 2.2 es correcta?**

A) Sustituye a WCAG 2.1, que queda derogada y sin validez
B) Es una norma ISO desde 2012 con el código ISO/IEC 40500
C) Es Recomendación del W3C desde octubre de 2023, añade nueve criterios y retira el criterio 4.1.1 «Análisis sintáctico»

<details><summary>Respuesta</summary>

**Correcta: C) Es Recomendación del W3C desde octubre de 2023, añade nueve criterios y retira el criterio 4.1.1 «Análisis sintáctico»** La norma ISO/IEC 40500:2012 corresponde a WCAG 2.0, no a la 2.2.

*Referencia: §2.1 [WCAG22] [WCAG20]*
</details>

---

### Pregunta 15

**El criterio 1.4.3 «Contraste (mínimo)», de nivel AA, exige una relación de contraste de:**

A) 3:1 para todo el texto
B) 4,5:1 para el texto normal y 3:1 para el texto grande
C) 7:1 para el texto normal y 4,5:1 para el texto grande

<details><summary>Respuesta</summary>

**Correcta: B) 4,5:1 para el texto normal y 3:1 para el texto grande** Los valores 7:1 y 4,5:1 corresponden al criterio 1.4.6 «Contraste (mejorado)», que es de nivel AAA.

*Referencia: §2.1 [WCAG22]*
</details>

---

### Pregunta 16

**Una aplicación municipal marca los campos obligatorios pintando su borde de rojo, sin ningún otro indicador. ¿Qué criterio WCAG incumple?**

A) 1.4.1 Uso del color
B) 2.1.1 Teclado
C) 4.1.2 Nombre, función, valor

<details><summary>Respuesta</summary>

**Correcta: A) 1.4.1 Uso del color** El color no puede ser el único medio visual para transmitir información: hace falta además un texto, un símbolo o una etiqueta.

*Referencia: §2.1 [WCAG22]*
</details>

---

### Pregunta 17

**El criterio 3.3.8 «Autenticación accesible (mínimo)», incorporado en WCAG 2.2:**

A) Obliga a implantar autenticación multifactor en todos los servicios públicos
B) Prohíbe exigir una prueba de función cognitiva sin ofrecer un método alternativo, y obliga a permitir pegar en los campos de contraseña
C) Exige que la contraseña tenga una longitud mínima de doce caracteres

<details><summary>Respuesta</summary>

**Correcta: B) Prohíbe exigir una prueba de función cognitiva sin ofrecer un método alternativo, y obliga a permitir pegar en los campos de contraseña** Recordar una contraseña, transcribir caracteres o resolver un rompecabezas son pruebas cognitivas que deben tener alternativa accesible.

*Referencia: §2.1 [WCAG22]*
</details>

---

### Pregunta 18

**Respecto a los requisitos de conformidad de WCAG, ¿cuál de las siguientes afirmaciones es correcta?**

A) La conformidad puede declararse de las partes accesibles de una página, excluyendo las demás
B) Basta con que sea conforme la primera pantalla de un proceso de varios pasos
C) La conformidad se predica de páginas completas y de procesos completos

<details><summary>Respuesta</summary>

**Correcta: C) La conformidad se predica de páginas completas y de procesos completos** Si un solo paso de la solicitud de cita no es conforme, no lo es todo el proceso.

*Referencia: §2.1 [WCAG22]*
</details>

---

### Pregunta 19

**¿Qué relación existe entre la norma EN 301 549 y las pautas WCAG?**

A) La EN 301 549 incorpora los criterios A y AA de WCAG en su capítulo sobre web y añade requisitos que WCAG no cubre
B) La EN 301 549 sustituye a WCAG en el ámbito europeo, que queda sin aplicación
C) Son normas independientes y sin relación: WCAG se aplica a la web y la EN 301 549 solo al hardware

<details><summary>Respuesta</summary>

**Correcta: A) La EN 301 549 incorpora los criterios A y AA de WCAG en su capítulo sobre web y añade requisitos que WCAG no cubre** Sus capítulos añaden hardware, comunicación bidireccional, documentos no web, software, documentación y servicios de apoyo, que quedan fuera del alcance de WCAG.

*Referencia: §2.2 [EN301549] [WCAG22]*
</details>

---

### Pregunta 20

**El Ayuntamiento licita la renovación de los tótems de autoservicio de sus oficinas de atención. ¿Qué exigencia de accesibilidad debe recoger el pliego?**

A) Únicamente la conformidad con WCAG 2.2 nivel AA
B) Ninguna, porque el hardware queda fuera de la normativa de accesibilidad
C) La conformidad con los capítulos aplicables de la EN 301 549, entre ellos el de hardware

<details><summary>Respuesta</summary>

**Correcta: C) La conformidad con los capítulos aplicables de la EN 301 549, entre ellos el de hardware** WCAG cubre el contenido web; para hardware, telefonía, documentos y software es la norma europea la que fija los requisitos, y es además la referencia de la contratación pública.

*Referencia: §2.2 [EN301549]*
</details>

---

### Pregunta 21

**Según el RD 1112/2018, la alegación de carga desproporcionada:**

A) Exime al organismo de publicar declaración de accesibilidad
B) Debe ser motivada, declararse expresamente y acompañarse de una alternativa accesible, y no puede fundarse en falta de prioridad, tiempo o conocimientos
C) Puede aplicarse de forma genérica a todo el sitio web sin justificación individualizada

<details><summary>Respuesta</summary>

**Correcta: B) Debe ser motivada, declararse expresamente y acompañarse de una alternativa accesible, y no puede fundarse en falta de prioridad, tiempo o conocimientos** La valoración atiende al tamaño, los recursos y la naturaleza del organismo frente al beneficio estimado para las personas con discapacidad.

*Referencia: §2.3 [RD1112-2018]*
</details>

---

### Pregunta 22

**La declaración de accesibilidad de un organismo público debe indicar el grado de cumplimiento mediante una de estas tres categorías:**

A) Plenamente conforme, parcialmente conforme o no conforme
B) Nivel A, nivel AA o nivel AAA
C) Conforme, en revisión o exento

<details><summary>Respuesta</summary>

**Correcta: A) Plenamente conforme, parcialmente conforme o no conforme** El modelo lo fija la Decisión de Ejecución (UE) 2018/1523, y la declaración debe recoger además el contenido no accesible, la fecha y el método de evaluación y el mecanismo de comunicación y reclamación.

*Referencia: §2.4 [DEC2018-1523] [RD1112-2018]*
</details>

---

### Pregunta 23

**Sobre las herramientas automáticas de evaluación de la accesibilidad, ¿qué afirmación es correcta?**

A) Detectan todos los criterios de conformidad, por lo que bastan para declarar la conformidad
B) No tienen valor alguno y no deben emplearse en una auditoría
C) Detectan solo una parte de los criterios, por lo que deben combinarse con revisión manual experta y con tecnologías de apoyo

<details><summary>Respuesta</summary>

**Correcta: C) Detectan solo una parte de los criterios, por lo que deben combinarse con revisión manual experta y con tecnologías de apoyo** Una herramienta detecta que falta el atributo `alt`, pero no que su contenido sea «imagen1.jpg»: una web puede superar el 100 % de las pruebas automáticas y ser inaccesible.

*Referencia: §2.4 [WCAG-EM] [OBSERVATORIO]*
</details>

---

### Pregunta 24

**Las cinco dimensiones de seguridad del Esquema Nacional de Seguridad son:**

A) Confidencialidad, integridad, disponibilidad, usabilidad y accesibilidad
B) Disponibilidad, integridad, confidencialidad, autenticidad y trazabilidad
C) Prevención, detección, respuesta, conservación y recuperación

<details><summary>Respuesta</summary>

**Correcta: B) Disponibilidad, integridad, confidencialidad, autenticidad y trazabilidad** Las tres primeras forman la triada clásica; autenticidad y trazabilidad son la aportación característica del esquema español.

*Referencia: §3.1 [ENS]*
</details>

---

### Pregunta 25

**El uso de cuentas genéricas compartidas por varias personas en un puesto de trabajo compromete principalmente:**

A) La trazabilidad, porque ninguna actuación resulta imputable a una persona concreta
B) La disponibilidad, porque el sistema se satura con accesos simultáneos
C) La integridad de las copias de seguridad

<details><summary>Respuesta</summary>

**Correcta: A) La trazabilidad, porque ninguna actuación resulta imputable a una persona concreta** Por eso el ENS exige cuentas nominativas y proscribe las genéricas salvo justificación excepcional.

*Referencia: §3.2.1 [ENS]*
</details>

---

### Pregunta 26

**La política de «puesto de trabajo despejado y pantalla limpia» es un control de naturaleza:**

A) Tecnológica, porque depende del software de cifrado instalado
B) De personas, porque consiste exclusivamente en formación
C) Física y organizativa, orientada a evitar la exposición no autorizada de información en el entorno del puesto

<details><summary>Respuesta</summary>

**Correcta: C) Física y organizativa, orientada a evitar la exposición no autorizada de información en el entorno del puesto** Se complementa con el bloqueo de sesión, los filtros de privacidad, la impresión segura y la destrucción segura de documentos.

*Referencia: §3.1.1 [ISO27002] [ENS]*
</details>

---

### Pregunta 27

**Antes de retirar del servicio un equipo que ha manejado datos personales, la medida correcta es:**

A) Formatear el disco, ya que el formateo elimina definitivamente la información
B) Aplicar un procedimiento de borrado seguro o de destrucción del soporte conforme a las categorías de saneamiento reconocidas
C) Borrar las carpetas del usuario y vaciar la papelera de reciclaje

<details><summary>Respuesta</summary>

**Correcta: B) Aplicar un procedimiento de borrado seguro o de destrucción del soporte conforme a las categorías de saneamiento reconocidas** Formatear no es borrar: la información sigue siendo recuperable, y en unidades de estado sólido el borrado exige órdenes específicas del dispositivo o el cifrado previo del soporte.

*Referencia: §3.1.1 [NIST-800-88]*
</details>

---

### Pregunta 28

**Respecto a la información que reside en el disco local del puesto de usuario, el criterio correcto es:**

A) El puesto no debe albergar información única: el dato de trabajo debe residir en el repositorio corporativo
B) Toda la información debe residir en el disco local para garantizar el trabajo sin conexión
C) Es indiferente dónde resida, siempre que el disco esté cifrado

<details><summary>Respuesta</summary>

**Correcta: A) El puesto no debe albergar información única: el dato de trabajo debe residir en el repositorio corporativo** Esta regla resuelve a la vez la disponibilidad, el control de acceso y el cumplimiento documental: el disco local es caché de trabajo, no archivo.

*Referencia: §3.1.2 [ENS]*
</details>

---

### Pregunta 29

**¿Qué mide el RPO (Recovery Point Objective)?**

A) El tiempo máximo que puede transcurrir hasta restablecer el servicio
B) El tiempo medio entre fallos de un componente
C) La cantidad máxima de información que se puede permitir perder, medida en tiempo hacia atrás desde el incidente

<details><summary>Respuesta</summary>

**Correcta: C) La cantidad máxima de información que se puede permitir perder, medida en tiempo hacia atrás desde el incidente** Determina la frecuencia de las copias; el tiempo de restablecimiento del servicio es el RTO, que mira hacia delante.

*Referencia: §3.1.2 [ENS]*
</details>

---

### Pregunta 30

**Un servicio con una disponibilidad comprometida del 99,9 % anual admite aproximadamente:**

A) 53 minutos de indisponibilidad al año
B) 8,8 horas de indisponibilidad al año
C) 3,65 días de indisponibilidad al año

<details><summary>Respuesta</summary>

**Correcta: B) 8,8 horas de indisponibilidad al año** El 99,99 % equivale a unos 53 minutos anuales y el 99 % a unos 3,65 días: cada nueve adicional divide aproximadamente por diez el tiempo admitido.

*Referencia: §3.1.2 [ENS]*
</details>

---

### Pregunta 31

**¿Cuál de estas combinaciones constituye autenticación multifactor en sentido estricto?**

A) Contraseña más código temporal generado por una aplicación en el móvil
B) Contraseña más pregunta de seguridad sobre datos personales
C) Contraseña más repetición de la contraseña en un segundo campo

<details><summary>Respuesta</summary>

**Correcta: A) Contraseña más código temporal generado por una aplicación en el móvil** La MFA exige dos factores de naturaleza distinta: aquí, algo que se sabe y algo que se tiene. La pregunta de seguridad es también conocimiento, por lo que no aporta un segundo factor.

*Referencia: §3.2.1 [NIST-800-63B]*
</details>

---

### Pregunta 32

**¿Qué característica hace que la autenticación con FIDO2/WebAuthn sea resistente al phishing?**

A) Que utiliza contraseñas de mayor longitud que las convencionales
B) Que envía el segundo factor por SMS a un número verificado
C) Que la credencial está ligada criptográficamente al dominio legítimo, por lo que no puede entregarse a un sitio suplantado

<details><summary>Respuesta</summary>

**Correcta: C) Que la credencial está ligada criptográficamente al dominio legítimo, por lo que no puede entregarse a un sitio suplantado** Ni siquiera un usuario engañado puede entregarla a un sitio fraudulento; el SMS, en cambio, se considera un canal restringido por su exposición a la interceptación y al intercambio fraudulento de tarjeta SIM.

*Referencia: §3.2.1 [WEBAUTHN] [NIST-800-63B]*
</details>

---

### Pregunta 33

**Respecto a la gestión de contraseñas, las guías actuales recomiendan:**

A) Forzar el cambio de contraseña cada 30 días para todos los usuarios
B) Favorecer la longitud sobre las reglas rígidas de complejidad y cambiar la contraseña cuando haya indicio de compromiso, no de forma periódica sistemática
C) Almacenar las contraseñas cifradas de forma reversible para poder recuperarlas si el usuario las olvida

<details><summary>Respuesta</summary>

**Correcta: B) Favorecer la longitud sobre las reglas rígidas de complejidad y cambiar la contraseña cuando haya indicio de compromiso, no de forma periódica sistemática** La caducidad periódica obligatoria degrada la calidad de las contraseñas; y en el servidor solo debe guardarse el resumen con una función diseñada para ello y sal única por usuario, nunca cifrado reversible.

*Referencia: §3.2.1 [NIST-800-63B] [OWASP-CHEAT]*
</details>

---

### Pregunta 34

**El modelo de autorización basado en roles (RBAC) resulta el más adecuado en la Administración porque:**

A) Asigna los permisos a roles y las personas a roles, lo que hace la autorización auditable y estable frente a la rotación de personal
B) Permite que cada empleado decida quién accede a los documentos que crea
C) Calcula la decisión de acceso en función de la hora y la ubicación de cada petición

<details><summary>Respuesta</summary>

**Correcta: A) Asigna los permisos a roles y las personas a roles, lo que hace la autorización auditable y estable frente a la rotación de personal** La opción de que decida el propietario del recurso describe el modelo discrecional (DAC) y la decisión por atributos y contexto describe el modelo ABAC.

*Referencia: §3.2.1 [ENS]*
</details>

---

### Pregunta 35

**El principio de mínimo privilegio aplicado al puesto de usuario implica, entre otras medidas, que:**

A) El usuario debe ser administrador local para poder resolver sus propias incidencias
B) Los permisos se conceden de forma permanente para evitar interrupciones del servicio
C) El usuario no es administrador local de su equipo y las tareas administrativas se realizan con cuentas separadas y nominativas

<details><summary>Respuesta</summary>

**Correcta: C) El usuario no es administrador local de su equipo y las tareas administrativas se realizan con cuentas separadas y nominativas** Es la medida que más eficazmente limita el alcance del código malicioso y la instalación de software no autorizado, y se completa con la revisión periódica y la retirada inmediata de permisos al cese.

*Referencia: §3.2.1 [SALTZER75] [ENS]*
</details>

---

### Pregunta 36

**El cifrado de disco completo de un portátil protege la información:**

A) En cualquier circunstancia, incluso frente a código malicioso que se ejecuta con la sesión iniciada
B) Cuando el equipo está apagado o el disco se extrae, pero no cuando la sesión está iniciada
C) Solo mientras el equipo permanece dentro de la red corporativa

<details><summary>Respuesta</summary>

**Correcta: B) Cuando el equipo está apagado o el disco se extrae, pero no cuando la sesión está iniciada** Con el sistema en marcha, los ficheros se entregan descifrados a cualquier proceso autorizado: el cifrado complementa, pero no sustituye, al control de acceso y al bloqueo de sesión.

*Referencia: §3.2.2 [NIST-800-111]*
</details>

---

### Pregunta 37

**¿Cuál es la diferencia esencial entre un virus y un gusano?**

A) El virus cifra la información y el gusano la borra
B) El virus afecta a servidores y el gusano a puestos de usuario
C) El virus se inserta en otro programa o fichero anfitrión, mientras que el gusano se propaga por sí mismo a través de la red

<details><summary>Respuesta</summary>

**Correcta: C) El virus se inserta en otro programa o fichero anfitrión, mientras que el gusano se propaga por sí mismo a través de la red** El cifrado de la información con exigencia de rescate caracteriza al ransomware, y el troyano se presenta como software legítimo sin replicarse.

*Referencia: §3.3.1 [ATTACK]*
</details>

---

### Pregunta 38

**Frente a un ransomware de tipo nuevo, todavía sin firma conocida, la defensa técnica más eficaz en el puesto es:**

A) El análisis de comportamiento en tiempo de ejecución, que detecta lo que el programa hace con independencia de su firma
B) La actualización diaria del catálogo de firmas del antivirus
C) El filtro de contenidos del navegador

<details><summary>Respuesta</summary>

**Correcta: A) El análisis de comportamiento en tiempo de ejecución, que detecta lo que el programa hace con independencia de su firma** La detección por firmas es ciega ante el código nuevo o polimórfico; y, en todo caso, lo único que garantiza la recuperación tras un cifrado consumado es la copia de seguridad aislada y verificada.

*Referencia: §3.3.1 [ATTACK] [ENS]*
</details>

---

### Pregunta 39

**Una copia de seguridad diferencial:**

A) Copia lo cambiado desde la última copia de cualquier tipo y se restaura con toda la cadena
B) Copia lo cambiado desde la última copia completa y se restaura con dos elementos: la completa y la última diferencial
C) Es equivalente a una instantánea del volumen

<details><summary>Respuesta</summary>

**Correcta: B) Copia lo cambiado desde la última copia completa y se restaura con dos elementos: la completa y la última diferencial** La que se mide desde la última copia de cualquier tipo y exige toda la cadena es la incremental; y la instantánea no es una copia de seguridad, porque depende del mismo almacenamiento.

*Referencia: §3.3.2 [ISO27002]*
</details>

---

### Pregunta 40

**La regla 3-2-1 de copias de seguridad, en su versión reforzada frente al ransomware, añade:**

A) Que las copias se realicen exclusivamente en horario nocturno
B) Que se conserven durante un mínimo de diez años
C) Al menos una copia inmutable o desconectada, y la verificación mediante pruebas de restauración

<details><summary>Respuesta</summary>

**Correcta: C) Al menos una copia inmutable o desconectada, y la verificación mediante pruebas de restauración** Un atacante con privilegios busca primero cifrar o borrar las copias; y una copia que nunca se ha restaurado no es una copia, sino una hipótesis.

*Referencia: §3.3.2 [ENS] [ISO27002]*
</details>

---

### Pregunta 41

**Un sistema de prevención de fuga de datos (DLP) se distingue de una copia de seguridad en que:**

A) La copia protege frente a la pérdida de la información y el DLP frente a su salida no autorizada
B) El DLP sustituye a la copia de seguridad en los puestos portátiles
C) La copia actúa sobre datos en tránsito y el DLP sobre datos en reposo exclusivamente

<details><summary>Respuesta</summary>

**Correcta: A) La copia protege frente a la pérdida de la información y el DLP frente a su salida no autorizada** El DLP clasifica la información, vigila los canales de salida (correo, web, extraíbles, impresión) y registra, avisa, cifra o bloquea la operación.

*Referencia: §3.3.2 [ISO27002]*
</details>

---

### Pregunta 42

**En el Esquema Nacional de Seguridad, la categoría de un sistema:**

A) Se calcula como la media de los niveles de sus cinco dimensiones
B) Es la correspondiente al nivel más alto alcanzado en cualquiera de sus dimensiones de seguridad
C) La fija libremente el responsable del sistema en función del presupuesto disponible

<details><summary>Respuesta</summary>

**Correcta: B) Es la correspondiente al nivel más alto alcanzado en cualquiera de sus dimensiones de seguridad** El nivel (bajo, medio o alto) se predica de cada dimensión y la categoría (básica, media o alta) del sistema: una sola dimensión valorada en nivel alto convierte todo el sistema en categoría alta.

*Referencia: §3.3.3 [ENS]*
</details>

---

### Pregunta 43

**¿Cuál de estos NO es un principio básico del Esquema Nacional de Seguridad?**

A) La gestión de la seguridad basada en los riesgos
B) La existencia de líneas de defensa
C) La certificación obligatoria de todos los productos por el fabricante

<details><summary>Respuesta</summary>

**Correcta: C) La certificación obligatoria de todos los productos por el fabricante** Los principios básicos son la seguridad como proceso integral, la gestión basada en riesgos, la prevención-detección-respuesta-conservación, la existencia de líneas de defensa, la vigilancia continua y reevaluación periódica y la diferenciación de responsabilidades.

*Referencia: §3.3.3 [ENS]*
</details>

---

### Pregunta 44

**El criterio de «desplazamiento a la izquierda» (shift left) en el ciclo de vida de desarrollo seguro significa que:**

A) La seguridad se introduce lo antes posible en el ciclo, porque el coste de corregir un defecto crece con la fase en que se detecta
B) Las pruebas de seguridad se concentran exclusivamente en la fase de verificación previa al despliegue
C) La responsabilidad de la seguridad se traslada al equipo de operaciones

<details><summary>Respuesta</summary>

**Correcta: A) La seguridad se introduce lo antes posible en el ciclo, porque el coste de corregir un defecto crece con la fase en que se detecta** Ello no significa «solo al principio»: la seguridad es actividad de todas las fases, incluidas el despliegue, la operación y la retirada.

*Referencia: §4.1.1 [NIST-SSDF] [MS-SDL]*
</details>

---

### Pregunta 45

**¿Qué diferencia a OWASP SAMM de BSIMM?**

A) SAMM se aplica a aplicaciones móviles y BSIMM a aplicaciones web
B) SAMM es un modelo prescriptivo de madurez y BSIMM es un modelo descriptivo construido observando programas reales
C) SAMM es una norma ISO certificable y BSIMM una recomendación del NIST

<details><summary>Respuesta</summary>

**Correcta: B) SAMM es un modelo prescriptivo de madurez y BSIMM es un modelo descriptivo construido observando programas reales** SAMM indica qué hacer y en qué orden madurar, con cinco funciones de negocio y tres niveles; BSIMM sirve para compararse con lo que hace el sector.

*Referencia: §4.1.1 [OWASP-SAMM] [BSIMM]*
</details>

---

### Pregunta 46

**Para redactar requisitos de seguridad verificables en el pliego de una aplicación municipal, la herramienta más adecuada de OWASP es:**

A) El Top 10, porque enumera los diez riesgos más críticos
B) SAMM, porque mide la madurez de la organización proveedora
C) ASVS, porque es un catálogo de requisitos verificables organizado en tres niveles

<details><summary>Respuesta</summary>

**Correcta: C) ASVS, porque es un catálogo de requisitos verificables organizado en tres niveles** El Top 10 es un documento de concienciación, no una norma de verificación; SAMM mide el proceso de la organización, no el producto entregado.

*Referencia: §4.1.1 [OWASP-ASVS] [OWASP-TOP10]*
</details>

---

### Pregunta 47

**En el modelo STRIDE, la elevación de privilegios (Elevation of privilege) niega la propiedad de:**

A) Autorización
B) Autenticidad
C) No repudio

<details><summary>Respuesta</summary>

**Correcta: A) Autorización** La autenticidad la niega la suplantación (Spoofing) y el no repudio lo niega el repudio (Repudiation); la manipulación niega la integridad, la revelación de información la confidencialidad y la denegación de servicio la disponibilidad.

*Referencia: §4.1.2 [SHOSTACK]*
</details>

---

### Pregunta 48

**El artículo 25 del RGPD impone al responsable del tratamiento:**

A) La obligación de cifrar todos los datos personales con AES-256
B) La protección de datos desde el diseño y por defecto, de modo que solo se traten los datos necesarios para cada finalidad sin intervención del usuario
C) La realización de una evaluación de impacto en todos los tratamientos, sin excepción

<details><summary>Respuesta</summary>

**Correcta: B) La protección de datos desde el diseño y por defecto, de modo que solo se traten los datos necesarios para cada finalidad sin intervención del usuario** La evaluación de impacto es una obligación del artículo 35, exigible cuando el tratamiento entrañe un alto riesgo; y el artículo 32 habla de medidas apropiadas al riesgo, sin imponer un algoritmo concreto.

*Referencia: §4.1.2 [RGPD]*
</details>

---

### Pregunta 49

**El principio de «diseño abierto» de Saltzer y Schroeder establece que:**

A) El código fuente de toda aplicación pública debe publicarse íntegramente
B) Cualquier persona puede modificar la configuración de seguridad del sistema
C) La seguridad no debe depender del secreto del diseño, sino del secreto de la clave

<details><summary>Respuesta</summary>

**Correcta: C) La seguridad no debe depender del secreto del diseño, sino del secreto de la clave** Es la formulación clásica del rechazo a la seguridad por oscuridad; ocultar la versión del servidor es una medida higiénica menor, no un control de seguridad.

*Referencia: §4.2.1 [SALTZER75]*
</details>

---

### Pregunta 50

**El principio de «mediación completa» aplicado a una aplicación web exige que:**

A) Cada acceso a cada objeto se verifique siempre, sin cachear la decisión de autorización tomada al iniciar sesión
B) Todas las peticiones pasen obligatoriamente por un cortafuegos de aplicación
C) La validación de datos se realice tanto en el cliente como en el servidor

<details><summary>Respuesta</summary>

**Correcta: A) Cada acceso a cada objeto se verifique siempre, sin cachear la decisión de autorización tomada al iniciar sesión** El cortafuegos de aplicación es una capa adicional, no la mediación; y la doble validación es una buena práctica distinta, en la que la del cliente cumple una función de usabilidad, no de seguridad.

*Referencia: §4.2.1 [SALTZER75]*
</details>

---

### Pregunta 51

**Respecto a la validación de entradas, la práctica correcta es:**

A) Validar únicamente en el cliente, para reducir la carga del servidor
B) Validar siempre en el servidor, preferir la lista blanca a la lista negra y canonicalizar antes de validar
C) Filtrar las comillas simples y la palabra «script» en todos los campos de entrada

<details><summary>Respuesta</summary>

**Correcta: B) Validar siempre en el servidor, preferir la lista blanca a la lista negra y canonicalizar antes de validar** El atacante no usa el formulario, envía la petición directamente; y las listas negras siempre quedan incompletas frente a codificaciones alternativas del mismo valor.

*Referencia: §4.2.2 [OWASP-CHEAT] [OWASP-PROACTIVE]*
</details>

---

### Pregunta 52

**La defensa correcta y suficiente frente a la inyección SQL es:**

A) Escapar las comillas simples de todos los parámetros recibidos
B) Restringir la longitud máxima de los campos de entrada del formulario
C) Emplear consultas parametrizadas (sentencias preparadas), de modo que los valores nunca se interpreten como código

<details><summary>Respuesta</summary>

**Correcta: C) Emplear consultas parametrizadas (sentencias preparadas), de modo que los valores nunca se interpreten como código** La consulta se compila con marcadores y los valores viajan aparte, sin poder alterar la estructura; el escapado manual es frágil y dependiente del motor.

*Referencia: §4.2.2 [OWASP-CHEAT] [OWASP-TOP10]*
</details>

---

### Pregunta 53

**Un ataque de XSS almacenado se caracteriza porque:**

A) La carga maliciosa se guarda en el servidor y afecta a todos los usuarios que visualizan el contenido
B) La carga viaja en la petición y se devuelve en la respuesta, por lo que requiere engañar a la víctima con un enlace
C) La carga nunca llega al servidor: el guion del cliente la toma de la URL o del almacenamiento local

<details><summary>Respuesta</summary>

**Correcta: A) La carga maliciosa se guarda en el servidor y afecta a todos los usuarios que visualizan el contenido** Las otras dos descripciones corresponden al XSS reflejado y al XSS basado en DOM respectivamente; el almacenado es el más grave por su alcance.

*Referencia: §4.2.2 [OWASP-TOP10] [OWASP-CHEAT]*
</details>

---

### Pregunta 54

**¿Qué relación hay entre OAuth 2.0 y OpenID Connect?**

A) Son dos nombres del mismo protocolo de autenticación
B) OAuth 2.0 es un marco de autorización delegada y OpenID Connect es la capa de autenticación construida sobre él, que añade el token de identidad
C) OpenID Connect es la versión anterior de OAuth 2.0, ya en desuso

<details><summary>Respuesta</summary>

**Correcta: B) OAuth 2.0 es un marco de autorización delegada y OpenID Connect es la capa de autenticación construida sobre él, que añade el token de identidad** Usar OAuth 2.0 «a secas» para autenticar usuarios es un error clásico de diseño.

*Referencia: §4.2.3.1 [RFC6749]*
</details>

---

### Pregunta 55

**Una aplicación permite consultar expedientes mediante la dirección `/expedientes/ver?id=48213`, y cambiar el número muestra el expediente de otra persona. Esta vulnerabilidad se clasifica como:**

A) Inyección SQL, categoría A03 del OWASP Top 10
B) Configuración de seguridad defectuosa, categoría A05
C) Pérdida de control de acceso con referencia directa a objeto insegura, categoría A01

<details><summary>Respuesta</summary>

**Correcta: C) Pérdida de control de acceso con referencia directa a objeto insegura, categoría A01** La corrección es comprobar en el servidor, en cada petición, que el expediente solicitado pertenece al usuario autenticado; usar identificadores no predecibles es una medida complementaria, nunca sustitutiva.

*Referencia: §4.2.3.1 [OWASP-TOP10]*
</details>

---

### Pregunta 56

**Regenerar el identificador de sesión en el momento de la autenticación es la defensa frente a:**

A) La fijación de sesión (session fixation)
B) La inyección de mandatos del sistema operativo
C) La falsificación de peticiones del lado del servidor (SSRF)

<details><summary>Respuesta</summary>

**Correcta: A) La fijación de sesión (session fixation)** En este ataque el adversario impone a la víctima un identificador de sesión que él ya conoce; si el identificador se regenera al autenticarse, el conocido deja de ser válido.

*Referencia: §4.2.3.2 [OWASP-ASVS]*
</details>

---

### Pregunta 57

**El atributo `HttpOnly` de una cookie de sesión sirve para:**

A) Forzar que la cookie viaje únicamente por HTTPS
B) Impedir que el código de guion del cliente pueda leerla, limitando el robo de sesión mediante XSS
C) Evitar que la cookie se envíe en peticiones de origen cruzado

<details><summary>Respuesta</summary>

**Correcta: B) Impedir que el código de guion del cliente pueda leerla, limitando el robo de sesión mediante XSS** Forzar HTTPS es la función del atributo `Secure` y evitar el envío en peticiones de origen cruzado es la del atributo `SameSite`, que mitiga el CSRF.

*Referencia: §4.2.3.2 [OWASP-CHEAT]*
</details>

---

### Pregunta 58

**Sobre el uso de JSON Web Tokens (JWT), ¿cuál de estas afirmaciones es correcta?**

A) Al ir firmados, su contenido queda cifrado y puede incluir datos personales sin riesgo
B) El servidor debe aceptar el algoritmo que indique la cabecera del propio token para garantizar la interoperabilidad
C) Un JWT es autocontenido y no revocable por sí mismo, por lo que exige vidas cortas y un mecanismo adicional de revocación

<details><summary>Respuesta</summary>

**Correcta: C) Un JWT es autocontenido y no revocable por sí mismo, por lo que exige vidas cortas y un mecanismo adicional de revocación** Además, el JWT va firmado pero no cifrado —su contenido es legible por quien lo posea— y el servidor debe fijar de antemano el algoritmo admitido y rechazar el algoritmo `none`.

*Referencia: §4.2.3.2 [RFC7519] [RFC8725]*
</details>

---

### Pregunta 59

**En el registro de auditoría de una aplicación, ¿qué información NO debe registrarse nunca?**

A) La identidad del usuario que realiza cada operación sobre datos sensibles
B) Las contraseñas, los identificadores de sesión y los tokens de acceso
C) Los intentos fallidos de autenticación y los fallos de autorización

<details><summary>Respuesta</summary>

**Correcta: B) Las contraseñas, los identificadores de sesión y los tokens de acceso** Tampoco deben registrarse claves criptográficas ni datos personales innecesarios: un registro indiscreto es una brecha de datos esperando ocurrir, y le son aplicables los principios de minimización y limitación del plazo de conservación.

*Referencia: §4.2.4 [OWASP-CHEAT] [RGPD]*
</details>

---

### Pregunta 60

**¿Cuál de estas afirmaciones sobre las técnicas de verificación de la seguridad del software es correcta?**

A) SAST analiza el código sin ejecutarlo, DAST ataca la aplicación en ejecución sin ver el código y SCA analiza las dependencias de terceros
B) DAST analiza el código fuente y SAST ataca la aplicación desplegada
C) Las herramientas automáticas detectan de forma fiable los fallos de lógica de negocio y de autorización

<details><summary>Respuesta</summary>

**Correcta: A) SAST analiza el código sin ejecutarlo, DAST ataca la aplicación en ejecución sin ver el código y SCA analiza las dependencias de terceros** Ninguna herramienta automática detecta los fallos de lógica de negocio ni de autorización: para eso hacen falta revisión manual de código y pruebas de penetración.

*Referencia: §4.3.2 [OWASP-ASVS] [OWASP-TOP10]*
</details>
