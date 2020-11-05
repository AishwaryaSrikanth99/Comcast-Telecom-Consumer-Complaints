# Comcast-Telecom-Consumer-Complaints

# DESCRIPTION  
  
Comcast is an American global telecommunication company. The firm has been providing terrible customer service. They continue to fall short despite repeated promises to improve. Only last month (October 2016) the authority fined them a $2.3 million, after receiving over 1000 consumer complaints.
The existing database will serve as a repository of public customer complaints filed against Comcast.
It will help to pin down what is wrong with Comcast's customer service.  
  
# Data Dictionary  
  
Ticket #: Ticket number assigned to each complaint  
Customer Complaint: Description of complaint  
Date: Date of complaint  
Time: Time of complaint  
Received Via: Mode of communication of the complaint  
City: Customer city  
State: Customer state  
Zipcode: Customer zip  
Status: Status of complaint  
Filing on behalf of someone  

# Analysis Task  
  
To perform these tasks, the following Python libraries such as NumPy, SciPy, Pandas, scikit-learn, matplotlib, and BeautifulSoup were used

- Imported data into Python environment.
- Provided the trend chart for the number of complaints at monthly and daily granularity levels.
- Provided a table with the frequency of complaint types.

Analyzed the maximum complaint types i.e., around internet, network issues, or across any other domains.
- Created a new categorical variable with value as Open and Closed. Open & Pending is to be categorized as Open and Closed & Solved is to be categorized as Closed.
- Provided state wise status of complaints in a stacked bar chart. Used the categorized variable from Q3. Provided insights on:  
1. State with maximum complaints  
2. State with highest percentage of unresolved complaints  
3. Provided the percentage of complaints resolved till date, which were received through the Internet and customer care calls.
