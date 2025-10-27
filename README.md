# Blockcipher_mode
Các chế độ mã khối trong C (ECB, CBC, CTR):
Dự án này minh họa cách hoạt động của ba chế độ mã khối cơ bản trong mật mã học:
- ECB (Electronic Codebook)
- CBC (Cipher Block Chaining)
- CTR (Counter Mode)

Chương trình được viết bằng ngôn ngữ C, sử dụng phép XOR để mô phỏng quá trình mã hóa và giải mã.  
Lưu ý: Đây chỉ là ví dụ minh họa nguyên lý

Cách biên dịch và chạy

Trên Windows
```bash
gcc ecb.c -o ecb
ecb.exe

gcc cbc.c -o cbc
cbc.exe

gcc ctr.c -o ctr
ctr.exe

Trên Linux/masOS
gcc ecb.c -o ecb && ./ecb
gcc cbc.c -o cbc && ./cbc
gcc ctr.c -o ctr && ./ctr


