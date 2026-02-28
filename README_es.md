# fast-screenshot

[English](./README.md)

## Instalación

Debian / Ubuntu:

- Con x11-apps puedes tomar la screenshot de manera rápida en formato xwd con el comando con el mismo nombre.

- Con netpbm puedes transformarla a otros tipos de formatos

- Con xclip puedes copiarla al portapapeles.
 
```sh
sudo apt install x11-apps netpbm xclip
git clone https://github.com/aguadecoco1301/fast-screenshot
cd fast-screenshot
```
```
# De esta forma, puedes ejecutarlo sin tener que escribir la ruta.
sudo mv fast-screenshot /usr/bin/fast-screenshoot
```
## Uso
Es fácil. Ejecuta la instrucción y en la ruta que hayas especificado se guardará la imagen. Por defecto es en tu carpeta de usuario.

Puedes ejecutar el programa con la instrucción --copy, de esta forma, no se guardará, si no que será copiada al portapapeles.

Puedes añadirlo a una combinación, por ejemplo, en i3, añade esto:

```sh
bindsym Print exec --no-startup-id fast-screenshot
bindsym Ctrl+Print exec --no-startup-id fast-screenshot
```

# Colaborar

Si deseás colaborar, ¡envía pull request!
