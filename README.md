# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on the popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.9.9, Visual Studio Code

## Summary
The analysis of the election show that:
- There were "369,711" votes cast in the election.
- The candidates were:
    - Charles Casper Stockahm
    - Diana DeGette
    - Raymon Anthony Doane
- The candidate results were:
    - Charles Casper Stockham received "23%" of the vote and "85,213" number of votes.
    - Diana DeGette received "73.8%" of the vote and "272,892" number votes. 
    - Raymon Anthony Doane received "3.1%" of the vote and "11,606" number of votes.
- The winner of the election was:
    - Diana DeGette, who received "73.8%" of the vote and "272,892" number of votes. 
    
## Challenge Overview

## Challenge Summary

### Overview of Election Audit
This audit was conducted to determine the winner of the election of a recent local congressional election in Colorado, as well as stastistics on the votes. 

### Election-Audit Results
- There were a total of 369, 711 votes cast for this election. This result was found by looping through the rows to count the total. 
- ![Vote Count Loop](https://user-images.githubusercontent.com/95246572/149638917-f133361a-be28-4bec-b958-3050f7b01f0e.png)
- This was the breakdown of the number of votes and the percentage of total votes for each county in the precinct.
- ![County Results](https://user-images.githubusercontent.com/95246572/149638973-ff408461-68a2-40b4-9f99-af7f883d0bb7.png)
- This was found by using an if statement within a for loop to determine how many votes each county received. And then using another for loop to calculate the percentage. 
- ![county for loop](https://user-images.githubusercontent.com/95246572/149639095-1c62ceb8-9e6f-47b3-b704-b55c4af7783d.png)
- ![County Calculation](https://user-images.githubusercontent.com/95246572/149639099-fbe872c3-8e6c-40cd-88c2-91c0701349b7.png)



### Election-Audit Summary

