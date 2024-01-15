# LẬP TRÌNH C

## Bài 1. programming in C 
Hàm main là nơi bắt đầu thực thi của chương trình.

Những phần chính của một chương trình C:
- Thư viện mà chương trình sử dụng.
- Chương trình chính với mã nguồn.

Những chú ý khi viết chương trình C:
- Các câu lệnh kết thúc bằng dấu ";"
- Luôn thụt lề các câu lệnh so với hàm main.

## Bài 2. Kiểu dữ liệu(Data type)
Kiểu dữ liệu: để lưu các dữ liệu về số, kí tự, văn bản,...

### Kiểu dữ liệu số nguyên 
1 byte = 8 bit
Đối với số nguyên ta chia làm số nguyên có dấu và số nguyên không dấu, từ số byte lưu trữ ta có thể suy ra số bit cần để biểu diển số nguyên đó, quy tắc xác định giá trị của 1 số nguyên:
Giả sử số nguyên có k bit
- Số nguyên có dấu: - 2^k-1 tới 2^k-1 - 1
- Số nguyên không dấu: 0 tới 2^k - 1

![Alt text](image.png) 