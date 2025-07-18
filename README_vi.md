## GameMaker không còn an toàn cho các dự án thương mại (ở thời điểm hiện tại)

### Tại sao tôi lại nói như vậy?

1. **Giá truy cập mã nguồn quá cao:**
   - 799,99 USD/năm hoặc 79,99 USD/tháng
   - Quyền truy cập bị *giới hạn, có thể bị thu hồi bất cứ lúc nào, không thể cấp lại quyền cho người khác, và không được chuyển nhượng*  
   → 📌 Trích từ **Điều 2** của *GameMaker Source Code License Agreement*

2. **Bạn không thực sự “sở hữu” runtime:**
   - Không được sử dụng, phân phối, fork hoặc nhúng runtime ra ngoài mục đích debug tạm thời
   - Không được xây dựng tool riêng hay tái sử dụng runtime theo bất kỳ cách nào

3. **Không hỗ trợ fork hoặc tái sử dụng cho nhiều dự án:**
   - License chỉ áp dụng cho một *sản phẩm cụ thể*
   - Không được dùng mã đã chỉnh sửa cho nhiều project khác nhau  
   → 📌 Trích từ **Điều 2** của License

4. **Không tương thích với thư viện mã nguồn mở phổ biến (GPL/LGPL):**
   - GPL và LGPL bị **cấm rõ ràng**
   - Chỉ dynamic linking mới được chấp nhận, nhưng cũng mang rủi ro pháp lý cao  
   → 📌 Trích từ **Điều 3** của License

5. **Không hỗ trợ CI/CD hoặc build tự động:**
   - Mọi hình thức automation build hoặc phân phối runtime đều có nguy cơ vi phạm license
   - Điều này khiến GameMaker không thể tích hợp vào quy trình làm game hiện đại trong studio chuyên nghiệp

---

### ❌ Tổng kết

> **Bạn trả tiền như thể bạn sở hữu nó – nhưng bạn không được dùng nó như thể bạn sở hữu nó.**

GameMaker hiện tại được thiết kế xoay quanh kiểm soát và hạn chế — **không phải hợp tác và mở rộng**.

Nếu bạn chỉ cần một engine để làm prototype nhỏ, GameMaker có thể phù hợp.  
Nhưng nếu bạn nghiêm túc với việc **phát triển và phát hành game thương mại**, đây **không phải là nền tảng đáng tin cậy về lâu dài.**

---

### 🔁 Các lựa chọn thay thế

1. **Godot Engine** (giấy phép MIT – mở hoàn toàn)
2. **Unreal Engine** (bán mở – nhưng có mô hình thương mại minh bạch, linh hoạt)
3. **Tự phát triển engine riêng** sử dụng **SDL**, **SFML**, hoặc **Vulkan/OpenGL** với giấy phép mở

---

### 📄 Nguồn tham khảo

- **GameMaker Source Code License Agreement** (có thể thay đổi bất cứ lúc nào):  
  🔗 [https://gamemaker.io/en/legal/sourcecode](https://gamemaker.io/en/legal/sourcecode)<br>
  🔗 [https://gamemaker.io/en/get](https://gamemaker.io/en/get)
