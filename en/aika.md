---
title: "Aika Commands"
old_id: 4
---
These are the commands supported by Aika, our chat bot.  

### General commands
- `!roll` - Returns a random number from 0 to 100  
- `!roll <num>` - Returns a random number from 0 to num  
- `!help` - Display help message  

### Faq commands
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

### Tillerino-like commands
Aika has some commands similar to Tillerino. Those commands work only if you send them to Aika through a PM. Remember that PP system has been implemented only on osu!standard and osu!mania. The bot doesn't support beatmaps recommendations at the moment, that functionality wil come later, hopefully.

- `/np` - Show PP for the current playing song (only if is a osu! standard song)  
- `!last` - Show info (and gained PP, if it was an osu! standard score) about the last submitted score  
- `!with <mods>` - Show PP for the previous requested beatmap with requested mods. Supported mods are `NF, EZ, HD, HR, DT, HT, NC, FL, SO, RX, AP.`. Don't use spaces for multiple mods (eg: `!with HDHR`)

### Admin commands
- `!system restart` - Restart the server. Everyone will be disconnected and reconnected automatically  
- `!system status` - Show server status  
- `!system reload` - Reload bancho settings (the one that are editable from RAP)  
- `!system maintenance on/off` - Turn on/off bancho maintenance mode  
- `!moderated on/off` - Turn on/off moderated mode for the current channel  
- `!silence <username> <count> <unit (s/m/h/d)> <reason>` - Silence a user  
- `!unsilence <target>` - Remove target's silence   
- `!kick <username>` - Kick an user from the server  
- `!ban <username>` - Ban and kick someone  
- `!unban <username>` - Unban someone  
- `!restrict <username>` - Restrict someone  
- `!unrestrict <username>` - Unrestrict someone  
- `!alert <message>` - Send a notification to every user connected to bancho  
- `!alertu  <username> <message>` - Send a notification to a specific user
