[Administración de grupos de recursos: Azure Portal - Azure Resource Manager | Microsoft Learn](https://learn.microsoft.com/es-es/azure/azure-resource-manager/management/manage-resource-groups-portal)

Resource group es la agrupacion de recursos relacionados logicamente.
- Se puede agrupar recursos que comparten el mismo ciclo de vida es decir una aplicacion completa un ejemplo seria agrupar por ambientes dev, qa, produccion esto para poder aplicar diferentes scripts, politicas, reglas de seguridad y diferentes reglas de politicas de acceso. ==(Recomendado)==
- Se puede agrupar recursos por su tipo un ejemplo seria agrupar todas las bases de datos y todas las aplicaciones 
- Se puede agrupar recursos por departamento
- Se puede agrupar por tarifas
- Se puede agrupar por zonas
- Se puede agrupar por una combinacion de tarifas y zonas
![[Pasted image 20230302105215.png]]
![[Pasted image 20230302105912.png]]
==**USAR GRUPOS DE RECURSOS!!!** (para agrupar aplicaciones y sus configuraciones) ==
**SE PUEDEN DAR PERMISOS A UN USUARIO A CIERTO GRUPO** (un repo, un pipeline, control de acceso a grupos por rol)
**SE PUEDEN CREAR POLITICAS A UN GRUPO** (que un rol pueda crear solo ciertas cosas)
[**PUEDO APLICAR UN PRESUPUESTO A UN GRUPO**](https://youtu.be/7w88KBVesPI?list=PLGjZwEtPN7j-Q59JYso3L4_yoCjj2syrM&t=83) (que solo se pueda gastar tanto dinero en cierto grupo)
# Se puede usar ARM o Terraform para setear Grupos de recursos

Cuando creo cualquier recurso
- Maquina virtual
- Cuenta de alamacenamiento
- App service
Va a vivir en un grupo de recurso un grupo de recursos tiene su propia metadata

Un grupo de recursos puede tener multiple regiones y multiple tipos de recursos

No se puede tener un grupo de recursos dentro de otro

Puede mover recursos entre diferentes grupos

En el sigiuente ejemplo El NIC (Network interface card) se comunica con la VNET (Virtual Network) en otro grupo afuera del que pertenece
![[Pasted image 20230225163357.png]]

Ejemplo de como se ve en azure

![[Pasted image 20230225165112.png]]