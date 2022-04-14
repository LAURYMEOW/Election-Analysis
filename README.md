# Election Analysis
Python programming software

## Overview of Election Audit

The purpose of this analysis is mainly based in an election audit of the tabulated results for US Congressional precinct in Colorado, US. using Python. 
The task consists in reporting the total number of votes cast, the total number of votes for each candidate and the winner of the election based on the popular vote.
Moreover we was make a counties involved analysis for deep the analysis.
If this audit is done successfully with Python, the code will be used to audit other congressional district, senatorial districts and local elections.

### Election-Audit Results:

- How many votes were cast in this congressional election?
The total number of votes registered in this congressional election was 369,711. With the information provided for this audit we cannot conclude if there was a lot or a little turnout, which would be very useful.

- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
Of the total votes, Jefferson obtained 38,855, equivalent to 10.5% of the total, while Denver obtained 306,055 votes, representing 82.8% of those registered, being the county that obtained the largest number of votes, leaving Arapahoe in last place, receiving 6.7% of the votes.

![Election by County](https://github.com/LAURYMEOW/Election_Analysis/blob/main/Results%20Counties.png)

- Which county had the largest number of votes?
It is evident from the graph above that the County with the highest participation was Denver with 82.8% of the total. 
Most likely, this result is related to the fact that this county is the capital and largest city of the state of Colorado.

- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
For its part, in the results obtained it can be seen that of the three candidates who participated in the electoral race, Diana DeGette obtained the vast majority of votes, achieving 73.8% of the list in favor, followed by Charles Casper with a percentage in favor 23% well below first place.
In last place is Raymond Anthony Doane with a support of 3.1%.

![Election by Candidates](https://github.com/LAURYMEOW/Election_Analysis/blob/main/Results%20Candidates.png)

- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
With the above, it can be confirmed that the candidate Diana DeGette was the winner of the Congressional Election with 272,892 votes in favor, that is, more than 50% of the list.

## Election-Audit Summary:

As expected, the results of an election at any level always leads to the handling of a huge list of data to make the corresponding counts and reach the final verdict as soon as possible. A careful and efficient handling of the data will support the results without risk, while a traditional and primitive use of the same can become cumbersome and even generate dubious conclusions.
That is why we have implemented the use of Python software to ensure that the results print the true population decision without the danger of counting errors. 
The script that was developed for this analysis can be used to count other elections regardless of the level where it is applied. In other words, it can be used for local, district, senate or even national elections, it is only necessary to make a moficiation if the addresses from where the data is taken and where the analysis results are going to be stored are different without altering its template.
Below is a summary breakdown of the parts of the code used to give you a more grounded idea of ​​how this script can be reused without much trouble.

![Code 1](https://github.com/LAURYMEOW/Election_Analysis/blob/main/Code%201.png)
![Code 2](https://github.com/LAURYMEOW/Election_Analysis/blob/main/Code%202.png)
![Code 3](https://github.com/LAURYMEOW/Election_Analysis/blob/main/Code%203.png)

We finally obtained something like:

![Election results](https://github.com/LAURYMEOW/Election_Analysis/blob/main/Election%20Results.png)

We can conclude that the code is flexible enough to be used in any type of election as well as it can be said that it represents an efficient vote counting procedure.
