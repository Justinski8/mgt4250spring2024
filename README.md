# mgt4250spring2024
This is a repo for the course project
Author(s): Justin Ziolkowski (jziolkowski@elon.edu) and Daniel Christopher (dchristopher@elon.edu)

## Project description

### Project Goal
Our overarching goal during this project is to analyze the performance of Major League Baseball’s top 50 highest-earning players when compared to their Wins Above Replacement (WAR) statistic. This offers a fascinating insight into the correlation between financial investment and on-field contribution. We can uncover whether hefty salaries align with higher-level performance or if there are disparities between compensation and actual impact on the game. This will show the efficiency of allocating resources in professional baseball.

* WAR = Wins Above Replacement - A metric that measures a player's value in all facets of the game by deciphering how many more "wins" he's worth over an "average player." EX) an average player would have a WAR of 0.0 *

## Questions of interest
#### Overarching Question
- What is the correlation between the top 50 highest paid MLB players and their on-field performance?

#### Sub Questions
1. How does WAR correlate to annual salary among the top 50 highest paid players?
2. How do teams and their largest contracts on payroll compare to one another?
3. Is a certain position group valued more than others based on the sum of their total contracts?
  
### Importance statement
These questions are *especially* **important** because ...
1. These questions are essential in the landscape of modern baseball because as contracts are becoming more lucrative, we need to understand if they are really worth the money.
2. To build off of this we must next know if certain teams have a proclivity to sign players to longer, wealthier contracts than others. 
3. Lastly, we must know if, in the market for players, a certain type of position has a predisposition to earn more than another.

These three inquiries allow us to view the market for players in a more complete way. 

## Data Description
### Link to Our Data

We created our own since there was nothing downloadable.

[https://elonuniversity-my.sharepoint.com/:x:/r/personal/dchristopher_elon_edu/Documents/Dataset.xlsx?d=wbf6685c4de4849468eecba0719961269&csf=1&web=1&e=V63la5](https://elonuniversity-my.sharepoint.com/:x:/g/personal/dchristopher_elon_edu/EcSFZr9I3kZJjuy6BxmWEmkBrcPOkBV315Njq89ts8Jc2A?e=NLuSLT)

### Columns of the Dataset
- The rows contain the rankings of the top 50 based on the total value of the contract
- The columns contains “Player”, “Position”, “Team”, “Years”, “AAV”, “2023 WAR”

1. Column Descriptions
2. Player - player name
3. Position - player position on the field
4. Team - franchise the player plays for
5. Years - how long a player’s contract is
6. AVV - player’s salary per year
7. 2023 WAR - player’s wins above replacement for the 2023 season


## Interpreting Visualizations
#### Tableau Public Link
https://public.tableau.com/app/profile/justin.ziolkowski/vizzes

#### Image #1 - Scatterplot
##### Answering Question 1
This shows AAV by WAR with players as the detail. It also includes a median for both WAR and for AAV. In our MLB analysis, examining tplayers' performance relative to WAR is vital for gauging resource efficiency. Detailing Average Annual Value (AAV) by WAR, alongside median values, aids in comparing individual player data, revealing the correlation between salary and on-field contribution.

#### Image #2 - Cluster Graph
##### Answering Question 2
This a graph of AAV/years with players as the detail, size as total contract value, clusters to show any potential trends within this, and team labels. This graph, plotting AVV against contract duration with players as details, provides visual insight into contract structures. By sizing markers according to total contract value and clustering to reveal potential trends, it facilitates understanding the relationship between player compensation, contract length, and team dynamics, enhancing project analysis.

#### Image #3 - Bar Chart
##### Answering Question 3
This is a bar chart separating the different positions and comparing the total contract value within each group. We categorized the position groups into outfielders, infielders and starting pitchers. This is beneficial to help conceptualize the topic. This bar chart categorizes players by position, illustrating total contract value within each group. It aids in conceptualizing how player roles relate to financial investment, providing clarity on where resources are allocated across different positions. Understanding these patterns enhances project comprehension by highlighting position-specific trends in contract valuation.



## Discussion and Summary
#### Article Link + Summary
https://bleacherreport.com/articles/10017936-report-mlb-proposes-basing-player-salaries-off-fangraphs-war-instead-of-arbitration

This article states that player arbitration, a three-year segment before a player is allowed free agency, should be determined through WAR rather than a legal arbitration process. The idea behind this is that WAR is such a valuable stat to summarize a player’s worth that it could be used in a mathematical way to determine a player's monetary worth. 


