# ENVIRONMENT VARIABLES 

>An environment variable is a variable whose value is set outside the program, typically through functionality built into the operating system or microservice. An environment variable is made up of a name/value pair, and any number may be created and available for reference at a point in time.

Hiểu đơn giản nó là một biến thuộc về cấu hình môi trường đang chạy, có thể ảnh hưởng đến tiến trình hoạt động của các chương trình 

## 1. Hiển thị biến môi trường 
Sử dụng lệnh `env` để hiể thị tất cả biến môi trường hiện có 

In biến môi trường: `printenv TEN_BIEN`

VD: `printenv HOME` 

Để sử dụng biến môi trường, ta đặt dấu $ trước tên biến 
cd $HOME: Di chuyển tới home 
echo $HOME: In nội dung biến HOME 

## 2. Cài đặt biến môi trường 
`export TEN_BIEN=GIATRI` 

Để cài đặt biến lâu dài, ta đặt biến đó trong file ~/.bashrc 
source ~/.bashrc: Chạy file 

Lệnh export cũng có thể dùng đặt lại giá trị cho biến 

Để xóa biến, ta dùng lệnh `unset TENBIEN`
