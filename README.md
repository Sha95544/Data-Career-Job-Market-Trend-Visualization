# Data-Career-Job-Market-Trend-Visualization
This project visualizes a dataset from survey results of 600+ participants in PowerBI working in careers that are related or unrelated to the "data" domain. 

![image](https://github.com/Sha95544/Data-Career-Job-Market-Trend-Visualization/assets/62758405/2b9ad1f6-406b-466c-9ee6-a2549ad100b9)

## Data overview
The data for the dashboard comes from an excel file showing the responses of survey participants in a tabular format. Some columns such as "Unique ID", "email etc are shown below.It can be seen that some of these columns are blank and thus serve no purpose in creating the final dashboard.

![image](https://github.com/Sha95544/Data-Career-Job-Market-Trend-Visualization/assets/62758405/9c09540d-98c6-427d-8f86-f2a8f0bb2e4b)

The next image depict columns with useful data for the final dashboard. These show metrics such as the avergae salary of a participant, the industry they currently work in, and their favourite programming language etc.

![image](https://github.com/Sha95544/Data-Career-Job-Market-Trend-Visualization/assets/62758405/049f27e1-9f38-4558-93c9-7fda831df220)

## The data cleaning process
The data was transformed within the PowerQuery editor within PowerBI for cleaning purposes. 

The first step involved removing the colums labelled E to I since they are completely blank and serve no purpose for the visualization.

![image](https://github.com/Sha95544/Data-Career-Job-Market-Trend-Visualization/assets/62758405/cb85fa9a-e519-4938-8cb1-220e54e46c81)

In the image blow, the current yearly salary as shown as a range and is in text format. To claulate the the average salary of a each survey taker. To calculate the avergae salary these colums were seperated out into two different columns based on delimiters such as '-' and the average salary was calculated using DAX expressions.

![image](https://github.com/Sha95544/Data-Career-Job-Market-Trend-Visualization/assets/62758405/4c676fb1-9db3-499e-b0f8-d23eb3fc948c)

In the orignal dataset the column shown below lists the job titles of the people who filled the survey. The titles include "data analyst", "data scientist" etc among others. It is also worth noting that many of these titles are labelled as "Others" followed by a specific role telling that these careers aren't related to "data".

![image](https://github.com/Sha95544/Data-Career-Job-Market-Trend-Visualization/assets/62758405/f69774a8-8741-46f1-8090-eb8c9c98ac42)

To streamline the analysis process, these "Others-job title" field were replaced by just "Others" by splitting the column based on certain delimiters.

The same process was carried out for the columns showing the favourite programming languages of survey takers and the industry they are currently associated with. The image below shows those columns in the original dataset.

![image](https://github.com/Sha95544/Data-Career-Job-Market-Trend-Visualization/assets/62758405/8a2818fd-4cc1-4689-908e-9d26ec6d2cd0) 

The next snippet shows how those columns appear in the final dataset loaded into PowerBI after being cleaned within the PowerQuery editor.

![image](https://github.com/Sha95544/Data-Career-Job-Market-Trend-Visualization/assets/62758405/093ba932-2f7c-4328-943e-6881a713da89)



## Key insights 

### Total number of survey takers and their age demographics

![image](https://github.com/Sha95544/Data-Career-Job-Market-Trend-Visualization/assets/62758405/8bfc59eb-9342-453f-87ab-47cd4fc5709c)

The dashboard reveals that a total of 630 people completely filled the survey. A larger pool of respondants could have provided much better insights on the overall trend within the data job market as well as ensured a much better representation from other countries throughout the world.

The average age of "29.87" suggests that, on average, data professionals in this job market are in their late twenties or early thirties suggesting a significantly large portion of early career professionals within the inudstry. Furthermore, it goes on to show that the landscape wihin this domain is rather competitive as younger professionals may bring fresh perspectives and innovative ideas to the industry.

### Regions from where the survey was filled

![image](https://github.com/Sha95544/Data-Career-Job-Market-Trend-Visualization/assets/62758405/ad29dc3a-6b08-4943-bd7a-b9043ac788d6)

The final dashboard shows that a major chunk of the survey was filled primarliy by the residents of the USA followed by India, the UK and Canada in comparitively smaller proportions. Participation from the rest of the globe wasn't as significant as compared to these four countries.

### Favourite programming language among partcipants
![image](https://github.com/Sha95544/Data-Career-Job-Market-Trend-Visualization/assets/62758405/1d853822-320d-46a8-a58f-41774ba4a254)

Python appears to be the most favoured programming language among all the participants with no other programming language posing a competetion to it. R follows in the second place. Python is a more general purpose programming language allowing users to seamlessly switch from web development to data analysis to machine learning while R was was initially designed specifically for statistical computing and graphics.Pyhton is also a fairly easy programming language to grasp for begineers and has a larger community as well as a rich collection of libraries for a variety of tasks owing to its greater popularity.The bars for languages titled as "Others" hold the third spot. This group ecompasses querying tools such as SQL. Other programming langugaes such as C++ and Java are far less popular since they cater to software development applications rather than data-related applications.

The result also shows that a major chunk of these responses are from data analysts and other data related professiosns such as data engineers and dara scientists make a smaller chunk in the overall distribution.

## Average Salary by Job title
![image](https://github.com/Sha95544/Data-Career-Job-Market-Trend-Visualization/assets/62758405/25f13e1b-ea4d-4a46-936a-758e44cdd78d)

The "data scientist" job title appears to be the highest paid among all of the data-related job roles followed closely by "data engineer" in the second place. 

This could suggest that data scientists are have the highest global demand among all of the data related job roles (at the time of the survey) . 

Data scientists typically require a strong educational background in fields such as statistics, computer science and machine learning. A higher level of education may lead to higher salaries compared to roles that may not demand the same level of academic qualifications.

The complexity and difficulty of the work can influence salary levels. Data scientists may be tasked with solving unique and complex problems, while data engineers may focus more on infrastructure and data pipeline development.

## Happiness with work-life balance

![image](https://github.com/Sha95544/Data-Career-Job-Market-Trend-Visualization/assets/62758405/5c223738-a3bf-466b-a86c-830642532447)

A work-life balance rating of 5.74 out of 10 suggests that, on average, professionals in data-related careers are moderately satisfied with their work-life balance. This numerical value falls below the midpoint of 10, indicating that there might be room for improvement, and professionals, on average, are not overly satisfied with the balance between their work and personal lives.

One of the reasons for this figure could be due to intense workloads. The tech and data industries are known for having fast-paced and dynamic work environments. Professionals may feel pressure to meet high expectations and deliver results quickly, which can impact work-life balance.

Many individuals in data-related professions are passionate about their work and may willingly dedicate extra time to projects. While dedication is commendable, it can also lead to longer working hours and potential strain on work-life balance.

The rise of remote work, especially in the tech industry, may have introduced challenges in separating work and personal life. Professionals might find it difficult to establish clear boundaries when working from home, impacting their overall satisfaction with work-life balance.

## Happiness with salary

![image](https://github.com/Sha95544/Data-Career-Job-Market-Trend-Visualization/assets/62758405/1115f1b1-463c-429f-a20f-73811f8aa193)

A happiness with salary index of 4.27 out of 10 suggests that, on average, professionals in data-related careers are reporting a relatively low level of satisfaction or happiness with their current salary. This numerical value indicates that there is dissatisfaction with the compensation provided for their work.

Professionals may feel that their current compensation does not reflect the complexity of their roles or the level of responsibilities they undertake. If they believe they are being undercompensated for the value they provide, it can impact satisfaction.


## Perceived difficulty of breaking into data

![image](https://github.com/Sha95544/Data-Career-Job-Market-Trend-Visualization/assets/62758405/d76ec71a-10b0-4119-bb5d-ffd409d0f9aa)

Roughly 25% of the participants say that they have found it hard to break into / get their feet under the data career industry while on the other hand around 21% also report that the have found the overall process to be relativley easy. 

The results thus shed light on how one person's journey into the data realm can be entirely different from another one. One individual might have majored in computer science, mathematics or other related degrees gving them an edge within the job hunt over those who have come into this career form totally unrelated academics and have had to learm all the skills required from scratch. 

Transitioning within a company to a data-related role is also far more easier particularly when a person already has the domain knowledge of the current industry (such as becoming a data analyst within healthcare from a primrary healthcare related role) as compared to searching for the same kind of role in a different industry as an entry-level data proffesional with no prior industry expereince to back one's credibility.
