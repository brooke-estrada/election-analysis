# Election-Analysis

## Project Overview
A Colorado Board of Elections employee, Tom, asked us to complete the following tasks to complete the election audit of the recent congressional election.

1. Calculate the total number of votes cast
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidates received.
4. Calculate the perecentage of votes each candidate won.
5. Determine the winnder of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.8.2, Visual Code 1.59.1

## Summary
The analysis of the election shows that:
- There were 369,711 votes cast in the election.
- The candidates were: 
  - Charles Casper Stockham  
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Capser received 23.0% of the vote and 85,213 number of votes.
  - Diana DeGette recieved 73.8% of the vote and 272,892 number of votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
- The winner of the Election was:
  - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.

## Overview of Election Audit: 
A Colorado Board of Elections employee, Tom, asked us to complete the election audit of the recent congressional election.

## Election-Audit Results: 

1. How many votes were cast in this congressional election?
  - There 369,711 votes cast in the election.
2. Which county had the largest number of votes?
    - The candidates were Charles Casper Stockham, Diana DeGette, and Raymon Anthony Doane.
      - Charles Capser received 23.0% of the vote and 85,213 number of votes.
      - Diana DeGette recieved 73.8% of the vote and 272,892 number of votes.
      - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
3. Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
   - Diana DeGette won. She who received 73.8% of the vote and 272,892 number of votes.

## Election-Audit Summary: 
Upon completion of this election audit, we've determined that the script can be used for future given the changes below.
- The file variables to read and write the csv and text files will need to be changed to the future election.
- Some states require the winner of an election to win over 50% of the total votes. In those cases, the if statment for determinng the winning candidate will need to include include an "AND" condition: Candidate received 50% of the total votes. For example the code may look like: 
  `if (votes > winning_count) and (vote_percentage > winning_percentage) and (winning_percentage > "50%"):`
