
# Introduction

Applications of statistical thinking continue to grow. It is only a matter of spotting the 

The inspiration for this analysis comes from a comment made in response to a video about Scott Walsh's woodworking and joint strength comparisons. The commenter raised a thought-provoking point about the statistical analysis used in the video. As statistics students, we are always eager to delve into the intricacies of data analysis and explore the underlying questions. In this discussion, we will focus on whether it's appropriate to consider the spread of results and normal distribution in data analysis, as well as the use of trimmed means.

# Background

Scott Walsh conducted joint strength tests, using a machine to measure the force required to break various types of joints. He collected five samples per joint and calculated the average after removing the maximum and minimum values. We will address three main questions in this analysis:

1. Was excluding the maximum and minimum values from the average a sound statistical practice?
2. What statistical tests can we perform with this data?
3. How many samples should be collected for a follow-up test to examine the glue-starved hypothesis?

# Understanding Trimmed Means and Summary Metrics

Trimmed means, although they remove data points, are valuable for summarizing data, as they provide robustness against outliers. The concept of trimming can be seen as a spectrum, with the mean at one end, the median at the other, and trimmed means in between. In this case, trimmed means offer a balanced approach. We can also consider the use of winsorized means, where extreme values are replaced by the next largest value, offering another robust summary metric option.

# Data Collection and Transparency

One might question the necessity of collecting data if values can be removed or altered. However, the critical factor here is transparency. Scott Walsh's practice of showing all the data is commendable because it allows for open dialogue and scrutiny. This aligns with the fundamental principle of data analysis: share all the data, not just summary statistics like the mean, median, or trimmed mean.

# Statistical Testing

Although Scott Walsh did not set out to perform a formal hypothesis test, we can conduct statistical tests using the data. In this analysis, we use an inductive argument to determine the likelihood of differences in joint strength. Instead of traditional t-tests, we employ a permutation test, which is more intuitive and avoids complex equations. The p-value represents the probability of observing a mean difference greater than the original mean difference.

# Addressing Assumptions and Sample Size

One may argue that the data is not normally distributed, and that a larger sample size is typically required for hypothesis testing. However, the need for normality assumptions depends on the chosen statistical method. In this case, the size of the observed differences in force allows for a smaller sample size. We'll explore how to determine the appropriate sample size in the subsequent sections.

# Testing Hypotheses

With this data, we can test various hypotheses. For instance, we can assess whether dovetail joints are stronger than butt joints. We obtain a p-value of 0.031, suggesting that dovetails are indeed stronger. The data is available for further exploration, allowing us to gain a deeper understanding of the relationship between data spread and mean differences.

# Determining Sample Size for Follow-up Tests

Suppose we wish to test the glue-starved hypothesis, comparing box joints and dovetail joints without glue starvation. To achieve a 95% chance of avoiding false positives and maintain a power of 80%, we need to collect 50 joints (25 per group) and use a permutation test. This test will help us assess if the joints are at least 200 pounds/in² stronger without glue starvation.

# Conclusion

In conclusion, as statistics students, we can appreciate the nuances of data analysis and the importance of transparency in data reporting. This analysis provides valuable insights into statistical testing, the role of trimmed means, and the determination of sample sizes for hypothesis testing. We encourage further exploration of the data to deepen our understanding of these statistical concepts.
