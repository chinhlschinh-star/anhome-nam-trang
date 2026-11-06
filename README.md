# Anhome 206 Nam Tràng: trang web

- `index.html`: toàn bộ trang (HTML + CSS + JS trong một file)
- `images/`: ảnh đã nén. `t3-*` là Tầng 3, `t2-*` là Tầng 2
- Muốn thêm hoặc bớt ảnh trong slideshow: sửa danh sách `G = { t3: [...], t2: [...] }` gần cuối `index.html`
- `_unused/`: ảnh tiện nghi cũ (giờ đã làm lại bằng HTML), không dùng nữa

## Đưa lên GitHub Pages (miễn phí)

1. Tạo repo mới trên github.com, ví dụ `anhome-nam-trang` (để Public)
2. Upload `index.html` và thư mục `images/` (dùng nút "Add file → Upload files")
3. Vào Settings → Pages → Source: "Deploy from a branch", Branch: `main` / `(root)` → Save
4. Sau 1–2 phút trang chạy ở `https://<tên-github>.github.io/anhome-nam-trang/`
5. (Tùy chọn) Gắn tên miền riêng ở Settings → Pages → Custom domain

## Nếu vẫn muốn giữ địa chỉ Google Sites

Google Sites chỉ cho chèn code vào một khung (iframe) có chiều cao cố định, nên không thể thay toàn bộ giao diện.
Cách gọn nhất: trong Google Sites chọn Chèn → Nhúng → "Theo URL", dán link GitHub Pages ở trên, rồi kéo khung cho cao hết trang.
Cách khác: để Google Sites chỉ còn một nút lớn trỏ sang trang GitHub Pages.
