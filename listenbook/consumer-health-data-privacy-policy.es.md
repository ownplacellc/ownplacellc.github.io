# Talefall — Audiobook Player: Política de privacidad de datos de salud del consumidor

**Fecha de entrada en vigor: 10 de octubre de 2026**

Esta es una traducción.

OWN PLACE LLC, 7707 NE 141st St, Kirkland, WA 98034-5321, EE. UU.
(contact@ownplace.net; teléfono +1 (213) 524-8012), desarrolladora de Talefall —
Audiobook Player (la «App»; identificador de paquete com.anisimov.audiobooks) y
operadora de las funciones de servidor que acompañan a la Suscripción a Talefall (el
«Servicio»): **Libro a partir de una idea** y **narración de su propio texto con la
voz de Talefall**.

Esta es nuestra **Política de privacidad de datos de salud del consumidor** conforme a la Ley My
Health My Data de Washington (Capítulo 19.373 RCW), la SB 370 de Nevada (NRS 603A.400 y
siguientes), la Ley de Privacidad de Datos de Connecticut y leyes similares. Forma parte de nuestra
[Política de privacidad](privacy-policy.es.html); en lo relativo a los datos de salud del consumidor, esta página
prevalece si ambas difieren. Está enlazada desde la página de inicio de ownplace.net.

## A1. Por qué existe esta política

El Servicio no es un servicio de salud y no solicitamos información de
salud. **Nuestra regla es que las ideas de libro y los textos enviados para narración no
deben contener datos personales sobre personas reales, incluido usted**, y en
particular ninguna información de salud. Usted lo confirma antes de cada pedido de libro. Para narrar el libro resultante, la App reutiliza esa confirmación; para otro libro que no la tenga, la App solicita una confirmación independiente antes de su primera narración con la voz de Talefall. Nuestro servidor aplica los filtros descritos en A5.

Aun así, el Servicio acepta texto libre. Si alguien escribe, en contra de la regla,
información que identifica a una persona y revela su salud física o mental pasada, presente o
futura —por ejemplo, un diagnóstico, un medicamento, un embarazo, salud reproductiva o sexual, atención de afirmación de género o una afección de salud
mental—, ese texto puede ser **dato de salud del consumidor**. No deja
de serlo por haber sido presentado como ficción. Esta política
explica qué ocurre con él. Se aplica a todas las personas, dondequiera que vivan.

## A2. Categorías que podemos recopilar y fuentes

Recopilamos datos de salud del consumidor solo si se incluyen en el texto enviado al
Servicio o en un mensaje que se nos envía.

| Categoría | Cómo podría surgir | Fuente | Vinculado a |
|---|---|---|---|
| Información de salud en una **idea de libro** | Escrita en la idea, en contra de la regla | La persona que hace el pedido | El pedido y el identificador de transacción original de Apple de la suscripción |
| Información de salud en un **texto enviado para narración** | Contenida en un libro en formato de texto que usted eligió narrar con la voz de Talefall | La persona que hace el pedido | Lo mismo |
| Información de salud en un **capítulo generado** | Escrita por el modelo de IA al producir el libro | Generada a partir del pedido | Lo mismo |
| Información de salud en una **denuncia de contenido o correo electrónico** | Escrita en una denuncia, un mensaje de soporte o una solicitud | La persona que denuncia o envía el mensaje, que puede escribir sobre otra persona | La denuncia o su dirección de correo electrónico |

No recopilamos datos de salud de otras apps ni dispositivos (incluido
HealthKit), no recopilamos ubicación precisa, no usamos geovallas y no
inferimos el estado de salud de nadie a partir de solicitudes, compras, idioma ni de nada
más.

## A3. Finalidades

No ofrecemos ningún servicio que trate datos de salud del consumidor y no
pedimos a nadie que los facilite. Si están presentes a pesar de la regla, pueden
tratarse automáticamente antes de que nadie lo advierta: por las revisiones de A5 y, si
estas no los detectan, por los pasos que escriben, moderan, narran y entregan el
libro solicitado. **Ni la confirmación de un usuario ni el hecho de que una solicitud
haya pasado nuestros filtros autoriza ese tratamiento.** Invocamos una excepción de «servicio
solicitado» solo cuando la ley aplicable lo permite y el
tratamiento es necesario y proporcionado para un servicio solicitado por la
persona a quien se refieren los datos, y nunca porque alguien haya enviado los datos de
otra persona. Cuando sabemos que un pedido contiene datos de salud del consumidor, detenemos el
pedido y todo tratamiento posterior, eliminamos las copias que controlamos (salvo que la
ley nos obligue a preservarlas), restituimos las horas y notificamos a cada proveedor de IA
que pueda haberlos recibido —Amazon Web Services y OpenRouter— que los elimine, indicando
las fechas y los identificadores que aún conservamos. Lo hacemos también tras la entrega.

Aparte de ese tratamiento residual y no intencionado, usamos los datos de salud del consumidor
solo:

1. para ejecutar las revisiones automáticas que rechazan las solicitudes que contienen datos personales
   o sensibles, y para moderar los capítulos generados (A5);
2. para responder a una denuncia, un mensaje de soporte o una solicitud de derechos; y
3. para cumplir una obligación legal.

No los usamos para publicidad, marketing, elaboración de perfiles, investigación, entrenamiento de modelos
ni ningún otro fin, y no los vendemos.

## A4. Quién los recibe

No tenemos entidades afiliadas. El contenido que pudiera contener datos de salud del consumidor, si
alguien lo incluye en contra de nuestra regla, puede llegar a los destinatarios siguientes, que
lo tratan para prestar el Servicio con los fines de A3; además, Amazon Web Services puede
conservar el contenido que marquen sus clasificadores de abuso para su detección automática
de abusos (A6). Consideramos a un destinatario
encargado del tratamiento de datos de salud del consumidor —de modo que la divulgación a él no sea
«compartir» conforme a la ley de Washington— solo en la medida en que un contrato vinculante
con él cubra ese tratamiento. **No nos basamos en ningún contrato con los proveedores de IA
como cobertura de los datos sensibles (véase «Límites contractuales» más abajo), por lo que no
hacemos tal afirmación respecto de Amazon Web Services, OpenRouter ni los proveedores de
alojamiento a los que OpenRouter enruta;** para ellos, nuestra protección es la prevención (A5)
y la eliminación al descubrirlo (A3).

Los libros se escriben por una de dos vías. **Vía principal:** el modelo GPT-6 Luna,
desarrollado por OpenAI, que Amazon Web Services ejecuta en Amazon Bedrock en regiones de
AWS en Estados Unidos. **Vía de respaldo:** el modelo GLM-5.3, desarrollado por Z.ai,
utilizado a través de OpenRouter con el identificador `z-ai/glm-5.3`, con las solicitudes
limitadas a los proveedores de alojamiento enumerados en la Política de privacidad; se usa
cuando la vía principal no está disponible o falla en un pedido, y para los pedidos hechos
con un permiso de una versión anterior. Un mismo libro puede escribirse en parte por cada
vía.

| Destinatario | Función | Qué recibe |
|---|---|---|
| **Modal Labs, Inc.** (modal.com), Estados Unidos | Alojamiento; ejecuta nuestro servicio, nuestro modelo narrador y nuestro modelo de moderación; mantiene almacenamiento de trabajo temporal | El pedido completo: idea o texto de narración, capítulos generados, audio |
| **Amazon Web Services, Inc. (Amazon Bedrock)** (aws.amazon.com) — vía principal para escribir libros | Ejecuta el modelo GPT-6 Luna que escribe el texto, en regiones de AWS en Estados Unidos. De forma predeterminada no almacena el contenido, pero conserva hasta 30 días el tráfico marcado por sus clasificadores de abuso para la detección automática de abusos | La idea y el texto de trabajo que produce nuestro programa escritor, sin ningún identificador añadido por nosotros |
| **OpenRouter, Inc.** (openrouter.ai) — vía de respaldo para escribir libros | Transmite las solicitudes de escritura de libros a los proveedores de alojamiento del modelo | La idea y el texto de trabajo que produce nuestro programa escritor, sin ningún identificador añadido por nosotros |
| **Proveedores de alojamiento del modelo GLM** (vía de respaldo), a los que se llega a través de OpenRouter: Baseten, Crusoe, Decart, DeepInfra, Fireworks AI, Inference.net, Modal, Morph, Novita AI, Parasail, Phala, Sail Research, Together AI, Venice y Wafer | Ejecutan el modelo que escribe el texto; OpenRouter los indica con sede en Estados Unidos y con conservación cero de datos | El mismo contenido |
| **Apple Inc.** (iCloud Mail) | Entrega y almacena el correo enviado a contact@ownplace.net | Lo que usted nos escribe y su dirección de correo electrónico |

La narración y la moderación se ejecutan en nuestros propios modelos en Modal; ese texto no se
envía a Amazon Web Services, a OpenRouter ni a sus proveedores. En la vía de respaldo no se
garantiza que el procesamiento ocurra solo en Estados Unidos. Ni OpenAI, el desarrollador
de GPT-6 Luna, ni Z.ai, el desarrollador de GLM, reciben pedidos.

**Límites contractuales.** Nuestro anexo de procesamiento de datos con OpenRouter es el
estándar, que excluye los datos sensibles. Amazon Web Services trata el contenido
conforme a su Anexo de Procesamiento de Datos de AWS estándar, incorporado a los
Términos de servicio de AWS; no nos basamos en él para autorizar el tratamiento de datos
sensibles. Por eso prohibimos enviar datos de salud y otros datos sensibles y los
filtramos antes de que nada llegue a un proveedor de IA (A5). No afirmamos tener protección contractual para datos sensibles
que no tenemos.

**Sin divulgaciones publicitarias y sin venta.** No divulgamos intencionalmente datos de salud del consumidor
a nadie, no los entregamos a anunciantes ni a corredores de datos y
no los vendemos. Pueden producirse divulgaciones incidentales a través de los destinatarios y el tratamiento descritos arriba; por ejemplo, si alguien incluye datos de salud del consumidor en una
idea de libro en contra de nuestra regla y nuestros filtros no lo detectan, se transmiten
al proveedor de IA de la vía utilizada —Amazon Web Services, u OpenRouter y sus proveedores
de alojamiento— para escribir el libro. Como no nos basamos en un contrato con estos
proveedores que cubra los datos sensibles, tal transmisión puede considerarse
«compartir» conforme a la ley de Washington. Nuestra regla y nuestros filtros no crean una
excepción a las leyes sobre datos de salud del consumidor, y el permiso del proveedor de IA
no autoriza el tratamiento de datos de salud del consumidor. Trabajamos para prevenir esas
transmisiones (A5); cualquier recopilación o divulgación no intencionada se gestiona conforme
a la ley aplicable, lo que incluye detener el tratamiento posterior, eliminar los datos y
notificar a los destinatarios (A3).
Cualquier intercambio previsto requeriría el consentimiento independiente que exige la
ley, y una venta requeriría la autorización independiente y firmada que exige la
ley. También podemos divulgar datos cuando la ley lo exija (por
ejemplo, una orden judicial válida).

## A5. Prevención: la regla, los filtros y ninguna opción de consentimiento

- **La regla.** Ningún dato personal sobre personas reales, incluido usted, en una idea de libro
  ni en un texto de narración. Los relatos deben ser ficción; los textos explicativos y las guías prácticas
  pueden abordar temas generales, no a un particular.
- **Confirmaciones.** Antes de cada pedido de libro: el interruptor *«Mi idea no contiene
  datos personales de personas reales»*, que cubre el texto exacto. Para un libro creado a partir de su idea, la App reutiliza la confirmación dada al realizar ese pedido para narrar el libro resultante; no le pide que confirme de nuevo. Para otro libro que no tenga esa confirmación, antes de su primera narración con la voz de Talefall usted confirma: «Este texto no contiene datos de una persona real». Con la voz de Apple en el dispositivo, el texto nunca sale de su dispositivo.
- **Filtro de entrada en nuestro servidor para ideas de libro** (antes de enviar nada a un
  proveedor de IA; en inglés, ruso y español): rechaza una idea que contenga,
  entre otros patrones, declaraciones sobre la salud, la orientación sexual, la identidad de género o los antecedentes penales del solicitante o de una persona cercana identificada, así como
  datos de contacto y números de identificación. Una solicitud rechazada no
  se envía, no usa horas y la App pide una reescritura. Nuestro registro anota
  solo la categoría del rechazo, no el texto. El texto enviado para narración no
  se analiza en busca de datos personales; se le aplican la confirmación por libro y la regla,
  y va únicamente a nuestro propio modelo narrador.
- **Moderación de salida.** Cada capítulo generado es revisado por nuestro propio
  modelo de moderación en Modal en busca de datos personales sobre personas reales y otro contenido
  prohibido antes de la narración y la entrega; un capítulo que no pasa no se
  entrega y el pedido se detiene.
- **Los filtros son imperfectos.** No reconocen todos los casos, y la
  regla se aplica a todo lo que se les escape.
- **Ninguna opción de consentimiento.** No pedimos consentimiento para tratar datos de salud del consumidor,
  y ningún toque en la App se trata como tal consentimiento. El permiso del proveedor de IA
  solo autoriza adónde va el contenido de los pedidos de libros. Si datos de salud del consumidor
  llegan a nosotros a pesar de la regla, los tratamos solo como se describe en A3 y
  los eliminamos como se describe en A6; cuando sabemos que un pedido los contiene, los
  eliminamos y podemos rechazar pedidos posteriores.

## A6. Cuánto tiempo se conservan

| Qué | Cuánto tiempo |
|---|---|
| Contenido del pedido (idea o texto de narración, capítulos generados, audio) | Almacenamiento de trabajo temporal cifrado en Modal, eliminado en cuanto la App confirma que ha guardado todos los capítulos; si la entrega no se confirma, el pedido caduca 7 días después de ser aceptado y se elimina en la siguiente limpieza programada, normalmente en 15 minutos (una limpieza fallida se reintenta). Se elimina antes cuando sabemos que contiene datos de salud del consumidor |
| Una solicitud rechazada | No se almacena; solo se registra la categoría del rechazo |
| Recibo del pedido | Se conserva 7 años después del último hecho financiero relacionado; contiene una huella SHA-256 del texto de la idea, nunca el texto |
| Denuncias de contenido (pueden incluir un pasaje) | 12 meses |
| Materiales conservados conforme a 18 U.S.C. § 2258A | 1 año desde el envío, o más tiempo cuando la ley lo exija |
| Correo electrónico | Hasta 24 meses después del último mensaje; se elimina antes si se solicita |
| Copias que conservan los proveedores de servicios | Modal puede conservar las entradas y salidas de las funciones hasta 7 días; Amazon Web Services no conserva contenido de forma predeterminada, pero conserva hasta 30 días el contenido marcado por sus clasificadores de abuso (al que no tenemos acceso directo) y puede conservar metadatos limitados; OpenRouter y los proveedores de alojamiento no conservan contenido con el enrutamiento de conservación cero de datos, pero pueden conservar metadatos limitados; las copias de seguridad que mantenga un encargado del tratamiento se eliminan a más tardar 6 meses después de una solicitud autenticada de Washington |

Conservamos datos de salud del consumidor más allá de un plazo de eliminación aplicable solo
cuando lo exija una obligación legal específica o una excepción legal.

## A7. Sus derechos

Dondequiera que viva, usted puede:

- **Confirmar y acceder** a si conservamos sus datos de salud del consumidor, obtener una copia
  de lo que aún existe y obtener una lista de cada destinatario que los recibió
  —encargados del tratamiento, contratistas y cualquier otro tercero, incluidos los destinatarios
  de transmisiones incidentales como Amazon Web Services, OpenRouter y los proveedores de
  alojamiento de OpenRouter—
  con sus datos de contacto (A4). No tenemos entidades afiliadas;
- **Eliminar** sus datos de salud del consumidor. Notificamos a cada destinatario que
  los recibió —encargados del tratamiento, contratistas y otros terceros— que los elimine,
  usando los identificadores que aún conservamos;
- **Retirar** el permiso del proveedor de IA en Ajustes, lo que detiene los nuevos pedidos
  de libros, y **pedirnos que dejemos de recopilar** sus datos de salud del consumidor, lo que
  tratamos como una solicitud de eliminación más un bloqueo de todo tratamiento posterior para su
  suscripción si usted lo pide;
- **Rectificar** los datos inexactos que aún conservemos;
- **Apelar** una denegación (A8); y
- **No ser discriminado** por ejercer estos derechos.

Las personas que no usan Talefall pero creen que otra persona envió sus datos tienen los mismos derechos. Como el contenido del pedido se elimina tras
la entrega, en la mayoría de los casos no queda contenido que facilitar ni eliminar.

## A8. Cómo presentar una solicitud, verificación y plazos

- **Escriba** a contact@ownplace.net con el asunto «Talefall: consumer health
  data request», o **llame** al +1 (213) 524-8012. Incluya el identificador de transacción
  original de su suscripción si lo tiene; el botón «Solicitar eliminación de datos» en Ajustes de la App prepara un correo con él. Las personas sin suscripción deben facilitar
  información que nos ayude a encontrar los datos.
- **Verificación.** Usamos una verificación comercialmente razonable y proporcionada
  (por ejemplo, un recibo de Apple de la suscripción). El
  identificador por sí solo no es prueba de legitimación. Los agentes autorizados pueden actuar con
  su permiso por escrito.
- **Plazos.** Respondemos dentro de los **45 días** siguientes a la recepción de la solicitud, prorrogables
  una vez hasta 45 días más cuando sea razonablemente necesario, con aviso y el
  motivo dentro del primer plazo. Cuando se aplique la ley de Nevada, eliminamos los datos
  cubiertos en un plazo de 30 días después de la autenticación y notificamos a los destinatarios.
- **Apelaciones.** Si denegamos una solicitud, responda dentro de 45 días; contestamos por
  escrito dentro de 45 días, explicamos nuestra decisión y le decimos cómo contactar
  al Fiscal General de Washington (www.atg.wa.gov) o al Fiscal General de su estado.

## A9. Evaluación

Como las solicitudes de texto libre podrían contener datos sensibles, mantenemos una
evaluación de protección de datos del Servicio, incluida la evaluación que exige la
Ley de Privacidad de Datos de Connecticut para el tratamiento de datos sensibles. Antes
de habilitar una nueva vía de IA o cambiar sustancialmente su tratamiento, actualizamos la
evaluación y resolvemos las conclusiones que exijan cambios en nuestro tratamiento o en
nuestras salvaguardas.

## A10. Cambios

Actualizaremos la fecha de entrada en vigor y publicaremos aquí la nueva versión. Nuestro Servicio
actual no ofrece una opción de consentimiento para datos sensibles; cualquier cambio que
permita tal tratamiento requerirá divulgaciones actualizadas, el consentimiento que exige la ley
y contratos adecuados con los encargados del tratamiento antes de que entre en vigor.

## A11. Contacto

OWN PLACE LLC, 7707 NE 141st St, Kirkland, WA 98034-5321, EE. UU.
Correo electrónico: contact@ownplace.net · Teléfono: +1 (213) 524-8012
