## Capítulo V: Product Implementation, Validation & Deployment
### 5.1. Software Configuration Management.
#### 5.1.1. Software Development Environment Configuration.
En esta sección, detallaremos las herramientas y plataformas que hemos utilizado como equipo para la realización de nuestro startup. Estas herramientas son esenciales para el desarrollo, la colaboración y la gestión del proyecto. A continuación, se presenta un resumen de cada una de las herramientas utilizadas:

- **GitHub**

    **Descripción:** GitHub es una plataforma de alojamiento de código fuente y colaboración basada en Git. Nos permite gestionar el código del proyecto, realizar revisiones de código, y colaborar de manera eficiente con nuestro equipo.<br>
    **Uso:** Se utilizó para el versionado del código, gestión de ramas y pull requests, así como para la documentación del proyecto.

- **Git**

    **Descripción:** Git es un sistema de control de versiones distribuido que facilita la gestión de cambios en el código fuente.<br> **Uso:** Se empleó para realizar commits, push y pull de cambios, así como para la gestión de ramas, permitiendo una colaboración fluida y eficiente en el desarrollo del proyecto.

- **Canva**

    **Descripción:** Canva es una herramienta de diseño gráfico en línea que permite crear gráficos y elementos visuales de manera intuitiva.<br> **Uso:** Se utilizó para diseñar gráficos y elementos visuales para la landing page del proyecto, incluyendo banners, íconos y otros elementos de diseño que mejoran la presentación visual de la aplicación.

- **Visual Studio Code**

    **Descripción:** Visual Studio Code (VS Code) es un editor de código fuente ligero y extensible que soporta una amplia variedad de lenguajes de programación.<br> **Uso:** Se utilizó como el principal editor de código para escribir y editar el código del proyecto, aprovechando sus extensiones para mejorar la productividad y facilitar el desarrollo.

- **WhatsApp**

    **Descripción:** WhatsApp es una aplicación de mensajería instantánea que facilita la comunicación rápida y efectiva.<br> **Uso:** Se empleó para la comunicación diaria entre los miembros del equipo, coordinando tareas, resolviendo problemas y organizando reuniones informales.

- **Google Meet**

    **Descripción:** Google Meet es una herramienta de videoconferencia que permite realizar reuniones virtuales con facilidad.<br> **Uso:** Se utilizó para llevar a cabo reuniones virtuales de equipo, facilitando discusiones en tiempo real y presentaciones de avances del proyecto a los stakeholders y al equipo.

- **Figma**

    **Descripción:** Figma es una herramienta de diseño colaborativo en línea que permite crear y prototipar interfaces de usuario.<br> **Uso:** Se empleó para el diseño de interfaces y prototipos del proyecto, permitiendo la colaboración en tiempo real entre diseñadores y desarrolladores para ajustar y revisar el diseño de la aplicación.


<br></br>

#### 5.1.2. Source Code Management.

**Gestión del Código Fuente:**


En esta sección, se detalla cómo gestionamos y supervisamos el desarrollo del código para el proyecto PawFect Care. Utilizamos GitHub como nuestra plataforma principal para la gestión del código fuente, complementada por Git como sistema de control de versiones. Además, seguimos el flujo de trabajo GitFlow para estructurar el desarrollo de manera eficiente.

- Repositorio GitHub para nuestra Landing Page:
<b>https://upc-pre-si729-2402-wx51-g4-aceitunitas.github.io/-PawfectCareLanding-Page.github.io/</b>


**Ramas Principales:**
- **main:** Esta rama, a menudo llamada "master", contiene la versión más estable y final del proyecto, lista para ser desplegada en producción. Los cambios integrados en esta rama han pasado todas las pruebas y revisiones necesarias, y se consideran completamente preparados para su lanzamiento.

- **develop:** La rama develop es el punto central de integración para las nuevas funcionalidades y mejoras en desarrollo. Las características y correcciones se fusionan en esta rama, donde se realizan pruebas adicionales antes de su eventual integración en la rama main.

**Ramas Auxiliares:**

- **releases:** Las ramas de tipo releases se crean para preparar nuevas versiones del proyecto. En estas ramas se llevan a cabo las pruebas finales y se corrigen errores menores antes del lanzamiento oficial. Una vez que una versión ha sido validada, los cambios se integran en la rama develop para futuros desarrollos y luego se fusionan en la rama main para su despliegue.

**Uso de GitFlow:**

- **Feature Branches:** Se utilizan ramas de características para desarrollar nuevas funcionalidades. Estas ramas se crean a partir de la rama develop y, una vez que se completa el desarrollo y se aprueban las revisiones, se fusionan nuevamente en la rama develop.

- **Bugfix Branches:** Para solucionar errores que necesitan ser corregidos antes de la siguiente versión, se utilizan ramas de corrección de errores. Estas ramas se crean a partir de la rama develop o, en casos críticos, desde la rama main.

- **Hotfix Branches:** Se emplean para abordar errores críticos que requieren una solución urgente en producción. Estas ramas se crean a partir de la rama main, y una vez que el problema se resuelve, los cambios se fusionan tanto en la rama main como en la rama develop.

Este enfoque estructurado con GitFlow nos permite gestionar el desarrollo del código de manera eficiente, facilitando la integración de nuevas características, la corrección de errores y la preparación de versiones estables para producción.



**Commits Conventions:**

En PawFect Care, los commits se nombran de acuerdo con el avance y el contenido específico del trabajo realizado. No seguimos una convención rígida para los nombres de los commits; en su lugar, los desarrolladores utilizan descripciones claras y concisas para reflejar las modificaciones implementadas. Esto nos permite una mayor flexibilidad a la hora de registrar el progreso, asegurando que cada commit tenga un nombre que represente con precisión el trabajo efectuado.

#### 5.1.3. Source Code Style Guide & Conventions.
En PawFect hemos implementado varias convenciones de estilo para asegurar un desarrollo de código claro y consistente en distintos lenguajes y tecnologías:

<b>HTML y CSS:</b> <br>

1. El tipo de documento se declara al inicio del archivo con `<!DOCTYPE html>`.

2. Se añaden los meta tags necesarios.

3. La etiqueta `<title>` se incluye dentro del bloque `<head>`.

4. Usamos una indentación de dos espacios.

5. Se escriben en minúsculas los nombres de los elementos HTML, atributos, propiedades, valores y selectores CSS.

6. Los atributos de los elementos HTML siempre están entre comillas.

7. Cada elemento HTML debe contar con su etiqueta de cierre.

8. Se evita escribir líneas de código demasiado largas.

9. Para las imágenes, se especifican tanto el ancho y alto como el texto alternativo.

<b>JavaScript</b>

1. Cada línea de código termina con un punto y coma.

2. Las variables y funciones siguen la convención de CamelCase.

3. Las cadenas de texto (strings) se colocan entre comillas simples.

4. La indentación es de 2 espacios.

5. Se utiliza preferentemente let y const en lugar de var para declarar variables.

6. Gherkin (Convenciones de Gherkin para Especificaciones Legibles)

7. Se utilizan los términos "Given", "When", "Then" y "And" para definir los pasos del escenario.

8. Los pasos que comienzan con "And" se indentan.

9. Se deja una línea en blanco entre los pasos.

10. Los parámetros se colocan entre comillas simples.

11. Se separan los escenarios con un comentario y dos líneas en blanco.


Estas convenciones nos ayudan a mantener el código organizado, legible y coherente a lo largo del proyecto.

- US01:

![Gherkin1](./assets/Chapter05/1.png)

- US02:

![Gherkin2](./assets/Chapter05/2.png)

- US03:

![Gherkin3](./assets/Chapter05/3.png)

- US04:

![Gherkin4](./assets/Chapter05/4.png)

- US05:

![Gherkin5](./assets/Chapter05/5.png)

- US06:

![Gherkin6](./assets/Chapter05/6.png)

- US07:

![Gherkin7](./assets/Chapter05/7.png)

- US08:

![Gherkin8](./assets/Chapter05/8.png)

- US09:

![Gherkin9](./assets/Chapter05/9.png)

- US010:

![Gherkin10](./assets/Chapter05/10.png)

- US11:

![Gherkin11](./assets/Chapter05/11.png)

- US12:

![Gherkin12](./assets/Chapter05/12.png)

- US13:

![Gherkin13](./assets/Chapter05/13.png)

- US014:

![Gherkin14](./assets/Chapter05/14.png)

- US15:

![Gherkin15](./assets/Chapter05/15.png)

### 5.1.4. Configuración de la implementación del software
En este apartado, abordaremos el despliegue de la Landing Page de Pawfect Care utilizando GitHub. A continuación, se describen los pasos para habilitar el acceso a la página de destino de Pawfect Care y se incluirán capturas de pantalla para ilustrar el proceso.

1. Nos aseguramos que la configuración de GitHub Pages esté habilitada para el repositorio de la Landing Page de Pawfect Care. Para ello, accedemos a la configuración del repositorio en GitHub.<br><br>

<img src="./assets/Chapter05/deploy1.jpg">

2. Accdemos a Github Pages:<br><br>
<img src="./assets/Chapter05/deploy2.jpg">

3. Tras seleccionar la configuracion adecuada, GitHub Pages nos proporcionará la URL de la Landing Page de Pawfect Care, la cual podremos compartir y acceder públicamente.<br><br>
<img src="./assets/Chapter05/rep3.png">

Enlace a la Landing Page de Pawfect Care:<br>
https://upc-pre-si729-2402-wx51-g4-aceitunitas.github.io/-PawfectCareLanding-Page.github.io/ 

## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1

<table>
  <tr>
    <th> Sprint # </th>
    <th> Sprint 1 </th>
  </tr>
  <tr>
    <td style="font-weight: bold;" colspan="2"> Sprint Planning Background </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Date </td>
    <td> 09/07/2024 </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Time </td>
    <td> 19:00 horas (GMT-5) </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Location </td>
    <td> Virtual (Google Meet) </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Prepared By </td>
    <td> Gutierrez Garcia, Jose Eduardo </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Attendees (to planning meeting) </td>
    <td>
      Bastidas Bastidas, Diego Martin<br>
      Chavez Uribe, Ario Joel<br>
      Gutierrez Garcia, Jose Eduardo<br>
      Perez Garcia, David Alexander<br>
      Zuniga Calle, Sebastian Gabriel
    </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Sprint 1 Review Summary </td>
    <td> Al este ser nuestro primer sprint de desarrollo no existe un review summary del sprint </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Sprint 1 Retrospective Summary </td>
    <td> Ya que es nuestro primer sprint aún no identificamos ningun plane de mejora. </td>
  </tr>
  <tr>
    <td style="font-weight: bold;" colspan="2"> Sprint Goal & User Stories </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Sprint 1 Goal </td>
    <td> Desarrollar e implementar las secciones clave de la Landing Page para que los usuarios puedan explorar las características principales de Pawfect Care y entender los beneficios del servicio. </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Sprint 1 Velocity </td>
    <td> <strong>8 </strong><br> El equipo ha establecido una capacidad de 8 Story Points para este Sprint, basada en la experiencia y la carga de trabajo estimada. </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Sum of Story Points </td>
    <td> 8 </td>
  </tr>
</table>


#### 5.2.1.2. Sprint Backlog 1

| id   | Title                  | Id  | Title                                                    | Description                                                                                                   | Estimations(Hours) | Assigned To   | Status(To-do /InProcess/ToReview/Done) |
| ---- | ---------------------- | --- | -------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- | ------------------ | ------------- | -------------------------------------- |
| US12 | Barra de navegación en la Landing Page     | TS01 |Barra de navegación en la Landing Page (Desarrollado en HTML, CSS y JS).| Implementación del header y la barra de navegación, desarrollados en HTML, CSS y JS con diseño responsive. | 8                  | Diego | Done                                   |
| US13 | Sección "Why Choose Us?"    | TS02 | Sección "Why Choose Us?" (Desarrollado en HTML, CSS y JS).|Implementación de la sección "Why Choose Us", con diseño responsive y optimización en HTML, CSS y JS. | 6                | David | Done                                   |
| HU03 | Sección de suscripciones           | TS03 | Sección de suscripciones (Desarrollado en HTML, CSS y JS).| Desarrollo de la sección de suscripciones, con integración de opciones de pago, en HTML, CSS y JS.           | 4                 | Jose   | Done                                   |
| H04 | Reseñas de clientes | TS04 | Reseñas de clientes (Desarrollado en HTML, CSS y JS).| Implementación de la sección de reseñas de clientes, con diseño responsive en HTML, CSS y JS.| 4 | Ario & Gabriel | Done

Este enfoque asegura que el equipo se concentre en las partes esenciales de la Landing Page, permitiendo que los usuarios exploren la plataforma de manera efectiva.

#### 5.2.1.3. Development Evidence for Sprint Review

| Repository | Branch | Commit Id | Commit <br>Message | Commit <br>Message Body | Commited <br>on (Date) |
|:-------------:|:---------------:|:-------------:|:-------------:|:---------------:|:-------------:|
| [PawFect Care <br>Landing Page](https://github.com/UPC-PRE-SI729-2402-WX51-G4-Aceitunitas/Pawfect-Care-Report) | main | b342095| Create index.html |  | 09/07/2024 |
| Landing | feat/section-home | e352819| feat: added/section-home |  | 09/07/2024 |
| Landing | feat/section-subscription | 5e84a90 | feat: added Section subscription |  | 09/07/2024 |
| Landing | feat/section-subscription | faf615f | feat: complete Section subscription |  | 09/07/2024|
| Landing | feat/section-review | 2b26403 | Add: feat: added contact, review and footer |  | 09/07/2024 |
| Landing | feat/section-typography | a1fe77e | feat: typography changed |  | 09/07/2024 |
| Landing | main| 2f9452b | feat: landing page deployment|  | 09/07/2024 |



#### 5.2.1.4. Testing Suite Evidence for Sprint Review
Durante este sprint, hemos llevado a cabo las pruebas de aceptación utilizando la herramienta Gherkin. Puedes encontrar los escenarios de estas pruebas dando click aqui: https://github.com/UPC-PRE-SI729-2402-WX51-G4-Aceitunitas/PawFect-care-Acceptance-Tests

| Repository | Branch | Commit Id | Commit <br>Message | Commit <br>Message Body | Commited <br>on (Date) |
|:-------------:|:---------------:|:-------------:|:-------------:|:---------------:|:-------------:|
| PawFect Care <br> Acceptance Tests | main | 4bbda94 | Initial commit |  | 09/07/2024 |
|   | main | 66c33e5 | feat: added acceptance tests |  | 09/07/2024 |
|   | main | 91e4297 | feat: added images |  | 09/07/2024 |


#### 5.2.1.5. Execution Evidence for Sprint Review
En esta entrega, el equipo PawFect Care ha logrado completar con éxito la creación y el deployment de la Landing Page.

Enlace del deployment de la Landing Page: [https://upc-pre-si729-2402-wx51-g4-aceitunitas.github.io/-PawfectCareLanding-Page.github.io/](https://upc-pre-si729-2402-wx51-g4-aceitunitas.github.io/-PawfectCareLanding-Page.github.io/)

Sección de header donde se encuentra el menu de navegación principal y el Banner donde se muestra un mensaje con una imagen acerca de PawFect Care:


Sección para saber que ofrecemos en nuestra plataforma:

<img src="./assets/Chapter05/rep3.png">

Seccion de ventajas

<img src="./assets/Chapter05/land1.png">

Sección de ventajas 2

<img src="./assets/Chapter05/land2.png">

Sección para ver las subscripciones que ofrecemos:

<img src="./assets/Chapter05/land3.png">

Sección de reseñas de clientes:

<img src="./assets/Chapter05/land4.png">

Sección de contacto:

<img src="./assets/Chapter05/land5.png">

Sección de footer:

<img src="./assets/Chapter05/land6.png">


#### 5.2.1.6. Services Documentation Evidence for Sprint Review

En esta entrega, nos enfocamos en Landing page, por lo que no fue necesario ningún servicio adicional.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

En este caso se uso GitHub Pages, para desplegar la Landing page, el cual nos sirvio para, a partir de un código en un repositorio poder desplegar la página. Enlace de la landing page: https://upc-pre-si729-2402-wx51-g4-aceitunitas.github.io/-PawfectCareLanding-Page.github.io/

<img src="./assets/Chapter05/sprint.png">

#### 5.2.1.8. Team Collaboration Insights during Sprint
Para llevar a cabo este proyecto se usaron distintas herramientas como Visual Studio Code; junto con manejo de versiones en Git. En este caso se dividio la landing page mostrada anteriormente en sectores, a partir de esto cada uno presentó su parte y luego un miembro juntó las partes para finalmente tener el resultado deseado.

<img src="./assets/Chapter05/commit.png">


## Conclusiones

- La colaboración efectiva entre los miembros del equipo es crucial para el éxito del proyecto. Cada integrante debe tener claro su rol y responsabilidades, lo que permite avanzar de manera organizada y cubrir todos los aspectos necesarios, desde la planificación hasta la implementación.

- La creación de User Stories y Product Backlog ayuda a priorizar las funcionalidades clave. Esto garantiza que las necesidades más importantes de los usuarios sean abordadas primero, permitiendo desarrollar un producto más alineado con las expectativas y requisitos del mercado.

- La arquitectura de software y el diseño orientado a objetos facilitan la escalabilidad y el mantenimiento del producto. Es fundamental definir correctamente la estructura del sistema para permitir una implementación ágil y minimizar problemas durante el despliegue y la validación.

## Bibliografía

- Sedano, L. (2024). _Manual para la gestión eficaz de clínicas veterinarias: Estrategias administrativas y organizativas._ Recuperado de https://puntomedic.cl/blogs/manuales-y-guias/manual-para-la-gestion-eficaz-de-clinicas-veterinarias-estrategias-administrativas-y-organizativas 

- BioSystems S.A. (s.f.). _Guía de buenas prácticas en veterinaria._ Barcelona, España: ioSystems S.A. Recuperado de https://covetrioja.org/wp-content/uploads/2021/10/VET_GuiaBuenasPracticas_ESP.pdf 



## Anexos

**Anexo 1:**

Entrevistas Médicos Veterinarios:<br>
- https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221a301_upc_edu_pe/EQ-ZYy2RvYpNgt1Qfy9tHTUByB1wTz3kGVrQscVWHWam9A?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=j1mdQ7

- https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221a301_upc_edu_pe/EbCW9J6OzTFKoDAHzGbfWzEBpDcpUG7M16WiUuDkC7iPMA

- https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221a301_upc_edu_pe/EYY7QpIHFxlDh0ksAmySO-kB1yHNDLGTJPHi61WTR0jlWg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=JeOE4m

Entrevistas Dueños de Mascotas:<br>

- https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221a301_upc_edu_pe/Ec1XInM48xNOvR2jbzHkwuABf9CG5aosdZClZOwqh0nyYw

- https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221a301_upc_edu_pe/EQxyGm-xOy9Gixk9iwdU5-4B7_sjaOllyMTn6QX3f6py1Q?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=aOWtoD

- https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221a301_upc_edu_pe/EZguwL4OXjdNkBzBDBzk7_IBxOR3aJXNCJtxhTOVihRx2w?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=YgjxMN


Video de muestra del prototipo:<br>
- https://upcedupe-my.sharepoint.com/:v:/g/personal/u202222942_upc_edu_pe/EQvCW-J5AvNMp7V0LnzxwWgB1LRddvYi7j22x7tsRPO17g?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=hd15Xj

**Anexo 2:**

Landing Page Figma:<br> 
https://upc-pre-si729-2402-wx51-g4-aceitunitas.github.io/-PawfectCareLanding-Page.github.io/


**Anexo 3:**

Presentación del Proyecto:<br> 
https://www.canva.com/design/DAGQH4YoDe8/bVXB2TFt09VzzVCTdg5aCQ/edit?utm_content=DAGQH4YoDe8&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

**Anexo 4:**

Landing Page:<br> 
https://upc-pre-si729-2402-wx51-g4-aceitunitas.github.io/-PawfectCareLanding-Page.github.io/


**Anexo 5:**

Class Diagram:<br>
https://lucid.app/lucidchart/361ed048-d40a-428f-9fce-46ad6b63b2e7/edit?viewport_loc=-2407%2C-1834%2C6485%2C3775%2CHWEp-vi-RSFO&invitationId=inv_f2d5b444-083c-417b-8a60-c2bbc478d9d7

**Anexo 6:**

Repositorio en GitHub para la Landing Page:<br>
https://github.com/UPC-PRE-SI729-2402-WX51-G4-Aceitunitas/-PawfectCareLanding-Page.github.io

**Anexo 7:**
Repositorio en Github para sprint review:<br>
https://github.com/UPC-PRE-SI729-2402-WX51-G4-Aceitunitas/PawFect-care-Acceptance-Tests.git

---
