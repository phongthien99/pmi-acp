---
title: "Little's Law"
weight: 202605181210
---

# Little's Law / Định luật Little

## 📝 CUE & NOTES

| CUE | EN | VI |
|---|---|---|
| **What is it?** | A formula that describes the relationship between **Work in Progress (WIP)**, **Throughput**, and **Cycle Time** in any stable system. Used by agile teams to forecast delivery and optimize flow. | Công thức mô tả mối quan hệ giữa **Work in Progress (WIP)**, **Throughput** và **Cycle Time** trong bất kỳ hệ thống ổn định nào. Dùng để dự báo bàn giao và tối ưu luồng làm việc Agile. |
| **3 Variables** | **WIP** = total work to be done (e.g. 10 stories in backlog). **Throughput** = how fast work is completed (e.g. 5 stories/week). **Cycle Time** = how long to finish all work (e.g. 2 weeks). | **WIP** = tổng công việc cần làm (vd. 10 story trong backlog). **Throughput** = tốc độ hoàn thành công việc (vd. 5 story/tuần). **Cycle Time** = thời gian hoàn thành toàn bộ công việc (vd. 2 tuần). |
| **The 3 Formula Variants** | **WIP = Throughput × Cycle Time** · **Cycle Time = WIP ÷ Throughput** · **Throughput = WIP ÷ Cycle Time** — Same formula, rearranged. Use whichever variable you need to solve for. | **WIP = Throughput × Cycle Time** · **Cycle Time = WIP ÷ Throughput** · **Throughput = WIP ÷ Cycle Time** — Cùng một công thức, sắp xếp lại. Dùng biến thể nào phù hợp với ẩn số cần tìm. |
| **When to use?** | Use to **forecast delivery time** (how long to finish all stories), **calculate throughput** (how many tasks per period), or **find WIP** (how much can the team handle in a given timeframe). | Dùng để **dự báo thời gian bàn giao** (mất bao lâu hoàn thành tất cả story), **tính throughput** (bao nhiêu task mỗi kỳ), hoặc **tìm WIP** (nhóm có thể xử lý bao nhiêu trong một khoảng thời gian). |
| **Key Points** | • Exam will give you 2 of the 3 variables — solve for the third. • The formula can be presented in any of the 3 arrangements. • Reducing WIP = faster cycle time. Increasing throughput = faster delivery. • Used heavily in **Kanban** for flow optimization and WIP limits. | • Đề thi sẽ cho 2 trong 3 biến — giải tìm biến còn lại. • Công thức có thể xuất hiện dưới dạng bất kỳ trong 3 cách sắp xếp. • Giảm WIP = cycle time nhanh hơn. Tăng throughput = bàn giao nhanh hơn. • Dùng nhiều trong **Kanban** để tối ưu luồng và giới hạn WIP. |
| **Mental Model** | Think of a **highway**: WIP = number of cars on the road, Throughput = cars exiting per hour, Cycle Time = how long it takes to cross the entire highway. More cars (↑WIP) with same exits (same throughput) = longer crossing time (↑Cycle Time). | Hình dung một **đường cao tốc**: WIP = số xe trên đường, Throughput = xe ra mỗi giờ, Cycle Time = thời gian để vượt toàn bộ đường cao tốc. Nhiều xe hơn (↑WIP) với cùng số cổng ra (throughput) = thời gian qua dài hơn (↑Cycle Time). |
| **Connections** | Links to: **Kanban** (WIP limits directly apply Little's Law) · **Velocity** (throughput per sprint) · **Product Backlog** (WIP = total stories) · **Burn-down chart** (visualizes cycle time progress) · **Flow efficiency** (optimize by balancing all 3 variables). | Liên kết với: **Kanban** (giới hạn WIP áp dụng trực tiếp Little's Law) · **Velocity** (throughput mỗi sprint) · **Product Backlog** (WIP = tổng story) · **Burn-down chart** (trực quan hóa tiến độ cycle time) · **Hiệu quả luồng**. |
| **Real-world Example** | **Example 1 — Forecast:** Team has 10 stories, throughput = 5/week → Cycle Time = 10÷5 = **2 weeks**. **Example 2 — Throughput:** 12 tasks done in 6 days → Throughput = 12÷6 = **2 tasks/day**. **Example 3 — WIP:** 4 tasks/day × 3-day cycle = **12 tasks WIP**. | **Ví dụ 1 — Dự báo:** Nhóm có 10 story, throughput = 5/tuần → Cycle Time = 10÷5 = **2 tuần**. **Ví dụ 2 — Throughput:** 12 task xong trong 6 ngày → Throughput = 12÷6 = **2 task/ngày**. **Ví dụ 3 — WIP:** 4 task/ngày × 3 ngày = **12 task WIP**. |
| **Pitfalls** | • Confusing **Cycle Time** (how long to finish ALL work) with time to finish ONE item. • Forgetting which formula variant to use — identify what's given and what's missing first. • Thinking it's complex — it's just division/multiplication of 3 variables. | • Nhầm **Cycle Time** (thời gian hoàn thành TẤT CẢ công việc) với thời gian hoàn thành MỘT item. • Quên dùng biến thể công thức nào — xác định cái đã biết và cái cần tìm trước. • Nghĩ nó phức tạp — chỉ là phép chia/nhân của 3 biến. |
| **Exam Tips** | • **One formula, 3 arrangements** — identify the unknown variable, then pick the right form. • Exam often gives a Kanban scenario with 2 known values → calculate the third. • "How long will it take?" → solve for **Cycle Time = WIP ÷ Throughput**. • "How fast is the team?" → solve for **Throughput = WIP ÷ Cycle Time**. • "How much work?" → solve for **WIP = Throughput × Cycle Time**. | • **Một công thức, 3 dạng** — xác định ẩn số, rồi chọn dạng phù hợp. • Đề thi thường cho tình huống Kanban với 2 giá trị đã biết → tính giá trị thứ ba. • "Mất bao lâu?" → tính **Cycle Time = WIP ÷ Throughput**. • "Nhóm làm nhanh cỡ nào?" → tính **Throughput = WIP ÷ Cycle Time**. • "Bao nhiêu công việc?" → tính **WIP = Throughput × Cycle Time**. |

---

## 📌 SUMMARY

| EN | VI |
|---|---|
| **Little's Law** connects three variables: **WIP** (total work), **Throughput** (work completed per period), and **Cycle Time** (time to finish all work) via the formula **WIP = Throughput × Cycle Time**. Rearrange to solve for whichever variable is unknown. On the exam, identify what's given, pick the right arrangement, and calculate — it's always simple arithmetic. | **Định luật Little** kết nối ba biến: **WIP** (tổng công việc), **Throughput** (công việc hoàn thành mỗi kỳ) và **Cycle Time** (thời gian hoàn thành tất cả công việc) qua công thức **WIP = Throughput × Cycle Time**. Sắp xếp lại để tìm biến còn thiếu. Trong đề thi, xác định cái đã cho, chọn dạng phù hợp và tính toán — luôn là phép tính đơn giản. |

---

## ✅ SELF-CHECK

| EN | VI |
|---|---|
| A team has 20 user stories and completes 4 per week. How long will it take to finish? | Một nhóm có 20 user story và hoàn thành 4 mỗi tuần. Mất bao lâu để xong? |
| A team finishes 15 tasks in 5 days. What is their throughput per day? | Một nhóm hoàn thành 15 task trong 5 ngày. Throughput mỗi ngày là bao nhiêu? |
| A Kanban team has a throughput of 6 tasks/day and a cycle time of 4 days. What is the WIP? | Một nhóm Kanban có throughput 6 task/ngày và cycle time 4 ngày. WIP là bao nhiêu? |
| What happens to Cycle Time if you reduce WIP while keeping Throughput constant? | Điều gì xảy ra với Cycle Time nếu bạn giảm WIP trong khi giữ Throughput không đổi? |
