# Tùy chỉnh Clumsy Bird – Phiên bản của Hoàng Công Minh

Chơi đi chơi lại bản gốc của Clumsy Bird đôi khi trở nên nhàm chán?  
Tin vui là bạn hoàn toàn có thể tùy biến giao diện, nhân vật và hiệu ứng để tạo phiên bản mang dấu ấn cá nhân của riêng mình!

---

## 🎨 Thay đổi hình ảnh (assets)

Bạn có thể thay thế các hình ảnh sau trong thư mục `data/img/`.  
**Lưu ý:** Bạn nên **giữ nguyên kích thước và tên file** để tránh lỗi hiển thị trong game.

| Tên file         | Kích thước | Mô tả                                  |
| ---------------- | ---------- | -------------------------------------- |
| `bg.png`         | 900x504px  | Hình nền chính của game                |
| `clumsy.png`     | 255x60px   | Chim bay, gồm 3 frame animation        |
| `gameover.png`   | 245x132px  | Logo “Game Over” khi thua              |
| `gameoverbg.png` | 505x361px  | Nền cho bảng điểm                      |
| `getready.png`   | 405x134px  | Hiển thị trước khi bắt đầu chơi        |
| `ground.png`     | 900x96px   | Hình nền mặt đất chuyển động           |
| `logo.png`       | 351x145px  | Logo chính của trò chơi                |
| `new.png`        | 48x48px    | Hiệu ứng “NEW” khi đạt điểm mới        |
| `pipe.png`       | 148x1664px | Ống nước – dài để linh hoạt tạo độ cao |

---

## 🗃️ Các mục khác bạn có thể tùy chỉnh

- **Âm thanh:** thay thế trong `data/sfx/` (file `.mp3`, `.ogg`)
- **Logic game:** sửa các file trong `js/entities/` và `js/screens/`
- **Font chữ:** thay thế `data/css/gamefont.*` nếu muốn

---

## ✍️ Lưu ý cuối cùng

Bạn không cần sửa mã JavaScript nếu bạn chỉ thay đổi hình ảnh/âm thanh giữ nguyên tên và kích thước file.

Đây là bản tùy chỉnh Clumsy Bird của **Hoàng Công Minh** – bạn có thể chia sẻ, phát triển và sáng tạo thêm không giới hạn!
