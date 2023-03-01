[[Azure]]
[[Aws]]

Que es la nube?
En la nube hay datacenters fisicos con cluster de servidores y racks con diferentes nodos.
La nube ofrece una cantidad de servicios muy grande como por ejemplo
- Almacenamiento
- Capacidad de computo (VMs)
- Networking (redes)
- Analiticas (monitoreo, logs)
Todos estos servicios se proveen sobre internet

Para que realmente la nube se llame la nube debe cumplir con ciertos requisitos que son los siguientes:
- Alta disponibilidad
- Escalabilidad
- Elasticidad
- Agilidad
- Recuperación ante desastres

Generalmente moverse a la nube es mas barato que mantener infraestructura propia

## Public cloud | Private cloud | Hybrid Cloud

### Public Cloud
- Azure es un ejemplo de public cloud
- La nube publica es OpEx
- Se accede desde internet
- Ilimitado
- Muchas Regiones
- Muchos Servicios (no estoy limitado por ejemplo a solo VMs)

### Private Cloud
- Tengo servidores fisicos
- Necesita una infraestructura por encima que maneja la nube privada (MGMT)
- La nube privada Es CapEx
- Tengo toda la libertad de configurarla como quiera
- Azure puede ser una nube privada (Azure Stack, Azure Arc)

### Hybrid Cloud
- Es una combinacion de ambas 
- Digamos que ofresco cierto servicio desde mis servidores fisicos onpremise pero en tiempos donde la carga es alta utilizo los recursos de una nube publica

