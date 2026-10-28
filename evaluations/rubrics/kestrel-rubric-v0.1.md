# Kestrel Human and LLM Response Evaluation Rubric

Version 0.1 | October 27 2026 | Proposed for pilot review

## Purpose and scope

Use this rubric to score answers to questions about Kestrel Freight Analytics using the four supplied company documents. Apply the same task instructions, source access, and scoring criteria to human and LLM responses. The unit of evaluation is one response to one task. Score what the response says, rather than its fluency, length, or apparent confidence.

This rubric measures factual answers and business analysis grounded in the documents, including calculations, risk assessment, and recommendations. Kestrel and its reported figures are fictional evaluation materials. Business judgments may differ; score their support, reasoning, and usefulness rather than agreement with a preferred recommendation.

## Source set

- S1: `data/raw/annual_report_2025.md` — company background, leadership, fiscal 2025 results, segments, customers, employees, and capital return.
- S2: `data/raw/q1_2026_earnings.md` — Q1 2026 results, comparative figures, LaneSight launch, and Q2 revenue outlook.
- S3: `data/raw/q2_2026_earnings.md` — Q2 2026 results, acquisition, customers, and full-year revenue guidance.
- S4: `data/raw/risk_factors_2026.md` — concentration, cloud dependency, industry exposure, credit facility, integration, and key personnel risks.

The source documents are the authority for this evaluation. Preserve the reporting period and distinguish historical results, forecasts, and authorizations. Use actual Q2 results for actual-Q2 questions; use the Q1 outlook when the question asks what was forecast. Treat unresolved source conflicts as uncertainty rather than silently selecting a value.

## Scoring model

| Dimension | Weight | What it measures |
| --- | --- | --- |
| A Factual accuracy | 30 | Correct facts, numbers, units, dates, and status |
| B Task coverage | 20 | Required parts of the question addressed |
| C Evidence and uncertainty | 20 | Traceable support and appropriate limits on claims |
| D Reasoning and calculations | 15 | Valid arithmetic, comparisons, and inference |
| E Decision usefulness | 15 | Actionable recommendations and relevant tradeoffs |

Rate each applicable dimension from 0 to 4. Weighted score = 100 × sum of applicable weight × rating ÷ 4, divided by the sum of applicable weights. Round only the final score to one decimal place. Example: A=3, B=4, C=3, D=4, E=3 gives 83.8 out of 100. Premark D as not applicable when the task needs no calculation, comparison, or inference; premark E as not applicable when it requests no recommendation or decision support. A=3, B=4, C=3 with D and E excluded gives 82.1 out of 100.

Report factual and business-analysis task results separately, along with applicable dimensions, because normalized scores on different task types do not measure identical skills.

Keep dimension scores and flags alongside the overall score. No pass threshold or performance bands are established in this version. Set them only after calibration and pilot review.

<!-- pagebreak -->

## Factual accuracy anchors

Assess substantive claims against the sources and task answer key. A material error changes the answer to a requested fact or could change the reader's conclusion. A minor error leaves that conclusion intact, such as harmless rounding beyond the required precision.

| Rating | Observable standard |
| --- | --- |
| 4 | All substantive stated facts are correct. Numbers, units, time periods, entities, and actual-versus-forecast status are preserved. |
| 3 | One minor factual error; no material errors. The requested conclusion remains correct. |
| 2 | One material factual error, or multiple minor errors; the response still contains useful correct substance. |
| 1 | Multiple material errors, or a central answer is contradicted by the sources, with little useful correct substance. |
| 0 | No correct substantive answer, or the response is entirely incorrect, unrelated, or empty. |

An omitted fact is normally a coverage issue, not a factual error. However, a blanket abstention on an answerable task earns A=0 because it supplies no correct substantive answer. An accurate statement that a requested fact is not disclosed can earn full accuracy when that is the correct answer.

## Task coverage anchors

Before collecting responses, define the required answer elements and their relative importance. Unless specified otherwise in the task key, give each element equal weight. An element counts as addressed when the response attempts the requested item; whether the attempt is correct is scored under A or D.

| Rating | Observable standard |
| --- | --- |
| 4 | Addresses all required answer elements and requested output requirements. |
| 3 | Addresses at least 75 percent but less than 100 percent of required elements. |
| 2 | Addresses at least 50 percent but less than 75 percent of required elements. |
| 1 | Addresses more than zero but less than 50 percent of required elements. |
| 0 | Addresses none of the required elements, or is empty or unrelated. |

For a single-element question, coverage is normally 4 or 0. Do not add unstated requirements for length, prose style, or extra background. If the prompt requires multiple risks, name how many are needed in the answer key. An explicit, appropriate statement that information is unavailable counts as addressing that element.

<!-- pagebreak -->

## Evidence and uncertainty anchors

Assess whether substantive claims can be traced to the supplied documents or to a transparent calculation from them. Exact citation formatting is not required unless the task asks for it. Source IDs, filenames, or unambiguous document titles are acceptable. Do not require external research.

| Rating | Observable standard |
| --- | --- |
| 4 | Claims are supported and traceable; derived values and assumptions are identifiable; missing information and uncertainty are handled correctly. Explicit citations meet any prompt requirement. |
| 3 | Support is recoverable, but one minor attribution or uncertainty gap remains; it does not change the interpretation. |
| 2 | A material support gap, unsupported inference, or missed disclosure limit remains, while some important claims are grounded. |
| 1 | Most central claims lack support, citations are substantially misleading, or unsupported certainty dominates. |
| 0 | No support can be established, cited evidence is fabricated throughout, or the response is empty or unrelated. |

Without a citation requirement, do not lower the score solely because the answer omits source labels. A short correct factual answer may earn 4 if its support is unambiguous. When citations are explicitly required, missing all citations caps C at 2; a wrong citation for the central answer also caps C at 2. Evaluate more severe failures against the anchors.

## Reasoning and calculation anchors

Apply only to tasks requiring arithmetic, comparison, synthesis that draws a conclusion, or inference. A task requiring only retrieval or listing has D marked not applicable in advance. A correct direct answer does not need unnecessary explanatory steps unless the prompt requires them.

| Rating | Observable standard |
| --- | --- |
| 4 | Method and conclusion are valid. Required arithmetic is correct, bases and periods match, and precision is appropriate. |
| 3 | Valid method with a minor arithmetic, rounding, or explanation slip that leaves the main conclusion intact. |
| 2 | Partly valid reasoning, but one material method or arithmetic error affects the conclusion. |
| 1 | A small relevant attempt is present, but the method or conclusion is mostly invalid. |
| 0 | No relevant reasoning or requested calculation is supplied, or the method is wholly invalid. |

Avoid duplicate penalties for the same defect. Score an incorrect copied source figure under A; score an arithmetic or inference error under D. If the method is valid for an incorrectly copied input, assess the method accordingly and flag the input error. Lower C separately only for an additional support or uncertainty failure. Coverage measures addressed elements, not correctness.

<!-- pagebreak -->

## Decision usefulness anchors

Apply E when a task requests recommendations, prioritization, or decision support. Premark it as not applicable for factual retrieval, calculations alone, and purely descriptive summaries. Score practical usefulness here; score factual correctness under A, evidence and uncertainty under C, and logical validity under D.

| Rating | Observable standard |
| --- | --- |
| 4 | Gives a clear recommendation or prioritization suited to the requested decision; identifies material tradeoffs and feasible next steps, including information needed to act. |
| 3 | Gives a useful recommendation and relevant tradeoff, but one minor implementation detail or decision condition is missing. |
| 2 | Gives a relevant recommendation, but material tradeoffs or actionable next steps are missing or too vague to guide the decision. |
| 1 | Offers mostly generic advice with little connection to the requested decision or practical action. |
| 0 | Supplies no relevant recommendation or decision support when requested. |

Do not require an invented budget, owner, deadline, or target. If a response proposes one, it must label it as a proposal. A defensible recommendation to defer a decision can earn full credit when it names the decision-critical information needed and a practical next step. Do not penalize a recommendation merely for differing from the calibration example.

## Business analysis calibration example

Example prompt: Recommend two management priorities following Q2 2026. Explain the evidence, a tradeoff for each priority, and a practical next step. Separate disclosed facts from your analysis.

One defensible answer prioritizes acquisition integration and service resilience. S3 establishes the $64 million cash acquisition of Bramblecote; S4 identifies integration risk. A response could recommend an integration review with milestones and customer-service checks. The tradeoff is management effort and integration expense versus expected operational benefits. The documents do not quantify synergies, so a response should propose validating them rather than claim savings are established.

A second priority could address the single-cloud-provider dependency disclosed in S4. A response could propose testing recovery procedures and assessing alternatives. The tradeoff is resilience versus cost and operational complexity. The documents do not establish that a second provider is affordable or necessary, so a comparative assessment is a stronger next step than an unconditional migration mandate.

Other supported priorities, such as customer concentration, financing capacity, or growth execution, are acceptable. Each selected priority counts as one coverage element; evidence, tradeoffs, and next steps are additional elements if requested. Freeze the element list before collection. Do not treat the reference choices as the only correct answers.

<!-- pagebreak -->

## Kestrel calibration answer key

These examples establish reference answers and common error checks. They are calibration material, not a finalized benchmark. Select task wording and required elements before collecting scored responses. Derived values below are calculated from the displayed source figures.

| Example task | Reference answer and source |
| --- | --- |
| Name the CEO and CFO | Dana Whitfield is CEO; Marcus Oyelaran is CFO. S1. |
| Give fiscal 2025 revenue and net income | Revenue $412.6 million; net income $38.9 million. S1. |
| Give the fiscal 2025 segment shares | Route Optimization Software 62 percent; Data Services 38 percent. S1. |
| Give Q2 2026 revenue and diluted EPS | Revenue $116.0 million; diluted EPS $0.38. S3. Do not substitute Q1 values of $108.3 million and $0.31. |
| Did Q2 revenue exceed its prior outlook | Yes. Actual $116.0 million versus outlook $112 million to $115 million; $1.0 million above the upper bound. S2 and S3. |
| Calculate first half 2026 revenue | $108.3 million + $116.0 million = $224.3 million. S2 and S3. |
| Calculate gross margin change from Q1 to Q2 2026 | 72.1 percent minus 71.4 percent = 0.7 percentage points, or 70 basis points. S2 and S3. This is not a 0.7 percent relative increase. |
| Calculate customer growth from end 2025 to end Q2 2026 | 3,120 minus 2,850 = 270; 270 divided by 2,850 × 100 = approximately 9.47 percent. S1 and S3. This is not year-over-year growth. |
| Identify the acquisition and consideration | Bramblecote Telematics, acquired June 12 2026 for $64 million in cash; provider of in-truck sensor data. S3. |
| Calculate undrawn revolving facility capacity | $150 million facility minus $40 million drawn = $110 million undrawn as of June 30 2026. S4. This is nominal unused capacity, not cash or guaranteed available liquidity. |
| State full-year 2026 revenue guidance | $470 million to $480 million; guidance, not actual revenue. S3. |
| Give Kestrel's share price or the cloud provider's name | Not disclosed in the supplied documents. Do not invent a value or vendor. S1 through S4. |

Accept equivalent wording and converted units. Unless a task sets tighter precision, accept amounts to the displayed precision and derived percentage changes within 0.1 percentage point of the reference. A percentage-point change and a relative percent change are different quantities. Preserve the source's reported growth rates when asked what it reported; recompute from displayed figures when asked to calculate growth.

<!-- pagebreak -->

## Rater procedure

1. Freeze the task prompt, allowed source set, answer key, required elements, applicable dimensions, citation requirements, and numerical tolerances before responses are collected. Keep calibration examples separate from held-out evaluation questions.
2. Give human and LLM respondents comparable source access and task instructions. Record differences in time limits or tool access. Record model version and generation settings separately from the blinded rating packet.
3. Assign response IDs and conceal respondent type from raters where feasible. Score independently before discussing disagreements. Do not reward verbosity, preferred wording, or confident tone.
4. Mark required elements as addressed or omitted. Verify substantive claims and calculations. Assign A through E using the anchors, and record evidence for deductions.
5. Record flags without adding automatic score penalties. Use fabrication for invented facts or citations, period error for a wrong reporting period, forecast confusion for treating guidance as actual, calculation error for invalid arithmetic, and nonresponse for an empty or irrelevant answer.
6. Use two independent raters for the calibration set. Discuss disagreements, revise ambiguous task keys or anchors, and rescore affected pilot responses consistently. Preserve original ratings and adjudicated ratings separately. Pilot results should determine the later review policy.

For an empty response, assign zero to all applicable dimensions and flag nonresponse. For a source-supported abstention on an unanswerable question, score it as a correct answer. For an unsupported abstention on an answerable question, award no factual or coverage credit for the missing answer; C may still credit an honest statement of uncertainty. Keep technical failures separate from scored responses until a rerun or exclusion policy is defined.

## Rating record

Record one row per rater and response with these fields: rubric version, task version, task type, run ID, task ID, response ID, rater ID, required elements addressed, A rating, B rating, C rating, D and E ratings or not applicable, weighted score, flags, supporting source locations, and short deduction notes. Add adjudication status and final adjudicated ratings without overwriting the independent scores.

## Decisions for pilot review

The study covers both factual answers and business analysis. The proposed weights and anchors require calibration. Define task count and difficulty for each type, citation rules, source and tool access, time limits, and the human comparison group. Agree on aggregation across task types before reporting a combined comparison.
