### Arquitectura de un cluster
Los siguientes nodos se encargan de manejar un cluster de kubernetes
[[Master Nodes]]
[[Woker Nodes]]
![[Pasted image 20230218175257.png]]
![[Pasted image 20230218175734.png]]

Como hace kubernetes para comunicar la creacion de un nuevo pod?
ejemplo:

usando kubectl le pedimos que cree un nuevo pod, kubectl le comunica esto al kube-apiserver que se encarga de crar un pod sin asignarlo a un nodo y le comunica esto al etcd, el etcd actualiza la informacion y le retorna esto al kube-apiserver para que le avise al usuario que se creo el pod, el kube-scheduler se mantiene monitoreando el kube-apiserver al ver que hay un pod creado sin un nodo asignado el scheduler identifica el nodo correcto donde deberia ir el nuevo pod y le avisa al kube-apiserver el apiserver vuelve a actualizar la informacion en el etcd cluster y luego le pasa esa informacion al kubelet en el nodo trabajador(worker node) apropiado, el kubelet crea el pod en el nodo y le indica a docker que debe desplegar la imagen de la aplicacion, una vez hecho esto el kubelet actualiza el estado al kube-apiserver y el apiserver nuevamente actualiza la informacion en el etcd cluster ***(Cada vez que se pide algun cambio siempre sigue un patron muy parecido a este)***

El **KUBE-APISERVER** esta en el centro de todas las diferentes tareas que se necesitan hacer para realizar un cambio en un cluster.