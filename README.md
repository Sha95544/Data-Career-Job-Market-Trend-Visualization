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

### Favourite programming language among partcipants:
![image](https://github.com/Sha95544/Data-Career-Job-Market-Trend-Visualization/assets/62758405/1d853822-320d-46a8-a58f-41774ba4a254)

Python appears to be the most favoured programming language among all the participants with no other programming language posing a competetion to it. R follows in the second place. Python is a more general purpose programming language allowing users to seamlessly switch from web development to data analysis to machine learning while R was was initially designed specifically for statistical computing and graphics.Pyhton is also a fairly easy programming language to grasp for begineers and has a larger community as well as a rich collection of libraries for a variety of tasks owing to its greater popularity.The bars for languages titled as "Others" hold the third spot. This group ecompasses querying tools such as SQL. Other programming langugaes such as C++ and Java are far less popular since they cater to software development applications rather than data-related applications.

The result also shows that a major chunk of these responses are from data analysts and other data related professiosns such as data engineers and dara scientists make a smaller chunk in the overall distribution.
