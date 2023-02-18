Es una herramienta que se utiliza para ejecutar comandos en un cluster.

Esta herramienta se usa desde la terminal y se comunica con el kube-apiserver de un cluster para traer informacion o ejecutar comandos de monitoreo, configuracion o programacion de un cluster.

Cuando se le pide a kubectl que traiga alguna informacion especifica el se comunica con el kube-apiserver que a su vez se comunica con etcd para traer la informacion solicitada.

Kubectl es la herramienta mas facil para controlar cluster pero no es la unica, tambien se puden hacer peticiones directas al kube-apiserver.