<div align="center">
  <h1>🌐 TaskSphere</h1>
  <p><strong>Project & Task Management Platform</strong></p>
  <p>Nền tảng quản lý dự án và công việc theo thời gian thực, xây dựng với kiến trúc tách biệt Frontend - Backend.</p>
</div>

## 📌 Tổng quan

TaskSphere là ứng dụng quản lý dự án theo thời gian thực, cho phép các nhóm cộng tác, phân công nhiệm vụ và theo dõi tiến độ hiệu quả. Hệ thống được thiết kế theo mô hình client-server tách biệt hoàn toàn, giao tiếp qua RESTful API và WebSocket.

## 🗂️ Cấu trúc repository

| Repository | Mô tả | Công nghệ |
|---|---|---|
| [tasksphere-backend](https://github.com/lenhien06/tasksphere-backend) | API server, xử lý business logic, xác thực, realtime | Java 21, Spring Boot 3.5.5, MySQL, Redis, WebSocket |
| [tasksphere-frontend](https://github.com/lenhien06/tasksphere-frontend) | Giao diện người dùng, quản lý state, kết nối API | Next.js 15, React 18, TypeScript, TanStack Query, Tailwind CSS |

## ✨ Tính năng chính

- 📋 Quản lý dự án và task: tạo, phân công, theo dõi trạng thái công việc
- ⚡ Realtime collaboration: cập nhật tức thì qua WebSocket
- 🔐 Xác thực và phân quyền: JWT-based authentication
- 🗄️ Caching thông minh: Redis cache tăng hiệu suất
