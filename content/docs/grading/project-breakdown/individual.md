---
title: Individual Project
weight: 5
bookHidden: false
---
# Individual Project

This is your own project, separate from the team project. Use one individual GitHub Pages website throughout the semester and register its link in [ML Class Hub](https://ml-class.cc.gatech.edu/). Improve that same site at midterm and final. The Hub assignment will identify the required dataset, label mappings, and submission details once staff configure it. **CIFAR-10 is an example, not a required dataset.** Dates appear on the [course schedule](../../../course-info/course-schedule-mahdi/).

## Website structure

Use clear sections that develop throughout the semester: **Introduction and question; Data and preparation; Methods; Evaluation and results; Discussion and limitations; Conclusion and next steps; References; Code and reproducibility; AI-use disclosure.** Explain your own choices and cite sources you actually read. Keep earlier work visible as you add experiments; correct mistakes rather than silently hiding them.

## Midterm: unsupervised analysis

Explore and preprocess the assigned data. Apply at least one unsupervised feature-selection or dimensionality-reduction method and compare it with the full-feature representation. Feature selection retains original features; methods such as PCA create new ones. Run a clustering algorithm on both representations and evaluate it with justified **internal measures**, such as silhouette score, Davies–Bouldin index, Calinski–Harabasz score, or another measure taught in class that fits the data. Explain what each chosen measure captures and its limitations; no single metric is required of everyone. Show representative clusters, failures, and what you will improve.

**Ground-truth labels are not required for this unsupervised checkpoint.** If the assigned data include reliable labels, you may report an external measure such as adjusted Rand index as optional post-fit analysis. Do not use labels to fit or tune the unsupervised method, and do not invent labels solely to obtain an external score. If labels are unavailable, explain that and use internal measures and qualitative inspection.

On your website, fill in the relevant sections above with preliminary evidence and a concrete next-step plan. Submit **one 10-minute unlisted YouTube video link** in the individual project workspace in ML Class Hub. Show your implementation, one result, one limitation, and the next experiment. Test the link while signed out and keep it available for staff review. This checkpoint does not require a TA interview; the team project does not require this video.

## Final: supervised comparisons and explanation

Extend the same website with completed experiments and conclusions. Undergraduate students complete **two** feature-selection/reduction methods and **two** prediction models; graduate students complete **three** methods and **three** prediction models. Compare each model on the full-feature baseline and every reduced representation using the binary, five-class, and full-class tasks specified for the assigned dataset. Keep one documented label mapping per task. For CIFAR-10, the full-class task has ten classes; another assigned dataset can have a different count.

Use consistent train, validation, and test splits. Fit preprocessing and feature selection on training data only; keep the test set out of model selection. Explain metrics, class-wise errors, runtime, feature relevance, failures, and limitations. Include code, environment, and steps to reproduce the key results. Accuracy alone is not the goal.

Meet your TA during the final interview window with a working core algorithm, baseline, and preliminary results. Be ready to demonstrate the work and explain your choices. Complete the website by the last instructional day. No second routine video is required. There is no separate pre-interview upload or website freeze. Show your current website and code during the meeting; the TA asks questions about the work you can explain then. Later edits count toward the existing final website deadline, not toward answers given in the interview.

## Prepared final-interview questions

Common questions may cover the assigned data and task labels; train/validation/test separation and leakage prevention; how a reduction or selection method works; why the chosen clustering and prediction measures fit the task; what a comparison or failure case shows; and which work the student implemented. These are examples, not a complete question list. The TA may ask other relevant questions about any part of the project or request a small demonstration using the current website and code. The interview tests understanding, not whether the TA reviewed a website version in advance.

## What the TA looks for

The TA looks for sound methodology, reproducible evidence, justified comparisons, honest interpretation, and your ability to explain your own work. The Hub project page shows checkpoint-specific instructions and feedback. See [Individual and Team Projects](../) for shared rules.