🚀 AI Workflow Pack for Project Management Productivity
📌 Project Overview
This repository contains an executive-level AI Workflow Pack designed to transform unstructured project notes, scattered team updates, and complex inbox communications into actionable executive summaries, structured decision-tracking tables, and risk mitigation plans.

The project demonstrates end-to-end prompt engineering frameworks (such as C.A.R.E. and the Verification Pass) tailored for civil and software project management environments, ensuring high-density, skimmable, and hallucination-free outputs.

🛠️ Included Workflows & Prompt Templates
1. Stakeholder Delay Notice (تحديثات التأخير لأصحاب المصلحة)
Task Type: Summarize + Plan

Purpose: Generates structured issue-escalation emails, separating confirmed facts from unconfirmed assumptions.

Prompt:

Plaintext
Context: بصفتي مهندس إدارة مشروع، أواجه تأخيراً لمدة [المدة] من مورد رئيسي في [اسم المشروع].
Action: اكتب رسالة لـ [الفريق الداخلي / المدير المباشر].
Role: [مشجع وعملي / رسمي ومباشر].
Expected Output: توضيح السبب، الأثر على العمل، والخطوات/البدائل المطلوبة.
2. Text-to-Table Converter (تحويل النوتات إلى جدول)
Task Type: Extract + Summarize

Purpose: Transforms raw meeting notes into a standard 5-column Markdown decision-tracking matrix.

Prompt:

Plaintext
Context: أعمل على إدارة وتتبع المستجدات التشغيلية للمشروع، ولدي مجموعة من الملاحظات اليومية المبعثرة.
Action: قم بتحليل النص المرفق واستخراج البيانات منه وإعادتها مصاغة في جدول Markdown منظم وعالي الدقة.
Role: بصفتك مدير مشروع محترف يركز على تنظيم البيانات وسرعة الفرز.
Expected Output: جدول من 5 أعمدة حصراً: (المسار/بند العمل، الحالة، الجهة/المسؤول، المشكلة/الإجراء المطلوب، الموعد القادم).
3. Executive Brief & Decision Tracker (الملخص التنفيذي وتتبع القرارات)
Task Type: Summarize + Extract

Purpose: Synthesizes complex operational notes into executive-ready bullet points paired with action item tables.

Prompt:

Plaintext
Context: لدينا مخرجات وملاحظات مبعثرة من اجتماع إطلاق المنتج التجريبي.
Action: قم بتحليل النص، واستخراج القرارات المؤكدة، والمهام المعلقة، والقرارات المطلوبة للبت فيها قبل الاجتماع القادم.
Role: بصفتك مدير مشروع مهني يركز على إدارة المخاطر وتسهيل اتخاذ القرارات.
Expected Output: تقديم ملخص مقسم إلى نقاط رئيسية سريعة القراءة يليه جدول تتبع الخمسة أعمدة.
4. Overloaded Inbox Triaging (إدارة الأزمات والرسائل المتراكمة)
Task Type: Analyze + Plan

Purpose: Evaluates high-pressure launch scenarios (TaskFlow case study) to extract minimum acceptable scopes (MVP) and assign team ownership.

Prompt:

Plaintext
Context: عودة من غياب مع وجود [عدد] رسالة وموعد حرج للإطلاق خلال [عدد] أيام.
Action: حلل الوضع وقدم حسم للقرارات الأربعة الرئيسية وتوزيع المهام على الفرق.
Role: Senior Product Manager خبير في إدارة الأزمات.
Expected Output: ملخص للقرارات الأربعة + جدول توزيع المهام الخماسي.
⚙️ Technical Documentation & Verification Pass Protocol
Core Methodology
C.A.R.E. Framework: Directs AI interactions via explicit Context, Action, Role, and Expected Output specifications.

Verification Pass Protocol: Implements rigorous step-by-step verification to trace all AI-generated claims back to raw input, eliminating factual hallucinations.

Standard 5-Column Schema:
Workstream/Item | Status | Owner/Stakeholder | Key Issue / Action Needed | Next Milestone

📜 Program Acknowledgement
This project was completed as part of the LO-FGP - Generative AI for Workplace Productivity training program at SDAIA Academy, under the supervision of Fahad Alqahtani.

The portfolio demonstrates the practical application of generative AI for workplace productivity through prompt engineering, professional writing, information processing, planning, verification, responsible use, and personal AI integration.

Official SDAIA Academy GitHub: SDAIA Academy

🤝 Community & Open-Source Engagement
We support and contribute to the Saudi technical community on GitHub:

⭐ Star high-quality Saudi AI repositories.

🔄 Fork and submit Pull Requests to foster open-source innovation.

👥 Follow SDAIA Academy for updates.
