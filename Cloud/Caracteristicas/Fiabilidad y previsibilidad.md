Reliability and Predictability

### Fiabilidad
La nube tiene capacidades de auto arreglarse, es decir si un nodo o un rack fallo mi maquina virtual por ejemplo seria redesplegada automaticamente a otro nodo o rack dentro de la region o zona de disponibilidad que yo halla configurado, esto tambian pasa con el **almacenamieto** y muchos mas servicios.

El autoescalamiento de las aplicaciones tambien hace parte de esta fiabilidad

Azure esta diseñado para fallar, es decir que podemos configurar azure para tener un backup en otra region por si en mi region se llega a caer

Se tiene que monitorear las propias aplicacion (Application insights - Azure)

### Previsivilidad
Se puede saber cuales recursos son los que se van a utilizar o recursos que se estan utilizando en este momento

Comportamientos 

Usar templates para desplegar para que todo siempre despliegue de la misma manera asi sabemos como va a funcionar siempre

Automatizacion

Devops - Pipelines - CI/CD
