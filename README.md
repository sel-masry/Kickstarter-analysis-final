# Kickstarter-analysis-final
## Overview of Project 
Louise's play was oh so close to reaching their fundrasing goal in such a short amount of time! This near miss piqued her interest into other plays and how they performed. The purpose of this analysis was to help Louise analyze her data set in order to identify how different campaigns fared in relation to their launch dates and funding goals. 

## Analysis and Challenges 
### Analysis
I performed my analysis by filtering out data to visualize outcomes based on the launch date. In her data set, Louise did not have a collum for dates that were easily readble. This was recified by converting the original values by '=(((J2/60)/60)/24)+DATE(1970,1,1)'to craete a date and then utilizing the 'YEAR()' function to extrat the year created from the date. This allowed us to craete a pivot table showing the varyign degrees of campaigns during the year.

### Challenges 
I had great difficulty utilizing the '=CountIF' function for the second deliverable 

## Results 
Launching your theatre campign in late spring or early summer (optimally May) increases your chances of having a successful campaign. The worst month to launch your campiagn is in December 


