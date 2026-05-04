# TaskSphere Landing Page

Landing page chính thức dùng để giới thiệu dự án **TaskSphere** theo hướng ngắn gọn, chuyên nghiệp và phù hợp cho demo sản phẩm, thuyết trình hoặc chia sẻ công khai.

## Overview

Trang này được xây dựng để trình bày nhanh các nội dung quan trọng của TaskSphere:

- giá trị sản phẩm đối với doanh nghiệp
- các nhóm tính năng lớn của hệ thống
- công nghệ sử dụng ở backend và frontend
- các thuật toán và business rules nổi bật
- thông tin đội ngũ phát triển

Landing page được triển khai dưới dạng **static HTML/CSS**, dễ chỉnh sửa, dễ deploy và phù hợp cho GitHub Pages.

## Live Demo

- Landing page: [https://lenhien06.github.io/tasksphere](https://lenhien06.github.io/tasksphere)
- Backend repository: [tasksphere-backend](https://github.com/lenhien06/tasksphere-backend)
- Frontend repository: [tasksphere-frontend](https://github.com/lenhien06/tasksphere-frontend)

## Highlights

- Trình bày sản phẩm theo góc nhìn business thay vì chỉ mô tả giao diện
- Tóm tắt các capability lớn như workspace health, sprint planning, Kanban, reporting, AI planning và notifications
- Thể hiện các phần logic nổi bật như AI scoring, capacity detection, burndown/velocity và dependency rules
- Có phần giới thiệu đội ngũ với ảnh thật và vai trò ngắn gọn

## Tech Context

Landing page phản ánh đúng stack chính của hệ thống:

- Backend: `Java 21`, `Spring Boot 3.5.5`, `Spring Security`, `MySQL`, `Redis`, `WebSocket`
- Frontend: `Next.js 15`, `React 18`, `TypeScript`, `TanStack Query`, `Tailwind CSS`

## Project Structure

```text
.
├─ index.html
└─ team-photos/
```

- `index.html`
  Landing page chính.

- `team-photos/`
  Ảnh thành viên và ảnh nhóm dùng trong phần giới thiệu đội ngũ.

## Editing Guide

Phần lớn thay đổi được thực hiện trực tiếp trong:

```html
index.html
```

Khi cập nhật ảnh thành viên:

1. thay file tương ứng trong `team-photos/`
2. cập nhật lại đường dẫn ảnh trong `index.html` nếu tên file thay đổi

## Deployment

Vì đây là static page, có thể deploy bằng nhiều lựa chọn đơn giản:

- GitHub Pages
- Netlify
- Vercel

Hoặc mở trực tiếp `index.html` trong trình duyệt để demo offline.

## Repository

- GitHub: [https://github.com/lenhien06/tasksphere](https://github.com/lenhien06/tasksphere)

