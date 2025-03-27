# LÀM VIỆC VỚI THƯ MỤC 
## 1. Tổ chức thư mục trong linux 
Linux sử dụng tổ chức thư mục kiểu `Hierachical Structure` (quan hê phân cấp). Mọi thứ đều bắt nguồn thừ thư mục root và trải ra các thư muc cấp nhỏ hơn 

Sử dụng dấu / để tạo đường dẫn thay vì \ trong Windows 

![Structore](https://res.cloudinary.com/rs-designspark-live/image/upload/c_limit,w_829/f_auto/v1/article/linux-filesystem_cfcd347a69d985358fef9424021716d926775286)

Được phân cấp dựa vào độ quan trọng của từng thư mục. Mỗi thư mục có 1 chức năng riêng. Ta có thể tham khảo tại [đây](https://www.rs-online.com/designspark/an-intro-to-linux-file-system-management)
## 2. Di chuyển giữa các thư mục 
Ta sử dụng lệnh `cd` để di chuyển giữa các thư mục 

***Cú pháp:*** 

 `cd` `ten thu muc` : DI chuyển vào trong 

 `cd` `../`: Di chuyển ra ngoài một cấp thư mục 

`cd $home`: Di chuyển ra tận ngoài thư mục root 

## 3. Tạo, xóa thư mục 

### 3.1 Tạo thư mục 
`mkdir` + *folder_name*: Tạo một thư mục trống trong thư mục hiện tại

`mkdir -p` *đường_dẫn*: Tạo thư mục mới ngay bên trong đường dẫn. Nếu sử dụng cách thứ nhất thì không thể truyền đường dẫn. 

### 3.2 Xóa thư mục 
`rm -r` *ten_thu_muc*: Xóa thư mục đúng tên 

Ngoài ra, lệnh `rm -r` hỗ trợ việc chèn đường dẫn để xóa 

## 3.3 Copy thư mục 
`cp folder_name destination`: Sao chép folder vào destination tương ứng. Nhưng không thể sao chép nếu trong dó có các thư mục và tệ con 

Có thể thực hiện sao chép nhiều thư mục bằng cách chèn thêm nhiều tên folder liên tiếp 

Ta có thể thực hiện sao chéo **Đê quy** bằng cách thê flag -r vào trước, Lúc này sẽ sao chép toàn bộ tệp và thư mục con 

## 4. Di chuyển thư mục 
`mv folder_name destination`: Di chuyển thư mục vào destination 

`mv name_1 name_2`: Nếu thực hiện trong cùng một thư mục thì nó sẽ có chức năng rename thư mục 





