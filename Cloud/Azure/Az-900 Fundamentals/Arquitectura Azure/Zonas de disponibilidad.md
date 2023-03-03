Separa fisicamente los recursos en [[Regiones]] de Azure ej: una puede estar en los angeles,  miami y otra en new york con esto podemos lograr 99,99% 

Basicamente esto permite que si una zona se cae la otra responda por la que esta caida para que esto funcione se debe tener mas de una instancia separada en esas zonas de disonibilidad esto da **resilencia** a cualquier servicio si hay un problema a nivel de [[Data center]].
![[Pasted image 20230301183746.png]]
### Zonas redundantes
Existe zonas que son redundantes es decir que haran lo que se dijo arriba pero sin necesidad de decirle que tiene que hacerlo
![[Pasted image 20230301183933.png]]

# Se puede usar ARM o Terraform para setear Zonas de disponibilidad

En ARM, los recursos que admiten las zonas de disponibilidad se especifican utilizando la propiedad `availabilitySet` en la definición de la máquina virtual o el recurso que se desea implementar en una zona de disponibilidad. Al especificar el conjunto de disponibilidad en la plantilla de Azure Resource Manager, se puede garantizar que la máquina virtual o el recurso se implementen en una o más zonas de disponibilidad dentro de la región.

En Terraform, puedes utilizar el proveedor de Azure para crear y administrar recursos en una o más zonas de disponibilidad en una región determinada. El proveedor de Azure de Terraform proporciona recursos para crear y administrar conjuntos de disponibilidad en una o más zonas de disponibilidad, y puedes definir la ubicación de un recurso utilizando código de infraestructura en formato HCL.