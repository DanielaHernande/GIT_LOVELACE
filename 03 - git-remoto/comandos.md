# Comando para conectar mi git local con git en la nube

- git remote add nombre_conexion url_conexion

# Comando para clonar o traer un repositorio de git remoto 

- git clone url_conexion

# Comando para listar las conexiones remotas 

- git remote -v

# COmando para eliminar una conexion remota 

- git remote remove nombre_conexion 

# Comando para enviar informacion a la nube 

- git push /*ENVIAR - solo hace push en la rama que estoy */

- git push nombre_conexion nombre_rama 

- git push -u nombre_conexion nombre_rama /*La letra "u" significa que si no existe la rama con el nombre que le pusimos a la rama entonces crearia una nueva rama*/

- git push --all /* Para enviar todos los archivos de todas las ramas */


# Comando para obtener cambios o la informacion que hay en el git remoto

- git pull /*Obtener*/
- git pull nombre_conexion nombre_rama 

