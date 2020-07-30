---
title: "How to connect to Akatsuki (Linux)"
old_id: 14
---
This guide is only for connecting osu! to Akatsuki, and not setting the game itself up. You can follow [this guide](https://gist.github.com/Francesco149/a2f796683a4e5195458f4bb171d88eb0) to set the client up.

### 1. Modifying the hosts file manually
Alternatively, you can edit your hosts file manually. To do so, run `nano /etc/hosts` as root/with sudo.

When you've got it open, paste the following at the bottom:

```
{ipmain} c.ppy.sh ce.ppy.sh c3.ppy.sh c4.ppy.sh c5.ppy.sh c6.ppy.sh a.ppy.sh i.ppy.sh osu.ppy.sh
{ipmirror} bm6.ppy.sh
```
**CTRL+X** and then **Enter** to save the file.

### 2. Installing the certificate
Download the certificate by clicking [*here*](https://old.akatsuki.pw/akatsuki.crt)

Open the Internet Explorer configuration by running `wine control`.

Double click the *Internet Settings* icon, navigate to the *Content* tab, then click the *Certificates...* button.

Click on *Import*, then *Next*.

Click *Browse...* then select the Akatsuki certificate.

Click *Next*.

Select *Place all certificates in the following store*, and click *Browse*.

Select **Trusted Root Certification Authorities**, and click *Ok*.

Click *Next*, *Finish*.

You should get a message saying **The import was successful**.


After that is done, you can start the client up, and log in with your Akatsuki credentials.
