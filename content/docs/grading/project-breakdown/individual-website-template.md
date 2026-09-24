---
title: Individual Website Template
weight: 6
bookHidden: false
---
# Individual Project Website Template

This is a **rendered Markdown example** of the website's required shape. For the individual project, **follow the headings and subsection order exactly** on one website. Replace every instruction and blank with your own work; do not omit a required subsection, even if its answer is that a result was unavailable and why. Your methods and findings will differ from another student's. **Do not copy sample results or assume a sample dataset is assigned.** The dataset, label mappings, and submission details in your [ML Class Hub assignment](https://ml-class.cc.gatech.edu/) take precedence. If an assignment detail is missing, ask the teaching team before choosing a substitute. Update the same page at midterm and final. See the [individual-project requirements](../individual/) for the stage rules and dates.

## 1. Introduction and question

### 1.1 Question and motivation

State in two or three sentences what you are trying to learn or predict from the assigned data and why the question matters. Name the actual dataset from your Hub assignment. Do not claim that a method is novel merely because you used it.

### 1.2 What this website contains

Briefly state what is already completed and what remains planned. At midterm, it is acceptable for final experiments to be marked **planned**; by the final deadline, replace plans with results or an honest explanation of what could not be completed.

## 2. Data and task definitions

### 2.1 Dataset and responsible use

Name the assigned data source, access rules, number of records, important features, missing values, and any restrictions or limitations. Explain cleaning or transformations you actually performed. Do not publish private or licensed records.

### 2.2 Label mappings for the final prediction tasks

Copy the **binary, five-class, and full-class task definitions** from your Hub assignment. Show exactly which original labels map to each target class. Use the same mapping throughout the project; do not quietly change it between models. If the assigned dataset or task description differs, follow the Hub assignment and explain the difference here. These labels are for final supervised prediction, not for fitting the midterm clustering method.

| Task from Hub | Original labels → target labels | Number of examples per target class |
|---|---|---|
| Binary | Fill in the assigned mapping | Fill in counts |
| Five-class | Fill in the assigned mapping | Fill in counts |
| Full-class | Fill in the assigned mapping | Fill in counts |

### 2.3 Train, validation, and test data

Explain how you divided the data, including the proportions or counts and any grouping needed to prevent leakage. State what was fitted on training data only. Use the same splits for fair final comparisons; do not choose a model after looking at test results.

## 3. Midterm: unsupervised analysis

### 3.1 Preparation and full-feature baseline

Describe the features and preprocessing used before clustering. Run clustering on the original, full-feature representation first. Explain the number of clusters and the choice of clustering settings.

### 3.2 Feature selection or dimensionality reduction

Apply **at least one** unsupervised method that either selects original features or creates a lower-dimensional representation. Name the method, how it was fitted without using labels, the number of retained features or dimensions, and why you chose it. If you use PCA, say that it creates new components rather than selecting original features.

### 3.3 Clustering comparison

Run a clustering algorithm on **both** the full-feature data and the selected/reduced representation. Keep the comparison fair: explain what changed and what stayed the same. Provide a small table such as this one with your real values:

| Representation | Clustering method and settings | Internal measure(s) | What the result suggests |
|---|---|---|---|
| Full features | Fill in | Fill in | Fill in |
| Selected/reduced features | Fill in | Fill in | Fill in |

### 3.4 Evaluation and interpretation

Choose suitable **internal** clustering measures taught in class, such as silhouette, Davies–Bouldin, or Calinski–Harabasz; explain what the chosen measures mean and why they fit the data. No one specific measure is mandatory. Inspect representative clusters, plots, and failures. If reliable labels happen to be available, an external measure may be added **after** clustering as optional interpretation; never use those labels to fit or tune the unsupervised method. If there are no labels, do not invent them.

### 3.5 Midterm conclusion and next steps

Say what worked, what did not, one limitation, and the next experiment. Keep preliminary findings visible when you later extend the page. The separate 10-minute unlisted video link goes in ML Class Hub, as stated in the [requirements](../individual/).

## 4. Final: supervised prediction

### 4.1 Methods required for your course level

- **CS 4641 · Undergraduate:** use **two** feature-selection/reduction methods and **two** prediction models.
- **CS 7641 · Graduate:** use **three** feature-selection/reduction methods and **three** prediction models.

List each method/model you actually ran, not just one you considered. Explain the key settings and why each comparison is useful. Keep the full-feature version as a baseline. A method from the midterm can count if you use and explain it in the final supervised comparisons.

### 4.2 Experiment plan and fair comparisons

For **each** assigned prediction task (binary, five-class, full-class), train **each** required prediction model on the full-feature baseline **and on every required selected/reduced representation**. Keep the label mapping and data split fixed within each task. Fit preprocessing and feature selection on training data only. Tune using validation data; report final test results without tuning on the test set.

### 4.3 Results

Show a table or figures that make all required combinations easy to find. Use suitable metrics for the task and include class-wise errors when they help explain performance. A compact table can use these columns (add rows for every task/model/representation combination):

| Task | Feature representation | Prediction model | Validation result | Test result | Important error or tradeoff |
|---|---|---|---|---|---|
| Binary | Full features | Fill in | Fill in | Fill in | Fill in |
| Binary | Method 1 | Fill in | Fill in | Fill in | Fill in |

### 4.4 Interpretation, failures, and limits

Explain which changes helped, which hurt, and **why the evidence supports that conclusion**. Discuss meaningful class-wise errors, runtime or computational cost, feature relevance when interpretable, and at least one failure case. Do not treat a small accuracy difference as proof of a generally better method. State limitations and what a next experiment would test.

## 5. Conclusion

Answer the original question using your actual results. Separate what you observed from what you infer. State the main limitation and next useful step.

## 6. References

List sources you actually used, with links or complete citations. Cite them near the claims or methods they support. Do not invent references.

## 7. AI-use disclosure

Disclose the tool, purpose, and scope of any generative-AI assistance under the [course policy](../../../guidelines/general/). Explain what you independently checked. If none was used, say so.

### Copyable Markdown heading outline

```markdown
# Individual Project
## 1. Introduction and question
### 1.1 Question and motivation
### 1.2 What this website contains
## 2. Data and task definitions
### 2.1 Dataset and responsible use
### 2.2 Label mappings for the final prediction tasks
### 2.3 Train, validation, and test data
## 3. Midterm: unsupervised analysis
### 3.1 Preparation and full-feature baseline
### 3.2 Feature selection or dimensionality reduction
### 3.3 Clustering comparison
### 3.4 Evaluation and interpretation
### 3.5 Midterm conclusion and next steps
## 4. Final: supervised prediction
### 4.1 Methods required for your course level
### 4.2 Experiment plan and fair comparisons
### 4.3 Results
### 4.4 Interpretation, failures, and limits
## 5. Conclusion
## 6. References
## 7. AI-use disclosure
```