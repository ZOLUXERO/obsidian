[Introducción a Azure Arc - Azure Arc | Microsoft Learn](https://learn.microsoft.com/es-es/azure/azure-arc/overview)

==Azure Arc es un servicio de Azure que permite extender la administración y el control de sus recursos y aplicaciones a través de múltiples plataformas y entornos, incluidos los centros de datos onPremise, otros proveedores de nube y dispositivos. 
ej:
AWS, OnPremise, Kubernetes etc==

Con Azure Arc, los usuarios pueden registrar y administrar recursos externos, como servidores físicos, VMs (máquinas virtuales), contenedores y Kubernetes (clúster de contenedores), a través de Azure Portal, Azure CLI, Azure PowerShell y API de Azure. Los recursos registrados pueden beneficiarse de las políticas y herramientas de administración de Azure, como la implementación de actualizaciones de seguridad, el monitoreo de estado y la configuración de la política de cumplimiento.

### Azure Arc proporciona una manera centralizada y unificada de:
-   Administrar todo el entorno mediante la proyección de los recursos existentes que no son de Azure y los recursos locales en Azure Resource Manager.
-   Administrar las máquinas virtuales, los clústeres de Kubernetes y las bases de datos como si se ejecutaran en Azure.
-   Usar los servicios y funcionalidades de administración de Azure que conozca, independientemente de dónde se encuentren.
-   Seguir usando ITOps tradicionales al tiempo que presenta prácticas de DevOps para admitir en el entorno nuevos patrones nativos en la nube.
-   Configurar ubicaciones personalizadas como una capa de abstracción a partir del clúster de Kubernetes habilitado para Azure Arc y las extensiones de clúster.

ej:
![[Pasted image 20230226154620.png]]

Además, Azure Arc permite la implementación y administración de aplicaciones en Kubernetes en cualquier entorno, como la nube pública, la nube privada, el centro de datos onPremise.

Agente que esta en un servicio externo para usar politicas y funcionalidades configuradas en Azure en otras plataformas pueden ser otras nubes, onPremise etc.

![[Pasted image 20230226155821.png]]