# Data-Career-Job-Market-Trend-Visualization
This project visualizes a dataset from survey results of 600+ participants in PowerBI working in careers that are related or unrelated to the "data" domain. 
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

![Uploading image.png…]()

