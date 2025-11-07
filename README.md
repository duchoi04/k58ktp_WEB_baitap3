# k58ktp_WEB_baitap3
nội dung bài tập 3
Bài tập 3   : môn Phát triển ứng dụng trên nền web

Giảng viên  : Đỗ Duy Cốp

Lớp học phần: 58KTPM

Ngày giao   : 2025-10-24 13:50

Hạn nộp     : 2025-11-05 00:00

--------------------------------------------------

Yêu cầu     : LẬP TRÌNH ỨNG DỤNG WEB trên nền linux
1. Cài đặt môi trường linux: SV chọn 1 trong các phương án

 - enable wsl: cài đặt ubuntu

 <img width="1106" height="636" alt="Screenshot 2025-11-05 021701" src="https://github.com/user-attachments/assets/bb858d28-bd50-484d-90e6-e99117f5219d" />

2. Cài đặt Docker (nếu dùng docker desktop trên windows thì nó có ngay)

<img width="946" height="700" alt="Screenshot 2025-11-05 021853" src="https://github.com/user-attachments/assets/1aebc4e5-c079-4259-8542-b75561e691f5" />

 Khởi động lại máy để kết nối tới docker(đã kết nối thành công)


<img width="1594" height="913" alt="image" src="https://github.com/user-attachments/assets/f532ad51-7cbf-457c-a584-a3966bb8363c" />



3. Tải các Docker Container bằng file docker-compose.yml:

Em sử dụng visual code để tạo file docker compose.yml:

<img width="1560" height="968" alt="image" src="https://github.com/user-attachments/assets/22089600-16a6-45db-bd22-b3847353e127" />



Chạy lệnh docker-compose up để tải xuống các Docker Container:

<img width="955" height="364" alt="Screenshot 2025-11-07 220405" src="https://github.com/user-attachments/assets/80a2ed00-2332-489f-85be-ae1b2109da64" />
<img width="937" height="425" alt="Screenshot 2025-11-07 220413" src="https://github.com/user-attachments/assets/8519592c-4470-499e-8e70-f111ef293a3c" />
<img width="935" height="184" alt="Screenshot 2025-11-07 220426" src="https://github.com/user-attachments/assets/3ddb2669-b004-49b5-acd9-56c14e21477e" />


Kiểm tra các Container trên Docker Desktop(đã xuất hiện):

<img width="1594" height="913" alt="Screenshot 2025-11-07 220733" src="https://github.com/user-attachments/assets/f50638ff-bd3a-443a-bc13-5484bc038356" />


Truy cập thử các ports(thành công):

<img width="1920" height="1080" alt="Screenshot 2025-11-07 220438" src="https://github.com/user-attachments/assets/51ce2aa6-18de-42a1-bdd6-53a40638c77e" />

<img width="1914" height="1080" alt="Screenshot 2025-11-07 220443" src="https://github.com/user-attachments/assets/753db052-6e9d-4aeb-bd49-99b4be8702cb" />

<img width="1920" height="1080" alt="Screenshot 2025-11-07 220503" src="https://github.com/user-attachments/assets/52748e22-9b15-4f5f-ad40-3bf83ce026b3" />

<img width="1920" height="1080" alt="Screenshot 2025-11-07 220509" src="https://github.com/user-attachments/assets/2f8d3996-9faa-455b-8562-fa7d10dc6f73" />

<img width="1911" height="1068" alt="Screenshot 2025-11-07 220553" src="https://github.com/user-attachments/assets/7b856bcd-7357-4205-a346-8e54008b4b5f" />


4. Lập trình web frontend+backend:

   
<img width="1920" height="1076" alt="image" src="https://github.com/user-attachments/assets/a2629fe8-209d-4afe-8f06-afb8da9a3edf" />

 em thưa thầy là đã cố gắng kết nối nhưng em vẫn ko kết nối được vào trang web.

  5. Nginx làm web-server

 - Cấu hình nginx để chạy được website qua url http://fullname.com(thay fullname bằng chuỗi ko dấu viết liền tên của bạn):

   <img width="1916" height="1069" alt="Screenshot 2025-11-08 022732" src="https://github.com/user-attachments/assets/8e976075-8de0-471a-b911-2aa9ef05301a" />

 - Cấu hình nginx để http://fullname.com/nodered:

 <img width="1908" height="1025" alt="Screenshot 2025-11-08 022900" src="https://github.com/user-attachments/assets/69a60a82-fbb2-481a-8fab-b03fdff2b402" />

   
 - Cấu hình nginx để http://fullname.com/grafana:

<img width="1920" height="1039" alt="Screenshot 2025-11-08 022918" src="https://github.com/user-attachments/assets/f76908c2-8aa9-4306-9571-4a681adb7552" />

6.
  - Qua bài này em biết được cách cài ubuntu, docker
  - Biết cách cài các Docker Container
  - Biết cách lấy dữ liệu từ database đến nodered
  - Biết cách cấu hình nginx để chạy được website qua url http : //fullname.com



 
