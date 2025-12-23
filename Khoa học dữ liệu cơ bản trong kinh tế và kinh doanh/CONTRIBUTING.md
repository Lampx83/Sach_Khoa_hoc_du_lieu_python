# Cách chỉnh sửa bài giảng
1. Fork repository về tài khoản cá nhân, ví dụ: https://github.com/Lampx83/Sach_Khoa_hoc_du_lieu_python
2. Clone repository fork về máy local, ví dụ: 
   ```
   git clone https://github.com/Lampx83/Sach_Khoa_hoc_du_lieu_python.git
   ```
3. Thực hiện chỉnh sửa bài giảng
4. Commit chỉnh sửa lên
   ```
   git commit -am "Sửa lỗi chính tả"
   git push
   ```
 5. Truy cập vào repository gốc (của trường công nghệ)
 6. Chọn Pull requests → New pull request
 7. Nhấn Compare across forks
 8. Cấu hình chính xác:
    * Base repository: NCT
    * Head repository: Của bạn
  9. Nhấn Create pull request
