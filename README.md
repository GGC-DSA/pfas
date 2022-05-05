# PFAS
## PFAS in Ga 
## Description
PFAS (Teflon, etc.) are found not only in pots and pans but also in the blood of people around the world, including 99 percent of Americans. PFAS chemicals pollute water, do not break down, and remain in the environment and people for decades. With that in mind we will be researching the water quality data. We will aiming to find simialrities in the water that had PFAS and those that did not. This will allow us to predict possible water systems that may need to get retested and treated for PFAS.

## Abstract 
The goal of our data analytics capstone project is to see any trends that will allow us to find where pfas/teflon in GA have been and will be. This will allow us to show any future sites that may have pfas in the water system. We are using previously found data to find any correlation to possible sites that may have been overlooked. Our data sets have two primary focus areas those being the actual chemical compound of Teflon and the factories. We will be pooling our data to make an interactive website that will locate any future sites, we can do this by tracking the factories that cause the most pollution, and also revisiting the sites that had a null value for the water containment level.

## Team
Andres Almaraz as Data Analyzer, Visualization, and Project Scribe  
David Luis Hiraldo-Panchana as Data Modeler, Visualization, and Team Manager

## Technology
Python, GitHub, Jupyter Notebook, Tableau, Deepnote, Bootstrap, HTML


## TimeLine 
https://time.graphics/line/618637

## Includes Project Flowchart and our power point presentation
https://docs.google.com/presentation/d/16LAbcNWwkhSBNQBo9aAx8Sn5ISaNQYd0sFxRM8UCxZQ/edit?usp=sharing



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
The hypothesis I came up with and worked on are if there is a correlation between any non-pfas chemicals to pfas~~, see if the dumpings have a connecion from the factories have a effect rise in pfas in the waters,~~ or if there is a rise of people contaminated with too much pfas in there body.

## Current progress
First iteration I have gathered data that shows more locations of watersites that were tested by many an organzation relating to the same group from the UCMR data(EPA). I am in the process of cleaning that data up and comparing the two to see the connections between them to confirm that they match to ensure consistency between the data. I had planned to examine only Georgia to be able to make predicitions between the chemicals and factories.
Second iteration: By this point I had discovered that Georgia didnt offer enough data with pfas to be able to suffiecently use. I then moved to focus on the whole United States to get enough information. I had also discoved that my previous two datasets were too complicated or did not provide with any information to determine if there was anything found in the water. I had decided to drop the both of those then. I also made progress in reformatting my data to be able to better test my theory by restructuring it and breaking it down into months from each year.
Added all my datasets into the notebook. Have been focusing on of them and broke it down to the locations and dates of found chemicals in georgia for each year between 2013-2016. I have also broken down my other sets but am waiting to match up those with teh ucmr data. Soon or later I am hoping to line that up with David's dataset to see if we could find factory dumpings in the same counties for possible correlations.
I moved on to focusing on the US as an whole, and I have broken down my data further down to the months and compared the pfas to the non-pfas chemicals to see a correlation. Then further tested to see each chemical to pfas. Then I moved on see the growth in pfas found in people over the US from 2013-2016.

[Andres Almaraz Notebook.zip](https://github.com/GGC-DSA/pfas/files/8173448/Andres.Almaraz.Notebook.zip)

## 3 and 4 Hypothesis
The two working hypotheses I have so far are, So I was thinking to see the correlation between the number of violations and the number of sites visited within those counties? Another hypothesis can be, Does population affect the number of violations that occurred on site.

## Current Progress of David's Notebook
I added my datasets, and have tried and single out the things needed to test my hypothesis, I have so far singled out a few thigns from a data set that primarily focuses on
the company and where they tested the water, how many people were in that area, how many sites were in that area, and how many of those sites had violations 
on site. With this I was going to test our hypothesis.

[David Teflon Notebook.zip](https://github.com/GGC-DSA/pfas/files/8172962/David.Teflon.Notebook.zip)

## Algorithm explanation
We had two algorithms that we used being K means clustering and linear regression to see if there was any corrlation between some of the chemical we had.



