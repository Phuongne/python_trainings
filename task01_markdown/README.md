##Task 1
-----------------

>Người thực hiện: Ngô Huỳnh Thảo Phương
>
>Tên tài liệu:
>http://bit.ly/2cxplkv
>http://bit.ly/2cxrr2B
>https://vi.wikipedia.org/wiki/Markdown
>
>Ngày cập nhật: 24/02/2017
---------------------------

##Mục lục:

[1.Github là gì? dùng làm gì?](#1)

[2.Tạo repository đặt tên là python_trainings](#2)

[3.Markdown là gì? Dùng để làm gì?](#3)

[4.Các cú pháp thường gặp.](#4)

[5.Cài đặt Sublime Text và tìm kiếm, cài đặt các công cụ hỗ trợ markdown (export HTML, markdown preview, …).](#5)

[6.Các công cụ viết markdown khác:](#6)

##Nội dung:

####1.Github là gì? Dùng làm gì?<a name="1"></a>

#####Github là gì?

Github là một dịch vụ máy chủ repository công cộng, mỗi người có thể tạo tài khoản trên đó để tạo ra các kho chứa của riêng mình để có thể làm việc.

![image](http://i.imgur.com/H51nBzj.png)

#####Github dùng làm gì?<a name=""></a>

GitHub chủ yếu được sử dụng để lưu trữ mã nguồn phần mềm, nhưng cũng thường được sử dụng với nhiều loại tập tin như Final Cut hoặc các tài liệu Word. Cho phép bạn lưu source code của mình lên đó. Người dùng có thể thay đổi đoạn code của mình mọi lúc mọi nơi hay cũng có thể khôi phục được code của mình vào một thời điểm bất kì.

![image](http://i.imgur.com/hUs1b9n.png)

####2.Tạo repository đặt tên là python_trainings.<a name="2"></a>

Đầu tiên, phải đăng kí miễn phí một tài khoản Github bằng cách truy nhập vào trang web : https://github.com

![image](http://i.imgur.com/tqZsu6q.png)

Sau khi tạo xong tài khoản với Username/Password và địa chỉ email, bạn phải vào email và kích hoạt tài khoản.

Bắt đầu tạo repository sau khi đăng nhập vào tài khoản.

Chọn New repository, tiếp theo làm theo hình mẫu :

![image](http://i.imgur.com/Pb8dNPN.png)

![image](http://i.imgur.com/8g7v3eB.png)

Repository đã được tạo ra. 

####3.Markdown là gì? Dùng để làm gì?<a name="3"></a>

#####Markdown là gì?

![image](http://i.imgur.com/PnmhyN2.png)

Markdown là một ngôn ngữ đánh dấu với cú pháp văn bản thô, được thiết kế để có thể dễ dàng chuyển thành HTML và nhiều định dạng khác sử dụng một công cụ cùng tên.

#####Markdown dùng để làm gì?

 + Markdown thường được dùng để tạo các tập tin readme, viết tin nhắn trên các diễn đàn, và tạo văn bản có định dạng bằng một trình biên tập văn bản thô.

 + Markdown còn dùng để tạo ra một định dạng văn bản thô dễ viết, dễ đọc, dễ dàng chuyển thành XHTML (hoặc HTML).

####4.Các cú pháp thường gặp.<a name="4"></a>

#####a. Thẻ tiêu đề :

 + Markdown sử dụng kí tự # để bắt đầu cho các thẻ tiêu đề, có thể dùng từ 1 đến 6 ký tự # liên tiếp. Mức độ riêu đề giảm dần từ 1 đến 6.

Tùy mục đích và ý thích bạn có thể sử dụng cách này để thể hiện các chỉ mục khác nhau.

 + Ví dụ :

![image](http://i.imgur.com/EioTEDr.png)

#####b. Chèn link, chèn ảnh :

 + Chèn link : Để chèn hyperlink bạn chỉ cần paste luôn link đó vào file .md http://gitmub.com hoặc cũng có thể sử dụng cú pháp sau để thu ngắn đường dẫn của link: `[text](link_can_chen)`.

 + Chèn hình : Để chèn ảnh hãy sử dụng cú pháp sau: `![text](link_hinh_can_chen)`.

#####c. Ký tự in đậm, in nghiêng :

 + Để in đậm đoạn text ta cần làm như sau : `** từ_cần_in_đậm **`

 + Để in nghiêng đoạn text ta cần làm như sau : `* từ_cần_in_nghiêng *`

#####d. Trích dẫn, bo chữ :

 + Để bo chữ ta cần làm như sau :
 
```sh 
  `đoạn_cần_bo` 
```

 + Để làm nổi bật một đoạn ta làm như sau : 

```javascript
    ```sh
         đoạn_cần_nổi_bật
    ```
```

#####e. Tạo bảng :

```sh
| Cột 1 Hàng 1 | Cột 2 | Cột 3 | Cột 4 |
|--------------|-------|-------|-------|
| Hàng 2 |   text  |   text   |   text   |
| Hàng 3 |   text  |   text   |   text   |
```

#####f. Khác:

 + Gạch ngang đoạn text : ` ~~text_cần_gạch~~`
 
 + Kẻ lề : `> Text `

 + Đường kẻ ngang : `------------`
 
####5.Cài đặt Sublime Text và tìm kiếm, cài đặt các công cụ hỗ trợ markdown (export HTML, markdown preview, …)<a name="5"></a>

#####Công cụ cần có :

 + Sublime Text 3.

 + Plugin Markdown Editing, Markdown Preview.

#####Thực hiện :

######Bước 1: Cài đặt Package Control:

 + Cài đặt ST3, download tại http://www.sublimetext.com/3.

 + Mở ST3, nhấn tổ hợp phím Ctr+` và nhập code sau:

` import urllib.request,os,hashlib; h = '2915d1851351e5ee549c20394736b442' + '8bc59f460fa1548d1514676163dafc88'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by) `

 + Khởi động lại ST3.

######Bước 2: Cài đặt Plugins

 + Vào Preferences > Package Control > Install Package > Nhập Markdown Editing

 + Tương tự nhưng nhập Markdown Preview.

 + Chờ cài đặt xong, khởi động lại ST3.

######Bước 3: Cài đặt phím tắt

 + Thiết lập phím tắt để sử dụng Markdown Preview: Vào Preferences > Key Bindings - User nhập (Bạn có thể sử lại alt+m thành phím tắt mà bạn muốn) sau đó lưu lại:

`[
{ "keys": ["alt+m"], "command": "markdown_preview", "args": {"target": "browser", "parser":"markdown"} }
]`

 + Khởi động lại ST3.

######Bước 4: Kiểm tra thử

 + Test xem như thế nào, tạo file *.md, nhập thử đoạn markdown.

 + Nhấn tổ hợp phím alt+m (mặc định) hoặc tổ hợp phím mà bạn đã cài đặt để xem trước trên trình duyệt.

####6.Các công cụ viết markdown khác<a name="6"></a>

#####a.StackEdit

StackEdit là ứng dụng soạn thảo văn bản trực tuyến với khả năng tích hợp với các tài khoản đám mây hay xuất file lên rất nhiều trang web nhanh chóng và tiện lợi

######Đặc điểm chính của ứng dụng soạn thảo văn bản trực tuyến StackEdit :

 + Trình soạn thảo ngôn ngữ markdown giàu tình năng với khả năng highlight cú pháp, hiển thị hình ảnh văn bản trực quan.

 + Soạn văn bản theo dạng WYSIWYG với các shortcut và nút chọn tiện ích.

 + Xem trước với Scroll Sync, so sánh, đối chiếu hình ảnh hiển thị của văn bản và dạng soạn thảo cùng lúc trên 2 cột song song.

 + Tích hợp công cụ kiểm tra lỗi chính tả ngay trong ứng dụng, hỗ trợ nhiều ngôn ngữ và có gợi ý cách sửa.

 + Khả năng tùy chỉnh đa dạng với nhiều lựa chọn theme, layout, shortcut.
 
 + Khả năng tải văn bản trực tiếp lên Blogger, GitHub, Tumblr, WordPress... Người dùng có thể lựa chọn tải lên dưới định dạng markdown, HTML hoặc tự định dạng đầu ra bằng bộ engine Underscore.

 + Cùng làm việc trên 1 file: File có thể được đồng bộ hóa và chia sẻ qua Google Drive hay Dropbox. Khi nhiều người cùng làm việc trên file, StackEdit sẽ thực hiện việc ghép các thay đổi được thực hiện bởi từng người dùng.

 + Tính năng bình luận trong bài viết hữu ích để trao đổi.

######Các lựa chọn cài đặt ứng dụng

 + Hướng layout của trang.

 + 7 lựa chọn theme.

 + Hỗ trợ tối đa 3 tài khoản Google Drive.

 + Lựa chọn sử dụng Markdown Extre, GitHub Flavored Markdown hoặc LaTeX.

 + Chế độ soạn thảo từ trái sang hay từ phải sang.

 + Lựa chọn extension đa dạng như Google Analytics, Notifications, Scroll Sync, Table of Contents...

#####b.jbt

#####c.tablesgenerator




