# Individual Project

This is the required layout for **your own individual project website** (the GitHub Pages link you register in ML Class Hub). This course page is only the example; your website will contain **your** answers, figures, and results. Keep the numbered headings and subsections below in this order. Replace the instructions under them with your own writing. At midterm, complete Sections 1–3 and mark final-only work as planned. By the final deadline, complete every section. Do not copy an example result as if it were yours.

**ML Class Hub will give you the dataset.** It does not supply a ready-made analysis or results. Use the dataset the course gives you; do not substitute another one. The final prediction questions depend on that dataset and will be stated separately. This template does not decide them.

## 1. Project question

### 1.1 What am I trying to learn?

State the question in plain language. Say why someone would care about the answer. For example, if the assigned data are images, a question might be whether useful groups can be found without labels and how well the images can later be classified. This is only an illustration, not an assigned question or dataset.

### 1.2 What have I completed so far?

At each checkpoint, briefly say what you have actually finished and what is still planned. **Do not describe a planned experiment as a result.** Update this short status when you update the same website.

## 2. The data provided by the course

### 2.1 What data did I receive?

Give the dataset name and the course-provided download or information link. Say how many examples it contains, what one example looks like, and what information (features) is available for each example. Explain missing values or data problems you noticed and what you did about them. If the course gives restrictions on using or sharing the data, follow those instructions; do not publish the data itself unless allowed.

### 2.2 What will I try to predict at the final?

Write the prediction question or questions the course specifies **for the dataset you receive**. Say, in ordinary words, what the model will see and what answer it will try to give. If the course has not yet specified this for your dataset, write **"To be provided by the course"** here and do not invent an answer. The website will be updated when that information is available.

### 2.3 How did I separate the data?

Explain how you kept some examples for learning and others for checking your work. **Training data** are examples the model learns from. **Validation data** help you choose settings or decide between models. **Test data** are saved until the end to check how well your chosen model works on examples it has not seen. State how many examples you put in each part. Do not let the model learn from the test examples or use their answers while choosing a model. This mistake is sometimes called **data leakage**. When comparing models, use the same saved test examples for each one.

## 3. Midterm: finding patterns without using the answers

This is **unsupervised learning**: your method finds patterns without using the known class labels to train it. Complete this section and the separate midterm video required in ML Class Hub.

### 3.1 How did I prepare the data?

Explain what you changed before running the method: for example, how you handled missing values or put numbers on a comparable scale. A **feature** is a piece of information about each example, such as a measurement or a column in a dataset. First use all available features. Later compare this with a version using less information. If a preparation step learns from data, fit it on training examples only.

### 3.2 How did I choose or reduce features?

Use at least **one** method that reduces the amount of information given to clustering. It may keep fewer of the original features or make a smaller set of new combined features. Name the method you used, say how many features remain, and explain your choice in plain language. Do not use known answers (class labels) to choose or train this midterm method.

### 3.3 What groups did the clustering method find?

**Clustering** means putting similar examples into groups without telling the method the correct class for each example. Name the clustering method and its important settings. Run it twice: once with all features and once with the smaller feature version from Section 3.2. State how many groups it found or was asked to find. Show examples or a figure that helps a reader see what the groups contain.

### 3.4 How did I judge the groups?

Use one or more ways **taught in class** to judge the groups **without looking at known class answers**. Name what you chose, give the actual result for grouping with all features and with fewer features, and explain whether that result is better or worse and why. No particular score is required in this template. Show a figure or a few examples from the groups and explain what they reveal. Do not show only a number without interpretation.

If the dataset has reliable known answers, you **may** compare them with the finished groups afterward as an extra check. This is optional. Do not invent answers, and do not use them to make or tune the groups. Also describe at least one group that makes sense and one result that is confusing or unsuccessful.

### 3.5 What did I learn, and what will I try next?

Summarize the main finding, one limitation, and the next experiment. Explain weak or unexpected results honestly. Your midterm video link is submitted in ML Class Hub, not as a new website.

## 4. Final: predicting the assigned answers

This is **supervised learning**: a model learns from examples whose answers (class labels) are known, then predicts answers for other examples. Keep Section 3 on the website and add the work below.

### 4.1 Which methods and prediction models did I run?

- <strong><span style="background-color:#e7f1fb;color:#123b67;border-left:4px solid #123b67;padding:0.1em 0.35em">CS 4641 · Undergraduate</span></strong>: run **two** different feature-selection/reduction methods and **two** different prediction models.
- <strong><span style="background-color:#f4eafa;color:#54236b;border-left:4px solid #54236b;padding:0.1em 0.35em">CS 7641 · Graduate</span></strong>: run **three** different feature-selection/reduction methods and **three** different prediction models.

List the methods and models you **actually ran**. A feature method can carry over from Section 3 if you use it again here. Explain what each does in your own words and why you chose it. A name alone is not enough.

### 4.2 Which comparisons did I make?

For every prediction question the course specifies for the dataset, run each required prediction model first with **all features** and then with **each** of your required smaller feature versions. Change only the feature version or model being tested; keep the examples used for training, choosing settings, and final testing the same. Prepare the data using training examples, choose settings using validation examples, and use test examples for the final check. This lets a reader tell whether a different model or fewer features really helped.

### 4.3 What were the results?

For each prediction question, show the results for **every model you ran** with all features and with each smaller feature version. Use the **real names** of your methods and your **actual scores** in a clearly labeled table or chart. Explain what the score measures, whether higher or lower is better, and what mistakes the model made. Do not show only your best result. There is no placeholder table to copy: its rows and names must come from the dataset and methods you actually used.

### 4.4 What worked, what failed, and why?

Compare results that answer **the same prediction question**. Explain where using fewer features helped or hurt, which answers the model confused, and whether one method took much longer to run. Show at least one concrete mistake or failure. A small score difference alone does not prove that one method is always better. State what you cannot conclude from these experiments.

## 5. Conclusion

Answer the question from Section 1 using your actual results. State the main limitation and one useful next step. Do not claim more than the evidence shows.

## 6. References

List the sources you actually used and cite them where they support a claim, method, or dataset description. Do not invent references.

## 7. AI-use disclosure

If you used generative AI for this project, name the tool, what you used it for, how much of the work it affected, and what you checked yourself. Follow the course AI policy. If you did not use it, say so.
