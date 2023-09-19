---
title: "Kết nối tới Akatsuki"
old_id: 1
---

## Kết nối tới Akatsuki: Patcher

- Tải Akatsuki Patcher, bạn có thể tìm thấy đường dẫn [tại đây](https://akatsuki.gg/patcher).
- Chạy Akatsuki Patcher.
- Chúc bạn chơi game vui vẻ!

## Kết nối tới Akatsuki: Windows Shortcut

- Tìm file `osu!.exe` trên máy tính của bạn.
- Chuột phải vào file `osu!.exe` và chọn **Create Shortcut**.
- Chuột phải vào shortcut mới tạo và chọn **Properties**.
- Trong **Properties**, thêm `-devserver akatsuki.gg` vào ô **Target**.
- Bấm vào nút **Apply** để lưu các thay đổi.
- Tắt cửa sổ **Properties**.
- Chạy game từ shortcut mới tạo.
- Chúc bạn chơi game vui vẻ!

Nếu chưa hiểu, bạn có thể xem hướng dẫn bằng video [tại đây](https://youtu.be/vN8zqgmN_kI)!

## Kết nối tới Akatsuki: Linux 

- Mở launch script osu! của bạn.
- Nếu `"$@"` chưa có ở sau `osu!.exe`, thêm nó vào. Ví dụ, thay `wine osu\!.exe` thành `wine osu\!.exe "$@"`.
- Khi chạy script, thêm `-devserver akatsuki.gg`. Ví dụ, nếu bạn hay dùng `./osu.sh` để mở osu!, hãy dùng `./osu.sh -devserver akatsuki.gg`.

Nếu bạn chỉ chơi trên Akatsuki, bạn có thể thay `"$@"` bằng `-devserver akatsuki.gg`. Bằng cách này, bạn sẽ không cần phải gõ thêm server address mỗi lần bạn muốn chơi nữa!

## Kết nối tới Akatsuki: MacOS

### Nếu bạn đang chạy `osu!.exe` trực tiếp: 
- Tìm **EXE Flags** trong file properties.
- Thêm `-devserver akatsuki.gg` vào ô argument.
- Lưu các thay đổi rồi chạy nó bình thường.
- Chúc bạn chơi game vui vẻ!

### Nếu bạn đang chạy `osu!.exe` dùng một file bat (`execute.bat`):
- Mở **file bat** trong một trình chỉnh sửa file.
- Thêm `-devserver akatsuki.gg` vào cùng một dòng với start `C:\osu!\osu!.exe`.
- Lưu file và chạy nó như bình thường.
- Chúc bạn chơi game vui vẻ!

## Quay trở lại Bancho (server chính thức):

- Xoá `-devserver akatsuki.gg` khỏi shortcut bạn dùng để mở osu!.

Bạn nên giữ cả 2 shortcut: một cho [server chính thức](https://osu.ppy.sh) và một cái nữa cho Akatsuki. Vì lý do bảo mật, mỗi lần đổi server bạn sẽ phải nhập lại tài khoản và mật khẩu của mình.

## Nếu bạn vẫn cần giúp đỡ:

- Nếu bạn có bất kỳ trở ngại nào, hãy liên hệ chúng mình tại [Discord](https://akatsuki.gg/discord) nhé!
