El estudiante debe diseñar un modelo de libreta de direcciones usando técnicas de
OOP, con un menú de texto que sirva como interfaz y que permita las operaciones de
buscar por nombre, apellido o número de teléfono un contacto, e incluya datos
Nombre, Apellido, Teléfono, Dirección, Empleo. Debe permitir Consultar contacto vía
Búsqueda, Crear nuevo contacto, Borrar un contacto, Modificar un Contacto. Sólo una
agenda debe poder existir al mismo tiempo al ejecutar el programa.
Pasos a seguir:
Identificar los requisitos de la aplicación: La primera tarea es identificar las clases que
van a ser necesarias para ejecutar la lógica de nuestra agenda. Y razonar de forma
breve pero relevante, por qué se considera que es posible y práctico el enfoque
elegido.
Establecer un plan de lifecycle: Explicar brevemente qué modelo de desarrrollo de
software (waterfall, espiral, agile...) proponemos usar para una aplicación de este tipo.
Establecer un plan para gestionar de acuerdo a dicho plan los bugs, la gestión de
crecimiento del programa, cómo se segmentaría en módulos el desarrollo para poder
avanzar de forma iterativa, etc.
Diseñar el documento funcional: Debe incluir el pseudocódigo, flujos de datos,
requisitos, modelos de desarrollo e información general.
Implementar la aplicación: Esto incluye poner en Python, una distribución en módulos
que contengan las clases por tipo, y usar los import que precise cada módulo dentro de
su propio módulo, así como establecer test unitarios mínimos que verifiquen, usando
assert la lógica de la aplicación.
Documentar la aplicación: Para ello se requiere el uso de comentarios en el propio
código, con especial cuidado de que sólo haya comentarios cuando sean necesarios y
crear un archivo readme en el mismo directorio que nuestros módulos y programa
principal que explique de forma breve cómo funciona la aplicación, especialmente en
términos de estado de los objetos y comportamiento de los mismos.


## Requisitos de la aplicación
### Requisitos Funcionales
1. **Crear Contacto**:
   - Permitir al usuario introducir nombre, apellido, teléfono, dirección y empleo para crear un nuevo contacto y agregarlo a la agenda.

2. **Buscar Contacto**:
   - Permitir al usuario buscar un contacto por nombre.
   - Permitir al usuario buscar un contacto por apellido.
   - Permitir al usuario buscar un contacto por número de teléfono.

3. **Modificar Contacto**:
   - Permitir al usuario seleccionar un contacto existente y actualizar sus datos (nombre, apellido, teléfono, dirección, empleo).

4. **Borrar Contacto**:
   - Permitir al usuario eliminar un contacto existente de la agenda.

5. **Consultar Contacto**:
   - Mostrar detalles de un contacto específico después de realizar una búsqueda exitosa.

6. **Unicidad de Agenda**:
   - Asegurar que solo una instancia de la agenda de direcciones sea accesible durante la ejecución del programa.

7. **Interfaz de Menú de Texto**:
   - Proveer una interfaz basada en texto que permita al usuario navegar y seleccionar operaciones de buscar, crear, modificar, borrar y consultar contactos.

### Requisitos No Funcionales:

1. **Eficiencia**:
   - Las operaciones de búsqueda, creación, modificación y eliminación deben ser rápidas y eficientes, optimizando el tiempo de la interacción del usuario con la interfaz.

2. **Usabilidad**:
   - La interfaz de menú de texto debe ser intuitiva y fácil de usar, con instrucciones claras para ayudar al usuario a navegar por las diferentes opciones sin dificultades.

3. **Persistencia de Datos**:
   - Los contactos deben ser almacenados de manera que puedan ser recuperados después de cerrar y reabrir el programa, como mediante un archivo de texto o una base de datos simple.

4. **Escalabilidad**:
   - El diseño debe permitir la fácil adición de nuevas funcionalidades o campos adicionales sin necesidad de rehacer la estructura del programa.

5. **Manejabilidad**:
   - El código debe estar bien documentado y organizado de manera que sea fácil de mantener y entender por otros desarrolladores.

6. **Confiabilidad**:
   - El sistema debe manejar adecuadamente errores como entradas inválidas o intentos de borrar contactos no existentes sin quebrar la funcionalidad general del programa.

7. **Portabilidad**:
   - El programa debe ser ejecutable en diferentes sistemas operativos (Windows, MacOS, Linux) sin necesidad de modificaciones significativas.

8. **Seguridad**:
   - Los datos de los contactos deben ser tratados con cuidado para evitar pérdidas o corrupción de datos, y si es necesario, implementar mecanismos de backup o recuperación.

9. **Rendimiento**:
   - El programa debe manejar eficientemente una cantidad razonable de contactos sin degradarse en rendimiento.

10. **Compatibilidad**:
    - Si se utiliza alguna biblioteca externa, debe ser compatible con el entorno de desarrollo y ejecución del programa.


## Enfoque Elegido

Para una aplicación de libreta de direcciones, podemos considerar varios modelos de desarrollo de software, cada uno con sus propias ventajas y desventajas. Sin embargo, un modelo que suele ser particularmente eficaz para este tipo de aplicaciones es el **modelo Agile**.

## ¿Por Qué Agile?

1. **Iteraciones Rápidas**:
   - La libreta de direcciones puede beneficiarse de iteraciones rápidas y frecuentes. Esto permite que se realicen mejoras y ajustes basados en el feedback del usuario de manera continua.

2. **Flexibilidad**:
   - Agile es muy flexible y permite cambios frecuentes en los requisitos. Esto es útil si se descubren nuevas necesidades o funcionalidades que no se habían considerado inicialmente.

3. **Enfoque en el Usuario**:
   - Agile pone un fuerte énfasis en la satisfacción del usuario y en el desarrollo de funcionalidades que proporcionen valor al usuario lo más pronto posible.

4. **Feedback Continuo**:
   - Al tener reuniones de revisión y retrospectiva con regularidad, es posible obtener feedback continuo y asegurarse de que el producto se ajusta a las expectativas del cliente.

5. **Descomposición de Tareas**:
   - El modelo Agile permite descomponer el proyecto en pequeñas unidades de trabajo manejables, lo que facilita el seguimiento del progreso y la identificación de problemas rápidamente.

### Plan de Lifecycle Usando Agile

1. **Planificación y Reunión de Requisitos**:
   - Identificar las historias de usuario y definir los requisitos funcionales y no funcionales de la aplicación.
   - Priorización de historias de usuario en un backlog.

2. **Sprint Planning**:
   - Seleccionar las historias de usuario de mayor prioridad para incluir en el próximo sprint.
   - Estimación del esfuerzo requerido para cada tarea.

3. **Desarrollo en Sprints**:
   - Realizar el trabajo de desarrollo en ciclos cortos, típicamente de 2-4 semanas.
   - Al final de cada sprint, tener una versión incremental del producto que pueda ser revisada.

4. **Revisión del Sprint**:
   - Demostrar la funcionalidad desarrollada durante el sprint a los interesados para obtener feedback inmediato.
   - Ajustar el backlog de acuerdo a las nuevas prioridades y feedback recibido.

5. **Retrospectiva del Sprint**:
   - Evaluar lo que ha funcionado bien y lo que puede mejorarse.
   - Implementar mejoras en el siguiente sprint.

6. **Release**:
   - Después de varios sprints, hacer una versión oficial de la aplicación para el cliente o los usuarios finales.
   - Continuar con el ciclo de sprints para futuras mejoras y mantenimiento.

### Ventajas del Modelo Agile para Esta Aplicación

- **Coste y Tiempo Reducidos**: Las iteraciones cortas permiten que los problemas se detecten temprano, evitando esfuerzos costosos de corrección más adelante.
- **Alta Calidad**: El enfoque en pruebas continuas y feedback asegura que la calidad del software se mantenga alta.
- **Satisfacción del Cliente**: El cliente está involucrado en cada etapa del proceso, lo que mejora la alineación del producto final con las expectativas del cliente.

En resumen, el modelo Agile es adecuado para la aplicación de la libreta de direcciones porque permite una respuesta rápida a los cambios y el feedback del usuario, mantiene un enfoque constante en la entrega de valor, y facilita el mantenimiento y mejora continua del producto.




## Gestión de Bugs

### Recolección de Bugs**:
   - **Herramienta de Seguimiento de Bugs**: Utilizar una herramienta como JIRA, Trello o GitHub Issues para documentar y seguir el estado de los bugs.
   - **Reporte de Bugs**: Desarrollar un formato estandarizado para reportar bugs que incluya detalles como: descripción del bug, pasos para reproducirlo, entorno de ejecución, severidad y prioridad.

### Prioritización de Bugs**:
   - **Categorías de Severidad**:
     - **Críticos**: Bugs que causan fallos críticos o bloquean funcionalidades clave. Deben ser resueltos inmediatamente.
     - **Altos**: Bugs que afectan funcionalidades importantes pero no bloquean todo el sistema. Resolver en el sprint actual.
     - **Medios**: Bugs que afectan la experiencia del usuario pero no son críticos. Resolver en los sprints subsiguientes.
     - **Bajos**: Bugs menores o de bajo impacto. Resolver cuando el tiempo lo permita.

### Ciclo de Vida del Bug**:
   - **Detección**: Reporte inicial del bug.
   - **Asignación**: Asignar el bug al desarrollador adecuado.
   - **Resolución**: Desarrollo y prueba de la solución.
   - **Verificación**: Confirmar que el bug ha sido resuelto por el equipo de pruebas.
   - **Cierre**: Cerrado el bug si la verificación es exitosa.
   - **Reapertura**: Reapertura si el bug persiste o se reportan problemas recurrentes.





### Pasos Para Crear el Documento Funcional

1. **Establecer el Propósito del Documento**:
   - Definir el objetivo del documento y a quién está dirigido.
   
2. **Recolección de Requisitos**:
   - Recopilar todos los requisitos funcionales y no funcionales.

3. **Identificación de Módulos**:
   - Determinar los módulos principales y submódulos necesarios para la aplicación.

4. **Diseño de Flujos de Datos**:
   - Crear diagramas de flujo de datos para ilustrar cómo la información se mueve y se procesa dentro del sistema.

5. **Especificación del Pseudocódigo**:
   - Escribir el pseudocódigo para los componentes clave del sistema.

6. **Descripción del Modelo de Desarrollo**:
   - Explicar el modelo de desarrollo elegido y cómo se aplicará al proyecto.

7. **Preparación de la Información General**:
   - Incluir detalles generales sobre el sistema, como las herramientas utilizadas, el entorno de desarrollo y los recursos necesarios.

### Índice del Documento Funcional

1. **Introducción**
   - Propósito del Documento
   - Audiencia Objetivo

2. **Información General**
   - Descripción del Sistema
   - Entorno de Desarrollo
   - Recursos Necesarios
   - Consideraciones y Supuestos

3. **Requisitos del Sistema**
   - **Requisitos Funcionales**
     - Crear Contacto
     - Buscar Contacto
     - Modificar Contacto
     - Borrar Contacto
     - Consultar Contacto
     - Unicidad de Agenda
     - Interfaz de Menú de Texto
   - **Requisitos No Funcionales**
     - Eficiencia
     - Usabilidad
     - Persistencia de Datos
     - Escalabilidad
     - Manejabilidad
     - Confiabilidad
     - Portabilidad
     - Seguridad
     - Rendimiento
     - Compatibilidad

4. **Modelo de Desarrollo**
   - Justificación del Modelo Agile
   - Plan de Lifecycle Agile
     - Planificación y Reunión de Requisitos
     - Sprint Planning
     - Desarrollo en Sprints
     - Revisión del Sprint
     - Retrospectiva del Sprint
     - Release

5. **Segmentación en Módulos**
   - Identificación de Módulos Principales
     - Gestión de Contactos
     - Búsquedas y Consultas
     - Interfaz de Usuario (CLI)
     - Persistencia de Datos
     - Gestión de Errores y Logs
   - Ciclo Iterativo del Desarrollo

6. **Gestión de Bugs y Crecimiento del Programa**
   - Herramienta de Seguimiento de Bugs
   - Prioritización de Bugs
   - Ciclo de Vida del Bug
   - Planificación de Escalabilidad
   - Documentación
   - Feedback Continuo y Backlog Dinámico

7. **Flujos de Datos**
   - Diagramas de Flujo de Datos
   - Descripción de Flujos 
   - Casos de Uso

8. **Pseudocódigo de Componentes Clave**
   - Ejemplos de Pseudocódigo
     - Módulo de Creación de Contactos
     - Módulo de Búsqueda de Contactos
