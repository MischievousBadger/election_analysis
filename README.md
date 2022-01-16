# election_analysis

## Overview of Election Audit
We have been tasked by the Colorado Board of Elections to complete an election audit of a recent local congressional election. 

1.  Calculate the total number of votes cast.
2.  Get a complete list of candidates who received votes. 
3.  Get a complete list of counties where votes were recorded.
4.  Calculate the total number of votes recorded in each county.
5.  Calculate the percentage of total votes each county recorded.
6.  Determine the county with the largest voter turnout. 
7.  Calculate the total number of votes each candidate received.
8.  Calculate the percentage of votes each candidate won.
9.  Determine the winner of the election based on popular vote.

## Purpose
The purpose of this project is to perform an election audit analysis of a US Congressional precinct for certification of the election.  It was requested by Board of Elections management to use Python to automate the audit, as if this method is successful, the code that is utilized to run the audit can be used for other election audits across the state including other congressional, Senate and local elections.  Mail-in ballot, punch card and direct recording electronic voting methods are used in the district and  tabulated by the central office.  A vote count report based on this tabulated data will then be used to audit and certify the election. 

## Resources
- Data Source:  election_results.csv
- Software:  Python 3.9.7, Visual Studio Code 1.63.2

## Election-Audit Results
The analysis of the election shows that:

- There were 369,711 votes cast in the election.
- County vote totals:
  - Jefferson county recorded 38,855 votes for 10.5% of the total vote count.
  - Denver county recorded 306,055 votes for 82.8% of the total vote count.
  - Arapahoe county recorded 24,801 votes for 6.7% of the total vote count. 
- County with the largest voter turnout: Denver
- The candidate results were:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 votes.
  - Diana DeGette received 73.8% of the vote and 272,892 votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 votes. 
- The winner of the election was:
  - Diana DeGette who received 73.8% of the vote and 272,892 votes.  
Please see following link to code-generated election results file: https://github.com/MischievousBadger/election_analysis/blob/f0f6856293b3c4ee480e8fcaabf1ca2960e27c60/analysis/election_results.txt

## Election-Audit Summary
Due to its success in automating the audit and analysis of this election, it is proposed to the election commission that this script be used to audit future elections in the state. The script is purposefully written to pull in data using variables that are generic and not specific to any particular district or locality. The script may need modification in certain areas in order to perform correctly for each individual election.  One area that may need to be changed are the dependencies, depending on the format of the data file used (here, a .csv file was used).  
![image](https://user-images.githubusercontent.com/90944163/149644820-a079e36e-f59a-4ce5-84f0-3ac186050b54.png)
Another area of the script that will need modification for each election are the variables which load the files; the paths will need to be changed specific to the location and/or names of the data file to be analyzed, as well as the location and names of the data file to which the results will be written. 
![image](https://user-images.githubusercontent.com/90944163/149644883-9d32b14a-1c43-497b-871e-8ff3ecd77f8f.png)
If a file type other than .csv is used, the code to read the data will need to be changed to the corresponding file format. 
![image](https://user-images.githubusercontent.com/90944163/149644914-20642f23-4f08-4959-b14d-7f3ad69c697d.png)



