# Data Mining Project: Hotel Demand Prediction
Group Members: Jagger, Yousef, Connor

## Key Requirements & Constraints

* **Team Size:** 3 students per team.
* **Dataset Rules:** Real data (Kaggle, UCI, Open Data) with 3,000 to 4,000+ records and 10+ variables supporting a clear business decision.
* **Deliverables:**
  1. Fully reproducible Jupyter notebook where Restart & Run All executes without errors.
  2. A 6 to 8 minute final presentation deck (PDF/Beamer or PPT).

---

## Important Deadlines

| Deadline | Milestone | What to Do |
| :--- | :--- | :--- |
| Before Block 2 (13.10) | Team Formation | Form and register your team of 3. |
| Before Block 3 (20.10) | Topic Approval | Submit a short written description covering the business decision, dataset source, target variable, and 2 planned model families. |
| Before Block 7 (17.11) | Final Submission | Upload the completed notebook and presentation slides. |
| Block 7 (17.11) | Presentation | Present the project live (6 to 8 minutes plus Q&A). |

---

## What Your Notebook Must Cover (CRISP-DM Cycle)

1. **Business Problem:** State the business decision supported by the model, the primary target variable, and a brief research question or hypothesis.
2. **Data & EDA:** Report basic descriptive statistics, class balance on the target, and a missingness analysis with evidence for missingness mechanisms.
3. **Data Preparation:** Handle imputation with indicator flags, categorical encoding, scaling, a stratified train/test split, and an explicit data leakage audit.
4. **Model 1 (Baseline):** Logistic Regression (or Linear Regression for numeric targets) built within a clean pipeline.
5. **Model 2 (Flexible Model):** Random Forest, Gradient Boosting (GBDT), Decision Tree, SVM, or Neural Network.
6. **Evaluation & Comparison:** Compare models on unseen test data using cross-validation (mean and standard deviation), ROC/PR curves, calibration, and a cost-based threshold.
7. **Interpretation & Business Recommendation:** Translate model outputs into actionable advice for the business decision.

---

## Recommended Weekly Roadmap

* **Week 1:** Register the team. Inspect candidate datasets using `head()`, `info()`, class balance checks, and missingness maps.
* **Week 2:** Submit the topic description. Complete thorough exploratory data analysis including distributions, bivariate target plots, and data-quality risks.
* **Week 3:** Build data preparation pipelines for imputation and encoding, train the baseline model on a stratified split, and write the leakage audit.
* **Week 4:** Train the second model family. Set up the evaluation kit covering cross-validation, ROC/PR curves, calibration, and cost thresholds.
* **Week 5:** Optional feature engineering (segmentation, rules, text features). Draft business recommendations and presentation slides.
* **Week 6:** Freeze the notebook by running Kernel Restart & Run All, finalize slides, rehearse timing to 6 to 8 minutes, and upload deliverables.

---

## Warnings & Policies

* **AI Policy:** You may use AI tools, but you are responsible for every line of code submitted. Expect to explain and modify code live during Q&A. Submissions undergo checks for unchecked AI generation patterns.
* **Evidence Log Habit:** Every claim in your data understanding notes or reports must be directly backed by a specific plot or metric.

*Note: Follow the project outline template to structure your final report and presentation slides step by step.*

# Install the libraries into the kernel this notebook is using place this at the beginning and then you can delete.
%pip install numpy pandas matplotlib scikit-learn seaborn
