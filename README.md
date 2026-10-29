# Potential Customers Prediction (ExtraaLearn)

A classification model that predicts which leads of an online education startup are likely to become paying customers, so the sales team can focus on them.

**Tools:** Python · pandas · scikit-learn (Decision Tree, Random Forest, GridSearchCV) · Matplotlib · Seaborn


## Key achievements

- **Analyzed 4,612 leads** (30% of them converted) across demographics, website behavior, marketing channels and recent activity.
- **Fixed overfitting in the decision tree.** The first tree scored 100% on training data but only 81% on test data. Cost-complexity pruning raised test accuracy to **87%** and precision for converting leads from 0.68 to **0.84**.
- **Tuned a random forest** with GridSearchCV (optimized for F1). It reached **87% test accuracy** and the best recall for converting leads (**0.74**), and overfit less than the untuned forest.
- **Found what drives conversion:**
  - **Time spent on the website** is the strongest predictor.
  - Leads who first came through the **website converted about 5x more** than those from the mobile app (~50% vs ~10%).
  - **Referrals convert at ~70%**, the highest of any channel. Print and digital ads showed no measurable lift.
  - Leads with more **complete profiles** and **professionals** convert at higher rates.

## Recommendations

- Score leads by how they engage with the website, and send high-engagement leads to sales first.
- Invest in a referral program and drive traffic to the website. Improve the mobile app experience.
- Strengthen phone outreach, especially to students and unemployed leads.
