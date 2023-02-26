[Creación de una suscripción de Contrato de cliente de Microsoft - Azure Cost Management + Billing | Microsoft Learn](https://learn.microsoft.com/es-es/azure/cost-management-billing/manage/create-subscription)

Es muy parecido a los grupos de recursos en el sentido de que ud los puede editar, configurar poner limites y usar en donde se necesiten.

Un caso de uso seria algo como subscripciones por ambiente una subcripcion para un ambiente de pruebas y otra para un ambiente de produccion.

# Se puede usar ARM o Terraform para setear Suscripciones

### Tanto Azure Resource Manager (ARM) como Terraform permiten crear, modificar y administrar suscripciones en Azure.

En ARM, se puede crear una nueva suscripción utilizando una plantilla de Azure Resource Manager. La plantilla de Azure Resource Manager es un archivo JSON que define los recursos que se deben implementar en una suscripción.

En Terraform, se utiliza el proveedor de Azure para crear, modificar y administrar suscripciones en Azure. Puedes utilizar código de infraestructura en formato HCL para definir la configuración de la suscripción, incluidos los recursos que se deben implementar en la suscripción y las políticas de cumplimiento que se deben aplicar.