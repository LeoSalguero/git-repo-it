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
Creo un archivo llamado .gitkeep que lo que hace es
tener en cuenta la carpeta vacía.

