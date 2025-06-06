# Exploratory Data Analysis of the Behavioral Risk Factor Survellance System (BRFSS) Dataset
This project uses the Behavioral Risk Factor Surveillance System (BRFSS) dataset to explore research questions related to sleep, self-perceived emotional support, depression, diabetes, and high blood pressure. This was the capstone project for the online certification in Statistics using R offered by Duke University. 

Link to project on Rpubs: https://rpubs.com/architn01/1309201 

**Research Questions:**
1. Is there a link between sleeping less and depression. Is this relationship moderated by self-percieved emotional support?
2. Are people who are diagnosed with diabetes at a younger age more likely to need insulin and have eye-health related issues.
3. Are people who sleep less, more likely to have high blood pressure (hypertension)?


**Key Findings:**
1. As one sleeps less, they are more likely to experience depression. Emotional support was very strongly negatively correlated with depression. As one feels they have less social support they are more likely to be depressed.  Emotional support approached a significant moderating effect (p = 0.13) on the relationship between sleep and depression, but only at the lowest level of self-percieved level of emotional support. Specifically, among participants who reported never receiving emotional support, more sleep was significantly associated with lower levels of depression (b = -1.40, p = 0.13).

2. The younger an individual is at the age of a diabetes diagnosis, the more likely they are to need insulin or to experience eye-health related issues. This could be due to factors such as being diagnosed with type-1 diabetes as a child, where the use of insulin is neccessary due to the inability to produce the hormone on one’s own. Another possible explanation is that the length of time with the diagnosis leads to greater complications (in both type 1 and type 2 diabetes), as seen with the eye-health related issues in this study.

3. It was found that both a lack of sleep (insomnia) and an excessive amount of sleep (hypersomnia) was associated with high blood pressure. The optimal amount of sleep for healthy blood pressure was found to be around 7-8 hours of sleep, which make sense given current research.
