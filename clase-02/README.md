# Clase 02 - Git Desarrollo Colaborativo

## .gitignore
Me permite indicar los archivos o carpetas que quiero que no formen parte del repositorio. Por ejemplo archivos de log durante desarrollo, archivos temporales, variables de entorno, etc.

**Se crea el archivo .gitignore dentro de la raíz del proyecto.**

## .gitkeep
Ayuda a git a versionar carpetas que quiero que sean parte del repositorio pero están vacías.

**Se crea el archivo .gitkeep dentro de la carpeta que quiero que git versione**

# RAMAS (BRANCHES)
Las ramas me permiten trabajar en diferentes partes del proyecto de manera auxiliar sin afectar las funcionalidad (código fuente que ya funciona)

### Listar ramas locales

```sh
git branch
```

### Listar ramas remotas


```sh
git branch -r
```

### Listar ramas locales y remotas


```sh
git branch -a
```

## Otra manera de hacer un commit
Para agregar más información sobre lo que hizo dentro de ese commit (A partir de la tercera línea)

1. Muevo los archivos al staging area

```sh
git add <nombre/archivo>
``` 

2. Hago un commit

```sh
git commit # Eso abre el nano/vim/vsc para que escribamos el mensaje
``` 

3. Una vez escrito el mensaje para confirmar

Ctrl + O + Enter (guardar) | Ctrl + X


