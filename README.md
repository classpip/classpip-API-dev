# Classpip API

## ¿Qué es Classpip?

[![Classpip Badge](https://img.shields.io/badge/classpip-dashboard-brightgreen.svg)](https://github.com/classpip/classpip-dashboard-dev)
[![Classpip Badge](https://img.shields.io/badge/classpip-movil--profesor-brightgreen)](https://github.com/classpip/classpip-movil-profesor-dev)
[![Classpip Badge](https://img.shields.io/badge/classpip-movil--estudiante-brightgreen)](https://github.com/classpip/classpip-movil-estudiante-dev)
[![Classpip Badge](https://img.shields.io/badge/classpip-server-brightgreen.svg)](https://github.com/classpip/classpip-server-dev)
[![Classpip Badge](https://img.shields.io/badge/classpip-API-brightgreen)](https://github.com/classpip/classpip-API-dev)
[![license](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/classpip/classpip/blob/master/LICENSE)


Classpip es una herramienta para introducir gamificación en el aula. La gamificación consiste en la introducción de las mecánicas típicas de los juegos en escenarios que no son juegos, para motivar a las personas a hacer cosas que quizá no tienen muchas ganas de hacer.

![classpip-arch](https://github.com/classpip/classpip/blob/master/classpip.png)

En la actualidad Classpip se compone de 5 aplicaciones, que se muestran en la figura, con una indicación de las tecnologías más importantes usadas en cada una de ellas. A continuación se describen esas aplicaciones y se proporcionan los enlaces a las versiones en desarrollo de cada una de ellas.
 
* *Classpip-dashboard*: Es la aplicación web con la que, desde su ordenador, el profesor puede tomar todas las decisiones sobre configuración de los juegos (por ejemplo, crear una colección nueva) e interacción con cada juego (por ejemplo, asignar puntos a los alumnos). 
[![Classpip Badge](https://img.shields.io/badge/classpip-dashboard-brightgreen.svg)](https://github.com/classpip/classpip-dashboard-dev)

* *Classpip-movil-profesor*: Es la aplicación mediante la cual el profesor puede hacer algunas funciones que resulta apropiado hacer desde un dispositivo móvil (por ejemplo, asignar cromos a alumnos concretos o consultar el ranking del juego de puntos).
[![Classpip Badge](https://img.shields.io/badge/classpip-movil--profesor-brightgreen)](https://github.com/classpip/classpip-movil-profesor-dev)

* *Classpip-movil-estudiante*: Es la aplicación mediante la cual el alumno interacciona con el juego (por ejemplo, consulta los puntos que tiene, intercambia cromos con los compañeros o responde a las preguntas de un juego de preguntas). 
[![Classpip Badge](https://img.shields.io/badge/classpip-movil--estudiante-brightgreen)](https://github.com/classpip/classpip-movil-estudiante-dev)
  
* *Classpip-API*: Es la aplicación que ofrece al resto de aplicaciones los servicios de acceso a datos en modo API-REST  (por ejemplo, obtener la lista de juegos de un grupo, o los cromos que tiene un alumno en su álbum).
[![Classpip Badge](https://img.shields.io/badge/classpip-API-brightgreen)](https://github.com/classpip/classpip-API-dev)
 
 * *Classpip-server*: Es la aplicación que realiza tareas de notificación entre los usuarios. Por ejemplo, recibe la notificación de que un alumno ha completado un cuestionario y remite esa notificación al Dash para que refleje esa circunstancia en el listado de alumnos que participan en el juego. También realiza tareas de registro de actividad (por ejemplo, registrar la creación de grupos o de juegos).
[![Classpip Badge](https://img.shields.io/badge/classpip-server-brightgreen.svg)](https://github.com/classpip/classpip-server-dev)

  

## Classpip-API
Este es el repositorio del código de la aplicación (en su versión en desarrollo) que permite exponer los datos en formato API-REST a las diferentes aplicaciones que los van a consumir (Dashboard, movil-profesor, movil-estudiante, etc.).

## Modelos de datos
Consulta aquí los [modelos de datos](https://github.com/classpip/classpip-API-dev/blob/master/ModelosClasspip.pdf) actuales usados en Classpip.

## Git y GitHub

Necesitarás instalarte Git y tener una cuenta en GitHub:
 
https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
 
https://github.com/

Debes crear una cuenta en Github para poder hacer contribuciones en el desarrollo del código de esta aplicación.

 
## NodeJS

Necesitas tener instalado NodeJS en la versión v10.13.0.
Comprueba que has instalado la versión correcta haciendo:

```
node -v
> v10.13.0
```

### Native addons on Linux (Ubuntu)

```
sudo apt-get install gcc g++ make
```

### Native addons on Windows
Instalalas con permiso de administrador
```
npm install -g windows-build-tools@5.1.0
```

## Strongloop y loopback

Instala las siguientes herramientas para gestionar los modelos de datos:

```
npm install -g strongloop@6.0.3
npm install -g loopback-cli@5.0.0
```

## Instalación de la aplicación

Para instalar la aplicación y organizar la información para futuras contribuciones hay que seguir los pasos del 1 al 6 del protocolo de instalación y contríbuciones que se encuentra aquí: https://github.com/classpip/classpip.

## Puesta en marcha
Por en marcha el servidor API-REST con el comando siguiente: 
```
npm run start
```
Podras navegar por los modelos de datos conectandote a: localhost:3000/explorer


