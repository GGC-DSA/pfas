# PFAS
## Links

[Poster](https://github.com/GGC-DSA/pfas/files/8636794/CREATE.Poster.pdf)


## Abstract 
Our goal was to find trends that will allow us to find PFAS/Teflon in US and GA. It is a manufactured chemical that can cause serious health issues if it enters a person's blood system. Teflon which can contain a chemical of PFAS and can be found on materials like nonstick pan or water repellent clothing. The chemical can never fully go away since it stays wherever it is left whether it is in the air, water, or someone’s body. Our goal is to be able to prevent any harm to people from PFAS at any site and find the offenders causing it.

## Team
Andres Almaraz as Data Analyzer, Visualization, and Project Scribe  
David Luis Hiraldo-Panchana as Data Modeler, Visualization, and Team Manager

## Technology
Python, GitHub, Jupyter Notebook, Tableau, Deepnote, Bootstrap, HTML


## TimeLine 
https://time.graphics/line/618637

## Our intial Data sets 
~~[biologicalresult.xlsx](https://github.com/GGC-DSA/pfas/files/8076303/biologicalresult.xlsx)~~  
~~[narrowresult (1).xlsx](https://github.com/GGC-DSA/pfas/files/8076304/narrowresult.1.xlsx)~~  
[2016_CDR_Industrial_Processing_and_Use_(May_2020).xlsx](https://github.com/GGC-DSA/pfas/files/8076312/2016_CDR_Industrial_Processing_and_Use_.May_2020.xlsx)  
[Water_System_Summary.csv](https://github.com/GGC-DSA/pfas/files/8076308/Water_System_Summary.csv)  
[ucmr-3-occurrence-data.zip](https://github.com/GGC-DSA/pfas/files/8076314/ucmr-3-occurrence-data.zip)  
[PFAS_Blood_Data.zip](https://github.com/GGC-DSA/pfas/files/8608164/PFAS_Blood_Data.zip)

## Notebooks and Collabs will be added here
(https://github.com/GGC-DSA/pfas/files/8263158/Capstone.zip)

## 1 and 2 Hypothesis
Is there is an indicator that can be used in finding PFAS in the water?  
If there is a rise of people contaminated to PFAS across the US

## What was done in Andres' Notebook
First iteration: I have gathered data that shows more locations of water sites that were tested an organization related to the same group from the UCMR data (EPA). I made process in cleaning that data up and comparing the two to see the connections between them to confirm that they match to ensure consistency between the data. I had planned to examine only Georgia to be able to make predictions between the chemicals and factories.
Second iteration: I discovered that Georgia didn't offer enough data with PFAS to be able to sufficiently use. I then focused on the whole United States to get more data. My previous two datasets were too complicated and did not provide clear data to determine if there were chemicals found at the sites. I dropped both at that moment. Made progress in reformatting my data to be able to better test my theory by breaking it down into months from each year.
Third iteration: Broken down the PFAS group of chemicals into separate chemicals for testing. Previously had them together as one assuming they were the same when they are not. Tested linear regression between all possible combinations of PFAS and non-PFAS chemicals.

[Andres Almaraz Notebook.zip](https://github.com/GGC-DSA/pfas/files/8173448/Andres.Almaraz.Notebook.zip)

## 3 and 4 Hypothesis
Is there a relationship between facilities, violations, and populations in Georgia?  
Where did PFAS occur most in Georgia in 2016?

## Final version of David's Notebook
I have hypothesis 3 and 4 with the each of the visualizations, I also supported one of the hypothesis with a clustering method which shows a strong relationship between the items that I was comparing.The next hypothesis focuses on Georgia specifically. The question asked was,Is there a relationship between facilities, violations, and populations in Georgia? Which the conclusion we found was yes There is a relationships between facilities, violations, and populations in Georgia: Lower populations equals more facilities.
Our last hypothesis was asking Where did PFAS occur most in Georgia in 2016? Which we concluded that the two most active pfas cases occurred in dalton and bartow county.

[David Teflon Notebook.zip](https://github.com/GGC-DSA/pfas/files/8172962/David.Teflon.Notebook.zip)

## Algorithm explanation
We had two algorithms that we used being K means clustering and linear regression to see if there was any corrlation between some of the chemical we had. Clustering was mainly used to see if there was a relationship between the two things I was looking at to see if there was a strong relationship.



