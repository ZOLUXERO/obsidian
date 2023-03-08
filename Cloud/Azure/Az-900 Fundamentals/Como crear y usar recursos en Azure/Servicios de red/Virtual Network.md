### [Como crear un Virtual Network](https://youtu.be/5NMcM4zJPM4?list=PLGjZwEtPN7j-Q59JYso3L4_yoCjj2syrM&t=265)
[Ejercicio: creación de una red virtual de Azure - Training | Microsoft Learn](https://learn.microsoft.com/es-es/training/modules/configure-network-for-azure-virtual-machines/3-exercise-create-azure-virtual-network)
Emula la infraestructura de una red
Permite crear, manejar, monitorear y asegurar conectividad entre recursos de azure.
### Caracteristicas
-   Permite aislar componentes de red lógicamente
-   Se puede segmentar en una o más subredes(subnet)
-   Las subredes(subnet) son secciones discretas
-   Habilita la comunicación de recursos entre sí, Internet y en las instalaciones
-   Alcance de una sola región
-   VNet peering(emparejamiento) permite la comunicación entre regiones
-   Es usado para aislar, segmentar, comunicar, filtrar y enrutar
### Subnet
- Permitir a los clientes manejar las direcciones IP de una manera mas eficiente
- Si se necesita un enrutamiento especifico entre servicios dentro de una subnet es buyeno usar [[User Defined Routes(UDR)]]
- Agrupar recursos relacionados para aplicar filtros y reglas de seguridad atraves de multiples recursos en una subnet, por ejemplo agrupando todos los recursos que alojan una aplicacion web y solo permitiendo trafico a esa subnet especifica
![[Pasted image 20230303162357.png]]
### [[NSG]](Network Security Group)
![[Pasted image 20230303163015.png]]
