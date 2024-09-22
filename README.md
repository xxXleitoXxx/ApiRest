#Api Rest
Como primer parametro,se deben definir la ubicacion del archivo que contiene nuestra base de datos,en mi caso creé un archivo llamado `testspring.mv.db` 

spring.datasource.url=jdbc:h2:///home/leitoxx/testspring

configuramos en el archivo `spring.datasource.url` la direccion del archivo `testspring.mv.db`

#Consultar con postman
##Consulta para obtener todos las clases 
![[GET_ALL.png]]
##Consulta para obtener una clase con un id especifico
![[GET_ONE.png]]
##Crear nueva clase
![[POST_CREATE.png]]
##Actualizar clase creada
![[PUT_UPDATE.png]]
