# Python

PROBLEM STATEMENT:
This is a consolidated the data for each of the player sold in the IPL 2022 auction and that of the retained player from each franchise. This data contains information like- matches played, runs, wickets, average, strike rate, catches, runouts, stumps, etc.
Based on these data points try to create the best 11 from these set of players from the current campaign.

we can summarise our analysis in the following steps:
•	Extraction and loading the data.
•	Cleaning the data and removing the noise.
•	Analyze the data on different parameters.
•	Visualizing the important statistical findings.
•	Making the best team of the 11 - based on the ICC WORLD CUP winning squad formation and last year's squad formation of the winning team in the IPL. i.e., how many batters. bowlers and allrounders should be included in the team.


Introduction to IPL auction Data:
	The dataset contains the batters sold in the IPL auction
	The dataset contains keepers and all-rounders sold in the auction
	The dataset contains the bowlers sold in the auction
	The dataset has uncapped players who will play the IPL for the first time

Analyzing the IPL auction data to find Best 11
1.	Gathering the IPL auction data
2.	Clean the data and remove the noise from the data
3.	Analyze the data for useful insights
4.	Analyze the data with useful visual representations
5.	Gather insights from final analysis
6.	Form the best 11 from above analysis

-----------------------------------------------------------------------

In my team I wanted to have 3 Batsmen, 1 Wicketkeeper, 3 allrounders and 4 bowlers which includes 7 Indian players & 4 overseas players
Step-1:
Created a data related to capped batters with Matches Played, Runs, Average & Strike Rate as considering these are the important factors for a batsmen
Step-2:
Created a data related to capped bowlers with Matches Played, Wickets, Bowling average, Economy & Bowling strike rate as considering these are the important factors for a bowler
Step-3:
Similarly for all-rounders & wicket keepers
Step-4:
Replaced all the Nans with zeros
Analysed each player type i.e., Batsman, Bowler, Wicket Keeper & All rounder
For Batsmen
	I considered top batsman as average with 32 and above
	For all these batters calculated Average, Strike rate, Runs & Matches played
	And from the analysis I considered David warner, KL Rahul & Virat Kohli are the top 3 batters
For Bowlers
	I considered top bowlers as bowling average with 24 and below
	For these bowlers calculated Bowling average, Bowling_Strike_Rate, Wickets, Economy& Matches played
	And from the above analysis I considered Bumrah, Rabada, Chahal & Coulter-Nile are the top 4 bowlers
Note: Since in IPL teams only 4 overseas players are allowed, I chose the next best bowler Varun Chakravarthy in place of Coulter-Nile
For Wicket keepers
	I considered top wicket keepers as average with 25 and above
	For these wicket keepers calculated Average, Strike rate, Runs, Matches played, Catches, Run outs & Stumps
	From the above analysis I considered MSD, Pant & De Kock are the top 3 keepers
For all rounders
	I considered top all rounders as strike rate with more than 140 plus
	For these all rounders calculated Average, Strike_Rate, Runs, Matches played, Bowling average, Bowling_Strike_Rate, Wickets & Economy
	From the above analysis I considered Russell, Narine & Hardik Pandya are the top 3 all rounders
Now, the initial analysis that has been done on the segregated data. Create a few visual representations of the same to get better analysis of the data.
Now its time to form the BEST 11 from the above analysis
In my team I wanted to have 3 Batsmen, 1 Wicketkeeper, 3 allrounders and 4 bowlers which includes 7 Indian players & 4 overseas players
Batters: KL Rahul, Virat Kohli, David Warner
All Rounders: Andre Russell, Sunil Narine, Hardik Pandya
Wicket-Keeper: M.S. Dhoni
Bowlers: Yuzvendra Chahal, Jasprit Bumrah, Varun Chakravarthy & Kagiso Rabada
For all the above 11 players I have done analysis using bar blot 


