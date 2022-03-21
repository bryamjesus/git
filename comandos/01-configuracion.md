# Comandos de configuración ⚙
_Comandos para la configuracion de git_

### Saber la versión de GIT
_Con este comando `git --version` vamos a poder saber la version la cual esta instalada en nuestra pc._

_Para utilizar el comando solo abra el programa git bash e introdusca el comando._
```bash
git --version
```

Lo cual nos dara este resultado.
```bash
git version 2.33.1.windows.1
```

### Tu identidad
_Despues de ver que se instalo correctamente git con el comando `git --version` tenemos que establecer el nombre de usuario y dirección de correo electronico._
```bash
git config --global user.name "Bryam Talledo"
git config --global user.email bryam@gmail.com
```

> Nota: esto solo se tiene que hacer una vez

### Nuestro editor
_El editor es parte vital para los desarrolladores por eso es vital decirle que editor usaremos a git._
_Con este le estaremos diciendo cual queremos que sea nuestro editor predeterminado. En este caso le estoy diciendo que es el Visual Studio Code._
```bash
git config --global core.editor "code --wait"
```
> Nota: Si tu editor de texto no es VS Code entoces cambialo por los siguientes

| Editor | Comando de configuración |
| ------ | ------ |
| Atom | git config --global core.editor "atom --wait" |
| BBEdit (Mac, with command line tools) | git config --global core.editor "bbedit -w" |
| Emacs | git config --global core.editor emacs |
| Gedit (Linux) | git config --global core.editor "gedit --wait --new-window" |
| Gvim (Windows 64-bit) | git config --global core.editor "'C:\Program Files\Vim\vim72\gvim.exe' --nofork '%*'" (Also see note below) |
