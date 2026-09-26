# Nhật ký hỗ trợ AI

## Mẫu log

- Mốc thời gian chính xác: `HH:MM dd/mm/yyyy`
- Tên công cụ sử dụng: `Tên công cụ và phiên bản`
- Câu prompt gửi đi nguyên văn:
- Tóm tắt phản hồi của AI:

## Log 01

- Mốc thời gian chính xác: `13:46 23/09/2026`
- Tên công cụ sử dụng: `GitHub Copilot`
- Câu prompt gửi đi nguyên văn:

> Tại file `prompt_log.md` hãy tạo cấu trúc như dưới để tôi viết log sự hỗ trợ AI. Sau khi tạo xong hãy ghi log đầu tiên là câu prompt này luôn :
>
> - Mốc thời gian chính xác: `HH:MM dd/mm/yyyy`
> - Tên công cụ sử dụng (ChatGPT 4o, Claude 3.5 Sonnet, Gemini 2.5 Pro...)
> - Câu prompt gửi đi nguyên văn
> - Tóm tắt phản hồi của AI

- Tóm tắt phản hồi của AI: Đã tạo cấu trúc nhật ký gồm bốn mục yêu cầu và ghi lại prompt đầu tiên trong file `prompt_log.md`.

## Log 02

- Mốc thời gian chính xác: `13:54 23/09/2026`
- Tên công cụ sử dụng: `Gemini`
- Câu prompt gửi đi nguyên văn:

> Hãy tìm 10 tin tuyển dụng trong vòng 60 ngày gần nhất:
> Bắt buộc: Có ít nhất 3 tin yêu cầu kỹ năng liên quan đến: AI Testing, LLM Evaluation, AI Quality Engineer, Automation Test with Copilot/AI.
> Kết quả: trả ra các thông tin tuyển dụng theo yêu cầu và kèm đường link ref đến các jd đó (ưu tiên các jd trên linked, indeed.v.v).

- Tóm tắt phản hồi của AI: Trả về 10 job trong đó 8/10 job thỏa mản yêu cầu.

## Log 03

- Mốc thời gian chính xác: `14:17 23/09/2026`
- Tên công cụ sử dụng: `Gemini`
- Câu prompt gửi đi nguyên văn:

> Hãy dựa vào dữ kiện trên. Bạn có thể truy cập link chính xác để đọc, hãy tạo sheet phân tích theo yêu cầu sau: "Với mỗi tin tuyển dụng, trích xuất vào báo cáo: Tên công ty, Vị trí, Đường dẫn URL bài đăng, Mức lương, Các kỹ năng chính." (Lưu ý: ở prompt này tôi có kèm theo link một vài job (job 1 2 3 trong thư mục bằng chứng) mà tôi tự tim để bù các job không phụ hợp của kết quả AI trả về ở trên). Sau đó mỗi job sinh ra một phần nội dung 1-2 câu AI Impact Analysis viết viết việc tác động của AI.

- Tóm tắt phản hồi của AI: Trả về một link dẫn đến google sheet với kết quả đầu ra về nội dung đúng 90% yêu cầu, trình bày không được chỉnh (thiếu dấu một số nơi, format lộn xộn).

## Log 04

- Mốc thời gian chính xác: `14:27 23/09/2026`
- Tên công cụ sử dụng: `Gemini tích hợp ở google sheet`
- Câu prompt gửi đi nguyên văn:

> Ở Cột F "Kỹ năng yêu cầu" phần nội dung từng dòng (chỉ áp dụng với tiếng việt), còn thiếu dấu, hãy sửa lại cho đúng tiếng việt có dấu.

- Tóm tắt phản hồi của AI: Chỉnh sửa lại đúng 100% tiếng việt có dấu.

## Log 05
- Mốc thời gian chính xác: `14:43 23/09/2026`
- Tên công cụ sử dụng: `Gemini`
- Câu prompt gửi đi nguyên văn:

> Vẽ cho tôi một sơ đồ tư duy (mindmap) bằng định dạng Mermaid thể hiện quy trình kiểm thử phần mềm theo chuẩn ISTQB Certified Tester Foundation Level (CTFL) mới nhất, bao gồm các vai trò và giai đoạn chính.

- Tóm tắt phản hồi của AI: Trả về đoạn mã code tạo sơ đồ tư duy Mermaid về quy trình và vai trò QA/QC theo chuẩn ISTQB CTFL.

## Log 06
- Mốc thời gian chính xác: `15:14 23/09/2026`
- Tên công cụ sử dụng: `Claude`
- Câu prompt gửi đi nguyên văn:

> Hãy đọc yêu cầu của đề bài này và tạo khung sườn cho báo cáo của tôi, yêu cầu rõ ràng, layout sạch sẽ và đơn giản. Trích xuất file docs

- Tóm tắt phản hồi của AI: Trả về một file docs với khung sườn có sẳn

## Log 07
- Mốc thời gian chính xác: `15:40 23/09/2026`
- Tên công cụ sử dụng: `Gemini`
- Câu prompt gửi đi nguyên văn:

>Hãy thực hiện tìm kiếm theo yêu cầu sau: 
>"Tìm 20 lỗi phần mềm (software defects) được công bố rộng rãi trong khoảng thời gian từ năm 2022 đến năm 2026.
>Bắt buộc: Có ít nhất 5 lỗi liên quan trực tiếp đến AI / LLM (ảo tưởng thông tin - hallucination, tấn công prompt injection, thiên vị dữ liệu - bias).
>Mỗi lỗi cần nêu rõ: Link nguồn tham khảo, mô tả chi tiết lỗi, mức độ nghiêm trọng (severity), hậu quả gây ra và giải pháp khắc phục."
>Sau khi tìm xong hãy tạo google bảng gồm các cột sau: STT, Tên sự cố & Link nguồn, Mô tả sự cố, Mức độ & Hậu quả, Hướng khắc phục.

- Tóm tắt phản hồi của AI: Trả về bảng thống kê chi tiết 20 sự cố phần mềm giai đoạn 2022–2026, bao gồm 6 sự cố đặc thù về AI/LLM và 14 lỗi phần mềm hệ thống lớn trên thế giới với đầy đủ link nguồn, phân tích mức độ nghiêm trọng và giải pháp khắc phục.

## Log 08
- Mốc thời gian chính xác: `13:36 26/09/2026`
- Tên công cụ sử dụng: `gemini`
- Câu prompt gửi đi nguyên văn:

>Hãy viết 15 test cases kiểm thử chức năng và phi chức năng cho thiết bị Quạt đứng hãn Senko LTS1636 (Quạt lửng 7 cánh) theo cấu trúc: ID, Objective, Input, Steps, Expected Result, Actual Result, Verdict.

- Tóm tắt phản hồi của AI: Trả về bảng 15 testcase đúng cấu trúc yêu cầu