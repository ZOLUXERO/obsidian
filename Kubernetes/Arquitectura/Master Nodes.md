Maneja, planea, monitorea y programa nodos

[[Control plane components]]

maneja y guarda informacion acerca de los diferentes nodos, que contenedor va en que nodo, en que momento se cargo etc, esto que se menciono se guarda en un alamacen de llaves -> valores de alta disponibilidad llamado [[etcd]]

cuando las peticiones para cargar o eliminar un contenedor llega estos se manejan en el [[Kube-Scheduler]]

en kubernetes hay controladores que ser encargan de diferentes tareas [[Controller Manager]]

para poder manejar un cluster un usuario externo debe poder ingresar a kubernetes para eso esta el [[Kube-apiserver]]