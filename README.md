# A/B Testing
A/B testing, also known as split testing, is a method of comparing two versions of a webpage, app, or other user experiences to determine which one performs better.
Steps for Running A/B Tests:
Based on the data there are two types of A/B tests we can run.
Binary A/B Testing: Learn how to compare two versions of a binary outcome to determine which one performs better.
Continuous A/B Testing: Discover how to compare means from continuous data and understand the statistical significance of their differences.

1.Set the Probability of Hypothesis:
Type 1 Error(Alpha):
Definition: The probability of rejecting the null hypothesis when it is true.
Common Value: 0.05 (5%)
If the p-value is greater the 5% we fail to reject the Hypothesis.

Type II Error (Beta)
Definition: The probability of failing to reject the null hypothesis when it is false.
Common Value: 0.20 (20%)
Power of the Test: 1 - Beta, often set to 0.80 (80%)

2.We need sample size (minimum recors) before we perform A/B Test.
Calculate Sample Size
To determine the necessary sample size, use the formula that incorporates the desired significance level (alpha), power (1 - beta), and effect size.

3.Assign Users
Assign Users: Randomly assign users to the control or treatment group.

4.Perform Statistical Test
For binary outcomes, use a Z-test.
For continuous outcomes, a t-test can be used.

5.Analyze the Test Results
Practical Significance
Beyond statistical significance, assess the practical significance of the results to determine if the observed effect is meaningful in a real-world context.
