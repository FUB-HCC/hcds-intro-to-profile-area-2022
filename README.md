# Introduction to Profile Area 2022 - Human-Centered Data Science
This repository contains all material needed to participate in "Introduction to Profile Area" exercise of the research group [Human-Centered Computing (HCC)][1] at Freie Universität Berlin.

You can find the introduction slides to the exercise inside this repository here **TODO: Add Slides**

## Agenda
- Introduction: 4 PM
- Forming Groups: 4:15 PM
- Working on Task 1: 4:20 PM
- Discussion: 5:15 PM
- End: 5:30 PM


## Task (Explanation method: LIME)

**Goal:** 🥅 &nbsp; Getting familiar with LIME as an explanation method for evaluating classifiers.

LIME was introduced as a model-agnostic and local explanation/interpretability method in the lecture. We will use the tutorial [Basic usage, two class. We explain random forest classifiers.](https://marcotcr.github.io/lime/tutorials/Lime%20-%20basic%20usage%2C%20two%20class%20case.html) provided in the [LIME repository](https://github.com/marcotcr/lime) on GitHub.

1. **First things first:** Get familiar with the [LIME repository](https://github.com/marcotcr/lime) on GitHub. Please read the README: https://github.com/marcotcr/lime.
2. Get the tutorial notebook running in a collaborative environment. You can use one of the options listed below the task, or one of you shares the screen.
3. Please step through the notebook and understand what is happening in each line. Please add markdown cells to your notebook to document your understanding of what is happening. You can also write down the question you have in mind, while stepping through the notebook or include links or references you used to get a deeper understanding of the notebook.
4. Get explanations for three different documents of the given [newsgroup dataset](https://scikit-learn.org/stable/datasets/#the-20-newsgroups-text-dataset) (currently document number 83 is used).
5. **Reflection**: Please answer the following questions for the discussion: 
    1. Which documents did you choose?
    2. What did you learn about the model?
    3. How _well_ do you think the classifier works? Why?
    4. For what role(s) (from task 1) are LIME explanations useful? Why?
    5. How useful is LIME for a non-data-scientist (e.g. non-ml-experts or designer)? Why?
    6. What **question types** is LIME able to answer? Why?


***
❗ Additional Information
## Running a collaborative jupyter notebook
There are many sites available that offer collaboration services with jupyter notebooks (with a different degree of collaboration functionality). Here is a non-exhaustive list of options:
- [CoCalc](https://cocalc.com/features/jupyter-notebook)
- [Deepnote](https://deepnote.com/)
- [Google Colab](https://colab.research.google.com/)
- [Kaggle Kernels](https://www.kaggle.com/code)
- [Binder](https://mybinder.org/)
- [Curvenote](https://curvenote.com/)

Jupyter notebook is by itself running a local server. You can also host that that server and enable collaboration using the `--collaborative` flag.
***


[1]:	https://www.mi.fu-berlin.de/en/inf/groups/hcc/index.html
