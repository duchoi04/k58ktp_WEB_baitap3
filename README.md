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


7. Lập trình web frontend+backend:
   
 SV chọn 1 trong các web sau:
 
 4.1 Web thương mại điện tử
 
 - Tạo web dạng Single Page Application (SPA), chỉ gồm 1 file index.html, toàn bộ giao diện do javascript sinh động
   
 - Có tính năng login, lưu phiên đăng nhập vào cookie và session
   
   Thông tin login lưu trong cơ sở dữ liệu của mariadb, được dev quản trị bằng phpmyadmin, yêu cầu sử dụng mã hoá khi gửi login

   Chỉ cần login 1 lần, bao giờ logout thì mới phải login lại.
  
 - Có tính năng liệt kê các sản phẩm bán chạy ra trang chủ
   
 - Có tính năng liệt kê các nhóm sản phẩm
   
 - Có tính năng liệt kê sản phẩm theo nhóm
   
 - Có tính năng tìm kiếm sản phẩm
   
 - Có tính năng chọn sản phẩm (đưa sản phẩm vào giỏ hàng, thay đổi số lượng sản phẩm trong giỏ, cập nhật tổng tiền)
  
 - Có tính năng đặt hàng, nhập thông tin giao hàng => được 1 đơn hàng.
   
- backend: sử dụng nodered xử lý request gửi lên từ javascript, phản hồi về json.

  5. Nginx làm web-server
 - Cấu hình nginx để chạy được website qua url http://fullname.com  (thay fullname bằng chuỗi ko dấu viết liền tên của bạn)
 - Cấu hình nginx để http://fullname.com/nodered truy cập vào nodered qua cổng 80, (dù nodered đang chạy ở port 1880)
 - Cấu hình nginx để http://fullname.com/grafana truy cập vào grafana qua cổng 80, (dù grafana đang chạy ở port 3000)

Yêu cầu sinh viên lưu code trên github
có file readme.md có hình ảnh + text: ghi lại nhật ký quá trình làm bài.

CÁCH ĐÁNH GIÁ:
1. Cài đặt được môi trường: 1đ
2. Cài đặt được các docker container với cấu hình phù hợp: 1đ
3. Web chạy được, giao diện phù hợp, chạy trên web sever nginx: 2đ
4. nodered api trả về json, test được: 2đ
5. front-end có js gọi được api nodered, nhận về json, hiển thị được kết quả từ json này. 2đ
6. Bài làm có dấu ấn, giải thích rõ ràng, hiểu vấn đề: 2đ
 - Có tính năng dành cho admin: Thống kê xem có bao nhiêu đơn hàng, call để xác nhận và cập nhật thông tin đơn hàng. chuyển cho bộ phận đóng gói, gửi bưu điện, cập nhật mã COD, tình trạng giao hàng, huỷ hàng,...
 - Có tính năng dành cho admin: biểu đồ thống kê số lượng mặt hàng bán được trong từng ngày. (sử dụng grafana)
 - backend: sử dụng nodered xử lý request gửi lên từ javascript, phản hồi về json.
