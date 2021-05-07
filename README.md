# Election_Anlysis
[PyPoll_Challenge](PyPoll_Challenge.py)

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local
congressional election.

1. Caculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate th epercentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.8.5, Visual Studio Code

## Summary
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- The candidates were:
    - Charles Casper Stockham
    - Diana Degette
    - Raymon Anthony Doane

- The candidate results were:
    - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
    - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
    - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.

- The winner of the election was:
    - Candidate (Diana DeGette), who received 73.8% of the vote and 272,892 number of votes.

## Challenge Overview
### Overview of Election Audit
- The purpose of this project is to find out which county is the largest based on the csv file. With exercise in Module 3, we have already got the solution for the winner. In addition to this project, we could get the full report for the csv file.

### Election-Audit Results
- How many votes were cast in this congressional election?
    - 369,711

- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
    - Jefferson: 10.5% (38,855) 
    - Denver: 82.8% (306,055) 
    - Arapahoe: 6.7% (24,801) 

- Which county had the largest number of votes?
    - Denver

- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
    - Charles Casper Stockham: 23.0% (85,213)
    - Diana DeGette: 73.8% (272,892)
    - Raymon Anthony Doane: 3.1% (11,606)
- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
    - Diana DeGette won the election, her vote count was 272,892, her percentage of the total votes was 73.8%

- Terminal Results 

![Terminal_Resuluts](/Resources/Terminal_Result.png)

- Text Results

![Text_Resuluts](/Resources/Text_Result.png)

## Challenge Summary
### Election-Audit Summary
- According to the results, we found the county, Denver, accounted for the most of the votes, around 82.8%. In this three county, we should figure it out the reason, that might be 
        1. The population of the county
        2. Number of valid votes and invalid votes.
    If it is based on the the populion, we should re-think about votes. We can work on it, by dividing three parts. For example, the population for three cities are 500k, 5 millions, 100k, then we could based on the population to do weight number for votes. 
    If it is based on the second reason, we should think about why there were so many unvalid votes in Charles Casper Stockham and Raymon Anthony Doane.
