
Crea un pod con imagen nginx
```
kubectl run nginx (--image=nginx)
```
Genera un archivo yml para un pod
```
kubectl run nginx <--image=nginx> --dry-run=client -o yaml
```
Con el -o wide da tambien alguna informacion detallada
```
kubectl get pods (-o wide)
```
Da informacion detallada de los pods se puede debugear con esto el estado y mas
```
kubectl describe pod (myapp-pod) 
```
Crea un nodo basado en la definicion del archivo yml
```
kubectl create (-f pod-definition.yml)
```
Es muy parecido a create
```
kubectl apply (-f pod-definition.yml) 
```
Elimina un pod en kubernetes
```
kubectl delete pod (webapp) (-f filename.yml)
```
Actualiza un replica set con nuevos parametros
```
kubectl replace (-f replica-definition.yml)
```
Escala las replicas de un nodo
```
kubectl scale --replicas=6 (-f replica-definition.yml) (replicaset <myapp-replicaset>)
```
Trae informacion de una replica
```
kubectl get replicaset
```
Abre el archivo de configuracion con el que se creo para ser editado cuando se hace esto hay que eliminar los pods antiguos para que tome el cambio
```
kubectl edit replicaset <new-replica-set> 
```
Trae la informacion de todos los nodos deployment y replicaset
```
kubectl get all
```
Trae la informacion de los deployment
```
kubectl get deployment
```
Crea un deployment
```
kubectl create deployment <--image=nginx nginx>
```
Genera un archivo yml para un deployment
```
kubectl create deployment <--image=nginx nginx --dry-run=client -o yaml>
```
Crear un archivo yml con replicas
```
kubectl create deployment (--image=nginx nginx --replicas=4 --dry-run=client -o yaml > nginx-deployment.yaml)
```
Mostrar opciones de ayuda deployment
```
kubectl create deployment --help
```