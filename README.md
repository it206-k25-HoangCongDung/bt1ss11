# [MINI PROJECT] XÂY DỰNG PRODUCT BACKLOG VÀ KẾ HOẠCH SPRINT CHO DỰ ÁN MOTOGO

> 👤 **Học viên:** Hoàng Công Dũng | **Mã SV:** PTIT-HCM-009
> 🏫 **Môn học:** it206-k25-HoangCongDung

---

## Nhiệm vụ 1: Phân rã Epic – Feature

Dự án MotoGo được phân rã thành 3 Epic cốt lõi nhằm giải quyết trực tiếp các bài toán nghiệp vụ cho du lịch xe máy tự lái tại Vũng Tàu và Đà Nẵng. Các Epic tập trung vào giá trị mang lại cho người dùng thay vì phân chia theo module kỹ thuật thuần túy.

- Epic 1: Quản lý và Tìm kiếm xe linh hoạt theo thời gian thực (Mang lại giá trị giúp khách thuê dễ dàng tìm được chiếc xe ưng ý, đúng lịch trình mà không sợ bị trùng lặp thời gian).
- Epic 2: Vận hành đơn hàng và Giữ chỗ thông minh (Mang lại giá trị bảo đảm quyền lợi đặt xe an toàn, chống tranh chấp lịch thuê giữa các cửa hàng).
- Epic 3: Quy trình bàn giao và Kiểm định chất lượng xe (Mang lại giá trị minh bạch hóa tình trạng xe trước và sau khi thuê, bảo vệ quyền lợi pháp lý cho cả hai bên).

## Nhiệm vụ 2: Danh sách User Story

Toàn bộ Product Backlog của Sprint 1 bao gồm 9 User Story, bám sát các mã FR (Functional Requirement) và BR (Business Rule) trong tài liệu yêu cầu. Trong đó có các story dành cho đối tượng chủ cửa hàng và nhân viên vận hành.

- US-01 | Là khách thuê, tôi muốn giữ chỗ chiếc xe vừa chọn để không bị người khác đặt mất trong lúc tôi thanh toán. | Truy vết: FR-10, BR-05 | Mức ưu tiên: Must | Story Point: 5 | AC: AC-01, AC-02, AC-03
- US-02 | Là khách thuê, tôi muốn tìm kiếm xe máy theo khoảng thời gian và địa điểm nhận xe để lọc ra danh sách xe còn trống chính xác. | Truy vết: FR-02, BR-01 | Mức ưu tiên: Must | Story Point: 3 | AC: AC-04, AC-05, AC-06
- US-03 | Là chủ cửa hàng, tôi muốn nhận thông báo có đơn đặt xe mới để kịp thời kiểm tra và xác nhận xe trong kho. | Truy vết: FR-04, BR-02 | Mức ưu tiên: Must | Story Point: 3 | AC: AC-07, AC-08, AC-09
- US-04 | Là nhân viên cửa hàng, tôi muốn hệ thống tự động khóa lịch xe đã được xác nhận để tránh bị trùng lặp đơn cho thuê. | Truy vết: FR-06, BR-03 | Mức ưu tiên: Must | Story Point: 5 | AC: AC-10, AC-11, AC-12
- US-05 | Là chủ cửa hàng, tôi muốn xem danh sách các đơn đặt xe trong ngày để sắp xếp nhân sự bàn giao xe. | Truy vết: FR-07 | Mức ưu tiên: Should | Story Point: 2 | AC: AC-13, AC-14
- US-06 | Là khách thuê, tôi muốn hủy đơn đặt xe trước thời gian nhận xe 24 giờ để được hoàn tiền cọc theo chính sách. | Truy vết: FR-12, BR-08 | Mức ưu tiên: Should | Story Point: 3 | AC: AC-15, AC-16, AC-17
- US-07 | Là nhân viên bàn giao, tôi muốn chụp ảnh hiện trạng xe trước khi giao để lưu làm bằng chứng xác thực. | Truy vết: FR-15, BR-10 | Mức ưu tiên: Should | Story Point: 5 | AC: AC-18, AC-19, AC-20
- US-08 | Là khách thuê, tôi muốn ký xác nhận biên bản giao nhận điện tử kèm hình ảnh trên ứng dụng. | Truy vết: FR-16, BR-10 | Mức ưu tiên: Could | Story Point: 3 | AC: AC-21, AC-22, AC-23
- US-09 | Là quản trị viên hệ thống, tôi muốn tích hợp tính năng định vị GPS thời gian thực trên xe máy cho thuê. | Truy vết: FR-25 | Mức ưu tiên: Won't | Story Point: 13 | AC: Không áp dụng cho Sprint 1

## Nhiệm vụ 3: Bảng tự đánh giá INVEST

Đánh giá 3 User Story tiêu biểu theo 6 tiêu chí INVEST để đảm bảo chất lượng Backlog trước khi đưa vào lập kế hoạch Sprint.

- Phần viết lại cho US-09 sau khi tách nhỏ thành công:
- Bản trước khi sửa: US-09 (Là chủ cửa hàng, tôi muốn theo dõi GPS toàn bộ xe cho thuê để chống trộm và quản lý lộ trình). Điểm: 13.
- Bản sau khi sửa 1: US-09A | Là chủ cửa hàng, tôi muốn xem vị trí cập nhật cuối cùng của xe trên bản đồ ứng dụng khi có yêu cầu. | Story Point: 5.
- Bản sau khi sửa 2: US-09B | Là chủ cửa hàng, tôi muốn nhận cảnh báo khi xe di chuyển ra khỏi vùng giới hạn tỉnh thành đã đăng ký. | Story Point: 5.
- Giải thích đã sửa: Chia nhỏ story 13 điểm gắn với phần cứng phức tạp thành 2 story độc lập, có thể phát triển gia tăng giá trị theo từng bước.

| Mã Story | Independent (Độc lập) | Negotiable (Thương lượng) | Valuable (Có giá trị) | Estimable (Ước lượng được) | Small (Đủ nhỏ) | Testable (Kiểm thử được) | Kết quả & Lý do |
| --- | --- | --- | --- | --- | --- | --- | --- |
| US-01 | Đạt | Đạt | Đạt | Đạt | Đạt | Đạt | Đạt - Story hoàn chỉnh, rõ ràng, dễ test. |
| US-04 | Đạt | Đạt | Đạt | Đạt | Đạt | Đạt | Đạt - Logic tự động khóa lịch chặt chẽ. |
| US-09 | Chưa đạt | Đạt | Đạt | Đạt | Chưa đạt | Chưa đạt | Chưa đạt do quá lớn (13 điểm), phụ thuộc phần cứng GPS phần cứng ngoài. |

## Nhiệm vụ 4: Acceptance Criteria

Xây dựng tiêu chí chấp nhận theo cấu trúc Given – When – Then cho 3 story có mức ưu tiên cao nhất, bao phủ cả luồng chính, ngoại lệ và quy tắc nghiệp vụ BR.

- US-01 (Giữ chỗ xe):
- | AC-01 (luồng chính) | Given khách đã chọn xe còn trống và bấm đặt, When hệ thống tạo đơn thành công, Then xe được giữ chỗ 30 phút và không hiển thị cho khách khác. |
- | AC-02 (ngoại lệ) | Given đơn đang ở trạng thái chờ thanh toán, When quá 30 phút mà khách chưa thanh toán cọc, Then đơn tự động hủy theo BR-05 và xe được mở lại trong kết quả tìm kiếm. |
- | AC-03 (nghiệp vụ BR-05) | Given hệ thống đang thực hiện giữ chỗ xe, When đếm ngược thời gian đạt mốc 30 phút, Then hệ thống kích hoạt cơ chế giải phóng tài nguyên kho theo đúng BR-05. |
- US-02 (Tìm kiếm xe):
- | AC-04 (luồng chính) | Given khách chọn mốc thời gian nhận trả xe tại Vũng Tàu, When khách bấm tìm kiếm, Then hệ thống hiển thị danh sách xe còn trống trong khung giờ đó. |
- | AC-05 (ngoại lệ) | Given khách chọn khoảng thời gian nhận xe nằm trong quá khứ, When bấm tìm kiếm, Then hệ thống báo lỗi không hợp lệ theo BR-01. |
- | AC-06 (nghiệp vụ BR-01) | Given khung giờ tìm kiếm trùng với lịch đã được xác nhận cọc của xe khác, When lọc kết quả, Then hệ thống ẩn xe đó khỏi danh sách hiển thị theo BR-01. |
- US-04 (Khóa lịch xe tự động):
- | AC-10 (luồng chính) | Given chủ cửa hàng bấm xác nhận đơn thuê, When đơn chuyển sang trạng thái đã cọc, Then hệ thống tự động khóa lịch xe trong khoảng thời gian tương ứng. |
- | AC-11 (ngoại lệ) | Given lịch xe đã bị khóa bởi một đơn khác trước đó, When hệ thống nhận yêu cầu xác nhận trùng lịch, Then từ chối và hiển thị cảnh báo lỗi trùng kho theo BR-03. |
- | AC-12 (kiểm tra kho) | Given trạng thái xe đã được khóa lịch, When có khách khác tìm kiếm cùng khung giờ, Then xe tuyệt đối không xuất hiện trong kết quả trả về. |

## Nhiệm vụ 5: Definition of Done

Bộ Definition of Done (DoD) chuẩn áp dụng đồng nhất cho mọi User Story trong suốt quá trình phát triển dự án MotoGo:

- 1. Code đã được viết hoàn chỉnh và vượt qua toàn bộ Unit Test với độ phủ mã nguồn đạt tối thiểu 80%. (Có / Không)
- 2. Code đã được review bởi ít nhất một thành viên khác trong Development Team và không còn lỗi nghiêm trọng. (Có / Không)
- 3. Đã viết và kiểm thử thành công tất cả các Acceptance Criteria (bao gồm luồng chính và ngoại lệ). (Có / Không)
- 4. Giao diện người dùng đã được kiểm tra tính tương thích trên cả thiết bị di động và máy tính bảng. (Có / Không)
- 5. Tài liệu kỹ thuật và mã nguồn đã được cập nhật, merge thành công lên nhánh chính của kho lưu trữ GitHub. (Có / Không)
- Phân biệt DoD và Acceptance Criteria: Acceptance Criteria là các điều kiện cụ thể để kiểm tra xem một User Story cụ thể có đạt yêu cầu nghiệp vụ hay không (ví dụ: AC của US-01 là giữ chỗ xe trong 30 phút). Trong khi đó, Definition of Done là tập hợp các tiêu chuẩn kỹ thuật chung mà mọi User Story đều phải hoàn thành trước khi được coi là Done (ví dụ: phải qua code review, phải pass unit test). Lấy ví dụ từ US-01: AC kiểm tra việc giữ xe 30 phút, còn DoD kiểm tra xem code của US-01 đã được viết unit test và review hay chưa.

## Nhiệm vụ 6: Prioritized Product Backlog

Sắp xếp thứ tự ưu tiên toàn bộ Backlog theo mô hình MoSCoW, đảm bảo tỷ lệ Must không vượt quá 50% tổng số story và gắn liền với mục tiêu kinh doanh của dự án MotoGo.

| Hạng mục | Mức MoSCoW | Lý do xếp hạng gắn với mục tiêu kinh doanh MotoGo |
| --- | --- | --- |
| US-01 | Must | Phục vụ mục tiêu cốt lõi kết nối khách và cửa hàng, đảm bảo không bị tranh chấp đơn thuê xe. |
| US-02 | Must | Giải quyết nghiệp vụ tìm kiếm xe trống - tính năng sống còn của nền tảng du lịch MotoGo. |
| US-03 | Must | Giúp cửa hàng nhận đơn nhanh chóng, đảm bảo luồng vận hành xuyên suốt tại Vũng Tàu và Đà Nẵng. |
| US-04 | Must | Bảo vệ kho xe không bị trùng lịch, giải quyết bài toán cốt lõi của nhà quản lý cửa hàng. |
| US-05 | Should | Hỗ trợ nhân viên sắp xếp lịch giao xe hàng ngày, tối ưu hóa hiệu suất vận hành tại chỗ. |
| US-06 | Should | Đảm bảo chính sách hoàn cọc minh bạch, nâng cao độ tin cậy và trải nghiệm cho khách du lịch. |
| US-07 | Should | Bảo vệ quyền lợi pháp lý khi giao nhận xe, tránh tranh chấp hư hỏng giữa hai bên. |
| US-08 | Could | Số hóa biên bản giao nhận bằng chữ ký điện tử, tăng tính tiện lợi nhưng có thể làm sau nếu gấp. |
| US-09 | Won't | Tích hợp định vị GPS phần cứng là tính năng nâng cao, chưa cần thiết cho phiên bản thử nghiệm MVP đầu tiên tại Vũng Tàu và Đà Nẵng. |

## Nhiệm vụ 7: Bảng ước lượng Story Point

Thực hiện ước lượng Story Point bằng phương pháp so sánh tương đối với story chuẩn (US-02 được chọn làm mốc chuẩn với 3 điểm Fibonacci).

- Lưu ý: Story US-09 ban đầu 13 điểm đã được tách nhỏ thành US-09A (5 điểm) và US-09B (5 điểm) đúng theo yêu cầu kỹ thuật.

| Mã Story | Story Point | Căn cứ so sánh tương đối với story chuẩn US-02 (3 điểm) |
| --- | --- | --- |
| US-02 | 3 | Story chuẩn làm mốc (độ phức tạp lọc tìm kiếm cơ bản). |
| US-01 | 5 | Phức tạp hơn US-02 do cần xử lý logic đếm ngược thời gian 30 phút và tự động giải phóng kho. |
| US-03 | 3 | Tương đương US-02, xử lý thông báo sự kiện đơn hàng đơn giản. |
| US-04 | 5 | Độ phức tạp cao trong việc xử lý concurrency khóa lịch kho xe tránh tranh chấp dữ liệu. |
| US-05 | 2 | Đơn giản hơn US-02, chỉ là truy vấn hiển thị danh sách theo ngày. |
| US-06 | 3 | Độ phức tạp vừa phải, xử lý logic thời gian 24 giờ và hoàn tiền cọc. |
| US-07 | 5 | Tương đương US-01, liên quan đến tải và lưu trữ hình ảnh hiện trạng xe. |
| US-08 | 3 | Tương đương US-03, xử lý ký xác nhận biên bản điện tử trên ứng dụng. |

## Nhiệm vụ 8: Kế hoạch Sprint 1

Sprint Goal: Xây dựng thành công hệ thống cốt lõi cho phép khách hàng tìm kiếm, đặt giữ chỗ xe máy an toàn và giúp chủ cửa hàng xác nhận, quản lý kho xe không bị trùng lịch tại thị trường Vũng Tàu và Đà Nẵng.

Sprint Backlog gồm các story: US-01, US-02, US-03, US-04 (Tổng cộng 16 Story Point, hoàn toàn phù hợp với velocity giả định của team là 20 điểm).

- Bảng capacity cá nhân của Development Team trong Sprint 1 (Sprint kéo dài 10 ngày làm việc, mỗi ngày 6 giờ làm việc thực tế sau khi trừ họp hành và dự phòng 20%):
- - Thành viên 1 (Backend Dev): 6 giờ/ngày * 10 ngày = 60 giờ.
- - Thành viên 2 (Frontend Dev): 6 giờ/ngày * 10 ngày = 60 giờ.
- - Thành viên 3 (Fullstack / Tester): 6 giờ/ngày * 10 ngày = 60 giờ.
- - Tổng capacity của Team: 180 giờ (đảm bảo hoàn thành tốt khối lượng task 49 giờ của Sprint 1).

| Mã Task | Mô tả công việc chi tiết | User Story liên quan | Số giờ dự kiến (Hours) |
| --- | --- | --- | --- |
| TSK-01 | Thiết kế cơ sở dữ liệu bảng đơn hàng và bảng giữ chỗ | US-01 | 6h |
| TSK-02 | Xây dựng API xử lý giữ chỗ 30 phút và cơ chế timeout | US-01 | 8h |
| TSK-03 | Viết API tìm kiếm xe theo thời gian và địa điểm | US-02 | 6h |
| TSK-04 | Thiết kế giao diện màn hình tìm kiếm xe trên App | US-02 | 6h |
| TSK-05 | Xây dựng API gửi thông báo đơn hàng mới cho chủ cửa hàng | US-03 | 5h |
| TSK-06 | Phát triển logic tự động khóa lịch xe khi đơn được xác nhận | US-04 | 8h |
| TSK-07 | Kiểm thử toàn bộ luồng tích hợp và viết Unit Test | US-01, US-02, US-03, US-04 | 10h |

## Phụ lục A: Nhật ký vai trò

Phụ lục ghi nhận các quyết định quan trọng của Scrum Team trong quá trình thực hiện bài tập:

1. Quyết định giới hạn phạm vi Sprint 1 chỉ chọn 4 story cốt lõi (US-01 đến US-04) với tổng 16 Story Point. Ra ở vai trò: Product Owner. Căn cứ: Dựa trên velocity giả định của team và mục tiêu kinh doanh cốt lõi tại Vũng Tàu và Đà Nẵng.

2. Quyết định tách story US-09 (13 điểm) thành 2 story 5 điểm là US-09A và US-09B. Ra ở vai trò: Development Team. Căn cứ: Tuân thủ quy tắc INVEST không để story vượt quá 13 điểm và giảm thiểu rủi ro kỹ thuật phần cứng.

3. Quyết định bổ sung cơ chế tự động hủy đơn sau 30 phút nếu chưa thanh toán (BR-05). Ra ở vai trò: Scrum Master kết hợp PO. Căn cứ: Giải quyết triệt để bài toán chiếm giữ kho xe ảo của khách hàng.

## Phụ lục B: Câu hỏi và giả định

Phụ lục ghi nhận các thắc mắc và giả định nghiệp vụ thực tế:

1. Câu hỏi đặt ra cho khách hàng (Đại diện công ty du lịch MotoGo): Nếu khách đặt xe và đã giữ chỗ 30 phút nhưng hệ thống thanh toán trực tuyến bị nghẽn mạng đúng phút thứ 29 thì xử lý thế nào? Câu trả lời / Giả định thay thế: Hệ thống tự động gia hạn thêm 10 phút ân hạn và gửi thông báo đẩy nhắc nhở khách hàng. Ảnh hưởng nếu giả định sai: Khách hàng có thể khiếu nại vì mất cọc oan uổng khi lỗi thuộc về cổng thanh toán.

2. Câu hỏi đặt ra cho khách hàng: Chủ cửa hàng có quyền đơn phương hủy đơn đã xác nhận khi xe gặp sự cố hỏng hóc bất ngờ không? Câu trả lời / Giả định thay thế: Cho phép hủy đơn, đồng thời hệ thống tự động gợi ý đổi sang một chiếc xe khác tương đương trong cùng cửa hàng cho khách. Ảnh hưởng nếu giả định sai: Khách du lịch bị lỡ lịch trình tại Vũng Tàu/Đà Nẵng và đánh giá thấp uy tín nền tảng MotoGo.

---

## 📁 Danh sách tệp tin nộp bài trong Repository
- 📝 `bt1.docx`: Báo cáo tài liệu phân tích nghiệp vụ hoàn chỉnh.
