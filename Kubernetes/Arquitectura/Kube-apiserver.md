es el principal componente de gestión de Kubernetes, es responsable de orquestar todas las operaciones dentro del clúster.

basicamente expone un api de kubernetes para ser usado por los usuarios externos para orquestar, monitorear un cluster

el kube-apiserver periodicamente obtiene informes de estado del [[kubelet]] para monitorear el status de los nodos y contenedores en ellos