# GitHub Issues

## 1. GitHub Issues là gì?

**GitHub Issues** là một cách tuyệt vời để theo dõi các nhiệm vụ, cải tiến, và lỗi cho các dự án của bạn. Các issues có thể được chia sẻ và thảo luận với các thành viên trong nhóm của bạn. Hầu hết các dự án phần mềm đều có một trình theo dõi lỗi nào đó. Trình theo dõi của **GitHub** được gọi là **Issues**, và nó có mặt trong các **repository** (kho lưu trữ).

## 2. Milestones, Labels, and Assignees

Đây là những tính năng tuyệt vời để lọc và phân loại các vấn đề trong dự án của bạn. Bạn có thể thay đổi hoặc thêm mới chúng trong cài đặt tương ứng ở cột bên phải.
### a. Milestones
**Milestones** là các vấn đề tương ứng với trong một dự án, một tính năng hay trong một khoảng thời gian bạn muốn.
ví dụ, 

* **Beta Launch** - Lỗi tập tin mà bạn cần phải sửa chữa trước khi bạn có thể khởi chạy phiên bản beta của dự án.

* **October Sprint** - Các vấn đề về tệp mà bạn muốn làm việc vào tháng 10. Nó giúp bạn tập trung nỗ lực của bạn khi có rất nhiều việc phải làm.
 
* **Redesign** - Giải quyết các vấn đề liên quan đến các thiết kế bạn muốn thay đổi dự án của bạn. Một cách tuyệt vời để thu thập ý tưởng từ các thành viên trong nhóm.

### b. Labels

Labels là một cách tuyệt vời để phân loại các loại vấn đề khác nhau. 
Các sự cố có thể có nhiều nhãn như bạn muốn và bạn có thể lọc bằng một hoặc nhiều nhãn cùng một lúc.

[![KdJCJ.png](https://guides.github.com/features/issues/labels-listing.png)](https://guides.github.com/features/issues/labels-listing.png)

### c. Assignees
Mỗi vấn đề có thể có một người quản lý và được chọn theo từng milestones, thông qua thanh cài đặt ở đầu vấn đề.

## 3. Notifications, @mentions, and References

Bằng cách sử dụng **@mentions** và **references** trong các vấn đề, bạn có thể thông báo cho các thành viên và các teams, và các vấn đề liên quan với nhau. Chúng giúp bạn tìm đúng người liên quan để giải quyết các vấn đề hiệu quả, và dễ học và sử dụng. 

###a. Notifications

Thông báo là cách để GitHub cập nhật các vấn đề của bạn.
Có hai cách để nhận thông báo: qua email và qua web. Bạn có thể định cấu hình cách bạn nhận thông báo trong phần cài đặt của mình.

[![KdJCJ.png](https://guides.github.com/features/issues/notifications.png)](https://guides.github.com/features/issues/notifications.png)

### b. @mentions
**@mentions** là cách đề cập đến thành viên trong GitHub Issues. Trong các nhận xét bạn có thể sử dụng **@username** của các thành viên khác để gửi thông báo cho họ. 
Sử dụng cú pháp /cc (viết tắt của carbon copy) để thông báo đến những thành viên bạn muốn đề cập trong các vấn đề.

vd:
```
/cc @phonguyen @thienguyen
```

Bạn cũng có thể gửi thông báo đến mọi thành viên trong team bằng cách sử dụng cú pháp:

vd:
```
/cc @acmeinc/browser-bugs
```
### c. References

**References** giúp bạn kết nối sâu vào công việc đang thực hiện với lỗi đang được theo dõi và là một cách tuyệt vời để xem lịch sử của dự án. Bạn có thể tham khảo các vấn đề bằng cách nhập một thẻ bắt đầu bằng **#** cùng với issue number.

 vd:
``` 
Hey @kneath, I think the problem started in #42
```

Khi đó sẽ có một sự kiện được tạo trong vấn đề số 42 như sau:

[![KdJCJ.png](https://guides.github.com/features/issues/reference.png)](https://guides.github.com/features/issues/reference.png)

## 4. Search
Ở đầu mỗi trang sẽ có nút tìm kiếm cho phép bạn tìm kiếm thông qua các vấn đề.
Bạn có thể giới hạn kết quả tìm kiếm bằng cách sử dụng : Keyword, State, Assignee.

[![KdJCJ.png](https://guides.github.com/features/issues/search.png)](https://guides.github.com/features/issues/search.png)

## 5. Overviews & Reports
Bên ngoài phần Issues, có hai trang khác giúp tóm tắt những gì đang xảy ra với các vấn đề trên kho của bạn và trên tất cả các kho của bạn.

### a. The Issue Dashboard (Bảng điều khiển)

Nếu bạn đang tìm kiếm một danh sách hoặc tất cả các vấn đề của mình trong nhiều dự án, Bẩng điều khiển thu sẽ giúp bạn làm điều đó:
Bạn có thể thu thập các vấn đề khác nhau trong: 

* Các Issues được giao cho bạn 
* Các Issues mà bạn đã tạo

### b. Pulse

Bên dưới mỗi repository có một phần gọi là Pulse - Pulse. Nó là một ảnh chụp nhanh mọi thứ đã xảy ra trong kho trong tuần vừa qua (hoặc ngày, v.v ...)

[![KdJCJ.png](https://guides.github.com/features/issues/pulse.png)](https://guides.github.com/features/issues/pulse.png)

Xem thêm tại:  [đây](https://guides.github.com/features/issues/#filtering)


