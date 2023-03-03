Si se habla de distribucion de trafico web(HTTP) usualmente la mejor opcion es usar Application Gateway esto es por que el application gateway ==esta diseñado para soportar trafico web== tiene mas caracteristicas que permiten a los usuarios manejar de mejor manera su trafico web

Cuando se construyen soluciones mas grande se deben separar el application gateway y los load balancers por tiers por ejemplo los componentes que manejan el trafico de una aplicacion web y otro tier para manejar el almacenamiento de data de una aplicacion
![[Pasted image 20230303170126.png]]

### Caracteristicas
-   Distribuye el tráfico web
-   Sirve como firewall de aplicaciones web
-   Se puede redireccionar
-   Afinidad de sesión
-   Se pueden enrutar URLs
-   <font color="red">!IMPORTANTE</font> Terminación SSL(permite desencriptar trafico en el application gateway y enviar una version desecriptada del request al servicio backend, esto para reducir el procesamiento requerido al desencriptar cada request que llega al backend aumentado aun mas la escalabilidad de la aplicacion)
	- ![[Pasted image 20230303170726.png]]