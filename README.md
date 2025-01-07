# SQL-Injection-Week-2

## Mục Tiêu
Bài tập tuần 2 yêu cầu thực hiện các nhiệm vụ liên quan đến khai thác lỗ hổng **SQL Injection (SQLi)** trên một ứng dụng web. Bài tập được chia thành 3 yêu cầu chính:

1. **Tìm đọc và thống kê ít nhất 100 writeup về khai thác lỗ hổng SQL Injection.**
2. **Khai thác lỗ hổng SQLi trong source code của bài tập web theo 2 cách:**
   - Khai thác bằng tool SQLMap.
   - Khai thác bằng cách viết Python Code.
3. **Vượt qua các challenge SQLi trên PortSwigger và HacktheBox.**

---

## Yêu Cầu 1: Tìm và Thống Kê Writeup về SQL Injection

### **Các bước thực hiện:**
- Tìm và thống kê ít nhất 100 bài viết (writeups) về khai thác lỗ hổng SQL Injection. Các bài viết này có thể đến từ các cuộc thi CTF hoặc từ các bug bounty của các công ty lớn như Apple, Facebook, Microsoft.
- Cung cấp liên kết đến các writeup có sẵn. Dưới đây là một số ví dụ:

### **Ví dụ về liên kết writeup:**
- [Facebook Bug Bounty Writeups](https://github.com/jaiswalakshansh/Facebook-BugBounty-Writeups)
- [SQL Injection Writeups Collection](https://github.com/search?q=sql+injection+writeup)
- [CTF Time](https://ctftime.org/)
- [Hackthebox SQLi Challenges](https://www.hackthebox.eu/)

---

## Yêu Cầu 2: Khai Thác Lỗ Hổng SQLi trong Source Code Bài Tập Web

### **Mô tả lỗ hổng SQLi:**
Ứng dụng web có một lỗ hổng SQL Injection. Mục tiêu là khai thác lỗ hổng này để dump được thông tin bảng `users`, và lấy được `username` và `password` của người dùng.

### **2.1. Khai Thác bằng Tool SQLMap**
### **2.2. Khai Thác bằng Python Code**
# Yêu Cầu 3: Vượt Qua Các Challenge SQLi trên PortSwigger và HacktheBox

## PortSwigger

PortSwigger Web Security Academy cung cấp các bài học và thử thách về SQL Injection, giúp bạn hiểu rõ hơn về cách thức tấn công và bảo vệ ứng dụng khỏi lỗ hổng SQLi.

### **Các bước thực hiện:**
1. Truy cập **PortSwigger Web Security Academy** tại [https://portswigger.net/web-security/sql-injection](https://portswigger.net/web-security/sql-injection).
2. Đọc các bài học SQL Injection từ cơ bản đến nâng cao.
3. Hoàn thành các thử thách SQL Injection có trong các bài học, mỗi thử thách sẽ giúp bạn phát triển kỹ năng khai thác SQLi trong các tình huống thực tế khác nhau.
4. Cố gắng giải quyết càng nhiều thử thách càng tốt, bao gồm:
   - **Basic SQL Injection**
   - **Union-based SQL Injection**
   - **Blind SQL Injection**
   - **Time-based Blind SQL Injection**

### **Mục tiêu:** 
- Nâng cao khả năng nhận diện và khai thác lỗ hổng SQLi trong các ứng dụng web thực tế.
- Giải quyết các thử thách sẽ giúp bạn có cái nhìn toàn diện về SQLi và kỹ thuật phòng ngừa.

---

## HacktheBox

**HacktheBox** là một nền tảng trực tuyến giúp bạn thực hành khai thác bảo mật và giải quyết các thử thách trong các môi trường giả lập. Để thực hành SQL Injection, bạn có thể tìm kiếm các challenges liên quan đến SQLi và giải quyết chúng bằng các kỹ thuật đã học.

### **Các bước thực hiện:**
1. Truy cập **HacktheBox** tại [https://www.hackthebox.eu/](https://www.hackthebox.eu/).
2. Đăng ký tài khoản nếu bạn chưa có.
3. Sau khi đăng nhập, tìm kiếm các thử thách (challenges) về **SQL Injection**.
4. Tham gia và cố gắng giải quyết các challenges SQLi.
5. Các challenges SQLi có thể liên quan đến việc khai thác lỗ hổng trong các ứng dụng web để:
   - Lấy thông tin từ cơ sở dữ liệu.
   - Bypass xác thực người dùng.
   - Giải quyết các tình huống khác như Blind SQLi hoặc Time-based SQLi.

### **Mục tiêu:** 
- Rèn luyện kỹ năng tấn công và bảo vệ SQL Injection trong các môi trường thực tế.
- Đối mặt với các tình huống khó khăn và cải thiện khả năng xử lý các dạng SQLi phức tạp.

---

## Tài Liệu Tham Khảo

- [PortSwigger Web Security Academy](https://portswigger.net/web-security/sql-injection)
- [HacktheBox](https://www.hackthebox.eu/)
