### [Como usar UDR](https://youtu.be/BUH9kVTrM-8?list=PLGjZwEtPN7j-Q59JYso3L4_yoCjj2syrM&t=128)
Sirve para sobreescribir el enrutamiento por defecto de Azure o para añadir nuevas rutas, esto se maneja con un recurso en Azure llamado Route Table:
- Estos Ruote Tables estan asociados con 0 o mas Vnet subnets
- Un caso de uso seria el siguiente donde ud quiere sobreescribir el routing por default que tiene azure para que todo el trafico pase primero por un firewall
![[Pasted image 20230304195554.png]]