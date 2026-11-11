# Kestrel Human to LLM Evaluation

Human evaluation of LLM responses using fictional company documents about Kestrel Freight Analytics. The project covers factual retrieval, calculations, source limitations, and business recommendations, with a shared rubric intended for both human and LLM responses.

## Current status

As of November 10, 2026:

- Four source documents, a version 0.1 rubric, and 30 pilot test cases are available.
- The [October 27 pilot folder](evaluations/runs/2026-10-27_pilot/) contains GPT-4.1-mini attempt 01, collected through OpenAI Playground. The response record dates collection to October 29, 2026; the folder retains its original name.
- All 30 cases have recorded responses and numeric scores in the human ratings file. These are the rater's recorded assessments, not independently validated or adjudicated results.
- An Excel calculator is available for weighted scores. It does not automatically synchronize with the Markdown ratings file.
- The broader human-to-LLM comparison design, rubric calibration, and analysis approach remain to be finalized. The evaluation plan and data dictionary are still outlines; no human respondent comparison or final analysis report is present yet.

This is a pilot set with calibration overlap, rather than an unseen held-out benchmark. Kestrel and its reported figures are fictional.

## Start here

| Material | Purpose |
| --- | --- |
| [Pilot ratings](evaluations/runs/2026-10-27_pilot/gpt-4.1-mini_attempt-01_ratings.md) | Read each prompt, LLM response, dimension ratings, score, source references, and deduction notes together |
| [Pilot response record](evaluations/runs/2026-10-27_pilot/gpt-4.1-mini_attempt-01_responses.md) | Review original responses, collection settings, shared instructions, and collection notes |
| [Score calculator](evaluations/runs/2026-10-27_pilot/gpt-4.1-mini_attempt-01_score-calculator.xlsx) | Download and open in Excel to calculate scores from dimension ratings |
| [Rubric](evaluations/rubrics/kestrel-rubric-v0.1.md) | Review scoring anchors, applicability rules, flags, and rater procedures |
| [Test cases and administrator keys](evaluations/tasks/kestrel-test-cases-v0.1.docx) | Review prompts, required elements, reference answers, and error checks; also available as [JSON](evaluations/tasks/kestrel-test-cases-v0.1.json) |

Use the attempt-specific response record linked above for this pilot. The shorter `gpt-4.1-mini_responses.md` file contains only an earlier model/date note.

## Source documents

These fixed source IDs are used throughout the rubric and run records; they do not depend on folder sorting.

| ID | Document |
| --- | --- |
| S1 | [2025 annual report](data/raw/annual_report_2025.md) |
| S2 | [Q1 2026 earnings](data/raw/q1_2026_earnings.md) |
| S3 | [Q2 2026 earnings](data/raw/q2_2026_earnings.md) |
| S4 | [2026 risk factors](data/raw/risk_factors_2026.md) |

The source documents are tracked in Git for reader reference. Preserve the originals. Local `.txt` upload copies are available under `data/processed/playground/`; processed files are excluded from Git by default.

## Tasks and scoring

The 30 cases are grouped into factual retrieval (01–10), calculations and source limits (11–20), and business analysis (21–30).

| Dimension | Weight |
| --- | ---: |
| A — Factual accuracy | 30 |
| B — Task coverage | 20 |
| C — Evidence and uncertainty | 20 |
| D — Reasoning and calculations | 15 |
| E — Decision usefulness | 15 |

Rate applicable dimensions from 0 to 4. Use the task key to determine whether D and E apply; exclude N/A dimensions from the calculation.

`Weighted score = 100 × sum(weight × rating) / (4 × sum(applicable weights))`

Round the final score to one decimal place. Leave unrun or unscored cases unscored rather than treating them as zeros. The calculator has all 30 cases, yellow rating inputs, preset N/A dimensions, and formulas that leave scores blank until all applicable ratings are valid.

The [rubric](evaluations/rubrics/kestrel-rubric-v0.1.md) governs scoring details, including citation requirements and deduction rules. Its weights and anchors remain subject to pilot calibration; no pass threshold is established. Report results by task type rather than assuming normalized scores measure identical skills across tasks.

## Project layout

| Location | Purpose |
| --- | --- |
| `PROJECT_CONTEXT.md` | Project status, confirmed decisions, and handoff notes for future chats |
| `docs/` | Study design, procedures, and data definitions |
| `data/raw/` | Four original fictional company source documents; preserve these unchanged |
| `data/processed/` | Derived files and local upload copies; excluded from Git by default |
| `data/examples/` | Small synthetic or shareable examples |
| `evaluations/tasks/` | Task definitions, prompts, and reference materials |
| `evaluations/rubrics/` | Scoring criteria and rating instructions |
| `evaluations/runs/` | Run records, responses, ratings, and run-specific metadata |
| `analysis/` | Reserved for analysis notebooks and reusable analysis code |
| `reports/` | Reserved for findings, final deliverables, and figures |
| `scripts/` | Reserved for repeatable preparation, validation, and execution utilities |

## Recording another run

1. Define the study and collection protocol in [the evaluation plan](docs/evaluation-plan.md), including models, source access, tool access, and retry rules. Complete [the data dictionary](docs/data-dictionary.md) as record conventions are settled.
2. Create a folder under `evaluations/runs/`, using a name such as `YYYY-MM-DD_short-description` based on when collection starts.
3. Copy [the response template](evaluations/runs/response-template.md) into that folder for each model and attempt. Record the actual settings, instructions, and verbatim answers. Give respondents the source documents, shared instructions, and prompts without administrator answer keys.
4. Copy [the ratings template](evaluations/runs/ratings-template.md) into the same folder for each independent rater. Record scores, evidence for deductions, flags, and source locations. Keep the reusable master templates blank.
5. Use consistent response IDs, such as `gpt-4.1-mini_attempt-01_KESTREL-01`, to connect records. The existing calculator identifies rows by case ID within its model/attempt context. If reusing it, update the run details and ratings for the new run.
6. Keep calculator inputs and Markdown scores consistent manually. Preserve independent ratings if adjudication is later needed; for a single-rater review, use `not requested` and leave adjudication results blank.
7. Commit and push the run files to make them visible on GitHub. Store subsequent analysis in `analysis/` and findings in `reports/`.

The current workflow uses Markdown records and an Excel calculator; no automated evaluation runner or analysis pipeline is included.
