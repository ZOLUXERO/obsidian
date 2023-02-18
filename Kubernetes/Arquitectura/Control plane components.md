son los componentes que comprenden un cluster de kubernetes, es decir los que manejan y guardan informacion acerca de los diferentes nodos, que contenedor va en que nodo, en que momento se cargo etc.

la mayoria de lo que se menciono se guarda en un alamacen de llaves -> valores de alta disponibilidad llamado [[etcd]]

cuando las peticiones para cargar o eliminar un contenedor llega estos se manejan en el [[Kube-Scheduler]]

en kubernetes hay controladores que ser encargan de diferentes tareas [[Controller Manager]]