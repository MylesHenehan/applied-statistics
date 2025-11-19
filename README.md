# README

## Overview

This repository contains **`problem.ipynb`**, a jupyter notebook in which I complete four statistical simulation exercises. These tasks involve randomization, sampling, and hypothesis testing, covering concepts such as permutation testing, sampling distributions, Type II error, and ANOVA.

------------------------------------------------------------------------

## Problems

### **Problem 1 --- Extending the Lady Tasting Tea**

In this problem, I extend Fisher's original Lady Tasting Tea experiment.

-   Original setup: 8 cups (4 tea-first, 4 milk-first)
-   New setup: 12 cups (8 tea-first, 4 milk-first)

I simulate the experiment by repeatedly shuffling cup labels with NumPy.
The goal is to estimate the probability that a participant would
correctly identify all cups purely by chance. I compare this estimated
probability to the original 8-cup experiment and discuss whether the
change in probability suggests adjusting (extending or relaxing) the
p-value threshold of the test.

------------------------------------------------------------------------

### **Problem 2 --- Normal Distribution**

I explore the sampling distribution of standard deviations from the
standard normal distribution.

Steps: 1. Generate 100,000 samples of size 10 from N(0,1) 2. For each
sample, compute: - Sample standard deviation (ddof=1) - Population
standard deviation (ddof=0) 3. Plot both distributions on the same
histogram with transparency 4. Describe differences between the two
distributions 5. Discuss how these differences change as sample size
increases

------------------------------------------------------------------------
## Requirements

Before running the notebook, install all required Python packages:
- Ensure you have Python 3.x installed.

Install dependencies using:
pip install -r requirements.txt


This will install all necessary packages listed in requirements.txt.

------------------------------------------------------------------------

## Full Reference List
- Analytics Toolkit. (2018). Confidence intervals, p-values, percent change and relative difference. Available at: https://blog.analytics-toolkit.com/2018/confidence-intervals-p-values-percent-change-relative-difference/ (Accessed: 10 November 2025).

- Fisher, R.A., (1935). The Design of Experiments. Edinburgh and London: Oliver & Boyd.

- Jaisingh, L.R. (2006) Statistics for the Utterly Confused, 2nd edn. McGraw-Hill, p. 5.

- GeeksforGeeks (2025) Overlapping Histograms in Python | Matplotlib. Available at: https://www.geeksforgeeks.org/python/overlapping-histograms-with-matplotlib-in-python/ (Accessed: 19 November 2025).

- Matplotlib. (no date). Matplotlib documentation. Available at: https://matplotlib.org/stable/contents.html (Accessed: 6 October 2025).

- NumPy. (no date). NumPy reference documentation. Available at: https://numpy.org/doc/stable/reference/index.html#reference (Accessed: 6 October 2025).

 - NumPy (no date) numpy.std — Standard deviation. Available at: https://numpy.org/devdocs/reference/generated/numpy.std.html (Accessed: 19 November 2025).

- Python Software Foundation. (no date a). itertools — Functions creating iterators for efficient looping. Available at: https://docs.python.org/3/library/itertools.html (Accessed: 6 October 2025).

- Python Software Foundation. (no date b). math — Mathematical functions. Available at: https://docs.python.org/3/library/math.html (Accessed: 6 October 2025).

- Python Software Foundation. (no date c). random — Generate pseudo-random numbers. Available at: https://docs.python.org/3/library/random.html (Accessed: 6 October 2025).

- Sagan, C. (1995). The Demon-Haunted World: Science as a Candle in the Dark. New York: Random House.

- Statisticshowto (no date) Bessel’s correction: Definition, examples. Available at: https://www.statisticshowto.com/bessels-correction/ (Accessed: 18 November 2025).

- Statsig. (no date a). Alpha and significance level in statistics. Available at: https://www.statsig.com/perspectives/alpha-significance-level-statistics (Accessed: 10 November 2025).

- Statsig. (no date b). Significance and stricter thresholds. Available at: https://www.statsig.com/perspectives/significance-stricter-threshold (Accessed: 10 November 2025).

- Statsig. (no date c). What is statistical significance? Available at: https://www.statsig.com/perspectives/what-is-statistical-significance (Accessed: 10 November 2025).

- YouTube. (2023). Understanding the p-value (video). Available at: https://www.youtube.com/watch?v=KS6KEWaoOOE (Accessed: 2 November 2025).