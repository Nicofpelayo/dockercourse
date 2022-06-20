HEALTHCHECK verifica que el correcto funcionamiento de los contenedores despues de levantarlos. Se utiliza para asegurarse que no haya errores

ONBUILD permite correr instrucciones, despues de que contenedores "hijos" sean creados. Se utiliza cuando se necesitan funciones de estos contenedores hijos para correr la instruccion, ya que de otro modo no estarían creados y no se podría realizar el comando.

VOLUME crea directorios dentro del contenedor con los nombres que les pases. A su vez, fuera del contenedor se crean volumenes que estan vinculados a esos mismos directorios. Se crean en la carpeta de volumenes que se definió en la instalación de docker. Se utiliza para que el equipo host pueda comunicarse con el contenedor.
