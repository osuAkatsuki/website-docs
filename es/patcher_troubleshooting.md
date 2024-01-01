---
title: "Solucionar problemas con el parche"
---

## ¡No puedo activar los fallos de RX mientras uso el parche!
Si no ves los dos opciones "Akatsuki" en la parte superior del menú de opciones, significa que el parche realmente no se ha cargado en osu!. Generalmente, esto se debe a que Windows Defender marca el archivo del parche como malicioso. No hay nada que se pueda hacer para solucionar esto, entonces necesitas desactivar **temporalmente** la protección en tiempo real para usar el parche.
- Abre el menú de opciones de **Seguridad de Windows** abriendo el menú Start y tecleando "Seguridad de Windows".
- Selecciona **Protección antivirus y contra amenazas**.
- Abajo de **Configuración de antivirus y protección contra amenazas**, selecciona **Administrar la configuración**.
- Desactiva **Protección en tiempo real**.
- Descarga otra vez el parche de la [página oficial de descargar](https://akatsuki.gg/patcher).

La protección en tiempo real se activará de nuevo después de algún tiempo, entonces para prevenir este problema en el futuro, recomendamos que excluyas el archivo del parche de Windows Defender:
- En el mismo menú **Protección antivirus y contra amenazas**, desplázate hacia abajo hasta que veas **Exclusiones**.
- Selecciona **Agregar o quitar exclusiones** (puede que tengas que dar la aplicación privilegios de administrador).
- Selecciona **Agregar exclusión** > **Archivo** y selecciona el archivo del parche.
- Puede que tengas que excluir la carpeta **Temp**, que también tiene archivos necesarios para el parche.
- Selecciona **Agregar exclusión** > **Carpeta**, y teclear `%temp%` en el recuadro en la parte superior.
- Haz clic en **Seleccionar Carpeta**.

## ¡No puedo cargar a ningún beatmap! ("Beatmap no se a podido cargar")
Para solucionar este problema, necesitas localizar su carpeta de osu! en el parche:
- Abre el archive del parche (`akatsuki_patcher.exe`).
- Haz clic en la opción **Locate**, y selecciona tu carpeta de osu!.
- Haz clic en **Launch** en el parche.

## ¡No puedo ejecutar el parche! (OS Error 10061)
Intentas usar una versión antigua del parche que ya no funciona. Descarga la versión más reciente del parche de la [página oficial de descargar](https://akatsuki.gg/patcher).

## ¡Sigo teniendo problemas!
Si sigues teniendo problemas después de mirar esta guía, por favor abre un ticket en nuestro [Discord](https://akatsuki.gg/discord) y describe el problema. ¡Haremos todo lo posible para ayudar!
