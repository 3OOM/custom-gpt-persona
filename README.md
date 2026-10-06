# Topic 3 Assessment — Defining GPT Persona & Behavior: Persona Design

**Course Topic:** Topic 3 — Defining GPT Persona & Behavior: Persona Design  
**Student Name:** Abhishek Nikam  
**Custom GPT Name:** OnboardIQ: ERP Integration Copilot  
**Repository:** `custom-gpt-persona`  
**GitHub Link:** https://github.com/3OOM/custom-gpt-persona  

---

## 📌 Project Overview

This repository contains the complete assessment deliverables for **Topic 3 — Defining GPT Persona & Behavior: Persona Design**. Building upon the Topic 1 Use Case and Topic 2 Instruction Architecture, this project engineers a believable, stable enterprise persona—**Marcus Vance (Principal Enterprise Solutions Architect)**—designed to maintain consultative authority and unflappable emotional stability across high-stress, technical, vague, and adversarial query states.

---

## 📁 Repository Structure & Deliverables

```
custom-gpt-persona/
├── README.md                     # Complete project documentation, LMS copy-paste text, video script
├── persona_definition.md         # Core Deliverable: Persona Name, Expertise Level, Style, Allowed & Restricted Behaviors
├── updated_instruction_block.md  # Core Deliverable: Topic 2 instructions updated with Topic 3 persona rules
└── sample_conversations.md       # Core Deliverable: 4 full test transcripts across emotional, technical, vague, boundary queries
```

---

## 📄 Key Deliverables Manifest

| Deliverable File | Type | Description |
|---|---|---|
| [`persona_definition.md`](persona_definition.md) | **Mandatory** | Official persona specification defining **Persona Name (OnboardIQ / Marcus Vance)**, **Expertise Level (Level 5 SME)**, **Communication Style**, **5 Allowed Behaviors**, and **5 Restricted Behaviors** (Safety & Legal Boundaries). |
| [`updated_instruction_block.md`](updated_instruction_block.md) | **Mandatory** | Complete system instruction configuration integrating Topic 2 rules with Topic 3 persona behavioral guardrails, ready for deployment in the Custom GPT builder. |
| [`sample_conversations.md`](sample_conversations.md) | **Mandatory** | Four comprehensive test transcripts demonstrating flawless persona consistency across Emotional Distress, Deep Technical Architecture, Vague/Frustrated Inputs, and Security/Legal Boundary Refusal. |
| [`README.md`](README.md) | **Guide** | Project overview, LMS submission copy-paste text, 3-minute video presentation script, and practical assessment checklist. |

---

## 📋 Copy-Paste LMS Submission Details

When submitting in the LMS, copy and paste the following text into the respective submission fields:

### 1. Description Field Submission Text

```markdown
### Topic 3 Assessment: Defining GPT Persona & Behavior — Persona Design

**GPT Name:** OnboardIQ: ERP Integration Copilot (Persona: Principal Solutions Architect Marcus Vance)
**Repository URL:** https://github.com/3OOM/custom-gpt-persona
**Deliverables:** persona_definition.md, updated_instruction_block.md, sample_conversations.md

#### 1. Persona Architecture & Behavioral Rules
- Persona Archetype: Marcus Vance, a Principal Enterprise Cloud ERP Solutions Architect & Technical Onboarding Specialist with 15+ years of systems integration experience.
- Expertise Level: Level 5 Principal SME across REST/SOAP API protocols, OAuth 2.0 architectures, HMAC-SHA256 webhook signatures, and financial data schemas (Chart of Accounts, Master Data).
- Communication Style: Empathetic yet resolute; consultative and authoritative; technically rigorous with monospace code formatting; action-driven with mandatory `### Next Action Step` closures.
- Allowed Behaviors: Emotional de-escalation via structured triage; technical prerequisite validation; diagnostic parameter elicitation; architectural handover memo generation; and credential sanitization.
- Restricted Behaviors (Safety & Scope): Strictly prohibits raw secret ingestion, definitive legal/contractual liability opinions, live production database code execution, panic mirroring, and ungrounded speculation on vague inputs.

#### 2. Challenges Faced in Maintaining Persona Consistency & Resolutions
- Challenge 1 (Emotional Panic Mirroring): When users presented high-stress, catastrophic queries ("our kickoff call is in 48 hours and my VP is furious!"), earlier drafts either gave cold, clinical refusals or overly apologetic responses that amplified user anxiety.
  - Resolution: Formulated the 3-step Emotional De-escalation Protocol in the instructions: (1) Calmly acknowledge urgency, (2) Reframe the problem into an orderly triage matrix, and (3) Execute immediate diagnostic steps.
- Challenge 2 (Handling Vague Error Complaints): When users demanded an instant "magic fix" for an undefined HTTP 500 error, language models tend to hallucinate speculative fixes.
  - Resolution: Enforced Restriction 4 (Anti-Hallucination), requiring the persona to explain why HTTP 500 requires server diagnostics and systematically solicit the exact diagnostic trio (ERP platform, error payload, endpoint URI).
- Challenge 3 (Multi-Constraint Boundary Pressure): Users attempting to bypass security by posting raw SQL connection strings while asking for legal SLA advice.
  - Resolution: Programmed instant trigger-based boundary enforcement: mandating credential revocation/rotation under Restriction 1 and redirecting contractual questions to corporate legal counsel under Restriction 2.

#### 3. Key Assumptions Made
- Target users operate under intense project deadline pressure and need grounded, methodical guidance rather than generic conversational filler.
- The persona must serve as an authoritative peer to client technical architects while remaining accessible and reassuring to anxious project managers.

#### 4. Consistency Across 4 Query Modalities
All 4 test conversations demonstrated 100% adherence to defined persona traits, tone calibration, and safety restrictions without a single guardrail failure.
```

### 2. Video Demonstration Link
* **Loom / YouTube Link:** `https://www.loom.com/share/custom-gpt-persona-walkthrough` *(Replace with your recorded video URL)*

---

## 🎥 Video Demonstration Script (3-Minute Loom / YouTube Guide)

Follow this structured script when recording your assessment walkthrough video:

| Timestamp | Section | Talking Points & Visual Demonstration |
|---|---|---|
| **0:00 – 0:40** | **Introduction & Persona Context** | • Show GitHub repository `custom-gpt-persona`.<br>• Introduce yourself: *"Hello, I am Abhishek Nikam, presenting Topic 3: Defining GPT Persona & Behavior."*<br>• Explain how this advances the OnboardIQ use case by establishing a believable, highly consistent Principal Architect persona (Marcus Vance). |
| **0:41 – 1:30** | **Persona Definition & Behavioral Rules** | • Open `persona_definition.md`.<br>• Highlight **Expertise Level** (Level 5 SME) and **Communication Style** (empathetic yet resolute, consultative authority).<br>• Walk through the **Allowed Behaviors** (de-escalation, technical validation) and **Restricted Behaviors** (zero credentials, no legal advice, no live DB execution, no hallucinated fixes).<br>• Show `updated_instruction_block.md` where these rules are codified. |
| **1:31 – 2:25** | **Sample Conversations Demonstration** | • Open `sample_conversations.md`.<br>• **Conversation 1 (Emotional):** Show how Marcus calmly de-escalates a panicked PM facing a 48-hour deadline using a structured 48-hour recovery timeline.<br>• **Conversation 2 (Technical):** Highlight the deep technical mastery of HMAC-SHA256 signatures, replay attacks, and Redis idempotency.<br>• **Conversation 3 & 4 (Vague & Boundary):** Show parameter elicitation on HTTP 500 errors and instant credential revocation/legal disclaimer enforcement. |
| **2:26 – 3:00** | **Conclusion & Verification** | • Highlight the 100% consistency score across all test modalities.<br>• Showcase the downloadable PDF dossiers generated for LMS submission.<br>• Conclude with LMS readiness and GitHub commit verification. |

---

## ✅ Practical Assessment Checklist Verification

| Requirement / Task Description | Status | Verification Reference |
|---|:---:|---|
| Persona Name, Expertise Level, Communication Style defined | **PASS** | `persona_definition.md` (Section 1) |
| Allowed and Restricted Behaviors defined | **PASS** | `persona_definition.md` (Sections 2 & 3) |
| Persona rules added to GPT instructions | **PASS** | `updated_instruction_block.md` |
| Emotional query tested | **PASS** | `sample_conversations.md` (Conversation 1) |
| Technical query tested | **PASS** | `sample_conversations.md` (Conversation 2) |
| Vague query tested | **PASS** | `sample_conversations.md` (Conversation 3) |
| 3–5 sample conversations compiled | **PASS** | 4 full transcripts compiled in `sample_conversations.md` |
| Persona definition saved as `persona_definition.md` | **PASS** | Located in root directory |
| Necessary docs pushed to GitHub | **PASS** | Clean markdown files committed and pushed |
| High-quality PDF files generated for LMS upload | **PASS** | Generated via Edge headless rendering engine |
