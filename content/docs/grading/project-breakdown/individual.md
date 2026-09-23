---
title: Individual Project
weight: 5
bookHidden: false
---
# Individual Project

This is your own project, separate from the team project. Use one individual GitHub Pages website throughout the semester and register its link in [ML Class Hub](https://ml-class.cc.gatech.edu/). Update the same website at midterm and final; do not create a new link for each checkpoint. The course-specific Hub assignment will identify the required dataset, label mappings, and submission details once staff configure it. **CIFAR-10 is an example, not a required dataset.** The [course schedule](../../../course-info/course-schedule-mahdi/) supplies dates.

## Midterm: unsupervised analysis

Explore and preprocess the assigned data. Apply at least one unsupervised feature-selection or dimensionality-reduction method, and compare its representation with a full-feature baseline. Feature selection keeps some original features; methods such as PCA create new features. Run a clustering algorithm on both representations, evaluate cluster quality with an internal measure such as silhouette score, and inspect representative successes, failures, and limitations. If labels are available, an external measure such as adjusted Rand index may be used **only for evaluation after fitting**; labels must not guide the unsupervised fit. Supervised classifiers are not required at midterm.

Document your choices, implementation, and preliminary results on your website. Submit **one 10-minute unlisted YouTube video link** in your individual project workspace in ML Class Hub. Show the algorithm in your own work, one result, a failure or limitation, and the next experiment. Test the link while signed out and keep it available for staff review. This checkpoint does not require a TA interview, and the video requirement does not apply to the team project.

## Final: supervised comparisons and explanation

Reuse and extend the midterm work. Undergraduate students complete **two** feature-selection/reduction methods and **two** prediction models; graduate students complete **three** methods and **three** prediction models. Compare each model on the full-feature baseline and every reduced representation using the binary, five-class, and full-class tasks specified for the dataset. Keep one documented label mapping for each task across experiments. For CIFAR-10, the full-class task has ten classes; a different assigned dataset can have a different full-class count.

Use consistent train, validation, and test splits. Fit preprocessing and feature selection on training data only, and keep the test set out of model selection. Explain the metrics, class-wise errors, runtime, feature relevance, meaningful failures, and limitations. Make code and the experimental setup reproducible; accuracy alone is not the goal.

Meet your TA during the final interview window with a working core algorithm, baseline, and preliminary results. Be ready to demonstrate the implementation and explain your own choices. Finish the website by the last instructional day; the interview happens earlier so you can use feedback to improve the final version. No second routine video is required.

## What the TA looks for

The TA looks for sound methodology, reproducible evidence, justified comparisons, honest interpretation, and your ability to explain the work. The Hub project page shows checkpoint-specific instructions and feedback. See [Individual and Team Projects](../) for shared rules and the other track.