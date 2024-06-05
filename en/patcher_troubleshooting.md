---
title: "Patcher Troubleshooting"
---

## I can't enable relax misses/relax failing when using the patcher!
If you don't see the two "Akatsuki" options at the top of the options menu, it means that the patcher has not actually been loaded into the game. This is usually due to Windows Defender falsely flagging the patcher files as malicious. As there is little we can do to remedy this, the only way to fix this issue is to **temporarily** disable Windows Defender:

- Open the **Windows Security** settings menu by opening the **Start Menu** and typing "Windows Security".
- Select **Virus & threat protection**.
- Under **Virus & threat protection settings**, select **Manage settings**.
- Disable **Real-time protection**.
- Redownload the patcher from the [official download page](https://akatsuki.gg/patcher).

It should be noted that real-time protection will automatically be re-enabled after some time, so to prevent this issue from recurring, it is recommended to exclude the patcher file from Windows Defender:

- Under the same **Virus & threat protection settings** menu, scroll down until you see **Exclusions**.
- Select **Add or remove exclusions** (you may need to allow the application administrator privileges).
- Select **Add an exclusion** > **File** and select the patcher executable file.
- You may also need to exclude the temp folder, which also contains files needed for the patcher:
- Select **Add an exclusion** > **Folder**, and type `%temp%` into the address bar at the top.
- Click **Select Folder**.

## I can't play any beatmaps when using the patcher! ("Beatmap could not be loaded successfully")
To fix this issue, you must relocate your osu! directory using the patcher:

- Open the patcher executable file.
- Click the **Locate** option, and navigate to your osu! directory.
- Click **Select Folder**.
- Launch osu! using the patcher.

## I can't launch the patcher! (OS Error 10061)
You are attempting to launch an old version of the patcher which is no longer supported. Please download the latest version of the patcher from the [official download page](https://akatsuki.gg/patcher).

## I'm still having issues!
If you are still having issues after following this guide, please open a ticket in our [Discord](https://akatsuki.gg/discord) and describe the issue. We will do our best to help!
