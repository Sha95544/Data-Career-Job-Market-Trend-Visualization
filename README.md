# Data-Career-Job-Market-Trend-Visualization
This project visualizes a dataset from survey results of 600+ participants in PowerBI working in careers that are related or unrelated to the "data" domain. 

![image](https://github.com/Sha95544/Data-Career-Job-Market-Trend-Visualization/assets/62758405/2b9ad1f6-406b-466c-9ee6-a2549ad100b9)

## Data overview
The data for the dashboard comes from an excel file showing the responses of survey participants in a tabular format. Some columns such as "Unique ID", "email etc are shown below.It can be seen that some of these columns are blank and thus serve no purpose in creating the final dashbpard.

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

The same process was carried out for the columns showing the favourite programming languages of survey takers and the industry they are currently associated with:

![image](https://github.com/Sha95544/Data-Career-Job-Market-Trend-Visualization/assets/62758405/5ff1a49c-23c0-476b-8547-7047455046c1)

