# ClaseGit184 

Configuración inicial de GIT
------------------------------

1) Descargar e instalar GIT desde http://git-scm.com
2) Con el proyecto abierto en VSC, abrir la Terminal, preferentemente CMD,
y ejecutar:

	2.1) git config --global user.name "UsuarioGitHub"
	2.2) git config --global user.email "EmailDeRegistroEnGitHub"



Para crear un nuevo Repositorio Remoto
--------------------------------------

1) En GitHub.com, seleccionar "New Repository" y en la casilla correspondiente
a "Repository Name" agregarle el mismo nombre que tiene en VSC.

2) En la Terminal de VSC

	2.1) git init
	2.2) git add .
	2.3) git commit -m "Leyenda/Comentario"
	2.4) git remote add origin https://github.com/DiazFernandito/NombreDelRepositorioGit
	2.5) git push -u origin master(*)

	(*) el "master" se refiere al nombre de la rama principal del proyecto en VSC
	(ángulo inferior izquierdo de la GUI de VSC)


Para conectarse desde una nueva terminal a un Repositorio Remoto Existente
--------------------------------------------------------------------------

1) Ingresar a GitHub.com en la sección "Clone with HTTPS" del repositorio y obtener la URL
2) Abrir una terminal de Windows (cmd)
3) Dirigirse a la carpeta de trabajo (cd)
4) Escribir :

	4.1) git clone "URL Obtenida" 

	Nota: se creará un carpeta con el nombre del Repositorio Remoto dentro de la carpeta
	de trabajo

5) en VSCode abrir la carpeta del Repositorio clonado
6) Abrir una terminal (cmd) y escribir

	6.1) git add .
	6.2) git commit "Leyenda/Comentario"
	6.3) git push

	o bien:
	
	6.1) git pull

Para Actualizar un Repositorio Remoto Existente
-----------------------------------------

1) En la Terminal de VSC

	1.1) git add .
	1.2) git commit -m "Leyenda/Comentario"
	1.3) git push


Para Actualizar el Repostorio Local desde un Remoto
---------------------------------------------------

1) En la Terminal de VSC

	1.1) git pull

