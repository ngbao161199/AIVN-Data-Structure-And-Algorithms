# Bài tập 2

**Câu 1**. Cho 3 số nguyên A, B, C. Viết chương trình tìm số lớn nhất trong 3 số trên.

| Input       | Output |
|-------------|--------|
| 3 5 7       | 7      |
| 999 888 777 | 999    |


**Câu 2**. Cho 3 số nguyên N, A, B với A, B đều bé hơn N. Xuất các số từ 0 -> N ngoại trừ các số trong khoảng từ A -> B.

| Input       | Output          |
|-------------|-----------------|
| 10 2 7      | 0 1 8 9 10      |
| 999 0 997   | 998 999         |

**Câu 3**. Cho 3 số nguyên N, A, B với A, B đều bé hơn N. Xuất các số từ 0 -> N ngoại trừ các số trong khoảng từ A -> B. Bên cạnh đó, cũng loại trừ các số chia hết cho 3 hoặc 5.

| Input       | Output                 |
|-------------|------------------------|
| 20 4 14     | 0 1 2 16 17 19 20      |

**Câu 4**. Nhập một số nguyên N. Viết chương trình Python hiển thị kết quả sau khi chuyển số nguyên N sang số nhị phân.

| Input | Output  |
|-------|---------|
| 77    | 1001101 |
| 17    | 10001   |

**Câu 5**. Theo định nghĩa của Wikipedia thì số nguyên tố là số tự nhiên lớn hơn 1, chỉ có 2 ước là 1 và chính nó. Theo định nghĩa này thì các số 2, 3, 5, 7, 11, ... là các số nguyên tố, trong đó số 2 là số nguyên tố chẵn duy nhất. Cũng như tính chất của số nguyên dương, chúng ta chỉ tìm thấy số nguyên tố nhỏ nhất chứ không thể tìm thấy số nguyên tố lớn nhất.
<br><br>
**Ví dụ**: 7 là số nguyên tố vì trong khoảng từ 2 - 6 không tồn tại số nào mà 7 chia hết cả.
<br> <br>
Từ một số nguyên N bất kỳ, hãy viết chương trình Python để kiểm tra xem chúng có phải số nguyên tố hay không. Nếu là số nguyên thì xuất ra màn hình là **TRUE** còn ngược lại là **FALSE**.

| Input  | Output  |
|--------|---------|
| 73     | TRUE    |
| 142    | FALSE   |

**Câu 6**. Các môn trên Đại học thường được tổ chức theo hình thức tín chỉ học phần. Các môn thường được chia ra các cột điểm với quy ước trọng số % khác nhau. Để qua môn, bạn cần điểm tổng kết của môn học lớn hơn hoặc bằng 5,0.<br>
Vì tuổi thanh xuân bận "cày game đua top" nên bạn giờ đây phải học hệ Liên kết của Trường Đại học X.<br> 
Vì điều kiện gia đình chỉ đủ trang trải việc học nên bạn đặt mục tiêu không rớt môn. Mà trong cuộc sống, đôi khi mọi thứ không như ta mường tượng. <br>
Bạn học Đại học với một ông thầy khó tính chuyên ra đề cuối kỳ đánh rớt sinh viên. Cuối kỳ thường chiếm trọng số cao, bạn sẽ phải tính toán các thang điểm từ những cột điểm khác (đã có điểm rồi) để nhắm chừng mình cần bao nhiêu điểm cho bài thi cuối kỳ để qua môn.

**Input**
- Nhập lần lượt a, b, c, d tương ứng tỷ lệ % tương ứng các cột điểm Quá trình, Thực hành, Giữa kỳ và Cuối kỳ.
- Nhập tiếp tục i, j, k tương ứng với số điểm của các cột Quá trình, Thực hành và Giữa kỳ.

**Output**
- Xuất ra số điểm tối thiểu bạn cần ở bài thi cuối kỳ để qua môn. Nếu không có số điểm tối thiểu nào phù hợp thì xuất ra 0. 

**Lưu ý**: 
  - Output cần được làm tròn tới vị trí thập phân thứ 2.
  - Điểm số ở trường không làm tròn, tính theo mốc 0,25. Ví dụ: 9,75.
  
| Input                       | Output |
|-----------------------------|--------|
| 20 30 0 50<br>1 7.75 0      | 0      |
| 15 15 10 60 <br>0 9.75 2.75 | 5.5    |

**Câu 7**. Viết chương trình nhập n và tính ```S(n) = 1 + 2 + 3 + … + n```


