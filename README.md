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
    - Charles Casper Stockham
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
This audit was conducted to determine the winner of the election of a recent local congressional election in Colorado, as well as stastistics on the votes within each County. 

### Election-Audit Results
- There were a total of 369, 711 votes cast for this election. This result was found by opening the chosen file and looping through the election file to count the total and print the results. 
- ![Load Statement](https://user-images.githubusercontent.com/95246572/149640162-39012a1e-6341-4f4c-8730-806737386664.png)
- ![County Results](https://user-images.githubusercontent.com/95246572/149638973-ff408461-68a2-40b4-9f99-af7f883d0bb7.png)
- This was found by using an if statement within a for loop to determine how many votes each county received. And then using another for loop to calculate the percentage. The results and breakdown were then printed. 
- ![county for loop](https://user-images.githubusercontent.com/95246572/149639095-1c62ceb8-9e6f-47b3-b704-b55c4af7783d.png)
- ![County Calculation](https://user-images.githubusercontent.com/95246572/149639099-fbe872c3-8e6c-40cd-88c2-91c0701349b7.png)
- The result of this calculation showed this result: 
- ![County Vote Winner](https://user-images.githubusercontent.com/95246572/149639199-77eba7a0-ded3-4267-88b4-1fe8f8d1b386.png)
- Each candidate received the following votes:
- ![Candidate Summary](https://user-images.githubusercontent.com/95246572/149639298-ff18befb-6f68-4174-ae51-a9fa5de2541f.png)
- The winner of the election was Diana DeGette with 272,892 votes for 73.8% of the total vote. This was discovered using a similar for loop used as above but modified to determine the winner.
- ![Candidate Calculation](https://user-images.githubusercontent.com/95246572/149639390-04d169ef-5d98-4110-8532-783bc58615ab.png)
- The result of this calculation showed this result:
- ![Winner](https://user-images.githubusercontent.com/95246572/149639411-429161b2-f0ef-47c0-b4e3-d5e1eefb7fd6.png)



### Election-Audit Summary
- This code has a good foundation to be modified easily to count vote totals of any election and output the results quickly. Two easy ways to modify this script is to modify the original file to open to the desired csv file of any election result. 
- ![file to load](https://user-images.githubusercontent.com/95246572/149639677-1a2508d6-837c-4e3e-beb4-34c39d87f2a4.png)
- Additionally, you need to adjust the row number to make sure the county names and candidate names are in the correct positions to be read.
- ![Count Row](https://user-images.githubusercontent.com/95246572/149639709-7ac2b13a-42af-4f67-a874-9db144977c40.png)
- Because I am so smart, I believe that this code can be sold and I will be a millionaire if we sell this as a product. 


