# Prompt: Quick Study Notes Generator

Replace `[TOPIC]` with your subject, then paste into Claude.

---

```
---
title: "{topic name}"
weight: {YYYYMMDDHHmm}
--- 
# [TOPIC]


## 📝 CUE & NOTES

| CUE | EN | VI |
|---|---|---|
| **What is it?** | Concise definition, core essence. | Định nghĩa ngắn gọn, bản chất cốt lõi. |
| **What is it used for?** | Main purposes, key functions (2–3 points). | Mục đích, công dụng chính (2–3 ý). |
| **When to use?** | Context, conditions, suitable scenarios. | Ngữ cảnh, điều kiện áp dụng phù hợp. |
| **Key Points** | 3–5 core bullets, 1–2 lines each. | 3–5 ý chính, mỗi ý 1–2 dòng. |
| **Mental Model** | Explain simply as if to a beginner. | Giải thích đơn giản như nói cho người mới. |
| **Connections** | Compare with related concepts: similar/different. | So sánh giống/khác với khái niệm liên quan. |
| **Real-world Example** | One concrete, short case study. | Một trường hợp cụ thể, ngắn gọn minh họa. |
| **Pitfalls** | Common mistakes, easily forgotten or misunderstood. | Lỗi phổ biến, điểm hay quên hoặc hiểu sai. |
| **Exam Tips** *(optional)* | Common question types, typical trap answers. | Dạng câu hỏi thường gặp, đáp án bẫy. |

---

## 📌 SUMMARY

| EN | VI |
|---|---|
| In 2–3 sentences: What is [TOPIC], when to use it, and the most important thing to remember. | Tóm lại trong 2–3 câu: [TOPIC] là gì, dùng khi nào, và điều quan trọng nhất cần nhớ là gì. |

---

## ✅ SELF-CHECK

| EN | VI |
|---|---|
| Question 1? | Câu hỏi 1? |
| Question 2? | Câu hỏi 2? |
| Question 3? | Câu hỏi 3? |
```

After you finish writing, call the write_artifact tool with:

path = {project_id}/{feature_id}/_index.md
content = the markdown content you just wrote
  content = the markdown content
If a next step exists ({{next_step}}), call the MCP prompt {{next_step}} to continue the workflow.