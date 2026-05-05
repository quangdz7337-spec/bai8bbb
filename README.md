# bai8bbb
Cài đặt thành công gdbserver
<img width="740" height="486" alt="98b46364-837a-46d1-bbaa-21ed7a75d1e9" src="https://github.com/user-attachments/assets/a7512662-5bb9-4ad7-99fa-b300fbb0344f" />
Biên dịch hệ thống, buildroot cấp nhật lại phiên bản có chứa thêm gdbserver sau đó flash vào thẻ nhớ và chạy thử trên BBB
Bài 2.2 đặt breakboip ở main, thực thi điều khiển chạy next, step, continue. thực hiện in và gán giá trị biến
<img width="742" height="552" alt="3e2c572a-2132-4e4a-a753-389798525915" src="https://github.com/user-attachments/assets/3bca29e2-e550-46e7-9db9-5aadc21a7889" />
Xem giá trị thanh ghi 
<img width="742" height="552" alt="18d8d6b4-8122-4d73-9665-df9d37469113" src="https://github.com/user-attachments/assets/826c3937-a7d7-41c7-8162-5ac233c17465" />
kết thúc và out
<img width="742" height="552" alt="4302f5f3-e17b-4315-943b-f419d06b0649" src="https://github.com/user-attachments/assets/f2b85892-cb31-47a6-ae74-3b235169b69a" />
gdb-multiarch ./app_test_debug
target remote 192.168.4.3:1234
Bài 2.3: Kiểm tra lỗi bằng công cụ valgrind
<img width="742" height="615" alt="111356d4-1517-44a2-ad2c-18c2b9450352" src="https://github.com/user-attachments/assets/bfcbac48-06fa-434a-904e-cb3e3f912a9b" />
==154==    definitely lost: 100 bytes in 1 blocks
Valgrind đã tóm gọn chính xác việc chương trình của bạn "vay" 100 bytes bộ nhớ (bằng lệnh malloc) nhưng lúc kết thúc lại "quên" trả lại (không dùng free)
sau khi sửa
<img width="742" height="615" alt="7268b9bc-a69a-4953-af85-b28acd085611" src="https://github.com/user-attachments/assets/964ef526-0789-48b8-b392-efdd5ad1ee8a" />
Tạo 1 chương trình có lỗi và kiểm tra bằng công cụ valgrind
Bài 2.4: 
Sinh ra file lỗi core leak khi chương trình bị sập
<img width="742" height="615" alt="7268b9bc-a69a-4953-af85-b28acd085611" src="https://github.com/user-attachments/assets/f2ac83fa-59ca-44cb-a57b-5253b16b509a" />
Chốt 2.4 thực thi chương trình mới tạo lỗi và xem thông báo lỗi
<img width="742" height="615" alt="7268b9bc-a69a-4953-af85-b28acd085611" src="https://github.com/user-attachments/assets/0e6555d1-4e2b-4ea2-85e2-1f6771ef4be8" />
bảng phân tích
<img width="747" height="424" alt="e48f6959-ac61-4c5a-a129-abd91efa85f7" src="https://github.com/user-attachments/assets/9f17e94b-1dc6-49d7-ad2e-cac282277883" />
lệnh perf record 
<img width="1232" height="761" alt="dee0ddb7-58b1-4a91-ac74-500e7c3f4116" src="https://github.com/user-attachments/assets/f72e9bdb-a330-4ad8-9f6e-8c8b6b0d2f5e" />
bài 2.6
<img width="1804" height="688" alt="0789afe0-2427-4883-b8cf-f096676a341e" src="https://github.com/user-attachments/assets/0d393bfc-9617-4f96-864c-71d6abf38a78" />
