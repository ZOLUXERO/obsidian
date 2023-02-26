**az-900 -> az-104 -> az-400**

==**USAR GRUPOS DE RECURSOS!!!** (para agrupar aplicaciones y sus configuraciones) ==

mapa de infraestuctura azure: [Azure global infrastructure experience (microsoft.com)](https://infrastructuremap.microsoft.com/explore)****

La nube usa un modelo a base de consumo [[consumption-based model]]

<font color="red">!IMPORTANTE</font>
	[[Servicios cloud]]
	[[Fiabilidad y previsibilidad]]
	[[Arquitectura Azure]]
	[[Azure Arc]] -> Agente que esta en un servicio externo para usar politicas y funcionalidades configuradas en Azure en otras plataformas pueden ser otras nubes, onPremise etc.

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
