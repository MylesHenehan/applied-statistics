# README

## Overview

This repository contains **`problems.ipynb`**, a jupyter notebook in which I complete four statistical simulation exercises. These tasks involve randomization, sampling, and hypothesis testing, covering concepts such as permutation testing, sampling distributions, Type II error, and ANOVA.

The aim of this repository is to demonstrate an understanding of probability, simulation, and statistical inference through a series of progressively structured exercises.

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

Here, I explore the sampling distribution of standard deviations from the
standard normal distribution.

This problem involves generating 100,000 samples of size 10 from a standard normal distribution and computing both sample and population standard deviations for each sample. The two distributions are visualised using overlapping histograms, and differences between them are analysed, including how these differences change as sample size increases.

------------------------------------------------------------------------
### **Problem 3 --- t-Tests**

In this problem, I simulate how often an independent t-test fails to detect a real difference between two groups (a Type II error).

By generating samples with varying effect sizes and repeatedly running the test, I estimate the probability of failing to reject the null hypothesis across different mean differences. I then visualise how the Type II error rate decreases as the difference between group means increases.

------------------------------------------------------------------------
### **Problem 4 --- ANOVA**

Here, I generate three independent samples with different true means and apply a one-way ANOVA to determine whether the groups differ statistically. The analysis demonstrates how ANOVA evaluates multiple groups simultaneously and highlights why it is preferred over running several separate t-tests, which would inflate the risk of false positives.

------------------------------------------------------------------------
## Requirements

Before running the notebook, install all required Python packages:
- Ensure you have Python 3.x installed.

Install dependencies using:
pip install -r requirements.txt

This will install all necessary packages listed in requirements.txt. All libraries used are from the approved list provided for the assignment.

------------------------------------------------------------------------

## Full Reference List
- Analytics Toolkit. (2018). Confidence intervals, p-values, percent change and relative difference. Available at: https://blog.analytics-toolkit.com/2018/confidence-intervals-p-values-percent-change-relative-difference/ (Accessed: 10 November 2025).

- Brownlee, J. (2022). Random seeds and reproducibility. Available at: https://medium.com/data-science/random-seeds-and-reproducibility-933da79446e3 (Accessed: 18 December 2025).

- DataCamp. (2024). Sample Standard Deviation: The Key Ideas. Available at: https://www.datacamp.com/tutorial/sample-standard-deviation (Accessed: 21 November 2025).

- Fisher, R.A.. (1935). The Design of Experiments. Edinburgh and London: Oliver & Boyd.

- Frost, J. (no date). Sample Size Essentials: The Foundation of Reliable Statistics. Statistics By Jim. Available at: https://statisticsbyjim.com/basics/sample-size/ (Accessed: 23 November 2025).

- GeeksforGeeks. (2025). T-test. Available at: https://www.geeksforgeeks.org/data-science/t-test/ (Accessed: 25 November 2025).

- Hayes, A. (2025). Sampling Errors in Statistics: Definition, Types, and Calculation. Investopedia. Available at: https://www.investopedia.com/terms/s/samplingerror.asp(Accessed: 4 December 2025).

- Investopedia. (2023). ANOVA (Analysis of Variance). Available at: https://www.investopedia.com/terms/a/anova.asp (Accessed: 13 December 2025).

- Jaisingh, L.R. (2006). Statistics for the Utterly Confused, 2nd edn. McGraw-Hill.

- JMP. (no date). T-Test (One-Sample T-Test) — JMP stats knowledge portal. Available at: https://www.jmp.com/en/statistics-knowledge-portal/t-test/one-sample-t-test (Accessed: 30 November 2025).

- GeeksforGeeks. (2025). Create a Pandas DataFrame from Lists. [online] Available at: https://www.geeksforgeeks.org/python/create-a-pandas-dataframe-from-lists/ (Accessed 1 December 2025).

- GeeksforGeeks. (2025). Overlapping Histograms in Python | Matplotlib. Available at: https://www.geeksforgeeks.org/python/overlapping-histograms-with-matplotlib-in-python/ (Accessed: 19 November 2025).

- Laerd Statistics. (n.d.) One-way ANOVA statistical guide. Available at: https://statistics.laerd.com/statistical-guides/one-way-anova-statistical-guide-2.php (Accessed: 13 December 2025).

- LibMontana (n.d.) Multiple pairwise comparisons using Tukey’s HSD. Available at: https://arc.lib.montana.edu/book/statistics-with-r-textbook/item/59 (Accessed: 14 December 2025).

- Maini, N. (2023). Standard Deviation and Bessel’s Correction. Available at: https://nickmaini.substack.com/p/standard-deviation-and-bessels-correction (Accessed: 21 November 2025).

- Matplotlib. (no date). Matplotlib documentation. Available at: https://matplotlib.org/stable/contents.html (Accessed: 6 October 2025).

- Numiqo. (no date). Effect size for Independent-Samples t-Test – Tutorial. Numiqo. Available at: https://numiqo.com/tutorial/effect-size-independent-t-test (Accessed: 4 December 2025).

- NumPy. (no date). numpy.arange — NumPy v… documentation. Available at: https://numpy.org/devdocs/reference/generated/numpy.arange.html (Accessed: 29 November 2025).

 - NumPy. (no date) numpy.std — Standard deviation. Available at: https://numpy.org/devdocs/reference/generated/numpy.std.html (Accessed: 19 November 2025).

- NumPy. (no date). NumPy reference documentation. Available at: https://numpy.org/doc/stable/reference/index.html#reference (Accessed: 6 October 2025).

- Python Software Foundation. (no date). itertools — Functions creating iterators for efficient looping. Available at: https://docs.python.org/3/library/itertools.html (Accessed: 6 October 2025).

- Python Software Foundation. (no date). math — Mathematical functions. Available at: https://docs.python.org/3/library/math.html (Accessed: 6 October 2025).

- Python Software Foundation. (no date). random — Generate pseudo-random numbers. Available at: https://docs.python.org/3/library/random.html (Accessed: 6 October 2025).

- Qualtrics. (no date). T-Test. Available at: https://www.qualtrics.com/en-gb/experience-management/research/t-test/ (Accessed: 25 November 2025).

- Sagan, C. (1995). The Demon-Haunted World: Science as a Candle in the Dark. New York: Random House.

- SciPy. (no date). scipy.stats.ttest_ind — SciPy v… documentation. Available at: https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.ttest_ind.html (Accessed: 30 November 2025).

- Scribbr. (2021). Statistical Power and Why It Matters. Scribbr. Available at: https://www.scribbr.com/statistics/statistical-power/ (Accessed: 4 December 2025).

- Statistics by Jim. (no date). Independent Samples T-Test. Available at: https://statisticsbyjim.com/hypothesis-testing/independent-samples-t-test/#google_vignette (Accessed: 25 November 2025).

- Statistics By Jim. (n.d.). Using confidence intervals to compare means. Available at: https://statisticsbyjim.com/hypothesis-testing/confidence-intervals-compare-means/ (Accessed: 14 December 2025).

- Statisticshowto. (no date). Bessel’s correction: Definition, examples. Available at: https://www.statisticshowto.com/bessels-correction/ (Accessed: 18 November 2025).

- Statology. (2023). Family-wise error rate (FWER) explained with examples. Available at: https://www.statology.org/family-wise-error-rate/ (Accessed: 13 December 2025).

- Statology. (2020). How to perform Tukey’s HSD test in Python. Available at: https://www.statology.org/tukey-test-python/ (Accessed: 14 December 2025).

- Statsig. (2025). Alpha and significance level in statistics. Available at: https://www.statsig.com/perspectives/alpha-significance-level-statistics (Accessed: 10 November 2025).

- Statsig. (2024). How to interpret a p-value in a T-test: A step-by-step guide. Statsig. Available at: https://www.statsig.com/perspectives/interpret-pvalue-ttest-guide(Accessed: 4 December 2025).

- Statsig. (2025). How to interpret t-statistic & hypothesis testing. Available at: https://www.statsig.com/perspectives/interpret-t-statistic-hypothesis-testing (Accessed: 25 November 2025).

- Statsig. (2024). Significance and stricter thresholds. Available at: https://www.statsig.com/perspectives/significance-stricter-threshold (Accessed: 10 November 2025).

- Statsig. (2024). What is statistical significance? Available at: https://www.statsig.com/perspectives/what-is-statistical-significance (Accessed: 10 November 2025).

- YouTube. (2013). StatQuest: ANOVA, clearly explained!!!. Available at: https://www.youtube.com/watch?v=rK3mXS3gHyI (Accessed: 9 December 2025).

- YouTube. (2023). Understanding the p-value (video). Available at: https://www.youtube.com/watch?v=KS6KEWaoOOE (Accessed: 2 November 2025).

- YouTube. (2020). What Is The Difference: Population Vs Sample Standard Deviation (video). Available at: https://www.youtube.com/watch?v=DA2MpLLs8Pg (Accessed: 21 November 2025).