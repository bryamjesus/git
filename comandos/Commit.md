# COMANDOS CUANDO SE REALIZA UN COMMIT 🤝

_Estos son los comandos que se utilizan cuando estas realizando un commit_

> Nota: commit significa compromiso

## Inicio del commit 🏃‍♂️

_Para iniciar un commit tenemos que ingresar el comando_

```bash
git init
```
## Agregar archivos y/o documentos ➕📄 ➕📁

_Para iniciar un commit tenemos que ingresar el comando:_ `git add <doc>`

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

