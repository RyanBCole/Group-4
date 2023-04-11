Welcome to our Project 1 Repository. There were three main questions we attempted to answer in this project about Formula 1 Racing. Those questions are as follows: 

1.	How much does the average pit stop time of a driver 
per race affect their finishing position? 
2.	 How much does the starting grid position of a driver 
affect their finishing position?
3.	 How much does weather affect the average pit stop 
time and average driver finishing position?

To do so, we selected 21 races between the years of 2021 and 2022 to analyze. The races are: 
Bahrain Grand Prix, Emilia Romagna Grand Prix, Portuguese Grand Prix, Spanish Grand Prix, Monaco Grand Prix, Azerbaijan Grand Prix, French Grand Prix, Styrian Grand Prix, Austrian Grand Prix, British Grand Prix, Hungarian Grand Prix, Belgian Grand Prix, Dutch Grand Prix, Italian Grand Prix, Russian Grand Prix, Turkish Grand Prix, United States Grand Prix, Mexico City Grand Prix, SÃo Paulo Grand Prix, Qatar Grand Prix, Saudi Arabian Grand Prix & Abu Dhabi Grand Prix. 
We also selected 21 drivers who competed in all the races listed above. The racers are as follows: 
Lewis Hamilton, Valterri Bottas, Max Verstappen, Sergio Perez, Charles Leclerc, Carlos Sainz, Lance Stroll, Sebastian Vettel, Esteben Ocon, Fernando Alonso, Mick Schumacher, Nikita Mazepin, Yuki Tsunoda, Pierre Gasly, George Russell, Nicholas Latifi, Lando Norris, Daniel Riccardo, Kimi Raikkonen, Antonio Giovinazzi, Kevin Magnussen, Alex Albon & Zhou Guanyu. 


Included in this repository is the Kaggle document we utilized to guide us along our data analysis. The CSV’s we pulled data from are located in the Formula_1_csv folder, the code we created to make our figures, the final analysis PowerPoint, and the written analysis for the entire project.  Our figures and analyses are below.


I.	Question 1
a.	How much does the average pit stop time of a driver per race affect their finishing position?
i.	Our null hypothesis for this question was that the average pit stop time of the driver for a race has no effect on their finishing position for that race. Our     alternative hypothesis was that the faster the average pit stop time of the driver was for a race, the better their result will be for that race. 
1.	For this question, we made two plots that show the average pit stop time for drivers vs their average finishing position throughout a season. For these plots,    we excluded data that included the pit stop times from red flag sessions which is when the race is stopped for an extended period. These results were fascinating    because there is somewhat of a positive correlation between faster average pit stop times and average finishing positions. For our scatter plot showing this          information, the line of best fit had an r-value of 0.1966. This means there is a weaker relationship between the two variables, but it is still noticeable.          However, there were a few drivers who had quicker pit stops, but not the best race results. Because of these results from our plots, we cannot make an accurate      conclusion about either of our hypotheses. Pit stop times likely play a major role for drivers and their finishing position, but it is also more likely that other factors like strategy, aerodynamics, and car performance play just as large of a role in a driver’s race. For future research, we would want to look at more data throughout the seasons, but it is important to note that pit stop crews can change from season to season, so it would be best to compare season by season to make a conclusion. 


<img width="670" alt="real_fig1" src="https://user-images.githubusercontent.com/124079708/231049534-9f9371b4-43ec-467a-9bb7-4d01b817d501.png">
<img width="414" alt="fig1 2" src="https://user-images.githubusercontent.com/124079708/231049754-8485fefd-124b-42b1-8d45-b2fca71f71db.png">


II.	Question 2
a.	How much does the starting grid position of a driver affect their finishing position?
i.	Our null hypothesis for this question was that average grid position for the driver has no effect on their race results in a season. Conversely, our alternative hypothesis was that the better average starting position a driver had in their season, the better race results they had in that season. 
1.	Upon looking at our data and creating various data frames to compare these two factors, we found conclusive results. We began by grouping the drivers for the 2021 season and getting their average starting position and then their average finishing position. From there we created a scatter plot to display this data and plotted a line of best fit. The r-value we obtained from this plot was 0.8522, meaning there was a strong correlation between these two variables. This was clear from the scatter plot too because much of the data stayed near the line of best-fit meaning that the better position they started in the race, the better they finished in races. This trend remained consistent across all 20 positions. The next plot we created was similar to the last one but showed these two variables grouped together by constructors. We wanted to see this data because this shows us data for two of the same cars, but with different drivers in each car. This gives us a better picture of how car performance is crucial for these two factors. Once again, there was a strong positive correlation here as our r-value for this scatter plot was 0.9319. Again, much of the data was consistent through all the positions and the points of data remained near the line of best fit. For this question, we rejected our null hypothesis and accepted our alternative hypothesis. We can conclude that starting a race in a better position will lead to better-finishing results in that race. 

![fig2 1](https://user-images.githubusercontent.com/124079708/231049964-e412eea3-349b-43be-8308-1d04a987c506.png)
![fig2 2](https://user-images.githubusercontent.com/124079708/231049977-8d6cd2f0-4211-4153-908f-87dda967d2e6.png)


III.	Question 3
a.	How much does weather affect the average pit stop time and average driver finishing position?
i.	Our null hypothesis for this question was that weather has no affect on the race result and the drivers with the best car finish better in this race. Our alternative hypothesis was that the driver with the fastest average pit stop times in this race finished better than the driver’s who had slower pit stop times. 
1.	Reviewing the data to this question did not provide much of a clear answer. We began by taking data from the 2021 Emilio Romagna Grand Prix and the 2021 Hungarian Grand Prix. We picked these two races because we believed the results were heavily influenced by the weather on the day of the race, which was a very rainy race. We made two scatter plots, one with the average pit stop time vs the average finishing position for these two races, and another with the average number of pit stops vs the average finishing position. The correlation between these variables across the two plots was weak to nonexistent and it is hard to make a conclusive decision. We think it is fair to say that weather-affected races are incredibly unpredictable, and any driver can win. The factors that influence a winner of a race may be more closely tied to the strategy of the driver, and the overall ability of the driver in the rain. Because of the results we saw in our scatter plots, we can accept our null hypothesis and reject our alternative hypothesis for this question. 

![fig3 1](https://user-images.githubusercontent.com/124079708/231050014-6484951a-5ddd-4c78-b539-7467dd27f8d7.png)
![fig3 2](https://user-images.githubusercontent.com/124079708/231050018-42f0edeb-0e17-47d8-bbbf-ef9ca6533f8a.png)









