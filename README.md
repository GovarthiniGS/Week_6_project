# Week_6_project
# Problem statement
The primary goals are to improve user engagement and increase the completion rate of the process. Specifically, Vanguard aims to determine if the new design leads to a higher completion rate and lower error rate while also considering the cost-effectiveness of the new design implementation.
# Hypotheses
I have formulated several hypotheses to test various aspects of the new design's effectiveness
Completion Rate Hypotheses
Error Rate Hypotheses
Average time spent on each step
Cost-Effectiveness Hypotheses
Demographics Hypotheses
# Timeline
The experiment was conducted from March 15, 2017, to June 20, 2017.
# Key Components
Control Group: This group interacted with the traditional online process.
Test Group: This group interacted with the new, enhanced digital interface.
Process Sequence:
Initial page
Step 1
Step 2
Step 3
Confirmation page (indicating process completion)
# Data Wrangling
Checking for null values : df.isnull().sum()
Handling missing values : df= fill na ()
Checking for duplicates: df.duplicated()
String formatting: df.rename()
# performance Metrica
# Performing Chi-Squared Tests for comparing Completion rate
p-value = 0.00
H0 is not equal to H1
Rejecting the null hypothesis

# Performing Chi-Squared Tests for comparing error rate
p-value = 0.00
H0 is not equal to H1
Rejecting the null hypothesis

# Completion rate with a Cost-Effectiveness threshold
Control Completion Rate: 65.59%
Test Completion Rate: 68.75%
Completion Rate Difference: 3.16%
                              threshold = 0.05(5%)
The increase in completion rate (3.16%) does not meet the 5% threshold.
                             # Define hypotheses
                  # H0: The increase in completion rate is less than 5%
                  # H1: The increase in completion rate is at least 5%
                                          Z-statistic: -4.91
                                                           P-value: 0.99
Fail to reject the null hypothesis: The increase in completion rate does not meet the 5% threshold.

# Additional Hypothesis testing
Tested whether the average age of clients engaging with the new process is the same as those engaging with the old process
              T-statistic: -19.12
               P-value: 0.00

   # H0: The average age of clients in the Test group is not significantly different from the average of clients in the control group
   # H1: The average age of clients in the Test group is significantly different from the average of clients in the control group
Reject the null hypothesis: The average age of clients in the Test group is significantly different from the average age of clients in the Control group.
# Challenges
Data Quality and Cleaning
Data Integration
Multiple sessions
Back tracking
Library Deprecations
# Learnings
Importance of Data cleaning
Derived metrics
Statistical testing
Updated libraries
# Recommendations & conclusion
Combining or reducing the number of process steps which could reduce error rate
They can also consider giving detailed information for each step or question
Getting feedback from all the participants
User support & Education
Referral bonus





