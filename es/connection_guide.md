---
title: "Cómo conectarse"
reference_version: 7dc4cffa956ec184a9bb8c7c2e27e39a
---

## Como conectarse a Akatsuki: Parche

- Descargar el Patcher de Akatsuki, puedes encontrarlo [aquí](https://akatsuki.gg/patcher).
- Ejecuta el parche de Akatsuki.
- ¡Disfruta jugando osu! en Akatsuki!

## Como conectarse a Akatsuki: Acceso directo de Windows

- Encuentra la aplicación `osu!.exe` en tu computadora.
- Haz click derecho en el archivo `osu!.exe` y selecciona **Crear acceso directo**.
- Haz click derecho en el acceso directo recién creado y selecciona **Propiedades**.
- En **Propiedades**, agrega `-devserver akatsuki.gg` en el campo **Destino**.
- Haz click en el botón **Aplicar** para guardar los cambios.
- Cierra la ventana de **Propiedades**.
- Ejecuta el juego desde el acceso directo.
- ¡Disfruta jugando osu! en Akatsuki!

También puedes encontrar un video tutorial [aquí](https://youtu.be/vN8zqgmN_kI)!

## Como conectarse a Akatsuki: Linux 

- Abre el script que usas para iniciar osu!
- Si `"$@"` aun no está presente después de `osu!.exe`, agrégalo. Por ejemplo, modifica `wine osu\!.exe` a `wine osu\!.exe "$@"`.
- Cuando inicies el script, agrega `-devserver akatsuki.gg`. Por ejemplo, si normalmente usas `./osu.sh` para iniciar osu!, ejecuta `./osu.sh -devserver akatsuki.gg`.

Si juegas exclusivamente en Akatsuki, puedes reemplazar `"$@"` con `-devserver akatsuki.gg`. De esta manera, no tendrás que escribir la dirección del servidor cada vez que quieras jugar.

## Como conectase a Akatsuki: MacOS

### Si ejecutas `osu!.exe` directamente: 
- Buscar **EXE Flags** en las propiedades del archivo.
- Agrega `-devserver akatsuki.gg` en el cuadro de argumentos.
- Guarda los cambios y luego ejecútalo normalmente.
- ¡Disfruta jugando osu! en Akatsuki!

### Si ejecutas `osu!.exe` a través de un archivo bat (`execute.bat`):
- Abre el **archivo bat** en un editor de archivos.
- Agrega `-devserver akatsuki.gg` en la misma línea que inicia `C:\osu!\osu!.exe`.
- Guarda los cambios y luego ejecútalo normalmente.
- ¡Disfruta jugando osu! en Akatsuki!

## Como volver a Bancho:

- Elimina el comando `-devserver akatsuki.gg` del acceso directo que usas para iniciar osu!.

Es recomendado mantener al menos dos accesos directos: uno para el [servidor oficial](https://osu.ppy.sh) y otro para Akatsuki. Por razones de seguridad, cada vez que cambies de servidor, deberás volver a ingresar tus credenciales de inicio de sesión.

## Solución de problemas:

- Si tienes algún problema, no dudes en contactarnos a través de nuestro [Discord](https://akatsuki.gg/discord).
