# Práctica de Git y GitHub

## Nombre del estudiante

Cristian Eduardo Moreno Hernandez.

## Matrícula

2630272

## Nombre de la práctica


**Creación y sincronización de repositorios con Git y GitHub**

## Objetivo

El objetivo de la práctica es aprender a crear un repositorio
local utilizando Git, vincularlo con un repositorio remoto en GitHub
y comprobar la sincronización de información en ambos sentidos:
del repositorio local hacia GitHub y de GitHub hacia el repositorio local.


## Descripción del procedimiento realizado

Primero se creó una carpeta llamada `practica_git_Cristian_Moreno`
para almacenar los archivos de la práctica. Después se abrió
PowerShell dentro de la carpeta y se utilizó el comando `git init`
para convertirla en un repositorio local de Git.

Posteriormente se cambió el nombre de la rama principal a `main`
utilizando `git branch -M main`. Después se crearon los archivos
`README.md` y `datos.txt`. En el archivo `datos.txt` se agregó
un texto inicial relacionado con la práctica.

A continuación se verificó el estado del repositorio con
`git status` y se agregaron los archivos al área de preparación
utilizando `git add .`. Después se realizó el primer commit con
el comando `git commit -m "Primer commit"` para guardar los
cambios en el historial del repositorio local.

Después se creó en GitHub un repositorio público con el mismo
nombre y sin archivos iniciales. Se vinculó el repositorio local
con el repositorio remoto utilizando `git remote add origin` y
se verificó la conexión mediante `git remote -v`.

Posteriormente se utilizó `git push -u origin main` para enviar
los archivos del repositorio local a GitHub.

Después se modificó el archivo `datos.txt` directamente desde
GitHub, agregando una nueva línea. El cambio se guardó mediante
un commit realizado en GitHub. Luego, desde PowerShell, se utilizó
`git pull origin main` para descargar los cambios realizados
en GitHub y comprobar que también aparecieran en el repositorio
local.

A final , se modificó nuevamente el archivo `datos.txt` desde
la computadora. Se verificó el estado con `git status`, se
agregaron los cambios con `git add .`, se creó un nuevo commit
con `git commit` y se enviaron los cambios a GitHub mediante
`git push`. De esta manera se comprobó el flujo de trabajo en
ambos sentidos: del repositorio local hacia GitHub y de GitHub
hacia el repositorio local.

## Comandos de Git utilizados

| Comando | Funciónamieto |
|---|---|
| `git init` | Inicializa un nuevo repositorio Git local. |
| `git branch -M main` | Cambia el nombre de la rama principal a `main`. |
| `git status` | Muestra el estado actual del repositorio. |
| `git add .` | Agrega los archivos modificados al área de preparación. |
| `git commit -m "Primer commit"` | Guarda los cambios en el historial local. |
| `git remote add origin URL` | Vincula el repositorio local con GitHub. |
| `git remote -v` | Muestra los repositorios remotos configurados. |
| `git push -u origin main` | Envía los cambios del repositorio local a GitHub. |
| `git pull origin main` | Descarga los cambios realizados en GitHub. |
| `git push` | Envía los nuevos commits locales a GitHub. |

## Creación del repositorio local

El repositorio local se creó mediante el comando `git init`.
Después se configuró la rama principal como `main`.
Posteriormente se crearon los archivos necesarios para la práctica
y se realizó el primer commit.

## Vinculación con GitHub

Se creó un repositorio público en GitHub con el mismo nombre que
el repositorio local. Después se utilizó `git remote add origin`
para establecer la conexión entre el repositorio local y el
repositorio remoto.

## Sincronización Local - GitHub

Para comprobar este flujo se realizó un commit en el repositorio
local y posteriormente se utilizó `git push`. De esta manera los
archivos y cambios realizados localmente fueron enviados al
repositorio de GitHub.

## Sincronización GitHub - Local

Para comprobar el flujo contrario se modificó el archivo
`datos.txt` directamente desde GitHub. Después se utilizó el
comando `git pull origin main` desde PowerShell para descargar
los cambios al repositorio local.

## Archivos del repositorio

### README.md

Tiene  la documentación de la práctica, los comandos utilizados
y la explicación del procedimiento realizado.

### datos.txt

Contiene información relacionada con la práctica y fue utilizado
para comprobar la sincronización de cambios entre GitHub y el
repositorio local.

## Conclusión

Al hacer esta practica entendi a como utilizar Git para controlar las versiones de un proyecto y a utilizar GitHub como repositorio remoto. Entendí el como fuciona el comando `push` y `pull`, el **comando push sirve para para enviar cambios y pull para obtener cambios desde GitHub**. Para terminar entendi que es posible trabajar y sincronizar un proyecto tanto desde la computadora como desde GitHub.
