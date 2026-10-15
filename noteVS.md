# Git Branch

## Notes 

`git branch` sirve para enlazar 

- `git branch` : Enlistar ramas
- `git branch <rama>`: Crea una nueva rama
- `git branch -D <rama>`: Elimina una rama 

## Ggit checkout

Git checkout sirve para intercambiar ramas o commits

- `git switch <rama>`: Cambiar a una rama

## Git add

- `git add .`: Añadir todos los archivos cambiados a staging
- `git add -u`: Añadir solo los archivos cambiados al area de staging

## Git commit

Guarda los cambios del staging area 

- `git commit -m "Comentario"`: Hace un commit con comentario
- `git commit -am "Comentario"`: Es un equivalente de usar tambien git add -u

## Git push 


Por default tenemos nuestro remote principal llamado *origin*

- `git push`: Por default sube los cambios de nuestro branch al *upstream* bransh, la cual es la branch default para sincronizar cambios 