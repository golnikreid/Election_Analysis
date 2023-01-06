
# Election_Analysis
## Overview of Election Audit
A Colorado Board of Election employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resource
- Data Source: election_results.csv
- Software: Python 9.7.6, Visual Studio Code 1.38.1

## Election Audit Results
The analysis of the election show that:
- There were 369,711 votes cast in the election
- The counties were:
	- Jefferson
	- Denver
	- Arapahoe
- The county results were:
	- Jefferson received 10.5% of the vote and 38,855 votes
	- Denver received 82.8% of the vote and 306,055 votes
	- Arapahoe received 6.7% of the vote and 24,801 votes
- The county with the largest number of votes was:
	- Denver with 305,055 votes
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received 23% of the vote and 85,213 votes
  - Diana DeGette received 73.8% of the vote and 272,892 votes
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 votes
- The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote and 272,892 votes
  
## Election Audit Summary
  This election analysis script is a powerful and accurate tool that was successfully used for this congressional precinct. With only some modifications this same script could used for just about any election. The script currently tracks the votes for two things: candidates and counties. The code is for these are quite similar and, in order to fit the script to any election, should be converted into its own function that can handle both candidates and counties. Finally, other elections may require tracking other aspects of an election but still require similar information tracking to candidates and counties (votes, vote percentage). The new function should also be made to handle those as well. Secondly, the output will likely need to be done on case by case basis as the verbiage of things like the largest county turnout and winning candidate are quite different. It's unlikely a single function could handle that so modifications to the output will be have to be made based on the election.
