# Search Queries and Execution Details

This document provides the standardized search strings, execution parameters, and database-specific search configurations applied during the literature search phase of the SLR.

---

## Execution Metadata
- Execution Date: September 25, 2026
- Target Period: 2024 - 2026
- Total Raw Records Identified (N): 605 records (across 4 digital libraries)

---

## Standardized Search String (PICO Framework)

The query string was designed following the PICO (Population, Intervention, Comparison, Outcome) model, connecting key terms with boolean operators (AND, OR):

("large language model" OR LLM OR "language models" OR "code LLMs")
AND
("dynamic context" OR "dynamic retrieval" OR "context management" OR "context engineering" OR "context pruning" OR "context selection" OR "adaptive context" OR "retrieval-augmented generation" OR RAG OR "agent memory")
AND
("static context" OR "fixed context" OR "limited context" OR "basic prompting" OR "baseline prompting" OR "static prompting" OR "static retrieval" OR "long context" OR "large context window" OR "single-turn")
AND
("functional correctness" OR "code correctness" OR "pass@k" OR "code metrics" OR "structural metrics" OR "structural quality" OR "code quality" OR "software quality" OR "maintainability" OR "static analysis")

---

## Database-Specific Search Parameters and Results

| Digital Library | Search Field / Mode | Query Adaptation / Syntax | Results (n) | Raw Export File |
| :--- | :--- | :--- | :---: | :--- |
| ACM Digital Library | Standard Field: All | Standard String | 456 | search/raw/acm.bib |
| Scopus | Search within - All Fields | Standard String | 106 | search/raw/scopus.bib |
| Web of Science | Smart Search - All Databases | Standard String | 36 | search/raw/wos.ris |
| IEEE Xplore | Standard Field: All | Standard String | 7 | search/raw/ieee.bib |
| Total Raw Identified | - | - | 605 | - |

---

## Search Execution Notes

1. Broad Scope: No restrictive language filters or document-type exclusions were applied directly within the database search interfaces to ensure maximum recall.
2. Post-Search Deduplication & Screening: All N = 605 records were imported into the Parsifal platform for deduplication and two-stage screening (Title/Abstract screening followed by Full-Text eligibility review).
