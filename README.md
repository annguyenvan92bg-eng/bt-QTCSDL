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
<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/cdf03b5b-e795-44ef-8e8e-29682e76c666" />





