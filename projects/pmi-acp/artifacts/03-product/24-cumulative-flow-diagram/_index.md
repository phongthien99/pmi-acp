---
title: "Cumulative Flow Diagram (CFD)"
weight: 202605091503
---

# Cumulative Flow Diagram (CFD)

## 📝 CUE & NOTES

| CUE | EN | VI |
|---|---|---|
| **What is it?** | A chart that shows how work flows through each stage of the process (Ready → Dev → Test → Deploy) over time. Each colored band represents one stage; the band's width = amount of work in that stage. | Biểu đồ hiển thị cách công việc chảy qua từng giai đoạn (Ready → Dev → Test → Deploy) theo thời gian. Mỗi dải màu đại diện một giai đoạn; độ rộng dải = lượng công việc trong giai đoạn đó. |
| **What is it used for?** | • Visualize work-in-progress across all stages at any point in time. • **Detect bottlenecks** before they cause major delays. • Track overall project progress toward completion. | • Trực quan hóa công việc đang thực hiện ở tất cả giai đoạn tại bất kỳ thời điểm nào. • **Phát hiện bottleneck** trước khi gây chậm trễ nghiêm trọng. • Theo dõi tiến độ tổng thể của dự án. |
| **When to use?** | When teams hand off work sequentially (e.g. Dev → Test → Deploy) and you need to spot where work is piling up or stalling. | Khi các nhóm bàn giao công việc tuần tự (vd: Dev → Test → Deploy) và cần phát hiện nơi công việc đang chồng chất hoặc đình trệ. |
| **Key Points** | 1. Work **flows downward**: Ready → Develop → Test → Deploy. 2. The **width** of a band at any point in time = how much work is in that stage. 3. A **widening band** = work is piling up there. 4. **Theory of Constraints**: the bottleneck is the stage **immediately after** the widening stage. 5. The widening stage itself is NOT the bottleneck — it's piling up *because the next stage isn't pulling work*. | 1. Công việc **chảy xuống**: Ready → Develop → Test → Deploy. 2. **Độ rộng** của một dải tại thời điểm bất kỳ = lượng công việc trong giai đoạn đó. 3. **Dải mở rộng** = công việc đang chồng chất ở đó. 4. **Lý thuyết Ràng buộc**: bottleneck là giai đoạn **ngay sau** giai đoạn mở rộng. 5. Bản thân giai đoạn mở rộng KHÔNG phải bottleneck — nó chồng chất *vì giai đoạn tiếp theo không kéo công việc*. |
| **Mental Model** | Think of a **highway with a tollbooth**: cars (work) keep entering the highway (Dev keeps taking from Ready), but the tollbooth (Testing) is slow → cars pile up BEFORE the toll. The pile-up is before Testing; the bottleneck IS Testing. | Hãy nghĩ như **đường cao tốc có trạm thu phí**: xe (công việc) liên tục vào đường (Dev liên tục lấy từ Ready), nhưng trạm thu phí (Testing) chậm → xe ùn lại TRƯỚC trạm. Ùn tắc xảy ra trước Testing; bottleneck CHÍNH LÀ Testing. |
| **Connections** | Relates to: **Kanban** (visualizing flow), **WIP limits** (preventing piling up), **Theory of Constraints** (find & fix the bottleneck), **Information Radiators** (CFD displayed visibly for the team). | Liên quan đến: **Kanban** (trực quan hóa dòng chảy), **WIP limits** (ngăn chồng chất), **Lý thuyết Ràng buộc** (tìm & sửa bottleneck), **Information Radiators** (CFD hiển thị cho nhóm thấy). |
| **Real-world Example** | Dev band widens massively through July. Testing band stays thin. → Developers keep pulling from Ready (blue shrinks) but testers aren't accepting work. **Bottleneck = Testing** (understaffed or under-skilled). Fix: add testers or train them. | Dải Dev mở rộng mạnh suốt tháng 7. Dải Testing vẫn mỏng. → Developers tiếp tục lấy từ Ready (blue co lại) nhưng testers không nhận công việc. **Bottleneck = Testing** (thiếu nhân lực hoặc thiếu kỹ năng). Cách sửa: thêm testers hoặc đào tạo họ. |
| **Pitfalls** | • Thinking the **widening stage** is the bottleneck — wrong, it's the stage **after** it. • Confusing band width with band height — width shows work *quantity*, not progress. • Ignoring CFD until late in the project — detect bottlenecks **early**. | • Nghĩ **giai đoạn mở rộng** là bottleneck — sai, đó là giai đoạn **sau** nó. • Nhầm độ rộng với độ cao của dải — độ rộng cho thấy *số lượng* công việc, không phải tiến độ. • Bỏ qua CFD cho đến cuối dự án — phát hiện bottleneck **sớm**. |
| **Exam Tips** | • Given a CFD, asked "where is the bottleneck?" → find the **widest/most growing band** → bottleneck is the band **right after** it. • Dev widening + Testing thin = **Testing is the bottleneck**. • Remember: Dev keeps taking from Ready (Ready shrinks) but won't hand off to Test → proof that Test is blocked. | • Được cho CFD, hỏi "bottleneck ở đâu?" → tìm **dải rộng nhất/tăng trưởng nhất** → bottleneck là dải **ngay sau** nó. • Dev mở rộng + Testing mỏng = **Testing là bottleneck**. • Nhớ: Dev tiếp tục lấy từ Ready (Ready co lại) nhưng không bàn giao cho Test → bằng chứng Test bị tắc nghẽn. |

---

## 📌 SUMMARY

| EN | VI |
|---|---|
| A **Cumulative Flow Diagram** visualizes how work moves through project stages over time, with each band's width showing how much work is in that stage. To find a **bottleneck**, apply the Theory of Constraints: the bottleneck is the stage **immediately after** the widening band — because it is not pulling work, causing the previous stage to pile up. | **Cumulative Flow Diagram** trực quan hóa cách công việc di chuyển qua các giai đoạn dự án theo thời gian, với độ rộng mỗi dải cho biết lượng công việc trong giai đoạn đó. Để tìm **bottleneck**, áp dụng Lý thuyết Ràng buộc: bottleneck là giai đoạn **ngay sau** dải mở rộng — vì nó không kéo công việc, khiến giai đoạn trước bị chồng chất. |

---

## ✅ SELF-CHECK

| EN | VI |
|---|---|
| How does work flow through a Cumulative Flow Diagram? | Công việc chảy như thế nào qua Cumulative Flow Diagram? |
| The Dev band is widening rapidly. Which stage is the bottleneck? | Dải Dev đang mở rộng nhanh. Giai đoạn nào là bottleneck? |
| What does the Theory of Constraints say about identifying a bottleneck in a CFD? | Lý thuyết Ràng buộc nói gì về việc xác định bottleneck trong CFD? |
| Why does the Ready band shrink even when there is a bottleneck in Testing? | Tại sao dải Ready co lại ngay cả khi có bottleneck ở Testing? |
