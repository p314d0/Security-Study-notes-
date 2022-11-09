# Security+ Notas de estudio

## Overview of Security

---

### Dominios (SYO-601)

- Ataques, amenazas y vulnerabilidades (24%)
- Arquitectura y diseño (21%)
- Implementacion (25%)
- Operaciones y respuesta al incidente (16%)
- Gobierno, riesgo y cumplimiento (14%)

### SEGURIDAD DE LA INFORMACION

---

Acto de protejer los datos e informacion contra el acceso no autorizado, la modificacion ilegal y la interrupcion, la divulgacion y la corrupcion y la destruccion.

### SEGURIDAD DE LOS SISTEMAS DE INFORMACION

---

Acto de proteger los sitemas que contengan y preocesan nuestros datos.

## Basicos y fundamentales

---

### LA TRIADA DE LA CIA

---

- **Confidencialidad**: Informacion no revelada a personas no autorizadas. Encryptacion = Confidencialidad
- **Integridad**: Garantizar que la informacion no ha sido modificada o alterada sin la debida autorizacion.
- **Disponibilidad**: Garantizar que la informacion se puede acceder, almacenar o proteger en todo momento.

### LAS TRIPLE AAA DE LA SEGURIDAD

---

- **Authentication**: Cuando se establece la identidad de una persona con pruebas y es confirmada por el sitema.

  5 METODOS DE AUTENTICACION

  - Algo que sabes : Contraseña, nombre de usuario.
  - Algo que eres : Huella dactilar, escaner ocular.
  - Algo que tienes: Token, licencia de conducir.
  - Algo que haces: Forma de hablar, firma.
  - Algun lugar: Factor de geolocalizacion basado en tu ubicacion, gps.

- **Authorization**: Cuando se da acceso a un usuario a determinados datos o zonas del edificio.

- **Accounting(Contabilidad)**: Seguimiento de los datos, el uso de los ordenadores y recursos de la red. NO-REPUDIO ocurre cuando tenes pruebas de que alguien cometio una accion.

### AMENAZAS DE SEGURIDAD

---

- **MALWARE** : Software malicioso
- **ACCESO NO AUTORIZADO**: Ocurre cuando se accede a los recursos e informacion sin el consentimiento del propietario.
- **FALLA DEL SITEMA**: Ocurre cuando una computadora es hackeada o una aplicacion individual falla.
- **INGENIERIA SOCIAL**: Acto de manipular usuarios para revelar informacion confidencial o realizar otra acciones subyacentes.

### MITIGAR AMENAZAS

---

- Controles fisicos: Alarmas, cerraduras, camaras de seguridad, tarjetas de identificacion y guradias de seguridad.
- Controles tecnicos: Tarjetas inteligentes, encriptacion, listas de acceso de control, deteccion de intrusos y autenticacion de red.
- Controles administrativos: Policias, procedimientos, entrenamiento en seguridad, plan de contingencia y planes para recuperacion en caso de desastres. La capacitación del usuario es el control de seguridad más rentable para usar

### HACKERS

---

Hay 5 tipos de hackers

- White Hats: Hackers no maliciosos que rompen la seguridad de una compania a pedido de la misma.
- Black Hats: Hackers maliciosos que rompen los sitemas de computacion y redes sin autorizacion o permisos.
- Gray Hats : Hackers sin ninguna afiliacion a una compania que atenta contra la seguridad de una compania arriesgandose a cargos penales por hacerlo.
- Blue Hats: Hackers que atentan contra la seguridad de una compania con el permiso de la misma pero no son empleados de ella.
- Elite: Hackers que buscan y explotan vulnerabilidades antes que nadie. Son 1 en 10.000

### ACTORES DE AMENAZAS

---

- Script Kiddies : Hackers con cero a poco conocimiento que solo usan herramientas que otros han echo.
- Hacktivistas : Hackers impulsados por un cambio social, agendas politicas o terrorismo.
- Crimen organizado: Hackers que son parte de un grupo criminal.
- Advanced persistent threat (Amenaza persitente avanzada): Grupos de piratas informáticos altamente capacitados y financiados (a menudo por estados nacionales) con
  inteligencia encubierta y de código abierto a su disposición

### INTELIGENCIA DE AMENAZAS Y FUENTES

---

- **Puntualidad**: Propiedad de una fuente de inteligencia que garantiza su actualización
- **Pertinencia**: Propiedad de una fuente de inteligencia que garantiza que se ajusta a los casos de uso previstos para ella
- **Exactitud**: Propiedad de una fuente de inteligencia que garantiza que produce resultados efectivos
- **Niveles de confianza** : Propiedad de una fuente de inteligencia que garantiza que produce declaraciones cualificadas sobre la fiabilidad
- **Propiedad** : La inteligencia sobre amenazas está muy extendida como oferta de servicio comercial donde el acceso a las actualizaciones e investigaciones está sujeto a una cuota de suscripción
- **Fuente cerrada** : Los datos se derivan de los esfuerzos de investigación y análisis del propio proveedor, como los datos de las redes neuronales que opera, además de la información extraída de los sistemas de sus clientes, convenientemente anonimizada.
- **De código abierto** : Datos disponibles para su uso sin necesidad de suscripción, que pueden incluir fuentes de amenazas similares a las de los proveedores comerciales y pueden contener listas de reputación y bases de datos de firmas de malware similares a los proveedores comerciales y pueden contener listas de reputación y bases de datos de firmas de malware: US-CERT,NCSC del Reino Unido, AT&T Security (OTX)
  , MISP, VirusTotal, Spamhaus, SANS ISC Dominios sospechosos

- Inteligencia de fuente abierta (OSINT): Métodos para obtener información sobre una persona u organización a través de
  registros públicos, sitios web y redes sociales

### CAZA DE AMENAZAS

- Caza de amenazas: Una técnica de ciberseguridad diseñada para detectar la presencia de amenazas que no han sido
  descubiertas por una supervisión de seguridad normal. La caza de amenazas es potencialmente menos perturbadora que las pruebas de penetración
- Establecimiento de una hipótesis: Una hipótesis se deriva de la modelización de la amenaza y se basa en posibles
  eventos con mayor probabilidad e impacto.
- Perfilar los actores y actividades de la amenaza: Implica la creación de un escenario que muestra cómo un posible atacante podría intentar una intrusión y cuáles podrían ser sus objetivos
- La caza de amenazas se basa en el uso de las herramientas desarrolladas para la supervisión periódica de la seguridad y la respuesta a incidentes
  - Analizar el tráfico de la red
  - Analizar la lista de procesos ejecutables
  - Analizar otros hosts infectados
  - Identificar cómo se ejecutó el proceso malicioso
- La caza de amenazas consume muchos recursos y tiempo para llevarla a cabo, pero puede reportar muchos beneficios
  - Mejora la capacidad de detección o integra la inteligencia
  - Reduce la superficie de ataque
  - Bloquear los vectores de ataque
  - Identificar los activos críticos

### MARCOS DE ATAQUE

---

- Kill Chain (Cadena de muerte):
  Un modelo desarrollado por Lockheed Martin que describe las etapas por las que un un actor de la amenaza progresa en una intrusión en la red

  - Reconocimiento : El atacante determina qué métodos utilizar para completar las fases del ataque
  - Armamento : El atacante acopla el código de carga útil que permitirá el acceso con el código de explotación que utilizará una vulnerabilidad para ejecutarse en el sistema objetivo
  - Entrega : El atacante identifica un vector para transmitir el código armado al entorno objetivo.
  - Explotacion: El código convertido en arma se ejecuta en el sistema objetivo mediante este mecanismo
  - Instalación : Este mecanismo permite que el código armado ejecute una herramienta de acceso remoto y logre la persistencia en el sistema objetivo.
  - Command & Control(C2): El código convertido en arma establece un canal de salida hacia un servidor remoto que puede utilizarse para controlar la herramienta de acceso remoto y, posiblemente, descargar herramientas adicionales para progresar en el ataque
  - Acciones sobre los objetivos:El atacante suele utilizar el acceso que ha conseguido para, de forma encubierta recoger información de los sistemas objetivo y transferirla a un sistema remoto (exfiltración de datos) o lograr otros objetivos y motivos. El análisis de la cadena de muerte puede utilizarse para identificar una matriz de acciones defensivas para contrarrestar el progreso de un ataque en cada etapa.

- MITRE ATT&CK Framework:
  - Una base de conocimientos mantenida por la Corporación MITRE para enumerar y explicar tácticas, técnicas y conocimientos o procedimientos comunes del adversario (attack.mitre.org)
  - La matriz de tácticas pre-ATT&CK se alinea con las fases de reconocimiento y armamento de la cadena de muerte
- Modelo Diamante de Análisis de Intrusión:
  - Un marco para analizar los incidentes de ciberseguridad y las intrusiones explorando las relaciones entre cuatro características principales: adversario, capacidad, infraestructura y víctima
