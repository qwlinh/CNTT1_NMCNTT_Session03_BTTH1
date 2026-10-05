## Bài 1: Quản lý lưu trữ và đường dẫn tệp trong Windows

----

# YÊU CẦN ĐẦU RA

## Phần 1 (Phân tích):
 - Sai lầm về vị trí lưu trữ: C:\Windows\System32 ( Thư mục hệ thống cốt lõi )
 - Sai lầm về tên file/thư mục: Dùng tiếng việt và có khoảng cách ( Bai Tap Cua Nam, bai tap 1.py )
 - Hiểu lầm về tốc độ mạng:
   + Gói cước tính theo Megabit (Mbps), còn dung lượng/tốc độ truyền tải tính theo Megabyte (MB/s) với quy đổi 1 Byte=8 bits.
   + Tốc độ thực tế 100 Mbps÷8=12.5 MB/s là chính xác hoàn toàn, nhà mạng không lừa đảo.
 - Dung lượng SSD 256GB hiển thị thấp hơn thực tế: Do nhà sản xuất tính theo hệ thập phân (1 GB=109 bytes), trong khi Windows tính theo hệ nhị phân (1 GiB=230 bytes). Quy đổi ra sẽ có khoảng 238 GB.

## Phần 2 (Hoàn thiện):
Thiết kế lại cây thư mục
 - Sử dụng ổ D:, tuân thủ cấu trúc 3 cấp, 4 trụ cột (study, project, resource, archive), và chuẩn đặt tên kebab-case (viết thường, cách nhau bằng dấu gạch ngang -).
 - Cây thư mục mẫu:
Plaintext
D:\
└── study\
    └── it108-nhap-mon-cntt\
           └── session-04\
               └── bai-tap-1.py
  - Đường dẫn chuẩn mới: D:\study\it108-nhap-mon-cntt\session-04\bai-tap-1.py
