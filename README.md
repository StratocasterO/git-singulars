# git-singulars
Repositori de proves de git pel curs de front end Singulars 2020

## Sobre este repositorio:

Este repositorio tiene el objetivo de familiarizar a los commands de Git y la interfaz de Github.
Este es el documento **README.md** del repositorio, podemos editar este documento con sintaxis **markdown**.
Si quieres saber lo básico de markdown, podéis encontrarlo [aquí](https://docs.github.com/en/free-pro-team@latest/github/writing-on-github/basic-writing-and-formatting-syntax).

## Comandos para inicializar Git:

Propongo de hacer un Cheat sheet de los comandos de Git en este documento, así podemos practicar el markdown y repasar el Git. Empiezo la lista:

1. Para inicializar un repositorio local, tenemos que usar:

```
$ git init
```

2. Enlazar repositorio remoto:

```
$ git remote add origin https://github.com/nombre_del_repo
```

"origin" es el nombre que tendrá en nuestro ordenador el repositorio remoto.

3. Actualizar los cambios:

```
$ git pull origin master
```

"origin" es el nombre del repositorio remoto y "master" el nombre de la rama de la que estamos trabajando.

## Comandos para trabajar con Git:

1. Commit

Para añadir cambios hechos en los archivos locales.

```
$ git commit -m "aquí_el_mensaje_que_describa_los_cambios"
```

2. Pull

Para sincronizar en nuestro repositorio local los cambios que se hayan subido al remoto.

```
$ git pull origin master
```

"origin" es el nombre del repositorio remoto y "master" el nombre de la rama de la que estamos trabajando.

3. Push

Para subir los cambios añadidos en los commits al repositorio remoto.

```
$ git push origin master
```

"origin" es el nombre del repositorio remoto y "master" el nombre de la rama de la que estamos trabajando.

## Otros comandos Git:

- Añadir credenciales:

```
$ git config --global user.name "Mona Lisa"
$ git config --global user.email "monalisa@louvre.fr"
```

"--global" sirve para no tener que añadir las credenciales en cada repo.

- Ver el estado del repositorio (si hay commits hechos, etc):

```
$ git status 
```

- Crear una rama nueva (para añadir cambios a un fichero)

```
$ git branch
```

- Cambiar de rama

```
$ git checkout
```