# Frontend Elearning English

Chào mừng bạn đến với dự án Frontend của hệ thống học tiếng Anh Elearning. Dự án này được xây dựng bằng React.js.

## 🔗 Liên kết quan trọng
- **Backend Repository:** [BackendFlutterAppElearningEnglish](https://github.com/NguyenVanNam121204/BackendFlutterAppElearningEnglish)
- **Hướng dẫn Backend:** Vui lòng tải Backend từ link trên và làm theo hướng dẫn trong README của repository đó để khởi chạy máy chủ.

## 🚀 Hướng dẫn khởi chạy Frontend

### 1. Cài đặt môi trường
Đảm bảo máy tính của bạn đã cài đặt:
- [Node.js](https://nodejs.org/) (Phiên bản 16.x hoặc mới hơn)
- npm hoặc yarn

### 2. Các bước thực hiện

1. **Di chuyển vào thư mục dự án:**
   ```powershell
   cd FrontElearningEnglish
   ```

2. **Cài đặt các thư viện (dependencies):**
   ```powershell
   npm install
   ```

3. **Cấu hình biến môi trường:**
   - Tạo file `.env` (nếu chưa có) dựa trên file `.env.example`.
   - Đảm bảo URL của Backend được cấu hình chính xác để Frontend có thể kết nối.

4. **Khởi chạy ứng dụng:**
   ```powershell
   npm start
   ```
   Ứng dụng sẽ chạy tại địa chỉ: `http://localhost:3000`

## 📂 Cấu trúc thư mục chính
- `src/Components`: Chứa các thành phần giao diện của ứng dụng.
- `src/Pages`: Các trang chính của hệ thống.
- `src/Services`: Các file API client để kết nối với Backend.
- `src/Context`: Quản lý trạng thái ứng dụng (Auth, Theme, v.v.).

## 🛠 Công nghệ sử dụng
- **React.js**
- **Axios** (Kết nối API)
- **Lucide React** (Icons)
- **CSS Modules / Tailwind CSS** (Giao diện)
