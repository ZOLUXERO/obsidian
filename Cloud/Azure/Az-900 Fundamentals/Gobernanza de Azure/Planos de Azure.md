### [Como usar Planos de Azure](https://youtu.be/3rSCnAZPNfo?list=PLGjZwEtPN7j-Q59JYso3L4_yoCjj2syrM&t=228)
-   **Paquete** de varios componentes de Azure ( **artefactos** )
    -   **Grupos de recursos**
    -   **Plantillas ARM**
    -   **Asignaciones de políticas**
    -   **Asignaciones de roles**
-   **Almacenamiento centralizado** para **patrones de diseño aprobados por la organización**
-   **Definición** de plano : describe lo que debería suceder (paquete reutilizable)
-   **Asignación** de blueprint : describe dónde debería suceder (implementación del paquete)
Servicio de Azure que ayuda a manejar los ambientes de azure de manera mas facil un caso de uso seria ud tiene una subcripcion y un grupo de recursos y quiere duplicar esa misma infraestructura sin tener que hacer todo manualmente, para esto puede usar los planos de azure estos guardan una definicion de un plano con los componentes que necesita, una vez guardados puede asignar los planos a una suscripcion para que esta replique los componentes del plano que utiliza
![[Pasted image 20230305152034.png]]