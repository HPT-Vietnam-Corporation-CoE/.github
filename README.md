# HPT Vietnam Corporation CoE

Chào mọi người, đây là không gian lưu trữ mã nguồn và tài liệu làm việc nội bộ của CoE tại HPT. 

Tổ chức GitHub này được lập ra để quản lý source code các dự án, lưu trữ các thử nghiệm công nghệ và giúp các thành viên trong nhóm dễ dàng cộng tác, chia sẻ tài nguyên kỹ thuật với nhau.

## 🎯 Hoạt động chính

* Nghiên cứu, phát triển và thử nghiệm các giải pháp công nghệ mới để giải quyết các bài toán nội bộ hoặc dự án thực tế.
* Tập trung vào mảng Trí tuệ nhân tạo (AI), Machine Learning và Tự động hóa (ví dụ: tự động hóa quy trình trích xuất dữ liệu từ tài liệu, hợp đồng).
* Lưu trữ tập trung các tài liệu thiết kế hệ thống, kịch bản triển khai và source code của team.

## 💻 Công nghệ & Framework đang sử dụng

Team đang làm việc và liên tục tìm hiểu các công cụ/nền tảng sau:
* **AI/ML Frameworks:** PyTorch, MLX...
* **LLM & APIs:** Tích hợp và ứng dụng các API từ Google, Mistral; sử dụng các công cụ theo dõi mô hình như Langfuse.
* **Xử lý giọng nói & Dữ liệu:** Các mô hình xử lý audio (như CosyVoice) và các pipeline xử lý dữ liệu tự động.

## 📌 Hướng dẫn dành cho thành viên

Để đảm bảo quy trình làm việc hiệu quả và an toàn, mọi người lưu ý các điểm sau:

1.  **Bảo mật:** Tuyệt đối không hardcode và đẩy các thông tin nhạy cảm (API keys, credentials, dữ liệu thật của công ty/khách hàng) lên repository. Khuyến khích sử dụng biến môi trường (`.env`).
2.  **Tổ chức Repository:** Đặt tên repo ngắn gọn, có ý nghĩa. Mỗi repository cần có một file `README.md` riêng hướng dẫn chi tiết cách cài đặt môi trường và chạy code.
3.  **Quy trình làm việc:** Tạo branch riêng cho từng tính năng hoặc bug fix. Vui lòng mở Pull Request (PR) và tag các thành viên khác review trước khi merge vào nhánh chính.

---
*Thành viên mới cần quyền truy cập vào các repository cụ thể vui lòng liên hệ trực tiếp với team trên group chat nội bộ.*