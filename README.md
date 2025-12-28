# 🏸 Project_CourtBadminton

## 📌 Giới thiệu
**Project_CourtBadminton** là một ứng dụng **đặt sân cầu lông** được phát triển trong khuôn khổ **môn học** tại trường.  
Dự án được xây dựng theo mô hình **Client – Server**, trong đó:

- **Frontend**: React Native (Expo)  
- **Backend**: Node.js + Express  
- **State Management**: @reduxjs/toolkit  
- **Database**: MySQL  

Dự án được thực hiện bởi **2 thành viên**, tập trung chính vào **React Native và Redux Toolkit**, kết hợp xây dựng API phía backend để phục vụ xác thực và quản lý dữ liệu.

---

## 👥 Thành viên thực hiện
- **Me - Tienphc0512**
- **[Teammate]**


---

## 🚀 Chức năng chính
- 🔐 Đăng nhập người dùng (JWT Authentication)
- 👤 Phân quyền theo role (user / admin)
- 🏸 Xem danh sách sân cầu lông
- ⏱️ Quản lý trạng thái sân (có thể huỷ / không thể huỷ)
- 🔔 Thông báo (Expo Notifications)
- 🗂️ Quản lý state toàn cục bằng Redux Toolkit
- 🌐 Gọi API bằng Axios

---

## 🧩 Công nghệ sử dụng

### 📱 Frontend
- React Native
- Expo
- @reduxjs/toolkit
- React Navigation
- Axios
- Expo Notifications
- Moment Timezone

### 🖥️ Backend
- Node.js (ES Module)
- Express.js
- MySQL
- JSON Web Token (JWT)
- dotenv
- node-cron
- CORS

### Backend
- MySQL
---
## ⚙️ Backend – Cài đặt & Chạy

### 1️⃣ Cài đặt
```bash
cd backend
npm install
```
### 2️⃣ Tạo file .env
```bash
PORT=3000
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=password
DB_NAME=court_badminton
JWT_SECRET=my_secret_key
```

### 3️⃣ Chạy server
```bash
node index.js
```

* Backend mặc định chạy tại:
```bash
http://localhost:3000
```

### 📱 Frontend – Cài đặt & Chạy
1️⃣ Cài đặt
```bash
cd frontend
npm install
```
2️⃣ Chạy ứng dụng
```bash
npm start
```

Hoặc:
```bash
npm run android
npm run ios
npm run web
```

🔐 Xác thực & Bảo mật

- Đăng nhập bằng JWT
  
- Token được trả về sau khi login thành công
  
- Backend kiểm tra token cho các API cần bảo vệ
  
- Phân quyền người dùng dựa trên role

📚 Kiến thức & Kỹ năng đạt được

- Phát triển ứng dụng di động bằng React Native

- Quản lý state với Redux Toolkit

- Làm việc với REST API

- Authentication với JWT

- Kết nối MySQL từ Node.js

- Làm việc nhóm & quản lý source code
