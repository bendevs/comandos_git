# comandos_git

Configuración Básica

Configurar Nombre que salen en los commits

	git config --global user.name "dev"

Configurar Email

	git config --global user.email dev1@gmail.com

Marco de colores para los comando

	git config --global color.ui true


Iniciando repositorio

Iniciamos GIT en la carpeta donde esta el proyecto

	git init

Clonamos el repositorio de github o bitbucket

	git clone <url>

Añadimos todos los archivos para el commit

	git add .

Hacemos el primer commit

	git commit -m "Texto que identifique por que se hizo el commit"

subimos al repositorio

	git push origin master
