# A/B Testing for Pricing Page Experiment

This project simulates a **business analyst A/B testing case** for a pricing-page experiment.

## Scenario
The growth team tested a new pricing-page layout designed to improve conversion. Leadership wants a statistically grounded recommendation on whether to roll it out.

## Questions answered
- Is there a statistically significant lift in conversion?
- What is the effect size, not just the p-value?
- Does treatment change average revenue per visitor?
- Are there heterogeneous effects by country, device, or customer segment?
- Are any data quality issues distorting the result?

## Files
- `data/pricing_experiment.csv`
- `notebooks/ab_test_analysis.ipynb`
- `data_dictionary.md`
- `requirements.txt`

## Real-world messiness included
- duplicated observations
- variant naming inconsistencies
- missing segment and country values
- negative revenue rows
- mixed timestamp formats
- inconsistent category casing
