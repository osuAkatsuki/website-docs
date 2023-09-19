---
title: "Aika Befehle"
reference_version: 3003188120241d686c132ad8e88a11e2
---
Dies sind die Befehle für unseren Bot, Aika.

### Allgemeine Befehle
- `!roll` - Wählt eine zufällige Zahl von 0 bis 100 aus.
- `!roll <num>` - Wählt eine zufällige Zahl von 0 bis num aus.
- `!help` - Hilft dir.
- `!pp [mode]` - Zeigt dein PP. Ist der `mode` nicht vorhanden, so zeigt Aika dein PP vom aktuellen Spielmodus. Ist der Modus vorhanden (Also `std/taiko/ctb/mania`), so zeigt Aika dein PP für diesen Spielmodus. **Dieser Befehl funktioniert nur in PNs**
- `!update` - Aktualisiert das Beatmapset, welches du in unserem Beatmap-Mirror `/np`ed hast. Nutze dies, wenn du eine Beatmap von osu!direct downloadest, jedoch die Beatmap veraltet oder zu neu ist.

### FAQ Befehle
- `!faq rules`  
- `!faq swearing`  
- `!faq spam`  
- `!faq offend`  
- `!faq english`  
- `!faq github`  
- `!faq discord`  
- `!faq blog`  
- `!faq changelog`  
- `!faq status`  

### Tillerino-ähnliche Befehle
Aika hat ein paar Befehle, welche ähnlich für Tillerino sind. Diese Befehle funktionieren nur, wenn du Aika privat anschreibst. Vergiss nicht, dass das PP-System nur für osu!standard und osu!mania umgesetzt wurde. Momentan kann der Bot keine Beatmapvorschläge anbieten.

- `/np` - Zeigt PP für den momentanen Song an. (Nur für osu!standard)  
- `!last` - Zeigt Infos (und erhaltenes PP, falls es ein osu!standard-Score ist.)
- `!with <mods>` - Zeigt PP für die vorherige, angefragte Beatmap mit Mods an. Unterstütze Mods sind `NF, EZ, HD, HR, DT, HT, NC, FL, SO.`. Benutze keine Leerzeichen für mehrere Mods. (z.B.: `!with HDHR`)

### Admin Befehle
- `!system restart` - Neustart des Servers. Jede Verbindung wird getrennt und wieder automatisch verbunden.
- `!system status` - Zeigt den Serverstatus.
- `!system reload` - Neu laden der Banchoeinstellungen (, welche von RAP editierbar sind).
- `!system maintenance on/off` - An-/Ausschalten von Bancho's Wartungsmodus.
- `!moderated on/off` - An-/Ausschalten des gemäßigten Modus für den aktuellen Kanal.
- `!silence <username> <count> <unit (s/m/h/d)> <reason>` - Schalte einen Spieler stumm.
- `!unsilence <target>` - Entferne den Mute einer Person.
- `!kick <username>` - Kicke ein Spieler vom Server.
- `!ban <username>` - Bann und kick jemanden.
- `!unban <username>` - Entbann jemanden.  
- `!restrict <username>` - Restricte jemanden. 
- `!unrestrict <username>` - Unrestrict jemanden. 
- `!alert <message>` - Sende eine Benachrichtugung zu jedem Spieler, welcher Verbunden ist.
- `!alertu  <username> <message>` - Sende eine Benachrichtigung zu einem bestimmten Spieler.
