
# Data Professional Breakdown

### Dashboard Link : https://app.powerbi.com/links/hg1R8Ng2kc?ctid=2929b0e6-f3ef-4cd4-a1e2-54a38c2065df&pbi_source=linkShare

Here, the excel file used for this project : [Power BI - Final Project.xlsx](https://github.com/user-attachments/files/18495195/Power.BI.-.Final.Project.xlsx)

# Introduction

The rapid evolution of data-related careers—such as data engineering, data analysis, and data science—has significantly reshaped the modern professional landscape. These roles are at the forefront of innovation, enabling businesses to harness data-driven insights for strategic decision-making. However, with this rapid growth comes an urgent need to understand the human aspect of these professions: **Are professionals in this field happy? Do they find their roles challenging or rewarding? Are they satisfied with their salaries and work-life balance?**



# Background

This project seeks to address these questions by analyzing the results of a comprehensive survey conducted among data professionals. The survey explores key aspects such as career satisfaction, perceived challenges, salary happiness, and priorities for future job opportunities. With responses from individuals at various stages of their data-related careers, this analysis aims to provide actionable insights into the current state of the field and its potential areas for improvement.
By leveraging tools like Power Query for data cleaning and Power BI for visualization, this project is designed to deliver a clear and engaging narrative. The findings will be made available to the broader community on GitHub, serving as a resource for professionals, aspiring data enthusiasts, and organizations aiming to attract and retain top talent in this competitive field.



- **Tools I used**

To achieve this, the following approaches were employed:

**1**. Power Query was used to clean unnecessary data and standardize the dataset, ensuring that the analysis was based on accurate and consistent information.

**2**. DAX (Data Analysis Expressions) was utilized to create new measures, providing clearer insights into the real meaning behind the collected data.

**3**. Power BI served as the primary tool for diving deep into the survey data, enabling the creation of interactive visualizations and uncovering key trends and patterns.


Here's a brief view of column created with DAX:

![Image](https://github.com/user-attachments/assets/c0514b55-6ae0-4be5-8606-82af883e3933)

As we can see, the initial table containing current yearly salary were not appropriate for our analysis. So, the urge to get real number was clearly visible. For that, I uses the DAX formula:

= Table.AddColumn(#"Lignes filtrées1", "average salary", each ([#"Q3 - Current Yearly Salary (in USD) - Copier.1"] + [#"Q3 - Current Yearly Salary (in USD) - Copier.2"])/ 2)
 
 # The analysis

 Each query for this project aimed at investigating specific aspect of breaking in data field job market. here's how I approached each question:

For this survey, we have been asking questions to 630 people Online with an average age of almost 30 years old.

![Image](https://github.com/user-attachments/assets/f67bf166-39bb-4941-a2b2-d74f13425e16)



 **1.Are professionals in this field happy?**

Happiness in the field of data professions can be evaluated through key metrics like salary satisfaction, work-life balance, and overall job fulfillment. From the survey responses:

- Salary Satisfaction

The average satisfaction level regarding salary was relatively low, with a mean score of **4.27** out of 10.

![Image](https://github.com/user-attachments/assets/d5578a7f-b63b-47c0-84ca-b4d3cf72fa11)
This suggests that many professionals feel undercompensated, which could be a factor influencing their overall happiness.
- Work-Life Balance



Respondents rated their satisfaction with work-life balance higher, with an average score of **5.74** out of 10.

![Image](https://github.com/user-attachments/assets/a67d3046-ec75-4163-9e35-28d84beb6cb5)

Although slightly better than salary satisfaction, this indicates that work-life balance remains an area with room for improvement.

- Overall Trends

There is significant variation across roles and career stages, with entry-level professionals and those switching careers into data fields reporting slightly lower happiness levels.
Senior professionals, although generally happier with their positions, still expressed concerns regarding workload and compensation.


### 2. Do Professionals Find Their Roles Challenging or Rewarding?
To answer this question, let explore the survey responses related to.

The perceived difficulty of entering the field.
How fulfilling or rewarding professionals find their current roles.
The alignment between their expectations and reality in terms of career satisfaction.

**1. Difficulty of Entering the Field
Survey responses revealed the following:**

44 respondents reported finding it “Very Difficult” to break into the field, while 156 said it was “Difficult.”
In contrast, 134 found it “Easy,” and 27 said it was “Very Easy.”
A large portion (269) felt it was “Neither Easy nor Difficult.”
This suggests that while some individuals face challenges in entering data professions, the experience varies significantly depending on background, resources, or prior exposure to data-related work.

**2. Rewarding Aspects of Roles**

Although data on this specific question isn’t explicitly stated, high demand for these roles likely contributes to feelings of value and accomplishment. However, as stated previously, salary dissatisfaction (average score **4.27/10**) and moderate work-life balance ratings (**5.74/10**) might dampen the overall sense of reward.

**3. Challenges in Day-to-Day Work
Professionals in data careers often deal with:**

Complex problem-solving, which can be intellectually stimulating but also stressful.
Long hours or high expectations to meet business objectives.
Those who view these challenges as opportunities to grow are likely to find their roles more rewarding. For others, these challenges may lead to burnout or frustration.


### 3. Are Professionals Satisfied with Their Salaries and Work-Life Balance?
Satisfaction with salaries and work-life balance are critical factors in understanding the well-being of data professionals. Here's what the survey data reveals:

**1. Salary Satisfaction**

The average satisfaction score for salary is **4.27** out of 10, which indicates a generally low level of contentment.
A significant portion of respondents rated their salary satisfaction between 2 and 7, with very few expressing high satisfaction.
This suggests that salary levels may not meet professionals' expectations, which could affect their overall happiness and motivation.

**2. Work-Life Balance Satisfaction**

The average score for work-life balance satisfaction is 5.74 out of 10, higher than salary satisfaction but still moderate.
Most respondents rated their satisfaction between 4 and 8, indicating a mixed experience.
While work-life balance is less of a concern than salaries, it remains an area where improvements could positively impact professionals' well-being.

**Comparative Observations**

Salary vs. Work-Life Balance: Respondents appear to be slightly more content with their work-life balance than with their salaries. However, both metrics fall below optimal satisfaction levels.
Professionals in senior roles or those with more experience may report slightly better scores, likely due to higher salaries or more control over their schedules.
Conclusion While data professionals appreciate the intellectual challenges and opportunities in their field, dissatisfaction with salaries and a moderate work-life balance rating reveal areas for improvement. Addressing these issues—through competitive compensation and policies supporting flexibility—could enhance their overall satisfaction and retention.

# What I learned

This project was my first experience working with Power BI, and it was a valuable learning opportunity. I developed skills in:

**Using Power Query** to clean and standardize data, ensuring consistency for analysis.
Creating new measures with **DAX** to derive meaningful insights from raw data.
Designing interactive **visualizations in Power BI**, which helped uncover trends and clearly present findings.
Through this project, I not only improved my technical proficiency but also gained a deeper understanding of survey data analysis and the challenges faced by data professionals. Sharing these findings on GitHub has allowed me to contribute to the broader data community.

Here are the images of the Power Bi Service and on the desktop presentation 

![Image](https://github.com/user-attachments/assets/a16a3993-250c-47b5-8052-d35188304733)



![Image](https://github.com/user-attachments/assets/8f917fd2-0d5a-422a-80d6-fa5f7028f159)




# Conclusion

## Insights

This analysis revealed several critical findings about the state of data professionals:

**1.Happiness Levels:** Professionals are moderately satisfied with their roles, though salary dissatisfaction stands out as a key issue. Work-life balance is relatively better but still falls short of expectations for many.

**2.Challenging Yet Rewarding Roles:** While roles in the data field are intellectually stimulating and offer growth opportunities, barriers to entry and workload challenges are common pain points.

**3.Opportunities for Improvement:** Addressing salary concerns and fostering better work-life balance could significantly enhance overall job satisfaction and retention in this field.

## Closing Thoughts

This project has provided valuable insights into the experiences of data professionals, highlighting both the strengths and challenges within the field. It has also been a tremendous learning opportunity for me, as I applied tools like Power Query, DAX, and Power BI to transform raw survey data into actionable narratives. The findings, shared on GitHub, aim to contribute to ongoing discussions about how organizations and individuals can thrive in the evolving data landscape.

As the demand for data professionals continues to grow, it is essential to prioritize their well-being and satisfaction. Doing so will not only benefit individuals but also strengthen the data-driven innovations that power today’s world.















 
