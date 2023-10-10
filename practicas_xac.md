# Desarrollo de APIs REST para BD vectoriales

## Desarrollo de un ejemplo API REST con Node y BD SQL-Server

El objetivo de este módulo es el entrenamiento para el desarrollo de un API REST que permita gestionar la información de una base de datos de torneos de golf.

### Diseño e implementación de la BD

Existen tres entidades a gestionar:
- Jugadores.
- Torneos.
- Resultados de los jugadores en los torneos.

Debe diseñarse una base de datos que permita albergar los datos de dichas entidades. Se utilizará la técnica de identificadores únicos (utilizando autonuméricos, IDENTITY en términos de SQL-Server).

Definir claves primarias y claves foráneas.

Entregables:
- Script de creación de BD (estructura).
- Script de inserción de un conjunto de datos de prueba.

Los dos scritps deben permitir la creación de una BD de pruebas desde cero.

### Diseño de API REST

Debe diseñarse un API REST que permita implementar un CRUD para las entidades anteriores. Adicionalmente deben poderse realizar consultas sobre jugadores y torneos por filtros. De los jugadores se tendrá que poder consultar los torneos en los que han participado (concepto nested resources o subresources).

Para ello deben estudiarse los siguientes contenidos:

- Diseño de un API REST (1h8min): https://www.udemy.com/course/aprende-a-disenar-una-api-restful-correctamente/


Nested resources:
https://www.moesif.com/blog/technical/api-design/REST-API-Design-Best-Practices-for-Sub-and-Nested-Resources/



Curso de Javascript:
https://www.studytonight.com/code/js-course/?ref=homecard

