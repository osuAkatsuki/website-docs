---
title: "Comandos de Aika"
reference_version: 3003188120241d686c132ad8e88a11e2
---
Estos son los comandos compatibles con Aika, nuestro chatbot.

### Comandos generales
- `!roll` - Devuelve un numero aleatorio del 0 y 100
- `!roll <num>` - Devuelve un numero aleatorio del 0 al num
- `!help` - Muestra el mensaje de ayuda 

### Comandos de preguntas frecuentes (FAQ)
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
Aika tiene algunos comandos similares a Tillerino. Esos comandos funcionan solamente si los envias a Aika a través de un mensaje privado. Recuerda que el sistema de PP ha sido implementado solamente en osu!standard y osu!mania. El bot no soporta recomendaciones de beatmaps por el momento, esa funcionalidad llegará más adelante, con suerte. 

- `/np` - Muestra el PP para la canción que se esté reproduciendo actualmente (Solo si es una canción de osu! standard) 
- `!last` - Muestra información (y PP ganado, si fue una puntuación de osu! standard) acerca la última puntuación enviada 
- `!with <mods>` - Muestra el PP para el beatmap solicitado anteriormente con los mods solicitados. Los mods soportados son `NF, EZ, HD, HR, DT, HT, NC, FL, SO, RX, AP.`. No uses espacios para múltiples mods. (ej: `!with HDHR`)

### Comandos de admin
- `!system restart` - Reinicia el servidor. Todos serán desconectados y reconectados automáticamente  
- `!system status` - Muestra el estado del servidor  
- `!system reload` - Recarga las configuraciones de bancho (aquellos editables desde RAP)  
- `!system maintenance on/off` - Activa/desactiva el modo de mantenimiento de bancho  
- `!moderated on/off` - Activa/desactiva el modo moderado para el canal actual  
- `!silence <username> <count> <unit (s/m/h/d)> <reason>` - Silencia a un usuario  
- `!unsilence <target>` - Elimina el silencio de un usuario   
- `!kick <username>` - Expulsa a un usuario del servidor  
- `!ban <username>` - Banea y expulsa a alguien  
- `!unban <username>` - Desbanea a alguien  
- `!restrict <username>` - Restringe a alguien  
- `!unrestrict <username>` - Quita la restricción a alguien  
- `!alert <message>` - Envia una notificación a todos los usuarios conectados a bancho  
- `!alertu  <username> <message>` - Envia una notificación a un usuario específico
