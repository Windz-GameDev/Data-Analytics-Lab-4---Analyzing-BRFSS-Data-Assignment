# Data-Analytics-Lab-4---Analyzing-BRFSS-Data-Assignment

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

Intro: 

This is my lab 4 assignment for the CAP4784 Introduction to Data Analytics Class at UNF. Overall, this lab was a very enjoyable challenge and helped me learn to use the NumPy Python library. I hope this project in the future will aid others in their NumPy and Data Analysis journey. If anyone has any questions or concerns, please let me know! I am always eager to learn and assist others.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

Project Description:

In this program, we analyzed BRFSS weight vs. height data from a CSV file. The data has five attributes:
age, current_weight (lbs), weight_a_year_ago (lbs), height (inches), and gender, where gender == 1 represents male
and 2 represents female. We also dived into Data Analysis with NumPy, converting data from a CSV into a NumPy array, and use that NumPy array to calculate things like mean, median, standard deviation, and interquartile range for a column. We also splice, and concatenate two dimensional arrays. 

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

Lab Instructions I followed: 

[CAP4784-Lab4-AnalyzingBRFSSData.pdf](https://github.com/Windz-GameDev/Data-Analytics-Lab-4---Analyzing-BRFSS-Data-Assignment/files/10996538/CAP4784-Lab4-AnalyzingBRFSSData.pdf)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

Running the App:

This repository was created in Google Collab, however works perfectly fine in PyCharm. To run this project on your computer, you will need a Python interpreter, version 3.11 recommended. 

To load the lab into PyCharm, perform the following steps.

  - Download the project as a zip.

    - Press the green code drop down button, then download as zip.
  
  - Extract the folder within to a location of your choosing.

  - Start a PyCharm instance, select File -> Create a New Project -> then navigate to the location where you extracted the folder and select it as the location.

  - Finally select an interpreter, 3.11 recommended, then press create. There is no need to create a welcome script.

  - You will be told the directory is not empty, simply press "create from existing source", then "this window".

  - You now have the project loaded in PyCharm.

You can run the script by navigating to it in the src folder in the PyCharm file explorer, double clicking the .py file, and pressing the run icon on the top right corner of the PyCharm window.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

Known Issues:

None known at the moment, please let me know if you discover anything.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

Testing:

Program was tested and run through both Pycharm and Google Collabs using the CSV included with repo and the Python 3.11 interpreter.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

Input:

Program takes a CSV as input and converts it to a NumPy array to perform data analysis. An example can be seen in the repository root folder.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

Output:

Program displays the data analysis results neatly formatted to the console. It currently does not export to an external file.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

Resources Used:

- https://colab.research.google.com/ // Primary development environment

- https://www.jetbrains.com/pycharm/ // Used for testing and pushing to Github

- https://numpy.org/doc/stable/reference/generated/numpy.genfromtxt.html

- https://numpy.org/doc/stable/reference/generated/numpy.concatenate.html

- http://www.cdc.gov/brfss // Contains a complete description of the survey data (CSV that was used)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
