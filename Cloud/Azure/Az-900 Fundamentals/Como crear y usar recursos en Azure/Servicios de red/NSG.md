Para agrupar reglas por Virtual Networks usar [[ASG]]
Los NSGs se pueden aplicar a la mayoria de servicios Azure que utilizan Vnets como:
- VMs
- Azure Kubernetes Service (AKS)
- Azure App Service Environments (ASE)
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