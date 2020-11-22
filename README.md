# Kickstarting with Excel

## Overview of Project

### Purpose
	This analysis was done to find trends in successful and failed kickstarter projects. Launch date and funding goals were the ###focus of the analysis. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
	For the first analysis, the data was filtered in a pivot table to only show projects that fell under the Theater category (Fig.1). Then, the remaining projects were separated by start month, and for each month the number of outcomes (successes, failures, and canceled) for the kickstarters each month were counted. This count is showed visually in Fig.2

![alt text](https://github.com/specialcanadian/kickstarter-analysis/blob/main/ExtraImages/PivotTable.png?raw=true)
Fig.1: Pivot table of kickstarter outcomes sorted by month

![alt text](https://github.com/specialcanadian/kickstarter-analysis/blob/main/Resources/TheaterOutcomesbyLaunchDate.png?raw=true)  
Fig.2: Plot of kickstarter outcomes sorted by month	


### Analysis of Outcomes Based on Goals
	The second analysis shows the outcome of Kickstarter campaigns for the “plays” subcategory, grouped by funding goals (Fig.3). A table was made to count the number of successes, failures, cancelations, and the total number within each funding goal range. These numbers were then used to calculate percentages of the outcomes, and to create plot of outcome based on goal (Fig.4).	

![alt text](https://github.com/specialcanadian/kickstarter-analysis/blob/main/ExtraImages/Chart.png?raw=true)
Fig.3

![alt text](https://github.com/specialcanadian/kickstarter-analysis/blob/main/Resources/Outcome_vs_Goals.png?raw=true)
Fig.4
### Challenges and Difficulties Encountered
	The first challenge I had was getting my data in the pivot table (Fig.1) to be grouped by month. Getting it correct took some research combined with trial and error. 
	Overall, I had some difficulty properly using Excel functions. If you click into the function entry box, anytime you click another cell, that cell gets entered into the function box. This feature of Excel is very helpful, but i often found myself accidently deleting a full COUNTIF function, then having to Ctrl-Z to fix it. Not a major problem, just a minor annoyance.   

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?:
	Two conclusions I can draw are the best and worst month to launch a Kickstarter campaign. From Fig.2, we can see that campaigns started in May tend to be very successful, while December appears to be the worst month to start one. 

- What can you conclude about the Outcomes based on Goals?:
	From Fig.3 and Fig.4, I can conclude that campaigns asking for less than $5000 are most successful. For goals greater than 25000, there are not many campaigns so it is hard to state a definite conclusion about them. 

- What are some limitations of this dataset?:
	The dataset does not say how the Kickstarter was advertised or what the pledge amount rewards are, if there are any. 

- What are some other possible tables and/or graphs that we could create?:
	We could create similar tables as before but this time add in filters to sort by country.
