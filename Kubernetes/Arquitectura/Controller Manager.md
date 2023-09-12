DepBasicamente el controller manager tiene la finalidad de estar pendiente, monitorear y responder por el status de su respectiva tarea sea nodo, replica, deployment etc.

Un ejemplo seria el **Node-controller**
Que se encarga de monitorear el status de los nodos y tomar acciones necesarias para que la aplicacion corra si interrupcion hace eso atravez del kube-apiserver el node-controller checkea el status de los nodos cada 5 segundos, si para de recibir informacion va a esperar por 40 segundos y si no recibe informacion lo pone como "unreachable" si un nodo queda con estado de "unreachable" el controller le da 5 minutos para que se vuelva a reiniciar si no lo hace elimina el pod asigando a ese nodo y lo provisona en los que si funcionan si es que el pod hace parte de un replica-set
![[Pasted image 20230218225606.png]]
Otro ejemplo seria el **Replica-controller** su trabajo es asegurarse que el numero deseado de pods siempre este arriba en el set de replicas si un pod no responde crea uno nuevo.

### Tipos de controllers.
![[Pasted image 20230218224707.png]]