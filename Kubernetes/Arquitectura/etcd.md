Basicamente funciona como una base de datos que guarda informacion en formato `llave -> valor`
- Simple
- Seguro
- Rapido
etcd se pude manejar como una base de datos con comandos como set and get etc.

cada comando que ud hace sea actualizar un nodo desplegar un pod, replica set etc, una vez es actualizado en el etcd server el cambio se considera completo.