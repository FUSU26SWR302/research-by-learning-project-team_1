Hệ thống ôn luyện thi THPT Quốc gia tích hợp AI




1.Giới thiệu dự án
Hệ thống web hỗ trợ học sinh THPT ôn luyện cho kỳ thi THPT Quốc gia. Hệ thống giúp học sinh làm bài kiểm tra đầu vào, phân tích năng lực học tập, đề xuất lộ trình ôn tập cá nhân hóa và luyện tập thông qua quiz, đề thi thử.


2. Mục tiêu
Hệ thống hướng tới các mục tiêu chiến lược sau:
Cá nhân hóa lộ trình học tập (Adaptive Roadmap): Tự động thiết kế, điều chỉnh danh mục bài học và bài luyện tập riêng biệt dựa trên năng lực thực tế của từng học sinh.
Tích hợp Trí tuệ nhân tạo (AI Feedback & Recommendation): Sử dụng các mô hình ngôn ngữ lớn qua API để tự động hóa việc giải thích lỗi sai chi tiết, chẩn đoán điểm yếu và đưa ra các lời khuyên học tập thực tế.
Tối ưu hóa quy trình luyện đề trực tuyến: Tạo môi trường kiểm tra giả lập phòng thi thực tế với áp lực thời gian chuẩn, tự động chấm điểm và bóc tách kết quả tức thì.
Chuẩn hóa và gán nhãn dữ liệu học liệu: Xây dựng hệ thống quản lý câu hỏi thông minh, phân loại chặt chẽ theo ma trận độ khó và các chuyên đề kiến thức cốt lõi.


3. Đối tượng sử dụng
Hệ thống phục vụ cho 5 nhóm tác nhân chính:
Khách truy cập (Guest): Người dùng chưa đăng nhập, có thể xem thông tin khóa học, tìm kiếm và đăng ký tài khoản.
Học viên (Student): Người dùng chính của hệ thống, tham gia học tập, xem bài giảng, làm bài kiểm tra và nhận chứng chỉ.
Giảng viên (Instructor): Người tạo và quản lý khóa học, đăng tải nội dung học tập, bài tập và theo dõi tiến độ học viên.
Quản trị hệ thống (System Administrator): Quản lý toàn bộ hệ thống, người dùng, phân quyền, nội dung và đảm bảo bảo mật nền tảng.
Hệ thống AI hỗ trợ (AI Learning Assistant): Thành phần AI hỗ trợ gợi ý khóa học, trả lời câu hỏi học tập và cá nhân hóa trải nghiệm người dùng.


4.  chức năng
Hệ thống tập trung triển khai các module nghiệp vụ cốt lõi của nền tảng học tập và luyện thi trực tuyến thông minh như sau:
Module
Mô tả phạm vi triển khai
Xác thực & Quản lý tài khoản: Hỗ trợ đăng ký tài khoản bằng Email hoặc mạng xã hội, đăng nhập bảo mật, quản lý hồ sơ cá nhân và cập nhật thông tin học tập của người dùng.
Học tập & Luyện thi trực tuyến: Cho phép học viên tham gia học tập, thực hiện bài kiểm tra đánh giá năng lực đầu vào (Entry Test), luyện đề trực tuyến có giới hạn thời gian và theo dõi kết quả học tập.
Chấm điểm & Phân tích tiến độ: Hệ thống tự động chấm điểm bài kiểm tra, đối chiếu đáp án, lưu lịch sử làm bài và trực quan hóa kết quả học tập thông qua biểu đồ thống kê.
Hệ thống AI hỗ trợ học tập: Ứng dụng AI để phân tích điểm yếu của học viên theo từng chủ đề kiến thức, hỗ trợ giải thích đáp án và đề xuất lộ trình học tập phù hợp.
Quản lý & Kiểm duyệt nội dung: Hỗ trợ quản lý học liệu, kiểm duyệt nội dung trước khi xuất bản, gắn nhãn (Tagging) cho câu hỏi và xử lý báo cáo lỗi từ người dùng.
Quản trị & Vận hành hệ thống: Quản lý tài khoản người dùng, phân quyền hệ thống, cấu hình tham số kỹ thuật, quản lý danh mục dữ liệu và giám sát hoạt động nền tảng.



5.Công nghệ
Hệ thống được phát triển theo mô hình Web Application.
Frontend: Xây dựng giao diện người dùng bằng ReactJS hoặc NextJS.
Backend: Phát triển API và xử lý nghiệp vụ bằng NodeJS/Spring Boot.
Database: Sử dụng PostgreSQL hoặc MySQL để lưu trữ dữ liệu hệ thống.
AI Integration: Tích hợp các mô hình AI thông qua OpenAI API hoặc các dịch vụ tương đương để hỗ trợ phản hồi thông minh và đề xuất học tập.
Authentication: Áp dụng JWT Authentication và Role-Based Access Control (RBAC).
Storage: Hỗ trợ lưu trữ tài liệu và học liệu trên Cloud Storage.
Deployment: Hệ thống có thể triển khai trên các nền tảng Cloud như Vercel, Railway hoặc AWS.



- Thành Viên
    + Nguyễn Văn Định DE190127
    + Nguyễn Quang Ngọc DE190419
    + Nguyễn Đình Huy DE190538
    + Lê Trần Gia Huy DE190749
    + Lê Ngọc Hoàng DE190085
