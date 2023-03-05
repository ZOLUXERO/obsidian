### [Como usar DDoS protection](https://youtu.be/MUVFMF9DgM0?list=PLGjZwEtPN7j-Q59JYso3L4_yoCjj2syrM&t=126)
Distributed denial of service, viene por defecto en la mayoria de servicios de Azure no se paga por este servicio.
-   **Servicio de protección DDoS** en Azure
-   Diseñado para
    -   **Detectar el tráfico malicioso** **y bloquearlo** mientras permite que los usuarios legítimos se conecten
    -   **Evite costos adicionales** para entornos de escalado automático
-   Tiene dos niveles
    -   **Básico** : habilitado automáticamente para la plataforma Azure
    -   **Estándar** : capacidades adicionales de mitigación y supervisión para los recursos de Azure Virtual Network ==(Se deberia usar esto asi si llega a pasar y se escalan los recursos subiendo el costo, Azure devuelve el dinero de los recursos usados)==
-   El nivel estándar utiliza el aprendizaje automático para **analizar los patrones de tráfico** para una mayor precisión
![[Pasted image 20230304212324.png]]