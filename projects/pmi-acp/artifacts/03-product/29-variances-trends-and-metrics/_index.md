---
title: "Variances, Trends & Metrics (Lagging vs Leading)"
weight: 202605091508
---

# Variances, Trends & Metrics (Lagging vs Leading)

## 📝 CUE & NOTES

| CUE | EN | VI |
|---|---|---|
| **What is a Variance?** | A **measure of how far actual results deviate from the plan** — used to track deviations in cost, time, or story points. Variance = Actual − Planned. | **Đo lường mức độ kết quả thực tế lệch so với kế hoạch** — dùng để theo dõi độ lệch về chi phí, thời gian hoặc story points. Variance = Thực tế − Kế hoạch. |
| **What is a Trend?** | A **pattern that emerges from multiple variances over time**, used to predict future outcomes. Where is performance heading? | **Mô hình xuất hiện từ nhiều variance theo thời gian**, dùng để dự đoán kết quả tương lai. Hiệu suất đang đi về đâu? |
| **What is a Lagging Metric?** | A metric that **reflects what has already happened** — historical data. Examples: story points completed last sprint, number of defects found last 3 sprints. Tells you what *did* happen. | Chỉ số **phản ánh những gì đã xảy ra** — dữ liệu lịch sử. Ví dụ: story points hoàn thành sprint trước, số lỗi tìm thấy trong 3 sprint qua. Cho biết điều gì *đã* xảy ra. |
| **What is a Leading Metric?** | A metric that **indicates what is currently happening or about to happen** — used for early warning and forecasting. Examples: tasks currently in progress, WIP nearing limits. Tells you what *will* happen. | Chỉ số **cho biết điều đang xảy ra hoặc sắp xảy ra** — dùng để cảnh báo sớm và dự báo. Ví dụ: số nhiệm vụ đang thực hiện, WIP gần đến giới hạn. Cho biết điều gì *sẽ* xảy ra. |
| **Key Points** | 1. **Variance** = single data point of deviation. **Trend** = pattern across multiple variances over time. 2. Small variance = minor issue. Large or growing variance = investigate immediately. 3. Variance can be positive (did MORE than planned) or negative (did LESS). 4. **Lagging** = rear-view mirror (what happened). **Leading** = windshield (what's coming). 5. Trends visible in: burn up/down charts, velocity charts, defect counts over sprints. | 1. **Variance** = điểm dữ liệu đơn lẻ về độ lệch. **Trend** = mô hình qua nhiều variance theo thời gian. 2. Variance nhỏ = vấn đề nhỏ. Variance lớn hoặc tăng = điều tra ngay. 3. Variance có thể dương (làm NHIỀU hơn kế hoạch) hoặc âm (làm ÍT hơn). 4. **Lagging** = gương chiếu hậu (điều đã xảy ra). **Leading** = kính chắn gió (điều sắp đến). 5. Trends hiển thị trong: biểu đồ burn up/down, velocity chart, số lỗi qua các sprint. |
| **Mental Model** | Variance = **one weather reading** (today it's 5°C colder than normal). Trend = **5-day forecast** (it's been getting colder each day — predict snow by Friday). Lagging = **yesterday's weather report**. Leading = **tomorrow's weather forecast**. | Variance = **một lần đo thời tiết** (hôm nay lạnh hơn bình thường 5°C). Trend = **dự báo 5 ngày** (mỗi ngày lạnh hơn — dự đoán tuyết vào thứ Sáu). Lagging = **bản tin thời tiết hôm qua**. Leading = **dự báo thời tiết ngày mai**. |
| **Connections** | Links to: **Velocity Chart** (shows velocity trend across sprints), **Burn Up/Down** (shows progress trend), **Retrospective** (where variance is discussed and acted on), **CFD** (shows flow trends), **Risk Management** (leading metrics trigger early risk responses). | Liên kết với: **Velocity Chart** (hiển thị xu hướng velocity qua các sprint), **Burn Up/Down** (hiển thị xu hướng tiến độ), **Retrospective** (nơi variance được thảo luận và hành động), **CFD** (hiển thị xu hướng dòng chảy), **Quản lý rủi ro** (leading metrics kích hoạt phản hồi rủi ro sớm). |
| **Real-world Example** | Team was expected to do 60 pts/sprint. Results: Sprint 1 = 60, Sprint 2 = 55, Sprint 3 = 50, Sprint 4 = 45. Each sprint has a variance of −5. The **trend** = declining velocity. Root cause investigation reveals 2 team members started summer vacation. PM adjusts planned points for summer sprints proactively. | Nhóm dự kiến 60 điểm/sprint. Kết quả: Sprint 1 = 60, Sprint 2 = 55, Sprint 3 = 50, Sprint 4 = 45. Mỗi sprint có variance −5. **Trend** = velocity giảm dần. Điều tra nguyên nhân gốc rễ phát hiện 2 thành viên bắt đầu nghỉ hè. PM điều chỉnh chủ động số điểm kế hoạch cho các sprint mùa hè. |
| **Pitfalls** | • Reacting to a single variance without looking for a trend — one bad sprint ≠ a problem; three bad sprints = investigate. • Confusing lagging (historical) with leading (predictive) metrics. • Only tracking negative variances — positive variances (overperformance) also need analysis: *what did we do right?* • Ignoring seasonal/recurring trends (e.g. summer slowdowns happen every year). | • Phản ứng với một variance đơn lẻ mà không tìm trend — một sprint xấu ≠ vấn đề; ba sprint xấu = điều tra. • Nhầm lagging (lịch sử) với leading (dự đoán). • Chỉ theo dõi variance âm — variance dương (vượt hiệu suất) cũng cần phân tích: *chúng ta đã làm gì đúng?* • Bỏ qua các trend theo mùa/định kỳ (vd: chậm lại mùa hè xảy ra mỗi năm). |
| **Exam Tips** | • **Variance** = deviation from plan (cost or schedule). **Trend** = pattern of variances over time. • **Lagging metric** = past data (story points done, defects found). **Leading metric** = current/predictive data (WIP count, tasks in progress). • If exam shows velocity dropping each sprint → identify the **trend** and investigate root cause. • Positive variance (better than planned) should also be analyzed in **retrospective** to repeat success. | • **Variance** = độ lệch so với kế hoạch (chi phí hoặc lịch trình). **Trend** = mô hình của các variance theo thời gian. • **Lagging metric** = dữ liệu quá khứ (story points xong, lỗi tìm thấy). **Leading metric** = dữ liệu hiện tại/dự đoán (số WIP, nhiệm vụ đang thực hiện). • Nếu đề cho thấy velocity giảm mỗi sprint → xác định **trend** và điều tra nguyên nhân gốc rễ. • Variance dương (tốt hơn kế hoạch) cũng nên được phân tích trong **retrospective** để lặp lại thành công. |

---

## 📌 SUMMARY

| EN | VI |
|---|---|
| A **variance** measures how far actual results deviate from the plan (e.g. spent $12K vs planned $10K = $2K variance). When variances are tracked over time, they reveal **trends** — patterns that help predict future performance. **Lagging metrics** describe what already happened (rear-view), while **leading metrics** indicate what is currently happening or about to happen (windshield). Together, these tools give project managers the ability to anticipate problems and act before they escalate. | **Variance** đo lường mức độ kết quả thực tế lệch so với kế hoạch (vd: chi $12K so với $10K = variance $2K). Khi variance được theo dõi theo thời gian, chúng tiết lộ **trend** — các mô hình giúp dự đoán hiệu suất tương lai. **Lagging metrics** mô tả điều đã xảy ra (gương chiếu hậu), trong khi **leading metrics** chỉ ra điều đang hoặc sắp xảy ra (kính chắn gió). Cùng nhau, những công cụ này giúp PM dự đoán vấn đề và hành động trước khi chúng leo thang. |

---

## ✅ SELF-CHECK

| EN | VI |
|---|---|
| What is the difference between a variance and a trend? | Sự khác nhau giữa variance và trend là gì? |
| Give one example each of a lagging metric and a leading metric. | Cho một ví dụ về lagging metric và một ví dụ về leading metric. |
| Velocity over 4 sprints: 60, 52, 45, 38. What does this trend indicate and what should the PM do? | Velocity qua 4 sprint: 60, 52, 45, 38. Trend này cho thấy điều gì và PM nên làm gì? |
| Why should a PM also investigate a positive variance, not just negative ones? | Tại sao PM cũng nên điều tra variance dương, không chỉ variance âm? |
