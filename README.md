# Analysis-of-Police-Incidents-in-SF-2017

## Summary
Living in the Bay Area, we love San Francisco, it is a beautiful city. But sometimes we are also concerned about safety issues in the city. I'd like to conduct an analysis and create visualziations to get a good understanding about the crime incidents happened in San Francisco, so we can be more aware. I found the interesting dataset about the police incidents in 2017 on data.sf.org. The main fields that we used are the columns about police incident categories, date and time of the incidents and the police district and location information of the incidents. I mainly used Pandas and Numpy modules to do analysis, and Matplotlib and Seaborn to create visualzations and gain interesting and useful insights.

## Key Visualizations
### 1. How did the daily police incidents change in SF during 2017?
![](Visualization%20Images/Count%20of%20Daily%20Police%20Incidents%20upload%20final.png)

As we can see from the above "heart beat" of daily police incidents in San Francisco during 2017, the count of daily police incidents fluctuated drastically across the year of 2017. The count of daily police incidents was the lowest on Christmas and Thanksgiving holidays.

### 2. How many police incidents happened in each hour of day and day of week for 2017?
![](Visualization%20Images/Heatmap%20of%20Police%20Incidents%20by%20Day%20and%20Hour%20upload.png)

The above heatmap shows that the count of police incidents were highest during 5pm-8pm and 12pm-1pm for all days of week. The count of police incidents on Friday and Saturday nights were also quite high.

### 3. What are the top 10 most common police incident categories in SF during 2017?
![](Visualization%20Images/Top%2010%20Most%20Common%20Police%20Incident%20Categories%20upload.png)

From the top 10 most common police incident categories, we can tell that most of the police incidents in SF were non-violent crimes. The count of "larceny/theft" category was much higher than any other categories.

### 4. Where did the "vehicle theft" incidents happen in San Francisco? 
(I personally am concerned about the vehicle theft incidents as I sometimes drive to SF)

![](Visualization%20Images/SF%20vehicle%20theft%20map.png)
The "vehicle theft" incident map shows that the "vehicle theft" incidents were all over the city, except the major parks in the city. The "vehicle theft" incidents were more concentrated in the business / commercial areas where there are lots of population.

## Dataset
Police Department Incidents - Previous Year (2017)

Incidents derived from SFPD Crime Incident Reporting system
https://data.sfgov.org/Public-Safety/Police-Department-Incidents-Previous-Year-2017-/9v2m-8wqu

## Python Jupyter Notebook in nbviewer
https://nbviewer.jupyter.org/github/andrewhuangca/Analysis-of-Police-Incidents-in-SF-2017/blob/master/Analysis%20of%20SF%20Police%20Incidents%20in%202017.ipynb

