---
title: "Lead Time vs Cycle Time"
weight: 202605181200
---

# Lead Time vs Cycle Time

## 📝 CUE & NOTES

| CUE | EN | VI |
|---|---|---|
| **What is it?** | **Lead Time**: Total time from the very start to the very end of a process. **Cycle Time**: Time to complete one specific part (step) within that process. | **Lead Time**: Tổng thời gian từ đầu đến cuối toàn bộ quy trình. **Cycle Time**: Thời gian hoàn thành một bước/phần cụ thể trong quy trình đó. |
| **What is it used for?** | Used to measure overall process duration (lead time) and the efficiency of individual steps (cycle time). Helps identify bottlenecks and optimize workflow. | Đo lường thời gian toàn bộ quy trình (lead time) và hiệu quả của từng bước (cycle time). Giúp xác định điểm nghẽn và tối ưu luồng công việc. |
| **When to use?** | Use lead time when evaluating end-to-end delivery (e.g., how long to ship a feature). Use cycle time when analyzing the efficiency of a specific step or task (e.g., how long to build one user story). | Dùng lead time khi đánh giá toàn bộ quá trình giao hàng. Dùng cycle time khi phân tích hiệu quả của một bước cụ thể hay một task. |
| **Key Points** | • Cycle time is always **part of** lead time — never greater than lead time. <br>• Shorter cycle time = more efficient step = higher throughput. <br>• Excessive Work in Progress (WIP) increases cycle time. <br>• Reducing cycle time allows more work to be completed in the same period. <br>• Cycle time is directly related to WIP via **Little's Law**. | • Cycle time luôn là **một phần của** lead time — không bao giờ lớn hơn. <br>• Cycle time ngắn hơn = bước hiệu quả hơn = thông lượng cao hơn. <br>• WIP (công việc đang làm dở) quá nhiều làm tăng cycle time. <br>• Giảm cycle time giúp hoàn thành nhiều việc hơn trong cùng thời gian. <br>• Cycle time liên quan trực tiếp đến WIP qua **Định luật Little**. |
| **Mental Model** | Think of a restaurant: **Lead time** = time from when you order to when you finish your meal and leave. **Cycle time** = time just to cook your dish in the kitchen. The kitchen's cooking time is one cycle inside the whole dining experience. | Hãy nghĩ đến nhà hàng: **Lead time** = từ lúc bạn gọi món đến lúc bạn ăn xong và rời đi. **Cycle time** = chỉ thời gian bếp nấu món ăn của bạn. Thời gian nấu là một chu kỳ nằm trong toàn bộ trải nghiệm dùng bữa. |
| **Connections** | **vs. Throughput**: Throughput is how many items are completed per unit of time; cycle time is how long one item takes. Linked by Little's Law: `WIP = Throughput × Cycle Time`. <br>**vs. WIP**: High WIP → longer cycle time → slower delivery. | **vs. Throughput**: Throughput là số lượng hoàn thành trong một đơn vị thời gian; cycle time là thời gian hoàn thành một đơn vị. Liên kết qua Định luật Little: `WIP = Throughput × Cycle Time`. <br>**vs. WIP**: WIP cao → cycle time dài → giao hàng chậm. |
| **Real-world Example** | **PMP Exam Prep (100 hrs total = Lead Time):** <br>• Course: 35 hrs (cycle time for this step) <br>• Practice tests: 30 hrs <br>• Review notes: 20 hrs <br>• Mindset prep: 10 hrs <br>**Car manufacturing (Lead Time = 50 hrs):** <br>• Build frame: 10 hrs (cycle time for frame step) | **Ôn thi PMP (100 giờ tổng = Lead Time):** <br>• Học khóa học: 35 giờ (cycle time bước này) <br>• Làm đề thi thử: 30 giờ <br>• Ôn lại ghi chú: 20 giờ <br>• Rèn tư duy: 10 giờ <br>**Sản xuất ô tô (Lead Time = 50 giờ):** <br>• Làm khung xe: 10 giờ (cycle time bước làm khung) |
| **Pitfalls** | • Confusing cycle time with lead time — remember: **cycle time is a subset, lead time is the whole**. <br>• Thinking reducing lead time always means reducing every step equally — focus on the bottleneck step. <br>• Ignoring WIP impact: adding more parallel tasks increases WIP and *increases* cycle time, slowing you down. | • Nhầm cycle time với lead time — nhớ: **cycle time là một phần, lead time là toàn bộ**. <br>• Nghĩ rằng giảm lead time nghĩa là giảm đều mọi bước — hãy tập trung vào bước nút thắt cổ chai. <br>• Bỏ qua tác động của WIP: làm nhiều việc song song tăng WIP và *tăng* cycle time, khiến bạn chậm lại. |
| **Exam Tips** | • Questions may give a multi-step process and ask you to identify lead time vs cycle time for a specific step. <br>• Watch for Little's Law calculation questions: `Cycle Time = WIP ÷ Throughput`. <br>• "Time to complete the entire project/product backlog" = **Lead Time**. <br>• "Time to complete one user story/feature" = **Cycle Time**. | • Đề thi có thể cho một quy trình nhiều bước và hỏi lead time hay cycle time của một bước cụ thể. <br>• Chú ý câu hỏi tính toán Định luật Little: `Cycle Time = WIP ÷ Throughput`. <br>• "Thời gian hoàn thành toàn bộ dự án/product backlog" = **Lead Time**. <br>• "Thời gian hoàn thành một user story/tính năng" = **Cycle Time**. |

---

## 📌 SUMMARY

| EN | VI |
|---|---|
| **Lead time** is the total time from start to finish of an entire process, while **cycle time** is the time to complete one specific step within that process — cycle time is always a part of lead time. Keeping cycle times short reduces waste, limits excessive WIP, and increases team throughput. The key thing to remember: reducing cycle time (individual step efficiency) is how agile teams improve overall lead time (delivery speed). | **Lead time** là tổng thời gian từ đầu đến cuối toàn bộ quy trình, còn **cycle time** là thời gian hoàn thành một bước cụ thể trong quy trình đó — cycle time luôn là một phần của lead time. Giữ cycle time ngắn giúp giảm lãng phí, hạn chế WIP quá mức và tăng thông lượng nhóm. Điều quan trọng nhất cần nhớ: giảm cycle time (hiệu quả từng bước) chính là cách các nhóm agile cải thiện lead time tổng thể (tốc độ giao hàng). |

---

## ✅ SELF-CHECK

| EN | VI |
|---|---|
| A product backlog has 5 stories. The team takes 1 year to finish all 5, and 2 months to finish one story. What is the lead time? What is the cycle time? | Product backlog có 5 story. Nhóm mất 1 năm để hoàn thành tất cả 5 story, và 2 tháng để hoàn thành một story. Lead time là bao nhiêu? Cycle time là bao nhiêu? |
| True or False: Cycle time can be longer than lead time. | Đúng hay Sai: Cycle time có thể dài hơn lead time. |
| How does increasing Work in Progress (WIP) affect cycle time? | Tăng Work in Progress (WIP) ảnh hưởng đến cycle time như thế nào? |
