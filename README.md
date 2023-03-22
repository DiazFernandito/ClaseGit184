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

