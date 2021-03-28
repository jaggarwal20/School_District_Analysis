# School_District_Analysis

## Table of Contents
- [1.0 Project Overview](#Project-Overview)
  * 1.1 Purpose
  * 1.2 Resources
- [2.0 Results](#Results)

- [3.0 Summary](#Summary)

<a name="Project-Overview"></a>
## Project Overview
### 1.1 Purpose
The school board sees that academic dishonesty is occurring and want to remove the ninth graders from the list as their grades have been altered.

 1. Replace ninth graders reading and math scores with NaN
 2. Conduct a school district analysis

### 1.2 Resouces
- Data Source: schools_complete.csv and students_complete.csv
- Software: Python 3.6.1, Jupyter Notebook

<a name="Results"></a>
## Results
* Replace ninth graders reading and math scores with NaN. 
  
  ![alt text](Resources/ninth_nan.png)
  
  
* Number and percentage of votes for each county. 
  
  - Jefferson County recieved 38855 votes, which is 10.5% of the total votes. 
  - Denver County received 306055 votes, which is 82.8% of the total votes.
  - Arapahoe County received 24801 votes, which is 6.7% of the total votes. 
  
* Which county had the largest number of votes?
  - Denver
 
* Number and percentage of votes each candidate received. 
  - Charles Casper received 23.0% of the vote and 85,213 number of votes.
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
  
* Determine the winner of the election based on popular vote.

  The winner of the election is Diana DeGette who received 73.8% of the votes and 272,892 number of votes. 

![alt text](Resource/election_analysis.png)

<a name="Summary"></a>
## Summary

This script can be effectively used to calculate votes for every election to count votes more accurately.  The votes are represented not only in a total vote count, but also in a percentage. The percentage allows for easier interpretation of the data and also normalizes the data, which allows for accurate reporting of who the winner is.
This script can be used for any election by adjusting the load file and save file paths. 
![alt text](Resources/Load_Save_File.png)

The variables can also be adjusted to represent the data more accurately. For instance if the votes is on a state level rather than a county level. 

