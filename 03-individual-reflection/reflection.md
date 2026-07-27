# Individual Reflection — Day 02

> Reflection phải do chính tôi viết từ trải nghiệm trong buổi lab. AI chỉ được gợi ý câu hỏi tự soi hoặc kiểm tra phần còn thiếu, không viết câu trả lời thay tôi.

## 1. Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng |
|---|---|---|
| Scan cá nhân | Tôi xác nhận 10 vấn đề mình đã trực tiếp gặp và bổ sung dữ kiện về workflow, thời gian và hậu quả. | Có 10 candidate problems từ trải nghiệm học tập, làm team lead và dùng AI coding agent. |
| Pitch Problem Card | Tôi pitch cả 3 Problem Cards: sàng lọc ứng viên Phoenix, onboarding thành viên mới và xác minh kết quả AI coding agent. | Nhóm có đủ 3 candidates của tôi để đưa vào bảng 15 candidates và challenge tính hợp lệ của metric. |
| Challenge bài của bạn khác | Tôi hỏi liệu bài toán mua sắm có thể giải quyết đủ bằng form bắt buộc và Rule mà chưa cần AI hay không. | Nhóm bổ sung form + Rule làm baseline đối chứng trong pilot. |
| Gom trùng / cluster | Tôi tổng hợp Top 3 của 5 thành viên thành 15 candidates và đề xuất gom theo actor, workflow và bottleneck thay vì chỉ theo tên topic. | Nhóm hình thành 4 clusters không trùng candidate và chọn Cluster D để shortlist. |
| Chọn candidate problem | Tôi so sánh #7, #8, #9 và tham gia chấm điểm theo actor, workflow, evidence, impact và phạm vi lab. | Nhóm chọn #7 — tiếp nhận và chuẩn bị hồ sơ mua sắm trước phê duyệt. |
| Validation / research | Tôi tham gia thu thập validation từ 3 người và kiểm tra các pattern từ Microsoft, SAP, Oracle cùng Google PAIR. | Nhóm tách evidence khỏi giả định, ghi nhận tín hiệu phản bác và xác định pattern AI extraction + Rule validation + Human review. |
| Workflow nhóm | Tôi vẽ current/future workflow và tách rõ bước của AI, Rule, Workflow, con người cùng fallback. | Bản nhóm chỉ đặt AI ở bước đọc/đối chiếu tài liệu; nhân viên vẫn xác nhận và người có thẩm quyền phê duyệt. |
| Problem Statement | Tôi làm rõ metric/cách đo và boundary/guardrail của Problem Statement v0/v1. | Nhóm tách active processing khỏi waiting time, giới hạn scope trước phê duyệt và bắt buộc xác nhận trường tài chính. |
| Rule / Workflow / Agent | Tôi lập luận chọn Workflow cho pilot, dùng Rule làm đối chứng và không chọn Agent vì đường đi đã cố định. | Nhóm chọn Workflow — AI extraction + Rule validation + Human review. |
| Decision | Tôi lập luận pain và điểm can thiệp AI đã đủ rõ để thử nghiệm, nhưng pilot phải giới hạn quyền, dùng dữ liệu đã ẩn và so sánh với form + Rule. | Nhóm quyết định Go có điều kiện cho pilot Workflow có AI, chưa Go production. |

## 2. Cách tôi dùng AI

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý cách nhóm trải nghiệm thành candidate problems và hỏi thêm dữ kiện. | Giúp tôi nhìn các trải nghiệm theo actor, workflow, bottleneck và metric. | Một số chi tiết ban đầu mới là suy đoán hoặc chưa có bằng chứng. | Tôi chỉ giữ 10 vấn đề mình đã gặp và bổ sung ví dụ, thời gian, tần suất, hậu quả thật. |
| Problem Card | Hỗ trợ cấu trúc thông tin đã xác nhận theo template. | Giúp kiểm tra đủ actor, workflow, bottleneck, impact, metric và non-AI alternative. | Các target dưới 4 giờ và dưới 15 phút chưa được validation. | Tôi đánh dấu các target này là giả thuyết cần kiểm chứng, không trình bày như kết quả thật. |
| Workflow | Nhờ AI chuyển mô tả workflow thành flowchart và gợi ý cách tách AI, Rule, human review, fallback. | Giúp tôi nhìn rõ các bước, handoff và human boundary để kiểm tra lại với workflow thật. | AI có xu hướng gộp nhiều bước hoặc đưa AI/Agent vào quá sớm trước khi scope đủ hẹp. | Tôi tự tách current/future workflow, giữ đường đi cố định, đặt Rule ở các điều kiện xác định được và giữ người thật ở bước review. |
| Research | Gợi ý các solution/pattern liên quan đến purchase requisition workflow, approval rule và AI tạo hồ sơ nháp. | Giúp tôi tìm được pattern form/Rule cho approval và pattern AI extraction → draft → human confirmation. | Một nguồn hoặc claim có thể không chứng minh được workflow của nhóm hay lợi ích thời gian; AI cũng có thể mở rộng scope quá mức. | Tôi chỉ giữ nguồn đã kiểm tra, ghi rõ khoảng trống, không dùng research như bằng chứng validation cho actor của nhóm. |
| Problem Statement | Kiểm tra các field actor, workflow, bottleneck, impact, metric và boundary. | Giúp phát hiện chỗ mô tả còn rộng và buộc phải tách baseline, target, cách đo. | AI có thể diễn đạt baseline/target như kết quả đã kiểm chứng dù thiếu log và mẫu. | Tôi gắn nhãn baseline sơ bộ, tách active processing khỏi waiting time và ghi rõ các giả định mở. |
| Rule / Workflow / Agent | So sánh ba mức giải pháp và nhờ AI phản biện việc chọn Agent. | Giúp làm rõ Workflow là mức vừa đủ khi các bước đã biết trước. | AI đề xuất tự động hóa toàn quy trình hoặc Agent quá sớm, chưa cân nhắc permission và audit. | Tôi chọn Workflow cho pilot, dùng Rule/form làm baseline và loại Agent vì không cần tự lập kế hoạch hay tự submit. |
| Decision | Dùng AI để kiểm tra tính nhất quán giữa evidence, metric, boundary và quyết định. | Giúp rà lại điều kiện Go/Not Yet/No-Go và rollback. | AI có thể khiến “Go” bị hiểu thành triển khai production dù evidence hiện chỉ đủ cho thử nghiệm nhỏ. | Tôi giới hạn quyết định thành Go có điều kiện cho pilot, bắt buộc đối chứng form + Rule và giữ tiêu chí rollback. |

## 3. Câu hỏi tự reflection

Tự trả lời sau khi hoàn thành hoạt động nhóm:

1. Tôi học được gì khi nghe Top 3 problems của các bạn khác?
2. Tôi đã pitch Problem Card nào và nhóm challenge điểm gì?
3. Tôi đã challenge candidate của bạn khác bằng câu hỏi nào?
4. Có lúc nào nhóm bắt đầu từ solution hoặc Agent trước khi hiểu workflow không?
5. Tôi có thay đổi ý kiến sau validation hoặc research không? Vì sao?
6. Tôi đã đóng góp cụ thể gì vào artifact cuối của nhóm?
7. Điều khó nhất khi viết Problem Statement là gì?
8. AI đưa ra điều gì sai, thiếu nguồn hoặc quá rộng? Tôi đã kiểm tra và sửa thế nào?
9. Vì sao nhóm chọn No AI, Rule, Workflow hoặc Agent?
10. Nếu làm lại, tôi sẽ challenge hoặc validation mạnh hơn ở điểm nào?

## 4. Reflection của tôi

Khi nghe Top 3 problems của các thành viên khác, tôi nhận ra evidence quyết định độ mạnh của một candidate. Một problem nghe có vẻ phù hợp với AI vẫn yếu nếu baseline và impact chỉ là giả định. Khi pitch cả ba Problem Cards của mình, nhóm challenge các metric chưa được validation. Với card Phoenix, tôi đổi target từ “hoàn thành trong 24 giờ kể từ lúc liên hệ” thành “có đủ thông tin để đánh giá chậm nhất 24 giờ trước deadline”, vì mục tiêu thật là tránh lỡ thời hạn chốt team.

Tôi challenge candidate mua sắm bằng câu hỏi: “Form bắt buộc và Rule có giải quyết đủ pain mà chưa cần AI không?”. Câu hỏi này khiến nhóm đưa form + Rule vào làm baseline đối chứng thay vì mặc định AI là giải pháp. Trong quá trình thiết kế future workflow, nhóm từng nghiêng về việc cho AI hoặc Agent xử lý nhiều bước. Sau khi vẽ lại workflow, tôi thấy các bước đã có thứ tự cố định: AI chỉ cần đọc và đối chiếu tài liệu, Rule kiểm tra điều kiện xác định được, nhân viên xác nhận dữ liệu và người có thẩm quyền phê duyệt. Vì vậy Workflow phù hợp hơn Agent.

Điều khó nhất khi viết Problem Statement là vừa làm metric đo được vừa giữ boundary đủ hẹp. Nhóm phải tách active processing khỏi thời gian chờ, giữ mốc 80–90 phút ở trạng thái baseline sơ bộ, đặt target pilot thay vì coi là kết quả và kết thúc scope trước phê duyệt. Sau validation và research, tôi giữ hướng dùng AI nhưng thu hẹp quyết định thành Go có điều kiện cho pilot: AI có điểm can thiệp hợp lý ở bước đọc/đối chiếu tài liệu không đồng nhất, còn production chỉ được xem xét nếu pilot chứng minh tốt hơn form + Rule và đạt guardrail.

AI hữu ích khi cấu trúc Problem Card, vẽ Mermaid, gợi ý pattern research và phản biện tính nhất quán. Tuy nhiên, AI từng có xu hướng nâng giả định thành evidence, mở scope ra toàn bộ quy trình mua sắm và đề xuất Agent quá sớm. Tôi sửa bằng cách chỉ giữ dữ kiện đã xác nhận, ghi rõ giả định mở, thu hẹp vào bước chuẩn bị hồ sơ trước phê duyệt, dùng form + Rule làm baseline và giữ human review cho dữ liệu tài chính.

## 5. Nếu làm lại

Nếu làm lại, tôi sẽ validation sớm hơn với người trực tiếp xử lý nghiệp vụ và ghi ngay số người, số mẫu cùng loại yêu cầu trước khi chấm candidate. Tôi cũng sẽ challenge mọi baseline và target bằng câu hỏi về nguồn, cách đo và trạng thái giả định. Trước khi thiết kế AI workflow, tôi sẽ kiểm tra form, checklist và Rule có giải quyết đủ pain hay không để tránh solution-first.

## 6. Tự kiểm cuối bài

- [x] Tôi nói rõ vai trò và đóng góp thực tế của mình trong nhóm.
- [x] Tôi nêu ít nhất một câu hỏi/challenge mình đã đưa ra.
- [x] Tôi ghi AI hữu ích ở đâu và sai/hời hợt ở đâu.
- [x] Tôi giải thích mình đã dùng nhận định cá nhân để sửa output AI thế nào.
- [x] Tôi giải thích được mạch problem → workflow → metric → boundary → độ phù hợp với AI.
- [x] Tôi giải thích được vì sao nhóm chọn Rule / Workflow / Agent và Go / Not Yet / No-Go.
- [x] Tôi nêu điều sẽ thay đổi nếu làm lại.
