
[Source](https://www.codeproject.com/Tips/808058/Reasons-for-using-design-patterns "Permalink to Reasons for using design patterns")

# Những lý do để sử dụng Design Pattern

## Introduction Giới thiệu

Sau những bài báo về vấn đề [ Tại sao thiết kế rất quan trọng trong phát triển phần mềm][1], Tôi muốn tiếp cận một khía cạnh mới, nâng cao hơn trong việc thiết kế phần mềm gọi là: `Design Patterns`.Như những bài báo trước của tôi, ý tưởng trong suốt cuộc họp với một thành viên dự án là làm sao để thiết kế phần mềm một cách tốt nhất. Nhân vật chính của cuộc thảo luận cho rằng sử dụng `Design Patterns`
 quá mất thời gian trong việc phát triển hệ thống thương mại. Mục đích của tôi trong bài viết này để chứng minh tại sao tôi tin ý kiến trên là sai.

Tôi sẽ không đi chi tiết vào bất kì cấu trúc hay ví dụ nào của `Design Patterns`.Có nhiều nguồn tham khảo tốt hơn để tìm những ví dụ có sẵn.

##  Design Pattern là gì?

Để bắt đầu, ta tìm hiểu `Design Pattern` chính xác là cái gì? Ở đây là vài định nghĩa về thuật ngữ này:

Tham khảo thông tin từ [Wikipedia][2]:

> "A design pattern in architecture and computer science is a formal way of documenting a solution to a design problem in a particular field of expertise."

*" Một `design pattern` trong kiến trúc và khoa học máy tính là một phương pháp tiêu chuẩn ghi chép để giải quyết vấn đề về thiết kế trong bất kì lĩnh vực chuyên môn nào."*

Tham khảo từ [Data & Object Factory][3]:

> "Design patterns are recurring solutions to software design problems you find again and again in real-world application development. Patterns are about design and interaction of objects, as well as providing a communication platform concerning elegant, reusable solutions to commonly encountered programming challenges. "

 *"Design patterns là các giải pháp định kì cho các vấn đề thiết kế phần mềm mà bạn liên tục phải tìm kiếm trong khi phát triển phần mềm trong thực tế. Patterns là các thiết kế và tương tác với các đối tượng, giống như là cung cấp 1 phương thức truyền thông 1 cách lịch sự, giải quyết được thách thức trong vấn đề lập trình là các giải pháp tái sử dụng. "*

Vì vậy một `Design Pattern` là đích đến cuối cùng để giải quyết các vấn đề,và có thể giải quyết được bất kì một vấn đề cụ thể nào. Khi các nhà phát triển phần mềm có xu hướng giải quyết các vấn đề tương tự, nó làm cho mọi vấn đề trong phần mềm có thể giải quyết được khi kết hợp các giải pháp khác nhau. Tại sao lại phải cố phát minh lại bánh xe?

## Tài liệu dễ hiểu

 `Design Patterns` được viết tài liệu rất dễ hiểu bởi các kĩ sư, các thiết kế, các nhà phát triển phần mềm, sau đó sản phẩm của họ được sử dụng trong các giải pháp cụ thể sẽ dễ hiểu hơn.

`Design Patterns` cung cấp cho các nhà phát triển phần mềm một loạt các giải pháp đã được thử nghiệm cho các vấn đề cơ bản, do đó, ta giảm được các nguy cơ cho dự án bằng việc không phải sử dụng một bản thiết kế mới và chưa được kiểm tra.

`Design Patterns` ban đầu có thể tốn nhiều thời gian phát triển, vì nếu đội của bạn chưa làm quen với nó thì phải đi lòng vòng. Tuy nhiên, khi nhìn vào quá trình phát triển, các thói quen sử dụng chúng tăng lên, thời gian để phát triển phần mềm sẽ giảm đi.

## So sánh với kĩ thuật dân dụng

Lấy một vài ví dụ tương tự `Design Pattern` trong kĩ thuật dân dụng (như tôi đã đề cập trong bài viết [Tại sao việc thiết kế rất quan trọng trong phát triển phần mềm][1]) có nhiều điểm tương đồng với nhau),như việc tìm kiếm một giải pháp để vượt qua một con sông. Đây là một vấn đề thường xuyên của một kĩ sư dân dụng, mà có một vài giải pháp được chứng minh và làm rõ. Các kĩ sư dân dụng có thể xây dựng 1 cây cầu hoặc một đường hầm.

 Tại sao các kĩ sư dân dụng lại cố gắng giải quyết vấn đề này từ đầu trong khi trong thực tế các giải pháp đều đã được nhắc tới? Có một sự tương đồng khi kĩ sư dân dụng cố gắng giải quyết vấn đề về dòng sông và kĩ sư phần mềm cố gắng giải quyết vấn đề của phần mềm:

* Các giải pháp (cầy hoặc đường hầm) đều có tài liệu và dễ hiểu
* Các giải pháp (cầy hoặc đường hầm) đều thường dùng để giải quyết các vấn đề của kĩ sư dân dụng
* Các giải pháp (cầy hoặc đường hầm) không cần phải xác định hay quy định nhưng nó khá trừu tượng và có thể điều chỉnh với các vấn đề cụ thể bằng tay ( các ví dụ như cầu hay đường hầm có thể được lựa chọn để thể hiện cho sự liên kết trong các vấn đề cụ thể của họ)

Các lập luận chống lại  `Design Patterns` như chúng không phù hợp cho mục đích thương mại do chúng mất quá nhiều thời gian để triển khai, nó không thể kéo dài. Thật ra `Design Patterns` tiết kiệm thời gian hơn (khi nhìn vào tổng quan quá trình phát triển ứng dụng) khi cho nhà phát triển tự chọn và thử nghiệm các giải pháp có sẵn sao cho họ có thể thích ứng với nhu cầu cụ thể của họ.
Vấn đề duy nhất tôi gặp phải từ `Design Patterns` là họ cần thời gian để học hỏi. Một số người trong số họ có thể khó nắm bắt và hiểu được chúng. Đây thật sự là một lý do thích hợp, do đó nó đòi hỏi cần có kĩ năng tốt hơn để có thể sử dụng chúng. Điều này có thể khiến chi phí dự án ban đầu tăng lên. Tuy nhiên, khi xem qua toàn bộ thời gian phát triển ứng dụng, tôi rất hi vọng các chi phí phát triển ban đầu có thể được bù lại do chi phí bảo trì thấp hơn, sự hiểu biết cao hơn và khả năng mở rộng dễ dàng hơn (làm cho ứng dụng mở rộng dễ dàng hơn, đáp ứng các cơ hội mới và phát triển cao hơn trong tương lai).

`Design Patterns` giảm bớt sự phức tạp, và giúp các giải pháp trở nên dễ hiểu hơn.

`Design Patterns` là các giải pháp đã được kiểm tra và thử nghiệm, các nhà phát triển không phải bắt đầu từ đầu, và có thể chạy ngay với một giải pháp đã được chứng minh nó có thể hoạt động (miễn là `Design Pattern` đang được sử dụng có thể giải quyết vấn đề tương tự). It would be wrong to expect a bridge to solve the problem of crossing an ocean, where a bridge would simply be unsuitable. Nó sẽ sai khi mong đợi một cái cầu băng qua đại dương, khi mà đơn giản là 1 cây cầu sẽ không phù hợp.

## Những lợi ích khi sử dụng các Design Pattern

`Design Patterns` cung cấp các ưu điểm sau:

* Cung cấp cho các nhà phát triển một loạt các giải pháp đã được kiểm tra và thử nghiệm để làm việc với chúng.
* Chúng là ngôn ngữ trung lập ( trung gian ) và vì thế có thể áp dụng vào bất cứ ngôn ngữ nào có hỗ trợ hướng đối tượng.
* Chúng được hỗ trợ bởi truyền thông bởi vì thực tế chúng đã được công nhận và có thể được nghiên cứu nếu nó không chỉ là một trường hợp cụ thể.
* Chúng một bản theo dõi chứng minh chúng được sử dụng rộng rãi và giảm các lỗi kĩ thuật cho các dự án.
* Chúng rất linh hoạt và có thể sử dụng trong bất kì ứng dụng hay tên miền nào.

## Kết luận

`Design Patterns`là một khoản đầu tư rất đáng, mặc dù đường cong học tập ban đầu khó khăn. Chúng cho phép bạn thực hiện các giải pháp cho các vấn đề đã được thử nghiệm và kiểm tra do đó tiết kiệm được thời gian và sức lực trong suốt quá trình triển khai và phát triển phần mềm. bằng các sử dụng các giải pháp đã được làm rõ và có tài liệu rõ ràng, sản phẩm cuối cùng sẽ có mức độ hoàn thiện cao hơn nhiều. Nếu giải pháp dễ hiểu hơn, sau đó bằng cách mở rộng nó, nó sẽ được bảo trì dễ dàng hơn.

[1]: http://www.codeproject.com/Tips/806867/Why-Design-is-Critical-to-Software-Development
[2]: http://en.wikipedia.org/wiki/Design_pattern
[3]: http://www.dofactory.com/Patterns/Patterns.aspx