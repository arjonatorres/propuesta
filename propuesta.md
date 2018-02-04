% ArTiKa
% Jose Carlos Arjona Torres
% Curso 2017/18

# Descripción general del proyecto

El proyecto ArTiKa consiste en una aplicación web, a través de la cual se podrá gestionar la seguridad de una vivienda y de sus alrededores, haciendo uso del control domótico a distancia, videovigilancia y avisos de peligro o sucesos de robos y similares.

## Funcionalidad principal de la aplicación

La principal función de la aplicación es la de crear una solución domótica para una vivienda. Cada usuario registrado dispondrá de una casa, dentro de ella podrá crear zonas (planta alta, planta baja, exteriores...), creando habitaciones en dichas zonas e incorporando módulos domóticos a cada una de esas estancias de la vivienda.

También existirá un tablón con publicaciones referentes a la seguridad, a través del cual se podrán notificar actos vandálicos, robos y demás hechos relacionados con la seguridad que puedan interesar al resto de usuarios. Este tablón podrá ser consultado por cualquier visitante sin necesidad de estar registrado, aunque sí habrá que estarlo para poder publicar.

Los usuarios también podrán enviarse mensajes privados entre ellos.

La aplicación la gestionará un administrador que tendrá el control absoluto sobre las viviendas, el tablón y sus publicaciones, pudiendo en todo caso modificar y eliminar cualquier mensaje improcedente. También podrá consultar en un mapa la ubicación de las viviendas de los usuarios.

## Objetivos generales

Los objetivos generales de la aplicación son:

* La gestión de los usuarios
* Gestionar la vivienda de cada usuario
* Gestionar los módulos de domótica instalados
* Gestionar el tablón de publicaciones
* Gestionar los mensajes privados entre usuarios
* La gestión de la aplicación por parte del administrador

# Elemento de innovación

En esta aplicación se usará la API de Google Maps para la geolocalización y su posterior visualización por parte del administrador.

También se usará la plantilla avanzada del Framework Yii2, que divide la aplicación en dos, una parte de front-end destinada a los usuarios normales, y una parte de back-end destinada al administrador.
