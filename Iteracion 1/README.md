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

## Características:

  * El usuario podrá registarse en el sistema de forma gratuita.
  * Crear y publicar tus propios eventos.
  * Ubicar los eventos en un mapa interactivo.
  * Buscar eventos por localización, fecha, categoría, entre otros parámetros de búsqueda.
  * Suscribirse a eventos para recibir notificaciones sobre actualizaciones del mismo.
  * Firmar asistencia a un evento, con lo cual PartyUp brindará recordatorios del mismo.
  * Compartir eventos mediante distintas redes sociales.
  * Los creadores de eventos podrán promocionar sus eventos realizando transferencias.
  * Soporte para móvil. **Próximamente**
  * Publicar fotos propias sobre eventos a los que se ha asistido. **Próximamente**
  
## Análisis de Dominio



## Bocetos de interfaz de Usuario


![alt text](https://github.com/CichaDex/IntegradorPoo2/blob/master/Bocetos/Page_1.png "Pantalla principal")

![alt text](https://github.com/CichaDex/IntegradorPoo2/blob/master/Bocetos/Page_2.png "Detalle de evento")


## Casos de Uso

- Calificar Evento
- Enviar Notificaciones
- Listar Eventos
- Reportar Evento

### Actores

1. Usuario: es cualquier persona que acceda a la aplicación y haga uso de sus funciones.
2. Sistema: el sistema realizará determinadas funciones cuando se den determinados factores.


__Calificar Evento__

__Actores__: Usuario

__Objetivo__: Guardar una calificación del usuario para promediar la calificación/reputación del Evento y de su creador.

__Flujo Principal__:

1. El sistema solicita información al usuario.
2. El usuario ingresa la información solicitada y confirma la acción.
3. El sistema procesa la información y añade una nueva calificación al evento correspondiente.
4. El sistema actualiza la calificación promedio del evento.
5. El sistema actualiza la reputación del creador del evento.


__Enviar Notificaciones__

__Actores__: Sistema

__Objetivo__: Notificar a los usuarios suscritos a cierto evento que el mismo se ha actualizado o tiene nuevas noticas.

__Flujo Principal__:

1. El sistema busca los usuarios suscritos al evento que se ha modificado.
2. El sistema envía un correo y/o notificación Push (En caso de tener la app instalada) a dichos usuarios.


__Listar Eventos__

__Actores__: Sistema

__Objetivo__: Mostrar en pantalla eventos que cumplan con ciertos parámetros/filtros.

__Flujo Principal__:

1. El sistema busca los eventos que tengan maás coincidencia con los filtros proporcionados.
2. El sistema muestra información breve de los eventos de determinada manera, dependiendo del menú en donde se llame el Caso de Uso.


__Reportar Evento__

__Actores__: Usuario

__Objetivo__: Guardar un reporte/denuncia del usuario para analizar y revisar un determinado Evento y su creador.

__Flujo Principal__:

1. El sistema solicita información al usuario.
2. El usuario ingresa la información necesaria y confirma el reporte.
3. El sistema almacena el reporte asociado a un evento.
4. Si se encuentran registrados muchos reportes del mismo evento, el sistema notifica a un supervisor.


## Arquitectura

- ...
- ...
- ...
- ...