<!-- Những dòng lệnh thực hiện trên terminal -->

<!-- Danh từ -->
# Terms 

<!-- Thư mục dự án -->
Repository(Repo)

<!-- Lệnh -->
# Commands

<!-- Sử dụng được git trong dự án -->
- git init

<!-- Trạng thái dự án (Hiểu thị tất cả file trên dự án-->
<!-- Nó cũng ghi nhận trạng thái của các file bị thay đổi nội dung -->
- git status

<!-- Chuẩn bị Lưu file -->
- git add
<!-- Ví dụ muốn lưu file index.html. Ta có thể đánh git add index.html--
Muốn lưu tất cả file để lưu git add . -->

<!-- Trở về lại tất cả, tất cả file chuẩn bị lưu sẽ dừng chuẩn bị lưu -->
- git reset

<!-- Chính thức lưu -->
- git commit

<!-- Cú pháp ghi chú -->
- -m ' ..........' 
<!--Ví dụ ghi chú sau dòng chính thức lưu : 
    git commit -m 'thời điểm chuẩn bị bắt đầu'   -->

<!-- Thể hiện thời điểm đã lưu  -->
- git log
<!-- Nó sẽ có id, người lưu, thời điểm lưu -->

- git log --oneline
<!-- Rút gọn thời điểm đã lưu, nó chỉ hiển thị những tập tin đã lưu trên dòng . Bao gồm id và tệp lưu  -->

- git checkout (id_comit)
<!-- Nếu dùng git log thấy những tệp đã lưu, nhưng bạn muốn chỉ chọn 1 tệp lưu trước đó. Ta sử dụng git checkout id tệp lưu đó. 
Ví dụ: có hai tệp lưu mang id   789: Tệp 1    833: Tệp 2 
Và ta chọn tệp 1.
Ta ghi git checkout 789
Và khi mở lên dữ án, nó chỉ hiển thị tệp 1 khi dùng Liver xem thành quả dự án-->
- git checkout master 
<!-- Là dạng resert trở về như cũ sau khi dùng git checkout(id_comit) -->

<!-- Nhánh của git checkout -->
- git branch 
<!-- Sau khi dùng git checkout thì ta sử dụng git branch. Nó sẽ hiển thị nhân tố đằng sau của git checkout. 
    Ví dụ: git checkout master là một dạng resert. 
            Thì dùng git branch, nó trả về master
            
    Ví dụ: git checkout 9372
            Thì git branch: 9372 -->



<!--  Đẩy code từ local repository (máy tính) lên remote repository (GitHub)
25:27: Lấy code từ remote repository đã có sẵn GitHub về local repository (máy tính)
28:00: Tạo và đẩy branch (nhánh) ở local lên Repository remote (GitHub)
29:18 : Lấy branch (nhánh) từ Repository remote (GitHub) về local repository (máy tính)
33:00: git ignore (ngăn chặn git theo dõi 1 file nào đó) -->