---
title: "Installing the certificate manually"
old_id: 12
---
如果你在连接 Akatsuki 时翻车了或者服务器切换器并没有正常安装证书, 你可以试着手动安装.

### 普通安装
- 首先, 下载 [证书](https://old.akatsuki.pw/akatsuki.crt)
- 然后, 打开 **certificate.cer**
- 点击 **Install certificate...**
- 点击 **Next**
- 选择 **Place all certificates in the following store** (第二项), 然后点击 **Browse...**
- 然后会弹出一个新窗口, 选择 **Trusted root certification authorities** 然后点击 **Ok**
- 点击 **Next**
- 点击 **Finish**

### 如果都翻车了...
...你得试试删掉所有 Akatsuki 的证书然后重装证书:

- 按下 **Win+R**  
- 输入 `mmc certmgr.msc` 然后按 **enter** 打开证书管理器
- 选择左边的 **Trusted root certification authorities**
- 选择右边的 **Certificates**
- 然后你可以看到列表里有 **[Akatsuki](https://onii-chan-please.come-inside.me/2020-05-05_10-02-46.png)** 和一些 **\*.ppy.sh**. 选择他们, **右键** 然后选择 **删除**  
- 选择所有对的选项 (Ok/Yes)  
- 重启服务器切换器, 点击 **Inspect**, 然后选择 **Install certificate**, 然后 **Yes**  
- 点击 **Test Akatsuki connection** 然后你应该就可以看到所有的域名都提示 "OK"
**如果所有检测都正常但是你还是连不上 Akatsuki, 试试以管理员权限运行 osu!**.
