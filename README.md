# PwC PowerBI Experience Call Center Trends Analysis

I participated in the open-access PwC Data Analytics Virtual Experience Program with Forage. Where I worked as a business data analyst to help an organization named “PhoneNow” to analyze their data and help them understand how they can leverage on their massive amount of data.

Live interact Dashboard on:https://github.com/Jagannathro/PWC_Call_Center/blob/main/Dashboard.mp4

## Project Overview & Business Problem

- Client’s Name: PhoneNow

- Client’s Industry: Telecom Company

I am working as a data analyst intern for PwC Switzerland when one of our important clients, a big telecom company reach out to me, to help visualize their data. Claire, the call center manager at PhoneNow wants me to help bring out insight from their call center data, she wants to know the total number of calls answered and abandoned, speed of answer, length of calls, overall customer satisfaction, and most importantly, she’s interested in knowing the accurate overview of long-term trends in customers and agent’s behavior.


From Claire’s mail, her KPIs includes (but not limited to):

- Overall customer satisfaction
- Overall calls answered and abandoned
- Calls by time
- Average speed of answer
- Agents performance quadrant.

### Tools Used to Carry Out This Project

- Microsoft Excel: which I used primarily to convert the data into a proper table.

- Microsoft PowerBI: As a PowerBI specialist, I carried out my data cleaning using the power query editor in PowerBI. I also carried out the visualization showing my insights (focusing on my KPIs) using the Data Analysis Expression (DAX) language for creating and calculating columns, measures and custom tables.

### Data Cleaning Process

- Data cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect, incomplete, irrelevant, duplicate, or improperly formatted.

- Data cleaning plays an important role in the analytical process by making sure that the answers we uncover are reliable, accurate, and of high quality.

- Below are the data cleaning process I carried out using the power query editor in PowerBI:

- I started by importing my data from Excel into PowerBi, however, instead of loading my data directly for visualization, I transform the data by loading it into the power query editor for cleaning.

- One of the reasons why we do data cleaning is to remove incomplete data. However, looking at my data, the incomplete data (Null) have values they represent i.e. they are related to either calls that are not answered (N) or calls that the agents are not able to resolve, hence, removing those data will limited the accuracy of my data and in turn the credibility of my analysis.

### Analysis & Insight

- The call center has 8 agents in total. With Jim having the highest total answered calls 536 and stewart with the lowest at 477.

- From the total of 5000(100%) calls that came in, the agents were able to answered 4054(81%) calls indicating that 946(19%) were abandoned.

- Out of the 4054(81%) calls answered, the agents were able to resolved 3646(73%) of the problem (customer concern) while they were not able to resolve those issues 408(27%) times.

- The agents average speed of answering calls was 54.75 seconds.

- Number of calls per months on January Number of calls answered 1455 and were abandoned calls is 317. February Number of calls answered 1298 and were abandoned calls is 318 and March Number of calls answered 1301 and were abandoned calls is 311.

## Overall Visualization.

<p align="center">
    <img src= 'https://github.com/Jagannathro/PWC_Call_Center/blob/main/PWC.png' height="500"></p>

### Recommendations

- With only 4.5 out of Target Value Satisfaction 2.7 of the customer being satisfied, the call center needs to invest in training the agents and most importantly, organize meetings with the agents to understand (and provide solutions) to the problems they might be facing.

- Out of every 10 calls that came in, the agents abandoned 1, this can be improved on. I will suggest employing 1 or 2 more agent.

- With 27%(408) issues not being able to be resolved, this indicates that the agents need more knowledge about the business / and its different services. I will advise the management to organize a workshop for the agents.
