# Xây dựng Game cơ bản cùng Python


> Tuỳ vào từng mức độ, bạn có thể thử sức xây dựng một số Game cơ bản từ Python qua các kiến thức đã học. Bạn có thể tuỳ chỉnh thêm qua áp dụng một số kiến thức khác để khiến game của mình thêm hấp dẫn.

## 1. Trò chơi đổ xí ngầu

![](https://www.stagelightingstore.com/76729-large_default/apollo-2-color-glass-gobo-1196-roll-the-dice.jpg)

Xây dựng chương trình mỗi khi bắt đầu sẽ hiển thị thông báo **Rolling Dice Game. Play or not (Yes/No)?**. Khi nhập vào màn hình **Yes** sẽ bắt đầu trò chơi và xuất ra trên màn hình kết quả từ 1 -> 6.  Nếu muốn kết thúc trò chơi, ta có thể nhập **No**.

**Gợi ý**:
- Bạn có thể tham khảo hàm ```random()``` để xây dựng trò chơi.

## 2. Trò chơi đoán số - Guessing game

![](https://jsbeginners.com/wp-content/uploads/2019/10/JavaScript-Number-Guessing-Game.png)

Xây dựng chương trình mỗi khi bắt đầu sẽ hiển thị thông báo **Guessing Game - Finding secret number. Let's type to find**. Người dùng sẽ có 5 lần nhập để đoán ra con số bí ẩn.

**Gợi ý**:
- Theo yêu cầu cho số lần đoán có thể là 5, nếu bạn set con số bí ẩn từ giá trị hàng trăm trở lên thì nên tăng số lần dự đoán.
- Nếu con số người dùng dự đoán thấp hơn con số bí ẩn thì xuất **Secret number is higher than this number, let's try again!**.
- Nếu con số người dùng dự đoán cao hơn con số bí ẩn thì xuất **Secret number is lower than this number, let's try again!**.
- Khi hết số lần dự đoán, màn hình sẽ xuất **Secret number is ... ! Do you want to try again? (Y/N)**. Nếu người dùng nhập **Yes** sẽ bắt đầu lại trò chơi, còn nếu nhập **No** sẽ kết thúc chương trình.
- Trường hợp người dùng dự đoán đúng con số bí ẩn, màn hình sẽ xuất **Congratulations!**.
- Bạn có thể tham khảo hàm ```random()``` để xây dựng trò chơi.

## 3. Trò chơi Dice Poker 

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQFpIRCyGk11qpRYhYkxaXmj-EldKme27cZMPc99ZrRAxSp3JL_WQ&s)

Tham khảo luật chơi tại [đây](https://en.wikipedia.org/wiki/Poker_dice)

Bạn có thể viết chương trình để mỗi khi bắt đầu sẽ hiển thị thông báo **Playing Poker Dice. Let's play? (Y/N)**. Nếu người dùng nhập **Yes** sẽ bắt đầu lại trò chơi, còn nếu nhập **No** sẽ kết thúc chương trình.

Để bắt đầu cơ bản thì trò chơi sẽ dành cho 2 người chơi. Khi bắt đầu chương trình sẽ trả về kết quả của 5 xí ngầu và hệ số Dice Poker từ mỗi người chơi. Sau đó sẽ so sánh kết quả giữa hai người chơi và xuất ra màn hình ai chiến thắng.

**Gợi ý**:
- Bạn có thể để người dùng lần lượt nhập tên trước khi bắt đầu trò chơi (Trong thực tế điều này sẽ tăng độ trải nghiệm của người dùng).
- Bạn có thể tham khảo hàm ```random()``` để xây dựng trò chơi.
