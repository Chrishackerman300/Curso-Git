# Curso de Git desde cero

## ¿Qué es Git?

Git es un software de control de versiones, donde podemos actualizar las versiones de nuestros proyectos de trabajos, como una app, una web o un video juego. Principalmente se trabaja utilizando la **la terminal (Git Bash)** que es la propia terminal de git.

Git es una tecnología muy demandada en el mundo TEC ya que es requerida como una habilidad para un programador o ingeniero de software. 

## Comandos importantes de Git

Aquí veremos los comandos más importantes para empezar a entender la utilización de git.

* ### git --version

Este comando nos mostrará la versión más reciente de nuestro git.

#### Comando:

```
git --version 
```

* ### git config --global

Este comando mostrará toda la información global de git.

#### Comando:

```
git config --global
```

* ### git config --globa user.name "User Name"

Este comando lo utilizamos para poder configurar git con nuestro nombre de usuario.

#### Comando:

```
git config --global user.name "User Name"
```

* ### git config --global user.email "Email"

Este comando lo utilizamos para poder configurar git con nuestro email.

#### Comando:

```
git config --global user.email "Email"
```

* ### git config --global core.editor "code --wait"

Con este comando configuraremos git con nuestro editor de código, en mi caso utilizó Visual Studio Code.

#### Comando:

```
git config --global core.editor "code --wait"
```

* ### ls

Este comando nos mostrará un listado completo de todo nuestro directorio, tanto archivos, carpetas y ejecutables dependiendo en que parte del directorio nos encontremos.

#### Comando:
```
ls
```

* ### pwd

Este comando mostrará la dirección del directorio en el que estemos.

#### Comando:

```
pwd
```

* ### cd

Este comando es para cambiar de directorio **(change directory)** este se utiliza ingresando cd y en seguida el nombre de la ruta a a que queremos acceder.

#### Comando:
```
cd ruta/
```

* ### cd ..

Este comando sirve para salir de una carpeta en el directorio.

#### Comando:

```
cd ..
```

* ### mkdir

Este comando crea una nueva carpeta en dicho directorio en el que estemos.

#### Comando:

```
mkdir Nueva Carpeta
```

* ### git init

Este comando es importante, ya que con este crearemos un nuevo repositorio de git en dicha carpeta en la que estemos.

#### Comando:

```
git init
```

* ### cd .git

Este comando sirve para acceder a nuestro repositorio de git.

#### Comando:

```
cd .git
```

* ### git status

Este comando mostrará el estatus de nuestro repositorio y toda su información.

#### Comando:

```
git status
```

* ### git status -s

Este comando es lo mismo que **git status** pero solo nos mostrará los **archivos que están o aún no esten en la etapa de stage.**

#### Comando:

```
git status -s
```

* ### git add

Este comando agregará el archivo con un nombre en específico a la etapa de stage de nuestro repositorio de git.

#### Comando:

```
git add index.html
```

* ### git add .

Este comando agregará todos los archivos de nuestra carpeta en la etapa de stage de nuestro repositorio. **No se recomienda utilizar este comando**.

#### Comando:

```
git add .
```

* ### git commit -m "Comentario"

Este comando compromete el archivo de la etapa de stage y o sube a nuestro repositorio, **es necesario ponerle un mensaje**.

#### Comando:

```
git commit -m "Mi archivo HTML"
```

* ### git commit -a

Este comando abre un archivo en nuestro editor de código y ahí le escribimos un mensaje y después lo cerramos. **Compromete todos los archivos en etapa de stage**.

#### Comando:

```
git commit -a
```

* ### rm

Este comando eliminará un archivo de nuestra git branch.

#### Comando:

```
rm index.html
```

* ### git restore --staged

Este comando sirve para sacar un archivo en la etapa de stage.

#### Comando:

```
git restore --staged
```

* ### git restore

Este comando sirve para recuperar un archivo de stage.

#### Comando:

```
git restore index.html
```

* ### mv

Con este comando podremos cambiar el nombre de un archivo.

#### Comando:

```
mv index.html proyecto.html
```

* ### git diff

Con este comando vemos de una forma más visual los cambios del archivo.

#### Comando:

```
git diff
```

* ### git branch

Este comando muestra la rama en la que estamos.

#### Comando:

```
git branch
```

* ### git branch -m

Este comando sirve para cambiarle el nombre a una rama de nuestro git.

#### Comando:

```
git branch -m Rama-1
```

* ### git checkout -b

Este comando sirve para crear una nueva rama y cambiarnos de rama en nuestro git.

#### Comando:

```
git branch -b Rama-2
```

* ### git checkout

Con este comando nos cambiamos a una rama ya existente en nuestro git.

#### Comando:

```
git checkout Rama-1
```

* ### git log

Este comando mostrará a detalle el historial de nuestro repositorio de git.

#### Comando:

```
git log
```

* ### git log --oneline

Este comando mostrará la información más importante del historial de nuestro repositorio de git.

#### Comando:

```
git log --oneline
```

* ### cat

Este comando mostrará el contenido del archivo.

#### Comando:

```
cat
```

* ### git merge

Este comando sirve para enviar las modificaciones de un branch al branch principal.

#### Comando:

```
git merge Rama-2
```

* ### git branch -d

Este comando eliminará una rama de nuestro branch.

#### Comando:

```
git branch -d Rama-2
```

* ### git push -u origin 

Este comando sirve para mandar a nuestro repositorio todos nuestros archivos creador en la rama, cuando modifiquemos un archivo existente, debemos insertarlo de nuevo a la rama.

#### Comando:

```
git push -u origin main
```

Curso creado por **Christian Ivan Mendoza Ramirez**.