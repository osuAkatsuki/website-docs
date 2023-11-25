---
title: Đề cử (rank) Beatmap
old_id: 69
---

# Quá trình để cử beatmap
Các map được gửi lên [server chính thức](https://osu.ppy.sh) nhưng không được đề cử (pending/graveyard) có thể được đề cử trên Akatsuki. Nếu bạn muốn "rank" một map, bạn phải gửi map vào đúng channel trong khu vực Nomination Request trên [Discord](https://akatsuki.gg/discord):

- `#nomination-std`: Dành cho map osu! [standard](https://osu.ppy.sh/wiki/en/Game_mode/osu!);
- `#nomination-taiko`: Dành cho map osu! [taiko](https://osu.ppy.shwiki/en/Game_mode/osu!taiko);
- `#nomination-ctb`: Dành cho map osu! [catch the beat](https://osu.ppy.sh/wiki/en/Game_mode/osu!catch);
- `#nomination-mania`: Dành cho map osu! [mania](https://osu.ppy.sh/wiki/en/Game_mode/osu!mania);

Khi map của bạn được gửi lên 1 trong 4 kênh trên và một Beatmap Nominator có thể kiểm tra map, họ sẽ kiểm tra map đó và quyết định xem map nên được **Ranked**, **Loved**, hay là giữ **Unranked**. Nếu bạn không vui với quyết định của một map, hoặc muốn report map ranked kém chất lượng - bạn phải gửi map đó vào kênh `#rank-discussion`.

# Nomination Statuses
Đây là một số các trạng thái nomination trên server và mục đích của chúng:

- **Ranked**: Map được rank dùng **mũi tên đúp hướng lên** trong màn hình chọn beatmap. Map ranked cho phép người chơi tranh hạng và lấy điểm PP khi set score. Trạng thái này được thay đổi bởi team Beatmap Nomination, hoặc server chính thức.
- **Approved**: Map được phê chuẩn dùng **icon dấu tick** trong màn hình chọn beatmap. Approved là một phần của hệ thống nomination cũ của server chính thức, và cho phép người chơi tranh hạng cũng như nhận điểm PP từ việc set scores. Trạng thái này chỉ có thể được áp dụng bởi server chính thức.
- **Qualified**: Các beatmap được qualified dùng **icon dấu tick** trong màn hình song selection. Nó sẽ vào queue, và sẽ được Ranked nếu map không bị disqualified. Trên Akatsuki, một khi map được chuyển từ **Qualified** sang **Ranked**, Điểm được gửi từ khi map đang qualified sẽ không bị xoá. Trạng thái này hiện chỉ được áp dụng bởi server chính thức.
- **Loved**: Các map được Loved dùng **hình trái tim** trong màn hình chọn map. Không giống như các map được Ranked, các map này sẽ không cho điểm PP. Trạng thái này được thay đổi bởi team Beatmap Nomination, hoặc server chính thức.
- **Unranked**: Map Unranked dùng **icon dấu hỏi** trong màn hình chọn map. Nó không có bảng xếp hạng, cũng không cho điểm PP và chỉ tính vào tổng Score của bạn (total score). Đây là trạng thái mặc định cho các beatmap.

# Nomination Criteria
Dưới đây là tiêu chí Nomination hiện có trên server. Do sự đa dạng của các chế độ chơi, mỗi chế độ có thể khác nhau một chút.

## Điều gì khiến một map được rank?
- Các map nhìn tổng quan tốt.

## Điều gì phiến một map bị loved?
- Các map có timing chưa chuẩn.
- Các map lạm dụng hệ thống PP.
- Các map 2B hoặc Aspire. Một số trường hợp ngoại lệ:
    - Chúng có thể được rank nếu như chúng không làm hỏng hệ thống PP hoặc hệ thống gửi điểm
- Các map không thể rank được nhưng khá nổi.
- Các map có hit object hoặc slider ẩn và không thể bấm được.
- Các map kém chất lượng và không được trau chuốt.
- Các mapset thay đổi độ khó ít một. Tất nhiên là tuỳ trượng hợp, ví dụ như:
    - Nếu một mapset có các độ khó chỉ edit BPM, BPM gốc sẽ được rank và còn lại sẽ chỉ được Loved. 
    - Nếu một mapset có các độ khó chỉ thay đổi AR, difficulty với AR cao nhất sẽ được rank, còn lại sẽ được Loved. 

## Điều gì khiến một map không thể được nominate tại đây?
- Các map có BN trong server chính thức. Nên đợi họ update/rank map trước khi request ở đây
- Map được đánh dấu là WIP hoặc Đang chờ trong server chính thức. Một số trường hợp ngoại lệ:
    - Nếu bạn đã liên hệ mapper và họ xác nhận là sẽ không thay đổi map nữa.
    - Nếu bạn là mapper và đang muốn rank map của chính mình.
- Các map liên quan tới vấn đề phân biệt chủng tộc, hoặc content NSFW (not safe for work).
- Các map được submit mà không có sự đồng ý của người làm map gốc.
- Các map chưa được hoàn thiện. Một số trường hợp ngoài lệ:
    - Nếu nó có đoạn bắt đầu và đoạn kết thúc một cách "đúng đắn".
- Các map được copy một cách trắng trợn.
- Các map khiến client kích hoạt ScoreV2.
