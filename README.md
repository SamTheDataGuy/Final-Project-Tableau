# Final-Project-Tableau

## Project/Goals
- Perform exploratory data analysis (EDA) on FIFA 2018 video game player data
- Attempt to discover interesting correlations from the data using visualizations
- Analyze player wages vs player overall score to see how players are overvalued/undervalued

## Process
### Step 1: download, clean, and upload dataset to Tableau
- Downloaded FIFA 2018 player data csv and converted to an excel file
- Created new column to show each players' first preferred position
- Removed stats based on position (columns CAM	CB	CDM	CF	CM	LAM	LB	LCB	LCM	LDM	LF	LM	LS	LW	LWB	RAM	RB	RCB	RCM	RDM	RF	RM	RS	RW	RWB	ST)
- Added cleaned excel file as a data source in Tableau

### Step 2: Create EDA visualizations
- Histograms for age, overall, wage
- Overall vs Average Wage
- Overall vs Ball Control
- Player Count by Nationality
- Average Wage by Nationality

### Step 3: Add visualizations to a dashboard

## Results

### Overall vs Wage
I chose option 2 using the FIFA 2018 player dataset.  

First I created histograms for overall and wage, and noticed that although players overall scores looked normally distributed, wage distribution looked to be on a reverse exponential curve.  This suggests that the relationship between overall score and wages is likely not linear, and there must be other factors affecting a player's wage.  

To look into this further I plotted overall vs average wage and player count.  The results show that players wages increase along with overall score, but the relationship is not linear.  Instead it looks to be exponential, and this is likely due to player availability.  There are many players with an overall score between 40-80, and so in this range as overall scores increase wages increase very slowly.  Once we get into the 80+ overall range, wages increase significantly.

This makes sense from a supply and demand perspective, but from a team management perspective this shows that "middle of the pack" players are undervalued and there are opportunities to gain a competitive advantage while spending less.  Let's imagine there are only two players on a team, and we build a team with a 90 overall player and a 60 overall player.  Their average overall score is 75, but their average wages add up to 287,689 Euros (287,000 + 689).  If we instead build a team with two 85 overall players, their average overall score is significantly higher at 85 and their wages are slightly less at 272,522 Euros (136,261 + 136,261).  By avoiding star players, we can build stronger teams at a lower cost.

### Overall vs Ball Control
Initially I compared overall score vs ball control on a scatter plot and saw that there was a linear relationship, but there was also a large number of players with low ball control scores that still had high overall scores.  Once I coloured the points by position I could see that these were all goal keepers, and this makes sense as being able to stop the ball is much more important for a goal keeper than ball control.  Looking at the rest of the positions it's clear that there is a linear relationship, and it's also evident that ball control has more of an affect on overall score for strikers and midfielders than it does for defenders.  

### Player Counts and Average Wages by Nationality
Plotting player counts and average wages on map charts also yielded some interesting results

(Fill in which Option you chose, either 1 or 2. List the dataset you selected for the project if you selected Option 2. Also, discuss the visualizations you created, and why. For Option 2, also identify what your data question was, and how you went through the prompts.)

## Challenges 
(discuss challenges you faced in the project)

## Future Goals
(what would you do if you had more time?)
