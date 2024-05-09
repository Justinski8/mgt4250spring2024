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

https://elonuniversity-my.sharepoint.com/:x:/r/personal/dchristopher_elon_edu/Documents/Dataset.xlsx?d=wbf6685c4de4849468eecba0719961269&csf=1&web=1&e=V63la5

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

#### Visualizations Built From Data
![Image 5-8-24 at 8 38 PM](https://github.com/Justinski8/mgt4250spring2024/assets/158494882/1c5ae3d4-e18a-47b5-9612-1850dc1abfd6)

<img width="584" alt="Screen Shot 2024-05-08 at 8 40 50 PM" src="https://github.com/Justinski8/mgt4250spring2024/assets/158494882/be4837d8-2225-45e9-b350-1a539e52915d">

<img width="289" alt="Screen Shot 2024-05-08 at 8 44 18 PM" src="https://github.com/Justinski8/mgt4250spring2024/assets/158494882/fa8fc42c-3143-4c4f-be27-717f67940d70">


## Discussion and Summary

```python
import pandas as pd
```
