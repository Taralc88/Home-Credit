# Home Credit Default Risk Project
Kaggle Competition: [Home Credit Default Risk](https://www.kaggle.com/competitions/home-credit-default-risk)

## Project Summary
Home Credit faced high financial losses due to client defaults. The business challenge was to predict which clients were most likely to default so that the company could better manage risk, offer tailored loan products, and improve portfolio performance.

The objective of this project was to build a machine learning model that could accurately identify high-risk clients and quantify the financial savings from using predictive insights in loan decisions.

## Solution
Our team developed an XGBoost classification model that achieved an AUC-ROC score of 0.76, outperforming baseline models. We used the model’s probability outputs to flag the top 20% riskiest applicants, identifying over 51% of expected defaulters. This strategy reduced the portfolio default rate from 8.07% to 4.90%.

We also translated these model results into clear financial impact estimates, showing that Home Credit could avoid approximately $1.36 billion in annual losses by rejecting or adjusting loans for the riskiest applicants.

## My Contribution
Built and evaluated linear regression models during the early stages for exploratory baseline analysis.
Led the financial impact analysis, calculating actual potential savings based on real client credit exposures and default behavior.
Delivered segment-specific insights to guide risk management and lending strategy, enhancing profitability while minimizing operational disruption.

### Business Value
* $1.36 billion in annual savings identified through targeting riskiest 20% of applicants.
* Default rate reduction from 8.07% to 4.90%, strengthening overall portfolio quality.
* Clear, actionable insights to help Home Credit make smarter lending decisions with minimal disruption to their loan volumes.

### Challenges Encountered
* **Model selection and tuning:** We evaluated logistic regression, linear regression, random forest, and XGBoost, balancing predictive power, overfitting risk, and interpretability.
* **Handling imbalanced data:** Managing class imbalance required careful up-sampling and down-sampling to ensure models learned meaningful patterns without distorting validation results.
* **Connecting model results to business impact:** We translated probability scores into financial savings by ranking clients, setting risk thresholds, and calculating exposure at risk, ensuring results were clear and actionable for business stakeholders.

### What I Learned
* How to bridge the gap between machine learning outputs and real-world business impact.
* The importance of clear financial storytelling when presenting technical models to non-technical audiences.
* How to validate model-driven assumptions (rejection thresholds, avoidable losses) with data-backed financial calculations while maintaining business objectives.
