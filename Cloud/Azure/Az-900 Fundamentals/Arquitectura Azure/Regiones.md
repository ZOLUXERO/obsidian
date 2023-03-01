Las Regiones estan distribuidas globalmente y existen [[Pares de regiones]]

La region se puede escoger para desplegar las aplicaciones

Para definir la region la mejor metrica que se puede usar es la latencia para saber cual elegir existen herramientas como estas:
[Azure Speed test](http://azurespeedtest.azurewebsites.net/)
[Productos por region](https://azure.microsoft.com/en-us/explore/global-infrastructure/products-by-region/?regions=us-east-2,us-east&products=all)

Cada región de Azure se nombra de manera única, por ejemplo, "East US" o "West Europe". Para garantizar la redundancia geográfica y la alta disponibilidad, cada región está emparejada con otra región en la misma área geográfica, como "West US" y "East US 2". Azure actualmente tiene 33 pares de regiones en todo el mundo.

#### Al utilizar pares de regiones en Azure, los clientes pueden implementar soluciones empresariales altamente disponibles y resistentes a fallos.

# Se puede usar ARM o Terraform para setear Regiones
En ARM, la creación de recursos de Azure en una región determinada se realiza al especificar la ubicación del recurso en la plantilla de Azure Resource Manager. La especificación de la ubicación en la plantilla indica a Azure en qué región crear el recurso.
- Para declarar pares de regiones en ARM, puedes especificar la ubicación de los recursos en cada una de las regiones emparejadas.

En Terraform, puedes utilizar el proveedor de Azure para crear y administrar recursos en una región específica. El proveedor de Azure de Terraform proporciona recursos para crear y administrar recursos en una región específica, y puedes definir la ubicación de un recurso utilizando código de infraestructura en formato HCL.
- Para declarar pares de regiones en Terraform, puedes utilizar el recurso `azurerm_resource_group`