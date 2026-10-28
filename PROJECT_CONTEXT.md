# Project context

## Confirmed context

- Project: Kestrel Human to LLM Evaluation.
- This folder is the project workspace.
- The user opened a new chat to begin with a fresh context window.
- The first requested step was to create the initial project structure.

## Current status

Initial folders and planning documents have been created. The user supplied four fictional Kestrel Freight Analytics source documents in `data/raw/`: the 2025 annual report, Q1 and Q2 2026 earnings releases, and 2026 risk factors.

The user confirmed that the rubric should evaluate both factual answers and business analysis. Version 0.1 is in `evaluations/rubrics/kestrel-rubric-v0.1.md` and its Word counterpart. It proposes shared criteria for human and LLM responses, five scoring dimensions, applicability rules, calibration examples, and rater procedures. Weights and anchors remain proposals for pilot review.

Step 2 is complete: `evaluations/tasks/kestrel-test-cases-v0.1.docx` contains 30 pilot cases and administrator scoring keys. Cases 01 to 10 cover factual retrieval, 11 to 20 calculations and source limits, and 21 to 30 business analysis. Each has a prompt, required elements, reference answer, source locations, applicable dimensions, and error checks. A JSON counterpart preserves the same case records for later evaluation tooling. The 16-page Word document was rendered and reviewed, and numeric reference calculations were checked. Respondents should receive prompts and shared instructions only, without scoring keys. This is a pilot set with calibration overlap, not an unseen held-out benchmark.

## Decisions still needed

- Specific evaluation questions and design of the human-to-LLM comparison.
- Tasks, datasets, and inclusion criteria.
- Human participant or rater procedures, if applicable.
- Models, versions, and execution settings.
- Calibration of the proposed rubric, outcome measures, and analysis approach.
- Implementation language and required tools.

## Next step

Review rubric and test-case version 0.1, then define pilot administration settings and complete `docs/evaluation-plan.md` before collecting responses.

## Handoff convention

Update this file when requirements, decisions, or status change. Record substantive study decisions in the planning documents and keep run-specific settings with each run.
