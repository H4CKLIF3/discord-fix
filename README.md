<h1 align="center"> Discord-Fix for Fedora </h1>

![Logo de Discord](https://github.com/H4CKLIF3/discord-fix/assets/45366091/cc4213b7-1202-44dd-a605-966e1c11ba9a)

![](https://img.shields.io/badge/Estado-Funcional-bue)
![GitHub Org's stars](https://img.shields.io/github/stars/camilafernanda?style=social)

Fedora tiene un problema con las actualizaciones de Discord. Este script lo soluciona!


Debido a que Fedora no da soporte inmediato a Discord en sus repositorios, hace que cuando llega una actualización de Discord tengas que descargar la actualización manualmente, descomprimir el archivo y ejecutar manualmente Discord cada vez que quieras usarlo. 

Por eso he creado este script que se ejecuta cada vez que se inicia el sistema operativo y configura los archvivos en sus respectivos directorios para que no tengas que hacer nada!

<h2>Comandos</h2>

Asegurate de tener discord-fix en la carpeta "Descargas", sino puedes moverlo con el comando
```bash
mv discord-fix ~/Descargas
```

Aplica permisos de ejecución
```bash
chmod +x discord-fix
```

Ejecuta el script
```bash
./discord-fix
```

Una vez hayas ejecutado el script, este actualizará Discord o lo instalará si no lo encuentra. Despues de la primera ejecución se creará una tarea crontab para que el script se ejecute solo cada vez que se inicia el equipo, de esta manera tendrás Discord siempre actualizado!
