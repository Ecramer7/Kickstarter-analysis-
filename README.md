# Kickstarter-analysis

## Overview of Project 

#### Louise is a client that is interested in different performance based Kickstarters and how they measure up her favorite play Fever. She is curious to see how the different campaigns performed in terms of the launch date compared to goals and outcomes based on goals. The results below conveying the results of each of these analyses based on a data sheet of worldwide Kickstarters. 

## Analysis and Challenges 

### Analysis and Challenges – Outcomes Based on Launch Date Chart 

#### This analysis was created by using a pivot table to sort the data until it depicted the launch date of theaters and their respective outcomes. Essentially, this graph shows how many successful, failed, and canceled theaters were launched in each month. This data allows Louise to see a potential trend in success rate associated with a certain month. 

#### The Challenges associated with this analysis was sorting the pivot table. When moving the Launch Data category to the columns section of the pivot table analysis, the default showed years. In order to get around this, some of the categories that auto populated needed to be erased for the table to present months. 

### Analysis and Challenges – Outcomes based on Goals Chart 

#### The purpose of this analysis is to use the COUNTIFS() function to count the number of successful, failed and cancelled plays, turn them into percentages compared to the total, and display the results in a line graph. 

#### The challenge with this analysis was making sure that the COUNTIFS() statements were written in a way that were representative of the final goal. When I began, my graph was incorrect because I used the “pledged” column instead of the goal column. It took me while to understand what was wrong, but once I figured it out, the rest was simple. 

## Results 

#### Theater launch dates are the most successful in May band the least successful in October. Theater launch dates get cancelled fairly consistently all year.

#### They highest percentage of successful plays happens when the goal amount is less than $1000 while the most failures happen between $45000 to $49999.

#### The Data is limited in the factors associated with failures. The data only has goal amount, pledge amount, category location and date to work with as factors for success or failure. It would be nice to analyse other in depth factors such as genre or sample preferences as well. 

#### Other graphs that could have been created witht the data are Subcategory Type VS Outcome in specific Countries, Backers count Vs Outcome Or average donation Vs Outcome. 

[Kickstarter_Challenge.xlsx](https://github.com/Ecramer7/Kickstarter-analysis-/files/9398412/Kickstarter_Challenge.xlsx)
![Outcomes Based on Launch Date](https://user-images.githubusercontent.com/111031608/186041521-79d6a7f6-e260-4e36-ac9a-f997a78badc7.png)
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/111031608/186041527-94ec68dc-a21a-4ea4-94a1-580eb2f58f6a.png)
![Theature_Outcomes_vs_Launch](https://user-images.githubusercontent.com/111031608/186041549-ae09d68b-0720-4a43-9820-f1bd6ecbf1d3.png)
