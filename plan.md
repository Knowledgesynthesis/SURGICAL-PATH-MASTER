# **SURGICAL PATH MASTER — OPTIMIZED MASTER PROMPT FOR EDUCATIONAL APP GENERATION**
A full-spectrum, **mobile-first**, **dark-mode**, **offline-ready** educational platform that teaches **Frozen Section Pathology + General Surgical Pathology** exactly as a **pathology resident** learns it during a surgical pathology rotation, frozen-section rotation, or in major textbooks (e.g., Rosai, Sternberg, etc. — conceptually only).

This app must cover:
- **Frozen section workflow**  
- **Intraoperative consultation reasoning**  
- **Grossing logic**  
- **Margins, orientation, and specimen handling**  
- **Intraoperative diagnostic pitfalls**  
- **Tissue processing basics**  
- **General surgical pathology differential frameworks**  
- **Common benign vs malignant patterns**  
- **Integration with radiology and clinical information**  
- **Reporting logic and synoptic frameworks**  

All content must be **synthetic**, **non-identifiable**, **session-only quizzes**, **no data storage**, and **no real images** (use illustrated diagrams/concept icons only).

---

# **MASTER PROMPT — Surgical Path Master Educational App Generator (SPECIALIZED VERSION)**

## **0. ROLE & MISSION**
You are:
- Product Manager  
- Senior Software Engineer  
- Senior Instructional Designer  
- Surgical Pathology SME  
- Frozen Section SME  
- Histotechnology SME  
- QA Specialist  
- UX Writer  

**Mission:**  
Create a complete educational platform for pathology residents to learn **frozen section interpretation**, **gross pathology**, and **core surgical pathology principles**, including diagnostic reasoning, pitfalls, and specimen-handling logic.

---

# **1. INPUTS (TO FILL WHEN RUNNING THE PROMPT)**

- **Primary Topics:** {{TOPICS}}  
  *Default:* frozen section workflow, grossing, tissue processing, general surgical pathology patterns.

- **Target Levels:** {{LEVELS}}  
  *Default:* PGY1–PGY4 pathology residents, cytopath fellows, surg path fellows.

- **Learning Context:** {{CONTEXT}}  
  *Default:* Frozen section service, daily signout, intraoperative consultation, call responsibilities.

- **Learning Objectives:** {{LEARNING_OBJECTIVES}}  
  *Examples:*  
  - Perform frozen-section triage and handle common specimen types.  
  - Distinguish benign vs malignant patterns in GI, GU, GYN, breast, endocrine, head & neck, soft tissue.  
  - Recognize artifacts in frozen tissue.  
  - Understand margin assessment.  
  - Apply synoptic concepts (conceptual only).  

- **Constraints:** {{CONSTRAINTS}}  
  Must include:
  - Mobile-first  
  - Dark-mode  
  - Offline-ready  
  - Synthetic diagrams only  
  - No tracking  
  - No real patient data  

- **References:** {{REFERENCES}}  
  High-level alignment only: CAP synoptic *concepts*, major surg path texts.

- **Tone:** {{VOICE_TONE}}  
  Default: “Calm, diagnostic, structured, high-yield, pattern-driven.”

---

# **2. EXECUTIVE SUMMARY & NAME OPTIONS**

**Goal:**  
To create a surgical pathology & frozen section “masterclass” that teaches residents to:
- Process specimens  
- Interpret common patterns  
- Avoid frozen-section pitfalls  
- Determine margins  
- Communicate with surgeons  
- Integrate histology + clinical context  

**Name Options:**  
- **Surgical Path Master** — “Frozen → Gross → Histology → Diagnosis.”  
- **Frozens & Gross Atlas** — “The workflow behind intraoperative pathology.”  
- **PathDx Studio** — “Interpretation through structured reasoning.”  

**Success Criteria:**  
- Users can confidently manage frozen sections.  
- Learners can identify major benign and malignant patterns.  
- Trainees understand grossing logic and margin assessment.  
- Users recognize common artifacts and pitfalls.  
- Learners can communicate effective intraoperative consult impressions.

---

# **3. PERSONAS & USE CASES**

### PERSONAS
1. **PGY-1 Resident on First Surg Path Rotation**  
   - Needs: Orientation, margins, specimen orientation.  
   - Pain: Frozen section stress.  
   - Goal: Basics + confidence.

2. **Senior Resident (PGY3–4)**  
   - Needs: Pattern recognition for common cancer types.  
   - Pain: Distinguishing atypia vs malignancy under pressure.  
   - Goal: Advanced reasoning, pitfalls, structured calls.

3. **Surg Path Fellow**  
   - Needs: High-level differential building.  
   - Goal: Complete pattern integration.

### USE CASES
- “Surgeon wants to know: ‘Is it cancer?’”  
- “Margin assessment on frozen.”  
- “Grossing a mastectomy / colectomy / thyroid.”  
- “Distinguishing reactive atypia from carcinoma.”  
- “When to say: ‘Deferred to permanent sections.’”  
- “Artifact identification: freezing, crush, cautery.”  

---

# **4. CURRICULUM MAP & KNOWLEDGE GRAPH**

## MODULE A — Frozen Section Mastery
- Workflow & roles: tech → pathologist → surgeon  
- Indications & contraindications  
- Acceptable frozen-section questions  
- Orientation, inking, and margins  
- Steps:
  1. Triage specimen  
  2. Gross assessment  
  3. Decide sampling  
  4. Review slide  
  5. Communicate impression  
- Common frozen cases:
  - Breast margins  
  - Sentinel lymph node (no real protocols)  
  - Thyroid nodules  
  - Ovary masses  
  - Lung nodules  
- Frozen artifacts:
  - Ice crystal  
  - Crush artifact  
  - Fat folding  
  - Thick sectioning  

---

## MODULE B — Gross Pathology Foundations
- Safety & PPE  
- Specimen orientation  
- Inking margins  
- Sectioning strategy  
- Cassette submission logic  
- Dictation principles  
- Common organs:
  - Breast  
  - GI tract (colon, appendix, stomach)  
  - GYN (uterus, cervix, ovary)  
  - GU (prostate, kidney)  
  - Endocrine (thyroid, parathyroid)  
  - Soft tissue (sarcoma vs benign)  
  - Head & neck (oral cavity, salivary glands)  

---

## MODULE C — Tissue Processing & Histotechnology
- Fixation  
- Dehydration, clearing, embedding  
- Microtomy  
- H&E overview  
- Special stains overview (icon only; no proprietary stains)  
- Artifacts  
- Frozen vs paraffin differences  

---

## MODULE D — General Surgical Pathology Patterns
### Epithelial Patterns
- Glands  
- Solid nests  
- Papillary structures  
- Squamous  
- Basaloid  
- Oncocytic  

### Stromal Patterns
- Fibrous  
- Myxoid  
- Hyalinized  
- Edematous  

### Inflammatory Patterns  
- Acute  
- Chronic  
- Granulomatous  

### Cytologic Atypia
- Nuclear enlargement  
- Hyperchromasia  
- Prominent nucleoli  
- Mitotic figures (conceptual)  

---

## MODULE E — System-Based Surgical Pathology
### 1. Breast
- Benign proliferations  
- DCIS vs invasive carcinoma  
- Lobular features  
- Fibroadenoma vs phyllodes patterning  
- Margin logic  

### 2. GI Tract
- Adenoma → dysplasia continuum  
- Adenocarcinoma patterns  
- Inflammatory bowel disease basics  
- Appendiceal patterns  

### 3. GU (Kidney & Prostate)
- Prostate grading concepts (no scoring)  
- Kidney tumor categories (RCC patterns)  

### 4. Endocrine
- Thyroid: benign nodules vs carcinoma patterns  
- Parathyroid hyperplasia vs adenoma basics  

### 5. GYN
- Endometrial hyperplasia vs carcinoma  
- Cervix patterns (SIL-like cytology patterns in surgical path)  
- Ovarian tumors (broad pattern categories only)  

### 6. Lung
- Adenocarcinoma vs squamous cell carcinoma patterns  
- Granulomas  

### 7. Soft Tissue
- Lipoma vs liposarcoma clues  
- Spindle-cell patterns  
- Cartilaginous patterns  

### 8. Head & Neck
- Thyroid again (overlaps)  
- Salivary gland tumors (broad patterns)  
- Mucosal dysplasia patterns  

---

## MODULE F — Frozen Section Pitfalls & Safety
- Don’t overcall carcinoma on:
  - Tangentially cut glands  
  - Atrophic or inflamed epithelium  
  - Cautery artifact  
- When to **defer** (biggest skill in frozens)  
- Communicating uncertainty properly  

---

## MODULE G — Diagnostic Integration & Reporting
- How to form a differential  
- “Favor benign” vs “favor malignant” logic  
- Gross–micro correlation  
- Synoptic elements (concept-level only)  
- How to write a clear final diagnosis  
- Avoiding ambiguous language  

---

# **5. INTERACTIVE MODELS**

| Interactive | Purpose | Inputs | Outputs | Visuals | Guardrails |
|------------|----------|--------|---------|---------|-----------|
| Frozen Section Workflow Simulator | Practice triage + interpretation | Specimen type | Steps to safe call | Flow diagram | Conceptual only |
| Margin Navigator | Understand margins | Orientation + inking | Margin interpretation | Tissue blocks | Educational |
| Artifact Identifier | Recognize frozen artifacts | Slide description | Artifact identification | Icon histology | No real images |
| Pattern Matcher | Identify common patterns | Description of tissue | Suggested pattern | Iconic histology | Educational |
| Dental Pathway Simulator | Frozen → defer logic | Scenario | “Call” vs “Defer” | Decision tree | Not diagnostic |
| Grossing Planner | Choose sections | Specimen type | Block submission plan | Grossing map | Conceptual |
| System Path Differentiator | Determine benign vs malignant | Pattern clues | Likely differential | Tile-based | No images |
| Integrated Report Builder | Form a diagnosis | Gross + micro clues | Report mockup | Text template | Educational only |

---

# **6. ASSESSMENT & MASTERY (Session-Only)**

Question types:
- MCQ  
- Frozen-section call judgments  
- Grossing logic  
- Pattern recognition  
- Margin interpretation  
- Artifact classification  
- System-specific differentials  
- Integrated cases  

End:
- “You answered X/Y this session.”  
- No stored results.

---

# **7. SURGICAL PATH & FROZEN SECTION REASONING FRAMEWORK**

1. **Specimen identification & orientation**  
2. **Ask: What question is the surgeon REALLY asking?**  
3. **Triage specimen appropriately**  
4. **Evaluate artifact vs true pathology**  
5. **Use major pattern categories** (glandular, squamous, spindle, small round blue cell)  
6. **Assess for invasion** (architecture, stroma reaction)  
7. **Check margins logically**  
8. **Defer vs call** decision  
9. **Clear communication**  
10. **Final report structure**  

Pitfalls:
- Overcalling atypia at frozen  
- Misinterpreting cautery  
- Mistaking tangential sections for invasion  
- Over- or under-sampling gross specimens  
- Overconfidence vs undercalling at frozens  

---

# **8. ACCESSIBILITY, EQUITY, SAFETY**

- WCAG 2.2 AA compliant  
- Dark-mode default  
- Inclusive case scenarios  
- No real images or PHI  
- Strict disclaimers:  
  “Educational only. Not for diagnosis or patient care.”  

---

# **9. TECH ARCHITECTURE**

Stack:
- React + TypeScript  
- Tailwind + shadcn/ui  
- Zustand (session-only)  
- Service Worker for offline mode  

Routes:
- `/frozens`  
- `/grossing`  
- `/processing`  
- `/patterns`  
- `/systems`  
- `/pitfalls`  
- `/integration`  
- `/cases`  
- `/assessment`  
- `/settings`

Settings ONLY:  
- Dark/light toggle  
- About  
- Disclaimer  

---

# **10. DATA SCHEMAS**

### Frozen Section Scenario Schema

