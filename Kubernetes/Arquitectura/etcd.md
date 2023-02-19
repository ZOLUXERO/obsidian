Basicamente funciona como una base de datos que guarda informacion en formato `llave -> valor`
- Simple
- Seguro
- Rapido

Etcd se pude manejar como una base de datos con comandos como set and get etc.

Cada comando que ud hace sea actualizar un nodo, desplegar un pod, replica set etc, una vez es actualizado en el etcd cluster solo ahi el cambio se considera completo.

## ejemplo de algunos comandos para ectd v2 y v3:
### v2 
```
1.  etcdctl backup
2.  etcdctl cluster-health
3.  etcdctl mk
4.  etcdctl mkdir
5.  etcdctl set
```
### v3
```
1.  etcdctl snapshot save
2.  etcdctl endpoint health
3.  etcdctl get
4.  etcdctl put
```