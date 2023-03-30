# ClaseGit184 

Configuración inicial de GIT
------------------------------

1) Descargar e instalar GIT desde http://git-scm.com
2) Con el proyecto abierto en VSC, abrir la Terminal, preferentemente CMD,
y ejecutar:

	> git config --global user.name "UsuarioGitHub"
	> git config --global user.email "EmailDeRegistroEnGitHub"



Para crear un nuevo Repositorio Remoto
--------------------------------------

1) En GitHub.com, seleccionar "New Repository" y en la casilla correspondiente
a "Repository Name" agregarle el mismo nombre que tiene en VSC.

2) En la Terminal de VSC

	> git init
	> git add .
	> git commit -m "Leyenda/Comentario"
	> git remote add origin https://github.com/DiazFernandito/NombreDelRepositorioGit
	> git push -u origin master(*)

	(*) el "master" se refiere al nombre de la rama principal del proyecto en VSC
	(ángulo inferior izquierdo de la GUI de VSC)


Para conectarse desde una nueva terminal a un Repositorio Remoto Existente
--------------------------------------------------------------------------

1) Ingresar a GitHub.com en la sección "Clone with HTTPS" del repositorio y obtener la URL
2) Abrir una terminal de Windows (cmd)
3) Dirigirse a la carpeta de trabajo (cd)
4) Escribir :

	> git clone "URL Obtenida" 

	Nota: se creará un carpeta con el nombre del Repositorio Remoto dentro de la carpeta
	de trabajo

5) en VSCode abrir la carpeta del Repositorio clonado
6) Abrir una terminal (cmd) y escribir

	> git add .
	> git commit "Leyenda/Comentario"
	> git push

	o bien:
	
	> git pull

Para Actualizar un Repositorio Remoto Existente
-----------------------------------------

1) En la Terminal de VSC

	> git add .
	> git commit -m "Leyenda/Comentario"
	> git push


Para Actualizar el Repostorio Local desde un Remoto
---------------------------------------------------

1) En la Terminal de VSC

	> git pull

