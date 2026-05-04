<div align="center">
<h1>🌐 TaskSphere</h1>
<p><strong>Project & Task Management Platform</strong></p>
<p>Nền tảng quản lý dự án và công việc theo thời gian thực, xây dựng với kiến trúc microservice tách biệt Frontend – Backend.</p>
</div>

📌 Tổng quan
TaskSphere là ứng dụng quản lý dự án theo thời gian thực, cho phép các nhóm cộng tác, phân công nhiệm vụ và theo dõi tiến độ hiệu quả. Hệ thống được thiết kế theo mô hình client–server tách biệt hoàn toàn, giao tiếp qua RESTful API và WebSocket.

🗂️ Cấu trúc repository
RepositoryMô tảCông nghệtasksphere-backendAPI server, xử lý business logic, xác thực, realtimeJava 17, Spring Boot 3, MySQL, Redis, WebSockettasksphere-frontendGiao diện người dùng, quản lý state, kết nối APINext.js 14, TypeScript, TanStack Query, Tailwind CSS

✨ Tính năng chính

📋 Quản lý dự án & task — Tạo, phân công, theo dõi trạng thái công việc
⚡ Realtime collaboration — Cập nhật tức thì qua WebSocket
🔐 Xác thực & phân quyền — JWT-based authentication
🗄️ Caching thông minh — Redis cache tăng hiệu suất
