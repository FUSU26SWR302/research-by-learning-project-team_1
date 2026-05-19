# Hệ Thống Ôn Luyện Thi THPT Quốc Gia Tích Hợp AI

## 1. Giới Thiệu Dự Án

Hệ thống web hỗ trợ học sinh THPT ôn luyện cho kỳ thi THPT Quốc gia.  
Hệ thống giúp học sinh:

- Làm bài kiểm tra đầu vào
- Phân tích năng lực học tập
- Đề xuất lộ trình ôn tập cá nhân hóa
- Luyện tập thông qua quiz và đề thi thử

---

## 2. Mục Tiêu

Hệ thống hướng tới các mục tiêu chiến lược sau:

### 2.1 Cá nhân hóa lộ trình học tập (Adaptive Roadmap)

Tự động thiết kế và điều chỉnh danh mục bài học, bài luyện tập riêng biệt dựa trên năng lực thực tế của từng học sinh.

### 2.2 Tích hợp Trí tuệ nhân tạo (AI Feedback & Recommendation)

Sử dụng các mô hình ngôn ngữ lớn thông qua API để:

- Giải thích lỗi sai chi tiết
- Chẩn đoán điểm yếu
- Đưa ra lời khuyên học tập
- Đề xuất nội dung luyện tập phù hợp

### 2.3 Tối ưu hóa quy trình luyện đề trực tuyến

Cung cấp môi trường thi thử giống thực tế với:

- Giới hạn thời gian
- Tự động chấm điểm
- Phân tích kết quả tức thì

### 2.4 Chuẩn hóa và quản lý học liệu

Xây dựng hệ thống ngân hàng câu hỏi:

- Phân loại theo môn học
- Gắn nhãn chuyên đề
- Phân chia độ khó
- Kiểm duyệt nội dung

---

## 3. Đối Tượng Sử Dụng

### 3.1 Guest (Khách truy cập)

- Xem thông tin khóa học
- Tìm kiếm nội dung
- Đăng ký tài khoản

### 3.2 Student (Học viên)

- Học tập trực tuyến
- Làm bài kiểm tra
- Luyện đề thi thử
- Theo dõi kết quả học tập
- Nhận gợi ý từ AI

### 3.3 Instructor (Giảng viên)

- Tạo khóa học
- Quản lý học liệu
- Đăng tải bài tập và đề thi
- Theo dõi tiến độ học viên

### 3.4 System Administrator

- Quản lý hệ thống
- Phân quyền người dùng
- Quản lý dữ liệu
- Giám sát bảo mật

### 3.5 AI Learning Assistant

- Hỗ trợ giải thích bài học
- Phân tích điểm yếu
- Đề xuất lộ trình học tập

---

## 4. Chức Năng Hệ Thống

### 4.1 Xác thực & Quản lý tài khoản

- Đăng ký / đăng nhập
- JWT Authentication
- Quản lý hồ sơ cá nhân
- Phân quyền người dùng

### 4.2 Học tập & Luyện thi trực tuyến

- Entry Test
- Quiz luyện tập
- Thi thử trực tuyến
- Theo dõi lịch sử làm bài

### 4.3 Chấm điểm & Phân tích tiến độ

- Tự động chấm điểm
- Thống kê kết quả
- Biểu đồ tiến độ học tập
- Phân tích năng lực

### 4.4 Hệ thống AI hỗ trợ học tập

AI hỗ trợ:

- Giải thích đáp án
- Phân tích lỗi sai
- Gợi ý chuyên đề cần cải thiện
- Cá nhân hóa lộ trình học

### 4.5 Quản lý & Kiểm duyệt nội dung

Giảng viên và quản trị viên có thể:

- Quản lý ngân hàng câu hỏi
- Gắn tag chuyên đề
- Kiểm duyệt nội dung
- Xử lý báo lỗi

### 4.6 Quản trị & Vận hành hệ thống

- Quản lý người dùng
- Quản lý dữ liệu
- Theo dõi hoạt động hệ thống
- Giám sát bảo mật

---

## 5. Công Nghệ Sử Dụng

| Thành phần | Công nghệ |
|---|---|
| Frontend | ReactJS / NextJS |
| Backend | NodeJS / Spring Boot |
| Database | PostgreSQL / MySQL |
| AI Integration | OpenAI API |
| Authentication | JWT + RBAC |
| Storage | Cloud Storage |
| Deployment | Vercel / Railway / AWS |

---

## 6. Kiến Trúc Hệ Thống

Hệ thống được thiết kế theo mô hình Client - Server gồm:

### Frontend
- Giao diện người dùng
- ReactJS / NextJS

### Backend API
- Xử lý nghiệp vụ
- Quản lý dữ liệu
- RESTful API

### Database
- Lưu trữ:
  - Người dùng
  - Bài kiểm tra
  - Học liệu

### AI Service
- Phân tích dữ liệu học tập
- Đưa ra phản hồi thông minh

### Cloud Storage
- Lưu trữ tài liệu
- Học liệu trực tuyến

---

## 7. Bảo Mật Hệ Thống

Hệ thống áp dụng:

- JWT Authentication
- Role-Based Access Control (RBAC)
- Mã hóa mật khẩu
- Kiểm tra quyền truy cập API
- Chống SQL Injection
- Bảo vệ dữ liệu người dùng

---

## 8. Hướng Phát Triển Tương Lai

- Mobile App
- AI Chatbot realtime
- Phân tích cảm xúc học tập
- Gợi ý đề thi theo xu hướng
- Gamification học tập
- Livestream học trực tuyến

---

## 9. Thành Viên Thực Hiện

| Họ và tên | Mã sinh viên |
|---|---|
| Nguyễn Văn Định | DE190127 |
| Nguyễn Quang Ngọc | DE190419 |
| Nguyễn Đình Huy | DE190538 |
| Lê Trần Gia Huy | DE190749 |
| Lê Ngọc Hoàng | DE190085 |

---

## 10. Kết Luận

Hệ thống ôn luyện thi THPT Quốc gia tích hợp AI là giải pháp học tập hiện đại giúp học sinh nâng cao hiệu quả ôn tập thông qua việc cá nhân hóa trải nghiệm học tập và ứng dụng AI vào giáo dục.

Dự án góp phần thúc đẩy chuyển đổi số trong lĩnh vực giáo dục và hỗ trợ học sinh đạt kết quả tốt hơn trong kỳ thi THPT Quốc gia.
