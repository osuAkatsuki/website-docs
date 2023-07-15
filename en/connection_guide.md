---
title: "How to connect to Akatsuki"
old_id: 1
---

## How to Connect to Akatsuki: Patcher

- Download the Akatsuki Patcher, it can be found [here](https://akatsuki.gg/patcher).
- Run the Akatsuki Patcher.
- Enjoy playing osu! on Akatsuki!

## How to Connect to Akatsuki: Windows Shortcut

- Locate the `osu!.exe` application on your computer.
- Right-click on the `osu!.exe` file and select **Create Shortcut**.
- Right-click on the newly created shortcut and select **Properties**.
- In **Properties**, add `-devserver akatsuki.gg` to the **Target** field.
- Click on **Apply** button to save changes.
- Close the **Properties** window.
- Run the game from the shortcut.
- Enjoy playing osu! on Akatsuki!

A video tutorial can also be found [here](https://youtu.be/vN8zqgmN_kI)!

## How to Connect to Akatsuki: Linux 

- Open your osu! launch script.
- If `"$@"` is not already present after `osu!.exe`, add it. For example, modify `wine osu\!.exe` to `wine osu\!.exe "$@"`.
- When launching the script, add `-devserver akatsuki.gg`. For instance, if you typically use `./osu.sh` to launch osu!, run `./osu.sh -devserver akatsuki.gg`.

If you exclusively play on Akatsuki, you can replace `"$@"` with `-devserver akatsuki.gg`. This way, you won't need to type the server address each time you want to play!

## How to Connect to Akatsuki: MacOS

### If you're running `osu!.exe` directly: 
- Look for **EXE Flags** in file properties.
- Add `-devserver akatsuki.gg` to the argument box.
- Save changes then run it normally.
- Enjoy playing osu! on Akatsuki!

### If you're running `osu!.exe` through a bat file (`execute.bat`):
- Open the **bat file** on a file editor.
- Add `-devserver akatsuki.gg` to the same line as start `C:\osu!\osu!.exe`.
- Save changes then run it normally.
- Enjoy playing osu! on Akatsuki!

## How to Return to Bancho:

- Remove the `-devserver akatsuki.gg` command from the shortcut you use to launch osu!.

It is recommended to maintain at least two shortcuts: one for the [official server](https://osu.ppy.sh) and another one for Akatsuki. For security reasons, each time you switch servers, you'll need to re-enter your login credentials.

## Troubleshooting:

- If you have any issues, feel free to contact us through our [Discord](https://akatsuki.gg/discord)!
