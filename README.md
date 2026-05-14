# Lab-Windows-Fundamentals-1

ở phần này, em đọc nội dung lab thì thấy windows hiện tại có nhiều phiên bản khác nhau, trong đó bản phổ biến là home và pro

câu hỏi lab hỏi là:

```
what encryption can you enable on pro that you can't enable in home?

```

hiểu đơn giản là lab đang hỏi: tính năng mã hóa nào có thể bật trên bản pro, nhưng bản home thì không bật được đầy đủ

sau khi xem sự khác nhau giữa windows home và windows pro, em thấy tính năng đó là:

```
bitlocker
```
### writeup lab – windows desktop

ở task này, em học về **windows desktop/gui**, là giao diện hiện ra sau khi đăng nhập vào windows. trong bài có nhắc các thành phần chính như **desktop**, **start menu**, **search box**, **task view**, **taskbar**, **toolbars** và **notification area**. 

với câu hỏi:

```text
which selection will hide/disable the search box?
```

ban đầu em dựa vào phần taskbar settings và chọn đáp án:

```text
hidden
```

đáp án này đúng vì muốn ẩn ô search trên taskbar thì chọn **hidden**.

tiếp theo, câu hỏi:

```text
which selection will hide/disable the task view button?
```

lúc đầu em trả lời sai theo kiểu mô tả hành động là:

```text
hide task view button
```

nhưng lab báo sai, vì nó cần đúng tên selection trong windows. sau đó em sửa lại thành:

```text
show task view button
```

lý do là mục **show task view button** dùng để bật/tắt nút task view. muốn ẩn nó thì bỏ tick ở mục này.

cuối cùng, câu hỏi:

```text
besides clock and network, what other icon is visible in the notification area?
```

ban đầu em nghĩ đáp án là:

```text
volume
```

vì trong bài có nhắc notification area có thể hiện **volume icon** và **network/wireless icon**. nhưng đáp án này không khớp format vì chỉ có 6 chữ. khi thấy gợi ý còn **1 space và 6 dấu _**, em biết đáp án phải có dạng `______ ______`.

vì vậy em sửa lại thành:

```text
action center
```

em biết vậy vì **action center** khớp đúng format: `action` 6 chữ, `center` 6 chữ, ở giữa có 1 dấu cách. đây cũng là đáp án đúng được lab xác nhận. 
