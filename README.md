# Election_Analysis

## Project Overview
A Colorado Broad of Elections employee has given you the following task to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code, 1.53.2

## Summary
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The candidate reuslts were:
   - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
   - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
   - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
- The winner of the election was:
   - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes. 
  
## Overview of election audit
Seth and tom submitted the election audit results to the election commission but they requested some additional data to complete the audit.
1. The voter turnout for each county.
2. The percentage of votes from each county.
3. The county with the highest turnout.

## Election-Audit results
Here are the following election outcomes.
- There were 367,711 votes cast in the congressional election.
- Following are the numbers of votes and the percentage of total votes for each county.
   - Jefferson received 10.5% of the vote and 38,855 number of votes.
   - Denver received 82.8% of the vote and 306,055 number of votes.
   - Arapahoe received 6.7% of the vote and 24,801 number of votes. 
- Denver had the largest number of votes. 
- Candidate results:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
- Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.  
  
## Election-Audit Summary
Even though the results above are calculated from the data for 3 counties, the script has been generalized to work for any number of counties. There are minimal changes required for the script to work if it was provided data for other counties.
In the script, the input is provided using the CSV file in this variable:
```
file_to_load = os.path.join("Resources", "election_results.csv")
```
For providing different input data, a different CSV filename instead of *election_results.csv* can be provided. 

However, the CSV file provided must contain data in the format below:
```
Ballot ID,County,Candidate
```

It is also possible to save the results in a different filename in the script instead of *election_analysis.txt* by changing the filename in this line:
```
file_to_save = os.path.join("analysis", "election_analysis.txt")
```
