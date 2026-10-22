# Cs-320-Pruebas-de-software-
Repositorio de la clase de Pruebas de software.

## Descripción del proyecto

En este curso desarrollé servicios en Java para administrar contactos, tareas y citas. También utilicé JUnit para crear pruebas unitarias que permitieran comprobar el funcionamiento de los métodos y verificar que los servicios cumplieran los requisitos establecidos. Este trabajo me ayudó a comprender la importancia de las pruebas, la calidad del software y la detección temprana de errores durante el desarrollo.

### 1. ¿Cómo me aseguro de que mi código, programa o software sea funcional y seguro?

Me aseguro de que el software sea funcional mediante pruebas unitarias que comprueban el comportamiento de los métodos, la validación de los datos y el cumplimiento de los requisitos. En este proyecto utilicé JUnit para probar los servicios de contacto, tareas y citas, incluyendo operaciones como agregar, actualizar y eliminar registros, así como la validación de campos obligatorios y restricciones de longitud. También reviso los resultados de las pruebas y corrijo los errores que se detecten. Para reforzar la seguridad, valido los datos de entrada, evito modificaciones no autorizadas y procuro que el código sea claro y fácil de mantener. Las pruebas no garantizan la ausencia total de errores, pero ayudan a reducir riesgos y aumentar la confianza en el software.

### 2. ¿Cómo interpreto las necesidades del usuario y las incorporo en un programa?

Primero identifico los requisitos del cliente y los convierto en comportamientos concretos que el programa debe cumplir. En los servicios de contacto, por ejemplo, cada contacto debía contar con información válida, como un identificador, nombre, número telefónico y dirección. A partir de esos requisitos, implementé validaciones para evitar datos vacíos, valores demasiado largos o identificadores duplicados, según las restricciones establecidas. Después utilicé pruebas unitarias para verificar que el servicio aceptara los datos válidos y rechazara los incorrectos. Este proceso me enseñó que comprender los requisitos antes de programar ayuda a crear soluciones más precisas y evita tener que corregir problemas importantes en etapas posteriores.

### 3. ¿Cómo abordo el diseño de software?

Abordo el diseño de software comenzando por analizar los requisitos y organizar la solución en clases y métodos con responsabilidades específicas. En este proyecto separé los objetos de contacto de la lógica de administración del servicio, lo que permitió mantener el código organizado y facilitar las pruebas. También considero los casos límite y las condiciones que podrían producir errores antes de implementar una funcionalidad. La experiencia con Java y JUnit me enseñó que un buen diseño no solo debe cumplir los requisitos, sino también facilitar el mantenimiento, las modificaciones y la detección de defectos. En futuros proyectos continuaré utilizando una estructura clara, validaciones apropiadas y pruebas desde las primeras etapas del desarrollo.

## Artefactos incluidos

- `Contact.java`: clase que representa la información de un contacto.
- `ContactService.java`: servicio que administra las operaciones sobre los contactos.
- `ContactTest.java`: pruebas unitarias de la clase Contact.
- `ContactServiceTest.java`: pruebas unitarias de las operaciones del servicio de contacto.
- Informe de síntesis y reflexiones del Proyecto final II.

## Aprendizaje y desarrollo profesional

Estos proyectos fortalecieron mis habilidades en Java, diseño de clases, validación de datos y pruebas unitarias con JUnit. También me ayudaron a desarrollar una mentalidad orientada a la calidad, en la que comprobar los requisitos y detectar errores es tan importante como implementar las funcionalidades. Los archivos y el informe incluidos en este repositorio representan evidencia de mi aprendizaje y pueden servir para demostrar mis conocimientos de pruebas de software a futuros empleadores.
