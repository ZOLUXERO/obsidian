Compute services es una categoria de servicios en azure que permite correr aplicaciones basadas en la nube.
[[Maquinas virtuales(VMs)]]
[[VMs Scale sets]]
[[Container Instances(ACI)]]
[[AKS]]
[[App Services]]
### Tabla Comparativa de servicios de computo y sus caracteristicas
![[Pasted image 20230302124021.png]]
### Cuando utilizar un servicio especifico? [Cual servicio Escoger](https://learn.microsoft.com/en-us/azure/architecture/guide/technology-choices/compute-decision-tree)
- [[Maquinas virtuales(VMs)]](IaaS): Cuando necesite software personalizado, requisitos personalizados, muy especializado y un alto grado de control
- [[VMs Scale sets]](IaaS): Cuando necesite auto-esclado de maquinas virtuales
- [[Container Instances(ACI)]](PaaS): Para alojar contenedores simples, fácil de comenzar
- [[AKS]](PaaS): Cuando necesite alojar y orquestar una gran cantidad de contenedores, altamente escalable y personalizable
- [[App Services]](PaaS): si necesita alojar aplicaciones web de manera rapida y sencilla esta es la mejor opcion
- Azure Functions (PaaS) (Función como servicio) (Serverless): micro/nanoservicios, excelente precio basado en el consumo, fácil de comenzar *(No deberia usar Azure functions para crear servicios o aplicaciones web de ningun tamaño pero si sirven como un buen complemento a estos)

![[Pasted image 20230302125048.png]]
