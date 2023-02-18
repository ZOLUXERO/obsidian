Es el principal componente de gestión de Kubernetes, es responsable de orquestar todas las operaciones dentro del clúster.

Basicamente expone un api de kubernetes para ser usado por los usuarios externos para orquestar, monitorear un cluster

El kube-apiserver periodicamente obtiene informes de estado del [[kubelet]] para monitorear el status de los nodos y contenedores en ellos

Cuando se hacen peticiones para traer informacion de cualquier tipo el kube-apiserver trae la informacion de [[etcd]]

<font color="red">!IMPORTANTE</font>
El **KUBE-APISERVER** esta en el centro de todas las diferentes tareas que se necesitan hacer para realizar un cambio en un cluster.

### De que se encarga el kube-apiserver?
![[Pasted image 20230218185311.png]]