# ⚔️ THE SYSTEM — Hunter Goal & Discipline Management

> *Hệ thống quản lý mục tiêu cá nhân (To-Do List) phong cách Manhwa Thợ Săn thức tỉnh, tích hợp cơ chế Gamification RPG và tự động đồng bộ đám mây đa thiết bị.*

---

## 🌟 Giới thiệu

**« THE SYSTEM »** không chỉ là một ứng dụng ghi chú công việc thông thường. Lấy cảm hứng từ giao diện "Hệ Thống" trong các bộ truyện tranh thợ săn (*Solo Leveling* vibe), ứng dụng biến các mục tiêu hằng ngày, bài tập và dự án thực tế của bạn thành các **Nhiệm vụ Thức Tỉnh (Quests)**. 

Hoàn thành mục tiêu để tích lũy **EXP**, thăng cấp bậc Thợ Săn (từ Hạng E đến Hạng S), mở khóa danh hiệu và gia tăng các chỉ số thuộc tính cá nhân: **STR, INT, VIT, DEX**.

---

## ✨ Tính năng nổi bật

* **Giao diện Liquid Dark Glassmorphism:** Thiết kế sang trọng trên nền tối than chì kết hợp kính mờ đa tầng, quầng sáng khúc xạ ngầm và hiệu ứng nổi khi lia chuột.
* **Tự động phân loại thông minh (Keyword Auto-Detection):**
  * Tự động quét nội dung công việc để phân bổ chỉ số tương ứng (**STR** cho thể chất, **INT** cho học tập/code, **VIT** cho sức khỏe/sinh hoạt, **DEX** cho kỷ luật/deadline).
  * Tự động chấm điểm độ khó và gán Rank từ **Hạng E** đến **Hạng S**.
* **Thanh Hạn Chót 1-Chạm:** Thiết lập deadline tức thì với các phím tắt nhanh (`+1h`, `+3h`, `Tối nay 23:59`, `Ngày mai`, `+3 ngày`).
* **Chuỗi Kỷ Luật & Hệ số Bổng lộc (Streak Multiplier):** Duy trì chuỗi ngày liên tục để kích hoạt các tầng buff EXP (`x1.2`, `x1.5`, `x2.0`).
* **Lịch Rèn Luyện Tương Tác:** Theo dõi nhật ký điểm danh theo tháng, hỗ trợ lọc nhanh các nhiệm vụ theo ngày cụ thể chỉ bằng 1 cú nhấp.
* **Chuông Cảnh Báo Hệ Thống:** Nhắc nhở điểm danh hàng ngày và phát tín hiệu cảnh báo với các nhiệm vụ sắp hết hạn (< 2 giờ) hoặc đã quá hạn.
* **Tùy biến Thợ Săn:** Hỗ trợ kho diện mạo *Shadow Hunter* mẫu hoặc tự tải ảnh đại diện từ thiết bị.
* **Bảng Vinh Danh (Leaderboard):** Bảng xếp hạng thợ săn trực quan dựa trên cấp độ và số ngày kỷ luật liên tục.
* **Tự Động Đồng Bộ Đám Mây (Cloud Auto-Sync):**
  * Cơ chế *Offline-first*: Dùng ngay không cần đăng nhập (lưu `localStorage`).
  * Tự động đồng bộ ngầm hai chiều lên **Google Sheets** qua Google Apps Script Web App khi liên kết Tên & Passcode.

---

## 🛠️ Công nghệ sử dụng

* **Frontend:** HTML5, Tailwind CSS, JavaScript (ES6+), FontAwesome 6, Canvas Confetti.
* **Typography:** `Inter` (UI), `JetBrains Mono` (Data HUD).
* **Backend / Database:** Google Apps Script (GAS) API + Google Sheets.
* **Hosting:** GitHub Pages.

---

## 🚀 Hướng dẫn triển khai lên GitHub Pages

1. **Fork** hoặc tải mã nguồn về máy tính:
   ```bash
   git clone [https://github.com/](https://github.com/)<tai-khoan-cua-ban>/the-system.git
