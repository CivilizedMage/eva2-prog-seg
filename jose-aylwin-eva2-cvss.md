
### 1.  Define vulnerabilidad, amenaza y riesgo en el contexto de la seguridad informática. ###

**Vulnerabilidad:** Es la debilidad o fallo en un sistema que ponga en riesgo los datos o información del mismo y otorgue la posibilidad de robar, cambiar o eliminar estos datos a un mal actor.

**Amenaza:** Son las acciones que utilizan una vulnerabilidad para dañar el sistema.

**Riesgo:** Es una forma de medir tanto la probabilidad de que un problema surga como el potencial daño que una amenaza o vulnerabilidad pueden tener en el sistema.

### 2.  ¿Qué es CVE y cuál es su propósito? ###

Es una lista con los nombres de vulnerabilidades cuyos nombres son estandarizados a nivel global para facilitar el intercambio de información y facilitar la búsqueda de vulnerabilidades.

### 3.  Menciona tres ventajas del uso de CVE. ###

1. Facilita la obtención de información de vulnerabilidades.
2. Ayuda a diferenciar distintas vulnerabilidades.
3. Consta de un constante soporte y actualizaciones.

### 4.  ¿Qué es CVSS y para qué se utiliza? ###

Es un sistema de medición cuyo objetivo es medir el daño que una vulnerabilidad puede generar en un sistema.

### 5.  Describe los tres grupos métricos del CVSS. ###

- Grupo Métrico Base: Representan vulnerabilidades que **no cambian** con el tiempo. Se verifican el vector de acceso (Local, LAN o Remoto), la complejidad del acceso (alto, medio o bajo) y la autenticación.
- Grupo Métrico Temporal: Representan vulnerabilidades que **pueden cambiar** con el tiempo. Se consideran 3 factores: explotabilidad, nivel de remediación y reporte de confianza.
- Grupo de Métrica de ambiente o entorno: Representan vulnerabilidades únicas dependiendo del entorno que tenga el usuario. Se definen la cantidad de usuarios afectados, se calcula el daño potencial, la distribución de los objetivos y los requisitos de confidencialidad, integirdad y disponibilidad.

### 6.  Explica el concepto de "componentes con vulnerabilidades conocidas" (OWASP A9:2017). ###

Son componentes los cuales si son explotados pueden generar pérdidas datos o de control y debilitar las defensas de un software.

### 7.  ¿Qué es la encriptación y cuál es su objetivo? ###

La encriptación es un proceso que vuelve ilegible cualquier documento por medio de un patrón con el fin de que pueda ser leído solo si se tiene esta misma.
Su finalidad es el ocultar información sensible a actores externos y que no utilicen la información.

### 8.  ¿Qué significan las siglas SOAP, WS y XML? ###

Son procesos de comunicación segura:

**SOAP:** Simple Object Access Protocol.

**WS:** Web Service o Web Services.

**XML:** Extensible Markup Language, estilizado como XML.

### 9.  ¿Qué es hardening y cómo se relaciona con la seguridad de sistemas? ###

Es una medida de seguridad cuyo objetivo es fortalecer la seguridad en un sistema para poder evitar posibles ataques, buscando reducir vulnerabilidades sin poner en riesgo al funcionamiento del sistema. 

### 10.  Describe tres acciones comunes de hardening. ###

1. Actualización constante de software: Al actualizar constantemente el software, estos proceden a bajar su vulnerabilidad.
2. Eliminar sofware innecesario: Sofware obsoleto o que ya no se utiliza pueden ser riesgosos el tenerlos al ser posibles vulnerabilidadaes que no generan ninguna utilidad.
3. Cerrar puertos: El cerrar puertos que no se utilicen permite el tener menos puntos de acceso para posibles ataques.

### 11.  ¿Qué es un CAPTCHA y cuál es su función? ###

Un CAPTCHA es una medida de seguridad que previene el acceso de bots a plataformas.

### 12.  ¿Qué se entiende por "autenticación robusta centralizada"? ###

Es un sistema de protección que se enfoca en la autenticación del usuario, utilizando una pertenencia del usuario, tal como una contraseña, firma o un token SMS, entre otras cosas.
