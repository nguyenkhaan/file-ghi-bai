# QUẢN LÍ TRONG LINUX 
Lệnh `sudo` `chmod` 
## sudo 
Lớp sudo giúp bạn chạy các file, phầ mềm hệ thống với quyề quản trị cao nhất **super user do** 

`sudo command`: Chạy lệnh với quyền sudo 
## chmod 
Trong Linux có phần ra 3 kiểu sở hữu cho file 
1. u (user): Chủ sở hữu. Thường là người tạo ra nó 
    - Xem danh sách người dùng: less `/etc/passwd `
2. g (group): Nhóm nguoif dùng có quyền truy cập chung và sử dụng 
3. o (other): Không thuôc hai nhóm trên 

Các quyền đối với file: 
1. r: đọc file 
2. w: Ghi file 
3. x: Thực thi 
### a. Sử dụng hệ thống kí hiệu 
1. +: Thêm quyề 
2. -: Xóa quyền 
3. =: Gán quyền 

`chmod doi_tuong ki_hieu,.. ten_file` 

Ví dụ: chmod u+wrx, go+r 

### b. Sử dụng chữ số 
- Số thứ nhất đại diện cho user, số thứ 2 đại diện cho group, số thứ 3 đại diện cho other 

- 0: Không có quyền
- 1: Thực thi
- 2: Viết
- 3: Viết và thực thi
- 4: Đọc
- 5: Đọc và thực thi
- 6: Đọc và viết
- 7: Đọc, viết và thực thi

`chmod n1n2n3 ten_file` 


