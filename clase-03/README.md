# Clase 03-GIT

## Repaso de branch

### Listo ramas
```sh
    git branch
    
``` 
### Para crear una rama

```sh
    git branch<nombreRama>
```


### Para cambiar de rama

```sh
    git switch <nombre-rama>
    
``` 
## GIT MERGE

### Tipos de Merge

Fast- Fodward (no hay ningun cambio que se solape con lo que está en la otra rama)
Fast- Fodward- Union automatica (no hay ningun cambio que se solape con lo que está en la otra rama)

Recursiva - Uniones automaticas(No hay colisiones de cambios)

Manual - Conflictos(ocurre cuando hay modificaciones en las mismas lineas)

### Abortar merge

```sh
    git merge --abort
```

### Agrego cosas q quiero tener en consideracion.
Agrego cosas q quiero tener en consideracion.
Tener en cuenta subir una rama al remoto.
Ver clone.
Ver Fork.

## Alias

### Como creo un alias?

```sh
    git config alias.lg "log --oneline --decorate --all --graph"
```
```sh
    git config alias.l "log --oneline"
```
```sh
    git config --get-regexp alias
```
### Para editar el archivo de configuracion de GIT
```sh
    git config -e
```
### Borrar alias:

```sh
     git config --unset alias.e
```

## Git Clone
Me permite clonar cualquier repositorio que exista en Github, gitlab,etc
```sh
     git clone https://github.com/LeoSalguero/git-repo-it.git
```
Para ponerlo en una carpeta especifica:
```sh
     git clone https://github.com/LeoSalguero/git-repo-it.git ./<nombre>
```
### Fork
Me permite crear un repo de cualquier proyecto  de Github

1. Vamos al repo que queremos hacer el fork. Presionamos el botón
2. Se cre el repo en mi cuenta .
3. Puedo clonar ese repo y empezar a trabajar.

## Subir rama local al remoto

```sh
    git push origin <nombreRama>
```
##  Para actualizar un fork
Necesito el remoto original. Del remoto al repo al cual hice el
fork.
## Agrego el remoto del repositorio original
```sh
    git remote add upstream <nombreUrl>
```
## Me traigo los ultimos commit de la repo original.
```sh
    git pull upstream <nombreRama>
```


# me traigo lo de mi propio repo remoto
```sh
    git pull 
```
# GIT STASH
Es una pila de almacenamiento que provee Git. Permite registrar temporalmente
los cambios del wd para seguir trabajando. Cuando hacemos un stash
se restablece el proyecto al ultimo commit.
## Crear el stash
Guarda los cambios que están en el wd , en un area temporal.
```sh
    git stash
```
## Recuperar el ultimo stash

sino hay conflicto, borra el stash.

```sh
    git stash pop
```
## Listar los stash
```sh
    git stash list
```
## Para recupear el stash sin borrarlo

```sh
    git stash apply stash@{1}
```
## Para borrar dicho stash

```sh
    git stash drop stash@{1}
```



