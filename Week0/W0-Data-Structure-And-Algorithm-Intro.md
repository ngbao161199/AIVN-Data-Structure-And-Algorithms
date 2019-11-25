# Tìm hiểu kiến thức về Cấu trúc dữ liệu và giải thuật

**Cấu trúc dữ liệu và giải thuật** là một trong những khái niệm cơ bản nhất trong tính toán. Chúng là nền tảng cơ bản để từ đó xây dựng các kiến trúc phần mềm, ứng dụng phức tạp hiện nay. Trang bị nền tảng cơ bản này là cực kỳ quan trọng trong thiết kế phần mềm và chúng liên quan đến ba đặc điểm sau:
- Làm thế nào các thuật toán thao tác thông tin có trong cấu trúc dữ liệu?
- Cách sắp xếp dữ liệu trong bộ nhớ?
- Các đặc tính hiệu suất của các cấu trúc dữ liệu cụ thể là gì?

![](https://image.slidesharecdn.com/datastructuresandalgorithms-131101140849-phpapp01/95/data-structures-and-algorithms-2-638.jpg?cb=1383315896)
<br><br>
Và tại đây, chúng ta sẽ nhìn nhận chủ đề này từ một số quan điểm. 
<br><br>
Đầu tiên, chúng ta sẽ xem xét các nguyên tắc cơ bản của ngôn ngữ lập trình Python từ góc độ cấu trúc dữ liệu và giải thuật. 
<br><br>
Thứ hai, điều quan trọng là chúng ta phải có một công cụ toán học chính xác. Chúng ta cần hiểu một số khái niệm cơ bản của khoa học máy tính và để thực hiện điều này, chúng ta cần toán học. Qua cách tiếp cận ở các hàm heuristic hay phát triển những nguyên lý cơ bản thì việc trang bị các nền tảng toán học sẽ vô cùng quan trọng.
<br><br>
Một khía cạnh quan trọng khác là đánh giá. Đo lường hiệu suất thuật toán liên quan đến thấu hiểu làm thế nào mỗi lần tăng kích thước dữ liệu ảnh hưởng đến hoạt động trên dữ liệu đó. Khi chúng ta làm việc trên các bộ dữ liệu lớn hoặc các ứng dụng thời gian thực, điều cần thiết là các thuật toán của chúng ta và cấu trúc dữ liệu được tổ chức hiệu quả.
<br><br>
Cuối cùng, chúng ta cần một chiến lược thiết kế thử nghiệm hiệu quả. Có thể hiểu rằng bạn thấu hiểu một vấn đề trong thực tế, tìm kiếm cấu trúc dữ liệu và giải thuật của ngôn ngữ lập trình liên quan đến việc để lựa chọn giải quyết và liên kết chúng vào cấu trúc lập trình.
<br><br>
Để trang bị một góc nhìn sâu sắc về **tư duy thuật toán**, hãy xem xét một ví dụ thực tế sau.
<br><br>
![](https://uploadarticle.com/wp-content/uploads/2018/03/timing-stock-market.jpg)
<br><br>
Hãy tưởng tượng chúng ta đang ở một thị trường xa lạ và chúng ta được giao nhiệm vụ mua một danh sách mặt hàng. Chúng ta giả định rằng thị trường được đặt ra ngẫu nhiên và mỗi nhà cung cấp bán ngẫu nhiên mặt hàng của các mục, một số trong đó có thể nằm trong danh sách của chúng ta. Mục đích của chúng ta là giảm thiểu giá chúng ta phải trả cho từng mặt hàng cũng như giảm thiểu thời gian dành cho thị trường. 
<br><br>
Một cách để tiếp cận điều này là để viết một thuật toán như sau:
<br><br>
Thực hiện một vòng lặp cho mỗi nhà cung cấp:
  1. Nhà cung cấp có các mặt hàng trong danh sách của chúng ta và có chi phí thấp hơn chi phí dự đoán cho các mặt hàng?
  2. Nếu có, mua và xóa khỏi danh sách; nếu không, chuyển sang nhà cung cấp tiếp theo.
  3. Nếu không còn nhà cung cấp, kết thúc.
<br><br>
Đây là một vòng lặp đơn giản với một quyết định và một hành động. Nếu chúng ta thực hiện điều này, chúng ta sẽ cần cấu trúc dữ liệu để xác định cả danh sách các mặt hàng chúng ta muốn mua cũng như danh sách các mặt hàng của từng nhà cung cấp. Chúng ta sẽ cần xác định cách phù hợp nhất với các mục trong mỗi danh sách và chúng ta cần một số cấu trúc logic để quyết định có nên mua hay không.
<br><br>
![](https://marketrealist.imgix.net/uploads/2016/09/Soybean-Prices-2016-09-12.jpg)
<br><br>
Có một số quan sát mà chúng ta có thể thực hiện liên quan đến thuật toán này. Thứ nhất, kể từ khi tính toán chi phí dựa trên dự đoán, chúng ta không biết chi phí trung bình thực là bao nhiêu; nếu chúng ta dự đoán chi phí của một mặt hàng, chúng ta đi đến cuối thị trường với các mặt hàng còn lại trên danh sách của chúng ta. Do đó, chúng tôi cần một cách hiệu quả để quay lại nhà cung cấp với chi phí thấp nhất.
<br><br>
Ngoài ra, chúng ta cần hiểu những gì xảy ra với thời gian cần thiết để so sánh các mục trên danh sách mua sắm với các mặt hàng được bán bởi mỗi nhà cung cấp là số lượng mặt hàng trong danh sách mua sắm của chúng ta, hoặc số lượng mặt hàng được bán bởi mỗi nhà cung cấp. Thứ tự mà chúng ta tìm kiếm thông qua các mục và hình dạng của cấu trúc dữ liệu có thể tạo ra sự khác biệt lớn đối với thời gian nó cần để thực hiện tìm kiếm. Rõ ràng, chúng ta muốn sắp xếp danh sách của mình, cũng như thứ tự truy cập mỗi nhà cung cấp, theo cách mà chúng ta giảm thiểu thời gian tìm kiếm.
<br><br>
Ngoài ra, hãy xem xét những gì xảy ra khi chúng ta thay đổi điều kiện mua để mua với giá rẻ nhất, không chỉ giá trung bình dưới đây. Điều này thay đổi hoàn toàn vấn đề. Thay vì tuần tự đi từ nhà cung cấp này sang nhà cung cấp tiếp theo, chúng ta cần đi qua thị trường một lần và, với kiến thức này, chúng ta có thể đặt hàng danh sách mua sắm của chúng ta liên quan đến các nhà cung cấp mà chúng tôi muốn lựa chọn.
<br><br>
Rõ ràng, có rất nhiều sự tinh tế hơn liên quan đến việc chuyển dịch một vấn đề trong thế giới thực sang một cấu trúc trừu tượng như ngôn ngữ lập trình. 
<br><br>
Ví dụ, khi tri thức chúng ta tiến bộ thông qua thị trường, kiến thức của chúng ta về giá thành của một sản phẩm được cải thiện => Chúng ta dự đoán giá trung bình sản phẩm trở nên chính xác hơn cho đến khi kiến thức của chúng ta về thị trường là gần như hoàn hảo. Giả sử bất kỳ loại thuật toán quay lui nào phát sinh chi phí, chúng ta có thể thấy nguyên nhân để xem xét toàn bộ chiến lược của mình. Các điều kiện như biến động giá cao, kích thước và hình dạng cấu trúc dữ liệu và chi phí quay lui tất cả quyết định nhiều nhất cho một giải pháp phù hợp.
