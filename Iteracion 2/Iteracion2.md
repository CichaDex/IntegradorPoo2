# PartyUp

## Grupo: Los recursantes

1. Candia Edgar Natán
2. Cichanowski Luis Jonatan
3. Delgado José Emanuel
4. Flores Luciano Adrian

## ¿Qué es "PartyUp"?

"PartyUp" es una aplicación web encargada de la publicación de diferentes clases de eventos alrededor de todo el mundo. Cualquier persona puede crear
un evento y publicarlo en PartyUp desde cualquier parte del mundo. De esta manera, los usuarios podrán promocionar y hacer públicos sus eventos, 
así como también conocer y asistir a otros. PartyUp brinda a los usuarios la capacidad de suscribirse de manera gratuita a sus eventos favoritos,
lo cual le permitirá estar al tanto de las noticias y actualizaciones del mismo.

## Lista de Características Claves:

  * El usuario podrá registarse en el sistema de forma gratuita.
  * Crear y publicar tus propios eventos.
  * Ubicar los eventos en un mapa interactivo.
  * Buscar eventos por localización, fecha, categoría, entre otros parámetros de búsqueda.
  * Suscribirse a eventos para recibir notificaciones sobre actualizaciones del mismo.
  * Firmar asistencia a un evento, con lo cual PartyUp brindará recordatorios del mismo.
  * Compartir eventos mediante distintas redes sociales.
  * Los creadores de eventos podrán promocionar sus eventos realizando transferencias.
  * Agregar eventos a favoritos.
  * Reportar un evento.
  * Recomendaciones de eventos similares.

## Lista de Características Extendidas:

  * Soporte para móvil. 
  * Publicar fotos propias sobre eventos a los que se ha asistido.
  
## Análisis de Dominio

![alt text](https://github.com/CichaDex/IntegradorPoo2/blob/master/Iteracion 2/Modelo de Dominio.jpg "Análisis de Dominio")

## Bocetos de interfaz de Usuario


![alt text](https://github.com/CichaDex/IntegradorPoo2/blob/master/Iteracion 2/Bocetos/Page_1.png "Pantalla principal")

![alt text](https://github.com/CichaDex/IntegradorPoo2/blob/master/Iteracion 2/Bocetos/Page_2.png "Evento Detallado")


## Casos de Uso


### Actores

1. Usuario: es cualquier persona que acceda a la aplicación y haga uso de sus funciones.
2. Sistema: el sistema realizará determinadas funciones cuando se den determinados factores.


__Calificar Evento__

__Actores__: Usuario

__Objetivo__: Guardar una calificación del usuario para promediar la calificación/reputación del Evento y de su creador.

__Flujo Principal__:

1. El usuario ingresa a la informacion detallada de un evento y hace click en el boton Calificar
2. El sistema solicita al usuario un puntaje y un comentario.
3. El usuario ingresa la información solicitada y confirma la acción.
4. El sistema procesa la información y añade una nueva calificación al evento correspondiente, actualiza la calificación
promedio del evento y la reputación del creador del mismo.


__Enviar Notificaciones__

__Actores__: Sistema

__Objetivo__: Notificar a los usuarios suscritos a cierto evento que el mismo se ha actualizado o tiene nuevas noticas.

__Flujo Principal__:

1. Este caso de uso es llamado por otros casos de uso y el sistema envía un correo y/o notificación Push 
(En caso de tener la app instalada), conteniendo informacion proveniente del caso de uso que lo invoca, a ciertos usuarios.


__Listar Eventos__

__Actores__: Sistema

__Objetivo__: Mostrar en pantalla eventos que cumplan con ciertos parámetros/filtros.

__Flujo Principal__:

1. El usuario ingresa a una página y el sistema busca los eventos que coinciden con los filtros proporcionados, tales como destacados,
recomendados, favoritos, etc.
2. El sistema muestra información de dichos eventos.


__Reportar Evento__

__Actores__: Usuario

__Objetivo__: Guardar un reporte/denuncia del usuario para analizar y revisar un determinado Evento y su creador.

__Flujo Principal__:

1. El usuario ingresa a la informacion detallada de un evento y hace clic en el boton Reportar Evento.
2. El usuario ingresa un titulo y una descripcion del reporte y lo confirma.
3. El sistema almacena el reporte asociado al evento.
4. Si se encuentran registrados muchos reportes del mismo evento, el sistema notifica a un supervisor.

__Modificar Evento__

__Actores__: Usuario

__Objetivo__: Modificar un evento existente y notificar de los cambios a sus seguidores.

__Flujo Principal__:

1. El usuario hace clic en modificar evento e ingresa a la pantalla de Modificar Evento, modifica los datos que desee
y confirma los cambios realizados.
2. El sistema guarda los cambios del evento y ejecuta el caso de uso Enviar Notificacion, teniendo en cuenta que la 
acción realizada fue la modificación de un evento y los usuarios a los cuales debe notificar son los suscriptores del mismo.

__Enviar Comentario__

__Actores__: Usuario

__Objetivo__: Agregar un comentario a un evento y envia una notificacion al creador del evento.

__Flujo Principal__:

1. El usuario ingresa texto en la casilla de comentarios de un evento, y lo envía.
2. El sistema actualiza la casilla de comentarios del evento y ejecuta el caso de uso Enviar Notificación, teniendo en
cuenta que la acción realizada fue una publicación de comentario, y el usuario al cual debe notificar es el creador del evento.

## Documentación Interfaz (API)


## Diagrama de Clases


## Javadoc


## Arquitectura

- HTML5
- Bootstrap (fw{html5,js, css})
- Javascript
- CSS
- Jquery
- JSON
- PHP
- Laravel(fw{php})
- SQL
