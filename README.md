# tarea-16
creación de ramas

# Proyecto: Tarea de Trabajo Colaborativo y Control de Versiones
### 1. Clonación del repositorio
   El primer paso fue clonar el repositorio desde GitHub a nuestras máquinas locales:
   ```bash (mantiene el formato adecuado.)
   git clone https://github.com/tu-usuario/nombre-del-repositorio.git 
   ```

### 2. Creación de la rama
   Creamos una nueva rama para trabajar en una funcionalidad específica sin afectar la rama principal:
   ```bash 
   git checkout -b rama-funciones
   ```
### 3. Creación y edición de archivos
   Se creó y editó un archivo llamado archivo.txt
   ```bash 
   touch archivo.txt
   ```
### 4. Commit y Push
    Después de realizar los cambios, se agregó el archivo a Git y se registraron los cambios en el repositorio local:
   ```bash 
   git add archivo.txt
   git commit -m "cree el archivo.txt"
   git push origin rama-funciones
   ```
### 5. Creación de Pull Request
    Finalmente, se creó un Pull Request (PR) en GitHub para fusionar la rama rama-funciones con la rama principal.

# Conflictos y Resolución
### Conflicto 1: Error al intentar hacer git pull
Al intentar hacer un git pull de la rama remota, nos encontramos con el siguiente error:
fatal: couldn't find remote ref rama-funciones
Este error ocurrió porque la rama rama-funciones no estaba aún subida al repositorio remoto. Para solucionarlo, se subió la rama correctamente, permitiendo asi que el git pull funcionara sin problemas
### Conflicto 2: Error al intentar hacer git commit debido a la falta de configuración del usuario
Cuando tratamos de hacer un comentario no nos permitia ya que el usuario y correo no estaban configurados, usando el comando de git config solucionamos eso.



