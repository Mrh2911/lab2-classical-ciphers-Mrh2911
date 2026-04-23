# Test Cases – FIT4012 Lab 2

## Caesar Cipher
- [x] **Encrypt `I LOVE YOU` với key `3`**
    - **Input:** `I LOVE YOU`, Key: `3`
    - **Expected Output:** `L ORYH BRX`
- [x] **Encrypt `hello world` với key `5`**
    - **Input:** `hello world`, Key: `5`
    - **Expected Output:** `mjqqt btwqi`
- [x] **Decrypt `LORYH BRX` với key `3`**
    - **Input:** `LORYH BRX`, Key: `3`
    - **Expected Output:** `I LOVE YOU`
- [x] **Caesar giữ dấu cách và định dạng chữ hoa/thường**
    - **Input:** `Keep Space 123`, Key: `1`
    - **Expected Output:** `Lffq Tqbdf 123`

## Rail Fence Cipher
- [x] **Encrypt `I LOVE YOU` với `2` rails**
    - **Input:** `I LOVE YOU`, Rails: `2`
    - **Expected Output:** `ILVYU OEOO` (Nếu giữ space) hoặc `IVULO EYO` (Nếu loại bỏ space)
- [x] **Encrypt `I LOVE YOU` với `4` rails**
    - **Input:** `I LOVE YOU`, Rails: `4`
    - **Expected Output:** `IYOUEOL V`
- [x] **Decrypt một bản mã Rail Fence hợp lệ**
    - **Input:** `IVU LOEYO`, Rails: `2`
    - **Expected Output:** `I LOVE YOU`

## Validation / File input
- [x] **Kiểm tra đầu vào không hợp lệ**
    - **Input:** Key là chữ cái (e.g., `abc`), key là số âm, hoặc rail < 2.
    - **Expected Behavior:** Chương trình hiển thị thông báo lỗi và yêu cầu nhập lại thay vì bị crash.
- [x] **Đọc thông điệp từ `data/input.txt`**
    - **Action:** Tạo file `input.txt` có nội dung `HELLO FIT`.
    - **Expected Behavior:** Chương trình đọc đúng nội dung và thực hiện mã hóa/giải mã như bình thường.
