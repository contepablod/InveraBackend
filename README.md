# Invera ToDo-List Challenge (Python/Django Jr-SSr)

La siguiente aplicación se encargará de administrar tareas. Para eso el usuario podrá:

- Crear una tarea: Para crear una tarea, el usuario deberá encontrarse en la url principal y acceder al link Task de la API. Dentro del mismo, podrá completar los cambos Jobs (para registar la tarea), Date(string de formato ¨mm-dd-aaaa¨) y Done (Marcador donde podrá decidir si la tarea fue realizada o no clicleando sobre el box). Deberá cliquear en POST para poder guardar los datos. A su vez, se generará un campo Auto_Date que contendrá la fecha de creación automatizada.
- Eliminar una tarea: Para eliminar una tarea deberá acceder a la url /Task/<id de la tarea> donde podrá cliquear el botón DELETE en rojo para eliminarla
- Marcar tareas como completadas: El usuario podrá marcar la tarea como completada accediendo a la misma a través de la url /Task/<id de la tarea> donde podrá cliquear la casilla Done y cliquear PUT para actualizar la información
- Poder ver una lista de todas las tareas existentes: Para poder ver una lista de todas las tareas el usuario deberá encontrarse en la url principal y acceder al link Task de la API. Dentro del mismo, deberá cliquear en GET y desplegar el menú para elegir API.
- Filtrar/buscar tareas por fecha de creación y/o por el contenido de la misma: Para filtrar datos, podrá utilizar el botón Filters que también se encuentra en el mismo lugar que el botón GET. Los matcheos de búsqueda no son exactos.


