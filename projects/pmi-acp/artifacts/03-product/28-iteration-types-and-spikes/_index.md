---
title: "Types of Iterations & Spikes"
weight: 202605091507
---

# Types of Iterations & Spikes

## 📝 CUE & NOTES

| CUE | EN | VI |
|---|---|---|
| **What are the 3 iteration types?** | **Iteration 0** (setup/no output) → **Development Iteration** (builds product) → **Iteration H** (hardening/cleanup). | **Iteration 0** (cài đặt/không có đầu ra) → **Development Iteration** (xây dựng sản phẩm) → **Iteration H** (hardening/dọn dẹp). |
| **Iteration 0** | The **setup iteration** before real work begins. No product is built. Used to: prepare the environment, establish the backlog, set up tools, and plan the first sprint. | **Iteration thiết lập** trước khi công việc thực sự bắt đầu. Không xây dựng sản phẩm. Dùng để: chuẩn bị môi trường, thiết lập backlog, cài đặt công cụ và lập kế hoạch sprint đầu tiên. |
| **Development Iteration** | The **core sprint** where the team builds the actual product — coding, testing, integrating. This is where story points are burned and features are delivered. | **Sprint cốt lõi** nơi nhóm xây dựng sản phẩm thực sự — lập trình, kiểm thử, tích hợp. Đây là nơi story points được tiêu thụ và tính năng được bàn giao. |
| **Iteration H** | The **hardening/release sprint** at the end. H = Hardening. No new features — only: code cleanup (remove redundant/dead code, comments), documentation, and preparation for release. | **Sprint hardening/phát hành** ở cuối. H = Hardening. Không có tính năng mới — chỉ: dọn dẹp code (xóa code thừa/chết, comment), tài liệu hóa và chuẩn bị phát hành. |
| **What is a Spike?** | A **short time-boxed investigation** (a few hours) done during or before an iteration to **test a theory or proof of concept** — not to build a feature. | **Điều tra ngắn có timebox** (vài giờ) thực hiện trong hoặc trước một iteration để **kiểm tra lý thuyết hoặc proof of concept** — không phải để xây dựng tính năng. |
| **Architectural Spike** | Tests whether a **technology or function can deliver the desired result** before the team commits to building with it. Prevents discovering mid-sprint that a core tool doesn't work. | Kiểm tra xem **công nghệ hoặc hàm có thể cung cấp kết quả mong muốn** trước khi nhóm cam kết xây dựng với nó. Ngăn phát hiện giữa sprint rằng một công cụ cốt lõi không hoạt động. |
| **Risk-Based Spike** | Tests a **contingency/fallback plan** to confirm it would work if a specific risk occurs. Validates the risk response before it's needed. | Kiểm tra **kế hoạch dự phòng/phương án thay thế** để xác nhận nó sẽ hoạt động nếu một rủi ro cụ thể xảy ra. Xác nhận phản hồi rủi ro trước khi cần đến. |
| **Mental Model** | Think of iterations as **phases of building a house**: Iteration 0 = surveying the land & laying the foundation. Development = building rooms. Iteration H = final inspection, painting, and cleanup before handing over the keys. Spikes = testing if a specific material (e.g. a new cement brand) works before using it throughout. | Nghĩ các iteration như **giai đoạn xây nhà**: Iteration 0 = khảo sát đất & đặt móng. Development = xây các phòng. Iteration H = kiểm tra cuối, sơn và dọn dẹp trước khi bàn giao chìa khóa. Spikes = kiểm tra xem một vật liệu cụ thể (vd: thương hiệu xi măng mới) có hoạt động không trước khi dùng xuyên suốt. |
| **Connections** | Links to: **Sprint/Iteration** (core agile cycle), **Technical Debt** (Iteration H addresses it), **Refactoring** (done in Iteration H), **Risk Management** (risk-based spike), **Timeboxing** (spikes are strictly timeboxed). | Liên kết với: **Sprint/Iteration** (chu kỳ agile cốt lõi), **Technical Debt** (Iteration H giải quyết nó), **Refactoring** (thực hiện trong Iteration H), **Quản lý rủi ro** (risk-based spike), **Timeboxing** (spikes được timebox chặt chẽ). |
| **Real-world Example** | Team needs to generate complex PDF reports using a third-party library. Before sprint starts, they run an **architectural spike** (3 hours): test if the library handles the required format. It works → sprint proceeds confidently. If it failed → they'd have chosen a different library before wasting a full sprint. | Nhóm cần tạo báo cáo PDF phức tạp dùng thư viện bên thứ ba. Trước khi sprint bắt đầu, họ chạy **architectural spike** (3 giờ): kiểm tra xem thư viện có xử lý được định dạng yêu cầu không. Hoạt động → sprint tiến hành tự tin. Nếu thất bại → họ đã chọn thư viện khác trước khi lãng phí cả sprint. |
| **Pitfalls** | • Confusing Iteration 0 with a development sprint — **no product output** in Iteration 0. • Thinking Iteration H adds features — it does **NOT**, only cleanup and docs. • Letting a spike run too long — spikes must be **strictly timeboxed** (hours, not days). • Confusing architectural spike (does it work?) with risk-based spike (does the fallback work?). | • Nhầm Iteration 0 với development sprint — **không có đầu ra sản phẩm** trong Iteration 0. • Nghĩ Iteration H thêm tính năng — **KHÔNG**, chỉ dọn dẹp và tài liệu. • Để spike chạy quá lâu — spikes phải được **timebox chặt chẽ** (giờ, không phải ngày). • Nhầm architectural spike (có hoạt động không?) với risk-based spike (phương án dự phòng có hoạt động không?). |
| **Exam Tips** | • Know all 3 iteration types and their order: **0 → Development → H**. • Iteration H = hardening = **cleanup only**, no new features. • **Spike** = short, timeboxed investigation — not a full sprint. • **Architectural spike** = proof of concept. **Risk-based spike** = testing a fallback/contingency. • If exam describes team "testing a theory before the sprint" → **spike**. | • Biết cả 3 loại iteration và thứ tự: **0 → Development → H**. • Iteration H = hardening = **chỉ dọn dẹp**, không có tính năng mới. • **Spike** = điều tra ngắn, có timebox — không phải sprint đầy đủ. • **Architectural spike** = proof of concept. **Risk-based spike** = kiểm tra phương án dự phòng. • Nếu đề mô tả nhóm "kiểm tra lý thuyết trước sprint" → **spike**. |

---

## 📌 SUMMARY

| EN | VI |
|---|---|
| Agile iterations come in three types: **Iteration 0** (setup, no output), **Development Iteration** (builds the product), and **Iteration H** (hardening — code cleanup and documentation only, no new features). A **spike** is a short, timeboxed investigation run before or during an iteration: an **architectural spike** tests if a technology works (proof of concept), while a **risk-based spike** validates a fallback plan for a potential risk. | Các iteration agile có ba loại: **Iteration 0** (thiết lập, không có đầu ra), **Development Iteration** (xây dựng sản phẩm) và **Iteration H** (hardening — chỉ dọn dẹp code và tài liệu, không có tính năng mới). **Spike** là điều tra ngắn, có timebox thực hiện trước hoặc trong iteration: **architectural spike** kiểm tra xem công nghệ có hoạt động không (proof of concept), trong khi **risk-based spike** xác nhận kế hoạch dự phòng cho rủi ro tiềm ẩn. |

---

## ✅ SELF-CHECK

| EN | VI |
|---|---|
| What are the 3 types of iterations in order? What happens in each? | 3 loại iteration theo thứ tự là gì? Mỗi loại làm gì? |
| What is the difference between an architectural spike and a risk-based spike? | Sự khác nhau giữa architectural spike và risk-based spike là gì? |
| Can Iteration H include new features? Why or why not? | Iteration H có thể bao gồm tính năng mới không? Tại sao? |
| What makes a spike different from a regular development iteration? | Điều gì làm cho spike khác với development iteration thông thường? |
