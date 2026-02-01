OPT Project README — Progress Log (Jan 2026)
Project

Goal: Build an analytics + AI workflow that starts from data preparation and evolves toward a student-support chatbot prototype (internal demo only).

Faculty Sponsors: Jeffrey Saltz; Ingrid Erickson
Reporting tool: Qualtrics (bi-monthly OPT reporting)

Reporting Periods & Work Completed
Jan 1 – Jan 15, 2026

Focus: Dataset understanding and readiness
Work completed:

Performed exploratory data analysis (EDA): schema/variable review, missing values & duplicates profiling

Generated descriptive stats and explored distributions/relationships (correlations + categorical breakdowns)

Identified data quality issues (outliers, inconsistent categories, skew)

Defined recommended preprocessing plan (cleaning, encoding, scaling, feature engineering)

Outputs:

EDA notes + initial data quality findings

Preprocessing plan for next step execution

Jan 16 – Jan 31, 2026

Focus: Pivot to data expansion + student chatbot prototype (internal)
Work completed:

Pivoted from only internal data to include public website content integrated with existing dataframes

Built a structured ingestion workflow to collect/organize content into a consistent dataset

Tracked dataset provenance (source + access date) and performed normalization/deduplication

Prototyped a student-facing chatbot concept using retrieval-based grounding (answers based on curated content)

Tested demo with sample student questions; documented failure cases and improvement ideas

Kept the demo internal (not public) pending compliance/usage review

Outputs:

Integrated dataset (existing DF + web-sourced DF) with documented schema/provenance fields

Internal chatbot demo prototype + test questions + error/failure notes

Reporting note: The reporting period option Jan 16–31, 2026 was not visible in the survey dropdown at the time of reporting, so the update was sent via email and will be entered in the survey once enabled.

Skills Developed (STEM)

Exploratory data analysis (EDA) and statistical profiling

Data cleaning and validation (missing values, duplicates, outliers, inconsistencies)

Feature planning/engineering mindset (encoding/scaling/transformations)

Data engineering workflows: ingestion, parsing, schema design, reproducibility

Dataset governance basics: provenance tracking + documentation

Applied NLP/AI prototyping: retrieval-grounded chatbot design, testing, error analysis, guardrails

Compliance & Safety Notes (for internal demo)

Demo remains private/internal

Sources are treated as public content with usage constraints (ToS/robots/access review)

Avoid collecting/storing personal or sensitive data

Rate limiting / lightweight collection preferred

Document where each item came from (source + date) to support review

Next Steps (Feb 2026)

Confirm source permissions/usage constraints and finalize “approved sources” list

Improve retrieval quality (chunking strategy, indexing, ranking, dedup)

Expand evaluation: structured test set of student questions + accuracy/relevance checks

Summarize results for sponsor review (what works, what fails, next experiments)
