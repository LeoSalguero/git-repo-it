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


