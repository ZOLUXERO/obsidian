### [Como usar Bloquear recursos](https://youtu.be/eDH20Ve0eI0?list=PLGjZwEtPN7j-Q59JYso3L4_yoCjj2syrM&t=200)
Permite bloquear recursos esto lo hace con la finalidad de prevenir borrados accidentales de algun recurso, esto se puede configurar con [[Acceso basado en Rol]] generalmente es buena idea bloquear la mayoria de recursos para que no se puedan eliminar
-   Diseñado para evitar la eliminación y/o **modificación** **accidental**
-   Usado junto con RBAC
-   Dos tipos de cerraduras
    -   **Solo lectura** ( **ReadOnly** ): solo se permiten acciones de lectura
    -   **Eliminar** ( **CanNotDelete** ): todas las acciones excepto eliminar están permitidas
-   Los ámbitos son **jerárquicos** ( **heredados** )
    -   Suscripciones > Grupos de recursos > Recursos
-   **Los grupos de administración** no se pueden bloquear
-   Solo las funciones **de propietario** y **administrador de acceso de usuario** pueden administrar bloqueos ( funciones **integradas** )

El alcance del bloqueo de recuros puede ser a nivel de suscipcion, grupos de recursos o recursos individuales.
![[Pasted image 20230304231614.png]]