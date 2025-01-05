# ¿Qué hacen los siguientes comandos?
• pwd (print working directory): Muestra la ruta completa del directorio de trabajo actual.
• ls (list): Lista los archivos y directorios en el directorio actual.
• cd (change directory): Cambia el directorio de trabajo actual a uno nuevo especificado.
• mkdir (make directory): Crea un nuevo directorio con el nombre especificado.
• touch: Crea un archivo vacío con el nombre especificado o actualiza la marca de tiempo del archivo si ya existe.

# ¿Puedes explicar qué sucede en el siguiente escenario si ingresas estos comandos y argumentos en la línea de comandos? (Los argumentos son instrucciones adicionales dadas a un comando).
• CD PROJECTS : Cambias el directorio actual al directorio llamado projects. Si projects existe en el directorio de trabajo actual, ahora estarás trabajando dentro de él.
• MKDIR NEW-PROJECT : Dentro del directorio projects, creas un nuevo directorio llamado new-project. Si todo va bien, tendrás un nuevo subdirectorio en projects.
• TOUCH NEW-PROJECT/NEWFILE.MD: Creas un archivo vacío llamado newfile.md dentro del directorio new-project. Si new-project existe, el archivo newfile.md será creado dentro de él.
• CD ..  : Cambias el directorio actual al directorio superior del actual, que te llevará de vuelta al directorio desde el que comenzaste (el padre de projects).
• LS PROJECTS/NEW-PROJECT :  Listas el contenido del directorio new-project que está dentro del directorio projects. Aquí deberías ver el archivo newfile.md que creaste anteriormente

# ¿Qué comando usarías en la terminal para listar todos los archivos, incluidos los archivos ocultos, en un directorio de Linux o macOS? Explica qué significan los parámetros utilizados en el comando
* ls: Este es el comando base que se utiliza para listar archivos y directorios.
* -a (abreviatura de "all"): Este parámetro indica que se deben incluir todos los archivos en la lista, incluidos los archivos ocultos. En sistemas Unix/Linux, los archivos ocultos son aquellos cuyos nombres comienzan con un punto (.), como .bashrc o .gitignore.
