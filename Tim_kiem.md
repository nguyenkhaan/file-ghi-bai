# TÌM KIẾM THÔNG TIN THƯ MỤC, Ổ ĐĨA  
Lệnh `grep`, `find`, `history`, `sort`
## 1. Lệnh grep 
Dùng để tìm kiếm nội dung trong đầu ra (stdin) hoặc trong một thư mục 

`grep "Noi_dung_can_tim" ten_file`: Tìm kiếm từ khóa trong file 

`grep "Noi_dung_can_tim" path`: Tìm kiem file có chứa từ khóa cần tìm bên trong đường dẫn 

Ngoài ra, còn cung cấp cho chúng ta một số chỉ thị 
1. -r: Tìm kiếm đẹ quy trong thư mục 
2. -i: Tìm kiếm không phân biệt hoa thường 
3. -n: Hiển thị số dòng của nội dung tìm kiế 
4. -o: Tìm kiếm chính xác (only matches)  
## 2. Lệnh find 
Tìm kiếm file hoặc thư mục theo nhiều tiêu chí 

`find path option option option expression`
- option: Tiêu chí tìm kiếm 
- path: đường dẫn bắt đầu tìm kiế 
- expression: biểu thức 