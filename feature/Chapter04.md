## 4.6. Domain-Driven Software Architecture. 

Este enfoque enfatiza la importancia de entender a fondo el negocio para el que se está desarrollando el software, con el objetivo de crear soluciones que satisfagan sus requerimientos de manera precisa.

### 4.6.1. Software Architecture Context Diagram.

El esquema de contexto es una herramienta de análisis que permite comprender las relaciones entre Pawfect Care y su entorno, facilitando así la identificación de posibles puntos de integración y mejora.

<p align = "center"> <img  alt="Diagram Context" src="/feature/assets/Chapter04/context_diagram.png"> </p>

### 4.6.2. Software Architecture Container Diagrams

El diagrama de contenedores es una herramienta esencial para comprender la arquitectura de Pawfect Care y detectar posibles cuellos de botella o dependencias innecesarias.

<p align = "center"> <img  alt="Container Diagram" src="/feature/assets/Chapter04/container_diagram.png"> </p>

### 4.6.3. Software Architecture Components Diagrams.

Los diagramas de componentes ofrecen una vista detallada de la arquitectura del software, ilustrando cómo se descompone en módulos y cómo estos se relacionan entre sí para formar un sistema cohesivo.

*Veterinarians Bounded Context*

<p align = "center"> <img  alt="Component Diagram" src="/feature/assets/Chapter04/component_diagram.png"> </p>

*Pet Owners Bounded Context*

<p align = "center"> <img  alt="Component Diagram" src="/feature/assets/Chapter04/component_diagram01.png"> </p>

## 4.7. Software Object-Oriented Design.

En esta parte, exploramos la arquitectura interna del sistema, mostrando cómo los patrones de diseño se han aplicado para organizar y optimizar los componentes del software.

### 4.7.1. Class Diagrams.

<p align = "center"> <img  alt="Class Diagram" src="/feature/assets/Chapter04/uml_pawfectcare.png"> </p>

### 4.7.2. Class Dictionary.

A continuación se presenta el código en formato markdown con las clases, atributos y métodos correspondientes:

### User
#### Representa a los usuarios del sistema, que pueden ser veterinarios o clientes.

| Campo        | Tipo      | Descripción                                    |
|--------------|-----------|------------------------------------------------|
| id           | long int  | Identificador único del usuario.               |
| firstname    | string    | Nombre del usuario.                            |
| lastname     | string    | Apellido del usuario.                          |
| email        | string    | Correo electrónico del usuario.                |
| password     | string    | Contraseña del usuario.                        |


### Client
#### Representa a los clientes del sistema que poseen mascotas.

| Campo        | Tipo      | Descripción                                    |
|--------------|-----------|------------------------------------------------|
| phone        | string    | Número de teléfono del cliente.                |
| address      | string    | Dirección del cliente.                         |
| pets         | list<Pet> | Lista de mascotas que posee el cliente.        |


### Veterinarian
#### Representa a los veterinarios en el sistema.

| Campo        | Tipo              | Descripción                                  |
|--------------|-------------------|----------------------------------------------|
| specialty    | string            | Especialidad del veterinario.                |
| appointments | list<Appointment> | Lista de citas que tiene el veterinario.     |


### Pet
#### Representa a las mascotas registradas por los clientes.

| Campo         | Tipo               | Descripción                                      |
|---------------|--------------------|--------------------------------------------------|
| id            | long int           | Identificador único de la mascota.               |
| name          | string             | Nombre de la mascota.                            |
| age           | short int          | Edad de la mascota.                              |
| breed         | string             | Raza de la mascota.                              |
| client        | Client             | Propietario de la mascota.                       |
| medicalHistory| list<MedicalHistory>| Lista de historiales médicos.                     |
| currentStatus | PetStatus          | Estado actual de salud de la mascota.            |


### PetStatus
#### Define los posibles estados de salud de una mascota.

| Campo         | Tipo        | Descripción                                            |
|---------------|-------------|--------------------------------------------------------|
| currentStatus | enum_status | Estado de salud de la mascota (saludable, enfermo, etc.).|
| updateDate    | localDate   | Fecha de la última actualización del estado.            |
| pet           | Pet         | Mascota a la que pertenece este estado.                 |


### Appointment
#### Representa las citas entre un veterinario y una mascota.

| Campo        | Tipo             | Descripción                                      |
|--------------|------------------|--------------------------------------------------|
| id           | long int         | Identificador único de la cita.                  |
| date         | LocalDateTime    | Fecha y hora de la cita.                         |
| pet          | Pet              | Mascota que asiste a la cita.                    |
| veterinarian | Veterinarian     | Veterinario que atiende la cita.                 |
| description  | string           | Descripción o motivo de la cita.                 |


### MedicalHistory
#### Representa el historial médico de una mascota.

| Campo        | Tipo              | Descripción                                        |
|--------------|-------------------|----------------------------------------------------|
| id           | long int          | Identificador único del historial.                 |
| date         | localDate         | Fecha del historial médico.                        |
| description  | string            | Descripción del historial médico.                  |
| treatments   | list<Treatment>   | Lista de tratamientos aplicados.                   |
| veterinarian | Veterinarian      | Veterinario a cargo del historial.                 |
| pet          | Pet               | Mascota a la que pertenece este historial.          |


### Treatment
#### Representa los tratamientos realizados a una mascota.

| Campo           | Tipo            | Descripción                                          |
|-----------------|-----------------|------------------------------------------------------|
| id              | long int        | Identificador único del tratamiento.                 |
| name            | string          | Nombre del tratamiento.                              |
| description     | string          | Descripción del tratamiento.                         |
| duration        | int             | Duración del tratamiento (en días, horas, etc.).     |
| medicalHistory  | MedicalHistory  | Historial médico al que pertenece este tratamiento.  |


### ClientRepository
#### Se encarga de gestionar las operaciones de base de datos relacionadas con los clientes.

| Método               | Tipo de Retorno  | Descripción                                  |
|----------------------|------------------|----------------------------------------------|
| save(Client)         | void             | Guarda un nuevo cliente.                     |
| findById(long id)    | Client           | Busca un cliente por su ID.                  |
| delete(Client)       | void             | Elimina un cliente.                          |
| findAll()            | List<Client>     | Encuentra todos los clientes registrados.    |


### PetRepository
#### Gestiona las operaciones de base de datos relacionadas con las mascotas.

| Método               | Tipo de Retorno  | Descripción                                  |
|----------------------|------------------|----------------------------------------------|
| save(Pet)            | void             | Guarda una nueva mascota.                    |
| findById(long id)    | Pet              | Busca una mascota por su ID.                 |
| delete(Pet)          | void             | Elimina una mascota.                         |
| findAll()            | List<Pet>        | Encuentra todas las mascotas registradas.    |


### AppointmentRepository
#### Gestiona las operaciones de base de datos relacionadas con las citas.

| Método               | Tipo de Retorno  | Descripción                                  |
|----------------------|------------------|----------------------------------------------|
| save(Appointment)     | void             | Guarda una nueva cita.                       |
| findById(long id)     | Appointment      | Busca una cita por su ID.                    |
| delete(Appointment)   | void             | Elimina una cita.                            |
| findAll()             | List<Appointment>| Encuentra todas las citas registradas.       |


### ClientService
#### Proporciona la lógica de negocio relacionada con los clientes.

| Método               | Tipo de Retorno  | Descripción                                  |
|----------------------|------------------|----------------------------------------------|
| register(Client)      | void             | Registra un nuevo cliente.                   |
| getClientById(long id)| Client           | Obtiene un cliente por su ID.                |
| getAllClients()       | List<Client>     | Obtiene todos los clientes registrados.      |


### PetService
#### Gestiona la lógica de negocio relacionada con las mascotas.

| Método                   | Tipo de Retorno  | Descripción                                    |
|--------------------------|------------------|------------------------------------------------|
| register(Pet)             | void             | Registra una nueva mascota.                    |
| getPetById(long id)       | Pet              | Obtiene una mascota por su ID.                 |
| updatePetStatus(PetStatus)| void             | Actualiza el estado de salud de una mascota.   |


### AppointmentService
#### Gestiona la lógica de negocio relacionada con las citas.

| Método                        | Tipo de Retorno  | Descripción                                  |
|-------------------------------|------------------|----------------------------------------------|
| scheduleAppointment(Appointment) | void          | Programa una nueva cita.                     |
| getAppointmentById(long id)    | Appointment      | Obtiene una cita por su ID.                  |
| getAllAppointments()           | List<Appointment>| Obtiene todas las citas registradas.         |

## 4.8. Database Design.

Decidimos emplear MySQL como sistema gestor de bases de datos, administrado a través de MySQL Workbench. Esta decisión se fundamenta en la familiaridad del equipo con el lenguaje SQL y en la capacidad de la herramienta para satisfacer las demandas de nuestro proyecto.

<p align = "center"> <img  alt="ERD Diagram" src="/feature/assets/Chapter04/erd_pawfectcare.png"> </p>
