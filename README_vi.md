## GameMaker không còn an toàn cho các dự án thương mại (ở thời điểm hiện tại)
Tại sao tôi lại nói như vậy?
1. **Giá để truy cập source code là rất cao:**
   - 799,99 USD/năm hoặc 79,99 USD/tháng
   - Quyền truy cập bị *giới hạn, có thể bị thu hồi mà không cần lí do rõ ràng, không thể cấp quyền lại cho người khác, không thể chuyển nhượng kể cả khi đã rời team* (được trích từ Điều 2 của License Agreement của GameMaker Source Code)
2. **Không thực sự "sở hữu" runtime:**
   - Không thể sử dụng, phân phối, fork, hoặc nhúng runtime theo bất kỳ cách nào nằm ngoài mục đích debug tạm thời
   - Không được tái phân phối hoặc xây dựng tool riêng từ runtime
3. **Không thể fork hoặc dùng nhiều project với nó**
   - Giấy phép bị giới hạn ở cấp độ từng product
   - Ta không thể dùng code đã chỉnh sửa cho nhiều project
   - Trích từ Điều 2 của License Agreement của GameMaker Source Code.
4. **Không tương thích với giấy phép GPL/LGPL hoặc đa số thư viện open source**
   - GPL/LGPL bị **cấm hoàn toàn**
   - Chỉ có dynamic linking mới được phép và ngay cả vậy cũng khá rủi ro
   - Trích từ Điều 3 của License Agreement của GameMaker Source Code.
5. **Không CI/CD hay build tự động được hỗ trợ:**
   - Bất kỳ hệ thống build tự động hoặc CI/CD đều có nguy cơ vi phạm license
   - Điều này khiến GameMaker không thể tích hợp vào quy trình làm game chuyên nghiệp

---

### Tổng kết
> **Bạn trả tiền như thể bạn sở hữu nó – nhưng bạn không được dùng nó như thể bạn sở hữu nó.**

GameMaker hiện nay được thiết kế dựa trên sự kiểm soát và giới hạn – không phải trên sự hợp tác hay khả năng mở rộng.

Nếu bạn đang làm prototype, GameMaker có thể phù hợp.  
Nhưng nếu bạn nghiêm túc với việc phát hành và kinh doanh game, đây **không phải là công cụ bạn có thể tin tưởng về lâu dài.**

---

### Thay thế

1. Godot Engine (giấy phép MIT)
2. Unreal Engine (nửa mở nhưng có mô hình thương mại hợp lí)
3. Engine tùy chỉnh làm bằng SDL/SFML với giấy phép mở
