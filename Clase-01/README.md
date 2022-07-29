# Clase 01-GIT


## Archivos Markdown (archivo.md)

https://www.markdownguide.org/cheat-sheet/

## Saber si tengo git instalado

**Nota:** = backlist = >ALT+96

```sh

    git --version

```

### Configuracion inicial de git

#### Configuro el usuario

```sh

    git config user.name "LeoSalguero" 

```
#### Configuro el mail

```sh

    git config user.email "lsalguero24091311@gmail.com"

```
#### Listo las configuraciones del usuario

```sh

    git config --get-regexp user

```




## COMANDO CONSOLA

### Limpio la consola

```sh 
    clear
```

### Listar archivos en consola

```sh 

    ls -la
```

### Ingreso a un directorio

```sh 

    cd <directorio>
```

### Retrocedo directorio

```sh 

    cd ..
```


### Creo repositorio git

```sh

    git init
```
### Paso del working directory (WD) al Index(staged). ojo que es case sensitive.

```sh

    git add <nombreArchivo>
```

### Paso del WD al Index mas de un archivo

```sh

    git add .
```

### Para saber lo que está pasando en el WD

```sh

    git status
```

### Para pasar del Index al Repositorio Local. Mensaje entre comillas.

```sh

    git commit -m <mensaje>
```

### Ver commits 

```sh

    git log
```

### ver commit resumidos

```sh

    git log --oneline
```

### Pasos para subir mi repo local al remoto

1.git init
2.git status
3.git add README.md
4.git commit -m "first commit"
5.git remote add origin https://github.com/LeoSalguero/git-repo-it.git
6.git push -u origin master





