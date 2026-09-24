---
title: Team Website Template
weight: 7
bookHidden: false
---
# Team Project Website Template

This is a **rendered Markdown example** of the required team-report shape, not a sample project to copy. Keep these **core headings** on the same team website from proposal through final so TAs can find the required evidence. Teams may add subsections, improve the layout, and build richer interactive features or software beyond this starting structure; do not replace or hide the required content. At proposal, write a plan; at midterm, replace plans with work completed so far; at final, revise the same sections to report the full evidence. Use your own question, data, methods, and results. See the [proposal](../proposal/), [midterm review](../midterm/), [final report](../final/), and [worked example](../#one-example-across-stages).

## 1. Introduction and related work

### 1.1 Research question and motivation

State one specific question, why it matters, and what a useful answer would look like. At final, explain any justified change from the proposal.

### 1.2 Prior work and your contribution

Summarize relevant sources you actually read. Explain what your team is testing or building beyond simply using an existing library. Do not claim novelty without evidence.

## 2. Problem definition and data

### 2.1 Data source and permission

Provide source, access or license, scale, features, labels when present, and privacy or responsible-use limits. Explain any data you could not obtain.

### 2.2 Preparation and evaluation split

Describe cleaning, train/validation/test construction, and how leakage is prevented. At proposal, describe the plan; later, report what was actually done.

## 3. Methods and baselines

### 3.1 Simple baseline

Name a simple comparison that answers the same question as the more advanced method. At midterm and final, show its actual result.

### 3.2 Models or methods

For each method, say what it does, why it fits the question, and whether it is **planned**, **running**, or **completed**. The [course-level minimums](../final/) apply: CS 4641 includes supervised learning; CS 7641 includes both supervised and unsupervised learning. Compare methods that answer the same question; report different tasks separately.

## 4. Experiments and results

### 4.1 Measures and figures

State what each measure means. Report actual values and clear figures, not just screenshots of code or a list of model names. Use suitable evidence for prediction and for grouping; do not force them into one accuracy comparison.

### 4.2 Required interactive visualization

By the final deadline, include **at least one working interactive visualization** tied to your own data or model results. For example, a reader could change a filter, class, feature, threshold, or parameter and see the relevant chart or model behavior update. JavaScript, animation, or a small simulation may be used when useful. Explain what the interaction reveals that a static figure does not. **A static image, an automatic animation with no useful interaction, or decorative motion does not satisfy this requirement.** The visualization is part of the required team project; it is **not itself bonus work**.

### 4.3 Result comparison and failures

Show the baseline and model results side by side for each comparable task. Explain tradeoffs, surprising cases, and failed experiments. At proposal, state what you plan to compare; at midterm, show preliminary evidence; at final, report the completed comparison.

## 5. Discussion and limitations

Explain what the results support, what they do not support, possible bias or uncertainty, and practical or ethical limits. Separate observation from speculation.

## 6. Conclusion and next steps

Answer the original question as far as the evidence allows. Name the next experiment that would be most useful.

## 7. Project plan and member contributions

Include the Gantt chart or equivalent milestones. At every checkpoint, identify each member's actual work and next responsibility. Update the record when the plan changes.

## 8. References and AI-use disclosure

Cite sources actually used near the claims they support. Disclose any generative-AI tools, their purpose and scope, and what the team verified under the [course policy](../../../guidelines/general/).

## 9. Optional work beyond the required project

A **working software product or decision-support tool** that uses the team's model—beyond the report website and its required interactive visualization—may qualify for the [optional bonus](../project-bonus/) when the team provides evidence and can demonstrate it. A JavaScript chart alone is required work, not an extra point. Bonus credit is not automatic; other substantial extensions are listed on the bonus page.

### Copyable Markdown heading outline

```markdown
# Team Project
## 1. Introduction and related work
### 1.1 Research question and motivation
### 1.2 Prior work and your contribution
## 2. Problem definition and data
### 2.1 Data source and permission
### 2.2 Preparation and evaluation split
## 3. Methods and baselines
### 3.1 Simple baseline
### 3.2 Models or methods
## 4. Experiments and results
### 4.1 Measures and figures
### 4.2 Required interactive visualization
### 4.3 Result comparison and failures
## 5. Discussion and limitations
## 6. Conclusion and next steps
## 7. Project plan and member contributions
## 8. References and AI-use disclosure
## 9. Optional work beyond the required project
```