**az-900 -> az-104 -> az-400**

<font color="red">!IMPORTANTE</font>
- **USAR GRUPOS DE RECURSOS!!!** (para agrupar aplicaciones y sus configuraciones)

- **USAR AZURE CLI** o [AZURE CLOUD SHELL](https://youtu.be/8JHY0xPssb8?list=PLGjZwEtPN7j-Q59JYso3L4_yoCjj2syrM&t=353)

- USAR Azure Advisor **ofrece recomendaciones prácticas para ayudarlo a optimizar sus recursos de Azure en términos de confiabilidad, seguridad, excelencia operativa, rendimiento y costo** [Como usar Azure advisor](https://youtu.be/58_6MkB2znI?list=PLGjZwEtPN7j-Q59JYso3L4_yoCjj2syrM&t=95)

- Si se tiene autoescalado en los recursos de azure seria buena idea usar Azure DDoS protection asi previene costos por autoescalado debido a ataques maliciosos **(Por defecto todos los servicios de Azure estan protegidos por un plan basico de proteccion contra ataques DDoS)**

##### [Marco de adopcion de la nube para Azure](https://youtu.be/d6usiB4MKq8?list=PLGjZwEtPN7j-Q59JYso3L4_yoCjj2syrM&t=1) Cuando, como y que estrategias se deberian usar para migrar la infraestructura de una organizacion a Azure

mapa de infraestuctura azure: [Azure global infrastructure experience (microsoft.com)](https://infrastructuremap.microsoft.com/explore)****

<font color="red">!IMPORTANTE</font>
	[[Servicios cloud]]
	[[Arquitectura Azure]]
	[[Como crear servicios]]
	[[Gestion y Seguridad]]
	[[Azure Marketplace]]
	[[Azure DevOps]]
	[[Gobernanza Azure]]

Para conectarse a la nube se usa internet las conexiones se pueden hacer por VPN, Express Route.

La nube se mantiene muy actualizada a diferencia de un servidor propio o on premise.

Por que usar la nube?
- Se paga por lo que se usa.
- A medida que cambia mi arquitectura o mis requerimientos puedo actualizarme rapidamente ej:
	- Si quiero cambiar de maquinas virtuales a contenedores lo puedo hacer facilmente
	- Me puedo cambiar facilemente a un app service
	- Puedo cambiar una base de datos que estaba en una maquina virtual a una base de datos administrada en azure
- Alta disponibilidad
- Recuperación ante desastres
- Agilidad (Se puede escalar rapidamente)
- Escalabilidad (Se puede escalar infinitamente)
- Elasticidad
- Si quiero dejar de usarlo lo elimino
- Capacidad de computacion enorme
- Se usa en demanda (en un par de minutos se puede escalar todo facilmente y rapido)
