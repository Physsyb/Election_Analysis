# Election_Analysis
  Performing an election analysis "Pypoll" with Python 

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.
 * Calculate the total number of votes cast
 * Get a complete list of candisates who received votes
 * Calculate the total number of votes each candidate received
 * Calculate the percentage of votes each candidate won
 * Determine the winner of the election based on popular votes

## Resources
  * Data Source: `election_results.csv` 
  * Software: Python 3.7.6, Visual Studio Code 1.52.1
  
## Summary
The summary of the election shows that:
* There were *369,711* votes cast in the election
* The candidates were:
   * Charles Casper Stockham
   * Diana DeGette
   * Raymon Anthony Doane
* The candidate results were:
   * Charles Casper Stockham received "*3.0%*" of the vote and "*85,213*" number of votes.
   * Diana DeGette received "*73.8%*" of the vote and "*272,892*" number of votes.
   * Raymon Anthony Doane received "*3.1*%" of the vote and "*11,606*" number of votes.
* The winner of the election was:
   * Diana DeGette who received "*73.8%*" of the vote and "*272,892*" number of votes.
 
 # Challenge Overview
 ## 1) Overview of Election Audit
 > Explain the purpose of this election audit analysis 
   
   The purpose of this challenge is to complete the audit with some additional data requested by the electoral commision. This will be achieved by working from the      module’s `election_results.csv`, use `for` loops and conditional statements with membership and logical operators to find the requested results. Then, print the results to the command line and save them to your `election_results.txt` file. The additional data required are:
   * The voter turnout for each county
   * The percentage if votes from each county out of the total count
   * The county with the highest turnout. 
   
In this project, our final Python script will need to be able to deliver the following information when we `run` the script: 
   * Total number of votes
   * A complete list of candidates who received votes
   * Total number of votes each candidate received
   * Percentage of votes won by each candidate
   * The winner of the election based on popular vote
   * The voter turnout for each county
   * The percentage if votes from each county out of the total count
   * The county with the highest turnout
  
 ## 2) Election-Audit Results
 > Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary.
 * How many votes were cast in this congrssional election?
   * Total Votes cast in this congressional election was 369,711  
![Capture 1_LI](https://user-images.githubusercontent.com/76136277/104855980-e224a080-58dd-11eb-852b-eb711e723caf.jpg)


 * Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
    * Jefferson received "*10.5%*" of the vote and "*38,855*" number of votes.
    * Denver received "*82.8%*" of the vote and "*306,055*" number of votes.
    * Arapahoe received "*6.7%*" of the vote and  "*24,801*" number of votes.    
![Capture 2_LI](https://user-images.githubusercontent.com/76136277/104856105-a8a06500-58de-11eb-9e06-40e9aadb077b.jpg)


 * Which county has the largest number of votes?
    * Denver has the largest number of votes      
![Capture 3_LI](https://user-images.githubusercontent.com/76136277/104856191-219fbc80-58df-11eb-83c3-b0f128eb9375.jpg)


 * Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
    * Charles Casper Stockham received "*3.0%*" of the vote and "*85,213*" number of votes.
    * Diana DeGette received "*73.8%*" of the vote and "*272,892*" number of votes.
    * Raymon Anthony Doane received "*3.1*%" of the vote and "*11,606*" number of votes.     
![Capture 4_LI](https://user-images.githubusercontent.com/76136277/104856433-9fb09300-58e0-11eb-8429-d2aaa320408b.jpg)


 * Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
    * Diana DeGette who received "*73.8%*" of the vote and "*272,892*" number of votes.    
![Capture 5_LI](https://user-images.githubusercontent.com/76136277/104856528-34b38c00-58e1-11eb-81e1-5e38df837330.jpg)


* Overview of the election result

  ![Capture 6](https://user-images.githubusercontent.com/76136277/104857426-7a268800-58e6-11eb-8d68-670687ba6b5f.PNG)

## 3) Election Audit Summary
> There is a statement to the election commission that explores how this script can be used for any election, with two examples for modifying the script.
* If there are elections with more data like age and gendeer, the script can be modified to include these characteristics and the analysis can be broken down even further. The script can be modified to find the most number of votes by age and gender, other than candidates and county.
* This script can also be modified to determine patterns among the characteristics. We could test the percentage of voters by county against each candidate. This would allow us to see which candidate was the most popular within a county or geographical area.
