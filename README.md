# Election_Analysis
## Overview of Election Audit
### Background

Client has asked for an analysis of election results that will inform the audit conducted by the Colorado Board of Elections. 

### Purpose

To create a Python script with election results.

## Election-Audit Results

- **Number of votes cast in this congressional election**

There was a total of 369,711 votes cast. 

- **Breakdown of the number of votes and the percentage of total votes for each county in the precinct**

County | Percent of votes | Total votes
------------ | -------------| -------------
Jefferson | 10.5% | 38,855
Denver | 82.8% | 306,055
Arapahoe | 6.7% | 24,801

The county name was extracted using the script shown in Image 1.

**Image 1. County Names**

![Extract_county_row](https://user-images.githubusercontent.com/78306719/110469948-e2e8e000-809f-11eb-8f08-3608d77cc611.PNG)

- **The county that had the largest number of votes**

Denver had the largest number of votes with an 82.8% and 306,055 total votes.

- **Breakdown of the number of votes and the percentage of the total votes each candidate received**

Candidate | Percent of votes | Total votes
------------ | -------------| -------------
Charles Casper Stockham | 23.0% | 85,213
Diana DeGette | 73.8% | 272,892
Raymon Anthony Doane | 3.1% | 11,606

The breakdown of the county votes and percentages was calculated using the scripts in Image 2 and Image 3.

**Image 2. Votes and Percentages**

![Loop](https://user-images.githubusercontent.com/78306719/110470677-c13c2880-80a0-11eb-9258-2351e8b0fbc0.PNG)

**Image 3. County Votes and Percentages**

![If_statement](https://user-images.githubusercontent.com/78306719/110470947-1c6e1b00-80a1-11eb-91d4-a191b1de633a.PNG)

- **Candidate who won the election**

Diana DeGette was the the winner of the election based on popular votes with a winning percentage of 73.8% and 272,892 votes.

## Election-Audit Summary

The Python script created for this election audit can be used for any election as long as the data in available. The script contains blank lists and dictionaries as well as statements allowing analyzation of other elections (See Image 4). The script can be modified to audit the votes and percentages of law proposals at the state or local level. The script can also be modified to audit votes and percentages for governor elections or state representatives.

**Image 4. Blank Lists and Dictionaries**

![blank_dictionaries_lists](https://user-images.githubusercontent.com/78306719/110469749-a4532580-809f-11eb-9cb4-289afe24e0fc.PNG)
