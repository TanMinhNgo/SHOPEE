# 🛒 Shopee Clone - MT-Shop

Một trang web thương mại điện tử được xây dựng theo mô hình Shopee, chuyên về mỹ phẩm và làm đẹp.

## 📋 Mô tả dự án

MT-Shop là một trang web bán hàng trực tuyến được thiết kế theo phong cách của Shopee, tập trung vào việc bán các sản phẩm mỹ phẩm và chăm sóc sắc đẹp. Website được xây dựng hoàn toàn bằng HTML, CSS và JavaScript thuần, có thiết kế responsive và giao diện thân thiện với người dùng.

## ✨ Tính năng chính

### 🏠 Trang chủ
- Header với thanh điều hướng đầy đủ
- Thanh tìm kiếm với gợi ý lịch sử
- Giỏ hàng với hiển thị số lượng sản phẩm
- Menu danh mục sản phẩm
- Hiển thị danh sách sản phẩm với grid layout
- Hệ thống phân trang

### 🛍️ Sản phẩm
- Hiển thị thông tin chi tiết sản phẩm
- Đánh giá sao và số lượng đã bán
- Tính năng yêu thích sản phẩm
- Nhãn giảm giá và khuyến mãi
- Thông tin thương hiệu và xuất xứ

### 📱 Responsive Design
- Tối ưu cho máy tính để bàn
- Thích ứng với tablet
- Giao diện mobile thân thiện
- Menu di động riêng biệt

### 🎨 Giao diện người dùng
- Thiết kế hiện đại, màu sắc hài hòa
- Sử dụng Font Awesome icons
- Hiệu ứng hover và transition mượt mà
- Layout grid system linh hoạt

## 🗂️ Cấu trúc thư mục

```
SHOPEE/
├── index.html                 # Trang chủ chính
├── README.md                  # Tài liệu dự án
└── assests/
    ├── css/
    │   ├── base.css          # CSS cơ bản và reset
    │   ├── grid.css          # Hệ thống grid layout
    │   ├── responsive.css    # CSS responsive
    │   └── style.css         # CSS chính của dự án
    ├── fonts/
    │   └── fontawesome-free-6.6.0-web/  # Font Awesome icons
    └── img/
        ├── 5b6e787c2e5ee052.png  # QR code
        ├── apple.png             # App Store logo
        ├── cart.png              # Biểu tượng giỏ hàng
        ├── google.png            # Google Play logo
        ├── user.jpg              # Avatar người dùng
        └── ohui*.png             # Hình ảnh sản phẩm
```

## 🚀 Cách sử dụng

### Yêu cầu hệ thống
- Trình duyệt web hiện đại (Chrome, Firefox, Safari, Edge)
- Không cần cài đặt thêm phần mềm

### Chạy dự án
1. **Clone repository:**
   ```bash
   git clone https://github.com/TanMinhNgo/SHOPEE.git
   ```

2. **Di chuyển vào thư mục dự án:**
   ```bash
   cd SHOPEE
   ```

3. **Mở trang web:**
   - Cách 1: Mở file `index.html` trực tiếp bằng trình duyệt
   - Cách 2: Sử dụng Live Server (khuyến nghị)
     ```bash
     # Nếu sử dụng VS Code với Live Server extension
     # Nhấp chuột phải vào index.html → "Open with Live Server"
     ```

4. **Truy cập website:**
   - Mở trình duyệt và truy cập: `http://localhost:5500` (nếu dùng Live Server)
   - Hoặc mở trực tiếp file `index.html`

## 🛠️ Công nghệ sử dụng

- **HTML5:** Cấu trúc trang web semantic
- **CSS3:** 
  - Flexbox và Grid Layout
  - CSS Variables
  - Media Queries cho responsive
  - Transitions và animations
- **Font Awesome 6.6.0:** Icons và biểu tượng
- **Google Fonts:** Font chữ Roboto
- **Normalize.css:** Reset CSS cho tính nhất quán

## 📱 Responsive Breakpoints

```css
/* Mobile */
@media (max-width: 739px) { }

/* Tablet */
@media (min-width: 740px) and (max-width: 1023px) { }

/* Desktop */
@media (min-width: 1024px) { }
```

## 🎯 Tính năng nổi bật

### 🔍 Tìm kiếm thông minh
- Thanh tìm kiếm với placeholder động
- Lịch sử tìm kiếm
- Tùy chọn tìm kiếm trong shop hoặc ngoài shop

### 🛒 Giỏ hàng
- Hiển thị số lượng sản phẩm
- Preview sản phẩm trong giỏ hàng
- Tính năng xem giỏ hàng

### 👤 Người dùng
- Hiển thị thông tin người dùng
- Avatar và tên người dùng
- Menu dropdown cho tài khoản

### 📊 Sản phẩm
- Hiển thị giá gốc và giá khuyến mãi
- Đánh giá sao 5 cấp độ
- Số lượng đã bán
- Thương hiệu và xuất xứ
- Nhãn "Yêu thích" và phần trăm giảm giá

## 🎨 Color Palette

```css
:root {
    --primary-color: #ee4d2d;
    --white-color: #fff;
    --black-color: #000;
    --text-color: #333;
    --border-color: #dbdbdb;
    --star-gold-color: #ffce3e;
}
```

## 📂 File CSS chính

- **base.css:** CSS reset, biến CSS, utility classes
- **grid.css:** Hệ thống grid 12 cột responsive
- **style.css:** Styles chính cho các component
- **responsive.css:** Media queries và responsive styles

## 🤝 Đóng góp

1. Fork dự án
2. Tạo branch cho tính năng mới (`git checkout -b feature/TinhNangMoi`)
3. Commit thay đổi (`git commit -m 'Thêm tính năng mới'`)
4. Push to branch (`git push origin feature/TinhNangMoi`)
5. Tạo Pull Request

## 📄 License

Dự án này được phát hành dưới [MIT License](LICENSE).

## 👨‍💻 Tác giả

**Ngô Minh Tân**
- GitHub: [@TanMinhNgo](https://github.com/TanMinhNgo)

## 📞 Liên hệ

Nếu bạn có bất kỳ câu hỏi nào về dự án, vui lòng tạo issue hoặc liên hệ trực tiếp.

---

⭐ Nếu bạn thấy dự án này hữu ích, hãy give nó một star nhé!
