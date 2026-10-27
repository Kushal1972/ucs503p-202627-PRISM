# Weekly Progress Journal — Aryan Chaturvedi (Roll No: 1024160009)

**Project Name:** PRISM (Poverty Risk Identification through Statistical Mapping)
**Role:** Contributor — Data Engineering, Modeling \& Documentation

\---

## Week 1 (Aug 3 - Aug 9): ML Options \& Team Ideation

* Evaluated classical ML options (Logistic Regression, Random Forest, SVM) suited to a tabular, syllabus-scope pipeline, ruling out satellite imagery/deep learning approaches as out of scope.
* Participated in team brainstorming sessions and helped narrow the topic down to district-level poverty classification for UCS503.
* Drafted early notes on the pain points: outdated snapshots, fragmented indicators, no ground-truth check, and "no explanation, only a label."

## Week 2 (Aug 10 - Aug 16): Primary Metric \& Fusion Layer Design

* Defined the primary evaluation metric: percentage overlap between model-flagged under-developed districts and the official 112-district ADP list, with a 75% target.
* Drafted the design for the data fusion layer: how NITI Aayog's National Multidimensional Poverty Index (MPI) 2023, Census, and NFHS records would be merged on cleaned state/district keys.
* Wrote the Time-to-Value and Scalability sections, emphasizing early validation against the ADP list and the modular, decoupled pipeline design.

## Week 3 (Aug 17 - Aug 23): Proposal Feedback \& Cluster Validation

* Reviewed and gave technical feedback on the Evaluation Criterion and Risks \& Mitigations sections of Kushal's proposal draft.
* Designed and built the "Poverty \& Development Zones in India" pitch presentation, translating the proposal's data-fusion pipeline into a clean, presentable slide flow.

## Week 4 (Aug 24 - Aug 30): NITI Aayog ADP List \& Feature Importance

* Collected and compiled the NITI Aayog Aspirational Districts Programme (ADP) list — the ground-truth reference list — for the validation step.
* Cross-checked the ADP dataset's district naming convention against the merged fusion table to flag additional name-matching edge cases.
* Outlined the feature-importance extraction approach that will back the explainability layer in later deliverables.

## Week 5 (Aug 31 – Sep 6): Use Case Diagram & Data Flow Diagrams

* Worked on preparing and refining the PRISM Use Case Diagram to represent the interactions between Government Data Sources, the Data Analyst/Administrator, the Aspirational Districts Programme (ADP), and the Policy Maker/Decision Maker.
* Contributed to designing the Level 0 and Level 1 Data Flow Diagrams (DFDs) to illustrate the overall PRISM system, its major processes, and the flow of data between source datasets, data processing, machine learning, validation, and decision support.
* Worked on Level 2 DFDs to break down the major processes into detailed sub-processes, covering data acquisition and quality assurance, district matching and data fusion, clustering and classification, and validation and explainability.
