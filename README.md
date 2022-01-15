# pandas-challenge

Repository holds README.md; HeroesOfPymoli.ipynb 

Output Lines: 
    Total Players:print("Total Players: " +str(totplayers))
    Purchasing Analysis (Total): totanalysis_df.head()
    Gender Demographics: gender_df2
    Purchasing Analysis (Gender): gender_df3
    Age Demographics: age_df2
    Purchasing Analysis(age): age_df3
    Top Spenders: sn_df3
    Most Popular Items:pop_df3
    Most Profitable Items: pop_df4
    
    
    3 Observable Trends
Users that are Male and users that are ages 20-24 play more, and therefore spend more. To increase current spending players, game purchases should be marketed towards that range.

Alternatively, to target the age range/ gender that is not playing as much or spending as much, the game and purchases should be marketed towards Females and Other/Nondisclosed and Age groups 30+ and <14 to increase overall players/number of purchases

To increase total purchase values, individual prices could probably be increased from the 3 dollar range to the 4 dollar range. The top 5 profitable items had similar purchase counts to the most popular items, but produced more profit. Within the age range that spends the most (20-24), the average person spends 4.32. All genders report spending over 4 dollars average per person.
    

Notes on code: 
Code is mostly a repition of the following: 
mean, sum, count, nunique for basic statistics 
groupby is used for the different analysis 
bins/cut was used for the age range to split the data into age ranges 
suffixes df1,2,3,4 were used as personal preference to distinguish between lines.