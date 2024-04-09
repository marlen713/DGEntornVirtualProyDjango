# DGEntornVirtualProyDjango


Desafío - Creando un entorno virtual para nuestro
proyecto Django
● Para realizar este desafío debes haber estudiado previamente todo el material
disponible en el LMS correspondiente a la unidad.
● Una vez terminado el desafío, comprime la carpeta que contiene el desarrollo de los
requerimientos solicitados y sube el .zip en el LMS.
● Desarrollo desafío: Individual
● Puntaje total: 10 puntos.
● Tiempo desarrollo: 90 a 120 minutos
● Para la realización del desafío deberás tener instalado en tu sistema operativo las
siguientes herramientas y programas utilitarios: python, pip y virtualenvwrapper
Descripción
Como profesional del desarrollo web con Django, probablemente te toque (o desees)
trabajar en más de un proyecto al mismo tiempo, lo cual plantea ciertas problemáticas como
el manejo de los módulos de python requeridos por cada proyecto.
Como vimos en la sesión anterior, un proyecto Django es un conjunto de aplicaciones que
tienen paquetes de python de los cuales dependen sus funcionalidades, por lo cual
normalmente distintos proyectos tendrán distintas dependencias, o al menos distintas
versiones de estas.
¡Importante! Las versiones utilzadas para este desafío, son para intencionar que es
posible tener, en un mismo proyecto de Django, múltiples aplicaciones y que estas
respondan a versiones distintas. Para obtener información de las últimas versiones
de Django, puedes consultar la documentación oficial.
_ 1
www.desafiolatam.com
Manejo de múltiples entornos virtuales y sus dependencias
Ya conoces los programas utilitarios pip y virtualenvwrapper y sus usos dentro de un
proyecto Django, es hora de ponerlos en práctica, recuerda que para instalar paquetes en un
entorno en específico, este debe encontrarse activado (Recuerda los pasos en la PPT para
activarlo).
Deberás crear 5 entornos virtuales distintos con los siguientes nombres:
1. ferretería
2. laesquina
3. onlyflans
4. prestobar
5. taller
Debe instalar las siguientes dependencias en cada uno de los entornos virtuales antes
nombrados:
● django 3.2
Para cada entorno virtual deberás instalar las siguientes dependencias:
● Para el entorno de ferreteria:
○ django 3.2.4
● Para el entorno de laesquina:
○ django en la última versión menor a 3
● Para el entorno onlyflans
○ django 3.2
● Para el entorno prestobar
○ astral en su última versión disponible
● Para el entorno de taller
○ pytz en su versión 2019.3
Para cada uno de los entornos virtuales, genere un respaldo de las dependencias en un
archivo llamado requirements-<nombre_entorno>.txt donde <nombre_entorno> es
reemplazado por el nombre del entorno virtual del cual proveen los entornos virtuales, por
ejemplo requirements-prestobar.txt
Luego de creados los archivos con extensión .txt se deben comprimir en 1 archivo zip
llamado requerimientos-desafio1.zip.
Como último paso, deberás crear un entorno virtual llamado calendariolunar en el cual
deberás instalar todos los requerimientos desde el archivo requirements.txt del proyecto,
una vez terminada esa tarea, deberás realizar un respaldo llamado
requirements-calendariolunar.txt
_ 2
www.desafiolatam.com
Requerimientos
1. Screenshot de la lista de todos los entornos virtuales creados
(2 Puntos)
2. Archivo requerimientos-desafio1.zip con respaldos de los requerimientos de todos
los entornos virtuales
(6 Puntos)
3. Archivo requirements-calendariolunar.txt con respaldo de requerimientos de entorno
virtual calendariolunar
(2 Puntos)
¡Mucho éxito!
Consideraciones y recomendaciones
Para la realización del desafío deberás tener instalado en tu sistema operativo las
siguientes herramientas y programas utilitarios: python, pip y virtualenvwrapper.
_  