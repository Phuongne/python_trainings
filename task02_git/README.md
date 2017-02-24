##Task 2

---------------------
>Người thực hiện: Ngô Huỳnh Thảo Phương
>
>Tên tài liệu:
>
>https://thachpham.com/tools/git-git-va-github-la-gi-tai-sao-nen-dung.html
>
>https://thachpham.com/tools/git-cai-dat-git-va-thiet-lap-ban-dau.html
>
>https://thachpham.com/tools/hieu-them-ve-commit-va-staging-area-git.html
>
>http://webfaver.com/thu-thuat/huong-dan-su-dung-git-co-ban.html
>
>Ngày cập nhật: 24/02/2017
----------------------

##Mục lục: 

[1.Git là gì? Dùng làm gì?](#1)

[2.Cài đặt git trên máy tính.](#2)

[3.Cách sử dụng git trên cmd (terminal).](#3)

[4.Sử dụng git để commit/ push file readme.md lên github.](#4)

##Nội dung:

####1.Git là gì? Dùng làm gì?<a name="1"></a>

 + Git là tên gọi của một Hệ thống quản lý phiên bản phân tán (Distributed Version Control System – DVCS) là một trong những hệ thống quản lý phiên bản của mã nguồn.

![image](http://i.imgur.com/9LhfF6U.png)

 + Git dùng để giúp mỗi máy tính có thể lưu trữ nhiều phiên bản khác nhau của một mã nguồn được nhân bản (clone) từ một kho chứa mã nguồn (repository), mỗi thay đổi vào mã nguồn trên máy tính sẽ có thể ủy thác (commit) rồi đưa lên máy chủ nơi đặt kho chứa chính. Và một máy tính khác (nếu họ có quyền truy cập) cũng có thể clone lại mã nguồn từ kho chứa hoặc clone lại một tập hợp các thay đổi mới nhất trên máy tính kia.

####2.Cài đặt git trên máy tính<a name="2"></a>

Đầu tiên ta phải cài đặt ứng dụng Git vào máy tính. (Đối với Windows)

Tải file .exe cài đặt Git tại địa chỉ: http://git-scm.com/download/win. Khi cài bạn có thể để nguyên tùy chọn mặc định mà không cần tùy chỉnh gì thêm nếu bạn chưa hiểu về nó.

Sau khi cài đặt Git vào Windows, bạn sẽ cần mở ứng dụng Git Bash lên để bắt đầu sử dụng các dòng lệnh của Git.

Tiếp theo bạn nên làm là khai báo tên và địa chỉ email vào trong file cấu hình của Git trên máy. Để làm điều này bạn sẽ cần sử dụng hai lệnh sau đây để thiết lập tên và email.

```sh
$ git config --global user.name : "ten_USERNAME"
$ git config --global user.email  "ten_mail"
```

Sau khi thiết lập xong, bạn có thể kiểm tra thông tin chứng thực trên user của bạn bằng cách xem tập tin : `cat ~/.gitconfig`.

####3.Cách sử dụng git trên cmd (terminal)<a name="3"></a>

Đầu tiên, ta phải tạo 1 folder gốc lưu trữ dữ liệu của các repo khi clone về máy tính.

Vào Start-> Run-> Cmd

![image](http://i.imgur.com/lpNYx5O.png)

Gõ lệnh: git clone `https://github.com/<ten_USERNAME>/<ten_repo>.git`

Trong đó câu lệnh trên ta copy như hình :

![image](http://i.imgur.com/hF443Tv.png)

![image](http://i.imgur.com/0kzHsFV.png)

Nhấn Enter và cho chương trình chạy. 

####4.Sử dụng git để commit/ push file readme.md lên github<a name="4"></a>

Đầu tiên, bạn chọn Git Bash. Tiếp theo dùng lệnh cd để đến được thư mục chính (master) đã được clone về trước đó.

![image](http://i.imgur.com/kQZO3c2.png)

Thực hiện commit lên github bằng các câu lệnh dưới đây: ( đảm bảo file readme.md đã được lưu trong thư mục chính đã tạo trước đó.)

```sh
$git add *
$git commit -m "text"
$git push origin master
```

Sau khi thực hiện các câu lệnh, trên màn hình xuất hiện master -> master (như hình) là việc commit/ push file readme.md lên github đã thành công.

![image](http://i.imgur.com/d5WAZGl.png) 


