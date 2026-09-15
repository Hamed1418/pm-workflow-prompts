# 07 - Workplace Integration Plan & Operational Prompts

## 📌 Overview
This module defines the long-term operational integration plan and provides practical prompt templates for deploying Generative AI into daily project management practices, team routines, and verification workflows.

---

## 🚀 Execution Roadmap & Operational Prompts

### Phase 1: Daily Routine Integration (Immediate)
**Goal:** Automate daily status updates, meeting note conversions, and task triaging.

#### 🎯 Prompt 1.1: Daily Action-Item Matrix (5-Column Format)
> **Context:** You are a Project Management Engineer converting raw meeting notes into structured action items.
> **Task:** Transform the provided raw notes into a 5-column action matrix.
> **Requirements:** 
> - Columns: `[Task ID | Action Item | Owner | Target Deadline | Priority (High/Med/Low)]`
> - Extract only explicit commitments; do not assume unmentioned deadlines.

---

### Phase 2: Workflow Standardization (Month 1-3)
**Goal:** Establish standardized prompt libraries for issue escalations and hallucination verification.

#### 🎯 Prompt 2.1: Escalation & Risk Log Generator
> **Context:** You are an Senior Site Supervision Engineer drafting a formal delay notification.
> **Task:** Draft a formal delay escalation letter to the client/contractor based on field observations.
> **Requirements:**
> - Include placeholders: `[Project Name]`, `[Contractor Name]`, `[Delay Days]`, `[Impact Area]`.
> - Maintain an authoritative, professional, and contractually compliant tone.
> - Provide 3 potential mitigation strategies at the end.

#### 🎯 Prompt 2.2: Fact-Verification Protocol (Anti-Hallucination Audit)
> **Context:** You are a QA/QC & Verification Engineer reviewing AI-generated project text against source documents.
> **Task:** Cross-reference the generated text `[Insert AI Text]` with the source document `[Insert Source Document]`.
> **Verification Rules:**
> 1. Flag any date, figure, or name not explicitly backed by the source document.
> 2. Classify missing data as "Unverified Assumption" and replace with `[TBD]`.
> 3. Output a 4-column audit table: `[Claim | Source Reference | Verification Status | Required Action]`.

---

### Phase 3: Continuous Enhancement & Scaling (Month 3+)
**Goal:** Refine system prompts and share open-source frameworks with the broader Saudi technical community.

#### 🎯 Prompt 3.1: Prompt Performance & Feedback Refinement
> **Context:** You are an AI Prompt Engineer optimizing operational templates based on field feedback.
> **Task:** Analyze the provided prompt `[Insert Prompt]` and user feedback `[Insert Feedback]`.
> **Requirements:** Re-engineer the prompt using the C.A.R.E. framework to eliminate ambiguity, enforce strict constraints, and improve output quality.
