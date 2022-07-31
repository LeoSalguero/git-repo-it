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





