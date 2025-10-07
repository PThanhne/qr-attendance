# 📷 QR Attendance

Ứng dụng điểm danh bằng mã QR, được viết bằng **React + ZXing**.

---

## 🚀 Tính năng chính

- Quét mã QR có định dạng `ATTEND:<MSSV>`
- Tự động lưu lịch sử điểm danh gồm:
  - Mã số sinh viên (MSSV)
  - Thời gian quét
- Xuất danh sách điểm danh ra file **CSV**
- Nút **Reset** để xoá toàn bộ lịch sử
- Cảnh báo nếu mã QR không hợp lệ

---

## 🧰 Công nghệ sử dụng

- **React** (CRA hoặc Vite)
- **@zxing/browser** – thư viện quét QR code
- **HTML5 getUserMedia** để truy cập camera

---

## 🖥️ Cách chạy project

```bash
# 1. Cài đặt dependencies
npm install

# 2. Chạy project
npm run dev   # hoặc npm start (tuỳ vào setup)
