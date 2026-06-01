---
layout: src/layouts/PostCursadaLayout.astro
title: Semana 10
inicio: 2026-06-01
mostrar: true

descripcion: Mundo NoSQL. MongoDB y Mongoose. Más Docker
importante: El lunes 01 de Junio es la fecha limite de la entrega de los TPs del Mundo Relacional. Hay tiempo hasta las 18 hs de realizar la entrega.

horarios:
  - Comision: Comisión 1 T.Noche (Prof. Gerardo Gonzalez Tulian)
    Dia: 2026-06-01
    Modalidad: PRESENCIAL
    Hora: 18.15hs
    Aula: MA-110
    Edificio: Edificio Malvinas Argentinas

ejercicios:
  - name: EP-Mongo Introduccion
    verEjercicio: https://github.com/EP-UnaHur-2025C1/mongo-v1
    comentarios:
      - name: Repositorio generado en EP-Mongo Introduccion - Grabación Clase 2C-2025
  - name: EP-Mongo más Detalels
    verEjercicio: https://github.com/EP-UnaHur/apiMongoV1
    comentarios:
      - name: Repositorio usado en la Clase 1C-2026 con más detalles.
videos:
  - nombre: EP-Mongo Introduccion - Grabación Clase 2C-2025
    urlYoutube: https://www.youtube.com/watch?v=BEyaztGqFRk
---

- A partir de esta semana nos adentramos en el mundo de las bases de datos NoSQL. En particular, trabajaremos con MongoDB, una base de datos documental que almacena la información en documentos JSON-like, ofreciendo gran flexibilidad para modelar y gestionar datos.

- Como ya es habitual en la materia, utilizaremos Docker para simplificar la puesta en marcha del entorno de trabajo. Mediante un archivo Docker Compose podremos levantar tanto el servidor de MongoDB como una herramienta cliente en cuestión de segundos, permitiéndonos concentrarnos en el desarrollo de nuestras aplicaciones.

- Para conectar nuestras aplicaciones Node.js con MongoDB utilizaremos Mongoose, una biblioteca de modelado de datos ODM (Object Document Mapper). Mongoose proporciona una capa de abstracción sobre MongoDB que nos permite definir esquemas, validar datos y trabajar con documentos utilizando objetos JavaScript, facilitando así la interacción con la base de datos y el mantenimiento del código.

- Durante las próximas clases aprenderemos a definir modelos, realizar operaciones CRUD (Create, Read, Update y Delete), establecer relaciones entre documentos y aplicar buenas prácticas para el desarrollo de aplicaciones que utilizan MongoDB como sistema de persistencia.
