Identificar el tipo de servicio correcto basado en el caso de uso

Como saber cual utilizar y cuando?

Cuando sea posible lo mejor es usar [[SaaS]] (Microsoft 365)
- **una solucion de mensajes, email etc.**

Quiero mover una aplicacion o mover data de onprimse a la nube Lift and shift
- [[IaaS]]

Si tengo un sitio web con Apache tomcat y quiero minimizar la responsabilidad que tengo
y la aplicacion es basada en la web Puedo usar [[PaaS]]
- **App services**

Si tengo un escenario donde tengo que correr un solo contenedor ej tengo una imagen de docker que necesito correr puedo usar [[PaaS]]
- **ACI (Azure Container Instance)**

Si tengo una arquitectura basada en microservicios que esta usando contenedores y necesito auto escalamiento necesito configuraciones e integracioes de redes mas complejas y completas, necesito hacer despliegues a gran escala puedo usar PaaS
- **AKS (Azure Kubernetes Service)**

Depronto necesito correr una funcion pequena de trabajo cada vez que un archivo se guarda en una cuenta de alamacenamiento o un mensaje se envia a una cola en este caso se puede usar [[Serverless computing]]
- **Functions**

Si quiero hacer un flow logico para un ejemplo cuando alguien reacciono un twitter se puede usar [[Serverless computing]] (con esto no necesita programar o codificar)
- **Logic apps**

![[Pasted image 20230301123548.png]]

Tambien existen servicios [[IOT]]