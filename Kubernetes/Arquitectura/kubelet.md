Es el encargado de manejar la comunicacion con los master nodes, empezando por informarle a un nodo master que esta interesado en unirse al grupo, recibir informacion sobre los contenedores que se van a cargar, cargar los contenedores apropiados segun sea necesario, enviar reportes al nodo master acerca del worker node y el estado de los contenedores.

Tambien se comunica con el contenedor para pedirle que baje cierta imagen y corra una instancia, el kubelet despues sigue monitoreando el estado del nodo, pod o contenedor en el y le da reportes a el kube-apiserver en un tiempo estimado.

Este agente corre en cada uno de los nodos de un cluster escucha a las instrucciones que le de el [[Kube-apiserver]] y despliega o destruye contenedores en los nodos segun se requiera.
