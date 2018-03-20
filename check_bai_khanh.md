[Nguồn](https://www.codeproject.com/Tips/808058/Reasons-for-using-design-patterns "Permalink to Reasons for using design patterns")

# Lý do sử dụng design patterns

## Introduction

Sau bài báo có tựa đề [Tại sao thiết kế lại quan trọng để phát triển phần mềm][1], tôi muốn giải quyết một khía cạnh nâng cao hơn một chút về thiết kế phần mềm được gọi là `Design Patterns`. Như bài báo trước của tôi, ý tưởng đến trong một cuộc thảo luận liên quan đến sự thành công của thiết kế phần mềm với một đồng nghiệp. Nội dung chính của cuộc thảo luận là `Design Patterns` quá tốn thời gian để sử dụng trong lĩnh vực phát triển phần mềm thương mại. Mục đích của tôi ở đây là để chứng minh tại sao tôi tin rằng đó là sai.

Tôi sẽ không đi vào bất kỳ chi tiết hoặc thực hiện bất kỳ cụ thể  về `Design Patterns`. Có rất nhiều nguồn tốt về chúng ở khắp nơi.

## Design Pattern là gì?

Vậy chúng ta sẽ ắt đầu ngay sau đây, `Design Pattern` chính xác là gì? Dưới đây là một vài định nghĩa cho thuật ngữ này:

Trích từ [Wikipedia][2]:

> "Một Design pattern trong kiến trúc và khoa học máy tính là một cách chính thức để ghi lại một giải pháp cho một vấn đề thiết kế trong một lĩnh vực chuyên môn cụ thể."

Trích từ [Data & Object Factory][3]:

> "Design patterns là giải phpas định kì các vấn đề thiết kế phần mềm mà bạn tìm thấy trong phát triển ứng dụng thực tế. Các mẫu về thiết kế và tương tác của các đối tượng, cũng như là cung cấp một nền tảng giap tiếp, các giải pháp tái sử dụng đối với các thách thức lập trình thông thường gặp phải. "

Vậy nên một `Design Pattern` là một mục đích chung trừu tượng của một vấn đề, nó có thể áp dụng cho một giải pháp cụ thể. Khi các nhà phát triển phần mềm có xu hướng giải quyết nhiều loại vấn đề tương tự, nó có ý nghĩa rằng bất kỳ giải pháp phần mềm sẽ kết hợp các yếu tố tương tự từ các giải pháp khác. Tại sao phải phát minh lại bánh xe?

## Tài liệu và sự tìm hiểu

`Design Patterns` là tài liệu và sự tìm hiểu rõ bởi các kiến trúc sư phần mềm, nhà thiết kế và nhà phát triển, thì ứng dụng của họ trong một giải pháp cụ thể cũng sẽ được hiểu rõ.

`Design Patterns` cung cấp cho một nhà phát triển phần mềm một loạt các giải pháp đã được thử nghiệm cho các vấn đề phổ biến, do đó giảm nguy cơ cho dự án bằng cách không phải sử dụng một thiết kế mới và chưa được kiểm tra.

`Design Patterns` ban đầu có thể không làm giảm thời gian phát triển, vì có nhiều khó khăn nếu đội không quen với chúng. Tuy nhiên, nhìn sâu hơn về hướng phát triển, một khi đã quen thuộc với chúng, thời gian phát triển sẽ giảm dần.

## Điểm tương đồng với kỹ thuật xây dựng

Để đưa ra một sự tương tự `Design Pattern` từ lĩnh vực kỹ thuật dân dụng (như tôi đã nêu trong bài báo của tôi [Tại sao thiết kế lại quan trọng để phát triển phần mềm][1]) có những điểm tương đồng gần giống với công nghệ phần mềm), sẽ là một giải pháp để vượt qua một con sông. Đây là vấn đề thường xuyên đối với các kỹ sư dân dụng, mà có một vài giải pháp được chứng minh và hiểu rõ. Các kỹ sư dân dụng có thể xây dựng một cầu hoặc đường hầm

Tại sao một kỹ sư dân dụng cố gắng giải quyết vấn đề này từ đầu khi có những giải pháp thế giới thực có thể được đề cập đến? Có sự tương đồng giữa kỹ sư xây dựng giải quyết vấn đề về sông và kỹ sư phần mềm giải quyết vấn đề phần mềm:

* Các giải pháp (cầu hoặc đường hầm) đều được hiểu và ghi lại
* Các giải pháp (cầu hoặc đường hầm) định kì giải quyết các vấn đề kỹ thuật xây dựng
* Các giải pháp (cầu hoặc đường hầm) không phải là xác định hoặc quy định, nhưng chúng là trừu tượng và có thể được điều chỉnh cho phù hợp với vấn đề cụ thể để (ví dụ như cầu hoặc các vật liệu xây dựng đường hầm có thể được lựa chọn để liên kết với các vấn đề cụ thể)

Lập luận chống lại `Design Patterns` rằng chúng không thích hợp cho mục đích thương mại do quá trình thực hiện lâu dài của chúng không duy trì được. `Design Patterns` tiết kiệm thời gian (khi nhìn vào còng đợi của ứng dụng) bằng cách cho nhà phát triển lựa chọn các giải pháp đã được thử nghiệm và thử nghiệm sẵn có mà họ có thể tùy chỉnh theo nhu cầu cụ thể của riêng họ.

Vấn đề duy nhất tôi đã gặp với `Design Patterns` là họ mất thời gian để học. Một số người trong số họ có thể khó nắm bắt và hiểu. Đó là một lý do chính đáng, vì nó đòi hỏi một nhà phát triển có tay nghề hơn để sử dụng chúng. Điều này sau đó có thể làm tăng chi phí dự án ban đầu. Tuy nhiên, khi xem qua vòng đời của một ứng dụng tôi hoàn toàn hy vọng những chi phí phát triển ban đầu sẽ được bù đắp do chi phí bảo trì liên tục thấp hơn do sự hiểu biết cao hơn và khả năng mở rộng dễ dàng hơn (làm cho ứng dụng dễ dàng hơn để mở rộng trong tương lai để đáp ứng các cơ hội mới và đang nổi lên).

`Design Patterns` giảm sự phức tạp, và do đó giải pháp trở nên dễ hiểu hơn.

`Design Patterns` là các giải pháp được thử nghiệm và thử nghiệm, nhà phát triển không cần phải bắt đầu từ đầu, và có thể bắt đầu ngay với một giải pháp đã được chứng minh để làm việc (miễn là `Design Pattern` được sử dụng để giải quyết một vấn đề tương tự). Sẽ là sai khi mong đợi một cây cầu để giải quyết vấn đề băng qua đại dương, nơi một cây cầu chỉ đơn giản là không phù hợp.

## Lợi ích của việc sử dụng Design Paterns

`Design Patterns` cung cấp các lợi ích sau đây.

* Họ cung cấp cho nhà phát triển một loạt các giải pháp thử và thử nghiệm để làm việc
* Chúng là ngôn ngữ trung gian và do đó có thể được áp dụng cho bất kỳ ngôn ngữ nào hỗ trợ hướng đối tượng
* Họ hỗ trợ truyền thông bởi thực tế là họ có tài liệu tốt và có thể được nghiên cứu nếu đó không phải là trường hợp.
* Họ đã có một hồ sơ theo dõi đã được chứng minh vì chúng đã được sử dụng rộng rãi và do đó làm giảm nguy cơ kỹ thuật cho dự án
* Chúng rất linh hoạt và có thể được sử dụng trong bất kỳ loại ứng dụng hoặc tên miền nào

## Kết luận

`Design Patterns`, mặc dù khó học tập ban đầu, nhưng là một đầu tư rất đáng giá. Họ sẽ cho phép bạn thực hiện các giải pháp được thử nghiệm cho các vấn đề, do đó tiết kiệm thời gian và nỗ lực trong giai đoạn triển khai của vòng đời phát triển phần mềm. Bằng cách sử dụng các giải pháp được hiểu rõ và có tài liệu, sản phẩm cuối cùng sẽ có độ hiểu biết cao hơn nhiều. Nếu giải pháp được dễ dàng hơn để hiểu, sau đó bằng cách mở rộng, nó cũng sẽ được dễ dàng hơn để duy trì.

[1]: http://www.codeproject.com/Tips/806867/Why-Design-is-Critical-to-Software-Development
[2]: http://en.wikipedia.org/wiki/Design_pattern
[3]: http://www.dofactory.com/Patterns/Patterns.aspx

## Thực hành
- https://coderoncode.com/design-patterns/programming/php/coding/development/2014/01/19/design-patterns-php-factories.html
- https://www.binpress.com/tutorial/the-factory-design-pattern-explained-by-example/142
- https://www.codeproject.com/Articles/852232/PHP-Singleton-Pattern-A-Step-by-Step-And-Problem-s
- http://www.fluffycat.com/PHP-Design-Patterns/

**Từ khoá:** `how to separate code to package php`, `step by step php design pattern singleton`(thay đổi singleton sang other để có thêm kết quả)
