# Markdown là gì?

![](https://i.pinimg.com/originals/c4/a6/db/c4a6db3cba16fc150e3db76ca3c326d2.png)

Markdown là cú pháp định dạng từ văn bản sang HTML cho người viết web với định dạng văn bản đơn giản dễ đọc, dễ viết, sau đó chuyển đổi nó sang định dạng HTML hay JSON với cấu trúc hợp lệ[1].


Markdown ban đầu được [phát triển bởi John Gruber](https://daringfireball.net/projects/markdown/) vào năm 2004. Thiết kế gọn nhẹ của Markdown đã thu hút các nhà phát triển và thiết kế phần mềm tin dùng.

Chúng ta có thể soạn tài liệu markdown trên Jupyter notebook hay những chương trình chuyên biệt như Markdown editor. Đầu tiên, chúng ta xây dựng tài liệu Markdown đầu tiên qua công cụ soạn thảo trực tuyến - [Dillinger](https://dillinger.io). 

### Xây dựng tiêu đề (header)

Markdown cung cấp hai kiểu tiêu đề: Setext và atx. Ở đây, ta sẽ tìm hiểu về kiểu tiêu đề atx. Để tạo tiêu đề kiểu atx, bạn đặt 1-6 **#**  ở đầu dòng - số lượng băm bằng với mức tiêu đề HTML hiển thị kết quả. Ví dụ:
![](https://i.imgur.com/gke27SF.png?1)

### In đậm, in nghiêng trong Markdown

Để trực quan hoá một cách tốt nhất, ta có thể xem qua ví dụ sau:
![](https://i.imgur.com/6ggmbFr.png?1)

### Chèn hyperlink cho text và hình ảnh trong Markdown

Trong Markdown ta sử dụng cú pháp sau để chèn link cho text:
> [text cần chèn hyperlink](đường dẫn đến link)

Tương tự việc chèn hyperlink, cú pháp sau đây sẽ giúp bạn chèn hình ảnh:
> ![](đường dẫn đến ảnh cần chèn)

Ví dụ: 
![](https://i.imgur.com/ZxT6qL6.png?1)

### Xây dựng Blockquotes

Để xây dựng Blockquotes, bạn đặt ký tự **>** ở đầu dòng. Ví dụ:
![](https://i.imgur.com/CKibdul.png?1)

### Xây dựng danh sách trong Markdown

Ta sử dụng dấu hoa thị, dấu cộng và dấu gạch nối (*, + và -) làm điểm đánh dấu danh sách. Ba điểm đánh dấu này có thể thay thế cho nhau. Ví dụ:
![](https://i.imgur.com/HAvkt3V.png?1)

### Chèn mã nguồn lập trình vào Markdown

Ta sử dụng ký hiệu `` để làm nội bật phần code. Hãy xem ví dụ sau:
![](https://i.imgur.com/LdUsktX.png?1)

### Chèn công thức toán học trong Markdown

Để chèn công thức toán, đầu tiên chúng ta cần dùng một editor để tạo công thức dùng mã LaTeX. Các editor hỗ trợ việc tạo công thức mà không cần chúng ta phải nhớ mã LaTeX. Ta có thể truy cập một trang editor hỗ trợ mẫu tại [đây](https://www.codecogs.com/latex/eqneditor.php) để xây dựng công thức.

![](https://i.imgur.com/LqXXUpB.png?1)

Đây là ví dụ tạo công thức từ trang web. Công thức được hiện thị ở phần dưới, và code latex tương ứng ở trong khung. Việc tạo công thức khá trực quan, các bạn thao tác với nó khoảng 30 phút là thành thạo.

Bước tiếp theo, chúng ta sẽ copy mã latex vào markdown và để trong cặp dấu $$ ... $$ như sau:

![](https://i.imgur.com/0SzWIDT.png?1)

Như vậy chúng ta đã học qua cách viết tài liệu Markdown cơ bản. Những tiện ích khác của Markdown, các bạn xem thêm ở [link sau đây](https://guides.github.com/features/mastering-markdown/) nhé.

# Nguồn tài liệu tham khảo

- [Markdown document from Daringfireball website](https://daringfireball.net/projects/markdown/basics)
