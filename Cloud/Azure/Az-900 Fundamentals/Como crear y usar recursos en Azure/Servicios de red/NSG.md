Para agrupar reglas por Virtual Networks usar [[ASG]]
Los NSGs se pueden aplicar a la mayoria de servicios Azure que utilizan Vnets como:
- VMs
- Azure Kubernetes Service (AKS)
- Azure App Service Environments (ASE)

### Como crear una maquina virtual y configurar un nsg desde azure cli:
https://learn.microsoft.com/es-es/training/modules/secure-network-connectivity-azure/6-configure-access-network-security-group
### Creación y administración de grupos de seguridad de red:
ACA HAY EJEMPLOS DE COMO CREAR UNA 
- VNET
- SUBNET
- NSG
- VMs
- ASG
- Como setear reglas NSG y ASG
usando Azure Cli
https://learn.microsoft.com/es-es/training/modules/secure-and-isolate-with-nsg-and-service-endpoints/3-exercise-network-security-groups
### Como crear un punto de conexión de servicio de red virtual de una aplicacion a un storage service:
- Una cuenta de almacenamiento deberia denegar todo el trafico y solo permitir el de la aplicacion
- Como montar un recurso compartido de archivos Azure
https://learn.microsoft.com/es-es/training/modules/secure-and-isolate-with-nsg-and-service-endpoints/5-exercise-vnet-service-endpoints

### [Como usar NSG](https://youtu.be/w8H5fWBHddA?list=PLGjZwEtPN7j-Q59JYso3L4_yoCjj2syrM&t=103)
- ==Permite hacer configuraciones para permitir o denegar trafico a recursos en una virtual network en Azure==
-   Filtrado controlado por **reglas**
-   Posibilidad de tener **múltiples** **reglas** de entrada y salida
-   Las reglas se crean especificando
    -   **Origen** / **Destino** (direcciones IP, etiquetas de servicio, grupos de seguridad de aplicaciones)
    -   **Protocolo** (TCP, UDP, cualquiera)
    -   **Puerto** (o intervalos de puertos, por ejemplo, 3389 – RDP, 22 – SSH, 80 HTTP, 443 HTTPS)
    -   **Dirección** (entrante o saliente)
    -   **Prioridad** (orden de evaluación)
![[Pasted image 20230304171545.png]]