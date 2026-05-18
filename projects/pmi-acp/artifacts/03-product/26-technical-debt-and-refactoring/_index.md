---
title: "Technical Debt & Refactoring"
weight: 202605091505
---

# Technical Debt & Refactoring

## 📝 CUE & NOTES

| CUE | EN | VI |
|---|---|---|
| **What is Technical Debt?** | A **backlog of cleanup work** that accumulates when code is not regularly tidied — redundant code, unused functions, dead code, informal comments left in production. | **Tồn đọng công việc dọn dẹp** tích lũy khi code không được làm sạch thường xuyên — code thừa, hàm không dùng, code chết, comment không chính thức để lại trong production. |
| **What is Refactoring?** | The process of **reviewing and cleaning up existing code** — removing dead code, unused functions, leftover fields, and informal comments — without changing the software's external behavior. | Quá trình **xem xét và làm sạch code hiện có** — xóa code chết, hàm không dùng, trường còn sót, comment không chính thức — mà không thay đổi hành vi bên ngoài của phần mềm. |
| **What is it used for?** | **Technical debt**: tracks how much cleanup is owed. **Refactoring**: resolves that debt — keeps code lean, readable, and maintainable so future changes are cheaper and safer. | **Technical debt**: theo dõi lượng công việc dọn dẹp còn nợ. **Refactoring**: giải quyết khoản nợ đó — giữ code gọn, dễ đọc và dễ bảo trì để các thay đổi sau rẻ hơn và an toàn hơn. |
| **Key Points** | 1. Technical debt grows if ignored → increases development cost & slows change implementation. 2. **Refactoring = the solution** to technical debt. 3. Dead code = code that exists but does nothing (e.g. code for a deleted field that was never removed). 4. Informal comments (e.g. "Bob, check this") must be removed before production. 5. Regular refactoring prevents debt from becoming unmanageable. | 1. Technical debt tăng nếu bỏ qua → tăng chi phí phát triển & làm chậm việc thực hiện thay đổi. 2. **Refactoring = giải pháp** cho technical debt. 3. Dead code = code tồn tại nhưng không làm gì (vd: code cho trường đã xóa nhưng chưa được dọn). 4. Comment không chính thức (vd: "Bob, xem cái này") phải xóa trước khi lên production. 5. Refactoring thường xuyên ngăn nợ trở nên không kiểm soát được. |
| **Mental Model** | Technical debt = **clutter in a workshop**: the more tools and scraps left lying around, the harder it is to find what you need and the more likely you are to trip. Refactoring = **tidying the workshop** so every tool is where it belongs and nothing is in the way. | Technical debt = **đồ lộn xộn trong xưởng**: càng nhiều công cụ và vật liệu vứt lung tung, càng khó tìm thứ cần và càng dễ vấp. Refactoring = **dọn dẹp xưởng** để mọi công cụ đúng chỗ và không có gì cản trở. |
| **Connections** | Links to: **Product Backlog** (technical debt items can be added as backlog stories), **Definition of Done** (refactoring criteria can be part of DoD), **Continuous Integration** (regular code cleanup fits CI culture), **Code Reviews** (catch debt early). | Liên kết với: **Product Backlog** (các mục technical debt có thể thêm vào backlog), **Definition of Done** (tiêu chí refactoring có thể là một phần DoD), **Continuous Integration** (dọn dẹp code thường xuyên phù hợp văn hóa CI), **Code Reviews** (phát hiện nợ sớm). |
| **Real-world Example** | A dev team deletes a database field but forgets to remove the 200 lines of code referencing it. Over 6 months, similar leftovers accumulate. Adding a new feature now takes 3x longer because devs must navigate all the dead code. Refactoring session removes 40% of the codebase — feature delivery speeds up immediately. | Nhóm dev xóa một trường database nhưng quên xóa 200 dòng code tham chiếu đến nó. Sau 6 tháng, các tồn đọng tương tự tích lũy. Thêm tính năng mới giờ mất gấp 3 lần vì dev phải điều hướng qua tất cả code chết. Phiên refactoring xóa 40% codebase — tốc độ bàn giao tính năng tăng ngay lập tức. |
| **Pitfalls** | • Thinking technical debt only applies to bad developers — all teams accumulate it naturally during fast-paced development. • Confusing refactoring with rewriting — refactoring cleans without changing behavior; rewriting rebuilds from scratch. • Ignoring debt until it's critical — small regular cleanups are far cheaper than one massive overhaul. | • Nghĩ technical debt chỉ xảy ra với dev kém — tất cả các nhóm đều tích lũy nó một cách tự nhiên trong quá trình phát triển nhanh. • Nhầm refactoring với viết lại — refactoring làm sạch mà không thay đổi hành vi; viết lại xây dựng lại từ đầu. • Bỏ qua nợ cho đến khi nghiêm trọng — dọn dẹp nhỏ thường xuyên rẻ hơn nhiều so với một lần đại tu lớn. |
| **Exam Tips** | • **Technical debt** = accumulated cleanup backlog from not maintaining code. • **Refactoring** = the answer/solution when exam asks "how do you address technical debt?" • Exam may describe symptoms (slow feature delivery, buggy code, hard to change) → answer = refactor. • Refactoring does NOT add new features — it only cleans existing code. | • **Technical debt** = tồn đọng dọn dẹp tích lũy từ việc không bảo trì code. • **Refactoring** = câu trả lời/giải pháp khi đề hỏi "làm thế nào để giải quyết technical debt?" • Đề có thể mô tả triệu chứng (bàn giao chậm, code lỗi, khó thay đổi) → đáp án = refactor. • Refactoring KHÔNG thêm tính năng mới — chỉ làm sạch code hiện có. |

---

## 📌 SUMMARY

| EN | VI |
|---|---|
| **Technical debt** is the backlog of code cleanup work that accumulates when developers skip regular maintenance — leaving dead code, unused functions, and informal comments in the codebase. Left unaddressed, it increases costs and slows down future development. The solution is **refactoring**: systematically reviewing and removing all unnecessary code without changing the software's behavior. | **Technical debt** là tồn đọng công việc dọn dẹp code tích lũy khi developer bỏ qua bảo trì thường xuyên — để lại code chết, hàm không dùng và comment không chính thức trong codebase. Nếu không giải quyết, nó tăng chi phí và làm chậm phát triển sau này. Giải pháp là **refactoring**: xem xét và xóa có hệ thống tất cả code không cần thiết mà không thay đổi hành vi phần mềm. |

---

## ✅ SELF-CHECK

| EN | VI |
|---|---|
| What is technical debt and what causes it? | Technical debt là gì và nguyên nhân gây ra nó? |
| What is refactoring and how does it differ from rewriting code? | Refactoring là gì và nó khác viết lại code như thế nào? |
| What are two consequences of ignoring technical debt? | Hai hậu quả của việc bỏ qua technical debt là gì? |
| On the exam, if a question describes slow, bug-prone code that's hard to change, what is the likely answer? | Trong bài thi, nếu câu hỏi mô tả code chậm, nhiều lỗi và khó thay đổi, đáp án có khả năng là gì? |
