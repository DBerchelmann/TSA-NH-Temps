<h1> Forecasting Temperatures In New Hampshire Based On Historical Data </h1>

Hi There,

Thank you for visiting my project looking into temperatures of New Hampshire. 








-------------------
<h3><u>The Goal</u></h3>

<font color = blue>**Why are we here?**</font>

* <font color = red>Goal 1:</font> <i>Find the best model to forecast temperatures in New Hampshire using time-series models</i>


-------------------
<h3><u>Where Is Our Data Coming From?</u></h3>

* This data is being pulled from Kaggle.
    * It can be found at the following link. https://www.kaggle.com/berkeleyearth/climate-change-earth-surface-temperature-data
    * When downloaded, you will have a number of .csv files. The one I used was Global Temperatures by State filtered down to New Hampshire, United States.



-------------

<h3><u>Data Dictionary</u></h3>
    
-  Please use this data dictionary as a reference for the variables used within in the data set.



|   Feature      |  Data Type   | Description    |
| :------------- | :----------: | -----------: |
|  dt |  DateTime |Year, Day, Month of temperature recording  |
|average_temperature | float64 | average temperature for that day |
|average_uncertainty | float64 | the 95% confidence interval around the average temperature for the state|
|season_name | object | season based on month the observation was taken |
|month_name | object | name of month observation was taken |





-------------------
 <h3><u>Questions</u></h3>

- Is there an upward or downward trend in temperatures over time?
- Is there a seasonality to temperatures?


--------------------
 <h3><u>How To Recreate This Project</u></h3>
 
 To recreate this project you will need use the following files:
 
.csv from Kaggle as linked and described at the beginning of this README>
 
 Your target variable will be average_temperature which is defined in the above data dictionary. This will be what you will be what you are trying to forecast.
 
 <b>Step 0.</b> Clone this repo to your local machine.
 
 <b>Step 1.</b> Import all necessary libraries to run functions. All functions are located within the notebook and can be copied from there.
 
 <b>Step 2.</b> Use pd.read to bring in the csv file from your local folder. 
 
 <b>Step 3.</b> Clean the data using my prep function and then explore on the split/trained data before going into modeling.
 
<b>Step 4.</b> After you have found a model that works, test that model against out of sample data using the different time-series models.
 
 For a more detailed look, please visit my final notebook for employee classification for further assistance.
 
--------------------



<h3>Key Takeaways, Recommendations, & Next Steps</h3>

Through this classification project I came away with the following <b> key takeaways</b>:

Average temperature has a monthly seasonality too it while an observed warmer trend can be seen at the year progression from 1880 through present day.

<b>Recommendations & next steps</b>:

More data showing high and low temperatures for each day instead of just an average for the month would be even more helpful.

-----
