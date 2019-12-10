# Giới thiệu về Jupyter Notebook

Jupyter Notebook là một ứng dụng web mã nguồn mở cho phép bạn tạo và chia sẻ các tài liệu có chứa mã nguồn trực tiếp, các công thức hay ký hiệu toán học và văn bản.

Jupyter đã hỗ trợ hơn 40 ngôn ngữ lập trình khác nhau và Python là một trong số đó. Để cài đặt Jupyter Notebook, cần yêu cầu Python 3.3 trở lên hoặc Python 2.7.

![](https://i2.wp.com/softwareengineeringdaily.com/wp-content/uploads/2018/07/jupyter-logo-featured-image.png?resize=600%2C315&ssl=1)

## Cài đặt Jupyter qua Anaconda

Bạn có thể cài đặt Python và Jupyter bằng Anaconda. Chỉ với Anaconda, bạn sẽ cài đặt Python, Notebook Jupyter lẫn các công cụ hỗ trợ tính toán. Bạn có thể tìm hiểu và tải Anaconda [tại đây](https://www.anaconda.com/distribution/)

## Cài đặt Jupyter với lệnh Pip

Với Window bạn mở Command Prompt, còn Linux bạn Terminal và chạy dòng lệnh sau:

```
python3 -m pip install --upgrade pip
python3 -m pip install jupyter
```

Thực hiện lệnh sau để khởi động Jupyter Notebook:

```
jupyter notebook
```

Khi khởi động, chương trình của bạn sẽ hiển thị như sau và Jupyter Notebook sẽ tự khởi động trên trình duyệt của bạn.

![](https://media.geeksforgeeks.org/wp-content/uploads/jupyter_launch.png)

Đầu tiên, bạn sẽ thấy Notebook Dashboard hiển thị danh sách các file ghi chép, tệp tin và thư mục con trong mục khởi động máy chủ.

![](https://i.imgur.com/MfVAmXe.png?1)

## Tạo một notebook đầu tiên

Bây giờ ở Dashboard, bạn có thể thấy một nút **New** ở góc trên cùng bên phải. Nhấp vào nó để mở danh sách thả xuống và sau đó nếu bạn nhấp vào Python3, nó sẽ tạo và mở ra một Notebook mới.

![](https://media.geeksforgeeks.org/wp-content/uploads/new_notebook.png)

Ở mỗi Block, bạn có thể tự do code và để chạy code bạn ấn tổ hợp phím **Shift** + **Enter**.

![](https://i.imgur.com/EsJWZyz.png?1)

Ở trên Block đầu tiên, bạn cũng sẽ thấy một nút **Code**. Nhấp vào nó để mở danh sách thả xuống và bạn có thể thấy ngoài Python thì bạn còn có thể sử dụng Markdown để ghi chú song hành khi code. Đây cũng là một trong những điểm đặc biệt của Jupyter Notebook.

## Tham khảo một số lệnh hữu ích với Jupyter 

1. Mở một notebook bất kỳ 

```
jupyter notebook notebook_name.ipynb
```

2. Theo mặc định, máy chủ notebook bắt đầu trên cổng 8888. Nếu cổng 8888 không khả dụng hoặc đang sử dụng, máy chủ notebook sẽ tìm kiếm cổng có sẵn tiếp theo. Bạn cũng có thể chỉ định một cổng bằng tay. Trong ví dụ này, AI VIET NAM sẽ đặt cổng máy chủ thành 9999:

```
jupyter notebook --port 9999
```

3. Lệnh khởi động máy chủ notebook mà không cần mở trình duyệt web

```
jupyter notebook --no-browser
```

4. Lệnh hỗ trợ ở Jupyter

```
jupyter notebook --help
```
