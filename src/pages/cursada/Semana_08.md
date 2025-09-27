---
layout: src/layouts/PostCursadaLayout.astro
title: Semana 8

inicio: 2025-09-27

importante: En esta semana estamos dejando disponible el primer TP Grupal que se deberá entregar antes de la clase del Lunes 20-Octubre-2025. Vayan cerrando y registrando cuanto antes los grupos en la planilla que se encuentra debajo . La plataforma elegida para presentar los TP también es Github classroom. La creación de los grupos se hace en el paso de "Aceptar asignación" la primera vez y lo debe hacer uno de los integrantes del grupo. Luego, el resto del grupo se unen eligiéndolo de la lista de grupos disponibles, también en el paso de "Aceptar asignación". Para los siguientes TP, ya les quedará asociado el usuario de github a un grupo, y solo un docente podrá cambiarlos o quitarlos de ese grupo.

descripcion: Profundizamos sobre relaciones en sequelize. Lazy vs Eager

horarios:
  - Comision: Comisión 1 T.Noche (Prof. Gerardo Gonzalez Tulian)
    Dia: Lunes 29 de Septiembre
    Modalidad: PRESENCIAL
    Hora: 18.10 hs
    Aula: MA-108
    Edificio: Edificio Malvinas Argentinas

  - Comision: Comisión 2 T.Noche (Prof. Lucas Figarola)
    Dia: Lunes 29 de Septiembre
    Modalidad: VIRTUAL
    Hora: 18.10 hs
    URL: https://meet.google.com/irv-giiv-wjd

videos:
  - nombre: EP - Presentación del TP - Gerardo (Cuatri Pasado)
    urlYoutube: https://www.youtube.com/watch?v=TdQgyjJ5Ems
  - nombre: Relaciones 1 a N - Gerardo (Cuatri Pasado)
    urlYoutube: https://www.youtube.com/watch?v=ERpnnth95ho
  - nombre: Relaciones N to M - Gerardo (Cuatri Pasado)
    urlYoutube: https://www.youtube.com/watch?v=DCttD9Nyz-U

ejercicios:
  - name: Anti-Social-Relational (TP Grupal )
    classroom: https://classroom.github.com/a/F3f9PyrQ
    repoUrl: 'EP-UnaHur-2025C2/Anti-Social-Relational' # Acá va la URL del repo sin el "https://github.com/"
    defaultBranch: 'main' # Acá va la rama default del repo
    fechaDeEntrega: Lunes 20-10 18:00 hs
    comentarios:
      - name: INSTRUCCIONES-> Un/a integrante del grupo acepta la asignación y procede a dar de alta el grupo (tengan acordado el nombre previamente), luego el resto de los/as integrantes también aceptan la asignación, y se unen a su grupo. La entrega la realizan haciendo push al reposotorio grupal desde cualquiera de los usuarios github del grupo. Podrán hacer los push hasta la fecha/hora límite indicada.
    obligatorio: true
---

- Link a la planilla donde deberan cargar de <a href="https://docs.google.com/spreadsheets/d/1rSvCLZnaDNMutM-jiGjlvfJG1BaK5Q9tJmYfS25i2tE/edit?usp=sharing" target="_blank">Equipos</a>

- Esta semana continuamos aprendiendo sobre las relaciones entre los modelos de sequelize. Nos focalizaremos en la relaciones One-To-Many y Many-to-Many con su correspondiente formas de acceder: lazy vs eager

- Vamos a continuar desarrollando una API que usará las distintas asociaciones que vayamos configurando y creando durante la clase.

- Recomendamos simpre revisar la documentación official para encontrar las ultimas actualizaciones. <a href="https://sequelize.org/docs/v6/core-concepts/assocs/" target="_blank"> Associations</a>
