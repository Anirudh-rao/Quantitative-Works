# Probability Theory
Probability theory is the mathematical branch that quantifies uncertainty, measuring how likely events are to occur. It assigns values between \(0\) (impossible) and \(1\) (certain) to outcomes. The framework relies on foundational concepts like the sample space (all possible results) and events (subsets of the sample space).

This section is divided into several parts:

1. Part 1: Foundations of Probability: Introduces core concepts like sample spaces, events, axioms of probability, and essential counting techniques.

2. Part 2: Conditional Probability and Independence: Explores how probabilities change given new information, leading to Bayes’ Theorem and the concept of independence.

3. Part 3: Random Variables and Distributions: Formalizes the idea of random outcomes using random variables and studies common patterns through discrete and continuous distributions.

4. Part 4: Multiple Random Variables: Extends the concepts to scenarios involving more than one random variable, covering joint distributions, covariance, and correlation.

5. Part 5: Limit Theorems and Their Significance: Discusses the foundational Law of Large Numbers and Central Limit Theorem, explaining why probability works in the long run and why the Normal distribution is ubiquitous.

6. Part 6: Advanced Topics and Applications: Provides introductions to Bayesian Inference, Markov Chains, and Monte Carlo methods, showcasing powerful applications of probability.


## Required software and setup

To follow along with the coding examples, you will need:

- Python: Version 3.7 or higher is recommended. We suggest installing Python via the Anaconda Distribution, which conveniently packages Python and many essential data science libraries.

- Jupyter Notebook or JupyterLab: The interactive environment used throughout the book. This comes bundled with Anaconda.

## Core Python Libraries:

- NumPy: For numerical operations, especially array manipulation. (Ex: Ensuring you can run import numpy as np successfully.)

- SciPy: For scientific and technical computing, particularly scipy.stats for probability distributions and scipy.special for functions like combinations/permutations.

- Matplotlib & Seaborn: For data visualization.

- Pandas (Optional but Recommended): For data manipulation, especially when working with datasets in later examples.

Chapter 1 provides detailed steps for setting up your environment. Typically, after installing Anaconda, you can install any missing libraries using pip or conda:

```
# Using conda (recommended if you used Anaconda)
conda install numpy scipy matplotlib seaborn pandas jupyterlab

# Or using pip
pip install numpy scipy matplotlib seaborn pandas jupyterlab

```