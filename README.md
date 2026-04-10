# bt-QTCSDL
1. Các service đang chạy

   <img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/eac42ccd-5a9c-49a2-bcfb-f7af33b5e76a" />
2. Cấu hình cho SQL server làm việc ở cổng động (Dynamic Port),TCP

   <img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/45aca356-0c7b-4c38-9cce-55763fa17938" />
3. Restart SQL Server

   <img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/e2a4fc81-2bf2-49f4-8b5b-6b980f5a8af7" />
4. Kiểm tra cổng 36002 có đang mở

   <img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/afee99b2-8018-44ef-8b6d-0b177214c74b" />
5. Kết nối đến SQL Server
- Kết nối bằng Windows Authentication

  <img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/2c80f0c5-4d0c-4c02-9388-f0912eb12cd8" />
 Kết quả thành công
<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/1a524a90-6207-4b1a-9d46-e0ff92c662c5" />
- Kết nối bằng SQl Server Authentication

  <img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/98917cf4-a564-4de4-8cac-5b1999fd90ff" />
 Kết quả thành công
<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/d2adf8bf-af47-43d0-9837-853a3f408192" />
6. Tạo cơ sở dữ liệu mới và chọn Path lưu cho file dữ liệu và file log
  
<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/4bc0f45b-17b0-4866-a5bc-62a7b89c35bd" />

 Kết quả thành công-cả 2 được lưu trên ổ E vào các thư mục khác nhau
 
<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/77c7e0dd-f414-483a-8e40-812ea43f1d5e" />
<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/e3f24655-9569-46b5-9cdb-f21f02c1441b" />
7. Tạo bảng dữ liệu(các trường dữ liệu phù hợp) với khóa chính là trường masv

<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/1de926d3-93ce-4695-8792-5e65ee60ff81" />

 *Sau khi hoàn tất lưu và đặt tên bảng

 8. Import dữ liệu từ file mẫu
 - Dùng Import Flat File
<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/626504e4-78d7-4b6d-962c-7245245c9ef7" />
 - Thêm file mẫu 
<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/0e06104f-4e44-4f85-9ae3-bdc87212cff1" />
 - Chỉnh sửa các thuộc tính cho phù hợp
<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/b6315a87-e6f9-4db1-814b-f02fcf67323c" />
 - Kiểm tra số dòng của dữ liệu đã import (kết quả 12004 dòng)
<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/68e4549a-aa79-48cf-b421-32c97aa31a46" />

9. Insert 1 row vào bảng với dữ liệu là thông tin cá nhân của sv đang làm bài

<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/b416767a-50fb-4571-8385-8deb6faccedf" />
- Kết quả thành công
<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/8a43409c-ca23-426e-82d5-ea4c051dbe52" />

10. Update trường noisinh thành 'Sao Hoả' cho những dòng có noisinh và diachi đều là NULL.

<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/a4b491e8-2caf-447c-98e8-5ceb427d7b1a" />
11. Tạo bảng SaoHoa gồm những sinh viên có nơi sinh ở 'Sao Hoả'
<img width="2560" height="1600" alt="Ảnh chụp màn hình 2026-04-10 190225" src="https://github.com/user-attachments/assets/63ee2ef2-ebae-4726-a2fa-676a82f5f8c8" />
- Kết quả thành công
<img width="2560" height="1600" alt="Ảnh chụp màn hình 2026-04-10 190343" src="https://github.com/user-attachments/assets/052d3e43-5f06-4c2f-b79d-41857de6c82e" />
12. Delete trong bảng SaoHoa những sinh viên cùng họ với em (họ Nguyễn)
<img width="2560" height="1600" alt="Ảnh chụp màn hình 2026-04-10 191058" src="https://github.com/user-attachments/assets/1bc87993-65e0-4511-b744-76457af54f95" />
13. Xuất toàn bộ kết quả của các bước thực hiện ra file dulieu.sql sử dụng tính năng GEN SCRIPT struct+data cho database
<img width="2560" height="1600" alt="Ảnh chụp màn hình 2026-04-10 191605" src="https://github.com/user-attachments/assets/89a2f3e4-50a6-44dc-98c5-f33a5bf609a6" />
<img width="2560" height="1600" alt="Ảnh chụp màn hình 2026-04-10 191835" src="https://github.com/user-attachments/assets/56b77a06-d708-40de-bf40-abe3cf7d50a1" />
<img width="2560" height="1600" alt="Ảnh chụp màn hình 2026-04-10 192523" src="https://github.com/user-attachments/assets/3f58b191-de0a-4a3c-a00c-dd8202e208d8" />
- Kết quả tạo thành công file
<img width="2560" height="1600" alt="Ảnh chụp màn hình 2026-04-10 193221" src="https://github.com/user-attachments/assets/f88a01f1-a706-44d3-a4e0-9c1cd60591f3" />
14. Xoá csdl đã tạo
<img width="2560" height="1600" alt="Ảnh chụp màn hình 2026-04-10 193730" src="https://github.com/user-attachments/assets/7db98af9-b6c9-43bc-9f98-2b290f81f13e" />
 - Sau khi xóa kiểm tra path đã mất file .mdf  và _log.ldf
<img width="2560" height="1600" alt="Ảnh chụp màn hình 2026-04-10 194008" src="https://github.com/user-attachments/assets/21558fc8-3703-4c68-9b83-38d6ee1d1fa5" />
<img width="2560" height="1600" alt="Ảnh chụp màn hình 2026-04-10 193948" src="https://github.com/user-attachments/assets/ce318034-c6ca-408c-870e-1728e1047451" />
15. Chạy lại file dulieu.sql
<img width="2560" height="1600" alt="Ảnh chụp màn hình 2026-04-10 194908" src="https://github.com/user-attachments/assets/725c1adf-8484-4564-93ea-806877f0114c" />
 - Kết quả dữ liệu đã khôi phục thành công
<img width="2560" height="1600" alt="Ảnh chụp màn hình 2026-04-10 194951" src="https://github.com/user-attachments/assets/656023fc-7ff9-4e1c-b2d7-9cc86de28d10" />
16. Upload file dulieu.sql lên github repository








