# econ3916-lab08-hypothesis-testing
# Hypothesis Testing — Is Job Training Worth It?

## Objective
I used the LaLonde job training experiment to test whether the training group had different 1978 earnings from the control group.

## Methodology
- Loaded data for 445 people: 185 trainees and 260 controls.
- Compared the earnings distributions for the treatment and control groups.
- Ran a one-sample t-test and a two-sample Welch's t-test.
- Calculated Cohen's d to measure the size of the treatment effect.
- Used power analysis to see whether the study had enough observations.
- Tested five demographic subgroups and corrected the p-values with Bonferroni and Benjamini-Hochberg.
- Wrote Welch's t-statistic from the formula and checked it against scipy.
- Simulated p-values to see what happens when the null is true and when a real effect exists.

## Key Findings
- Trainees earned $1,794.34 more on average in 1978 than the control group.
- The Welch's t-test gave t = 2.6741 and p = 0.0079.
- Cohen's d was 0.2727, which is a small effect.
- The study's achieved power was about 80.8%.
- Two of the five subgroup tests were significant before correction.
- One subgroup remained significant after Bonferroni correction.
- The results suggest the training had a positive earnings effect, but statistical significance by itself does not tell us whether the program is worth its cost.
