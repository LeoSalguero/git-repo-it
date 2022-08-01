# Clase 04

Vamos a ver algunas cosas de Github

## GIT HUB PAGES
En los setting del proyecto, en el sidebar
buscamos pages y ahi habilitamos para que 
el repo se empiece a servir en la web.

## GIT GIST
Permite crear pequeños snippet de codigo para compartir.

## GIT TAGS
### Crear tag en ultimo commit

```sh
    git tag -a v1.0.0 -m "Version 1.0.0"
``` 
### Crear tag en un commit especifico
```sh
    git tag -a v1.0.0 <HASH> -m "Version 1.0.0"
``` 
## Listar todos los tags
```sh
    git tag
``` 
## Ver mas informacion de un tag en particular
```sh
    git show <identificadorDelTag>
``` 
Ejemplo:
```sh
    git show v1.0.0
```
## Subir todos los tags(NO RECOMENDADO)
```sh
    git push  --tags
```
### Subir un tag en especifico:
```sh
    git push origin <tag-name>
```
### Borrar tag:
```sh
    git tag -d <tag-name>
```
## GIT amend
Sirve para cuando uno se equivoca sobre todo en el ultimo commit.
Por ejemplo al hacer un commit  y olvidarse de guardar el archivo
que estaba modificando.
```sh
    git commit --amend -m <mensaje>
```

## Para traer todos los archivos del ultimo commit en el estado q estaban en el ultimo commit
```sh
    git checkout -- .
```
# GIT RESET
```sh
1. git reset --soft <hash>   Trae todos los cambios al WD
```
```sh
2. git reset --mixed <hash> ( es lo lo mismo que poner git reset)
```
```sh
3. git reset --hard <hash>
```



```sh
    git checkout -- .
```


# GIT REFLOG







