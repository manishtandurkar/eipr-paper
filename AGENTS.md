# AGENTS.md — IEEE Research Paper Generator

## Task
Write a complete IEEE-format research paper in LaTeX using the project information below.

---

## Project Information

- **Institution:** RV College of Engineering, Bengaluru – 560059, India
- **Department:** Industrial Engineering & Management
- **Semester:** VI | Experiential Learning (EL) Project
- **Topic:** Innovation Capability and Startup Survival Relationships
- **Group Size:** 4 members

### Problem Statement
Despite innovation being widely regarded as a key driver of business success, there is limited empirical evidence on how specific innovation capabilities influence the survival of early-stage startups, particularly in developing economies like India. This study examines the relationship between innovation capability and startup survival, exploring the mediating and moderating factors that strengthen or weaken this link.

### Theoretical Grounding
- **Dynamic Capabilities Theory** (Teece et al., 1997) — firms survive by sensing, seizing, and reconfiguring capabilities
- **Resource-Based View / RBV** (Barney, 1991) — innovation capability as a VRIN resource for competitive advantage

### Conceptual Framework

| Role | Variables |
|---|---|
| Independent Variables | Product Innovation Capability, Process Innovation Capability, Marketing Innovation Capability |
| Mediator | Competitive Advantage |
| Dependent Variable | Startup Survival |
| Moderators | Founder Experience, Funding Stage |

### Hypotheses
- H1–H3: Each type of innovation capability positively affects startup survival
- H4: Competitive advantage mediates the innovation → survival relationship
- H5: Founder experience moderates the innovation → survival relationship
- H6: Funding stage moderates the innovation → survival relationship
- H7–H9: Each type of innovation capability positively affects competitive advantage

### Methodology
- **Design:** Quantitative, cross-sectional survey
- **Target:** Startup founders in India (0–7 years old startups)
- **Sample Size:** 200–300 respondents
- **Tool:** Structured questionnaire, 5-point Likert scale
- **Analysis:** PLS-SEM using SmartPLS
- **Reliability:** Cronbach's alpha > 0.7, CR > 0.7, AVE > 0.5

### Research Gaps Addressed
1. No India-specific study on innovation capability and startup survival
2. Innovation capability not disaggregated into product, process, and marketing types
3. Mediating role of competitive advantage untested in early-stage startups
4. Moderating role of founder experience and funding stage underexplored
5. Lack of SEM-based model for Indian tech startups

---

## Paper Details

- **Title:** Innovation Capability and Startup Survival: An Empirical Study of Early-Stage Ventures in India
- **Format:** IEEE Conference Paper
- **LaTeX Class:** `\documentclass[conference]{IEEEtran}`
- **Target Length:** 6–8 pages (IEEE double column)
- **Citation Style:** IEEE numeric `[1]`, `[2]`, ... using `\bibitem`

---

## Paper Structure

### 1. Title & Authors
- Author names: Author 1, Author 2, Author 3, Author 4
- Affiliation: Department of Industrial Engineering & Management, RV College of Engineering, Bengaluru – 560059, India

### 2. Abstract (~250 words)
- Motivation: why startup survival matters
- Gap: lack of India-specific, disaggregated innovation capability study
- Objective: examine product, process, marketing innovation → startup survival
- Method: PLS-SEM, survey of Indian startup founders
- Contribution: mediating role of competitive advantage, moderating role of founder experience and funding stage

### 3. Keywords
Innovation Capability, Startup Survival, Dynamic Capabilities, Competitive Advantage, PLS-SEM, Entrepreneurship, India

### 4. Introduction (~500 words)
- Open with startup failure statistics (70% fail within 5 years)
- Establish importance of innovation for survival
- State research gap and objectives
- End with paper organization paragraph

### 5. Literature Review (~800 words)
- Theme 1: Innovation and startup survival (direct link)
- Theme 2: Dynamic capabilities and startup performance
- Theme 3: Innovation ecosystems and social capital
- Theme 4: Resource-Based View and startup survival
- Theme 5: Competitive advantage as mediator
- Theme 6: Founder characteristics as moderators
- End with research gap paragraph

### 6. Conceptual Framework & Hypotheses (~400 words)
- Include `\begin{figure}...\end{figure}` placeholder for framework diagram
- List all 9 hypotheses (H1–H9) with 1–2 supporting citations each

### 7. Research Methodology (~600 words)
- Research design, target population, sampling, instrument
- Reliability and validity criteria
- PLS-SEM analysis steps: measurement model → structural model → mediation → moderation

### 8. Expected Results & Discussion (~400 words)
- Expected findings per hypothesis (use future tense — paper is pre-data-collection)
- Link to Dynamic Capabilities Theory and RBV
- Implications for Indian startup ecosystem

### 9. Conclusion (~200 words)
- Summarize objectives and approach
- State theoretical and practical contributions
- Limitations and future research directions

### 10. References
IEEE numeric format — include at least 20 references from themes above.

---

## LaTeX Rules
- Use `\documentclass[conference]{IEEEtran}` — do NOT manually set two-column layout
- Use `\section{}`, `\subsection{}` for headings
- Tables: `\begin{table}[htbp]` with `\caption{}` above the table
- Figures: `\begin{figure}[htbp]` with `\caption{}` below the figure
- Citations: `\cite{key}` inline, `\bibitem` at end
- Abstract inside `\IEEEtitleabstractindextext{}`

## Key Variable Abbreviations
| Construct | Abbrev | Role |
|---|---|---|
| Product Innovation Capability | PIC | IV |
| Process Innovation Capability | PROC | IV |
| Marketing Innovation Capability | MIC | IV |
| Competitive Advantage | CA | Mediator |
| Startup Survival | SS | DV |
| Founder Experience | FE | Moderator |
| Funding Stage | FS | Moderator |

## Tone & Style
- Academic, formal, third-person, passive voice where appropriate
- Define all acronyms on first use
- Every claim must have a citation
- Do not invent data — frame results as "expected" or "proposed"
