Es el encargado de manejar la comunicacion con los master nodes, empezando por informarle a un nodo master que esta interesado en unirse al grupo, recibir informacion sobre los contenedores que se van a cargar, cargar los contenedores apropiados segun sea necesario, enviar reportes al nodo master acerca del worker node y el estado de los contenedores.

Este agente corre en cada uno de los nodos de un cluster escucha a las instrucciones que le de el [[Kube-apiserver]] y despliega o destruye contenedores en los nodos segun se requiera.

El Kubelet tambien da reportes acerca del nodo y los contenedores que se encuentran en el 