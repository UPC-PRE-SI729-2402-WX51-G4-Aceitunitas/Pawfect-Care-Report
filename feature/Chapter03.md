# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping.

- **Primer segmento: Médicos Veterinarios**

<br><img src="./assets/Chapter03/Tobe1.jpeg" alt="To Be Scenario Map 1" style="width: 1000px; height: auto;" ><br>

- **Segundo segmento: Dueños de Mascotas**

<br><img src="./assets/Chapter03/Tobe2.jpeg" alt="To Be Scenario Map 2" style="width: 1000px; height: auto;" ><br>


## 3.2. User Stories
# Gestión de Usuarios
**EP01: Como administrador, deseo gestionar los usuarios para asegurar que solo personas autorizadas tengan acceso al sistema.**

| User Story ID | Título                     | Descripción                                                                                                                                                    |
|---------------|----------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| US01          | Registro de Usuario        | Como visitante, deseo registrarme en la plataforma para poder utilizar las funcionalidades del sistema                                                        |
| US02          | Recuperación de Contraseña | Como usuario, deseo recuperar mi contraseña en caso de olvidarla para no perder el acceso a mi cuenta                                                         |
| US03          | Gestión de Perfiles de Usuarios | Como administrador, deseo gestionar los perfiles de los usuarios para mantener la información y permisos actualizados.                                    |

---

# Gestión de Mascotas
**EP02: Como usuario, deseo gestionar la información de mis mascotas para mantener sus datos actualizados.**

| User Story ID | Título                     | Descripción                                                                                                                                                    |
|---------------|----------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| US04          | Creación de Perfil de Mascota | Como usuario, deseo crear un perfil de mi mascota para tener su información almacenada en la plataforma.                                                  |
| US05          | Edición de Perfil de Mascota | Como usuario, deseo editar el perfil de mi mascota para actualizar su información cuando sea necesario.                                                    |
| US06          | Visualización de Perfiles de Mascotas | Como usuario, deseo visualizar los perfiles de mis mascotas para revisar la información registrada.                                                    |
| US07          | Búsqueda de Mascotas por ID | Como administrador, deseo buscar mascotas por ID para acceder rápidamente a su información en el sistema.                                                   |
| US08          | Gestión de Perfiles de Mascotas | Como administrador, deseo gestionar los perfiles de mascotas para asegurarme de que la información esté correctamente registrada y actualizada.          |

---

# Gestión de Citas Veterinarias
**EP03: Como usuario, deseo gestionar las citas veterinarias de mis mascotas para asegurarme de que reciban atención médica a tiempo.**

| User Story ID | Título                     | Descripción                                                                                                                                                    |
|---------------|----------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| US09          | Agendamiento de Citas      | Como usuario, deseo agendar citas veterinarias para asegurar que mi mascota reciba atención médica en el momento adecuado.                                     |
| US10          | Cancelación de Citas       | Como usuario, deseo cancelar una cita si no puedo asistir, para evitar problemas de horario y reorganizar la atención.                                        |
| US11          | Gestión de Citas Veterinarias | Como administrador, deseo gestionar las citas veterinarias para coordinar correctamente la atención de las mascotas.                                     |
| US12          | Búsqueda de Citas por ID   | Como administrador, deseo buscar citas por ID para acceder rápidamente a la información de la cita.                                                           |
| US13          | Edición de Citas Veterinarias | Como administrador, deseo editar las citas para hacer cambios en la fecha o estado cuando sea necesario.                                                 |

---

# Gestión de Notificaciones
**EP04: Como usuario, deseo recibir notificaciones sobre eventos importantes relacionados con mis mascotas para estar siempre informado.**

| User Story ID | Título                     | Descripción                                                                                                                                                    |
|---------------|----------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| US14          | Notificación de Citas Veterinarias | Como usuario, deseo recibir notificaciones de citas veterinarias para recordarme cuándo debo llevar a mi mascota al veterinario.                      |
| US15          | Notificación de Historial Médico | Como usuario, deseo recibir notificaciones sobre actualizaciones en el historial médico de mi mascota para estar al tanto de su salud.                   |
| US16          | Gestión de Notificaciones   | Como administrador, deseo gestionar el envío de notificaciones para asegurarme de que los usuarios reciban información importante a tiempo.               |

---

# Navegación y Funcionalidades de la Landing Page
**EP05: Como visitante, deseo explorar la página principal de Pawfect Care para entender los servicios y características que ofrece la plataforma.**

| User Story ID | Título                                     | Descripción                                                                                                                                                     |
|---------------|-------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| US17          | Barra de Navegación en la Landing Page     | Como visitante, deseo usar la barra de navegación para acceder fácilmente a las diferentes secciones de la plataforma.                                        |
| US18          | Visualización de la Sección "Why Choose Us?" | Como visitante, deseo revisar la sección "Why Choose Us?" para entender los beneficios y servicios de la plataforma.                                     |
| US19          | Gestión de Suscripciones en la Landing Page | Como visitante, deseo revisar los planes de suscripción en la página principal para elegir el plan más adecuado para mí.                                  |
| US20          | Revisión de Reseñas de Clientes           | Como visitante, deseo revisar las reseñas de otros clientes para evaluar la experiencia de otros usuarios con la plataforma.                                 |
| US21          | Envío de Mensajes de Contacto             | Como visitante, deseo enviar un mensaje de contacto a través de la landing page para comunicarme con el equipo de Pawfect Care.                             |
| US22          | Visualización de Videos en la Sección de Características | Como visitante, deseo ver los videos informativos sobre los productos y servicios para conocer más sobre Pawfect Care.                                    |

---

# Gestión de Clientes
**EP06: Como administrador, deseo gestionar la información de los clientes para mantener los datos actualizados y organizados.**

| User Story ID | Título                     | Descripción                                                                                                                                                    |
|---------------|----------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| US24          | Creación de Perfiles de Clientes | Como administrador, deseo crear perfiles de clientes para registrar la información de contacto y sus mascotas.                                            |
| US25          | Edición de Perfiles de Clientes | Como administrador, deseo editar los perfiles de clientes para actualizar su información personal y de contacto.                                          |
| US26          | Búsqueda de Clientes por ID | Como administrador, deseo buscar clientes por su ID para acceder rápidamente a su información y gestionar sus mascotas.                                      |

---

# Gestión de Eventos Veterinarios
**EP07: Como administrador o doctor veterinario, deseo gestionar los eventos veterinarios para asegurarme de que las mascotas reciban la atención adecuada.**

| User Story ID | Título                     | Descripción                                                                                                                                                    |
|---------------|----------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| US27          | Creación de Eventos Veterinarios | Como administrador, deseo crear eventos veterinarios como desparasitaciones, vacunaciones, y chequeos para gestionar el historial médico de las mascotas.    |
| US28          | Edición de Eventos Veterinarios | Como administrador, deseo editar los eventos veterinarios para corregir fechas o agregar información adicional.                                            |
| US29          | Búsqueda de Eventos por ID | Como administrador, deseo buscar eventos veterinarios por ID para revisar o modificar la información rápidamente.                                            |
| US30          | Gestión del Estado de los Eventos | Como administrador, deseo cambiar el estado de los eventos (ej. completado, pendiente) para reflejar su estado actual.                                   |

---

# Gestión de Historial Médico de las Mascotas
**EP08: Como usuario o administrador, deseo gestionar el historial médico de las mascotas para llevar un registro de sus atenciones y tratamientos.**

| User Story ID | Título                     | Descripción                                                                                                                                                    |
|---------------|----------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| US31          | Visualización del Historial Médico | Como usuario, deseo visualizar el historial médico de mi mascota para revisar su estado de salud y tratamientos previos.                                  |
| US32          | Actualización del Historial Médico | Como administrador o doctor veterinario, deseo actualizar el historial médico de las mascotas para que los usuarios tengan la información más reciente sobre sus tratamientos. |

---

# Funcionalidades de Idioma en la App Web
**EP09: Como usuario, deseo cambiar el idioma de la plataforma para navegar entre las versiones en inglés y español de la app web.**

| User Story ID | Título                     | Descripción                                                                                                                                                    |
|---------------|----------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| US23          | Cambio de Idioma en la App Web | Como usuario, deseo cambiar el idioma de la app web para poder utilizarla en inglés o español según mi preferencia.                                        |

<br><br>
# Historias de Usuario y Criterios de Aceptación

## US01: Registro de Usuario
**Relacionado con (Epic ID):** EP01

**Descripción:**  
Como administrador, deseo gestionar los usuarios para asegurar que solo personas autorizadas tengan acceso al sistema.

### Criterios de Aceptación:
- **Escenario 1:** El usuario necesita registrarse en el sistema  
  - **Dado que** el usuario está en la página de registro,  
  - **Cuando** el usuario completa todos los campos requeridos (nombre completo, teléfono, correo electrónico, dirección y contraseña),  
  - **Entonces** el sistema debe permitir al usuario crear una cuenta y mostrar un mensaje de confirmación.

- **Escenario 2:** El usuario ingresa un correo electrónico ya registrado  
  - **Dado que** el usuario intenta registrarse con un correo electrónico ya asociado a una cuenta,  
  - **Cuando** el usuario ingresa el correo duplicado y envía el formulario,  
  - **Entonces** el sistema debe mostrar un mensaje de error indicando que el correo ya está registrado.

- **Escenario 3:** El usuario deja campos obligatorios sin llenar  
  - **Dado que** el usuario intenta registrarse sin completar todos los campos obligatorios,  
  - **Cuando** el usuario presiona el botón de registro sin llenar todos los campos,  
  - **Entonces** el sistema debe mostrar un mensaje de error solicitando que se completen todos los campos requeridos.

---

## US02: Recuperación de Contraseña
**Relacionado con (Epic ID):** EP01

**Descripción:**  
Como usuario, deseo recuperar mi contraseña en caso de olvidarla para no perder el acceso a mi cuenta.

### Criterios de Aceptación:
- **Escenario 1:** El usuario necesita recuperar su contraseña  
  - **Dado que** el usuario ha olvidado su contraseña y está en la página de recuperación de contraseña,  
  - **Cuando** el usuario ingresa su correo electrónico registrado y solicita la recuperación,  
  - **Entonces** el sistema debe enviar un correo con un enlace para restablecer la contraseña.

- **Escenario 2:** El usuario ingresa un correo electrónico no registrado  
  - **Dado que** el usuario intenta recuperar la contraseña con un correo electrónico no registrado en el sistema,  
  - **Cuando** el usuario envía el formulario con el correo no registrado,  
  - **Entonces** el sistema debe mostrar un mensaje de error indicando que no se ha encontrado ninguna cuenta asociada a ese correo.

- **Escenario 3:** El usuario no recibe el correo de recuperación  
  - **Dado que** el usuario ha solicitado la recuperación de la contraseña,  
  - **Cuando** no recibe el correo de recuperación en un tiempo razonable (10 minutos),  
  - **Entonces** el sistema debe ofrecer al usuario la opción de reenviar el correo de recuperación o contactar con el soporte.

---

## US03: Gestión de Perfiles de Usuarios
**Relacionado con (Epic ID):** EP01

**Descripción:**  
Como administrador, deseo gestionar los perfiles de los usuarios para mantener la información y permisos actualizados.

### Criterios de Aceptación:
- **Escenario 1:** El administrador edita el perfil de un usuario  
  - **Dado que** el administrador está en la sección de gestión de usuarios,  
  - **Cuando** selecciona el perfil de un usuario y edita su información (nombre, correo, teléfono, dirección),  
  - **Entonces** el sistema debe permitir que el administrador guarde los cambios y mostrar un mensaje de confirmación.

- **Escenario 2:** El administrador desactiva una cuenta de usuario  
  - **Dado que** el administrador desea desactivar la cuenta de un usuario,  
  - **Cuando** selecciona la opción de desactivar en la lista de usuarios,  
  - **Entonces** el sistema debe cambiar el estado del usuario a "inactivo" y el usuario no podrá acceder al sistema hasta ser reactivado.

- **Escenario 3:** El administrador elimina un perfil de usuario  
  - **Dado que** el administrador está gestionando perfiles de usuarios,  
  - **Cuando** selecciona la opción de eliminar el perfil de un usuario,  
  - **Entonces** el sistema debe eliminar permanentemente el perfil y todos sus datos asociados, mostrando una advertencia antes de la eliminación.

---

## US04: Creación de Perfil de Mascota
**Relacionado con (Epic ID):** EP02

**Descripción:**  
Como usuario, deseo crear un perfil de mi mascota para tener su información almacenada en la plataforma.

### Criterios de Aceptación:
- **Escenario 1:** El usuario crea un perfil para su mascota  
  - **Dado que** el usuario está en la página de creación de perfil de mascota,  
  - **Cuando** ingresa toda la información requerida (nombre de la mascota, fecha de nacimiento, raza, género, historial clínico),  
  - **Entonces** el sistema debe permitir la creación del perfil y mostrar un mensaje de confirmación de éxito.

- **Escenario 2:** El usuario deja campos obligatorios sin llenar  
  - **Dado que** el usuario está intentando crear el perfil de una mascota,  
  - **Cuando** deja uno o más campos obligatorios vacíos,  
  - **Entonces** el sistema debe mostrar un mensaje de error indicando que debe completar todos los campos requeridos antes de crear el perfil.

- **Escenario 3:** El usuario introduce un nombre de mascota duplicado  
  - **Dado que** el usuario está creando un perfil de mascota,  
  - **Cuando** ingresa un nombre de mascota que ya existe en su cuenta,  
  - **Entonces** el sistema debe mostrar una advertencia solicitando al usuario que elija un nombre único o que diferencie entre mascotas con nombres similares.

---

## US05: Edición de Perfil de Mascota
**Relacionado con (Epic ID):** EP02

**Descripción:**  
Como usuario, deseo editar el perfil de mi mascota para actualizar su información cuando sea necesario.

### Criterios de Aceptación:
- **Escenario 1:** El usuario edita el perfil de su mascota  
  - **Dado que** el usuario está en la página de edición del perfil de su mascota,  
  - **Cuando** realiza cambios en la información del perfil (por ejemplo, actualiza el historial clínico o cambia la raza),  
  - **Entonces** el sistema debe permitir guardar los cambios y mostrar un mensaje de confirmación de éxito.

- **Escenario 2:** El usuario intenta guardar un perfil con información incompleta  
  - **Dado que** el usuario está editando el perfil de una mascota,  
  - **Cuando** intenta guardar el perfil sin haber completado todos los campos requeridos,  
  - **Entonces** el sistema debe mostrar un mensaje de error solicitando que complete toda la información requerida.

  ---

  ## US11: Gestión de Citas Veterinarias
**Relacionado con (Epic ID):** EP03

**Descripción:**  
Como administrador, deseo gestionar las citas veterinarias para coordinar correctamente la atención de las mascotas.

### Criterios de Aceptación:
- **Escenario 1:** El administrador visualiza todas las citas  
  - **Dado que** el administrador está en la sección de gestión de citas,  
  - **Cuando** accede al listado de citas agendadas,  
  - **Entonces** el sistema debe mostrar todas las citas con detalles como fecha, hora, veterinario asignado, y estado de la cita (agendada, cancelada, etc.).

- **Escenario 2:** El administrador filtra las citas por estado o fecha  
  - **Dado que** el administrador está gestionando las citas,  
  - **Cuando** utiliza los filtros para buscar citas según estado (agendada, cancelada, completada) o fecha,  
  - **Entonces** el sistema debe mostrar solo las citas que coincidan con los criterios seleccionados.

---

## US12: Búsqueda de Citas por ID
**Relacionado con (Epic ID):** EP03

**Descripción:**  
Como administrador, deseo buscar citas por ID para acceder rápidamente a la información de la cita.

### Criterios de Aceptación:
- **Escenario 1:** El administrador busca una cita por su ID  
  - **Dado que** el administrador está en la sección de citas,  
  - **Cuando** ingresa el ID de una cita en el campo de búsqueda,  
  - **Entonces** el sistema debe mostrar la cita correspondiente al ID ingresado.

- **Escenario 2:** El administrador ingresa un ID inválido  
  - **Dado que** el administrador está buscando una cita por ID,  
  - **Cuando** ingresa un ID que no existe en el sistema,  
  - **Entonces** el sistema debe mostrar un mensaje de error indicando que no se encontró ninguna cita con ese ID.

---

## US13: Edición de Citas Veterinarias
**Relacionado con (Epic ID):** EP03

**Descripción:**  
Como administrador, deseo editar las citas para hacer cambios en la fecha o estado cuando sea necesario.

### Criterios de Aceptación:
- **Escenario 1:** El administrador edita la fecha de una cita  
  - **Dado que** el administrador está en la página de gestión de citas,  
  - **Cuando** selecciona una cita y cambia su fecha u hora,  
  - **Entonces** el sistema debe actualizar la cita y enviar una notificación al usuario afectado indicando el cambio.

- **Escenario 2:** El administrador cambia el estado de una cita  
  - **Dado que** el administrador está gestionando citas,  
  - **Cuando** selecciona una cita y cambia su estado (de agendada a completada o cancelada),  
  - **Entonces** el sistema debe reflejar el cambio y enviar una actualización al usuario de la cita.

---

## US14: Notificación de Citas Veterinarias
**Relacionado con (Epic ID):** EP04

**Descripción:**  
Como usuario, deseo recibir notificaciones de citas veterinarias para recordarme cuándo debo llevar a mi mascota al veterinario.

### Criterios de Aceptación:
- **Escenario 1:** El usuario recibe una notificación de recordatorio de cita  
  - **Dado que** el usuario ha agendado una cita veterinaria,  
  - **Cuando** faltan 24 horas para la cita,  
  - **Entonces** el sistema debe enviar una notificación al usuario recordándole la cita con los detalles de la misma (fecha, hora, veterinario).

- **Escenario 2:** El usuario recibe una notificación de recordatorio el día de la cita  
  - **Dado que** el usuario tiene una cita veterinaria programada,  
  - **Cuando** es el mismo día de la cita, 1 hora antes de la hora programada,  
  - **Entonces** el sistema debe enviar una notificación final de recordatorio.

---

## US15: Notificación de Historial Médico
**Relacionado con (Epic ID):** EP04

**Descripción:**  
Como usuario, deseo recibir notificaciones sobre actualizaciones en el historial médico de mi mascota para estar al tanto de su salud.

### Criterios de Aceptación:
- **Escenario 1:** El usuario recibe una notificación de actualización del historial médico  
  - **Dado que** el veterinario ha actualizado el historial médico de la mascota,  
  - **Cuando** se añaden nuevos registros médicos (vacunas, diagnósticos, tratamientos),  
  - **Entonces** el sistema debe enviar una notificación al usuario indicando que hay actualizaciones disponibles en el historial médico de su mascota.

- **Escenario 2:** El usuario recibe una notificación de resultados de exámenes médicos  
  - **Dado que** el usuario está esperando los resultados de un examen médico para su mascota,  
  - **Cuando** el veterinario sube los resultados al sistema,  
  - **Entonces** el sistema debe notificar al usuario de que los resultados están disponibles para su revisión.

---

## US16: Gestión de Notificaciones
**Relacionado con (Epic ID):** EP04

**Descripción:**  
Como administrador, deseo gestionar el envío de notificaciones para asegurarme de que los usuarios reciban información importante a tiempo.

### Criterios de Aceptación:
- **Escenario 1:** El administrador programa el envío de notificaciones  
  - **Dado que** el administrador está en la sección de gestión de notificaciones,  
  - **Cuando** establece los criterios de envío (por ejemplo, recordatorios de citas con 24 horas de antelación),  
  - **Entonces** el sistema debe programar las notificaciones de acuerdo a los criterios establecidos.

- **Escenario 2:** El administrador cancela una notificación programada  
  - **Dado que** el administrador ha programado una notificación para una cita,  
  - **Cuando** la cita es cancelada o reprogramada,  
  - **Entonces** el sistema debe cancelar automáticamente la notificación relacionada o ajustarla a la nueva fecha/hora.

---

## US27: Creación de Eventos Veterinarios
**Relacionado con (Epic ID):** EP07

**Descripción:**  
Como administrador, deseo crear eventos veterinarios como desparasitaciones, vacunaciones y chequeos para gestionar el historial médico de las mascotas.

### Criterios de Aceptación:
- **Escenario 1:** Creación de un evento veterinario exitoso  
  - **Dado que** soy un administrador o doctor veterinario,  
  - **Cuando** accedo al módulo de creación de eventos veterinarios e ingreso los detalles requeridos (tipo de evento, fecha, mascota, etc.),  
  - **Entonces** el sistema debe guardar el evento en el historial médico de la mascota y mostrar un mensaje de confirmación de creación exitosa.

- **Escenario 2:** Creación de evento con campos obligatorios faltantes  
  - **Dado que** soy un administrador intentando crear un evento veterinario,  
  - **Cuando** intento guardar un evento sin completar los campos obligatorios (ej. tipo de evento o fecha),  
  - **Entonces** el sistema debe mostrar un mensaje de error indicando que se deben completar todos los campos requeridos antes de guardar.

---

## US28: Edición de Eventos Veterinarios
**Relacionado con (Epic ID):** EP07

**Descripción:**  
Como administrador, deseo editar los eventos veterinarios para corregir fechas o agregar información adicional.

### Criterios de Aceptación:
- **Escenario 1:** Edición de evento veterinario exitoso  
  - **Dado que** soy un administrador,  
  - **Cuando** accedo a un evento veterinario previamente creado y realizo modificaciones (ej. cambiar la fecha o agregar notas adicionales),  
  - **Entonces** el sistema debe guardar los cambios y mostrar una notificación de que el evento ha sido editado con éxito.

- **Escenario 2:** Edición de evento con fecha no válida  
  - **Dado que** soy un administrador editando un evento,  
  - **Cuando** intento cambiar la fecha a una fecha inválida (ej. una fecha en el pasado para un evento futuro),  
  - **Entonces** el sistema debe mostrar un mensaje indicando que la fecha no es válida y debe ser corregida.

---

## US29: Búsqueda de Eventos por ID
**Relacionado con (Epic ID):** EP07

**Descripción:**  
Como administrador, deseo buscar eventos veterinarios por ID para revisar o modificar la información rápidamente.

### Criterios de Aceptación:
- **Escenario 1:** Búsqueda exitosa de evento por ID  
  - **Dado que** soy un administrador,  
  - **Cuando** ingreso el ID de un evento veterinario en el campo de búsqueda,  
  - **Entonces** el sistema debe mostrar los detalles del evento correspondiente y permitir su revisión o modificación.

- **Escenario 2:** Búsqueda de evento con ID no existente  
  - **Dado que** soy un administrador buscando un evento veterinario,  
  - **Cuando** ingreso un ID que no existe en el sistema,  
  - **Entonces** el sistema debe mostrar un mensaje indicando que no se ha encontrado ningún evento con ese ID.

---

## US30: Gestión del Estado de los Eventos
**Relacionado con (Epic ID):** EP07

**Descripción:**  
Como administrador, deseo cambiar el estado de los eventos (ej. completado, pendiente) para reflejar su estado actual.

### Criterios de Aceptación:
- **Escenario 1:** Cambio exitoso de estado de evento  
  - **Dado que** soy un administrador gestionando eventos veterinarios,  
  - **Cuando** cambio el estado de un evento de "pendiente" a "completado",  
  - **Entonces** el sistema debe actualizar el estado del evento y reflejar el cambio en el historial médico de la mascota.

- **Escenario 2:** Cambio de estado con eventos no completados  
  - **Dado que** soy un administrador revisando un evento,  
  - **Cuando** intento cambiar el estado de un evento a "completado" pero no se han realizado todas las acciones requeridas (ej. una cita pendiente),  
  - **Entonces** el sistema debe mostrar una advertencia indicando que el evento no puede marcarse como completado hasta que se cumplan todos los requisitos.

---

## US31: Visualización del Historial Médico
**Relacionado con (Epic ID):** EP08

**Descripción:**  
Como usuario, deseo visualizar el historial médico de mi mascota para revisar su estado de salud y tratamientos previos.

### Criterios de Aceptación:
- **Escenario 1:** Visualización exitosa del historial médico  
  - **Dado que** soy un usuario autenticado en la plataforma,  
  - **Cuando** accedo al perfil de mi mascota y selecciono la opción de visualizar el historial médico,  
  - **Entonces** el sistema debe mostrarme todos los detalles del historial médico, incluyendo diagnósticos, tratamientos, y citas previas de mi mascota.

- **Escenario 2:** Historial médico sin información registrada  
  - **Dado que** soy un usuario autenticado accediendo al perfil de mi mascota,  
  - **Cuando** intento visualizar el historial médico y no existen registros previos de atención,  
  - **Entonces** el sistema debe mostrar un mensaje indicando que no hay información médica disponible en el historial de la mascota.

---

## US32: Actualización del Historial Médico
**Relacionado con (Epic ID):** EP08

**Descripción:**  
Como administrador o doctor veterinario, deseo actualizar el historial médico de las mascotas para que los usuarios tengan la información más reciente sobre sus tratamientos.

### Criterios de Aceptación:
- **Escenario 1:** Actualización exitosa del historial médico  
  - **Dado que** soy un administrador o doctor veterinario,  
  - **Cuando** realizo una actualización en el historial médico de una mascota (ej. registrar un nuevo diagnóstico o tratamiento),  
  - **Entonces** el sistema debe guardar los cambios y reflejar la nueva información en el perfil de la mascota, accesible para los usuarios.

- **Escenario 2:** Intento de actualización con campos obligatorios incompletos  
  - **Dado que** soy un administrador o doctor veterinario intentando actualizar el historial médico,  
  - **Cuando** dejo campos obligatorios sin completar (ej. fecha del tratamiento o diagnóstico),  
  - **Entonces** el sistema debe mostrar un mensaje de error solicitando que se completen los campos obligatorios antes de guardar los cambios.

- **Escenario 3:** Verificación de actualizaciones previas en el historial  
  - **Dado que** soy un administrador o doctor veterinario,  
  - **Cuando** accedo a un historial médico previamente actualizado,  
  - **Entonces** debo poder visualizar un registro detallado de todas las actualizaciones realizadas, incluyendo las fechas y los usuarios que realizaron cada modificación.


## 3.3. Impact Mapping.

Este Impact Map muestra cómo Pawfect Care alinea sus objetivos de negocio con los impactos deseados. Detalla los entregables específicos y las user stories que abordan estos impactos, asegurando que cada aspecto del desarrollo de la plataforma mejore la eficiencia y la experiencia del usuario.


<br><img src="./assets/Chapter03/Impactmap.png" alt="Impact Map" style="width: 1000px; height: auto;" ><br>

## 3.4. Product Backlog.

Con el fin de simplificar la complejidad de las tareas, hemos utilizado la escala de Fibonacci (1/2/3/5/8) para crear nuestro product backlog.
Historia de usuario base:
Tomamos como referencia US06: Como usuario, quiero agendar citas para que mi mascota reciba atención veterinaria a tiempo. (Posee 3 puntos de historia).
Asimismo, utilizamos la herramienta “Planning Poker Online” para poder votar en grupo y decidir la dificultad de cada historia de usuario, tomando como punto intermedio el User Story 06

<table>
  <thead>
    <tr>
      <th># Orden</th>
      <th>User Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Story Points (1/2/3/5/8)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>US01</td>
      <td>Registro de Usuario</td>
      <td>Como administrador, deseo permitir a los usuarios registrarse para que puedan acceder al sistema.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>2</td>
      <td>US06</td>
      <td>Agendamiento de Citas</td>
      <td>Como usuario, deseo gestionar las citas veterinarias de mis mascotas para asegurarme de que reciban atención médica a tiempo.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>3</td>
      <td>US12</td>
      <td>Barra de navegación en la Landing Page</td>
      <td>Como usuario, quiero un menú para ver las secciones de la aplicación.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>4</td>
      <td>US13</td>
      <td>Sección "Why Choose Us?"</td>
      <td>Como usuario, quiero una sección que explique por qué debo elegir Pawfect Care para entender los beneficios y características de la plataforma.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>5</td>
      <td>US02</td>
      <td>Recuperación de Contraseña</td>
      <td>Como administrador, deseo que los usuarios puedan recuperar sus contraseñas en caso de olvido </td>
      <td>2</td>
    </tr>
    <tr>
      <td>6</td>
      <td>US05</td>
      <td>Edición de Perfil de Mascota</td>
      <td>Como usuario, deseo gestionar la información de mis mascotas para mantener sus datos actualizados.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>7</td>
      <td>US03</td>
      <td>Gestión de Perfiles de Usuarios</td>
      <td>Como administrador, deseo gestionar los perfiles de los usuarios para asegurar que solo personas autorizadas tengan acceso.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>8</td>
      <td>US04</td>
      <td>Creación de Perfil de Mascota</td>
      <td>Como usuario, deseo crear un perfil de mascota para mantener sus datos organizados.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>9</td>
      <td>US07</td>
      <td>Cancelación de Citas</td>
      <td>Como usuario, deseo cancelar las citas veterinarias de mis mascotas cuando sea necesario.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>10</td>
      <td>US08</td>
      <td>Notificaciones de Citas</td>
      <td>Como usuario, deseo recibir notificaciones sobre eventos importantes relacionados con las citas de mis mascotas.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>11</td>
      <td>US14</td>
      <td>	Sección de suscripciones</td>
      <td>Como usuario, quiero una sección de suscripciones para entender las opciones de pago y los beneficios asociados.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>12</td>
      <td>US15</td>
      <td>Reseñas de clientes</td>
      <td>Como usuario, quiero leer reseñas de otros clientes para evaluar la calidad del servicio antes de usar la plataforma.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>13</td>
      <td>US099</td>
      <td>Notificaciones de Historial Médico</td>
      <td>Como usuario, deseo recibir notificaciones sobre actualizaciones en el historial médico de mis mascotas.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>14</td>
      <td>US10</td>
      <td>	Publicación en el Foro</td>
      <td>Como usuario, deseo publicar en un foro comunitario para intercambiar experiencias y consejos con otros dueños de mascotas.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>15</td>
      <td>US11</td>
      <td>Moderación del Foro</td>
      <td>Como usuario, deseo moderar el foro para asegurar que las discusiones sean respetuosas y relevantes.</td>
      <td>8</td>
    </tr>
      </tbody>
</table>

---
