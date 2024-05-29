A1. Caso de estudio.
Un estudio de caso que involucra las operaciones de una empresa ficticia, las operaciones
locales de una gran empresa petrolera global. Dispone de una gran infraestructura
informática utilizada por numerosas áreas de negocio. Su red incluye una variedad de
servidores que ejecutan una variedad de aplicaciones de software típicas de organizaciones
de su tamaño. También utiliza aplicaciones que son mucho menos comunes, algunas de las
cuales se relacionan directamente con la salud y seguridad de quienes trabajan en la
petrolera.
Las características de su infraestructura son:
● Tienen conectados entre sí mediante una intranet distintos servidores para brindar
mejores capacidades de gestión, por lo son potencialmente accesibles desde
Internet.
● Varios directores de ingeniería destacaron la importancia que tiene para la empresa
la fiabilidad de la red Supervisory Control and Data Acquisition (supervisión, control y
adquisición de datos) y de los nodos. Cualquier fallo en los registros de SCADA
expondría a la empresa a multas y sanciones legales.
● Varios responsables de TI indicaron que una gran cantidad de datos críticos estaban
almacenados en varios servidores de archivos, ya sea en modo de archivos
individuales o en bases de datos.
○ Algunos de estos datos fueron generados automáticamente por aplicaciones
○ Otros por empleados utilizando una aplicación de oficina común.
○ Otros son de producción y resultados operativos, contratos y licitaciones,
personal, respaldos de aplicaciones, gastos operativos y de capital, estudios
y planificación de petrolio y perforación exploratoria.

● Otro grupo de responsables de TI identifican otros tres sistemas clave (los
servidores de Finanzas, Adquisiciones y Mantenimiento/Producción) fundamentales
para el funcionamiento eficaz de las áreas comerciales principales. Cualquier

compromiso en la disponibilidad o integridad de estos sistemas afectaría la
capacidad de la empresa para realizar operaciones de manera efectiva.
● Finalmente identificó el correo electrónico como otro activo clave, tras entrevistas
con todas las áreas de negocio de la compañía se determina lo siguiente:
○ El uso del correo electrónico como herramienta empresarial abarca todos los
ámbitos empresariales.
○ Alrededor del 60% de toda la correspondencia se realiza en forma de correo
electrónico, que se utiliza para comunicarse diariamente con la oficina
central, otras unidades de negocio, proveedores y contratistas, así como para
realizar una gran cantidad de correspondencia interna.
○ Al correo electrónico se le da mayor importancia de lo habitual debido a la
ubicación remota de la empresa.











B1. Seguridad física.
A partir de la naturaleza de la empresa analizada, asesore a la empresa resolviendo las
siguientes cuestiones que le plantea
1. De entre las siguientes incidencias en los centros de datos de sus bases petrolíferas
humos, gases tóxicos, calor o llamas. ¿Que causaría más muertes si sucediera un
incendio?.

    La presencia de humos y gases tóxicos en un centro de datos puede ser más 
    peligrosa que el calor o las llamas. Los humos y gases tóxicos pueden propagarse
    rápidamente por el centro de datos, lo que puede dificultar la evacuación de las
    personas y aumentar el riesgo de asfixia y envenenamiento. Además, los humos y
    gases tóxicos pueden dañar los equipos y sistemas de TI, lo que puede resultar en
    pérdidas financieras significativas para la empresa.



1. Se ha planificado desplegar infraestructura en una nueva explotación petrolífera.
Implementar controles de seguridad física. Identifique una lista de cuatro pasos a
realizar antes de instalar cables en las instalaciones de un centro.

    Antes de instalar cables en las instalaciones de un centro, es importante realizar los
    siguientes pasos:
    1. Realizar una evaluación de riesgos para identificar las amenazas y vulnerabilidades
    2. Diseñar un plan de seguridad física que incluya la ubicación de los cables y los puntos de acceso a la red 
    3. Implementar controles de seguridad física, como cámaras de vigilancia y sistemas de control de acceso
    4. Realizar pruebas de seguridad para garantizar que los cables se instalen de manera segura y protegida.
    5. Capacitar al personal en las medidas de seguridad física y en el manejo de los cables de red.
    6. Mantener un registro de los cables instalados y de las medidas de seguridad implementadas.
    7. Realizar auditorías periódicas para garantizar el cumplimiento de las políticas de seguridad física.
    8. Actualizar los controles de seguridad física según sea necesario para hacer frente a nuevas amenazas y vulnerabilidades.


1. De los archivadores resistentes al fuego, sistemas anti incendios, alarmas
antiincendios, o mobiliarios en general. Identifique con qué elementos debería llevar
más cuidado la empresa analizada debido a que se genere una situación conflictiva
en un centro de datos o rack.
Responda con un máximo de 3 a 4 líneas en Arial de tamaño 11.

    La empresa debería prestar especial atención a los sistemas anti incendios y a las alarmas
    antiincendios en un centro de datos o rack. Estos elementos son fundamentales para
    detectar y extinguir incendios de manera rápida y eficaz, lo que puede ayudar a evitar
    daños graves en los equipos y sistemas de TI, así como a proteger la vida de las personas
    que trabajan en el centro de datos. Además, los sistemas anti incendios y las alarmas
    antiincendios pueden ayudar a minimizar el tiempo de inactividad y las pérdidas financieras
    asociadas a un incendio en un centro de datos o rack.
















B2. Gestión de la Seguridad.
Con la descripción realizas la lista de activos del apartado A1 Caso de estudio, identifique
en una tabla una lista de aspectos y riesgos que sobre lo activos, especificando:
● Activo.
● Amenaza/Vulnerabilidad.
● Controles recomendados.
● Probabilidad.
● Consecuencia.
● Nivel de riesgo.
● Prioridad de riesgo.
Apóyese en las diapositivas 27-30 de la sesión del día 10 Gestión de la Seguridad y
Evaluación de Riesgos.
Entregue una tabla de formato

| Activo                                 | Amenaza/Vulnerabilidad           | Controles recomendados                                                                                 | Probabilidad | Consecuencia                | Nivel de riesgo | Prioridad de riesgo |
| -------------------------------------- | -------------------------------- | ------------------------------------------------------------------------------------------------------ | ------------ | --------------------------- | --------------- | ------------------- |
| Web Server                             | Ataque de denegación de servicio | Implementar un firewall y un sistema de detección de intrusiones                                       | Alta         | Interrupción del servicio   | Alto            | Alta                |
| Base de datos                          | Fuga de información              | Encriptar la información y establecer políticas de acceso                                              | Media        | Pérdida de confidencialidad | Medio           | Medio               |
| Correo electrónico                     | Phishing                         | Capacitar a los empleados en la identificación de correos      electrónicos fraudulentos               | Alta         | Robo de credenciales        | Alto            | Alta                |
| Servidores de archivos                 | Acceso no autorizado             | Implementar autenticación multifactor y control de acceso                                              | Media        | Pérdida de datos sensibles  | Medio           | Medio               |
| SCADA                                  | Ataque de malware                | Actualizar regularmente el software y realizar análisis de                            vulnerabilidades | Alta         | Interrupción de operaciones | Alto            | Alta                |
| Servidores de Finanzas                 | Fuga de información              | Encriptar la información y establecer políticas de acceso                                              | Media        | Pérdida de confidencialidad | Medio           | Medio               |
| Servidores de Adquisiciones            | Acceso no autorizado             | Implementar autenticación multifactor y control de acceso                                              | Media        | Pérdida de datos sensibles  | Medio           | Medio               |
| Servidores de Mantenimiento/Producción | Interrupción del servicio        | Realizar copias de seguridad y establecer planes de contingencia                                       | Media        | Pérdida de productividad    | Medio           | Medio               |





B3. Selección de controles asociados a la evaluación.
A partir de la información proporcionada es evidente que varios de los posibles controles del
NIST 800-53 deben ser seleccionados. Haga una selección de aquellos prestando especial
atención a los controles relacionados con:
● El mantenimiento regular y sistemático de los sistemas operativos.
● El software de aplicaciones en los sistemas de servidor y cliente.
y concretamente con los aspectos que incluyen:
● Política y procedimientos de gestión de configuración.
● Configuración básica.
● Política y procedimientos de mantenimiento del sistema.
● Mantenimiento periódico.
● Corrección de fallos.
● Protección de código malicioso.
● Protección contra spam y software espía.
Identifiquelos en una tabla con la siguiente lista de aspectos
● Riesgo (activo/amenaza)
● Nivel de Riesgo
● Controles recomendados
● Prioridad
● Control Seleccionado
Apóyese en la diapositiva 15 de la sesión del día 10 Controles, planes y procedimientos de
seguridad.

| Riesgo (activo/amenaza)                     | Nivel de Riesgo | Controles recomendados                                                              | Prioridad | Control Seleccionado |
| ------------------------------------------- | --------------- | ----------------------------------------------------------------------------------- | --------- | -------------------- |
| SCADA vulnerabilidades                      | Alto            | Actualizar regularmente el software y realizar análisis de vulnerabilidades         | Alta      | CM-2                 |
| Servidores de Finanzas                      | Medio           | Encriptar la información y establecer políticas de acceso                           | Medio     | CM-6                 |
| Servidores de                               | Medio           | Implementar autenticación multifactor y control de acceso                           | Medio     | CM-7                 |
| Servidores de                               | Medio           | Realizar copias de seguridad y establecer planes de     contingencia                | Medio     | CM-8                 |
| Web Server                                  | Alto            | Implementar un firewall y un sistema de detección de intrusiones                    | Alta      | CM-8                 |
| Correo electrónico                          | Alta            | Capacitar a los empleados en la identificación de correos electrónicos fraudulentos | Alta      | CM-8                 |
| Servidores de archivos                      | Medio           | Implementar autenticación multifactor y control de acceso                           | Medio     | CM-8                 |
| Servidores de      Mantenimiento/Producción | Medio           | Realizar copias de seguridad y establecer planes de contingencia                    | Medio     | CM-8                 |




| Riesgo (activo/amenaza)                     | Nivel de Riesgo | Controles recomendados                                                              | Prioridad | Control Seleccionado |
| ------------------------------------------- | --------------- | ----------------------------------------------------------------------------------- | --------- | -------------------- |
| SCADA vulnerabilidades                      | Alto            | Actualizar regularmente el software y realizar análisis de vulnerabilidades         | Alta      | CM-2                 |
| Web Server/Denegación de servicio           | Alto            | Implementar firewall y sistema de detección de intrusiones                          | Alta      | SI-4                 |
| Base de datos/Fuga de información           | Medio           | Encriptar la información y establecer políticas de acceso                           | Media     | SC-13                |
| Correo electrónico/Phishing                 | Alto            | Capacitar a los empleados en la identificación de correos electrónicos fraudulentos | Alta      | AT-2                 |
| Servidores de archivos/Acceso no autorizado | Medio           | Implementar autenticación multifactor y control de acceso                           | Media     | AC-2                 |

























| Activo                 | Amenaza/Vulnerabilidad           | Controles recomendados                                                              | Probabilidad | Consecuencia                | Nivel de riesgo | Prioridad de riesgo |
| ---------------------- | -------------------------------- | ----------------------------------------------------------------------------------- | ------------ | --------------------------- | --------------- | ------------------- |
| Web Server             | Ataque de denegación de servicio | Implementar un firewall y un sistema de detección de intrusiones                    | Alta         | Interrupción del servicio   | Alto            | Alta                |
| Base de datos          | Fuga de información              | Encriptar la información y establecer políticas de acceso                           | Media        | Pérdida de confidencialidad | Medio           | Medio               |
| Correo electrónico     | Phishing                         | Capacitar a los empleados en la identificación de correos electrónicos fraudulentos | Alta         | Robo de credenciales        | Alto            | Alta                |
| Servidores de archivos | Acceso no autorizado             | Implementar autenticación multifactor                                               |







C. Arquitectura de seguridad
C1. Evaluación y diseño de componentes de seguridad en los sistemas
de información.
Entregue una solución en un esquema para evitar violaciones de seguridad
1. La solución debe contemplar al menos:
a. Una o más zonas desmilitarizadas.
b. Los cortafuegos que considere.
c. Pasarelas de correo electrónico y/o servidores proxy.
1. Identifique claramente en el esquema que elementos dan
a. Aislamiento lógico.
b. Cuales considera que elimina o reduce notablemente el riesgo.
1. Existen teletrabajadores y puntos remotos desde lo que se accede con un cliente
VPN. En qué medida encriptar la comunicación para estos elementos, puede ser
considerada un control de seguridad para cumplir con los objetivos de construir y
mantener segura la red de este cliente.
Los alumnos que los deseen hacer en diapositivas de presentación, tienen a su disposición
los iconos del archivo AB3 Iconos-C1


## Esquema
![Esquema]()





C2. Diseñe un plan de entrenamiento Ingeniería Social.
Utilizando Metasploit, cree un modelo de ataque de Ingeniería Social basado en phishing
que generé un ataque del lado del cliente. Establezca en el modelo todos los aspectos que
permita concienciar a la organización del peligro de abrir archivos sin identificar, de
remitentes desconocidos.
Responda con la lista de secuencia de opciones seleccionada y el modelo final del texto y
asunto del correo.

1. Inicie Metasploit y seleccione el módulo de phishing de ingeniería social.
2. Configure el módulo con el texto y el asunto del correo electrónico.
3. Seleccione el archivo adjunto malicioso y configure el servidor de phishing.
4. Envíe el correo electrónico a los empleados de la organización y realice un seguimiento de las respuestas.
5. Analice los resultados del ataque de phishing y conciencie a los empleados sobre los riesgos de abrir archivos de remitentes desconocidos.
6. Implemente controles de seguridad, como filtros de correo electrónico y capacitación en concienciación sobre seguridad, para mitigar el riesgo de ataques de phishing en el futuro.
7. Realice pruebas de penetración regulares para identificar y corregir posibles vulnerabilidades en la red y los sistemas de información.
8. Establezca políticas de seguridad claras y procedimientos de respuesta a incidentes para abordar posibles amenazas y vulnerabilidades en la organización.
9. Capacite al personal en las mejores prácticas de seguridad y en la identificación de posibles amenazas en la red y los sistemas de información.
10. Realice auditorías de seguridad regulares para garantizar el cumplimiento de las políticas de seguridad y la protección de los activos críticos de la organización.










C3. Documentación y detalles del diseño de los componentes de
seguridad.
Identifique una lista de advertencias y/o detalles que permita a la organización, de forma
comprensiva y adecuada, reexaminar cualquier aspecto que considere importante. Agrupe
las advertencias en siguientes bloques funcionales:
● En los puntos de acceso a la red.
● En las puertas de enlace, máquinas de saltos y los puntos de salida en el exterior.
● En los hosts y resto de nodos red.
● En el resto de elementos físicos y lógicos de la red y/o el edificio.
Responda con un máximo de 4 o 5 líneas en Arial de tamaño 11 por cada punto.

Advertencias en los puntos de acceso a la red:

## Advertencias en las puertas de enlace, máquinas de salto y los puntos de salida en el exterior:
1. Asegúrese de que las puertas de enlace y las máquinas de salto estén protegidas con contraseñas seguras y actualizadas.
2. Implemente controles de acceso basados en roles para restringir el acceso a los puntos de salida en el exterior.
3. Realice pruebas de penetración regulares para identificar y corregir posibles vulnerabilidades en los puntos de acceso a la red.
4. Establezca políticas de seguridad claras y procedimientos de respuesta a incidentes para abordar posibles amenazas y vulnerabilidades en los puntos de acceso a la red.
5. Capacite al personal en las mejores prácticas de seguridad y en la identificación de posibles amenazas en los puntos de acceso a la red.


## Advertencias en los puntos de acceso a la red:
1. Asegurarse de que los puntos de acceso a la red estén protegidos con contraseñas
2. Implementar controles de acceso basados en roles para restringir el acceso a los
3. puntos de acceso a la red.
4. Realizar pruebas de penetración regulares para identificar posibles vulnerabilidades en los puntos de acceso a la red.

## Advertencias en los hosts y resto de nodos red:
1. Mantener actualizados los sistemas operativos y las aplicaciones para protegerse contra vulnerabilidades conocidas y ataques de malware.
3. Implementar controles de acceso basados en roles y privilegios para limitar el acceso a los recursos y datos sensibles.
5. Realizar copias de seguridad periódicas de los datos críticos y almacenarlas en un lugar seguro y protegido.
7. Capacitar al personal en las mejores prácticas de seguridad y concienciar sobre los riesgos de seguridad asociados con el uso de la red y los sistemas de información.
9. Implementar controles de seguridad física, como cámaras de vigilancia y sistemas de control de acceso, para proteger los equipos y sistemas de TI contra robos y daños.

## Advertencias en el resto de elementos físicos y lógicos de la red y/o el edificio:
1. Realizar auditorías de seguridad regulares para identificar y corregir posibles vulnerabilidades en los elementos físicos y lógicos de la red y del edificio.
2. Implementar controles de seguridad física, como alarmas antiincendios y sistemas de control de acceso, para proteger los activos críticos y garantizar la continuidad del negocio.
3. Establecer políticas de seguridad claras y procedimientos de respuesta a incidentes para abordar posibles amenazas y vulnerabilidades en los elementos físicos y lógicos de la red y del edificio.
4. Capacitar al personal en las mejores prácticas de seguridad y en la identificación de posibles amenazas en los elementos físicos y lógicos de la red y del edificio.






D2. Ensayo NIST 800-53. Controles y mitigaciones de seguridad
recomendados.

Marco tecnologico: CM Configuration Management
El texto que entrega debe abordar los siguientes puntos:
● Una breve introducción a los aspectos psicológicos o de comportamiento utilizados
para eludir el marco tecnológico.
● Identificar patrones de comportamiento en artículos, noticias, etc. relacionados con
el comportamiento humano en otras áreas o disciplinas.
● Signos o señales que pueden ayudarnos a identificar cómo mitigar este patrón y
como se puede aplicar en el contexto de la ciberseguridad


## Texto
### Introducción
El marco tecnológico de Configuration Management (CM) es un conjunto de actividades que se realizan para garantizar que los elementos de configuración de un sistema se gestionen de manera eficiente y efectiva. El CM es esencial para garantizar que los sistemas de información sean seguros y estén protegidos contra amenazas y vulnerabilidades. Sin embargo, el CM también puede ser utilizado por los atacantes para eludir las medidas de seguridad y comprometer la integridad y confidencialidad de los sistemas de información.

### Patrones de comportamiento
Los atacantes pueden utilizar el CM para eludir las medidas de seguridad mediante la manipulación de los elementos de configuración de un sistema. Por ejemplo, un atacante puede modificar la configuración de un sistema para permitir el acceso no autorizado o para ocultar su presencia en el sistema. Los atacantes también pueden utilizar el CM para introducir vulnerabilidades en un sistema o para deshabilitar las medidas de seguridad existentes.

### Mitigación del patrón de comportamiento
Para mitigar el uso malintencionado del CM, es importante implementar controles de seguridad sólidos y seguir las mejores prácticas de gestión de la configuración. Algunas medidas que se pueden tomar para mitigar este patrón de comportamiento incluyen:






La presentación que realice debe abordar los siguientes puntos
● Describir y presentar brevemente el texto que entrega.
● Casos prácticos de lo que nos enseña. Como por ejemplo:
    ○ Dónde y qué tipo de tecnología nos puede ayudar a mitigar.
    ○ Cómo se puede aplicar en el contexto de la ciberseguridad.
● Basándose en el estándar NIST 800-53, lista de verificación de configuraciones y
especificaciones de seguridad recomendadas que puede implementar con fines de
cumplimiento de la recomendación.


## Presentación
### Introducción
En este ensayo, se abordará el marco tecnológico de Configuration Management (CM) y cómo puede ser utilizado por los atacantes para eludir las medidas de seguridad. Se presentarán patrones de comportamiento relacionados con el uso malintencionado del CM y se discutirán las medidas de mitigación que se pueden tomar para proteger los sistemas de información contra este tipo de amenazas.

### Casos prácticos
Un caso práctico de cómo se puede aplicar la mitigación del uso malintencionado del CM en el contexto de la ciberseguridad es mediante la implementación de controles de seguridad sólidos y la adopción de las mejores prácticas de gestión de la configuración. Por ejemplo, se pueden establecer políticas y procedimientos claros para la gestión de la configuración de los sistemas de información, incluyendo la identificación y autenticación de los elementos de configuración, la documentación de los cambios realizados y la realización de auditorías regulares para garantizar el cumplimiento de las políticas y procedimientos establecidos.

### Lista de verificación de configuraciones
Basándose en el estándar NIST 800-53, se pueden implementar las siguientes especificaciones de seguridad recomendadas para mitigar el uso malintencionado del CM:
1. CM-1: Configuration Management Policy and Procedures
2. CM-2: Baseline Configuration
3. CM-3: Configuration Change Control
4. CM-4: Security Impact Analysis
5. CM-5: Access Restrictions for Change
6. CM-6: Configuration Settings

Estas especificaciones de seguridad ayudarán a garantizar que los sistemas de información sean gestionados de manera segura y protegidos contra amenazas y vulnerabilidades relacionadas con el CM.

