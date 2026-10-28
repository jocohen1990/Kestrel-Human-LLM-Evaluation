# Kestrel Human to LLM Evaluation

Workspace for designing, running, and analyzing human-to-LLM evaluations.

## Project layout

| Location | Purpose |
| --- | --- |
| `PROJECT_CONTEXT.md` | Project status, confirmed decisions, and handoff notes for future chats |
| `docs/` | Study design, procedures, and data definitions |
| `data/raw/` | Original inputs and collected data; preserve these unchanged |
| `data/processed/` | Cleaned or transformed data derived from raw inputs |
| `data/examples/` | Small synthetic or shareable examples |
| `evaluations/tasks/` | Task definitions, prompts, and reference materials |
| `evaluations/rubrics/` | Scoring criteria and rating instructions |
| `evaluations/runs/` | Run records, responses, ratings, and run-specific metadata |
| `analysis/` | Analysis notebooks and reusable analysis code |
| `reports/` | Findings and final deliverables |
| `reports/figures/` | Figures used in reports |
| `scripts/` | Repeatable preparation, validation, and execution utilities |

## Getting started

1. Define the evaluation question and study design in `docs/evaluation-plan.md`.
2. Define record fields in `docs/data-dictionary.md`.
3. Add evaluation tasks and scoring rubrics to `evaluations/`.
4. Conduct a small pilot and record its inputs, settings, outputs, and ratings together in a run folder.
5. Analyze results and document findings in `reports/`.

Use stable task and run identifiers to connect inputs, responses, and ratings. Prefer run folder names such as `YYYY-MM-DD_short-description`.

No programming language, model provider, dependencies, or scoring method has been selected yet. The current structure contains no evaluation data or executable implementation.
