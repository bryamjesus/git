# COMANDOS GLOBALES π

_Comandos globales para asΓ­ manejar de mejor manera GIT_


## Limpiar terminal π§½

_Puede que estΓ©s realizando pruebas o constantes cambios y no puedes visualizar de la mejor manera la terminal. Entonces este comando te ayudara al dejar tu terminal limpia_

```bash
clear
```
## Listar archivos y documentos π

_Lista todos documentos y archivos en la ruta que estas_

```bash
ls
```
Para mostrar los archivos que esta oculto solo agrega `-a`
```bash
ls -a
```
Tambien puedes usar este comando
```bash
dir
```

## Ver ruta πΆββοΈ

_Para ver la ruta en la cual nosotros estamos ubicados_

```bash
pwd
```

## Moverse de carpeta a carpeta πππ

_Es para moverse entre las carpetas_

```bash
cd git-curso/
```
Y para retorceder entre las carpetas
```bash
cd ..
```
> Nota: Para utilizar el autocompletado utiliza `TAB`

## Crear carpeta π

_Este es un comando es para la creaciΓ³n de carpetas_

```bash
mkdir curso-git
```
> Nota: Si el nombre de la carpeta tiene espacion pues usa `""`

## Abrir nuestro editor texto π»

_Este codigo abre nuestro editor de texto con la ruta en la que se encuentra_

```bash
code .
```

Si no estas en la ruta entonces puedes poner `code <ruta>`
```bash
code e/Cursos/Git/
```

## Eliminar una carpeta ππ

_Con este comando vamos a poder eliminar la(s) archivo(s) seleccionado(s):_ `rm <doc.*>`

```bash
rm index.html
```
> Nota: Es solo para documentos

## Editar nombre de archivo o carpeta βπ || βπ
_Si deseamos renombrar usamos:_ `mv <carpeta || nombre.*> <nuevo || nuevo.*>`

En una carpeta
```bash
mv carpeta-js JavaScript
```
En una documento
```bash
mv index.html registro.html
```
> Nota: Al cambiar de nombre el documento tienes que poner la extension tambien


## Ver contenido de una archivo ππ

_Ver todo el contenido del archivo seleccionado:_ `cat <doc.*>`

```bash
cat index.html
```
> Nota: Es solo para documentos

