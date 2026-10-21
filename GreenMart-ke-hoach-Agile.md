# Kế hoạch vận hành Agile cho GreenMart

## 1. Lý do chọn Agile

Waterfall chốt yêu cầu từ đầu và để khách xem sản phẩm muộn. Khi nhu cầu bán hàng đa kênh thay đổi, đội có thể phải sửa lại nhiều phần. Agile chia công việc thành các phần nhỏ, trình diễn thường xuyên và nhận phản hồi để điều chỉnh. Vì yêu cầu của GreenMart có thể thay đổi, cách làm này phù hợp hơn cho sáu tuần đầu.

## 2. Bốn giá trị Agile

| Thói quen hiện tại | Giá trị cần chú ý | Cách làm mới |
|---|---|---|
| Chỉ bình luận trên phần mềm | Cá nhân và sự tương tác | Họp ngắn hằng ngày, trao đổi trực tiếp khi có vướng mắc; vẫn ghi lại quyết định cần thiết. |
| Viết tài liệu rất chi tiết rồi trình diễn cuối dự án | Phần mềm chạy được | Chia nhỏ tính năng và trình diễn bản chạy được sau mỗi Sprint; tài liệu giữ ở mức cần dùng. |
| Mỗi thay đổi phải chờ phê duyệt hai tuần | Hợp tác với khách hàng | Product Owner trao đổi thường xuyên với GreenMart, làm rõ và sắp xếp yêu cầu cùng khách. |
| Luôn giữ kế hoạch ban đầu dù thực tế đổi | Phản hồi với thay đổi | Xem lại backlog sau phản hồi, cập nhật thứ tự ưu tiên và kế hoạch Sprint tiếp theo. |

## 3. Khung Scrum

Chọn Sprint cố định hai tuần, tương ứng ba Sprint trong sáu tuần. Bảng công việc và mục tiêu Sprint giúp mọi người thấy tiến độ (minh bạch); Daily Scrum và Sprint Review giúp kiểm tra tiến độ và sản phẩm (thanh tra); nhóm điều chỉnh kế hoạch và cách làm qua phản hồi và Retrospective (thích nghi). Scrum giúp khách xem sản phẩm sớm và đội cập nhật ưu tiên thường xuyên.

## 4. Phân vai

Giả định Long là Product Owner, Hoa là Scrum Master; An, Bình, Chi và Dung là Developers.

| Vai trò | Có thể quyết định | Không tự quyết định |
|---|---|---|
| Long — Product Owner | Sắp xếp Product Backlog và làm rõ giá trị sản phẩm với khách. | Cách kỹ thuật chi tiết hoặc ép đội nhận khối lượng vượt khả năng. |
| Hoa — Scrum Master | Hỗ trợ đội hiểu Scrum, giúp tháo gỡ trở ngại và cải thiện cách phối hợp. | Thay Product Owner quyết định ưu tiên sản phẩm hoặc giao việc như quản lý cá nhân. |
| An, Bình, Chi, Dung — Developers | Cùng lập kế hoạch công việc, chọn cách triển khai và bảo đảm chất lượng Increment. | Đơn phương đổi mục tiêu Sprint hoặc thứ tự Product Backlog thay Product Owner. |

## 5. Product Backlog và Sprint đầu

Thứ tự sau là đề xuất ban đầu, có thể điều chỉnh sau khi trao đổi với GreenMart:

1. Xem danh sách sản phẩm và giá bán.
2. Tìm sản phẩm theo tên.
3. Xem thông tin và tình trạng còn hàng.
4. Thêm sản phẩm vào giỏ hàng.
5. Đặt hàng online với thông tin giao hàng.
6. Thanh toán khi nhận hàng.
7. Theo dõi trạng thái đơn hàng.
8. Thanh toán trực tuyến.

**Mục tiêu Sprint 1:** Khách có thể xem và tìm sản phẩm để chọn mặt hàng phù hợp. Sprint Backlog gồm các hạng mục 1–3, cùng các công việc thiết kế màn hình, lập trình, kiểm thử và sửa lỗi do nhóm phân chia. Đây là phạm vi dự kiến, đội cần xác nhận sức chứa khi lập kế hoạch.

**Increment dự kiến:** Một phiên bản chạy được cho phép xem danh sách, tìm theo tên và xem chi tiết sản phẩm; các chức năng đã kiểm thử và đáp ứng tiêu chuẩn hoàn thành chung của nhóm.

## 6. Lịch sự kiện trong một Sprint hai tuần

| Sự kiện | Thời điểm | Mục đích |
|---|---|---|
| Sprint | Hai tuần liên tục | Tạo Increment hướng tới mục tiêu. |
| Sprint Planning | Đầu ngày đầu tiên | Thống nhất mục tiêu, chọn công việc và lập kế hoạch. |
| Daily Scrum | Mỗi ngày làm việc, tối đa 15 phút | Developers xem tiến độ tới mục tiêu và điều chỉnh kế hoạch trong ngày. |
| Sprint Review | Gần cuối ngày làm việc cuối | Xem Increment với khách và nhận phản hồi cho backlog. |
| Sprint Retrospective | Sau Review, trước Sprint tiếp theo | Xem lại cách làm và chọn cải tiến thực hiện trong Sprint tới. |

## 7. Xử lý thay đổi

- **Khách muốn ưu tiên đặt hàng online giữa Sprint:** Long ghi nhận và làm rõ yêu cầu, trao đổi với khách và đội, cập nhật thứ tự Product Backlog. Nhóm giữ mục tiêu Sprint hiện tại và xem xét đưa yêu cầu vào Sprint Planning tiếp theo; nếu thay đổi ảnh hưởng mục tiêu thì cả đội cần trao đổi rõ trước khi điều chỉnh.
- **Một tính năng chưa hoàn thành tại Review:** Đội nói rõ tình trạng, không giới thiệu là đã xong và không tính vào Increment hoàn thành. Hạng mục quay lại Product Backlog để Product Owner xem xét thứ tự; đội chỉ trình diễn phần đã đạt tiêu chuẩn hoàn thành và thu nhận phản hồi phù hợp.
