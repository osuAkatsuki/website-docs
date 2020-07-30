---
title: "Installing the certificate manually"
old_id: 12
---
If you're having troubles connecting to Akatsuki or the switcher doesn't install the certificate properly, you can try installing it manually.

### Instructions
- First, download the certificate [by clicking here](https://old.akatsuki.pw/akatsuki.crt)
- Then, open **certificate.cer**
- Click **Install certificate...**
- Click **Next**
- Select **Place all certificates in the following store** (second option), then click **Browse...**
- A new window will pop up, select **Trusted root certification authorities** and click **Ok**
- Click **Next**
- Click **Finish**

### If everything else fails...
...you can try to remove all existing Akatsuki certificates and install the certificate again. Follow these steps:

- Press **Win+R**  
- Type `mmc certmgr.msc` in the run box and press **enter** to open the Certificate Manager  
- Select **Trusted root certification authorities** on the left  
- Select **Certificates** on the right  
- You should see some **[Akatsuki](https://onii-chan-please.come-inside.me/2020-05-05_10-02-46.png)** and some **\*.ppy.sh** entries in the list. Select them, **right click** and click on **Delete**  
- Select all the positive options (Ok/Yes etc)  
- Restart the switcher, click on **Inspect**, then choose **Install certificate**, then **Yes**  
- Click on **Test Akatsuki connection** and you should see "OK" for every domains  
**If the inspect dialog is fine but you still can't connect to Akatsuki from the game client, try running osu! as administrator**.
