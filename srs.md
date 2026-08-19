BƯỚC 1: XÁC ĐỊNH BUSINESS CONTEXT – NGỮ CẢNH NGHIỆP VỤ
1. Khách hàng muốn trả lời câu hỏi gì?
Công ty ABC muốn trả lời câu hỏi nghiệp vụ chính: Làm thế nào để xây dựng một nền tảng đặt xe có thể tự động hóa toàn bộ quy trình từ khi khách hàng yêu cầu xe, tìm và phân công tài xế, thực hiện chuyến đi, tính cước, thanh toán, thông báo đến đánh giá sau chuyến; đồng thời hệ thống có thể phục vụ số lượng lớn khách hàng và tài xế và dễ dàng mở rộng trong tương lai?
Làm thế nào để tự động tìm và phân công tài xế phù hợp thay vì thực hiện thủ công?
Làm thế nào để khách hàng theo dõi được trạng thái chuyến đi?
Làm thế nào để quản lý tập trung khách hàng, tài xế, phương tiện và chuyến đi?
Làm thế nào để tính cước và quản lý thanh toán hiệu quả?
Làm thế nào để gửi thông báo kịp thời cho khách hàng và tài xế?
Làm thế nào để nhân viên vận hành theo dõi, quản lý và xử lý sự cố?
Làm thế nào để hệ thống có thể mở rộng khi số lượng người dùng và nhu cầu tăng?
2. Vì sao cần xây dựng CAB System?
Hệ thống hiện tại của Công ty ABC còn nhiều hạn chế: việc phân công tài xế chủ yếu được thực hiện thủ công, khách hàng khó theo dõi trạng thái chuyến đi, thông tin thanh toán chưa được quản lý tập trung và bộ phận vận hành gặp khó khăn khi muốn mở rộng hệ thống.
Vấn đề hiện tại	Ảnh hưởng
Phân công tài xế chủ yếu thủ công	Tốn thời gian, khó xử lý khi số lượng chuyến tăng.
Khách hàng khó theo dõi chuyến	Trải nghiệm khách hàng chưa tốt.
Thanh toán chưa quản lý tập trung	Khó quản lý giao dịch và doanh thu.
Hệ thống khó mở rộng	Khó đáp ứng khi số khách hàng và tài xế tăng.
Khó bổ sung chức năng mới	Tăng chi phí và rủi ro ảnh hưởng các chức năng đang hoạt động.
3. Mục tiêu của hệ thống
Mục tiêu tổng quát là xây dựng một nền tảng CAB hoàn chỉnh, ổn định và có khả năng phát triển lâu dài, hỗ trợ xuyên suốt quy trình: Đặt xe → Tìm tài xế → Phân công → Thực hiện chuyến → Tính cước → Thanh toán → Thông báo → Đánh giá.
Tự động hóa việc tìm và phân công tài xế.
Cho phép khách hàng theo dõi trạng thái chuyến đi.
Quản lý tập trung khách hàng, tài xế, phương tiện và chuyến đi.
Hỗ trợ tính cước và nhiều phương thức thanh toán.
Tự động gửi thông báo về các sự kiện quan trọng.
Hỗ trợ nhân viên vận hành quản lý và giám sát hoạt động.
Cung cấp báo cáo, thống kê phục vụ quản lý.
Đảm bảo xác thực, bảo mật và phân quyền.
Cho phép các thành phần mở rộng độc lập khi tải tăng.
Dễ dàng bổ sung dịch vụ, phương thức thanh toán và kênh thông báo trong tương lai.
4. Ai là người sử dụng hệ thống?
Người sử dụng	Vai trò
Khách hàng (Customer)	Đăng ký, đăng nhập, cập nhật thông tin, đặt xe, chọn loại xe, theo dõi chuyến, xem lịch sử, thanh toán và đánh giá tài xế.
Tài xế (Driver)	Quản lý hồ sơ và phương tiện, cập nhật trạng thái hoạt động, nhận/từ chối chuyến và cập nhật trạng thái chuyến.
Nhân viên vận hành (Operation Staff)	Quản lý khách hàng, tài xế, phương tiện, chuyến đi; theo dõi hoạt động, xử lý sự cố, tra cứu giao dịch và thực hiện chức năng quản trị theo quyền.
Ngoài ba nhóm người dùng chính, CAB System còn tương tác với nhà cung cấp thanh toán bên ngoài để thực hiện thanh toán điện tử.
5. Giá trị của CAB System so với hệ thống cũ
Hệ thống cũ	CAB System mới
Phân công tài xế thủ công	Tự động tìm và phân công tài xế phù hợp.
Khó theo dõi chuyến	Theo dõi trạng thái chuyến đi rõ ràng.
Thanh toán chưa tập trung	Quản lý thanh toán tập trung và hỗ trợ thanh toán điện tử.
Khó biết vị trí tài xế	Lưu vị trí tài xế để tìm tài xế gần khách hàng và dự kiến thời gian đến.
Khó xử lý khi tài xế từ chối	Tự động tiếp tục tìm tài xế khác mà khách hàng không phải tạo lại yêu cầu.
Thông báo hạn chế	Thông báo tự động theo các sự kiện của chuyến đi.
Quản lý vận hành khó khăn	Có giao diện quản trị và phân quyền.
Khó thống kê	Có báo cáo về số chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả tài xế.
Khó mở rộng	Các thành phần có thể mở rộng độc lập.
Khó thêm chức năng	Kiến trúc linh hoạt để thêm dịch vụ, thanh toán và nhà cung cấp thông báo mới.
6. Business Problem
Business Problem chính: Hệ thống đặt xe hiện tại của Công ty ABC còn phụ thuộc nhiều vào xử lý thủ công, đặc biệt trong việc phân công tài xế; khách hàng khó theo dõi trạng thái chuyến đi; thông tin thanh toán chưa được quản lý tập trung; và hệ thống hiện tại khó mở rộng khi số lượng khách hàng, tài xế và nhu cầu sử dụng tăng lên.
Những hạn chế này làm giảm hiệu quả vận hành, ảnh hưởng đến trải nghiệm khách hàng và gây khó khăn cho doanh nghiệp khi muốn mở rộng quy mô.
7. Các Business Problem cụ thể
1. Phân công tài xế còn thủ công: Tốn thời gian, khó tìm tài xế phù hợp/gần khách hàng và khó xử lý khi tài xế không phản hồi hoặc từ chối.
2. Khách hàng khó theo dõi chuyến đi: Khách hàng khó biết hệ thống đang tìm tài xế, tài xế nào nhận chuyến, thời gian dự kiến đến và trạng thái hiện tại.
3. Thanh toán chưa được quản lý tập trung: Doanh nghiệp cần quản lý tiền mặt và thanh toán điện tử, đồng thời xử lý trường hợp giao dịch điện tử thất bại.
4. Hệ thống hiện tại khó mở rộng: Khó đáp ứng tải tăng, khó triển khai chức năng mới từng phần và cần hạn chế lỗi ở một chức năng ảnh hưởng toàn hệ thống.

# BƯỚC 2: XÁC ĐỊNH STAKEHOLDER

Dựa trên nội dung **Customer-Requirement.docx**, các stakeholder của dự án **CAB System** có thể xác định như sau:

| **Stakeholder**                                            | **Vai trò**                                                                                                                                                                                              |
| ---------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Ban giám đốc / Ban lãnh đạo Công ty ABC**                | Đưa ra định hướng, mục tiêu và yêu cầu tổng thể của dự án; mong muốn hệ thống có khả năng mở rộng lâu dài; theo dõi các báo cáo về số chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả tài xế. |
| **Khách hàng (Customer)**                                  | Người trực tiếp sử dụng hệ thống để đăng ký/đăng nhập, nhập điểm đón – điểm đến, chọn loại xe, đặt xe, theo dõi chuyến đi, xem lịch sử, thanh toán và đánh giá tài xế.                                   |
| **Tài xế (Driver)**                                        | Người cung cấp dịch vụ vận chuyển; quản lý hồ sơ và phương tiện, cập nhật trạng thái sẵn sàng, nhận/từ chối chuyến và cập nhật trạng thái trong quá trình thực hiện chuyến.                              |
| **Nhân viên vận hành (Operation Staff)**                   | Quản lý khách hàng, tài xế, phương tiện và chuyến đi; theo dõi các chuyến đang diễn ra, kiểm tra trạng thái tài xế, hỗ trợ xử lý chuyến gặp lỗi và tra cứu lịch sử giao dịch.                            |
| **Business Analyst (BA)**                                  | Phân tích yêu cầu nghiệp vụ, xác định phạm vi, tác nhân, quy trình nghiệp vụ, yêu cầu chức năng/phi chức năng, business rules, ngoại lệ và làm rõ những yêu cầu chưa được khách hàng xác định.           |
| **Nhà cung cấp thanh toán bên ngoài (Payment Provider)**   | Cung cấp dịch vụ thanh toán điện tử được tích hợp với CAB System; xử lý giao dịch thanh toán mà không yêu cầu CAB lưu trực tiếp thông tin thẻ/tài khoản nhạy cảm.                                        |
| **Nhà cung cấp dịch vụ thông báo (Notification Provider)** | Hỗ trợ gửi thông báo cho khách hàng và tài xế. Hệ thống được yêu cầu có khả năng bổ sung thêm các kênh/nhà cung cấp thông báo trong tương lai.                                                           |
| **Nhóm phát triển (Development Team)**                     | Xây dựng và triển khai CAB System dựa trên các yêu cầu đã được BA làm rõ.                                                                                                                                |

Trong đó, tài liệu xác định rõ **3 nhóm người dùng chính** của hệ thống là **Khách hàng, Tài xế và Nhân viên vận hành**.  Nhân viên vận hành còn chịu trách nhiệm quản lý và giám sát hoạt động, trong khi ban lãnh đạo cần các báo cáo phục vụ quản lý. 

**Lưu ý:** “Nhà cung cấp dịch vụ thông báo” và “Nhóm phát triển” được suy ra từ yêu cầu tích hợp/mở rộng và bối cảnh phát triển trong tài liệu; tài liệu không định danh một tổ chức cụ thể cho hai stakeholder này. 

### Bảng ngắn gọn để đưa vào bài

| **Stakeholder**             | **Vai trò**                                               |
| --------------------------- | --------------------------------------------------------- |
| Ban giám đốc / Ban lãnh đạo | Định hướng, đưa ra yêu cầu và theo dõi hiệu quả hoạt động |
| Khách hàng                  | Đặt xe, theo dõi chuyến, thanh toán, đánh giá             |
| Tài xế                      | Nhận chuyến và thực hiện chuyến đi                        |
| Nhân viên vận hành          | Quản lý và giám sát hoạt động hệ thống                    |
| Business Analyst            | Phân tích và làm rõ yêu cầu nghiệp vụ                     |
| Payment Provider            | Xử lý thanh toán điện tử                                  |
| Notification Provider       | Cung cấp kênh/dịch vụ gửi thông báo                       |
| Development Team            | Phát triển và triển khai hệ thống CAB                     |
 STAKEHOLDER MATRIX – MA TRẬN MỨC ĐỘ ẢNH HƯỞNG

Dựa trên các stakeholder đã xác định từ **CAB System**, có thể xây dựng **Stakeholder Matrix theo 2 tiêu chí:**
* **Power (Mức độ ảnh hưởng/quyền lực):** Khả năng tác động đến quyết định, yêu cầu và sự thành công của dự án.
* **Interest (Mức độ quan tâm):** Mức độ stakeholder quan tâm hoặc bị ảnh hưởng bởi CAB System.

Tài liệu cho thấy ban lãnh đạo đưa ra các kỳ vọng cấp cao; khách hàng, tài xế và nhân viên vận hành là các nhóm sử dụng/nghiệp vụ chính.  
## 1. Ma trận Power – Interest
                     MỨC ĐỘ QUAN TÂM (INTEREST)
                          THẤP                     CAO
                 ┌─────────────────────┬──────────────────────────────┐
                 │                     │                              │
     CAO         │   KEEP SATISFIED    │       MANAGE CLOSELY         │
                 │                     │                              │
                 │ Payment Provider    │ ★ Ban giám đốc / Lãnh đạo   │
                 │                     │ ★ Business Analyst (BA)      │
MỨC ĐỘ           │                     │ ★ Nhân viên vận hành         │
ẢNH HƯỞNG        │                     │                              │
(POWER)          ├─────────────────────┼──────────────────────────────┤
                 │                     │                              │
     THẤP        │      MONITOR        │        KEEP INFORMED         │
                 │                     │                              │
                 │ Notification        │ ★ Khách hàng                 │
                 │ Provider            │ ★ Tài xế                     │
                 │                     │ ★ Development Team           │
                 │                     │                              │
                 └─────────────────────┴──────────────────────────────┘
```

## 2. Bảng đánh giá mức độ ảnh hưởng

| Stakeholder                     |  Power  | Interest | Nhóm Matrix        | Giải thích                                                                     |
| ------------------------------- | :-----: | :------: | ------------------ | ------------------------------------------------------------------------------ |
| **Ban giám đốc / Ban lãnh đạo** | **Cao** |  **Cao** | **Manage Closely** | Quyết định mục tiêu, định hướng và kỳ vọng của hệ thống                        |
| **Business Analyst (BA)**       | **Cao** |  **Cao** | **Manage Closely** | Phân tích, làm rõ yêu cầu và xác định phạm vi hệ thống                         |
| **Nhân viên vận hành**          | **Cao** |  **Cao** | **Manage Closely** | Trực tiếp quản lý khách hàng, tài xế, phương tiện và chuyến đi                 |
| **Khách hàng**                  |   Thấp  |  **Cao** | **Keep Informed**  | Trực tiếp sử dụng dịch vụ đặt xe và chịu ảnh hưởng lớn bởi chất lượng hệ thống |
| **Tài xế**                      |   Thấp  |  **Cao** | **Keep Informed**  | Trực tiếp nhận và thực hiện chuyến thông qua hệ thống                          |
| **Development Team**            |   Thấp  |  **Cao** | **Keep Informed**  | Xây dựng và triển khai hệ thống dựa trên yêu cầu đã được xác định              |
| **Payment Provider**            | **Cao** |   Thấp   | **Keep Satisfied** | Ảnh hưởng đến khả năng xử lý thanh toán điện tử                                |
| **Notification Provider**       |   Thấp  |   Thấp   | **Monitor**        | Cung cấp kênh thông báo và có thể được thay thế/mở rộng trong tương lai        |

**Lưu ý:** mức Power/Interest ở bảng trên là **đánh giá phân tích** dựa trên vai trò được mô tả trong tài liệu, chứ tài liệu không trực tiếp gán các mức “Cao/Thấp”. Ví dụ, tài liệu xác định BA có trách nhiệm làm rõ các vấn đề chưa chốt trước khi nhóm phát triển xây dựng giải pháp. 
## 3. Ý nghĩa 4 vùng của Stakeholder Matrix
**Manage Closely – Quản lý chặt chẽ:** Ban lãnh đạo, BA và nhân viên vận hành cần được tham gia thường xuyên vào quá trình phân tích yêu cầu, xác nhận nghiệp vụ và các quyết định quan trọng.
**Keep Satisfied – Duy trì sự hài lòng:** Payment Provider cần được quản lý tốt về yêu cầu tích hợp, bảo mật và xử lý giao dịch.
**Keep Informed – Cập nhật thông tin:** Khách hàng, tài xế và Development Team cần được cung cấp đầy đủ thông tin liên quan đến yêu cầu, thay đổi và hoạt động của hệ thống.
**Monitor – Theo dõi:** Notification Provider cần được theo dõi nhưng mức độ tham gia vào quyết định nghiệp vụ cốt lõi thấp hơn. CAB System cũng được yêu cầu có khả năng mở rộng thêm các kênh thông báo mà không phải thay đổi toàn bộ hệ thống. 
