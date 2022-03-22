# COMANDOS CUANDO SE REALIZA UN COMMIT 🤝

_Estos son los comandos que se utilizan cuando estas realizando un commit_

> Nota: commit significa compromiso

## Clonar un repositorio 👥

_Traer un repositorio de GitHub_ `git clone <link>`

```bash
git clone https://github.com/bryamjesus/blog-coffee-react.git
```
> Consejo 💡: Abres Git Bash y pones [`code <ruta>`](https://github.com/bryamjesus/git-curso/blob/main/comandos/Global.md#abrir-nuestro-editor-texto-)

## Inicio del commit 🏃‍♂️

_Para iniciar un commit tenemos que ingresar el comando_

```bash
git init
```

## Agregar archivos y/o documentos ➕📄 ➕📁

_Agrega los archivos para el commit:_ `git add <doc>`

Este es para agregar todos los archivos
```bash
git add .
```
> Recomendación: No es buena práctica agregar todos los archivos, es mejor realizarlo individualmente

Este es para agregar archivos especificos
```bash
git add index.html
```
> Consejo 💡: Si vas agregar más de un archivo separando por espacios
>  ```bash 
> git add index.html registro.html 
> ```

## Ver el estado del commit 🔥

_Con este comando veremos el estado del commit nos dira que si hemos modificado/eliminado algun archivo y que no le hemos hecho `git add <doc>`_

```bash
git status
```
Para mostar el estado de nuestro commit de una forma mas resumida se le agrega `-s`
```bash
git status -s
```
## Mensaje 📨

_Para poner un mensaje que es como un resumen de lo hecho. Poner un mensaje que tenga sentido_

```bash
git commit -m "Primer commit"
```
> Consejo 💡: Si solo ingresa `git commit` se abrira el editor de texto en el cual nosotros tendremos que poner el mensaje en la `Linea 1` guardar y cerrar, al momento que cerramos en el terminal saldra nuestro mensaje

## Eliminar un archivo GIT 🗑📄

_Este es comando es igual al comando [rm](https://github.com/bryamjesus/git-curso/blob/main/comandos/Global.md#eliminar-una-carpeta-) con la sutil diferencia es que al momento de eliminar este realizar un [git add](https://github.com/bryamjesus/git-curso/edit/main/comandos/Commit.md#agregar-archivos-yo-documentos--)._ `git rm <doc.*>`

```bash
git rm index.html
```
> Consejo 💡: Para que veas que se realizar el comando [git add](https://github.com/bryamjesus/git-curso/edit/main/comandos/Commit.md#agregar-archivos-yo-documentos--) utiliza el comando [git status]()



