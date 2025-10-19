# 🌷 Tặng Nè - Website Chúc Mừng 20/10

Website chúc mừng ngày Phụ nữ Việt Nam 20/10 với hiệu ứng đẹp mắt.

## ✨ Tính năng

- 🌸 **Trang chào mừng** với bó hoa tulip và QR code
- 💐 **Hoa rơi** liên tục với hiệu ứng đẹp mắt
- 🎵 **Nhạc nền** tự động phát
- 🌺 **Thư/quà rơi** từ trên xuống, click để xem lời chúc
- 💕 **Responsive** - đẹp trên mọi thiết bị

## 🚀 Cách sử dụng

1. Mở file `welcome.html` để bắt đầu
2. Click vào bó hoa để chuyển sang trang chúc mừng
3. Click vào các thư/quà rơi xuống để xem lời chúc

## 📁 Cấu trúc file

```
├── welcome.html          # Trang chào mừng với QR code
├── index.html           # Trang chúc mừng chính
├── tulip-gift.html      # Trang bó hoa tulip (dự phòng)
└── assets/              # Thư mục chứa hình ảnh, nhạc
    ├── hoaqrcode.png    # Hình bó hoa QR code
    ├── a.mp3            # Nhạc nền
    ├── a1.jpg - a5.jpg  # Hình ảnh cho popup
    ├── letters.png      # Hình thư
    ├── h1.png, h3.png   # Hình hoa
    ├── q3.png           # Hình quà
    └── t2.png, t5.png   # Hình khác
```

## 🎨 Tùy chỉnh

### Thay đổi lời chúc
Mở `index.html`, tìm mảng `messages` (dòng ~424):
```javascript
const messages = [
    {
        img: "./assets/a1.jpg",
        text: "Lời chúc của bạn"
    },
    // Thêm nhiều lời chúc khác...
];
```

### Thay đổi nhạc nền
Thay file `./assets/a.mp3` bằng file nhạc của bạn

### Thay đổi hình ảnh
Thay các file trong thư mục `assets/`

## 💖 Demo

Truy cập: [Link sẽ có sau khi deploy]

## 📝 License

Free to use - Made with ❤️
