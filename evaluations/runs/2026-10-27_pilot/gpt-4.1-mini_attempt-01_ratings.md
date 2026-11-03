# Kestrel response ratings template

## Rating details

- Run ID: [01]
- Response record filename: [gpt-4.1-mini_attempt-01_responses.md]
- Rater ID: [JOC]
- Rating date: [11/2/2026]
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

Model response (verbatim from gpt-4.1-mini_attempt-01_responses.md):

Kestrel's CEO is Dana Whitfield, who serves as the Chief Executive Officer, responsible for overall company leadership and strategic direction.

Kestrel's CFO is Marcus Oyelaran, who serves as the Chief Financial Officer, responsible for managing the company's financial actions.

- Task type: Factual
- Response ID: KESTREL-01
- Required elements: Name of CEO, CFO and identify each person's role.
- CEO name and role: Addressed
- CFO name and role: Addressed

| Dimension | Rating | Reason |
| --- | --- |
| A Factual accuracy | 4 | Both names and roles are correct
| B Task coverage | 4 | Both required elements are addressed
| C Evidence and uncertainty | 2 | Correct, source-supported answer, but required citation by the shared instructions is missing.
| D Reasoning and calculations | N/A | This case requires factual retrieval only.
| E Decision usefulness | N/A | No recommendation is requested

- Weighted score: 85.7
- Flags: none
- Supporting source locations: S1 - annual_report_2025.md, Leadership section
- Deduction notes: C = 2: Correct, source-supported answer, but required citation by the shared instructions is missing.
- Adjudication status: not requested
- Final adjudicated ratings and score:
- Adjudicator, date, and rationale:

### KESTREL-02 Company background

Prompt (task version kestrel-test-cases-v0.1):

> Identify Kestrel's headquarters, founding year, and the business problem its products address.

Model response (verbatim from gpt-4.1-mini_attempt-01_responses.md):

Kestrel Freight Analytics is headquartered in Omaha, Nebraska. The company was founded in 2017. Its products address the business problem of helping shipping and logistics companies plan freight routes more efficiently through software and data products.

- Task type: Factual
- Response ID: KESTREL-02
- Required elements: Location of Kestrel's HQ, fouding year and the business problem its products address.
- Headquarters: Addressed
- Founding year: Addressed
- Product purpose: Addressed

| Dimension | Rating | Reasons |
| --- | --- |
| A Factual accuracy | 4 | All requested information is provided.
| B Task coverage | 4 | All requested information is provided.
| C Evidence and uncertainty | 2 | Correct, source-supported answer, but required citation by the shared instructions is missing.
| D Reasoning and calculations | N/A |
| E Decision usefulness | N/A |

- Weighted score: 85.7
- Flags: none
- Supporting source locations: S1 - annual_report_2025.md, Summary section
- Deduction notes: [brief reasons, or none after review]
- Adjudication status: not requested
- Final adjudicated ratings and score:
- Adjudicator, date, and rationale:

### KESTREL-03 Annual financial results

Prompt (task version kestrel-test-cases-v0.1):

> State fiscal 2025 revenue, fiscal 2024 revenue, and fiscal 2025 net income. Include units and periods.

Model response (verbatim from gpt-4.1-mini_attempt-01_responses.md):

The fiscal year revenue and net income figures are as follows:

    Fiscal 2025 revenue: $412.6 million
    Fiscal 2024 revenue: $349.7 million
    Fiscal 2025 net income: $38.9 million

All amounts are for the respective full fiscal years.

- Task type: Factual
- Response ID: KESTREL-03
- Required elements: Fiscal 2025 revenue, fiscal 2024 revenue, fiscal 2025 net income with all units and periods included.
- 2025 revenue: Addresssed
- 2024 revenue: Addresssed
- 2025 net income: Addresssed

| Dimension | Rating | Reasons |
| --- | --- |
| A Factual accuracy | 4 | All requested information is provided.
| B Task coverage | 4 | All requested information is provided.
| C Evidence and uncertainty | 2 | Correct, source-supported answer, but required citation by the shared instructions is missing.
| D Reasoning and calculations | N/A |
| E Decision usefulness | N/A |

- Weighted score: [unscored]
- Flags: [not reviewed]
- Supporting source locations: S1 - annual_report_2025.md, Financial results for fiscal year 2025 section
- Deduction notes: Correct, source-supported answer, but required citation by the shared instructions is missing.
- Adjudication status: not requested
- Final adjudicated ratings and score:
- Adjudicator, date, and rationale:

### KESTREL-04 Revenue segment mix

Prompt (task version kestrel-test-cases-v0.1):

> Name both revenue segments and give each segment's share of total revenue in 2025.

Model response (verbatim from gpt-4.1-mini_attempt-01_responses.md):

The two revenue segments for Kestrel Freight Analytics in 2025 are:

    Route Optimization Software segment, which contributed 62% of total revenue.
    Data Services segment, which contributed 38% of total revenue.

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

Model response (verbatim from gpt-4.1-mini_attempt-01_responses.md):

The Q1 2026 financial results for Kestrel Freight Analytics are as follows:

    Revenue: $108.3 million
    Net Income: $9.2 million
    Diluted EPS: $0.31

All amounts are in US dollars.

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

Model response (verbatim from gpt-4.1-mini_attempt-01_responses.md):

The reported financial results for Kestrel Freight Analytics in Q2 2026 are as follows:

    Revenue: $116.0 million
    Net Income: $11.4 million
    Diluted Earnings Per Share (EPS): $0.38
    Gross Margin: 72.1%

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

Model response (verbatim from gpt-4.1-mini_attempt-01_responses.md):

The product launched by Kestrel Freight Analytics in February 2026 is called LaneSight. It predicts freight lane congestion up to 14 days in advance. The maximum prediction horizon of LaneSight is 14 days.

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

Model response (verbatim from gpt-4.1-mini_attempt-01_responses.md):

The acquired business is Bramblecote Telematics.
The acquisition was completed on June 12, 2026.
The purchase price was $64 million, paid in cash.
Bramblecote Telematics' business is providing in-truck sensor data.

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

Model response (verbatim from gpt-4.1-mini_attempt-01_responses.md):

Dividend Policy: Kestrel does not pay a dividend (from the 2025 Annual Report).
Buyback Authorization: In November 2025, the board authorized a share buyback program of up to $25 million (from the 2025 Annual Report).
Repurchase Amount Disclosed: The sources do not disclose how much was actually repurchased under the buyback authorization.

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

Model response (verbatim from gpt-4.1-mini_attempt-01_responses.md):

The revolving facility details for Kestrel Freight Analytics are as follows:

    Facility size: $150 million revolving credit facility.
    Amount drawn: $40 million drawn as of June 30, 2026.
    Measurement date: June 30, 2026.
    Contractual interest-rate formula: SOFR plus 1.75%.

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

Model response (verbatim from gpt-4.1-mini_attempt-01_responses.md):

To calculate the first-half 2026 revenue and net income by summing Q1 and Q2 figures:

Revenue calculation:

    Q1 2026 revenue = $108.3 million
    Q2 2026 revenue = $116.0 million
    First-half 2026 revenue = Q1 revenue + Q2 revenue
    First-half 2026 revenue = $108.3 million + $116.0 million = $224.3 million

Net income calculation:

    Q1 2026 net income = $9.2 million
    Q2 2026 net income = $11.4 million
    First-half 2026 net income = Q1 net income + Q2 net income
    First-half 2026 net income = $9.2 million + $11.4 million = $20.6 million

Summary:

    First-half 2026 revenue = $224.3 million
    First-half 2026 net income = $20.6 million

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

Model response (verbatim from gpt-4.1-mini_attempt-01_responses.md):

To calculate the dollar and percentage increase in revenue from Q1 to Q2 2026:

    Q1 2026 revenue = $108.3 million
    Q2 2026 revenue = $116.0 million

Dollar increase = Q2 revenue − Q1 revenue
= $116.0 million − $108.3 million
= $7.7 million

Percentage increase = (Dollar increase / Base revenue) × 100
Base used = Q1 2026 revenue = $108.3 million

= ($7.7 million / $108.3 million) × 100
≈ 7.11%

Summary:

    Dollar increase in revenue from Q1 to Q2 2026: $7.7 million
    Percentage increase based on Q1 2026 revenue: approximately 7.11%

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

Model response (verbatim from gpt-4.1-mini_attempt-01_responses.md):

The gross margin for Q1 2026 was 71.4%, and for Q2 2026 it was 72.1%.

To calculate the gross margin improvement from Q1 to Q2 2026:

Subtraction in percentage points:
72.1% - 71.4% = 0.7 percentage points

Conversion to basis points:
0.7 percentage points × 100 = 70 basis points

Answer:

    Gross margin improvement = 0.7 percentage points
    Gross margin improvement = 70 basis points

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

Model response (verbatim from gpt-4.1-mini_attempt-01_responses.md):

The comparison period is from the end of fiscal year 2025 to the end of the second quarter (Q2) of 2026.

    At the end of 2025, Kestrel had 2,850 enterprise customers.
    At the end of Q2 2026, Kestrel had 3,120 enterprise customers.

The increase in enterprise customers from the end of 2025 to the end of Q2 2026 is:

3,120 - 2,850 = 270 customers.

To calculate the percentage increase:

(270 / 2,850) * 100% ≈ 9.47%.

Summary:

    Increase in customers: 270
    Percentage increase: approximately 9.47%
    Comparison period: from December 31, 2025, to June 30, 2026 (end of Q2 2026).

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

Model response (verbatim from gpt-4.1-mini_attempt-01_responses.md):

To estimate the 2025 revenue for each segment, we use the total 2025 revenue and the segment revenue shares provided in the Kestrel Freight Analytics Annual Report 2025.

Given data:

    Total revenue for 2025: $412.6 million
    Route Optimization Software segment share: 62%
    Data Services segment share: 38%

Calculation:

    Route Optimization Software revenue 2025:
    = Total revenue * Segment share
    = $412.6 million * 62%
    = $412.6 million * 0.62
    = $255.812 million (derived estimate)

    Data Services revenue 2025:
    = Total revenue * Segment share
    = $412.6 million * 38%
    = $412.6 million * 0.38
    = $156.488 million (derived estimate)

Summary:

    Estimated Route Optimization Software revenue 2025: $255.8 million (derived)
    Estimated Data Services revenue 2025: $156.5 million (derived)

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

Model response (verbatim from gpt-4.1-mini_attempt-01_responses.md):

The reported FY2025 revenue growth rate is 18%, as stated in the Kestrel Freight Analytics Annual Report 2025.

The revenue figures for FY2024 and FY2025 are:

    FY2024 revenue: $349.7 million
    FY2025 revenue: $412.6 million

Calculating the growth rate using these figures:

[
\text{Growth Rate} = \frac{\text{FY2025 Revenue} - \text{FY2024 Revenue}}{\text{FY2024 Revenue}} \times 100 = \frac{412.6 - 349.7}{349.7} \times 100 = \frac{62.9}{349.7} \times 100 \approx 17.99%
]

Rounded, this is approximately 18%.

Therefore, the reported 18% revenue growth rate is consistent with the growth calculated from the FY2024 and FY2025 revenue figures after rounding.

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

Model response (verbatim from gpt-4.1-mini_attempt-01_responses.md):

The Q2 revenue outlook issued in the Q1 2026 earnings release was a revenue range of $112 million to $115 million.

The actual Q2 2026 revenue reported was $116.0 million.

Comparison with the upper bound of the outlook ($115 million):

    Dollar beat = $116.0 million - $115 million = $1.0 million
    Percentage beat = ($1.0 million / $115 million) × 100% ≈ 0.87%

Summary:

    Q2 2026 revenue outlook in Q1 release: $112 million to $115 million
    Actual Q2 2026 revenue: $116.0 million
    Dollar beat versus upper bound: $1.0 million
    Percentage beat versus upper bound: approximately 0.87%

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

Model response (verbatim from gpt-4.1-mini_attempt-01_responses.md):

To calculate the H2 2026 revenue range needed to reach the full-year 2026 revenue guidance:

    Full-year 2026 revenue guidance (from Q2 2026 Earnings Release):
        Lower bound: $470 million
        Upper bound: $480 million

    Reported H1 2026 revenue (sum of Q1 and Q2 2026 revenues):
        Q1 2026 revenue: $108.3 million
        Q2 2026 revenue: $116.0 million
        H1 2026 total revenue = $108.3M + $116.0M = $224.3 million

    H2 2026 revenue needed:
        Lower bound = $470M - $224.3M = $245.7 million
        Upper bound = $480M - $224.3M = $255.7 million

Therefore, Kestrel Freight Analytics needs H2 2026 revenue in the range of approximately $245.7 million to $255.7 million to meet its full-year 2026 revenue guidance.

This calculation is based on the company-issued full-year 2026 revenue guidance and reported H1 2026 revenue; however, no explicit H2 guidance range was provided by the company. The above H2 target is derived, not company-issued H2 guidance.

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

Model response (verbatim from gpt-4.1-mini_attempt-01_responses.md):

The nominal undrawn revolver capacity at June 30, 2026, for Kestrel Freight Analytics is calculated as follows:

    Total revolving credit facility: $150 million
    Amount drawn as of June 30, 2026: $40 million

Nominal undrawn revolver capacity = $150 million - $40 million = $110 million

Regarding establishing Kestrel's cash balance or unrestricted borrowing availability:

    The revolving credit facility limit establishes the maximum available credit to Kestrel, part of which is drawn ($40 million), leaving $110 million undrawn and available to borrow.
    The undrawn revolver capacity ($110 million) represents the unrestricted borrowing availability under this credit facility.
    However, the information provided does not state Kestrel's actual cash balance or any other sources of cash.
    Therefore, while the $110 million undrawn revolver capacity defines how much Kestrel can borrow instantly, it does not directly establish the company's cash balance.
    The cash balance and borrowing availability are distinct, with borrowing availability limited to the revolver minus current borrowings.

In summary:

    The revolver limit of $150 million and drawn amount of $40 million lead to $110 million in undrawn revolver capacity.
    The $110 million undrawn capacity defines Kestrel’s unrestricted borrowing availability under the revolver as of June 30, 2026.
    The actual cash balance is not provided and cannot be established solely from revolver information.

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

Model response (verbatim from gpt-4.1-mini_attempt-01_responses.md):

Here is the requested information based only on the supplied sources:

    Kestrel's share price: The documents do not provide any information about Kestrel's share price. Therefore, it cannot be determined.

    Cloud provider: The "Risk Factors 2026" document states that Kestrel runs its products on "a single third-party cloud provider" but does not name the provider. Therefore, the exact cloud provider cannot be determined from the documents.

    SOFR rate applicable to June 30, 2026 borrowings: According to the "Risk Factors 2026" document, borrowings on Kestrel's revolving credit facility as of June 30, 2026 carry an interest rate of SOFR plus 1.75%. However, the documents do not provide the exact SOFR rate number applicable on June 30, 2026. Thus, the exact SOFR rate cannot be determined.

Summary:

    Share price: Cannot be determined.
    Cloud provider: Cannot be determined by name.
    SOFR rate: Not provided; only the spread over SOFR (1.75%) is known.

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

Model response (verbatim from gpt-4.1-mini_attempt-01_responses.md):

Here are two distinct integration workstreams recommended for Bramblecote's integration into Kestrel Freight Analytics, based on provided documents:

    Product Integration Workstream
        Source-based rationale: The acquisition of Bramblecote Telematics, described as a provider of in-truck sensor data (Q2 2026 Earnings Release), offers a potential complement to Kestrel's core Route Optimization Software and Data Services products. Integrating sensor data into Kestrel’s analytics and route optimization tools could enhance product capabilities such as the recently launched LaneSight, which predicts freight lane congestion.
        Tradeoff: Integrating sensor data into existing software products may require significant engineering resources and pose risks of delaying feature releases due to complexity. This could impact time to market and disrupt existing development priorities.
        Practical next step: Perform a technical assessment and create a roadmap for how Bramblecote’s sensor data APIs and infrastructure can be integrated with Kestrel’s platform and the LaneSight product.

    Customer Base and Sales Synergy Workstream
        Source-based rationale: Kestrel expanded its enterprise customer base from 2,850 at the end of 2025 to 3,120 by Q2 2026, coinciding with the Bramblecote acquisition (Annual Report 2025, Q2 2026 Earnings). Leveraging Bramblecote’s existing customer relationships and integrating sales teams could accelerate cross-selling of Kestrel products to Bramblecote customers and vice versa.
        Tradeoff: Sales and customer account integration may create short-term disruption or customer service challenges as teams merge and adjust processes, risking dissatisfaction if not carefully managed.
        Practical next step: Initiate joint sales training and develop bundled offerings combining Kestrel and Bramblecote solutions, while aligning customer support teams under a unified approach.

Missing fact needed before committing resources: An important missing fact is the detailed compatibility and overlap of Bramblecote’s technology stack, product features, and customer segments with Kestrel’s current offerings and markets. Understanding these technical and market alignments or gaps is essential to prioritize integration effort and resource allocation effectively.

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

Model response (verbatim from gpt-4.1-mini_attempt-01_responses.md):

Initial approach to Kestrel's cloud concentration risk:

Since Kestrel relies on a single third-party cloud provider to run all its products, it faces a concentration risk where an extended outage at that provider could disrupt service to all customers. Addressing this risk early is important to maintain service reliability and customer trust.

Comparison of two mitigation options:

    Multi-cloud architecture: Kestrel could distribute its cloud workloads across multiple cloud providers to reduce dependency on any single provider.
        Pros: Improves resilience and uptime by allowing failover or load balancing between clouds.
        Cons: Increases complexity of engineering and operations, requiring integration efforts and possibly higher costs.

    Investing in robust disaster recovery and backup within the existing cloud provider:
        Pros: Lower complexity than multi-cloud; faster to implement leveraging the current provider’s infrastructure.
        Cons: Does not eliminate risk of a complete provider-wide outage; recovery times may still impact customer service.

Tradeoff between the options:

Multi-cloud reduces the single-provider risk more comprehensively but adds operational complexity and cost, while focusing disaster recovery within one cloud provider is simpler but less effective at eliminating the risk.

Proposed next step:

Conduct a comprehensive risk and cost-benefit analysis comparing multi-cloud architecture vs. enhanced disaster recovery to determine the optimal approach aligned with business priorities and technical capabilities.

One missing fact that could change the choice:

Information on the current cloud provider's historical outage frequency, SLA terms, and costs for multi-cloud setups is missing; a detailed understanding of these factors could significantly influence which mitigation strategy is preferable.

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

Model response (verbatim from gpt-4.1-mini_attempt-01_responses.md):

Estimate of 2025 Revenue Attributable to Largest Customer:

    Total revenue in 2025: $412.6 million
    Largest customer accounted for 9% of total revenue in 2025 (Risk Factors 2026)
    Revenue from largest customer = 9% × $412.6 million = approximately $37.13 million

Recommended Mitigation:

    Diversify the customer base to reduce dependency on the largest customer.

Explanation of One Tradeoff:

    Diversifying the customer base may require increased sales and marketing expenses and could dilute focus on major clients, potentially impacting service quality or growth with key accounts.

One Next Step:

    Conduct a customer segmentation analysis to identify growth opportunities with smaller customers and develop a targeted acquisition strategy to reduce concentration risk.

Limit on Interpreting the Estimate as a Future-Loss Forecast:

    The 9% figure reflects historical revenue concentration and does not predict whether the largest customer will be lost in the future; it only indicates potential revenue impact if such loss occurs. Customer retention dynamics and contracts can change, making this estimate an incomplete forecast of future loss.

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

Model response (verbatim from gpt-4.1-mini_attempt-01_responses.md):

Recommendation on executing additional buybacks immediately vs. reviewing liquidity:

    Authorization:

    The Board authorized a share buyback program of up to $25 million in November 2025.

2. Acquisition payment:

    The company completed a acquisition of Bramblecote Telematics on June 12, 2026, costing $64 million in cash.

3. Revolver balance:

    Kestrel has a $150 million revolving credit facility.
    As of June 30, 2026, $40 million was drawn on the revolver.
    Interest rate on borrowings is SOFR plus 1.75%.

Tradeoff:

    Executing additional buybacks immediately would return capital to shareholders, but could constrain liquidity especially after a large $64 million acquisition and with an existing $40 million revolver draw.
    Conversely, reviewing liquidity first would allow management to ensure sufficient cash and borrowing capacity remain to fund operations, integration of acquisition, and risk mitigation before deploying excess cash to buybacks.

Next step:

    Management should first review current cash balances, cash flow forecasts, and liquidity position—including availability on the revolver—before proceeding with additional buybacks.

Two missing inputs:

    Current cash and cash equivalents balance to assess immediate liquidity.
    Near-term free cash flow or operating cash flow projections to understand how much cash could be available for buybacks without impairing operations or acquisition integration efforts.

Summary:
Given the recent large cash acquisition and $40 million revolver draw, management should prudently review liquidity before executing more share buybacks within the authorized $25 million program. This balances returning capital to shareholders with maintaining financial flexibility.

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

Model response (verbatim from gpt-4.1-mini_attempt-01_responses.md):

Let's calculate the H2 average quarterly revenue needed to reach the midpoint of FY2026 guidance and compare it with Q2 revenue:

    Full-year 2026 revenue guidance range is $470 million to $480 million.
        Midpoint = ($470M + $480M) / 2 = $475 million.

    Revenue already reported for H1 2026:
        Q1 2026 revenue = $108.3 million
        Q2 2026 revenue = $116.0 million
        H1 total = $108.3M + $116.0M = $224.3 million

    Revenue needed in H2 2026 to reach midpoint guidance:
        Required H2 revenue = Midpoint FY2026 guidance - H1 revenue
        = $475M - $224.3M = $250.7 million

    Average quarterly revenue needed in H2 (Q3 and Q4):
        = $250.7M / 2 = $125.35 million per quarter

Comparison with Q2 revenue:

    Q2 revenue was $116.0 million.
    The required average quarterly revenue in H2 ($125.35 million) is about $9.35 million higher than Q2 revenue, implying Kestrel needs to increase quarterly revenue in each of the second-half quarters by about 8% over Q2 2026 to hit the midpoint of guidance.

Implications for execution:

    To meet the midpoint full-year guidance, the company must accelerate growth compared to recent performance in Q2.
    This suggests stronger sales execution or further market expansion will be necessary in H2.
    Without forecasting success, this elevation in required quarterly revenue reflects an execution challenge.

Proposed monitoring action:

    Closely track monthly and quarterly revenue trends in Q3 and Q4 2026 to gauge progress towards the $125.35 million quarterly target.
    Monitor customer additions and product sales uptake, especially integration progress of Bramblecote Telematics acquired in June 2026, to identify drivers or obstacles to revenue growth.

Data request:

    Request detailed revenue breakdown by product line and customer segment for Q3 2026 to assess which areas are contributing most to any revenue increase as compared to Q2.
    Additonally, request integration status and expected contribution forecast from Bramblecote Telematics to understand its impact on H2 revenue.

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

Model response (verbatim from gpt-4.1-mini_attempt-01_responses.md):

To calculate the net margin for Q1 and Q2 2026:

Net margin formula:
Net margin = (Net income / Revenue) × 100%

From the Q1 2026 Earnings Release:

    Revenue Q1 2026 = $108.3 million
    Net income Q1 2026 = $9.2 million

Net margin Q1 2026 = (9.2 / 108.3) × 100% ≈ 8.49%

From the Q2 2026 Earnings Release:

    Revenue Q2 2026 = $116.0 million
    Net income Q2 2026 = $11.4 million

Net margin Q2 2026 = (11.4 / 116.0) × 100% ≈ 9.83%
Assessment of Profitability Direction:

    The net margin increased from approximately 8.49% in Q1 2026 to 9.83% in Q2 2026, indicating an improving profitability trend quarter over quarter.
    Additionally, gross margins slightly increased from 71.4% in Q1 2026 to 72.1% in Q2 2026, supporting the positive profitability trend.

What the figures show:

    Improving profitability in the first half of 2026.
    Effective revenue growth (21% year-over-year in Q1 and 19% in Q2).
    Positive operational performance possibly supported by product launches like LaneSight (Q1) and an expanding customer base (3,120 customers in Q2).

What the figures cannot explain:

    The impact of the June 2026 acquisition of Bramblecote Telematics on future profitability is unclear—not yet reflected fully in Q2 results, and integration risks remain.
    Whether the improving margins are sustainable long-term, as potential risks include customer concentration, cloud dependency, fuel price volatility impacting customers, and integration challenges.
    Specific expense drivers or one-time costs affecting net income are not detailed.
    How operating costs or research & development expenses changed from Q1 to Q2.

Recommended Follow-up Analysis:

Recommendation: Perform a detailed segment and expense analysis to understand the drivers behind margin expansion and the cost impact of the Bramblecote acquisition.

    Tradeoff: This analysis requires more granular financial data that may not be publicly available; it consumes analytic resources and may delay timely insights but provides clarity on sustainable profitability.
    First step: Obtain or request detailed segment reporting and expense breakdowns for Q1 and Q2 2026, including acquisition-related costs and integration expenses.

In summary, Kestrel Freight Analytics' net margin improved from Q1 to Q2 2026, signaling positive profitability momentum. However, without deeper data on cost structure and acquisition impacts, conclusions on sustainability and long-term profitability drivers cannot be drawn confidently. A follow-up detailed financial analysis focusing on segments and expenses is necessary.

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

Model response (verbatim from gpt-4.1-mini_attempt-01_responses.md):

To evaluate LaneSight's commercial promise in connection with Kestrel's business, the approach should focus on how effectively the new product enhances Kestrel's core value proposition in freight route planning and congestion prediction.

Proposed Evaluation Approach:

    Connection to Kestrel's Business: LaneSight predicts freight lane congestion up to 14 days in advance, complementing Kestrel's established route optimization and data services. It could strengthen the Route Optimization Software segment (which contributed 62% of revenue in 2025) by providing predictive insights that improve route planning and logistics efficiency.

    Two Success Measures:
        Revenue Growth Contribution: Track incremental revenue attributable to LaneSight sales or upselling, aiming for an increased share in Kestrel’s total revenue beyond the current 18%-21% growth trends seen in Q1 and Q2 2026.
        Customer Adoption and Retention: Monitor the number of enterprise customers actively using LaneSight and improvements in customer retention or acquisition, contributing to growth from 3,120 customers at the end of Q2 2026.

    One Tradeoff:
        Resource Allocation vs. Integration Risk: Investing heavily in LaneSight development, marketing, and integration (especially with sensor data post-Bramblecote acquisition) may strain resources or distract from existing products. Additionally, integration risks could affect operational focus and financial performance, as noted in acquisition risks.

    First Step:
        Conduct a pilot program with key enterprise customers (including existing large customers) to gather real-world usage data and feedback on LaneSight’s predictive accuracy and operational impact.

    One Missing Input:
        The report does not provide specific customer feedback or sales data on LaneSight usage or its direct impact on revenue and margins, which is critical to assess its commercial viability and value contribution.

This evaluation method aligns LaneSight’s commercial promise with Kestrel’s business strategy, balancing growth potential against operational risks and focusing on measurable outcomes.

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

Model response (verbatim from gpt-4.1-mini_attempt-01_responses.md):

Plausible Pathway from Fuel Price Volatility to Kestrel's Revenue Risk:

Fuel price volatility affects many of Kestrel's customers, who are primarily trucking and logistics companies. Since these customers’ budgets are highly sensitive to fuel price fluctuations (as noted in the "Industry conditions" risk factor), spikes in fuel costs can lead to reduced freight activity or delayed technology investments. This could lessen demand for Kestrel's route optimization software and data services, thereby reducing its revenue. For example, if fuel prices sharply increase, trucking companies may cut back on expenses, including purchasing optimization software or data subscriptions from Kestrel.

Recommended Response:

Kestrel should focus on developing and marketing products that help logistics customers manage and mitigate fuel cost risks, such as LaneSight’s congestion predictions or leveraging the data capabilities from Bramblecote Telematics sensors to optimize fuel efficiency. Demonstrating clear ROI on fuel savings may make Kestrel’s offerings more essential despite fuel price volatility, stabilizing revenue.

Tradeoff:

Investing heavily in new product development or acquisitions to address fuel volatility risks (e.g., the Bramblecote purchase for $64 million) requires capital and management focus, potentially diverting resources from other growth opportunities. This could also increase integration risks, as noted.

Next Step:

Conduct customer-focused market research to quantify how fuel price changes impact purchasing behavior and identify which product features most alleviate these concerns. This will guide product roadmap prioritization and sales strategies.

Missing Fact Limiting Confidence:

The company's disclosures do not specify what portion of revenue is variable or contracted, nor detail how sensitive customer spending specifically is to fuel price changes. Without granular data on customer spending patterns relative to fuel price shifts, it is difficult to precisely estimate Kestrel’s revenue risk exposure to fuel price volatility.

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

Model response (verbatim from gpt-4.1-mini_attempt-01_responses.md):

Two distinct responses to key personnel risk at Kestrel Freight Analytics are:

    Implement Key-Person Life Insurance
        Rationale: Purchasing key-person life insurance provides financial protection to the company in case of the sudden loss of CEO Dana Whitfield or other senior leaders. The proceeds from such insurance can help cover unexpected costs, recruit and retain replacement executives, or stabilize the company during leadership transitions. This response directly mitigates financial risk stemming from personnel loss without altering operational structure.
        First step: Conduct a valuation of the coverage amount needed based on the financial impact of losing key personnel.

    Develop Succession Planning and Leadership Development Programs
        Rationale: Establishing a robust succession plan and training internal candidates for senior roles reduces dependency on any single individual by ensuring a pipeline of qualified leaders. This strengthens organizational resilience and continuity beyond an individual's tenure or unexpected departure. It is a proactive, operational strategy to mitigate key personnel risk.
        First step: Identify critical leadership positions and potential internal successors to begin mentoring and development.

Tradeoff comparison:

    Key-person insurance provides immediate financial protection but does not address operational continuity or leadership gaps. It also involves ongoing premium costs.
    Succession planning improves internal capabilities and long-term stability but requires time and investment to develop talent, and may not fully mitigate sudden financial losses due to unexpected leadership exits.

Missing fact needed to choose the right mix:

    The document does not specify the company's tolerance for leadership transition risk, or the estimated financial impact of losing key personnel beyond headline risk statements. Specifically, information on the potential financial loss magnitude or business disruption timeframe after losing Dana Whitfield or other leaders is required to optimally balance insurance coverage level versus investment in leadership development.

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

Model response (verbatim from gpt-4.1-mini_attempt-01_responses.md):

Management Assessment for Kestrel Freight Analytics

Disclosed Facts:

    Fiscal 2025 revenue was $412.6 million, up 18% from 2024.
    Q1 2026 revenue was $108.3 million, up 21% year over year.
    Q2 2026 revenue was $116.0 million, up 19% year over year.
    Net income for fiscal 2025 was $38.9 million; Q1 2026 net income was $9.2 million; Q2 2026 net income was $11.4 million.
    Gross margin improved from 69.8% in Q1 2025 to 71.4% in Q1 2026 and 72.1% in Q2 2026.
    LaneSight product launched in February 2026.
    Acquisition of Bramblecote Telematics for $64 million cash completed in June 2026.
    Enterprise customers increased from 2,850 at end 2025 to 3,120 at Q2 2026.
    Board authorized a $25 million share buyback program in Nov 2025.
    Kestrel has a $150 million revolving credit facility with $40 million drawn as of June 30, 2026 (interest: SOFR + 1.75%).

Derived Values:

    Revenue growth signals sustained momentum: FY 2025 to FY 2026 annualized growth expected to exceed 18%, with Q1 and Q2 2026 showing 19-21%+ YoY increases.
    Gross margin expansion (~1.6 to 2.3 percentage points since 2025/2026 comparison) indicates improving profitability.
    Customer base growing (~9.5% increase from end 2025 to mid-2026).
    The acquisition represents a sizable investment (~15.5% of annual 2025 revenue) and will require integration efforts.
    Credit facility utilization stands at ~27% of capacity, indicating moderate leverage and some financial flexibility.

Judgments:

    Growth Signal: Strong double-digit revenue growth in FY 2025 and continuing through Q1 and Q2 2026, reinforced by new product launch (LaneSight) and acquisition to expand data capabilities. Customer growth also supports positive momentum.
    Profitability Signal: Gross margin expansion and steady net income growth suggest improved operational efficiency and pricing power.
    Financial Constraint/Uncertainty: Moderate leverage due to acquisition financing increases financial obligations. Additionally, integration risk of Bramblecote Telematics and exposure to reliance on a single cloud provider present operational risks. Customer concentration with a single customer representing 9% of revenue is an uncertainty.

Recommended Priorities:

    Priority: Successful Integration of Bramblecote Telematics
        Rationale: The acquisition is key to strengthening data services and competitive positioning, supporting growth and product innovation.
        Tradeoff: Requires significant management focus and resource allocation, which could strain operations and distract from core business. Integration risk could disrupt existing operations or delay benefits realization.
        Next Step: Establish a dedicated cross-functional integration team with clear milestones, risk monitoring, and contingency plans. Prioritize smooth IT, sales, and support system alignment.

    Priority: Mitigating Financial and Customer Concentration Risks
        Rationale: Ensuring financial flexibility and reducing dependency on a single major customer are critical to sustainable profitability and operational stability.
        Tradeoff: Initiatives may require increased sales and marketing investments or renegotiations with customers, potentially impacting short-term margins.
        Next Step: Develop a customer diversification plan targeting growth among smaller clients and new verticals. Review capital structure with finance team to assess potential for debt optimization or additional liquidity sources.

This management assessment balances disclosed financial performance, derived metrics, and prudent judgments to guide Kestrel Freight Analytics toward sustainable growth, profitability, and risk management.

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
