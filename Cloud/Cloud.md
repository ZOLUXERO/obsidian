[[Cloud/Azure/Azure]]
[[Aws]]

Que es la nube?
En la nube hay datacenters fisicos con cluster de servidores y racks con diferentes nodos.
La nube ofrece una cantidad de servicios muy grande como por ejemplo
- Almacenamiento (archivos, bases de datos etc)
- Capacidad de computo (VMs, servidores)
- Networking (redes al momento de conectar con azure o fuera de la compañia)
- Analiticas (monitoreo, logs y telemetria)
Todos estos servicios se proveen por internet

Para que realmente la nube se llame ***"la nube"*** debe cumplir con ciertos requisitos o caracteristicas que son los siguientes:
- [[Caracteristicas]]

Generalmente moverse a la nube es mas barato que mantener infraestructura propia esto es debido al concepto de Economias de escala (Entre mas grande la compañia mas barato puede llegar a ser el producto o el precio por unidad)

La nube usa un modelo a base de consumo

## Public cloud | Private cloud | Hybrid Cloud

### Public Cloud
- Azure es un ejemplo de public cloud
- La nube publica es OpEx
- Se accede desde internet
- Ilimitado
- Muchas Regiones
- Muchos Servicios (no estoy limitado por ejemplo a solo VMs)
- Agilidad
- Alta disponibilidad

### Private Cloud
- Tengo servidores fisicos
- Necesita una infraestructura por encima que maneja la nube privada (MGMT)
- La nube privada Es CapEx
- Tengo toda la libertad de configurarla como quiera
- Control sobre la seguridad y la infraestructura
- Azure puede ser una nube privada (Azure Stack, Azure Arc)
- Es dificil de manejar y requiere experticia

### Hybrid Cloud
- Es una combinacion de ambas 
- Digamos que ofresco cierto servicio desde mis servidores fisicos onpremise pero en tiempos donde la carga es alta utilizo los recursos de una nube publica
- Es dificil de manejar y requiere experticia
- Es el mas flexible de todos los modelos

