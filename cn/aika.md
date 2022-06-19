---
title: "Aika Commands"
old_id: 4
---
这里是机器人 Aika 或 chat bot 的使用说明.  

### 通用指令
- `!roll` - 返回 0 ~ 100 的一个随机数  
- `!roll num` - 返回 0 ~ num 的一个随机数
- `!help` - 显示帮助信息
- `!pp [mode]` - 显示你的当前 pp. 如果没有填写 `mode` , Aika 会告诉你当前模式的 pp. 如果你写了 `mode` (`std/taiko/ctb/mania`), Aika 会告诉你那个模式的 pp. **本指令仅私聊有效**
- `!update` - 更新你上次在地图镜像里 `/np` 的图. 如果你刚下了个图, 然后提示过期了, 但是点了更新一直提示你更新, 就用这个指令. 

### Faq 指令
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

### 类 Tillerino 指令
Aika 拥有类似 Tillerino 的指令. 这些指令只有在私聊才有用. 谨记 PP 系统只在 std 和 mania 有用. Aika 暂时不支持地图推荐指令, 不过应该快了, 咕咕咕.

- `/np` - 显示当前图的 PP (只在 std 模式有用)  
- `!last` - 显示上次提交成绩的信息 (以及获取 PP, 如果是 std 模式)
- `!with <mods>` - 显示上次请求的地图带 `mods` 的 PP 信息. 目前支持的 mods 有 `NF, EZ, HD, HR, DT, HT, NC, FL, SO.`. 多 mods 不要使用空格. (例: `!with HDHR`)

### 管理员指令
- `!system restart` - 重启服务器. 所有人都会被自动退出并重连
- `!system status` - 显示服务器状态 
- `!system reload` - 重读 bancho 设定 (the one that are editable from RAP)  
- `!system maintenance on/off` - 开关 bancho 的 maintenance 模式
- `!moderated on/off` - 开关当前频道的管理模式
- `!silence <username> <count> <unit (s/m/h/d)> <reason>` - 禁言用户
- `!removesilence <target>` - 解除禁言 
- `!kick <username>` - 踢出用户
- `!ban <username>` - 封禁用户
- `!unban <username>` - 解封用户
- `!restrict <username>` - 重定向用户
- `!unrestrict <username>` - 解除重定向用户
- `!fokabot reconnect` - 让 Aika 重新连接上服务器
- `!alert <message>` - 向所有在线玩家推送提示
- `!alertuser  <username> <message>` - 向特定用户推送提示
