### [Como usar Azure policy](https://youtu.be/9WO4EBgUJXk?list=PLGjZwEtPN7j-Q59JYso3L4_yoCjj2syrM&t=261)

- Azure policy valida propiedades de azure para tomar decisiones ej de una politica: una aplicacion que se ejecuta en una sola region.
- Las politicas no checkean los permisos de usuario las politicas asumen que el usuario ya tiene permisos si llego hasta aca
- Se admiten políticas **integradas** y **personalizadas**
- Las **Iniciativas** de políticas permiten agrupar definiciones de politicas
- **Definición** de política : define lo que hace una politica
	-   Defina el **efecto** que tendra en el recurso(denegar, auditar, agregar, modificar, etc.)
- **Asignación** de política: asignación de una definición/iniciativa de política a un ámbito
    -   Los alcances se pueden asignar a
        -   grupos de gestión
        -   suscripciones
        -   grupos de recursos
        -   recursos
- Esto se valida al momento de la creación o **actualización** **de recursos** y al momento de actualizar usar **tareas de remediación**
![[Pasted image 20230305150148.png]]