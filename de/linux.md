---
title: "Wie verbindet man sich mit Akatsuki(Linux)"
reference_version: 8d9cbded63e0df5dc485e0401b25d8f8
---
Diese Anleitung dient nur für die Verbindung mit Akatsuki. Du kannst [dieser Anleitung](https://gist.github.com/Francesco149/a2f796683a4e5195458f4bb171d88eb0) folgen um dein Spiel einzustellen.

### 1. Modizifiere die hosts-Datei manuell
Alternativ kannst du die hosts-Datei manuel editieren. Führe `nano /etc/hosts` als root/with sudo aus.

Wenn es geöffnet ist, füge das Folgende ein:

```
{ipmain} c.ppy.sh ce.ppy.sh c3.ppy.sh c4.ppy.sh c5.ppy.sh c6.ppy.sh a.ppy.sh i.ppy.sh osu.ppy.sh
{ipmirror} bm6.ppy.sh
```
**CTRL+X** und dann **Enter** um die Datei zu speichern.

### 2. Installieren des Zertifikates
Lade dir das Zertifikat herunter, welches du [*hier*](https://old.akatsuki.gg/akatsuki.crt) findest.

Öffne die Konfiguration für den Internet Explorer, indem du `wine control` ausführst.

Doppelklick das *Internet Settings*-Symbol, gehe zum *Content* tab und klicke dann auf den *Certificates...*-Knopf

Klicke auf *Import*, dann *Next*.

Klicke auf *Browse...*, dann wähle Akatsuki's Zertifikat aus.

Klicke auf *Next*.

Wähle *Place all certificates in the following store* aus und klicke auf *Browse*.

Wähle **Trusted Root Certification Authorities** aus und klicke auf *Ok*.

Klicke auf *Next*, dann *Finish*.

Du solltest eine Nachricht bekommen, die sagt **The import was successful**.


Danach kannst du den Client öffnen und dich in Akatsuki einloggen.
