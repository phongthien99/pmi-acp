---
title: "Value-Based Prioritization"
weight: 202605181200
---

# Value-Based Prioritization / Ưu tiên hóa dựa trên Giá trị

## 📝 CUE & NOTES

| CUE | EN | VI |
|---|---|---|
| **What is it?** | The practice of ordering the **product backlog** so the most valuable features are built first. Features are ranked by **business value, risk, and dependencies** — not by ease of implementation. | Thực hành sắp xếp **product backlog** để tính năng có giá trị nhất được xây dựng trước. Tính năng được xếp hạng theo **giá trị kinh doanh, rủi ro và phụ thuộc** — không phải theo mức độ dễ thực hiện. |
| **Why does it matter?** | Without value-based prioritization, teams may build easy features first and deliver high-value features last — or never. Agile's core promise is **early delivery of the most valuable work**. | Không có ưu tiên hóa dựa trên giá trị, nhóm có thể xây tính năng dễ trước và giao tính năng có giá trị cao cuối — hoặc không bao giờ. Cam kết cốt lõi của Agile là **bàn giao sớm công việc có giá trị nhất**. |
| **Who prioritizes?** | Always the **customer / Product Owner** (Scrum) or **customer on-site** (XP). They use the product, so only they know what's truly most valuable. The team does not prioritize. | Luôn là **khách hàng / Product Owner** (Scrum) hoặc **khách hàng tại chỗ** (XP). Họ dùng sản phẩm nên chỉ họ biết điều gì thực sự có giá trị nhất. Nhóm không ưu tiên hóa. |
| **Method 1: Simple Scheme** | Customers sit down and rank features: #1, #2, #3… Simplest method. Can create chaos if stakeholders disagree or there are many features. | Khách hàng ngồi xuống và xếp hạng tính năng: #1, #2, #3… Phương pháp đơn giản nhất. Có thể gây hỗn loạn nếu stakeholder không đồng ý hoặc có nhiều tính năng. |
| **Method 2: MoSCoW** | **M**ust have (fails without it) · **S**hould have (interrupts if missing) · **C**ould have (nice to have, adds value) · **W**ould like (defer to later if needed). Musts → top, Would-likes → bottom. | **M**ust have (thất bại nếu thiếu) · **S**hould have (gián đoạn nếu thiếu) · **C**ould have (tốt khi có, thêm giá trị) · **W**ould like (hoãn lại nếu cần). Must → đầu, Would-like → cuối. |
| **Method 3: Dot Voting** | Each participant gets a set number of dots (e.g. 50). Allocate dots to features based on importance. Feature with the **most dots** rises to the top of the backlog. | Mỗi người nhận một số dot nhất định (vd. 50). Phân bổ dot cho tính năng theo mức độ quan trọng. Tính năng có **nhiều dot nhất** lên đầu backlog. |
| **Method 4: 100 Point Method** | Same as dot voting but each person gets **100 points** to allocate. Points can be distributed unevenly (e.g. 50 on one feature, 1 on another). Higher total points = higher priority. | Giống dot voting nhưng mỗi người nhận **100 điểm** để phân bổ. Điểm có thể phân bổ không đều (vd. 50 cho một tính năng, 1 cho tính năng khác). Tổng điểm cao hơn = ưu tiên cao hơn. |
| **Method 5: Monopoly Money** | Give stakeholders fake money equal to the **project budget**. They "spend" money on features based on perceived value. Forces realistic trade-offs since the total budget is fixed. | Cho stakeholder tiền giả bằng **ngân sách dự án**. Họ "chi tiêu" tiền cho tính năng dựa trên giá trị cảm nhận. Buộc phải đánh đổi thực tế vì tổng ngân sách cố định. |
| **Method 6: Kano Analysis** | Categorizes features into 3 types: **Delighters/Exciters** (missing = neutral, present = delight) · **Satisfiers** (more = better, core value) · **Dissatisfiers/Basic needs** (missing = angry, present = neutral — e.g. password reset). | Phân loại tính năng thành 3 loại: **Delighters** (thiếu = bình thường, có = thích thú) · **Satisfiers** (càng nhiều càng tốt, giá trị cốt lõi) · **Dissatisfiers** (thiếu = bực bội, có = bình thường — vd. đặt lại mật khẩu). |
| **Mental Model** | Prioritization is like a **restaurant menu in a tasting menu format** — the chef (team) serves dishes in the order the chef knows will deliver the best experience. But the customer decides which dishes matter most. Without their input, the chef might serve dessert first and the main course last. | Ưu tiên hóa giống như **thực đơn theo thứ tự phục vụ** — đầu bếp (nhóm) phục vụ món theo thứ tự. Nhưng khách hàng quyết định món nào quan trọng nhất. Không có ý kiến của họ, đầu bếp có thể phục vụ tráng miệng trước và món chính cuối. |
| **Connections** | Links to: **Product Backlog** (what gets prioritized) · **Sprint Planning** (team picks top items) · **Collaboration Games** (Prune the Tree also prioritizes features) · **Value Delivery** (core agile principle) · **Product Owner role** (owns the prioritized backlog). | Liên kết với: **Product Backlog** (cái được ưu tiên hóa) · **Sprint Planning** (nhóm chọn item đầu danh sách) · **Collaboration Games** (Prune the Tree cũng ưu tiên tính năng) · **Bàn giao Giá trị** (nguyên tắc Agile cốt lõi) · **Vai trò Product Owner** (sở hữu backlog đã ưu tiên). |
| **Real-world Example** | An accounting software team has 20 features. Without prioritization, devs build "export to Excel" (easy) first. With MoSCoW: "invoice creation" is a Must, "export to Excel" is a Could. Team builds invoicing first — customers get value from sprint 1. | Nhóm phần mềm kế toán có 20 tính năng. Không ưu tiên hóa: dev xây "xuất Excel" (dễ) trước. Với MoSCoW: "tạo hóa đơn" là Must, "xuất Excel" là Could. Nhóm xây hóa đơn trước — khách hàng có giá trị từ sprint 1. |
| **Pitfalls** | • Team prioritizing instead of the customer — **wrong**. • Prioritizing by ease/speed instead of value — defeats agile's purpose. • Confusing MoSCoW letters: **M=Must, S=Should, C=Could, W=Would like** (not "Won't"). • Kano: dissatisfiers (basic needs) don't add delight when present — only hurt when absent. | • Nhóm ưu tiên hóa thay vì khách hàng — **sai**. • Ưu tiên theo mức độ dễ/nhanh thay vì giá trị — phá vỡ mục đích Agile. • Nhầm chữ MoSCoW: **M=Must, S=Should, C=Could, W=Would like** (không phải "Won't"). • Kano: dissatisfiers không tạo niềm vui khi có — chỉ gây đau khi thiếu. |
| **Exam Tips** | • "Who prioritizes the backlog?" → always **Product Owner / Customer**, never the team. • MoSCoW order on backlog: Must → Should → Could → Would like. • Dot voting = dots · 100-point method = points — both produce same outcome (ranked list). • Kano dissatisfier example: password reset — **no joy when present, frustration when absent**. | • "Ai ưu tiên hóa backlog?" → luôn là **Product Owner / Khách hàng**, không bao giờ là nhóm. • Thứ tự MoSCoW trên backlog: Must → Should → Could → Would like. • Dot voting = dot · 100-point = điểm — cả hai cho kết quả giống nhau (danh sách xếp hạng). • Kano dissatisfier ví dụ: đặt lại mật khẩu — **không vui khi có, bực bội khi thiếu**. |

---

## 📌 SUMMARY

| EN | VI |
|---|---|
| **Value-based prioritization** ensures the team always builds the most valuable features first by having the **customer/Product Owner** rank the product backlog. Methods range from simple ranking to MoSCoW, dot voting, 100-point, monopoly money, and Kano analysis — all producing the same output: a **prioritized backlog**. Without it, teams risk delivering low-value work early and high-value work late or never. | **Ưu tiên hóa dựa trên giá trị** đảm bảo nhóm luôn xây tính năng có giá trị nhất trước bằng cách để **khách hàng/Product Owner** xếp hạng product backlog. Các phương pháp từ xếp hạng đơn giản đến MoSCoW, dot voting, 100-point, monopoly money và Kano — tất cả tạo ra cùng một đầu ra: **backlog được ưu tiên hóa**. Không có nó, nhóm có nguy cơ bàn giao công việc ít giá trị sớm và công việc có giá trị cao muộn hoặc không bao giờ. |

---

## ✅ SELF-CHECK

| EN | VI |
|---|---|
| Who is responsible for prioritizing the product backlog, and why? | Ai chịu trách nhiệm ưu tiên hóa product backlog và tại sao? |
| What do the letters in MoSCoW stand for, and what order do they appear on the backlog? | Các chữ trong MoSCoW viết tắt của gì và chúng xuất hiện theo thứ tự nào trên backlog? |
| How does dot voting work, and how is it similar to the 100-point method? | Dot voting hoạt động như thế nào và nó tương tự với 100-point method ở điểm nào? |
| In Kano analysis, what is a "dissatisfier"? Give one example. | Trong Kano analysis, "dissatisfier" là gì? Cho một ví dụ. |
