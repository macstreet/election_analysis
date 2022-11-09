# Written Analysis of the Election Audit

## Overview of Election Audit
The purpose of this election audit was to provide additional information regarding turnout of each of the counties in this district. The information gathered included voter turnout by county, percentage of votes from each county (out of total count), and which county had the highest voter turnout.

## Election-Audit Results
### - How many votes were cast in this congressional election?
According to this dataset, there were 369,711 votes cast in this district.

### - Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
In Jefferson County, there were a total of 38,855 votes, which made up 10.5% of the total votes for the district. Denver County saw a turn out of 306,055 voters, which accounts for 82.8% of total votes. Lastly, Arapahoe County had a total of 24,801 votes, making the smallest percent of votes for the district at 6.7%.


### - Which county had the largest number of votes?
Denver County had the largest turn out of voters, at 306,055 votes and 82.8% of total votes cast for the district. 

### - Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
Charles Casper Stockham received 85,213 votes, equaling 23.0% of the total votes for all candidates. Diana DeGette saw 272,892 votes, making up 73.8% of total votes. Finally, Raymon Anthony Doane received 11,606 votes, which is 3.1% of total votes. 

### - Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
Diana DeGette won the election with a vote count of 272,892 and total vote percentage of 73.8%.

## Election-Audit Summary
This script may be used in the future to run audits on other elections as needed. As long as the dataset is in the same structure as this one, with three columns - "Ballot ID", "County", "Candidate" - this script may only need slight modifying in order to be used for other election audits. 
One consideration for modification is where the dataset file is located. The script on Line 9 will need to be modified to match the file path of where dataset is located so the script can find it. Another consideration for modification is for the text file. A line of code will need to be inserted into this script in order to create a text file if one hasn't already been created. On Line 13, the code "open(file_to_save, "w")" should be inserted in order to create the text file "election_analysis.txt". Also, as with Line 9, be sure you have created a folder called "analysis" created where the text file will be created and saved. 
