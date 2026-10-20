# Base de datos del Polideportivo Municipal de O Porriño

Proyecto académico de fin de módulo de **Bases de Datos** en el que diseñé e implementé, utilizando **MySQL**, una base de datos relacional para la gestión de un polideportivo municipal.

El proyecto parte de las necesidades de un centro deportivo: organizar sus instalaciones, usuarios, reservas, actividades y competiciones, manteniendo relacionadas las distintas partes de la información.

## Funcionalidades y datos gestionados

- **Usuarios y reservas:** registro de usuarios y de las instalaciones reservadas, con fecha, horario y estado.
- **Instalaciones y actividades:** información de los espacios deportivos, actividades programadas y participantes inscritos.
- **Personal:** gestión de entrenadores y monitores mediante una especialización de la entidad Personal.
- **Competiciones:** organización de equipos, jugadores, partidos y árbitros.

## Trabajo realizado

1. **Análisis de requisitos:** descripción del funcionamiento del polideportivo y sus reglas de negocio.
2. **Diseño de la base de datos:** elaboración de los modelos entidad-relación y relacional, junto con sus diccionarios de datos.
3. **Implementación en MySQL:** creación de tablas, claves primarias y foráneas, relaciones e inserción de datos de prueba.
4. **Consultas SQL:** obtención del número de equipos inscritos en cada competición y de las plazas ocupadas y libres de las actividades.
5. **Procedimiento almacenado:** consulta de las reservas realizadas por un usuario a partir de su identificador.
6. **Función:** cálculo del número de plazas disponibles en una actividad.
7. **Trigger:** prevención de reservas que se solapen para una misma instalación, fecha y franja horaria.

## Tecnologías y conceptos utilizados

- **MySQL y SQL**
- Diseño de bases de datos relacionales
- Diagramas entidad-relación y modelo relacional
- Claves primarias, claves foráneas e integridad referencial
- Consultas con `JOIN`, agrupaciones y subconsultas
- Procedimientos almacenados, funciones y triggers

## Documentación

El desarrollo completo del proyecto está recogido en el siguiente documento, que incluye los diagramas, los diccionarios de datos, capturas de la implementación y las pruebas de las consultas y rutinas SQL:

**[Ver memoria del proyecto (PDF)](IRENE.pdf)**

> **Nota:** Este repositorio presenta la memoria del proyecto en PDF. Las instrucciones SQL se muestran en las capturas incluidas en el documento.

## Autora

**Irene Figueroa Bugarín**
