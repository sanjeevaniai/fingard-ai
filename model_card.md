# Model Card — Fin Guard AI

## Model Overview
Model Name: Fin Guard AI — Credit Scoring Platform
Version: 1.1.0
Last Updated: August 2024
Owner: Risk Management Team
Organization: Fin Guard AI Corp

## Intended Use
Credit scoring and loan approval recommendations
for consumer lending customers across the
United States.

Primary use cases:
- Credit worthiness assessment
- Loan approval recommendations
- Risk tier classification
- Adverse action determination

Out of scope:
- Insurance underwriting
- Employment decisions
- Housing decisions

## Training Data
Source: Historical lending data 2015-2023
Size: 2.3 million loan applications
Consent: Standard terms of service
Note: Training data predates 2024 economic
conditions. Performance on post-2024
applications has not been formally validated.

## Bias Evaluation
Last evaluated: September 2023
Status: OVERDUE — evaluation is now
18 months old. Quarterly evaluation required.
Method: Disparate impact analysis
Result: Passed at time of evaluation
Next evaluation: Overdue since December 2023

## Human Oversight
Loan officers review recommendations
above $50,000.
Automated approval for amounts below $25,000
without human review.
Named oversight owner: Not formally assigned.

## Performance
Accuracy: 88.1 percent on 2023 test set
Performance on 2024-2025 data: Not validated
Hallucination rate: Not measured
Last evaluated: September 2023

## Regulatory Alignment
ECOA: Compliant
FCRA: Compliant
SR 11-7: Partial — independent validation pending
EU AI Act: Not assessed
ISO 42001: Not certified

## Known Limitations
Model trained on pre-2024 data.
Economic conditions have changed significantly.
Human review threshold of $25,000 may be
too high for automated decisions affecting
financially vulnerable individuals.

## Contact
risk@fingardai.com
