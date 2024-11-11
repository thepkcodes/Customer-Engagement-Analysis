**Case Description**

In 2022, there were high expectations for the growth of the 365 company and increased student engagement based on the introduction of new website platform features. Some of these features included an XP system that enabled students to track their progress, level up, and earn rewards by completing various learning objectives. The platform also offered in-app coins that could be exchanged for special awards, a leaderboard where students could compete for top positions in different divisions, earning weekly rewards and advancing up the ladder, and streaks to motivate students to maintain consistent learning habits. Additionally, the company expanded its course library, covering a broader range of topics to provide its students with a richer set of skills and attract a larger audience. These enhancements were anticipated to positively impact the student experience, create an effective strategy for customer engagement, and contribute to the company's success in the coming year. With this Customer Engagement Analysis in Excel project, you must analyze whether the new additions to the platform have increased student engagement.

**Project Files**

During this Customer Engagement Analysis in Excel project, you’ll analyze a dataset from the 365 company. It’s important to note that personal user information has been masked to ensure privacy, and the database's volume has been reduced for practical reasons. Nevertheless, you can consider this dataset to accurately represent the company’s operations—providing a realistic and relevant context for your analysis.

In addition, consider the following information about the column values while working with the data:

student_id – the unique identifier for each student in the dataset. The field contains IDs for students who used the 365 Data Science platform with free or paid accounts in Q4 2021 (October 1, 2021 – December 31, 2021, both included) and Q4 2022 (October 1, 2022 – December 31, 2022, both included).
student_country – identifies the country of each student. The field provides information about students’ geographic location and can help analyze regional differences or conduct country-specific analyses.
Paid – indicates whether a student had a paid account during the specified period. It is a binary variable, where '1' represents a paid account and '0' represents a free or unpaid account. It helps differentiate between students who have access to additional features or content through a paid subscription.
minutes_watched_21 – represents the student’s engagement level, as expressed by the number of minutes a student has watched in Q4 2021.
minutes_watched_22 – denotes the student’s engagement level, as expressed by the number of minutes a student has watched in Q4 2022.

**Project Rquirements**

To complete this Customer Engagement Analysis in Excel, please install Microsoft Excel 2007 or later. Additionally, you’ll need the Data Analysis ToolPak to perform the analysis. Follow the steps below to check if the Data Analysis ToolPak is installed.

Open Microsoft Excel.
Go to the Data tab in the top menu.
Look for the Data Analysis button in the Analysis group. If you see it, the ToolPak has already been installed, and you can proceed with the analysis.

Installing the Data Analysis ToolPak (for Windows):

Click on the File tab in the top left corner of Excel.
Select Options at the bottom of the left-hand navigation pane.
In the Excel Options window, click on Add-Ins on the left.
In the Manage drop-down menu at the bottom of the window, select Excel Add-ins and click the Go button.
In the Add-Ins window, check the box next to Analysis ToolPak and click OK to install it.

**Methods Used**

Descriptive Statistics
Inferential Statistics

**Tools Used**

MS Excel

**Result Overview**

1.**Descriptive Statistics**

**Task 1:** The analysis indicates that, on average, low-engagement-paid students showed a more significant increase in their watching time compared to free-plan students from Q4 2021 to Q4 2022. This suggests that paid-plan students may perceive more value in the platform, potentially due to access to premium features or content. Conversely, the median watch time decreased for free-plan students, implying that typical students in this group did not enhance their engagement. These findings suggest that engagement strategies may be more effective for paid-plan students, possibly driven by their monetary investment. However, increased variability among paid-plan students suggests diverse responses to platform offerings, highlighting the need for personalized approaches to boost engagement. Further analysis is warranted to understand the factors influencing engagement among paid and free-plan students.

**Task 2:** The rising skewness and kurtosis observed in both groups from Q4 2021 to Q4 2022 indicate a growing proportion of students watching substantially more content compared to the majority. Particularly noteworthy is the trend among free-plan students, exhibiting higher skewness and kurtosis in Q4 2022 than their paid-plan counterparts. This suggests a pronounced increase in engagement among free-plan students during this period, emphasizing a notable shift in viewing patterns.

2.**Confidence Interval:** The comparison between paid and free-plan students in Q4 2022 reveals a substantial difference in engagement levels. Paid-plan students watched significantly more minutes, with a confidence interval of 351.99 to 384.72 minutes, compared to free-plan students, with a confidence interval of 61.71 to 70.59 minutes. This aligns with the expectation that paid-plan subscribers are more engaged due to their investment in the platform. However, higher engagement among paid-plan students may not solely stem from the subscription; additional features or content availability could contribute. Conversely, factors such as platform changes or competition may explain the decrease in engagement observed among free-plan students.

3.**Hypothesis Testing:**

**Task 4:** The t-statistic value of -3.05 is below the critical value of -1.645, leading to the rejection of the null hypothesis. This indicates that the mean minutes watched by students in Q4 2021 is significantly smaller than the mean minutes watched in Q4 2022. However, it's important to note that rejecting the null hypothesis does not confirm the alternative hypothesis; it simply suggests that the data provide enough evidence against the null hypothesis. The t-statistic of 29.78 for free-plan students surpasses the critical value of -1.645, resulting in the failure to reject the null hypothesis. This indicates insufficient evidence to conclude that the mean engagement of free-plan students in Q4 2022 is smaller than that of paid-plan students. These findings align with previous results from confidence intervals, emphasizing the distinction in engagement patterns between the two groups. In terms of error types, a Type I error could lead to incorrect assertions of increased engagement, while a Type II error might overlook actual increases, affecting decision-making and resource allocation within the company. The significance level, determined by the researcher, influences the probability of these errors, underscoring the importance of careful consideration in hypothesis testing.

**Task 5:** The conclusions indicate a failure to reject the null hypothesis, as both the calculated t-statistic surpasses the critical value and the p-value exceeds the specified significance level. If the hypothesis that US students watch more or an equal amount of content as Indian students is rejected, it implies that, on average, US students consume less content than their Indian counterparts.
**Market Differences:** The disparity in engagement between Indian and US students may imply that the platform is more appealing or relevant to the Indian audience, highlighting the need for further exploration into the specific features or content that drive this discrepancy. However, such inquiries extend beyond the current analysis's scope.
**Growth Oppurtunities:** The lower engagement among US students presents a potential growth opportunity for the 365 company. Strategies to enhance engagement may involve targeted marketing initiatives, augmenting content tailored to US students' preferences, or implementing other strategic approaches.
**Resource Allocation:** For instance, if Indian students exhibit higher engagement, it may justify directing resources towards developing content and features specifically tailored to this demographic.
