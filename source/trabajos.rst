Trabajos Realizados
===================

----

.. note::

    Para obtener las credenciales de acceso a los distintos servicios y equipos, por favor consulta la guia de credenciales de acceso
    relativa a todos los servicios de DAETSAM. Si no sabes de que estoy hablando aqui, pregunta por delegación para que te
    den la información relativa a ese tema.

----

Equipos informaticos
--------------------
Una de las primeras tareas a realizar a la hora de comenzar la beca fue la limpieza (tanto hardware como software)
de los equipos de trabajo en delegación, puesto que llevaban mucho tiempo sin mantenimiento, con software desactualizado
y en algunos equipos había evidencias de posibles virus o malware presente.
Se formateo todos los equipos y se crearon dos grupos de equipos de trabajo: Mostrador (equipos orientados a atención
al público) y equipos de trabajo.

Software común a ambos tipos:

* Sistema operativo: Windows 10 Pro
* Microsoft Office Suite 2013
* Adobe reader
* Google Chrome & Mozilla Firefox
* TeamViewer (gestion de equipos en remoto)
* Adobe Photoshop 2015
* Autodesk Autocad 2016
* Skype
* Adobe Acrobat Pro

Software específico en equipos de trabajo:

* Adobe After Effects
* Adobe Illustrator
* Adobe InDesign
* Adobe PremierPro
* Sketchup 2016
* Autodesk Revit 2016
* Autodesk 3D Max 2016

Página web
----------
A finales del curso, se comenzaron a realizar los trabajo de renovacion de la plataforma web de Delegación. La web estaba alojada
en los servidores de la escuela en el dominio de: http://daetsam.aq.upm.es. El problema de esta arquitectura y servicio
es que no se tiene acceso total al servidor, solamente acceso FTP controlado desde una determinada ip. Por lo tanto, cuando
la web se cae o se corta el servicio de la misma, hay que comunicar a servicios informaticos del centro de cálculo para que
vuelvan a ponerla operativa, este proceso puede demorarse desde horas hasta dias en algunas ocasiones.
Por este motivo, se tomó la desición de mover la web (manteniendo la que estaba acualmente existente en los servidores del cdc)
hacia un servidor propio. Para ello, se contrato un servidor de tipo cloud con 1and1, esto permite tener una estructura
elástica que se puede redimensionar en condiciones de mucho tráfico web.

Estructura de la web, nuevo contenido, ideas que se tiene con ella, datos de acceso, roles



Adquisición de Servidor Principal
---------------------------------
Al comenzar con la gestión de la actualizacion de los servicios de la delegación, se disponia de un ordenador de sobremesa
convertido en servidor. El sistema estaba armado sobre un Windows 7 Home Edition, y constaba solamente de recursos compartidos
en red.
Se tomo la desición en junta, de renovar el servidor y por ello se compro un servidor profesional destinado para uso exclusivo
de Directorio Activo y recursos de red. Se ponderó la seguridad en la informacion y la integridad de los recursos. Para ello se le dotó
al servidor de un doble sistema de RAID1 con redundancia tanto en el sistema operativo, como en los datos (si un disco falla, puede seguir
funcionando, en este caso se incorporaria un segundo disco, y se restableceria el backup en ambos discos, por lo tanto, puede fallar
como maximo un disco de cada). Ademas, se valoró cuales eran las necesidades a futuro de los proximos años de la delegacion, y se decidio de
dotarle tambien de un hardware potente para afrontar dichas tareas, el servidor finalmente cuenta con los siguientes componentes:

* **Procesador:**
* **Memoria Ram:**
* **Placa Base:**
* **Disco duro (S.O):**
* **Disco duro (Archivos):**



Creacion de Active Directory
----------------------------

Adquisición de nuevo servidor web
---------------------------------

Creación de nuevos servicios web
--------------------------------

Nuevos servicios disponibles en Delegación de Alumnos ETSAM:

* `DAETSAM`_: Nueva página web de Delegación. Destinada a alojar todas las novedades
    en la ETSAM y demás noticias de interés para los alumnos de la escuela. De a poco
    se irán incorporando nuevos servicios y estructuras que ayuden a mejorar los servicios
    que se ofrecen.
* `Cursos`_: Debido a que la delegacion cuenta con una gran oferta de cursos, se tomó la desición
    de ir alojando en esta web toda la informacion relativa a los cursos. Una vez que se regularice
    la situación económica en las delegaciones de centro de la UPM se podrá optar por generar
    pagos online y reserva de los mismos de manera online, sin tener que acudir personalmente a
    la delegacion para la reserva o asignación de plazas para los mismos.
* `Agora`_: Agora es una de las novedades éste año. Es una plataforma joven, creada para una interacción
    muy dinámica por parte de la gente, de fácil utilización (su interfaz se parece mucho a facebook), y
    su finalidad es convertir ésta plataforma en una red social a nivel DAETSAM, en la cual publicar información
    relativa a eventos e información de interés para miembros de la delegación y público general de la escuela.

.. _DAETSAM: https://daetsam.es
.. _Cursos: https://cursos.daetsam.es
.. _Agora: https://agora.daetsam.es


Creación de arquitectura de red entre servicios
-----------------------------------------------

La arquitectura de la Red en DAETSAM ha quedado de la siguiente manera:

Listado de IP y equipos:

* **Mostrador 01:**
* **Mostrador 02:**
* **Equipo 01:**
* **Equipo 02:**
* **Equipo 03:**
* **Equipo 04:**
* **Servidor AD:**
* **Servidor BACKUP:**
* **Servidor WEB:**
* **Portatil ADMIN:**
