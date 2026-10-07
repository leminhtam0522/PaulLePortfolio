# Paul Le — Personal Portfolio Website

Portfolio cá nhân của **Lê Minh Tâm (Paul Le)** — Học viên Thạc sĩ Quản trị Kinh doanh tại Đài Loan.  
Trang web giới thiệu về hành trình học tập, kinh nghiệm làm việc thực tế, các dự án cộng tác quốc tế và thuyết trình hội nghị.

---

## 🛠️ Công nghệ sử dụng
- **Cấu trúc & Nội dung:** Semantic HTML5 thuần, hiện đại, tối ưu SEO và Accessibility.
- **Giao diện & Phong cách:** Vanilla CSS với Dark Mode sang trọng, typography cân đối (Instrument Serif & Inter), hiệu ứng micro-animations mượt mà.
- **Tương tác:** Vanilla JavaScript (hỗ trợ Lightbox phóng to ảnh đầy đủ, điều hướng cuộn mượt, bộ đệm an toàn khi tải).
- **Tính độc lập & Di động:** Tất cả 7 ảnh thực tế và bản PDF CV đã được nhúng an toàn, đảm bảo hiển thị tức thì trên mọi nền tảng mà không bị phụ thuộc tài nguyên ngoài.

---

## 🚀 Hướng dẫn Triển khai trên Vercel (Vercel Deployment)

Dự án này là website tĩnh chuẩn (Pure HTML/CSS/JavaScript), sẵn sàng chạy ngay khi import từ GitHub vào Vercel với cấu hình sau:

| Thông số cấu hình | Giá trị cài đặt trên Vercel | Ghi chú |
|---|---|---|
| **Root Directory** | `./` (để trống hoặc mặc định) | Toàn bộ dự án nằm ở thư mục gốc |
| **Framework Preset** | `Other` | Dự án HTML/CSS/JS thuần, không dùng framework build |
| **Build Command** | *Để trống (None)* | Không cần lệnh build |
| **Output Directory** | `.` (hoặc để trống) | Trang chính là `index.html` tại thư mục gốc |
| **Production Branch** | `main` | Nhánh triển khai chính |

---

## 📂 Cấu trúc thư mục
```
├── index.html                  # File chính chạy trên Vercel và trình duyệt web
├── Paul Le Portfolio .html     # Bản gốc của Portfolio
├── vercel.json                 # Cấu hình routing tĩnh trên Vercel
├── .gitignore                  # Bỏ qua node_modules, logs và file tạm
├── README.md                   # Hướng dẫn chi tiết dự án & cấu hình Vercel
└── Image/                      # Thư mục lưu trữ ảnh gốc và ảnh tối ưu
    ├── banco.jpg / banco.JPG   # Workplace photograph
    ├── tour.jpg / tour.JPG     # Class tour photograph
    ├── kyoto.jpg               # Conference presentation photograph
    ├── portrait.jpg            # Personal portrait
    ├── international.jpg       # International classmates photograph
    ├── teamwork.jpg            # Class project photograph
    └── contact.jpg             # Contact portrait
```

---

## 📱 Khả năng tương thích
Đã được kiểm thử và xác nhận hoạt động hoàn hảo trên các độ phân giải:
- **Desktop lớn / 2K:** 2560 × 1440
- **Desktop tiêu chuẩn Full HD:** 1920 × 1080
- **Laptop phổ thông:** 1366 × 768
- **Thiết bị di động:** Màn hình điện thoại (Responsive chuẩn 1 cột, chạm vuốt mượt mà)
