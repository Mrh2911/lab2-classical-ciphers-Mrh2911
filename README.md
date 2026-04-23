# fit4012-lab2-classical-ciphers-starter

Starter repo cho **FIT4012 – Lab 2: Mã hoá cổ điển**.

## Trạng thái dự án
- [x] Caesar Cipher: Hoàn thành Q1, Q2, Q3.
- [x] Rail Fence Cipher: Hoàn thành Q4, Q5, Q6, Q7, Q8.
- [x] Kiểm thử: Đã chạy 9/9 test cases thành công.

## Mục tiêu
- Cài đặt và mở rộng **Caesar Cipher** (Xử lý chữ thường, dấu cách, giải mã).
- Cài đặt và mở rộng **Rail Fence Cipher** (Nhiều ray, giữ dấu cách, giải mã, validation).
- Làm quen với quy trình nộp bài qua **GitHub repo**.

## Cách biên dịch & Chạy
### Caesar Cipher
```bash
g++ -std=c++17 -O2 -Wall -Wextra -o caesar_bin src/caesar.cpp
./caesar_bin
