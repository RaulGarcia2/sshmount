# montassh
Script para hacer un montaje sshfs

## Uso
El uso de este script será como sigue:
~~~
montassh [-p puerto] [usuario@]host
~~~
Este script comprobará la existencia de la carpeta
~~~
$HOME/mnt/host
~~~
Si no existe esta carpeta la crea y nos hará un montaje ssh del $HOME del usuario en el host indicado en la carpeta $HOME/mnt/host
## Características
Este script lee el fichero ***.ssh/config*** y lee si hay alguna entrada del **host** y lee las propiedades de **user**, **port**
