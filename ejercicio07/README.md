Se ejecutan dos contenedores
Estan basados en las imagenes nicopaez/jobvacancy-ruby:1.3.0 y postgres


En la primera línea se indica la version de la imagen, luego se detallan los servicios. La web utiliza la primera imagen mencionada, y la base de datos la segunda. La web utiliza el puerto 3000 y esta vinculada con la base de datos. Uiliza el environment de produccion y se le pasa el acceso a la base de datos de postgres. En la base de datos se detalla la contraseña a utilizar para acceder a la base de datos.


