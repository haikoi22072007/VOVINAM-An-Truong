# CLB Hub — Vovinam An Trường

Bản thử nghiệm tĩnh chạy trên GitHub Pages.

## Tính năng
- Tổng quan thành viên, lịch hoạt động, lượt điểm danh và quỹ
- Thêm/xóa thành viên
- Tạo hoạt động
- Điểm danh thành viên
- Ghi thu/chi và tính số dư
- Xuất dữ liệu JSON để sao lưu

## Triển khai
Đặt `index.html`, `manifest.json`, `sw.js` ở thư mục gốc repository, sau đó Settings → Pages → Deploy from a branch → `main` → `/(root)`.

## Quan trọng
Bản này lưu dữ liệu bằng localStorage trên từng trình duyệt. Không có tài khoản xác thực thật, phân quyền máy chủ hay đồng bộ giữa nhiều thiết bị. Không dùng cho dữ liệu nhạy cảm hoặc quản lý tài chính chính thức trước khi tích hợp backend an toàn.
