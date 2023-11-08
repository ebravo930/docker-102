#Respuesta
##¿Qué pasa si cambias el valor de la variable PORT? ¿Qué cambios debes hacer para cambier el port a 8080?
Se debe cambiar el valor del puerto en el archivo .env y en el compose.yaml, se debe cambiar el 8000:8000 por 8080:8080

¿Cuál es el tamaño de la imagen del servidor flask?
143MB
¿Cuál es el tamaño de la imagen postgres?
417MB
¿Cuándo fueron creadas cada una de las imágenes?
docker-102-server -> 23 minutes ago 
postgres -> 7 weeks ago   

¿Cuál es la causa del error?
El error 
docker-102-db-1      | 2023-11-08 22:56:11.003 UTC [34] ERROR:  relation "books" does not exist at character 15   
docker-102-db-1      | 2023-11-08 22:56:11.003 UTC [34] STATEMENT:  SELECT * FROM books;