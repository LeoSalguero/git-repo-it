# Clase 02-GIT

** Git log

Muestra los commits

```sh

    git log
```

**Nota:** Para salir es con la letra **q**

### Por fecha

git log --since="2021-12-20"
git log --after="2021-12-20"
git log --before="2021-12-27"
git log --after="2021-12-20" --before="2021-12-27"

```sh
    git log -1 # cantidad de commits que va a mostrar el gitlog
```
```sh
    git log --oneline --decorate --all --graph
```


### GIT IGNORE

Sirve para ignorar archivos que no quiero seguir
Creo el archivo **.gitignore** en el directorio raiz
y dentro coloco el nombre del archivo o la carpeta
que no quiero seguir.

### GIT KEEP

Me permite seguir una carpeta vacía.
Creo un archivo llamado **.gitkeep** que lo que hace es
tener en cuenta la carpeta vacía.

### Forma corta de hacer un git add y un git commit
**Nota**: tengo que tener todos los archivos seguidos
si tengo alguna untracked esos archivos no se van a 
commitear.
```sh
    git commit -am "mensaje commit"
``` 


### REMOTE
#### Lista alias de remotos y url
```sh
    git remote -v
``` 
### Agrego remoto a mi repo
```sh
    git remote add <nombre-alias> <url-repo>
``` 
### Renombra el alias de la URL del remoto
```sh
    git remote rename <nombre-antiguo> <nombre-nuevo>
``` 
### Borrar remoto
```sh
    git remote rm <alias-del-remoto> 
``` 
ejemplo:
```sh
    git remote rm origin 
``` 

### Forma corta de hacer un status y ver los cambios en el WD
```sh
    git status --short
``` 

## RAMAS ( BRANCHES)

Agrego algo en la rama nueva


