---
title: "Cost of Defects"
weight: 202605091210
---

# Cost of Defects / Chi phí lỗi sản phẩm

## 📝 CUE & NOTES

| CUE | EN | VI |
|---|---|---|
| **What is it?** | The principle that the **later a defect is discovered** in the development cycle, the **more expensive** it is to fix. Cost grows as the product matures. | Nguyên tắc: **càng phát hiện lỗi muộn** trong chu kỳ phát triển, **chi phí sửa càng cao**. Chi phí tăng dần khi sản phẩm càng hoàn thiện. |
| **Why does cost increase?** | As development progresses, more code/design is **built on top** of existing work. Fixing a defect deep in the stack requires unwinding and updating everything above it. | Khi phát triển tiến xa hơn, nhiều code/thiết kế được **xây chồng lên** công việc cũ. Sửa lỗi sâu trong stack đòi hỏi tháo gỡ và cập nhật tất cả những gì bên trên. |
| **Key Points** | **Cheapest → Most Expensive:** <br>1. Peer programming (caught live, ~$0 extra) <br>2. Continuous Integration (caught at code merge) <br>3. Test-Driven Development (caught during unit tests) <br>4. Reviewer / Customer Inspection (code is working, much more to unwind) <br>5. System Testing (entire system involved) <br>6. Design Defect (wrong language/platform — rebuild from scratch) <br>7. User Acceptance Testing (back to requirements) <br>8. **Production** (most expensive — recall, reputation loss, legal) | **Rẻ nhất → Đắt nhất:** <br>1. Peer programming (bắt ngay, ~$0 thêm) <br>2. Continuous Integration (bắt khi merge code) <br>3. Test-Driven Development (bắt trong unit test) <br>4. Reviewer / Customer Inspection (code đang chạy, nhiều thứ phải tháo) <br>5. System Testing (toàn hệ thống liên quan) <br>6. Design Defect (sai ngôn ngữ/nền tảng — làm lại từ đầu) <br>7. User Acceptance Testing (quay lại requirements) <br>8. **Production** (đắt nhất — thu hồi, mất uy tín, pháp lý) |
| **Mental Model** | Imagine building a house. A wrong measurement found **while drawing blueprints** costs nothing to erase. Found **after laying the foundation** costs concrete removal. Found **after the roof is on** costs demolishing the whole structure. Same defect — wildly different cost based on *when* it's caught. | Hình dung xây nhà. Sai số phát hiện **lúc vẽ bản thiết kế** không tốn gì để xóa. Phát hiện **sau khi đổ móng** tốn tiền đập bê tông. Phát hiện **sau khi lợp mái** tốn tiền phá toàn bộ. Cùng một lỗi — chi phí khác nhau hoàn toàn tùy *khi nào* phát hiện. |
| **When to use?** | Use this principle to justify investing in **early defect detection practices**: peer programming, CI/CD pipelines, TDD, and automated testing — all of which pay for themselves by catching defects cheap. | Dùng nguyên tắc này để biện minh cho việc đầu tư vào **thực hành phát hiện lỗi sớm**: peer programming, CI/CD, TDD, kiểm thử tự động — tất cả đều hoàn vốn bằng cách bắt lỗi khi còn rẻ. |
| **Connections** | Links to: **Peer Programming** (cheapest defect catcher) · **CI/CD** (automated early detection) · **TDD** (tests written before code) · **Shift Left Testing** (move testing earlier in the cycle) · **Technical Debt** (deferred defects compound over time). | Liên kết với: **Peer Programming** · **CI/CD** · **TDD** · **Shift Left Testing** (đưa kiểm thử về sớm hơn) · **Technical Debt** (lỗi tích lũy theo thời gian). |
| **Real-world Example** | Samsung Galaxy Note 7 (battery defect causing fires): defect discovered **after production & delivery**. Result: global recall, billions in losses, banned from airlines. If caught in design/testing phase, cost = fraction of the recall. | Samsung Galaxy Note 7 (lỗi pin gây cháy): lỗi phát hiện **sau khi sản xuất & bàn giao**. Kết quả: thu hồi toàn cầu, tổn thất hàng tỷ đô, bị cấm trên máy bay. Nếu phát hiện ở giai đoạn thiết kế/kiểm thử, chi phí chỉ là một phần nhỏ. |
| **Pitfalls** | • Thinking CI/TDD is "extra cost" — it's actually cost **prevention**. • Assuming defects only matter in software — applies to any product. • Underestimating cascade effect: one buried defect can invalidate layers of work built above it. | • Nghĩ CI/TDD là "chi phí thêm" — thực ra là **phòng ngừa** chi phí. • Giả sử lỗi chỉ quan trọng trong phần mềm — áp dụng cho mọi sản phẩm. • Đánh giá thấp hiệu ứng dây chuyền: một lỗi ẩn có thể làm vô hiệu nhiều lớp công việc bên trên. |
| **Exam Tips** | • "Cost of defects" questions: **earlier = cheaper**, always. • If a question asks which practice **best reduces defect cost** → peer programming or CI/CD is the answer. • "Defect found in production" = most expensive scenario — know this cold. | • Câu hỏi về "cost of defects": **càng sớm = càng rẻ**, luôn luôn. • Nếu câu hỏi hỏi thực hành nào **giảm chi phí lỗi tốt nhất** → peer programming hoặc CI/CD là đáp án. • "Lỗi phát hiện ở production" = kịch bản đắt nhất — nhớ chắc điều này. |

---

## 📌 SUMMARY

| EN | VI |
|---|---|
| The **cost of fixing defects rises dramatically** the later they are found in the development cycle — from near-zero during peer programming to billions in a product recall. Agile practices like **peer programming, CI, and TDD** exist specifically to catch defects as early (and cheaply) as possible. The key rule: **shift detection left** — find it early, fix it cheap. | **Chi phí sửa lỗi tăng mạnh** theo thời gian trong chu kỳ phát triển — từ gần bằng không khi peer programming đến hàng tỷ đô khi thu hồi sản phẩm. Các thực hành Agile như **peer programming, CI và TDD** được thiết kế để phát hiện lỗi sớm nhất (và rẻ nhất) có thể. Quy tắc cốt lõi: **đưa phát hiện về sớm** — tìm sớm, sửa rẻ. |

---

## ✅ SELF-CHECK

| EN | VI |
|---|---|
| List the defect discovery stages from cheapest to most expensive to fix. | Liệt kê các giai đoạn phát hiện lỗi từ rẻ nhất đến đắt nhất để sửa. |
| Why does a defect found during system testing cost more than one found during peer programming? | Tại sao lỗi phát hiện trong system testing tốn kém hơn lỗi phát hiện khi peer programming? |
| Name two Agile practices that help catch defects early and cheaply. | Kể tên hai thực hành Agile giúp phát hiện lỗi sớm và rẻ. |
| What real-world event illustrates the cost of a defect found after production? | Sự kiện thực tế nào minh họa chi phí của lỗi phát hiện sau khi sản xuất? |
