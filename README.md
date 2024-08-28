# A/B Testing Experiment: Urban Wear Email Sign-Up Improvement

## Project Overview

This project focuses on an A/B testing experiment conducted for Urban Wear, a clothing brand preparing to launch its eCommerce store. The goal of the experiment was to maximize the number of email sign-ups on the brand's pre-launch page by testing whether changing the submit button color from blue to green would result in a higher sign-up rate.

## Business Objective

Urban Wear's business objective was to increase the number of email sign-ups from potential customers before the official launch of the eCommerce store. The A/B test was designed to determine whether a simple UI change—switching the color of the submit button—could lead to a measurable improvement in sign-up rates.

## Experiment Design

### Hypotheses

- **Null Hypothesis (H₀):** The sign-up rates for the blue and green buttons are the same.
- **Alternative Hypothesis (H₁):** The sign-up rates for the blue and green buttons are different.

### Experiment Parameters

- **Alpha (Significance Level):** 0.05
- **Power:** 0.80
- **Minimum Detectable Effect (MDE):** 10% improvement in the sign-up rate

### Procedure

1. **Exploratory Data Analysis (EDA):** Analyzed pretest data to understand baseline performance, including visitor counts and sign-up rates over time.
2. **Sample Size Calculation:** Determined the required sample size for each group (control and treatment) based on the experiment parameters.
3. **Experiment Duration Analysis:** Estimated the number of days needed to collect sufficient data, considering different traffic allocation scenarios.
4. **Running the Experiment:** Conducted the A/B test over a two-week period, tracking sign-up rates for the control (blue button) and treatment (green button) groups.
5. **Assessing Validity Threats:** Performed an AA test and a chi-square test for Sample Ratio Mismatch (SRM) to ensure the reliability of the results.
6. **Statistical Inference:** Applied Chi-Squared and T-Tests to evaluate the experiment results, followed by confidence interval analysis.

## Results

- **Control Group (Blue Button):** 14,942 users with a sign-up rate of 9.6%
- **Treatment Group (Green Button):** 15,139 users with a sign-up rate of 10.8%
- **Lift in Sign-Up Rate:** 12.8%
- **Statistical Significance:** The observed difference was statistically significant with a p-value of 0.000 and a 95% confidence interval for the relative lift ranging from 5.7% to 19.9%.

## Recommendation

Given the practical and statistical significance observed, the recommendation is to implement the green submit button on the Urban Wear pre-launch page to maximize email sign-ups.
