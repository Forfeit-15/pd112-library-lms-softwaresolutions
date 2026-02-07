# Library Management System – Vendor Repository  
**Module:** ICT2113 Software Modelling and Analysis (AY2025/26 T2)  
**Vendor:** SoftwareSolutions  
**Customer:** LittleLibrary

---

## 1. Repository Purpose

This repository serves as the **centralised, version-controlled source of truth** for all artefacts produced by SoftwareSolutions during the analysis, specification, and implementation of the **Web-based Library Management System (LMS)** for LittleLibrary.

The repository supports:
- Regulated revision of requirements derived from the Project Specification (PS)
- Traceability across analysis, modelling, and implementation artefacts
- Controlled transition between project phases in accordance with BCIC methodology

---

## 2. Project Context

LittleLibrary operates under the Singapore Library Board (SLB) and is undergoing a digital transformation to address inefficiencies caused by manual record-keeping. SoftwareSolutions has been engaged to analyse, design, and implement a web-based LMS to support book catalogue management, user profiles, loans, fines, and reporting, in alignment with Singapore’s Smart Nation initiative.

---

## 3. Repository Structure
```
├── docs/
│ ├── analysis/
│ │ └── ICT2113_P2-1166A_Analysis_Report.pdf
│ │
│ ├── specification/
│ │ └── ICT2113_P2-1166A_Project_Specification.pdf
│ │
├── traceability/
│ │ └── requirements_traceability.md
│
├── models/
│ ├── clarify/
│ │ ├── catalogue_responsive_sketch.jpg
│ │ └── profile_visibility_sketch.jpg
│ │
│ ├── use-cases/
│ │ └── use_case_diagram.png
│ │
│ └── data-dictionary/
│ └── data_dictionary.md
│
├── src/
│ └── Python/Django application source code
│
└── README.md
```

---

## 4. Key Artefacts

### Project Specification (PS)
- Location: `docs/specification/`
- Represents the authoritative customer requirements input.

### Analysis Report
- Location: `docs/analysis/`
- Documents SoftwareSolutions’ application of BCIC and IRC to analyse, clarify, and interpret requirements derived from the PS.

### Clarification Models (Paper Napkin Prototypes)
- Location: `models/clarify/`
- Informal explanatory artefacts used during the Clarify phase to reason about ambiguous requirements.

### Requirements Models
- Location: `models/use-cases/` and `models/data-dictionary/`
- Includes use case diagrams and data dictionary artefacts aligned with clarified and corrected requirements.

### Implementation Source Code
- Location: `src/`
- Contains the Python/Django implementation of the LMS, developed in later project phases.

---

## 5. Traceability

Traceability between original Project Specification requirements, BCIC analysis outcomes, and corrected SRS-ready requirements is maintained via artefacts located in:

docs/traceability/


This ensures accountability, auditability, and controlled evolution of requirements throughout the project lifecycle.

---

## 6. Methodology

This project applies the **BCIC analysing method** and **Internal Incongruous Requirements Checklist (IRC)** to ensure that requirements are:
- Clear
- Consistent
- Testable
- Suitable for formal specification and implementation

---

## 7. Notes

- This repository separates **analysis artefacts** from **implementation assets** to prevent contamination of requirements by downstream design or coding decisions.
- Quantitative performance thresholds and design details are introduced only during appropriate lifecycle phases.

---

© 2026 SoftwareSolutions – ICT2113 Academic Project
