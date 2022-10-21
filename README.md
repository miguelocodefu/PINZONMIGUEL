# PINZONMIGUEL
Parcial practico viernes 21 de octubre 2022 ingenieria de software

HU-01 como administrador sedeo habilitar/ deshabilitar la auditoria sobre las operaciones de borrar y modificar en el proyecto para llevar la trazabilidad


DESCRIPCIÓN

Se desea crear un sistema de auditoria para el sistema de UD. Esta desarrollado el cual debe habilitar desde la interfaz de usuario 

CRITERIOS DE ACEPTACIÓN 

•	Cuando se borre un registro y este habilitara la opción de auditoría, debe guardar la hora de la acción, un consecutivo usuario que realizo la acción y valor existente del registro

•	Cuando se modifique el registro y este habilite la opción de auditoría, debe guardar la hora de la acción, un consecutivo, usuario que realizo la acción y el valor anterior y valor posterior del registro  


_________________________________________________________________________

ISUES

Crear la entidad auditoria 
Crear la base de datos 
Crear el script para la validación 
Crear proceso almacenado para eliminar y modificar los registros de la entidad auditoria 
Crear la validación dentro del frontend para la visualización 
Modificar los controlador 
Crear un super usuario llamado "ADMIN"
El usuario ADMIN tiene que revertir procesos 