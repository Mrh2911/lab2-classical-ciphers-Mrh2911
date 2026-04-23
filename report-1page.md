# Report 1 Page – FIT4012 Lab 2

## 1. Mục tiêu
Tóm tắt ngắn gọn mục tiêu của bài lab.

## 2. Cách làm
- Hoàn thiện Caesar Cipher cho chữ thường, dấu cách và giải mã.
- Hoàn thiện Rail Fence Cipher cho giải mã, giữ dấu cách, kiểm tra đầu vào và đọc file.
- Chạy thử trên nhiều test case.

## 3. Kết quả chính
## 3. Kết quả chính
### 3.1 Caesar Cipher
| Input | Key | Ciphertext / Plaintext | Nhận xét |
|---|---:|---|---|
| I LOVE YOU | 3 | L ORYH BRX | Giữ đúng dấu cách và chữ hoa. |
| hello world | 5 | mjqqt btwqi | Xử lý tốt chữ thường. |
| LORYH BRX | 3 | I LOVE YOU | Giải mã chính xác về bản rõ. |

### 3.2 Rail Fence Cipher
| Input | Rails | Ciphertext / Plaintext | Nhận xét |
|---|---:|---|---|
| I LOVE YOU | 2 | ILVYU OEOO | Ghép các ký tự theo hàng ngang. |
| I LOVE YOU | 4 | IYOUEOL V | Zigzag 4 tầng làm xáo trộn mạnh hơn. |
| IVU LOEYO | 2 | I LOVE YOU | Khôi phục đúng vị trí zigzag. |

### 3.3 Input validation / file input
- **Đầu vào không hợp lệ:** Khi nhập key là "abc", chương trình báo lỗi "Invalid Input" và yêu cầu nhập lại số nguyên.
- **Kết quả đọc file:** Đã đọc thành công nội dung từ `data/input.txt` và mã hóa theo cấu hình người dùng.

## 4. Kết luận
Qua bài lab, em hiểu rõ sự khác biệt giữa mã hóa thay thế và hoán vị. Khó khăn lớn nhất là việc duy trì dấu cách trong Rail Fence sao cho khi giải mã không bị lệch vị trí. Điều này giúp em nắm vững hơn cách điều hướng chỉ số mảng 2 chiều.
