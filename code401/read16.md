# Data Science Primer

 ## Bird's Eye View


### Supervised Learning
Supervised learning includes tasks for "labeled" data (i.e. you have a target variable).

In practice, it's often used as an advanced form of predictive modeling.
Each observation must be labeled with a "correct answer."
Only then can you build a predictive model because you must tell the algorithm what's "correct" while training it (hence, "supervising" it).
Regression is the task for modeling continuous target variables.
Classification is the task for modeling categorical (a.k.a. "class") target variables.

### Unsupervised Learning
Unsupervised learning includes tasks for "unlabeled" data (i.e. you do not have a target variable).

In practice, it's often used either as a form of automated data analysis or automated signal extraction.
Unlabeled data has no predetermined "correct answer."
You'll allow the algorithm to directly learn patterns from the data (without "supervision").
Clustering is the most common unsupervised learning task, and it's for finding groups within your data.


### Exploratory Analysis

- Plot Numerical Distributions


Next, it can be very enlightening to plot the distributions of your numeric features.

Often, a quick and dirty grid of histograms is enough to understand the distributions.

Here are a few things to look out for:

- Distributions that are unexpected
- Potential outliers that don't make sense
- Features that should be binary (i.e. "wannabe indicator variables")
- Boundaries that don't make sense
- Potential measurement errors

At this point, you should start making notes about potential fixes you'd like to make. If something looks out of place, such as a potential outlier in one of your features, now's a good time to ask the client/key stakeholder, or to dig a bit deeper.


- Plot Categorical Distributions
Categorical features cannot be visualized through histograms. Instead, you can use bar plots.

In particular, you'll want to look out for sparse classes, which are classes that have a very small number of observations.

- Plot Segmentations
Segmentations are powerful ways to observe the relationship between categorical features and numeric features.

- Study Correlations
Finally, correlations allow you to look at the relationships between numeric features and other numeric features.

## Data Cleaning
The steps and techniques for data cleaning will vary from dataset to dataset. As a result, it's impossible for a single guide to cover everything you might run into.

However, this guide provides a reliable starting framework that can be used every time. We cover common steps such as fixing structural errors, handling missing data, and filtering observations.

## Feature Engineering


The first of these heuristics is checking to see if you can create any interaction features that make sense. These are combinations of two or more features.

By the way, in some contexts, "interaction terms" must be products between two variables. In our context, interaction features can be products, sums, or differences between two features.

## Model Training

It might seem like it took us a while to get here, but professional data scientists actually spend the bulk of their time on the steps leading up to this one:

- Exploring the data.
- Cleaning the data.
- Engineering new features.
Again, that’s because better data beats fancier algorithms.

In this lesson, you'll learn how to set up the entire modeling process to maximize performance while safeguarding against overfitting. We will swap algorithms in and out and automatically find the best parameters for each one