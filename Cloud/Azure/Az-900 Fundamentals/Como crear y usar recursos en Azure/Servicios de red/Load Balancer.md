### Caracteristicas
-   Distribuye el tráfico(NO WEB)
-   Admite escenarios de entrada y salida
-   Se usa para escenarios de alta disponibilidad
-   Permite aplicaciones TCP (protocolo de control de transmisión) y UDP (protocolo de datagramas de usuario)
-   Permite tráfico Interno(Internal Load Balancer) y Externo(Public Load Balancer)
-   Permite el reenvio de puertos(Port Forwarding)
-   Se puede escalar a millones de flujos

Distribuye el trafico sobre varios recursos, esto permite tener escalamiento horizontal(que es preferible al vertical) y alta disponibilidad.

Si se distribuye los recursos en diferentes [[Zonas de disponibilidad]] se puede lograr una disponiblidad del 99,99% que es lo mas recomendado para aplicaciones importantes.

Esto se debe a que el load balancer automaticamente checkea el estado de los componentes de la aplicacion a los que esta conectado, si por ejemplo una de las VMs
dejara de funcionar, automaticamente redirige el trafico a la que esta funcionando.
![[Pasted image 20230303164618.png]]
Cuando se construyen soluciones mas grande se deben separar los load balancer por tiers por ejemplo los componentes que manejan el trafico de una aplicacion web y otro tier para manejar el almacenamiento de data de una aplicacion==(Para manejar trafico de una aplicacion web es mejor usar Application Gateway)==
![[Pasted image 20230303164932.png]]