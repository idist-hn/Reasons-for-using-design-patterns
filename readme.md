
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

`Design Patterns` ban đầu có thể tốn nhiều thời gian phát triển, vì nếu đội của bạn chưa làm quen với nó thì phải đi lòng vòng. Tuy nhiên, looking further down the development pipeline, once familiarity with them increases, development timescales should gradually reduce.

## So sánh với kĩ thuật dân dụng

To give an analogy of a `Design Pattern` from the field of civil engineering (which as I stated in my article [Why design is Critical to Software Development][1]) has close similarities to software engineering), would be to think of a solution for crossing a river. This is a recurring problem for civil engineers, to which there are a couple of well documented and understood solutions. The civil engineers may build a bridge or a tunnel.

Why would a civil engineer try to solve this problem from scratch when there are real world solutions that can be referred to? There are close parallels between the civil engineer solving the river problem, and the software engineer solving a software problem:

* The solutions (bridge or tunnel) are both well understood and documented
* The solutions (bridge or tunnel) solve recurring civil engineering problems
* The solutions (bridge or tunnel) are not deterministic or prescriptive, but are abstract and can be tailored to the specific problem to hand (the bridge or tunnel building materials for example can be selected for their alignment to the specific problem)

The argument against `Design Patterns` that they are not suitable for commercial use due to their taking too long to implement does not hold up. `Design Patterns` save time (when viewed over the lifetime of the application) by giving the developer a selection of tried and tested off-the-shelf solutions which they can tailor to their own specific needs.

The only issue I have come across with `Design Patterns` is that they take time to learn. Some of them can be difficult to grasp and comprehend. This is a reasonable criticism, as it therefore requires a more skilled developer to use them. This then may increase the project costs initially. However, when viewed over the lifetime of an application I would fully expect those initial development costs to be recouped due to the lower ongoing maintenance costs due to the higher comprehension and easier extensibility (making the application easier to extend in the future to meet new and emergent opportunities).

`Design Patterns` reduce complexity, and therefore the solution becomes easier to comprehend.

`Design Patterns` are tried and tested solutions, the developer does not need to start from scratch, and can hit the ground running with a solution that has been proven to work (as long as the `Design Pattern` being used solves a similar problem). It would be wrong to expect a bridge to solve the problem of crossing an ocean, where a bridge would simply be unsuitable.

## Những lợi ích khi sử dụng các Design Pattern

`Design Patterns` therefore provide the following benefits.

* They give the developer a selection of tried and tested solutions to work with
* They are language neutral and so can be applied to any language that supports object-orientation
* They aid communication by the very fact that they are well documented and can be researched if that is not the case.
* They have a proven track record as they are already widely used and thus reduce the technical risk to the project
* They are highly flexible and can be used in practically any type of application or domain

## Kết luận

`Design Patterns`, despite their initial learning curve, are a very worthwhile investment. They will enable you to implement tried and tested solutions to problems, thus saving time and effort during the implementation stage of the software development lifecycle. By using well understood and documented solutions, the final product will have a much higher degree of comprehension. If the solution is easier to comprehend, then by extension, it will also be easier to maintain.

[1]: http://www.codeproject.com/Tips/806867/Why-Design-is-Critical-to-Software-Development
[2]: http://en.wikipedia.org/wiki/Design_pattern
[3]: http://www.dofactory.com/Patterns/Patterns.aspx