# Comandos Git
## git init ---> Crea un repositorio local
## git status ---> Lista todos los ficheros nuevos o modificados (Comparados con el HEAD)
## git diff <filename> ---> Muestra los cambios con el HEAD (Repositorio)
## git log [-p] [--graph] [--all] [--oneline] ---> Muestra los cambios (commits) que se han hecho al HEAD (Repositorio):
## Existen varias opciones para el "git log", por ejemplo:
### -p ---> Muestra los detalles de cada commit.
### --graph ---> Muestra una esquema con el historial de commits.
### --all ---> Muestra los commits de todas las ramas.
### --oneline ---> Muestra los commits en una sola línea.
## git commit -m "message" ---> Guarda las instantáneas del archivo permanentemente al historial de versiones.
## git push [origin] [master] ---> Carga todos los ficheros validados de forma local al repositorio remoto.
## git pull [origin] [master] ---> Descarga e incorpora los cambios del repositorio remoto.
## git branch <branch_name> ---> Crea una nueva rama.
## git branch -l ---> Muestra las ramas existentes.
## git branch --v ---> Muestra con más detalle las ramas existentes.
## git merge <branch_name> -m "message" ---> Crea un nuevo commit que añade la rama especificada a la rama activa.