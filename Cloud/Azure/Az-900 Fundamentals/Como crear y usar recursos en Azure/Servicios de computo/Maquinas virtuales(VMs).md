### [Como crear una maquina virtual](https://youtu.be/inaXkN2UrFE?list=PLGjZwEtPN7j-Q59JYso3L4_yoCjj2syrM&t=290)
La virtualizacion ==es la emulacion de maquinas fisicas==, nos da la habilidad de crear diferentes configuraciones de hardware por maquina/app tambien podemos instalar diferentes sistemas operativos por maquina/app la ventaja que nos da esto es la separacion de ambientes donde cada uno de ellos tendra sus puertos, file systems, servicios, middleware y configuraciones
Tambien existen [[VMs Scale sets]]
![[Pasted image 20230302112413.png]]
Las maquina virtuales es un servicio de tipo IaaS

Los escenarios en los que se utilizan una VM generalmente son:
- Un requerimiento de software con una configuracion de sistema custom
- Lift and shift Escenarios

### Ejemplo de recursos necesarios para una maquina virtual bajo un grupo de recursos de Azure
La mejor practica seria usar grupos de recursos para ordenar todos los recursos que necesita una maquina virtual o ambiente.
[Información general sobre las máquinas virtuales en Azure - Azure Virtual Machines | Microsoft Learn](https://learn.microsoft.com/es-es/azure/virtual-machines/overview)
![[Pasted image 20230226160642.png]]