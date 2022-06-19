---
title: "How to connect to Akatsuki"
old_id: 1
---
- [注册](https://akatsuki.pw/index.php?p=3) 一个账号
- 下载 [Akatsuki 服务器切换器](https://akatsuki.pw/static/switcher.zip)
- 移动 switcher.zip 压缩包里的所有文件<b>进一个单独文件夹</b>.
- 打开 `switcher.exe`. 如果系统让你安装我们的签名, 点确定.
- 点击 **Switch to Akatsuki**. (你现在可以关掉切换器了)
- 打开 [这个页面](https://c.ppy.sh), 他应该看起来像 [这样](https://akatsuki.pw/static/successful_c_page.png).
- 重启 osu! 然后用你的 Akatsuki 服务器账号登录.
- 玩的开心!

## 疑难杂症
如果你有任何问题, 打开服务器切换器的 **Inspect** 窗口.

重点部分是 Hosts 文件窗口. 如果你切换服务器失败, 一般情况下他会说你的 Hosts 文件只读.

一般来说这是杀毒软件的锅; 切换器修改了 `C:\Windows\System32\drivers\etc` 路径下的 `hosts` 文件;
这让我们能重定向 *.ppy.sh 到 *.akatsuki.pw (所以你才可以连上我们服务器), 不过, 有些广告恶意软件也
会修改这个文件来重定向到他们的推广页, 所以你可以理解为什么杀毒软件这么谨慎.

请关掉你的防火墙 / 杀毒软件并重试.
如果错误依然发生, 请考虑加入我们的 [Discord](https://akatsuki.pw/discord) 的 #help channel, 或者查看我们的 [FAQ](https://akatsuki.pw/doc/5).

### 如何在 Akatsuki 服务器上玩
- 确保你安装了 [Microsoft Visual C++ Redistributable for Visual Studio 2019](https://aka.ms/vs/16/release/vc_redist.x64.exe) !
- 开启 `switcher.exe`
- 点击 **Click to Activate**
- 确保服务器切换器显示了 **Switch was successful! Please make sure to restart your client.**
- 重启 osu! 然后用你的 Akatsuki 服务器账号登录.
- 玩的开心!

## 切换回 osu!
想切换回官方服务器, 你只需要打开服务器切换器, 然后点击 **Switch to osu!**.
**NOTE**: 你可能会发现你的浏览器重定向所有的 osu 官方页面到 akatsuki.
别担心, 这很正常: 你的浏览器 '缓存' 数据, 用于方便的重复请求, 这样访问网站效率更高.
有的人重启浏览器就好了, 但有的时候你需要手动清理缓存. 按下 Ctrl + H, 点击 "清理浏览数据", 
选择 "Cookies 和其他站点信息", 你只用选择你切换到 Akatsuki 期间的时间进行清除. 操作完成后, 
重启浏览器就好了.