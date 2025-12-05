# eHMI for Autonomous Vehicles in LMIC Environments (India)

**Course:** ISE 210 Human Factors & Ergonomics + ISE 222 Systems Design  
**Duration:** Fall 2024 – Fall 2025  


## Overview

Led human factors research and systems design for external Human-Machine Interfaces (eHMI) enabling safe AV–pedestrian communication in Indian urban traffic. Combined meta-analysis of global AV safety data with Axiomatic Design and Quality Function Deployment to create context-aware, inclusive, and robust eHMI solutions for low- and middle-income countries (LMICs).

## My Role

- Led systematic review (PRISMA) and meta-analysis of 34 studies on AV safety across infrastructure settings
- Applied Axiomatic Design to map stakeholder needs → Functional Requirements → Physical Solutions
- Built House of Quality (QFD) linking customer requirements to engineering parameters
- Defined acceptance criteria, verification measures, and hardware specifications
- Synthesized human factors, machine perception, and infrastructure constraints into actionable design

## Methods & Frameworks

- **Meta-Analysis:** REML random-effects model with Hartung-Knapp adjustments, meta-regression
- **Axiomatic Design:** Independence Axiom, uncoupled FR–PS matrices (Level 1 & 2 decomposition)
- **Quality Function Deployment (QFD):** House of Quality for prioritization
- **Human Factors:** Cognitive load analysis, inclusive design for diverse literacy/age groups
- **Systems Engineering:** Requirement traceability, verification matrices, environmental robustness specs

## Key Outcomes

### Research Findings
- **Safety Gap Quantified:** Pooled Risk Ratio = 1.44 (95% CI: 0.58–3.61), indicating 44% higher risk in LMIC environments
- **High Heterogeneity:** τ² = 1.399, I² = 98.5% — performance varies dramatically by local context
- **Root Causes Identified:** Road quality and sensor detection failures explain nearly all between-study variance (τ² → 0 in meta-regression)
- **Policy Implication:** Universal AV protocols unsafe without local adaptation

### Design Solution
- **eHMI System:** 360° LED light bar with AI-powered context engine, behavior rules, and ruggedized enclosure
- **Visual Language:** Traffic-light-inspired (red/amber/green), colour-blind-safe, icon-based (no text)
- **Critical Parameters (from HoQ):**
  - Colour coding scheme (relative importance: 0.159)
  - Display luminance & contrast (0.147)
  - Icon clarity (0.147)
  - Warning priority logic (0.145)
- **Acceptance Criteria:** ≥1,000 cd/m² luminance, ≥95% icon recognition at 20m, <300ms latency, IP65+ protection

## Metrics & Impact

| Metric                          | Result/Insight                                    |
|---------------------------------|---------------------------------------------------|
| Studies Analyzed                | 34 (from 500+ screened via PRISMA)               |
| Market Context                  | $24B global AV market, 64% consumer distrust     |
| Pooled Risk Ratio (LMIC)        | 1.44 (95% CI: 0.58–3.61)                         |
| Heterogeneity                   | I² = 98.5% (context-dependent performance)       |
| Meta-Regression τ² Reduction    | ~100% when controlling road quality + detection  |
| eHMI Icon Recognition Target    | ≥95% at 20m (diverse user groups)                |
| Hardware Robustness             | IP65+, −20°C to +50°C operating range            |

## Featured Artifacts
- [Design Specification Document (PDF)](Tapkir,%20S.%20and%20Abdelmalak%20A.%20_Universal%20Vehicle%20Protocols%20versus%20Local%20Realities.pdf)
  
- [Axiomatic Design (xlsx)](Axiomatic%20Design.xlsx)
- [House of Quality (xlsx)](House%20of%20Quality_Results.xlsx)


- [Research Paper: Universal Vehicle Protocols vs. Local Realities (PDF)](Tapkir,%20S.%20and%20Abdelmalak%20A.%20_Universal%20Vehicle%20Protocols%20versus%20Local%20Realities.pdf)
- [Presentation: Systematic Gaps and Safety Risks in AV Deployment (PDF)](AV_HFE_PPT_ISE%20210.pdf)
- [Video: eHMI Demo/Explanation](https://drive.google.com/file/d/1rkbV0AeiV2KMaC-LnVSyDxQ_eW_X7siK/view?usp=drive_link) 
## Impact for AI Product Management

- **Human-Centered AI:** Designed explainable, trustworthy AI interface for safety-critical human–machine interaction
- **Systems Thinking:** Mapped user needs → technical specs → verification, ensuring traceability and accountability
- **Context-Aware Design:** Demonstrated that "one-size-fits-all" AI fails; local adaptation is product requirement, not afterthought
- **Evidence-Based Prioritization:** Used QFD to focus engineering effort where customer value is highest
- **Cross-Functional Leadership:** Bridged human factors, perception AI, hardware engineering, and policy constraints

## How to Review

- Check out the video for quick and clear picture 
- Start with the **Overview** and **Key Outcomes** for strategic context
- Read the research paper for methodology, meta-analysis results, and policy implications
- Review the presentation for visual summary and design framework
- Check **Metrics & Impact** for quantified business and safety outcomes
- Contact me for deeper discussion on design rationale, future prototyping, or stakeholder engagement

---
