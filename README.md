# Hypothesis-Testing-using-R
## Analysis of Dining Preference in The Campus by performing Hypothesis Testing using RStudio <br>
###  Study Objective: <br>
The objective of this study is to investigate the proportion of individuals who prefer "Cafe By The Valley" over all other eateries on the campus. The aim was to gather unbiased insights by ensuring an equal representation from each department within the campus, recognizing that different departments may have varying preferences.
<br>
---
Two statistical tests were employed to assess the preference for "Cafe By The Valley" – the prop.test and fisher.test functions in R Studio. In both the tests, Alpha or the Level of Significance is taken as 0.5 <br>
Two statistical tests were employed to assess the preference for "Cafe By The Valley" – the prop.test and fisher.test functions in R Studio. In both the tests, Alpha or the Level of Significance is taken as 0.5<br>
Prop.pest is the test of given proportions or equal proportions. This is a one sample proportion test, it is a type of Z-test.In this case, we used it to test if the proportion of people preferring "Cafe By The Valley" is significantly different from 50%, which is the null hypothesis value (p = 0.5).<br>
With a dataset of 50 rows, the one-sample proportions test is used to check if the proportion of people preferring "Cafe By The Valley" is significantly different from what we expected (0.5). The continuity correction is applied to improve accuracy when dealing with discrete data, helping us understand if the cafe's preference is statistically significant. Essentially, it tells us if the observed preference is likely a real effect and not just due to random chance in our limited dataset.<br>
This test revealed a statistically significant result (p-value = 0.01253) with an estimated proportion of 0.67. This suggests strong evidence to reject the null hypothesis (p = 0.5) in favor of the alternative, indicating that more than half of the surveyed individuals prefer "Cafe By The Valley."<br><br>
Fisher's Exact Test is used for small datasets or 2x2 contingency tables, exploring associations between categorical variables. It calculates the probability of seeing a specific frequency distribution in the table. A contingency table is a way to organize categorical data, showing the count of observations for different combinations of variables. It's important to note that Fisher's Exact Test is a non-parametric method, meaning it doesn't rely on specific assumptions about the underlying distribution of the data like the data does not have to follow a normal distribution.<br>
The test is particularly useful when dealing with categorical data, as it provides an exact p-value for the observed distribution in the contingency table. This ensures the validity of the statistical inference, especially when analyzing proportions or odds ratios in smaller datasets.<br>

The Fisher's Exact Test gave a low p-value of 0.00384, showing a strong and significant connection between choosing "Cafe By The Valley" and the surveyed group. The infinite odds ratio emphasizes a substantial association, highlighting a clear preference for Cafe By The Valley.<br>

Inference:<br>
Both statistical tests consistently point towards a significant preference for "Cafe By The Valley" among the surveyed individuals. The proportion of individuals favoring this eatery is estimated to be approximately 0.67, and the odds of choosing it over others are significantly different from the null hypothesis value of 1. These findings provide strong evidence to support the inference that "Cafe By The Valley" is a preferred choice among the campus community.
---

