### [Como usar Acceso basado en rol](https://youtu.be/4v7ffXxOnwU?list=PLGjZwEtPN7j-Q59JYso3L4_yoCjj2syrM&t=397)
En todos los recursos de Azure se le puede asignar permisos a un usuario dependiendo de su rol
**El rol** (definición de rol) es una **colección de acciones** que **la identidad asignada** podrá realizar.
-   Sistema de autorización integrado en Azure Resource Manager (ARM)
-   Diseñado para la gestión de acceso detallada de los recursos de Azure
-   La asignación de roles es una combinación de
    -   Definición de roles: lista de permisos como crear VM, eliminar SQL, asignar permisos, etc.
    -   Principal de seguridad: usuario, grupo, principal de servicio e identidad administrada y
    -   Ámbito: recurso, grupos de recursos, suscripción, grupo de administración
-   Jerárquico
    -   Grupos de administración > Suscripciones > Grupos de recursos > Recursos
-   Se admiten funciones integradas y personalizadas