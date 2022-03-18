# Olympic-Games-Analysis-Project-
Visualize data that will help readers understand countries' historical performance in the Summer Olympics and gain insights into competitors using SQL, Power bi, Dax
# Business Problem
"As a data analyst working at a news company you are asked to visualize data that will help readers understand how countries have performed historically in the summer Olympic Games.

You also know that there is an interest in details about the competitors, so if you find anything interesting then don’t hesitate to bring that in also.

The main task is still to show historical performance for different countries, with the possibility to select your own country."
# Data Collection & Table Structures
The necessary data was first put into a SQL database and afterwards transformed using the transformations that you can see below.
 **Olympic Games View**
 
![image](https://user-images.githubusercontent.com/63034550/159065367-3817c3a7-37a9-467a-aa1c-a86e0c0d63db.png)

# Data Model
As this is a view where dimensions and facts have been combined, the data model that is created in Power BI is one table. The query from previous step was loaded in directly.

![Capture1](https://user-images.githubusercontent.com/63034550/159065547-35e57b23-b8c6-4094-a7ce-45f664d3208e.PNG)

# Measurements
The following calculations were created in the Power BI reports using DAX (Data Analysis Expressions). To lessen the extent of coding, the re-use of measures (measure branching) was emphasized:

![image](https://user-images.githubusercontent.com/63034550/159066317-3a001347-a8eb-452c-a081-e9bf27448b1b.png)

# Olympic Games Analysis
The finished dashboard consist of visualizations and filters that gives an easy option for the end users to navigate the summer games through history. Some possibilities are to filter by period using year, nation code to focus on one country or look into either a competitor or specific sports over time.

![Capture](https://user-images.githubusercontent.com/63034550/159066532-d69455c2-ebc8-483e-848e-0ea4472775a6.PNG)


