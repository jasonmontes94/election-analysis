# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes to cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner, of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.10.6, Visual Studio Code, 1.70.2

## Summary
The analysis of the election show that:

- There were 369,711 votes cast in the election.

![ElectionResults](/Resources/ElectionResults.png)

- The candiates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
  
- The Candidate results were:
  - Charles Casper Stockham received 23.0% of the vote.
  - Diana DeGette received 72.8% of the vote.
  - Raymon Anthony Doane received 3.1% of the vote.

![CandidateVotes.png](/Resources/CandidateVotes.png)

- the winner of the election was:
  - Diana Degette, who received 72.8% of the vote with 272,892 votes!

## Challenge Overiew
The python code we had written adequately showed detailed information that not only determined the outcome of the election, but provided voting statistics for each candidate as well as each county that participated in the vote as seen below.

![CountyVotes.png](/Resources/CountyVotes.png)

Here is the code that allowed us to tally each counties vote when a new county name was introduced in the county list:

![CountyVoteCode.ong](/Resources/CountyVotes.png)

## Challenge Summary
However, this script also provides room in which we can modify the code to include information on how exactly each county voted. For example, we could see the percentage of the vote for each candidate within each county by including a For loop that goes through each row and records which county AND candidate each vote was cast for.

Another way we can modify the script is to include which candidate had the most votes in each county with and If statement. This could show how each county would tend to vote for future elections.
