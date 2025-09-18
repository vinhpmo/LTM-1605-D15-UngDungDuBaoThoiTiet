<h2 align="center">
    <a href="https://dainam.edu.vn/vi/khoa-cong-nghe-thong-tin">
        🎓 Faculty of Information Technology (DaiNam University)
    </a>
</h2>

<h2 align="center">
    Ứng dụng tra cứu thời tiết online
</h2>

<div align="center">
    <p align="center">
        <img src="docs/aiotlab_logo.png" alt="AIoTLab Logo" width="170"/>
        <img src="docs/fitdnu_logo.png" alt="FIT Logo" width="180"/>
        <img src="docs/dnu_logo.png" alt="DaiNam University Logo" width="200"/>
    </p>

[![AIoTLab](https://img.shields.io/badge/AIoTLab-green?style=for-the-badge)](https://www.facebook.com/DNUAIoTLab)
[![Faculty of Information Technology](https://img.shields.io/badge/Faculty%20of%20Information%20Technology-blue?style=for-the-badge)](https://dainam.edu.vn/vi/khoa-cong-nghe-thong-tin)
[![DaiNam University](https://img.shields.io/badge/DaiNam%20University-orange?style=for-the-badge)](https://dainam.edu.vn)

</div>

🌦 Ứng dụng Tra cứu Thời tiết Online (Java RMI)
📖 Giới thiệu đề tài

Trong thời đại công nghệ thông tin phát triển mạnh mẽ, nhu cầu nắm bắt thông tin thời tiết nhanh chóng và chính xác là rất cần thiết. Đề tài “Ứng dụng tra cứu thời tiết online sử dụng Java RMI” được xây dựng nhằm:

🏫 Minh họa mô hình Client – Server trong môn Lập trình mạng.

🌍 Kết nối và xử lý dữ liệu từ API OpenWeatherMap.

📱 Giúp người dùng nhập tên thành phố và nhanh chóng nhận được thông tin thời tiết.

Ứng dụng vừa mang tính học tập (thực hành RMI, lập trình phân tán), vừa có tính thực tiễn (tra cứu dữ liệu thời tiết thật).

👉 **Điểm nổi bật**:
- Người dùng có thể nhập tên thành phố và nhận thông tin thời tiết ngay lập tức
- Hỗ trợ nhiều thành phố trên toàn thế giới, dữ liệu cập nhật theo thời gian thực
- Giao diện client hiện đại với các thông báo trạng thái rõ ràng
- Log hoạt động chi tiết giúp theo dõi quá trình giao tiếp
📌 Giới thiệu dự án
## 📝 1. Giới thiệu đề tài
Tên đề tài: Ứng dụng Tra cứu Thời tiết Online
Ngôn ngữ: Java
Mô hình: Client – Server (RMI)
Chức năng chính:
Người dùng nhập tên thành phố.
Server gọi API OpenWeatherMap để lấy thông tin.
Hiển thị kết quả cho Client (console hoặc giao diện Swing).
⚙️ Yêu cầu môi trường
☕ Java JDK 8+ (khuyến nghị JDK 11).
📝 Eclipse IDE hoặc IDE khác (IntelliJ, NetBeans).
🌍 Kết nối Internet để gọi API thời tiết.
📦 Thư viện JSON (ví dụ: org.json hoặc Gson).

**Chi tiết công nghệ:**
- **Java SE 11+**: Ngôn ngữ lập trình chính
- **Java Swing**: Xây dựng giao diện người dùng
- **Socket Programming**: Giao tiếp Client-Server qua TCP
- **HTTP Client**: Kết nối với WeatherAPI.com
- **JSON Parsing**: Xử lý dữ liệu JSON từ API (custom parser)
- **Multithreading**: ExecutorService cho xử lý đồng thời

## 🚀 2. Đăng ký và lấy API
🔑 Chuẩn bị API Key
Đăng ký tài khoản tại: OpenWeatherMap (https://www.weatherapi.com/my/ )
Lấy API Key trong mục API Keys.
Dán API key vào WeatherServiceImpl.java (thay YOUR_API_KEY).
## 🚀3 Hướng dẫn chạy
1️⃣ Khởi động RMI Registry
rmiregistry
⚠️ Giữ cửa sổ này mở, đừng tắt.
2️⃣ Chạy Server
Run WeatherServiceImpl.java.
Console hiển thị:
WeatherService is running...
3️⃣ Chạy Client
Run WeatherClient.java.
Nhập tên thành phố (ví dụ: Hanoi).
Nhận kết quả thời tiết.

## ✉️ 3. Liên hệ

**Tác giả**: Nguyễn Thế Vinh

📧 **Email**: vinhvh010204@gmail.com

🏫 **Trường**: Đại học Đại Nam - Khoa Công nghệ Thông tin  


---



