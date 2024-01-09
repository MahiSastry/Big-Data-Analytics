**Introduction**
The aspect of data generation and increased interest in the sports domain be it player-competitor analysis, betting, 
team strategy has resulted in sport teams and coaches looking for different opportunities to sharpen their game.
In the past, coaches have used data and intuition to a large extent in informing their decisions and communication with their athletes. 
Increased data-driven decisions have shown increased benefits in the athlete’s performance and athlete-coach association. 
The project aims to analyze athlete data and provide actionable insights to both the player and the coach through visualizations and easy-to-understand actionable insights. 

**Working**
  **Research objectives**
  1.To examine the demographic patterns in competitive data:
    Analyze performance by  age,gender and state to identify any   patterns by event or other criteria.
  2.Performance metrics analysis:
    Examine criteria like reaction time, performance by qualification and heat performance
  3.Winner analysis:
    Present descriptive statistics of top 3 performers by event.
  
  
  **Data collection and methodology**
    The source of this analysis comes from the official website of Athletics Federation of India. 
  
  **Data analysis**
    **Introduction to Data Analysis:**
      “38th-National-Junior-Athletics-Championships-2023” from Athletics Federation of India is the dataset based on which the analysis is being done.
    **Data Cleaning and Preprocessing**
      **Conversion of data source format** : the dataset of concern was available in pdf format which was then converted to a csv with the help of a conversion software. Link for the same can be found in the reference section.
      **Loading multiple files to a dictionary** 
      **Renaming the columns** : there are instances where the column name is not recognized and becomes part of the dataset records. The column was then renamed appropriately by identifying the location of the names in the dataset.
      **Dropping null values** : null values were dropped in the excel sheets itself and also the cleaning stage in the main code. 
      **Data cleaning**: string type columns consisted of unnecessary spaces and special characters. Integer columns were formatted as they were decimal values. Conversion of columns to appropriate data types. 
      Standardizing inconsistencies in naming columns or column values.
      **Exploratory Data Analysis**:
        1.describe() and groupby()with the help of formatted tables provided descriptive statistics ( mean, percentiles, min and max) , enabling us to understand the distribution of performance and reaction time by event, state, round(prelims,semis and final). 
        2.Bar graphs were used to visualize the comparison by age and gender to identify any demographic patterns. 
        3.Heat maps were used to under state wise performance.
        4.Dataframes were used to store the winners of each event and thus displayed in appropriate fashion.

	

**Findings and results**: we can create a profile for a new athlete based on the trends we found when it came to age , state, gender and average performance metrics for each event. Note : This statement is made general as each event has it’s specifications and would result in loss if generalization is to be made across all the events in consideration.




