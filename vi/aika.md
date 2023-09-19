---
title: "Các lệnh của Aika"
old_id: 4
---
Đây là những lệnh bạn có thể sử dụng với Aika, bot chat của Akatsuki.  

### General commands
- `!roll` - Trả kết quả một số ngẫu nhiên từ 0 đến 100  
- `!roll <số>` - Trả kết quả một số ngẫu nhiên từ 0 đến số đã cho
- `!help` - Hiển thị danh sách lệnh & cách dùng (như trang này)

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
Aika có một số lệnh cơ bản khá giống Tillerino. Chúng sẽ chỉ hoạt động nếu như bạn gửi PM cho Aika. Hiện tại bot chỉ tính được PP cho osu!standard và osu!mania và chưa thể gợi ý map cho bạn như Tillerino, nhưng hi vọng sắp tới sẽ có, chắc thế...

- `/np` - Hiển thị PP cho map bạn đang nghe/chơi (chỉ hoạt động với map osu!standard)  
- `!last` - Hiển thị thông tin (và PP nhận được, nếu đó là score osu! standard) của score cuối cùng bạn đã chơi (submit)   
- `!with <mods>` - Hiển thị PP cho map bạn đã `/np` trước đó với mod đã cho. Các mod được hỗ trợ là `NF, EZ, HD, HR, DT, HT, NC, FL, SO, RX, AP.`. Đừng dùng dấu cách nếu bạn muốn xem PP của 2 mod trở lên (vd: `!with HDHR`)

### Admin commands
- `!system restart` - Khởi động lại server. Tất cả mọi người sẽ bị ngắt kết nối và sẽ tự kết nối lại sau ít phút  
- `!system status` - Hiển thị tình trạng server  
- `!system reload` - Làm mới cài đặt bancho (mấy cái chỉnh được trong RAP)  
- `!system maintenance on/off` - Bật/tắt chế độ bảo trì
- `!moderated on/off` - Turn on/off moderated mode for the current channel  
- `!silence <username> <count> <unit (s/m/h/d)> <reason>` - Cho ai đó nín lại  
- `!unsilence <target>` - Bỏ chế độ nín của ai đó   
- `!kick <username>` - Đá một người khỏi server  
- `!ban <username>` - Cấm chơi và đá ai đó khỏi server  
- `!unban <username>` - Huỷ bỏ lệnh cấm chơi của ai đó  
- `!restrict <username>` - Cho ai đó vào danh sách hạn chế  
- `!unrestrict <username>` - Xoá ai đó khỏi danh sách hạn chế  
- `!alert <message>` - Gửi một thông báo cho tất cả các người dùng đang online
- `!alertu  <username> <message>` - Gửi thông báo tới một người nhất định trên server
