# Comandos de configuración de GIT 🐙

_Comandos para la configuracion de git_

## Saber la versión de GIT 👓

_Con este comando `git --version` vamos a poder saber la version la cual esta instalada en nuestra pc._

_Para utilizar el comando solo abra el programa git bash e introdusca el comando._

```bash
git --version
```

Lo cual nos tiene que dar un resultado parecido a este.

```bash
git version 2.33.1.windows.1
```

## Tu identidad 🧔

_Despues de ver que se instalo correctamente git con el comando `git --version` tenemos que establecer el nombre de usuario y dirección de correo electronico._

```bash
git config --global user.name "Bryam Talledo"
git config --global user.email bryam@gmail.com
```

> Nota: esto solo se tiene que hacer una vez

## Nuestro editor ✏

_El editor es parte vital para los desarrolladores por eso es vital decirle que editor usaremos a git._
_Con este le estaremos diciendo cual queremos que sea nuestro editor predeterminado. En este caso le estoy diciendo que es el Visual Studio Code._

```bash
git config --global core.editor "code --wait"
```

Si tu editor no es VS Code guíate de la tabla acontinuación:

| Editor                                | Comando de configuración                                                                                                                 |
| ------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| Atom                                  | `git config --global core.editor "atom --wait"`|
| BBEdit (Mac, with command line tools) | `git config --global core.editor "bbedit -w"` |
| Emacs                                 | `git config --global core.editor emacs`|
| Gedit (Linux)                         | `git config --global core.editor "gedit --wait --new-window"`|
| Gvim (Windows 64-bit)                 | `git config --global core.editor "'C:\Program Files\Vim\vim72\gvim.exe' --nofork '%\*'"` (Vea la nota a continuación)|
| Kate (Linux)                          | `git config --global core.editor "kate"`|
| nano                                  | `git config --global core.editor "nano -w"`|
| Notepad (Windows 64-bit)              | `git config core.editor notepad`|
| Notepad++ (Windows 64-bit)            | `git config --global core.editor "'C:\Program Files\Notepad\notepad.exe' -multiInst -notabbar -nosession -noPlugin"` (Vea la nota a continuación) |
| Scratch (Linux)                       | `git config --global core.editor "scratch-text-editor"`|
| Sublime Text (macOS)                  | `git config --global core.editor "/Applications/Sublime\ Text.app/Contents/SharedSupport/bin/subl --new-window --wait"`|
| Sublime Text (Windows 64-bit)         | `git config --global core.editor "'C:\Program Files\Sublime Text 3\sublime_text.exe' -w"` (Vea la nota a continuación)|
| TextEdit (macOS)                      | `git config --global core.editor "open --wait-apps --new -e"`|
| Textmate                              | `git config --global core.editor "mate -w"`|
| Textpad (Windows 64-bit)              | `git config --global core.editor "'C:\Program Files\TextPad 5\TextPad.exe' -m` (Vea la nota a continuación)|
| UltraEdit (Windows 64-bit)            | `git config --global core.editor Uedit32`|
| Vim                                   | `git config --global core.editor "vim --nofork"`|
| Visual Studio Code                    | `git config --global core.editor "code --wait"`|
| VSCodium (Free/Libre Open Source Software Binaries of VSCode)                    | `git config --global core.editor "codium --wait"`|
| WordPad             | `git config --global core.editor '"C:\Program Files\Windows NT\Accessories\wordpad.exe"'"`|
| Xi             | `git config --global core.editor "xi --wait"`|

> Nota: Si tiene un editor de 32 bits en un sistema Windows de 64 bits, el programa se instalará en `C:\Program Files (x86)\` en lugar de `C:\Program Files\` como en la tabla anterior.
>
> [Página de referencia](https://git-scm.com/book/en/v2/Appendix-C%3A-Git-Commands-Setup-and-Config)

## Comprobar configuración

_Después de haber terminado de configurar tenemos que ver si las se han realizado de la mejor manera entonces para eso ponemos el siguiente codigo:_

```bash
git config --list
```
_Si es que quieres ver una configuración en especifico pues se pone `git config <key>`_
```bash
git config user.name
git config user.email
```
> Nota: Si quieres ayuda con git solo usa el comando `git help <key>` , `git <verb> --help` o `man git-<verb>`
> ```bash 
> git help config
> ```
>
> [Página de referencia](https://git-scm.com/book/es/v2/Inicio---Sobre-el-Control-de-Versiones-%C2%BFC%C3%B3mo-obtener-ayuda%3F)

