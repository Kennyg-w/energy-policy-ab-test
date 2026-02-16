# 📊 Cheatsheet: A/B Testing & Statistical Significance

## 1. The Core Variables
| Variable | Professional Name | What it represents |
| :--- | :--- | :--- |
| **`Control`** | Baseline Group | Users who stayed on the old policy (Standard). |
| **`Treatment`** | Test Group | Users who tried the new "Peak Reward" policy. |
| **`P-Value`** | **Significance Level** | The probability that the results happened by random chance. |
| **`Alpha (α)`** | Threshold | The "Line in the Sand" (usually 0.05). If P < Alpha, it's a win. |
| **`Effect Size`** | Lift / Drop | The actual % change (In this case, a 4.33% reduction). |

## 2. The Logic & The "Why"
*   **The Null Hypothesis ($H_0$):** We assume the policy DOES NOT work until we prove otherwise.
*   **The T-Test:** A mathematical tool that compares the means of two groups while accounting for the "noise" (standard deviation) in the data.
*   **The Result:** Our P-Value (0.0021) is much lower than 0.05. Therefore, we **Reject the Null Hypothesis**.

## 3. Interview Script
> "I designed and simulated an A/B test to evaluate a new energy-saving policy. Using an Independent T-Test, I achieved a **P-Value of 0.0021**, proving with 99% confidence that the 4.33% reduction in peak-hour usage was statistically significant and not due to random variance. This allowed for a data-driven recommendation to scale the policy."