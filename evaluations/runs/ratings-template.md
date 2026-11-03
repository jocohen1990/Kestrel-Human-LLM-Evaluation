# Kestrel response ratings template

Copy this blank master into the same run folder as the responses. Rename the copy, for example `model-name_attempt-01_rater-01_ratings.md`. Use a separate copy for each independent rater and attempt. Keep the master blank.

## Rating details

- Run ID: [same ID as the response record]
- Response record filename: [filename]
- Rater ID: [your identifier]
- Rating date: [date you score the responses]
- Task version: kestrel-test-cases-v0.1
- Rubric version: kestrel-rubric-v0.1

## How to fill this in

Use the rubric anchors and administrator task keys. Each section below is one response rating. Replace [unscored] with an integer from 0 to 4 only after reviewing the response. N/A is prefilled according to the task key; it is excluded from the weighted score. An unrun case stays unscored, rather than receiving zeros. Record technical failures separately until the rerun or exclusion rule is defined.

Weights: A factual accuracy = 30; B task coverage = 20; C evidence and uncertainty = 20; D reasoning and calculations = 15; E decision usefulness = 15.

Weighted score (0-100) = 100 x sum(weight x rating for applicable dimensions) / (4 x sum(applicable weights)). Round the final score to one decimal place. Leave it unscored until every applicable dimension is rated.

For required elements, mark each as addressed or omitted using the task key. Record correctness under the appropriate scoring dimension. Explain deductions with source locations or response excerpts. Flags do not add automatic penalties. Allowed rubric flags: fabrication, period error, forecast confusion, calculation error, nonresponse; use none when no flags apply.

Keep independent ratings unchanged. If adjudication is needed, record its status and final ratings separately below. Do not send this completed rating record or the administrator keys to respondents.

## Response ratings

### KESTREL-01 Leadership roles

Prompt (task version kestrel-test-cases-v0.1):

> Name Kestrel's CEO and CFO and identify each person's role.

- Task type: Factual
- Response ID: [unique ID linking to this case in the response record]
- Required elements:
- CEO name and role: [addressed / omitted / not reviewed]
- CFO name and role: [addressed / omitted / not reviewed]

| Dimension | Rating |
| --- | --- |
| A Factual accuracy | [unscored] |
| B Task coverage | [unscored] |
| C Evidence and uncertainty | [unscored] |
| D Reasoning and calculations | N/A |
| E Decision usefulness | N/A |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: [document ID and section]
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: [not requested / pending / complete]
- Final adjudicated ratings and score: [leave blank unless adjudicated; preserve independent scores above]
- Adjudicator, date, and rationale: [leave blank unless adjudicated]

### KESTREL-02 Company background

Prompt (task version kestrel-test-cases-v0.1):

> Identify Kestrel's headquarters, founding year, and the business problem its products address.

- Task type: Factual
- Response ID: [unique ID linking to this case in the response record]
- Required elements:
- Headquarters: [addressed / omitted / not reviewed]
- Founding year: [addressed / omitted / not reviewed]
- Product purpose: [addressed / omitted / not reviewed]

| Dimension | Rating |
| --- | --- |
| A Factual accuracy | [unscored] |
| B Task coverage | [unscored] |
| C Evidence and uncertainty | [unscored] |
| D Reasoning and calculations | N/A |
| E Decision usefulness | N/A |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: [document ID and section]
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: [not requested / pending / complete]
- Final adjudicated ratings and score: [leave blank unless adjudicated; preserve independent scores above]
- Adjudicator, date, and rationale: [leave blank unless adjudicated]

### KESTREL-03 Annual financial results

Prompt (task version kestrel-test-cases-v0.1):

> State fiscal 2025 revenue, fiscal 2024 revenue, and fiscal 2025 net income. Include units and periods.

- Task type: Factual
- Response ID: [unique ID linking to this case in the response record]
- Required elements:
- 2025 revenue: [addressed / omitted / not reviewed]
- 2024 revenue: [addressed / omitted / not reviewed]
- 2025 net income: [addressed / omitted / not reviewed]

| Dimension | Rating |
| --- | --- |
| A Factual accuracy | [unscored] |
| B Task coverage | [unscored] |
| C Evidence and uncertainty | [unscored] |
| D Reasoning and calculations | N/A |
| E Decision usefulness | N/A |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: [document ID and section]
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: [not requested / pending / complete]
- Final adjudicated ratings and score: [leave blank unless adjudicated; preserve independent scores above]
- Adjudicator, date, and rationale: [leave blank unless adjudicated]

### KESTREL-04 Revenue segment mix

Prompt (task version kestrel-test-cases-v0.1):

> Name both revenue segments and give each segment's share of total revenue in 2025.

- Task type: Factual
- Response ID: [unique ID linking to this case in the response record]
- Required elements:
- Route Optimization Software name and share: [addressed / omitted / not reviewed]
- Data Services name and share: [addressed / omitted / not reviewed]

| Dimension | Rating |
| --- | --- |
| A Factual accuracy | [unscored] |
| B Task coverage | [unscored] |
| C Evidence and uncertainty | [unscored] |
| D Reasoning and calculations | N/A |
| E Decision usefulness | N/A |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: [document ID and section]
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: [not requested / pending / complete]
- Final adjudicated ratings and score: [leave blank unless adjudicated; preserve independent scores above]
- Adjudicator, date, and rationale: [leave blank unless adjudicated]

### KESTREL-05 First quarter results

Prompt (task version kestrel-test-cases-v0.1):

> Report Q1 2026 revenue, net income, and diluted EPS, with units.

- Task type: Factual
- Response ID: [unique ID linking to this case in the response record]
- Required elements:
- Revenue: [addressed / omitted / not reviewed]
- Net income: [addressed / omitted / not reviewed]
- Diluted EPS: [addressed / omitted / not reviewed]

| Dimension | Rating |
| --- | --- |
| A Factual accuracy | [unscored] |
| B Task coverage | [unscored] |
| C Evidence and uncertainty | [unscored] |
| D Reasoning and calculations | N/A |
| E Decision usefulness | N/A |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: [document ID and section]
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: [not requested / pending / complete]
- Final adjudicated ratings and score: [leave blank unless adjudicated; preserve independent scores above]
- Adjudicator, date, and rationale: [leave blank unless adjudicated]

### KESTREL-06 Second quarter results

Prompt (task version kestrel-test-cases-v0.1):

> Report Q2 2026 revenue, net income, diluted EPS, and gross margin.

- Task type: Factual
- Response ID: [unique ID linking to this case in the response record]
- Required elements:
- Revenue: [addressed / omitted / not reviewed]
- Net income: [addressed / omitted / not reviewed]
- Diluted EPS: [addressed / omitted / not reviewed]
- Gross margin: [addressed / omitted / not reviewed]

| Dimension | Rating |
| --- | --- |
| A Factual accuracy | [unscored] |
| B Task coverage | [unscored] |
| C Evidence and uncertainty | [unscored] |
| D Reasoning and calculations | N/A |
| E Decision usefulness | N/A |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: [document ID and section]
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: [not requested / pending / complete]
- Final adjudicated ratings and score: [leave blank unless adjudicated; preserve independent scores above]
- Adjudicator, date, and rationale: [leave blank unless adjudicated]

### KESTREL-07 LaneSight launch

Prompt (task version kestrel-test-cases-v0.1):

> Name the product launched in February 2026, describe what it predicts, and state the maximum prediction horizon.

- Task type: Factual
- Response ID: [unique ID linking to this case in the response record]
- Required elements:
- Product name: [addressed / omitted / not reviewed]
- Predicted condition: [addressed / omitted / not reviewed]
- Prediction horizon: [addressed / omitted / not reviewed]

| Dimension | Rating |
| --- | --- |
| A Factual accuracy | [unscored] |
| B Task coverage | [unscored] |
| C Evidence and uncertainty | [unscored] |
| D Reasoning and calculations | N/A |
| E Decision usefulness | N/A |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: [document ID and section]
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: [not requested / pending / complete]
- Final adjudicated ratings and score: [leave blank unless adjudicated; preserve independent scores above]
- Adjudicator, date, and rationale: [leave blank unless adjudicated]

### KESTREL-08 Acquisition terms

Prompt (task version kestrel-test-cases-v0.1):

> Identify the acquired business, completion date, purchase price and payment form, and the acquired company's business.

- Task type: Factual
- Response ID: [unique ID linking to this case in the response record]
- Required elements:
- Target name: [addressed / omitted / not reviewed]
- Completion date: [addressed / omitted / not reviewed]
- Price and payment form: [addressed / omitted / not reviewed]
- Business description: [addressed / omitted / not reviewed]

| Dimension | Rating |
| --- | --- |
| A Factual accuracy | [unscored] |
| B Task coverage | [unscored] |
| C Evidence and uncertainty | [unscored] |
| D Reasoning and calculations | N/A |
| E Decision usefulness | N/A |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: [document ID and section]
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: [not requested / pending / complete]
- Final adjudicated ratings and score: [leave blank unless adjudicated; preserve independent scores above]
- Adjudicator, date, and rationale: [leave blank unless adjudicated]

### KESTREL-09 Capital return policy

Prompt (task version kestrel-test-cases-v0.1):

> State Kestrel's dividend policy and the buyback authorization's maximum amount and authorization month. State whether the sources disclose how much was actually repurchased.

- Task type: Factual
- Response ID: [unique ID linking to this case in the response record]
- Required elements:
- Dividend policy: [addressed / omitted / not reviewed]
- Authorization amount: [addressed / omitted / not reviewed]
- Authorization month: [addressed / omitted / not reviewed]
- Actual repurchase disclosure status: [addressed / omitted / not reviewed]

| Dimension | Rating |
| --- | --- |
| A Factual accuracy | [unscored] |
| B Task coverage | [unscored] |
| C Evidence and uncertainty | [unscored] |
| D Reasoning and calculations | N/A |
| E Decision usefulness | N/A |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: [document ID and section]
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: [not requested / pending / complete]
- Final adjudicated ratings and score: [leave blank unless adjudicated; preserve independent scores above]
- Adjudicator, date, and rationale: [leave blank unless adjudicated]

### KESTREL-10 Borrowing terms

Prompt (task version kestrel-test-cases-v0.1):

> Give the revolving facility size, amount drawn and measurement date, and contractual interest-rate formula.

- Task type: Factual
- Response ID: [unique ID linking to this case in the response record]
- Required elements:
- Facility size: [addressed / omitted / not reviewed]
- Drawn amount and date: [addressed / omitted / not reviewed]
- Interest formula: [addressed / omitted / not reviewed]

| Dimension | Rating |
| --- | --- |
| A Factual accuracy | [unscored] |
| B Task coverage | [unscored] |
| C Evidence and uncertainty | [unscored] |
| D Reasoning and calculations | N/A |
| E Decision usefulness | N/A |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: [document ID and section]
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: [not requested / pending / complete]
- Final adjudicated ratings and score: [leave blank unless adjudicated; preserve independent scores above]
- Adjudicator, date, and rationale: [leave blank unless adjudicated]

### KESTREL-11 First half totals

Prompt (task version kestrel-test-cases-v0.1):

> Calculate first-half 2026 revenue and net income by summing Q1 and Q2. Show both calculations.

- Task type: Calculation
- Response ID: [unique ID linking to this case in the response record]
- Required elements:
- Revenue calculation and total: [addressed / omitted / not reviewed]
- Net income calculation and total: [addressed / omitted / not reviewed]

| Dimension | Rating |
| --- | --- |
| A Factual accuracy | [unscored] |
| B Task coverage | [unscored] |
| C Evidence and uncertainty | [unscored] |
| D Reasoning and calculations | [unscored] |
| E Decision usefulness | N/A |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: [document ID and section]
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: [not requested / pending / complete]
- Final adjudicated ratings and score: [leave blank unless adjudicated; preserve independent scores above]
- Adjudicator, date, and rationale: [leave blank unless adjudicated]

### KESTREL-12 Sequential revenue growth

Prompt (task version kestrel-test-cases-v0.1):

> Calculate the dollar and percentage increase in revenue from Q1 to Q2 2026. Show the base used for the percentage.

- Task type: Calculation
- Response ID: [unique ID linking to this case in the response record]
- Required elements:
- Dollar increase: [addressed / omitted / not reviewed]
- Percentage calculation with Q1 base: [addressed / omitted / not reviewed]

| Dimension | Rating |
| --- | --- |
| A Factual accuracy | [unscored] |
| B Task coverage | [unscored] |
| C Evidence and uncertainty | [unscored] |
| D Reasoning and calculations | [unscored] |
| E Decision usefulness | N/A |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: [document ID and section]
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: [not requested / pending / complete]
- Final adjudicated ratings and score: [leave blank unless adjudicated; preserve independent scores above]
- Adjudicator, date, and rationale: [leave blank unless adjudicated]

### KESTREL-13 Gross margin movement

Prompt (task version kestrel-test-cases-v0.1):

> Calculate the gross margin improvement from Q1 to Q2 2026 in percentage points and basis points. Show the subtraction.

- Task type: Calculation
- Response ID: [unique ID linking to this case in the response record]
- Required elements:
- Percentage-point calculation: [addressed / omitted / not reviewed]
- Basis-point conversion: [addressed / omitted / not reviewed]

| Dimension | Rating |
| --- | --- |
| A Factual accuracy | [unscored] |
| B Task coverage | [unscored] |
| C Evidence and uncertainty | [unscored] |
| D Reasoning and calculations | [unscored] |
| E Decision usefulness | N/A |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: [document ID and section]
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: [not requested / pending / complete]
- Final adjudicated ratings and score: [leave blank unless adjudicated; preserve independent scores above]
- Adjudicator, date, and rationale: [leave blank unless adjudicated]

### KESTREL-14 Enterprise customer growth

Prompt (task version kestrel-test-cases-v0.1):

> Calculate the increase in enterprise customers from the end of 2025 to the end of Q2 2026 in customers and percent. Identify the comparison period.

- Task type: Calculation
- Response ID: [unique ID linking to this case in the response record]
- Required elements:
- Customer increase: [addressed / omitted / not reviewed]
- Percent calculation: [addressed / omitted / not reviewed]
- Comparison period: [addressed / omitted / not reviewed]

| Dimension | Rating |
| --- | --- |
| A Factual accuracy | [unscored] |
| B Task coverage | [unscored] |
| C Evidence and uncertainty | [unscored] |
| D Reasoning and calculations | [unscored] |
| E Decision usefulness | N/A |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: [document ID and section]
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: [not requested / pending / complete]
- Final adjudicated ratings and score: [leave blank unless adjudicated; preserve independent scores above]
- Adjudicator, date, and rationale: [leave blank unless adjudicated]

### KESTREL-15 Estimated segment revenue

Prompt (task version kestrel-test-cases-v0.1):

> Estimate 2025 revenue for each segment using the reported revenue and segment shares. Show your calculations and identify the estimates as derived.

- Task type: Calculation
- Response ID: [unique ID linking to this case in the response record]
- Required elements:
- Software estimate and calculation: [addressed / omitted / not reviewed]
- Data Services estimate and calculation: [addressed / omitted / not reviewed]
- Derived estimate qualification: [addressed / omitted / not reviewed]

| Dimension | Rating |
| --- | --- |
| A Factual accuracy | [unscored] |
| B Task coverage | [unscored] |
| C Evidence and uncertainty | [unscored] |
| D Reasoning and calculations | [unscored] |
| E Decision usefulness | N/A |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: [document ID and section]
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: [not requested / pending / complete]
- Final adjudicated ratings and score: [leave blank unless adjudicated; preserve independent scores above]
- Adjudicator, date, and rationale: [leave blank unless adjudicated]

### KESTREL-16 Reported versus calculated growth

Prompt (task version kestrel-test-cases-v0.1):

> State the reported FY2025 revenue growth rate, calculate growth from the displayed FY2024 and FY2025 revenues, and explain whether the results are consistent after rounding.

- Task type: Calculation
- Response ID: [unique ID linking to this case in the response record]
- Required elements:
- Reported rate: [addressed / omitted / not reviewed]
- Calculated growth: [addressed / omitted / not reviewed]
- Rounding explanation: [addressed / omitted / not reviewed]

| Dimension | Rating |
| --- | --- |
| A Factual accuracy | [unscored] |
| B Task coverage | [unscored] |
| C Evidence and uncertainty | [unscored] |
| D Reasoning and calculations | [unscored] |
| E Decision usefulness | N/A |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: [document ID and section]
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: [not requested / pending / complete]
- Final adjudicated ratings and score: [leave blank unless adjudicated; preserve independent scores above]
- Adjudicator, date, and rationale: [leave blank unless adjudicated]

### KESTREL-17 Quarterly outlook comparison

Prompt (task version kestrel-test-cases-v0.1):

> State the Q2 revenue outlook issued in the Q1 release, compare actual Q2 revenue with its upper bound, and calculate the dollar and percentage beat against that upper bound.

- Task type: Calculation
- Response ID: [unique ID linking to this case in the response record]
- Required elements:
- Prior outlook range: [addressed / omitted / not reviewed]
- Actual and direction versus upper bound: [addressed / omitted / not reviewed]
- Dollar beat: [addressed / omitted / not reviewed]
- Percentage beat calculation: [addressed / omitted / not reviewed]

| Dimension | Rating |
| --- | --- |
| A Factual accuracy | [unscored] |
| B Task coverage | [unscored] |
| C Evidence and uncertainty | [unscored] |
| D Reasoning and calculations | [unscored] |
| E Decision usefulness | N/A |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: [document ID and section]
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: [not requested / pending / complete]
- Final adjudicated ratings and score: [leave blank unless adjudicated; preserve independent scores above]
- Adjudicator, date, and rationale: [leave blank unless adjudicated]

### KESTREL-18 Revenue needed in the second half

Prompt (task version kestrel-test-cases-v0.1):

> Calculate the H2 2026 revenue range needed to reach the full-year revenue guidance range, using reported H1 revenue. State whether your result is company-issued H2 guidance.

- Task type: Calculation
- Response ID: [unique ID linking to this case in the response record]
- Required elements:
- H1 input: [addressed / omitted / not reviewed]
- Lower-bound calculation: [addressed / omitted / not reviewed]
- Upper-bound calculation: [addressed / omitted / not reviewed]
- Status of derived range: [addressed / omitted / not reviewed]

| Dimension | Rating |
| --- | --- |
| A Factual accuracy | [unscored] |
| B Task coverage | [unscored] |
| C Evidence and uncertainty | [unscored] |
| D Reasoning and calculations | [unscored] |
| E Decision usefulness | N/A |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: [document ID and section]
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: [not requested / pending / complete]
- Final adjudicated ratings and score: [leave blank unless adjudicated; preserve independent scores above]
- Adjudicator, date, and rationale: [leave blank unless adjudicated]

### KESTREL-19 Revolver capacity and limits

Prompt (task version kestrel-test-cases-v0.1):

> Calculate nominal undrawn revolver capacity at June 30, 2026. Can it establish Kestrel's cash balance or unrestricted borrowing availability? Explain each limit.

- Task type: Calculation
- Response ID: [unique ID linking to this case in the response record]
- Required elements:
- Undrawn-capacity calculation: [addressed / omitted / not reviewed]
- Cash-balance limitation: [addressed / omitted / not reviewed]
- Borrowing-availability limitation: [addressed / omitted / not reviewed]

| Dimension | Rating |
| --- | --- |
| A Factual accuracy | [unscored] |
| B Task coverage | [unscored] |
| C Evidence and uncertainty | [unscored] |
| D Reasoning and calculations | [unscored] |
| E Decision usefulness | N/A |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: [document ID and section]
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: [not requested / pending / complete]
- Final adjudicated ratings and score: [leave blank unless adjudicated; preserve independent scores above]
- Adjudicator, date, and rationale: [leave blank unless adjudicated]

### KESTREL-20 Information that is not disclosed

Prompt (task version kestrel-test-cases-v0.1):

> Using only the supplied sources, state Kestrel's share price, name its cloud provider, and give the exact SOFR rate applicable to June 30, 2026 borrowings. For each item, say if it can be determined.

- Task type: Source limits
- Response ID: [unique ID linking to this case in the response record]
- Required elements:
- Share-price disclosure status: [addressed / omitted / not reviewed]
- Cloud-provider disclosure status: [addressed / omitted / not reviewed]
- SOFR disclosure status: [addressed / omitted / not reviewed]

| Dimension | Rating |
| --- | --- |
| A Factual accuracy | [unscored] |
| B Task coverage | [unscored] |
| C Evidence and uncertainty | [unscored] |
| D Reasoning and calculations | N/A |
| E Decision usefulness | N/A |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: [document ID and section]
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: [not requested / pending / complete]
- Final adjudicated ratings and score: [leave blank unless adjudicated; preserve independent scores above]
- Adjudicator, date, and rationale: [leave blank unless adjudicated]

### KESTREL-21 Acquisition integration priorities

Prompt (task version kestrel-test-cases-v0.1):

> Recommend two distinct integration workstreams for Bramblecote. For each, give the source-based rationale, one tradeoff, and a practical next step. Identify one missing fact needed before committing resources.

- Task type: Business analysis
- Response ID: [unique ID linking to this case in the response record]
- Required elements:
- Workstream 1: [addressed / omitted / not reviewed]
- Rationale 1: [addressed / omitted / not reviewed]
- Tradeoff 1: [addressed / omitted / not reviewed]
- Next step 1: [addressed / omitted / not reviewed]
- Workstream 2: [addressed / omitted / not reviewed]
- Rationale 2: [addressed / omitted / not reviewed]
- Tradeoff 2: [addressed / omitted / not reviewed]
- Next step 2: [addressed / omitted / not reviewed]
- Missing decision-critical fact: [addressed / omitted / not reviewed]

| Dimension | Rating |
| --- | --- |
| A Factual accuracy | [unscored] |
| B Task coverage | [unscored] |
| C Evidence and uncertainty | [unscored] |
| D Reasoning and calculations | [unscored] |
| E Decision usefulness | [unscored] |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: [document ID and section]
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: [not requested / pending / complete]
- Final adjudicated ratings and score: [leave blank unless adjudicated; preserve independent scores above]
- Adjudicator, date, and rationale: [leave blank unless adjudicated]

### KESTREL-22 Cloud resilience decision

Prompt (task version kestrel-test-cases-v0.1):

> Recommend an initial approach to Kestrel's cloud concentration risk. Compare two mitigation options, identify one tradeoff between them, propose one next step, and name one missing fact that could change the choice.

- Task type: Business analysis
- Response ID: [unique ID linking to this case in the response record]
- Required elements:
- Initial recommendation: [addressed / omitted / not reviewed]
- Two mitigation options: [addressed / omitted / not reviewed]
- Comparative tradeoff: [addressed / omitted / not reviewed]
- Next step: [addressed / omitted / not reviewed]
- Decision-changing information: [addressed / omitted / not reviewed]

| Dimension | Rating |
| --- | --- |
| A Factual accuracy | [unscored] |
| B Task coverage | [unscored] |
| C Evidence and uncertainty | [unscored] |
| D Reasoning and calculations | [unscored] |
| E Decision usefulness | [unscored] |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: [document ID and section]
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: [not requested / pending / complete]
- Final adjudicated ratings and score: [leave blank unless adjudicated; preserve independent scores above]
- Adjudicator, date, and rationale: [leave blank unless adjudicated]

### KESTREL-23 Customer concentration response

Prompt (task version kestrel-test-cases-v0.1):

> Estimate the 2025 revenue attributable to the largest customer. Recommend a mitigation, explain one tradeoff and one next step, and state one limit on interpreting the estimate as a future-loss forecast.

- Task type: Business analysis
- Response ID: [unique ID linking to this case in the response record]
- Required elements:
- Revenue estimate and calculation: [addressed / omitted / not reviewed]
- Mitigation: [addressed / omitted / not reviewed]
- Tradeoff: [addressed / omitted / not reviewed]
- Next step: [addressed / omitted / not reviewed]
- Forecast limitation: [addressed / omitted / not reviewed]

| Dimension | Rating |
| --- | --- |
| A Factual accuracy | [unscored] |
| B Task coverage | [unscored] |
| C Evidence and uncertainty | [unscored] |
| D Reasoning and calculations | [unscored] |
| E Decision usefulness | [unscored] |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: [document ID and section]
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: [not requested / pending / complete]
- Final adjudicated ratings and score: [leave blank unless adjudicated; preserve independent scores above]
- Adjudicator, date, and rationale: [leave blank unless adjudicated]

### KESTREL-24 Capital allocation choice

Prompt (task version kestrel-test-cases-v0.1):

> Recommend whether management should execute additional buybacks immediately or first review liquidity. Address the authorization, acquisition payment, and revolver balance; give one tradeoff, one next step, and two missing inputs.

- Task type: Business analysis
- Response ID: [unique ID linking to this case in the response record]
- Required elements:
- Recommendation: [addressed / omitted / not reviewed]
- Buyback authorization context: [addressed / omitted / not reviewed]
- Acquisition payment context: [addressed / omitted / not reviewed]
- Revolver context: [addressed / omitted / not reviewed]
- Tradeoff: [addressed / omitted / not reviewed]
- Next step: [addressed / omitted / not reviewed]
- Missing input 1: [addressed / omitted / not reviewed]
- Missing input 2: [addressed / omitted / not reviewed]

| Dimension | Rating |
| --- | --- |
| A Factual accuracy | [unscored] |
| B Task coverage | [unscored] |
| C Evidence and uncertainty | [unscored] |
| D Reasoning and calculations | [unscored] |
| E Decision usefulness | [unscored] |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: [document ID and section]
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: [not requested / pending / complete]
- Final adjudicated ratings and score: [leave blank unless adjudicated; preserve independent scores above]
- Adjudicator, date, and rationale: [leave blank unless adjudicated]

### KESTREL-25 Full-year growth execution

Prompt (task version kestrel-test-cases-v0.1):

> Calculate the H2 average quarterly revenue needed to reach the midpoint of FY2026 guidance. Compare it with Q2 revenue, assess what this implies for execution without predicting success, and propose a monitoring action and one data request.

- Task type: Business analysis
- Response ID: [unique ID linking to this case in the response record]
- Required elements:
- Midpoint and H1 basis: [addressed / omitted / not reviewed]
- Required H2 average calculation: [addressed / omitted / not reviewed]
- Q2 comparison: [addressed / omitted / not reviewed]
- Qualified execution assessment: [addressed / omitted / not reviewed]
- Monitoring action: [addressed / omitted / not reviewed]
- Data request: [addressed / omitted / not reviewed]

| Dimension | Rating |
| --- | --- |
| A Factual accuracy | [unscored] |
| B Task coverage | [unscored] |
| C Evidence and uncertainty | [unscored] |
| D Reasoning and calculations | [unscored] |
| E Decision usefulness | [unscored] |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: [document ID and section]
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: [not requested / pending / complete]
- Final adjudicated ratings and score: [leave blank unless adjudicated; preserve independent scores above]
- Adjudicator, date, and rationale: [leave blank unless adjudicated]

### KESTREL-26 Profitability interpretation

Prompt (task version kestrel-test-cases-v0.1):

> Calculate net margin for Q1 and Q2 2026 and assess the direction of profitability. Distinguish what the figures show from what they cannot explain. Recommend one follow-up analysis, with its tradeoff and first step.

- Task type: Business analysis
- Response ID: [unique ID linking to this case in the response record]
- Required elements:
- Q1 net-margin calculation: [addressed / omitted / not reviewed]
- Q2 net-margin calculation: [addressed / omitted / not reviewed]
- Direction: [addressed / omitted / not reviewed]
- Causal limitation: [addressed / omitted / not reviewed]
- Follow-up recommendation: [addressed / omitted / not reviewed]
- Tradeoff: [addressed / omitted / not reviewed]
- First step: [addressed / omitted / not reviewed]

| Dimension | Rating |
| --- | --- |
| A Factual accuracy | [unscored] |
| B Task coverage | [unscored] |
| C Evidence and uncertainty | [unscored] |
| D Reasoning and calculations | [unscored] |
| E Decision usefulness | [unscored] |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: [document ID and section]
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: [not requested / pending / complete]
- Final adjudicated ratings and score: [leave blank unless adjudicated; preserve independent scores above]
- Adjudicator, date, and rationale: [leave blank unless adjudicated]

### KESTREL-27 LaneSight commercial assessment

Prompt (task version kestrel-test-cases-v0.1):

> Propose a way to evaluate LaneSight's commercial promise. Connect it to Kestrel's business, propose two success measures, identify one tradeoff, specify a first step, and name one missing input.

- Task type: Business analysis
- Response ID: [unique ID linking to this case in the response record]
- Required elements:
- Business connection: [addressed / omitted / not reviewed]
- Success measure 1: [addressed / omitted / not reviewed]
- Success measure 2: [addressed / omitted / not reviewed]
- Tradeoff: [addressed / omitted / not reviewed]
- First step: [addressed / omitted / not reviewed]
- Missing input: [addressed / omitted / not reviewed]

| Dimension | Rating |
| --- | --- |
| A Factual accuracy | [unscored] |
| B Task coverage | [unscored] |
| C Evidence and uncertainty | [unscored] |
| D Reasoning and calculations | [unscored] |
| E Decision usefulness | [unscored] |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: [document ID and section]
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: [not requested / pending / complete]
- Final adjudicated ratings and score: [leave blank unless adjudicated; preserve independent scores above]
- Adjudicator, date, and rationale: [leave blank unless adjudicated]

### KESTREL-28 Fuel volatility exposure

Prompt (task version kestrel-test-cases-v0.1):

> Explain one plausible pathway from fuel price volatility to Kestrel's revenue risk, recommend a response, give one tradeoff and one next step, and identify one missing fact that limits confidence.

- Task type: Business analysis
- Response ID: [unique ID linking to this case in the response record]
- Required elements:
- Risk pathway: [addressed / omitted / not reviewed]
- Recommendation: [addressed / omitted / not reviewed]
- Tradeoff: [addressed / omitted / not reviewed]
- Next step: [addressed / omitted / not reviewed]
- Confidence-limiting information: [addressed / omitted / not reviewed]

| Dimension | Rating |
| --- | --- |
| A Factual accuracy | [unscored] |
| B Task coverage | [unscored] |
| C Evidence and uncertainty | [unscored] |
| D Reasoning and calculations | [unscored] |
| E Decision usefulness | [unscored] |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: [document ID and section]
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: [not requested / pending / complete]
- Final adjudicated ratings and score: [leave blank unless adjudicated; preserve independent scores above]
- Adjudicator, date, and rationale: [leave blank unless adjudicated]

### KESTREL-29 Key personnel risk response

Prompt (task version kestrel-test-cases-v0.1):

> Recommend two distinct responses to key personnel risk. Explain the rationale for each, compare one tradeoff between them, identify a first step, and state one missing fact needed to choose the mix.

- Task type: Business analysis
- Response ID: [unique ID linking to this case in the response record]
- Required elements:
- Response 1: [addressed / omitted / not reviewed]
- Rationale 1: [addressed / omitted / not reviewed]
- Response 2: [addressed / omitted / not reviewed]
- Rationale 2: [addressed / omitted / not reviewed]
- Comparative tradeoff: [addressed / omitted / not reviewed]
- First step: [addressed / omitted / not reviewed]
- Missing decision input: [addressed / omitted / not reviewed]

| Dimension | Rating |
| --- | --- |
| A Factual accuracy | [unscored] |
| B Task coverage | [unscored] |
| C Evidence and uncertainty | [unscored] |
| D Reasoning and calculations | [unscored] |
| E Decision usefulness | [unscored] |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: [document ID and section]
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: [not requested / pending / complete]
- Final adjudicated ratings and score: [leave blank unless adjudicated; preserve independent scores above]
- Adjudicator, date, and rationale: [leave blank unless adjudicated]

### KESTREL-30 Management briefing with priorities

Prompt (task version kestrel-test-cases-v0.1):

> Write a brief management assessment with one growth signal, one profitability signal, and one financial constraint or uncertainty. Recommend two priorities; for each give a rationale, tradeoff, and next step. Separate disclosed facts, derived values, and judgments.

- Task type: Business analysis
- Response ID: [unique ID linking to this case in the response record]
- Required elements:
- Growth signal: [addressed / omitted / not reviewed]
- Profitability signal: [addressed / omitted / not reviewed]
- Financial constraint or uncertainty: [addressed / omitted / not reviewed]
- Priority 1: [addressed / omitted / not reviewed]
- Rationale 1: [addressed / omitted / not reviewed]
- Tradeoff 1: [addressed / omitted / not reviewed]
- Next step 1: [addressed / omitted / not reviewed]
- Priority 2: [addressed / omitted / not reviewed]
- Rationale 2: [addressed / omitted / not reviewed]
- Tradeoff 2: [addressed / omitted / not reviewed]
- Next step 2: [addressed / omitted / not reviewed]
- Fact versus inference distinction: [addressed / omitted / not reviewed]

| Dimension | Rating |
| --- | --- |
| A Factual accuracy | [unscored] |
| B Task coverage | [unscored] |
| C Evidence and uncertainty | [unscored] |
| D Reasoning and calculations | [unscored] |
| E Decision usefulness | [unscored] |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: [document ID and section]
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: [not requested / pending / complete]
- Final adjudicated ratings and score: [leave blank unless adjudicated; preserve independent scores above]
- Adjudicator, date, and rationale: [leave blank unless adjudicated]
