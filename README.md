# Project Title
## Mental Health Survey Analysis

---

### Project Overview
This project aims to analyze a mental health survey dataset to understand the prevalence of mental health issues, common challenges faced by individuals, and the potential factors influencing mental health. By utilizing data visualization techniques, such as histograms, bar charts, and correlation heatmaps, this analysis will visualize the distribution of variables and examine relationships between them. Additionally, hierarchical clustering will help group individuals with similar characteristics and uncover distinct patterns within the data.

---

### Problem Statement
Mental health is a critical aspect of overall well-being, yet it is often overlooked and underfunded. Many individuals face barriers such as stigma, lack of access to care, and unawareness of coping strategies, which can worsen mental health challenges. This project seeks to identify prevalent mental health issues, explore factors influencing mental health, and provide actionable insights. Understanding these areas can contribute to more effective mental health interventions, policies, and awareness efforts.

---

### Project Objectives

1. **Understand the prevalence of mental health issues:** Analyze mental health-related variables to identify common challenges and assess the spread of mental health conditions among individuals.
2. **Explore relationships between variables:** Investigate correlations among variables to uncover potential factors that influence mental health.
3. **Identify distinct groups within the data:** Use hierarchical clustering to group individuals based on similar characteristics, identifying distinct mental health patterns.
4. **Provide insights and recommendations:** Based on the analysis, offer insights into the factors affecting mental health and provide recommendations for individuals, organizations, and policymakers.

---

### Data Overview

The dataset consists of **300,000 rows and 17 columns**. The columns capture a variety of attributes related to mental health, demographics, and lifestyle factors that may influence mental well-being. Data source can be found here - https://www.kaggle.com/datasets/bhavikjikadara/mental-health-dataset

Below is a brief description of each column:

- **Timestamp**: Time when the survey was completed.
- **Gender**: Gender of the respondent.
- **Country**: Country where the respondent resides.
- **Occupation**: Respondent’s occupation.
- **Self_employed**: Indicates if the respondent is self-employed.
- **Family_history**: Whether there is a family history of mental health issues.
- **Treatment**: If the respondent has sought treatment for mental health issues.
- **Days_Indoors**: Number of days spent indoors, potentially reflecting isolation or remote work.
- **Growing_Stress**: Indicator of increased stress levels over time.
- **Changes_Habits**: Changes in habits that could affect mental health.
- **Mental_Health_History**: Respondent’s personal history of mental health issues.
- **Mood_Swings**: Frequency of mood swings experienced by the respondent.
- **Coping_Struggles**: Indicator of struggles with coping mechanisms.
- **Work_Interest**: Level of interest in work, which could correlate with mental well-being.
- **Social_Weakness**: Difficulty in social situations.
- **Mental_health_interview**: Willingness to discuss mental health in an interview setting.
- **Care_options**: Awareness of mental health care options available.

This diverse set of variables allows for an in-depth analysis of different aspects of mental health, helping to uncover patterns, correlations, and potential areas for intervention.

--- 

### Data Visualization and Interpretations

#### Distribution of Days Indoors

- ![Distribution of Days Indoors](https://github.com/Phenomkay/Mental-Health-Survey-Analysis/blob/b711e463078d7fe9f14a4cf7fb3464e845042042/distribution%20of%20days%20indoors.png)

**Key Observations:**

- **Bimodal Distribution**: The distribution exhibits two distinct peaks, suggesting two common patterns of indoor behavior:
    - **Frequent outings**: A significant portion of respondents reported going out every day or almost every day.
    - **Extended indoor periods**: Another group spent more than two months indoors, indicating extended periods of isolation.

**Potential Insights:**

- **Mental Health Implications**: This bimodal distribution might suggest different mental health implications for individuals who frequently go out versus those who spend extended periods indoors.
- **Lifestyle Factors**: The distribution could be influenced by occupation, location, or personal preferences, which may affect the time spent indoors.
  
---

#### Distribution of Growing Stress

- ![Distribution of Growing Stress](https://github.com/Phenomkay/Mental-Health-Survey-Analysis/blob/4aa5580d0cb1da4e61c372f1d3b8464cf84f752b/distribution%20of%20growing%20stress.png)

**Key Observations:**

- **Bimodal Distribution**: We see two distinct peaks:
    - **Significant Growth in Stress**: Many respondents reported a significant increase in stress.
    - **No Change in Stress**: Another group reported no change in their stress levels.

**Potential Insights:**

- **Prevalence of Stress**: The high frequency of respondents indicating "Yes" shows that a significant portion of the population is experiencing growing stress.
  
---

#### Distribution of Coping Struggles

- ![Distribution of Coping Struggles](https://github.com/Phenomkay/Mental-Health-Survey-Analysis/blob/4aa5580d0cb1da4e61c372f1d3b8464cf84f752b/distribution%20of%20coping%20struggles.png)

**Key Observations:**

- **Bimodal Distribution**: Two peaks:
    - **Significant Coping Struggles**: Many respondents reported significant coping struggles.
    - **No Coping Struggles**: Another group reported no coping struggles.

**Potential Insights:**

- **Prevalence of Coping Struggles**: This distribution indicates that a significant portion of the population faces challenges in coping with stressors.

---

#### Treatment Distribution

- ![Treatment Distribution](https://github.com/Phenomkay/Mental-Health-Survey-Analysis/blob/4aa5580d0cb1da4e61c372f1d3b8464cf84f752b/treatment%20distribution.png)

**Key Observations:**

- **Bimodal Distribution**: Roughly equal frequencies for "Yes" and "No" indicate that the population is evenly divided regarding treatment-seeking behavior.

**Potential Insights:**

- **Equal Treatment Seeking**: This suggests a significant portion of the population seeks treatment for mental health issues, while another significant portion does not.

---

#### Self Employment Distribution

- ![Self Employment Distribution](https://github.com/Phenomkay/Mental-Health-Survey-Analysis/blob/4aa5580d0cb1da4e61c372f1d3b8464cf84f752b/self%20employment%20distribution.png)

**Key Observations:**

- **Uneven Distribution**: The "No" category has a significantly higher frequency, indicating a larger population of respondents not self-employed.

**Potential Insights:**

- **Prevalence of Traditional Employment**: The dominance of "No" suggests that traditional employment is more common among the surveyed population.

---

#### Family History Distribution

- ![Family History Distribution](https://github.com/Phenomkay/Mental-Health-Survey-Analysis/blob/4aa5580d0cb1da4e61c372f1d3b8464cf84f752b/family%20history%20distribution.png)

**Key Observations:**

- **Bimodal Distribution**: Noticeable difference in frequency, with "No" being dominant.

**Potential Insights:**

- **Prevalence of Family History**: The higher frequency of "No" suggests that family history of mental health issues is less common in the population.

---

#### Correlation Heatmap

- ![Correlation Heatmap](https://github.com/Phenomkay/Mental-Health-Survey-Analysis/blob/4aa5580d0cb1da4e61c372f1d3b8464cf84f752b/mental%20health%20correlation%20heatmap.png)

**Key Observations:**

- **Weak Correlations**: Limited relationships between variables, with only a few showing moderate associations.

**Potential Insights:**

- **Limited Interdependencies**: These weak correlations suggest relatively independent variables.

---

#### Hierarchical Clustering

- ![Hierarchical Clustering](https://github.com/Phenomkay/Mental-Health-Survey-Analysis/blob/4aa5580d0cb1da4e61c372f1d3b8464cf84f752b/dendrogram.png)

**Key Observations:**

- **Distinct Clusters**: Three distinct clusters with varying sizes.

**Potential Insights:**

- **Natural Groupings**: The dendrogram indicates clear clusters, suggesting patterns that can be further analyzed for unique characteristics.

---

### Insights and Recommendations

1. **Stress Management:** Offer training on effective stress management techniques.
2. **Coping Skills Training:** Provide programs to help individuals develop robust coping mechanisms.
3. **Mental Health Support:** Encourage professional help-seeking and the use of support networks.
4. **Address Barriers to Treatment:** Work to remove barriers, including cost, accessibility, and stigma, to improve access to mental health care.
5. **Promote Early Intervention:** Advocate for early intervention to prevent mental health issues from escalating.
6. **Reduce Stigma:** Support ongoing efforts to reduce the stigma around mental health.

---

### Conclusion: Mental Health Awareness
This analysis emphasizes the importance of mental health awareness and accessible, effective mental health services. Understanding the factors that impact mental health and providing the appropriate support can enable individuals to manage their challenges and lead healthier, more fulfilling lives.
