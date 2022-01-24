# Election Analysis for a Colorado Congressional District

## Overview of Election Audit
A Colorado Board of Elections employee has sought assitance in writing a scipt to analyze a large dataset of election results from a Congressional District. 

Specifically, we are being asked to complete the following: 
- Calculate total number of votes cast in the election 
- List the Candidates who recieved votes
- Find the total number of votes for each Candidate
- Find the percentage of votes for each Candidate
- Determine the winner by popular votes
- Find each county's voter turnout 
- Calculate the percentage of each county's share of votes from the total votes
- Find the county with the highest voter turnout 

## Election Audit Results
The script we've written produces the following results:

```
Election Results
-------------------------
Total Votes: 369,711
-------------------------

County Votes:
Jefferson: 10.5% (38,855)
Denver: 82.8% (306,055)
Arapahoe: 6.7% (24,801)

-------------------------
Largest County Turnout: Denver
-------------------------
Charles Casper Stockham: 23.0% (85,213)
Diana DeGette: 73.8% (272,892)
Raymon Anthony Doane: 3.1% (11,606)
-------------------------
Winner: Diana DeGette
Winning Vote Count: 272,892
Winning Percentage: 73.8%
-------------------------
```
From this output, we can clearly see the answers to the questions we've been tasked with analyzing. A total of 369,711 votes were cast across three counties: Jefferson, Denver, and Arapahoe. We can see that the largest voter turnout was in Denver County with more than 80% of the votes cast there. Diana DeGette has won the lion's share of the votes, and therefore the popular vote, with 73.8% of voters casting their ballots for her. 


## Summary and Recommendations
Context is always an important part of interpreting data. With over 80% of the total votes, it's clear to see that Denver County is the largest share of the voter pool in this Congressional district. This isn't suprising, based on the common knowledge that Denver County holds a large metropolitan area - the City of Denver. If this script had returned a higher number of votes from a rural county vs. a highly populated county, more investigation would be warranted. 

This script can be used for more applications than just a single Congressional district's election. With some simple modifications, this can be adapted for elections of any size. For example, an analysis of a federal election might use this code by changing "counties" to "states". Beyond that, this script can be further developed to include additional data. For example, if a dataset includes party affiliation, a few additional parameters can be written in to include that factor in the analysis. The applications of data analytics are far-reaching and as we see here, have many real life applications. 
