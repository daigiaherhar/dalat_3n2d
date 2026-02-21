# 🌲 Lịch trình Đà Lạt 3N2Đ

Lịch trình 3 ngày 2 đêm – chill, nhậu, ngắm hoàng hôn & bình minh. Địa điểm hot, mới.

## 📂 Cấu trúc web (host GitHub Pages)

```
├── index.html          ← Trang chủ (mở khi vào site)
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── dalat_binh_minh.png
│   ├── dalat_hoang_hon_chill.png
│   └── dalat_kombi_cactus.png
├── README.md
└── .gitignore
```

## 🚀 Đưa lên GitHub & bật GitHub Pages

1. **Tạo repo trên GitHub**
   - Vào [github.com](https://github.com) → New repository.
   - Đặt tên repo (vd: `da-lat-3n2d` hoặc `lich-trinh-da-lat`).
   - Chọn Public, **không** tick "Add a README" (đã có sẵn trong folder).
   - Create repository.

2. **Push code lên GitHub** (trong thư mục project):

   ```bash
   git init
   git add .
   git commit -m "Lịch trình Đà Lạt 3N2Đ - web GitHub Pages"
   git branch -M main
   git remote add origin https://github.com/USERNAME/REPO_NAME.git
   git push -u origin main
   ```
   Thay `USERNAME` và `REPO_NAME` bằng tên GitHub và tên repo của bạn.

3. **Bật GitHub Pages**
   - Vào repo → **Settings** → **Pages** (menu trái).
   - **Source**: Deploy from a branch.
   - **Branch**: `main` (hoặc `master`) → folder **/ (root)**.
   - Save.

4. **Xem site**
   - Sau vài phút, site sẽ có tại:  
     **https://USERNAME.github.io/REPO_NAME/**

## 📷 Ảnh minh họa

Trang dùng 3 ảnh trong `assets/`:

| File | Mô tả |
|------|--------|
| `dalat_binh_minh.png` | Bình minh Đà Lạt |
| `dalat_hoang_hon_chill.png` | Chill hoàng hôn |
| `dalat_kombi_cactus.png` | Kombi Land |

Nếu bạn đã tạo ảnh trong Cursor, copy 3 file trên từ thư mục **assets** của project vào `assets/` rồi commit & push để ảnh hiện trên web.

## 📄 File khác

- **lich_trinh_da_lat_3n2d.html** – Bản lịch trình đơn file (mở trực tiếp bằng trình duyệt, không cần host).
