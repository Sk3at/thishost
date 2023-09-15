# thishost

Bienvenid@

Este es un script simple que utiliza la funcion ping de una forma elegante para determinar si un host se encuentra activo y el tipo de sistema operativo que esta corriendo en el mismo (basandose en el TTL).

La instalacion del script es sencilla, simplemente importa el archivo a algun directorio que se encuentre disponible en tu PATH y dale permisos de ejecucion con el comando:
>chmod +x ./thishost
>
Para consultar que directorios se encuentran en tu PATH podes ejecutar:
>echo $PATH

La otra opcion es colocar el archivo en el directorio de tu gusto y agregar la ruta a tu PATH.
Por ejemplo, digamos que el archivo lo importas a tu capeta de descargas, entonces deberias ejecutar el siguiente comando:
>export PATH=$PATH:/home/usuario/Descargas

Si agregas el archivo de forma manual tene en cuenta que vas a tener que agregar el PATH cada ves que reinicies tu terminal. Lo ideal es colocarlo dentro del archivo de configuracion de tu terminal (.bashrc o .zhrc dentro de tu directorio home).

Este es un preview del script:

![image](https://github.com/Sk3at/thishost/assets/92405961/c4dc26e9-a7af-4de5-af11-57848b459804)


¡¡Saludos!!
