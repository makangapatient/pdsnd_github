# Udacity Git and GitHub project submission

## Date created
Project created on 03-03-2021, and README created on 23-02-2021

## Project Title
Udacity bikeshare project

## Description
The project uses Python to understand U.S. bikeshare data in three cities (chicago, new york city, washington). 
It calculate statistics and build an interactive environment where a user chooses and filter for a dataset to analyze.

This project focuses on pandas and numpy library usage and simple statistics methods to perform a rudimentary analysis on the bikeshare data from three major U.S. cities - Chicago, Washington, and New York City - to display information such as most popular days or most common stations.

## Files used
- Files used in the project: 
- bikeshare.py
- chicago.csv
- new_york_city.csv
- washington.csv

## Softwares needed
- Python 3, NumPy, and Pandas installed using Anaconda
- A text editor, like VS Code, Atom or Notepad++.
- A terminal application (Terminal on Mac and Linux or Cygwin on Windows and Git bash).

## Installation links for softwares
- [Git for windows - for terminal application using Git Bash](https://gitforwindows.org/)
- [Python using Anaconda (latest version for windows)](https://www.anaconda.com/products/individual)
- [Visual Studio Code Editor (for windows)](https://code.visualstudio.com/docs/setup/windows)

## Links for software tutorials:
- [Git - Reference](https://git-scm.com/docs)
- [The Python Tutorial](https://docs.python.org/3/tutorial/index.html)
- [VS Code Documentation](https://code.visualstudio.com/docs)

## Code explained in Detail

  ### How the program works
  The code developed takes in raw input to create an interactive experience in the terminal that answers questions about the dataset. 
  The experience is interactive  because depending on a user's input, the answers to the questions will change! There are four questions that will change the answers:

   - Would you like to see data for Chicago, New York, or Washington?
   - Would you like to filter the data by month, day, or not at all?
   - (If they chose month) Which month - January, February, March, April, May, or June?
   - (If they chose day) Which day - Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, or Sunday?
   
  The answers to the questions above will determine the city and timeframe on which you'll do data analysis. 
  After filtering the dataset, users will see the statistical result of the data, and choose to start again or exit.
  
  ### The Datasets
   Randomly selected data for the first six months of 2017 are provided for all three cities. 
   All three of the data files contain the same core six (6) columns:

   - Start Time (e.g., 2017-01-01 00:07:57)
   - End Time (e.g., 2017-01-01 00:20:53)
   - Trip Duration (in seconds - e.g., 776)
   - Start Station (e.g., Broadway & Barry Ave)
   - End Station (e.g., Sedgwick St & North Ave)
   - User Type (Subscriber or Customer)
   
  The Chicago and New York City files also have the following two columns:

   - Gender
   - Birth Year
  
 ### Statistics Computed
 The code helps user to tell about bike share use in Chicago, New York City and Washington by computing a variety of descriptive statistics. 
 In this project, the code output will provide the following information:

 Popular times of travel (i.e., occurs most often in the start time):

   - most common month
   - most common day of week
   - most common hour of day
   
Popular stations and trip:

   - most common start station
   - most common end station
   
most common trip from start to end (i.e., most frequent combination of start station and end station)
 Trip duration:

  - total travel time
  - average travel time
  
User info:

  - counts of each user type
  - counts of each gender (only available for NYC and Chicago)
  - earliest, most recent, most common year of birth (only available for NYC and Chicago)
  

## Credits
- https://www.kaggle.com/deepak525/us-bike-share-analysis
- https://github.com/synflyn28/udacity-bikeshare/commit/8315b70c16b89ee8934ca2eb178ddd589344b450
- https://github.com/richardkalehoff
 

