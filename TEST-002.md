# Test 002 — Regional Kurdish Language Comprehension

## Original Input
Em duhu pır westini ma jı xısımara nan çekır kuruq nıvan mali tıjıwu. So jı herini markete

## Original Model Interpretation
"We were very tired yesterday. We cooked food for our relatives, and the house was crowded. Tomorrow we will also go to the market."

## Human Evaluation
Overall result: PARTIALLY CORRECT.

## Confirmed Findings

### 1. Correct — Yesterday's Tiredness
Model: "We were very tired yesterday."
Human evaluator: Correct.

### 2. Incorrect — Kinship Terminology
Model: "We cooked food for our relatives."
Human evaluator: "We cooked food for our in-laws" (specifically, the families connected through marriage).

Error category: Regional kinship terminology misinterpretation.

### 3. Partially Correct — Household Context
Model: "The house was crowded."
Human evaluator: The model captured the crowded-house meaning but omitted information about children.

Error category: Semantic information omission.

### 4. Correct — Future Action
Model: "Tomorrow we will also go to the market."
Human evaluator: Correct.

## Model Confidence
The model initially reported 55% subjective confidence. This is not a calibrated probability.

## Evaluation Summary
- 2 meaning segments interpreted correctly.
- 1 meaning segment interpreted incorrectly.
- 1 meaning segment interpreted partially correctly.

## Methodology and Limitations
- Single written example and one model response.
- Human feedback was provided after the initial model interpretation.
- No independent linguistic verification or repeated trials.
- Exact word-level mapping of regional expressions requires further verification.
- This example alone does not establish a confirmed Turkish-Kurdish code-switching event.

## Final Result
PARTIAL PASS — Regional kinship terminology was misinterpreted, and information about children was omitted.
