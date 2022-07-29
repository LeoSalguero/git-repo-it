# Clase 01-GIT


## Archivos Markdown (archivo.md)

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




