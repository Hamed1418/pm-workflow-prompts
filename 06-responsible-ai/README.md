# 06 - Responsible AI & Enterprise Data Governance

## 📌 Overview
This module outlines governance guidelines, data privacy standards, and ethical AI usage principles, alongside operational prompt templates for redacting sensitive data and enforcing human-in-the-loop (HITL) review protocols.

---

## 🛡️ Operational Governance Prompts

### 1. Data Sanitization & PII Redaction Prompt
> **Context:** You are a Data Privacy Officer ensuring enterprise data protection compliance before feeding text to external AI systems.
> **Task:** Review the following project text `[Insert Raw Text]` and sanitize all confidential entities.
> **Sanitization Rules:**
> - Replace all specific names, supplier identities, and client details with generic placeholders (e.g., `[Client A]`, `[Contractor X]`).
> - Replace financial figures, contract values, and exact site locations with `[Confidential Figure]` or `[Site Location]`.
> - Retain technical logic, timeline structures, and operational intent.

---

### 2. Human-in-the-Loop (HITL) Verification & Responsibility Checklist
> **Context:** You are a Certified Senior Civil Engineer and Project Manager conducting a final review on AI-generated communications.
> **Task:** Review the generated text `[Insert AI Text]` against project specs `[Insert Spec Ref]` to issue a technical clearance.
> **Audit Checklist:**
> 1. Verify that no technical liabilities or contractual commitments are implicitly accepted.
> 2. Ensure safety and QA/QC compliance statements match local Saudi engineering codes.
> 3. Highlight any section requiring formal sign-off from the Lead Engineer prior to external dispatch.
