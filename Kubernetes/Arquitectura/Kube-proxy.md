Se asegura que las reglas necesarias esten implementadas en los **nodos trabajadores (worker nodes)** para permitir que los contenedores que esten corriendo en ellos se puedan comunicar entre si.

Kube-proxy es un proceso que corre en cada nodo de un cluster de kubernetes, su trabajo es buscar nuevos servicios y cada vez que un servicio es creado, lo busca y crea nuevas reglas apropiadas en cada nodo para reenviar el trafico de ese servicio a el pod adecuado.
![[Pasted image 20230218233411.png]]
