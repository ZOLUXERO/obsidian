Identifica el nodo correcto para colocar un contenedor enbase a los requisitos de recursos de los contenedores, la capacidad de los nodos trabajadores o cualquier otra política o restricción, como manchas y tolerancias o reglas de afinidad entre otros nodos.

#### El scheduler revisa cada pod y le asigna el mejor nodo en el que se puede poner en base a unos calculos ej:
El scheduler mira que el pod tiene un requerimiento de 10 CPUs el filtra los nodos existentes y escoje los que cumplan los requerimientos del pod, despues de eso con los nodos restantes les da un ranking de 0 a 10 un ejemplo seria que el scheduler calcula los recursos diponibles en el nodo despues de poner el pod en ellos, es decir si hay un nodo con 12 CPUs y uno con 16 le va a dar un mejor ranking al de 16 para poner el pod.
![[Pasted image 20230218231208.png]]

<font color="red">!IMPORTANTE</font>
Ud puede customizar e incluso escribir su propio scheduler con sus propias reglas

#### ==El Scheduler solamente es responsable de decidir cual pod va en cual nodo, el scheduler no se encarga de poner el pod en el nodo, ese trabajo es del Kubelet==