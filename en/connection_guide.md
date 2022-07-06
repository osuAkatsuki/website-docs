---
title: "How to connect to Akatsuki"
old_id: 1
---

- [Register](https://akatsuki.pw/index.php?p=3) an Akatsuki account first!
 
## How to connect to Akatsuki: Windows Shortcut

- Create a new **Shortcut** from the `osu!.exe` game file
- Right click the Shortcut and go on **Properties**
- Add `-devserver akatsuki.pw` to the **Target**, right after your directory
- Your changes should look like [this](https://akatsuki.pw/static/connection_guide.png)
- Click on **Apply**
- Run your Shortcut
- Enjoy!

A video tutorial can also be found [here](https://youtu.be/vN8zqgmN_kI).

## How to connect to Akatsuki: Linux 

- Open the script you use to launch osu

- Add `"$@"` after `osu!.exe` if it’s not already present
So if it looks like: `wine osu\!.exe`, it will become: `wine osu\!.exe "$@"`
- Then, add `-devserver akatsuki.pw` when you launch the script
So if you launch osu! with: `./osu.sh`, you can launch Akatsuki with: `./osu.sh -devserver akatsuki.pw`

If you only play on Akatsuki, you can also replace `"$@"` with `-devserver akatsuki.pw` so you don’t have to type the server address each time!

## How to connect to Akatsuki: MacOS

- Open your osu! Wineskin

- If you're running `osu!.exe` directly: 
Look for file properties, there'll be an argument box: **EXE Flags**
Add `-devserver akatsuki.pw` to the argument box 
Save changes then run it normally

- If you're running `osu!.exe` through a bat file (`execute.bat`):
Open the bat file on a file editor
On the same line as `start C:\osu!\osu!.exe`, add: `-devserver akatsuki.pw`
Save changes then run it normally

## How to return to Bancho:

To go back to Bancho you can simply remove the `-devserver` command from the Shortcut. Although from our connection guide it is implicit that you should maintain at least two shortcuts: one being for Bancho, and the other one for Akatsuki. 
Please keep in mind that, for security reasons, every time you switch servers you'll have to reinsert your login credentials.

## Troubleshooting:

If you have any issues, feel free to contact us through our [discord](https://akatsuki.pw/discord)!
