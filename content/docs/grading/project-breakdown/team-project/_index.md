---
title: Team Project
weight: 10
bookHidden: false
---
# Team Project

This is the **registered team's project** (40% of the course grade), not the individual assignment. Your team chooses a feasible question and lawful dataset and uses **one team website** for every stage.

1. [Team proposal](../proposal/): introduce the question, data, planned methods, evaluation, and team plan.
2. [Team midterm review and TA meeting](../midterm/): update that same website with work completed, early results, and next steps.
3. [Team final report and TA interview](../final/): complete the report and explain the team's work.
4. [Team website template](../team-website-template/): use the same core headings at all three stages. Preview or download the Markdown starter here. At final, the team may improve the design and add useful subsections without removing the core headings.

Check the [course schedule](../../../course-info/course-schedule-mahdi/) for dates. Keep the **team website link** in [ML Class Hub](https://ml-class.cc.gatech.edu/); it is separate from each student's individual link. Every member must understand the whole team project. See the [optional team bonus](../project-bonus/) and [past awardees](../award_galore/) for additional information.

---

## What the team-method requirements mean

- **Model or method:** code that uses data to make a prediction or find a pattern. Naming an algorithm in the report is not enough at midterm or final.
- **Run it:** apply the method to the project's real dataset and show its output.
- **Evaluate it:** show a suitable number, table, or figure and explain what that evidence does and does not tell you.
- **Baseline:** a simple result to beat. For a positive/negative prediction task, always predicting the more common label is one possible baseline.
- **Supervised learning:** train using known answers (labels), such as reviews already marked positive or negative, then predict labels for new reviews.
- **Unsupervised learning:** find patterns without using those answers during training, such as grouping similar reviews. If labels exist, they can be used afterward to help interpret the groups, not to train the grouping method.

## One example across stages

Suppose a team has customer reviews and asks **"Can we predict whether a review is positive or negative, and what themes appear in the reviews?"** This is only an example; teams may choose other questions, datasets, and algorithms.

1. **Proposal:** describe the data and plan to try a majority-label baseline, logistic regression, and a decision tree to predict positive/negative labels. A CS 7641 team also plans a method such as K-means to group reviews without using labels. Explain what each method would help answer; no results are required yet.
2. **Midterm:** a CS 4641 team has run the baseline and at least one classifier, and shows results and a limitation. A CS 7641 team has also run a grouping method and shows what the groups reveal. Show real work, even if results are weak.
3. **Final:** compare the baseline, logistic regression, and decision tree on the **same prediction task** using an appropriate test measure. The CS 7641 team also reports the grouping results separately. **Do not compare clustering and classification by pretending they have the same accuracy measure**; they answer different questions. Explain the tradeoffs, errors, and what was learned.

The named algorithms and review dataset are illustrative, not required. A different valid baseline, model family, or dataset can satisfy the requirements when the team explains its choices and results.

## Choose an ambitious but feasible topic

A strong topic has a clear question, data you can lawfully use, a baseline, an evaluation plan, and time for error analysis. Possible domains include language, vision, health or scientific data, recommendations, time series, security, robotics, and responsible AI. Simply calling a model API, using a fashionable dataset, or promising high accuracy is not enough. Ask what your project will teach someone that a straightforward baseline cannot.

Originality can come from a new question, data source, application setting, careful comparison, method adaptation, evaluation under realistic constraints, or a usable system. Novelty is encouraged, **not required for full credit**. A careful, reproducible study can be excellent even when its models are established. The [past awardees](../award_galore/) offer inspiration, not templates to copy; some older Georgia Tech links require sign-in.

Treat the project as portfolio-quality work: document your own contribution, methods, evidence, limitations, and code so you can explain it on a résumé or in an interview. A strong project can provide a starting point for later research or a paper.

## Shared integrity and data rules

Both projects permit disclosed, verified generative-AI assistance under [General Course Policies](../../../guidelines/general/). Cite sources you actually read; verify claims, results, and references. Protect private and licensed data. Describe individual contributions honestly. The [optional team-project bonus](../project-bonus/) rewards substantial work beyond the required project; [awards](../award_galore/) are separate recognition.