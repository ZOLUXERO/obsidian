[Administración de grupos de recursos: Azure Portal - Azure Resource Manager | Microsoft Learn](https://learn.microsoft.com/es-es/azure/azure-resource-manager/management/manage-resource-groups-portal)

Resource group estan para organizacion cuando se agrupan estos recursos se tiene que mirar primero si ellos comparten el mismo ciclo de vida.

==**USAR GRUPOS DE RECURSOS!!!** (para agrupar aplicaciones y sus configuraciones) ==
**SE PUEDEN DAR PERMISOS A UN USUARIO A CIERTO GRUPO** (un repo, un pipeline, control de acceso a grupos por rol)
**SE PUEDEN CREAR POLITICAS A UN GRUPO** (que un rol pueda crear solo ciertas cosas)
**PUEDO APLICAR UN PRESUPUESTO A UN GRUPO** (que solo se pueda gastar tanto dinero en cierto grupo)
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