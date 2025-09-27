# 📖 Hướng dẫn sử dụng – WinUtilPro Installer

## 1. Giới thiệu
WinUtilPro Installer là công cụ giúp bạn cài nhiều ứng dụng Windows cùng lúc, dựa trên `winget` và script tùy chỉnh.  
Phần mềm có 2 chế độ:
- **Basic (Free)**: giới hạn số ứng dụng mỗi lượt.
- **Premium**: mở toàn bộ tính năng, không giới hạn.

---

## 2. Màn hình chính


### Thành phần chính
- **Danh mục (Categories)**:  
  - *Favorites*: hiển thị app bạn đánh dấu ★.  
  - Các category khác (*Browsers*, *Office*, *Dev Tools*, *System*...).  
- **Thanh tìm kiếm**: nhập từ khóa để lọc app nhanh.  
- **Danh sách ứng dụng**: tick chọn app cần cài đặt.  
- **Sidebar**: nút *Chọn tất cả*, *Bỏ chọn tất cả*, *Ẩn/Hiện log*.  
- **Log Panel**: hiển thị tiến trình cài đặt (có thể ẩn để giảm lag).

---

## 3. Cài đặt ứng dụng

1. Mở phần mềm.  
2. Chọn category hoặc Favorites.  
3. Tick các ứng dụng cần cài.  
4. Nhấn **Install**.  
5. Theo dõi quá trình trong **Log Panel**.  

👉 Với Premium: bạn có thể **xuất script `.bat`** hoặc **chạy trực tiếp WinUtil.ps1** để tái sử dụng.

---

## 4. Quản lý Favorites

- Tick app → nhấn nút ★ để thêm vào Favorites.  
- Vào mục **Favorites** để cài nhanh các app thường dùng.  
- Rất tiện khi cài lại máy mới: chỉ cần mở Favorites, tick, Install.

---

## 5. About / Premium

- Tab **About**: thông tin phiên bản, mô tả, link GitHub/Docs.  
- Tab **Premium**: so sánh Basic vs Premium, nhập/xóa License, nút nâng cấp.  

---

## 6. Tính năng Premium

- Không giới hạn số app cài cùng lúc.  
- Thêm flag nâng cao:  
  - `--silent` (cài yên lặng)  
  - `--upgrade` (cập nhật app)  
  - `--force` (ép cài)  
  - `--admin` (chạy với quyền quản trị)  
- Xuất file `.bat` hoặc chạy trực tiếp PowerShell script.  
- Tuỳ chọn nâng cao khác.  

---

## 7. Mẹo sử dụng

- **Ẩn log** khi không cần theo dõi để phần mềm chạy mượt hơn.  
- Dùng **Favorites** để cài nhanh bộ app quen thuộc.  
- Nếu muốn tái sử dụng nhiều lần → xuất `.bat` (Premium).  
- Nhấn **Ctrl+F** để tìm app nhanh, **Ctrl+A** để chọn tất cả, **Ctrl+D** bỏ chọn tất cả, **Esc** xoá ô tìm kiếm.  

---

## 8. Hỗ trợ & Liên hệ

- Repo GitHub: [longurara/winutilpro-installer](https://github.com/longurara/winutilpro-installer)  
- Tác giả: **longurara**  

---
