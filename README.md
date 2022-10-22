# Overview of Election Audit: 

The Colorado Board of Elections has tasked you with counting votes, providing county turnout and determining the winning candidate. In the results, you will find:

1. List of all counties
2. Votes received per county 
3. Percentage of voter turnout
5. List all the candidates
6. Votes received per candidate
7. Percentage of winning candidate 
8. Largest county turnout and winning candidate

# Election-Audit Results: 

![image](https://user-images.githubusercontent.com/114771735/197340934-c1bb5e46-174e-4e62-a551-187c6266dd12.png)

# Election-Audit Summary:

The vote counting script can be utilized for any election given the Data Source provides at minimum the following criteria: Ballot ID representing vote casted, County and Candidate. 

To successfully run the script on any results file, we can modify the code to reference the corresponding column number for county and candidates. For instance, in the "election_results.csv" file, we have candidate names in the third column (referenced PyPoll_Challenge.py Line 50 as candidate_name = row [2]) and county name in the second column (referenced PyPoll_Challenge.py Line 53 as county_name = row [1]). If future data sources have these criterias in differing columns we would determine the new column and update our code accordingly. 

If data sources have additional information linked to ballot ID, such as gender, race or political party affiliation, we can determine the voter count, percentage and majority of each demographic for that election by iterating the code with new variables. 

## Resources
- Data Source. election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1


