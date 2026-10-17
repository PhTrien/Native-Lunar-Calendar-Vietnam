<img width="1920" height="1080" alt="Screenshot (461)" src="https://github.com/user-attachments/assets/f673594a-08ca-417c-a0a1-ea179ce343cd" />

## English

This mod integrates the Vietnamese lunar calendar directly into the Windows 11 taskbar calendar flyout.

### Features
* **Preserves the native Windows 11 design language:** Integrates cleanly into the system calendar flyout without external floating overlays or heavy UI modifications.
* **Full compatibility:** Works smoothly alongside **Windows 11 Notification Center Styler**, **Start Menu Styler**, and **Taskbar Styler**.
* **Accurate Hồ Ngọc Đức lunar algorithm (UTC+7):** Accurately computes new moon days, solar terms, leap months, and lunar new year transitions.
* **Holiday & festival names:** Shows short names of traditional Vietnamese holidays and international observances (Tết, Giỗ Tổ, 30/4, 2/9, Christmas, etc.).
* **Custom events:** Add personal anniversaries, birthdays, and reminders (by solar or lunar date) directly in Settings.
* **Weekend & special day highlighting:** Highlights Saturdays, Sundays, New Moon (1st), and Full Moon (15th) days.
* **Modern today indicator:** Optional subtle translucent rounded square indicator for the current date.

### Requirements & Setup
This mod requires Windows' built-in secondary calendar feature to be enabled so that the native calendar cells provide the necessary label element:
* Go to **Settings > Time & language > Date & time**.
* Under **Show additional calendars in the taskbar**, select **Simplified Chinese (Lunar)** or **Traditional Chinese (Lunar)**.
* The mod will seamlessly replace the default lunar text with accurate Vietnamese lunar dates, festivals, and custom events!

---

## Tiếng Việt

Bản mod tích hợp lịch âm Việt Nam trực tiếp vào bảng lịch hệ thống Windows 11.

### Tính năng nổi bật
* **Hòa nhập với phong cách Windows 11:** Tích hợp liền mạch vào giao diện lịch Windows 11 gốc, không dùng cửa sổ nổi hay can thiệp nặng nề. Các tùy chọn làm nổi bật như viền bo góc ngày hiện tại hay bôi đỏ thứ cuối tuần có thể tùy chỉnh hoặc tắt trong Cài đặt.
* **Tương thích hoàn toàn:** Hoạt động mượt mà cùng lúc với **Windows 11 Notification Center Styler**, **Start Menu Styler** và **Taskbar Styler**.
* **Thuật toán âm lịch Hồ Ngọc Đức chuẩn xác (UTC+7):** Tính đúng ngày Sóc, điểm Hoàng kinh mặt trời, tháng nhuận và chuyển năm âm lịch.
* **Bôi đỏ & Tên ngày Lễ:** Hiển thị tên rút gọn các dịp lễ Tết truyền thống Việt Nam và ngày lễ quốc tế.
* **Sự kiện quan trọng cá nhân:** Cho phép tạo danh sách ngày kỷ niệm, sinh nhật theo cả Dương lịch lẫn Âm lịch ngay trong Settings!
* **Bôi đỏ ngày Cuối tuần, Mùng 1 và Rằm (15 âm):** Giúp theo dõi ngày sóc vọng thuận tiện.

### Yêu cầu & Hướng dẫn cài đặt
Bản mod yêu cầu kích hoạt tính năng lịch phụ trong Windows để các ô ngày có sẵn thành phần nhãn hiển thị:
* Mở **Settings > Time & language > Date & time**.
* Tại mục **Show additional calendars in the taskbar**, chọn **Simplified Chinese (Lunar)** hoặc **Traditional Chinese (Lunar)**.
* Mod sẽ tự động thay thế phần chữ lịch phụ bằng ngày âm lịch Việt Nam chuẩn xác cùng tên các ngày lễ, sự kiện!

---

## Credits / Lời cảm ơn

This mod is based on the calendar plumbing and UI hooks from:
* [Chinese Holiday Calendar](https://github.com/ramensoftware/windhawk-mods/blob/main/mods/chinese-holiday-calendar.wh.cpp) by dcsmf (GPL-3.0-only)
* [Agenda in Calendar View](https://github.com/ramensoftware/windhawk-mods/blob/main/mods/agenda-in-calendar-view.wh.cpp) by lonfro (GPL-3.0-only)
* [Windows 11 Notification Center Styler](https://github.com/ramensoftware/windhawk-mods/blob/main/mods/windows-11-notification-center-styler.wh.cpp) by m417z (GPL-3.0-only)
* Vietnamese lunar calendar calculation algorithm by [Hồ Ngọc Đức](https://www.informatik.uni-leipzig.de/~duc/amlich/).
