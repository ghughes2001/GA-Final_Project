# GA-Final_Project
Summary:

    Have you ever been interested in coffee? I am a big coffee drinker and my final project idea is analying coffee based on certain characteristics like taste and smell. My question is to see if there is any correlation between bags of coffee and the different characteristics. I found some data on Kaggle and want to see how many bags of coffee have the best charcateristics.
    My first file reads in the data (already cleaned) and store it as a new updated table of the data I will use. This will be a new variable in stored as a .csv file. Then, I have anothwr file that uses matplotlib to graph data of the new table. This is where I can see the correleation between how many abgs of coffee have good characteristics. After I complete the previous two files, there will be a final file that runs the machine learning algorithm from sklearn. The first step will be to modify some of the data if I have strings in columns. My goal is to have all numerocal values. Then, I split the data so I can get a more accurate prediction and decrease the chances of over/under-fitting. After splitting the set, I start to run the regression classifier from sklearn for analyzing the data set and graphing the visualization.

Problem Satement:

    My question is to see if there is any correlation between bags of coffee and the different characteristics

Technical Soltion:

    The solution is implemented in python uses libraries like pandas for reading data, numpy for modifying the data, matplotlib to plot the data, train/test split to split the data into training and testing sets, and linear regression from sklearn for fitting data and finding the accuracy of that fit. And finally, I wrote two functions that takes in the dataframe file and reads the data then checks that said file for null values.

 FILES:
 
    FINAL-Reading-Data.ipynb
        - reads in the data and looks through it to see what is in the data and if information is all there. Then, I need to mess with the data. I         will remove some of the unneccesary columns in dataframe. And save the new/updated version as a .csv file.
    FINAL-Analyzing-Data-Part-1.ipynb
        - This file is where I plot using matplotlib.pyplot some of the characteristics of the coffee. Then, I saved and exported them into an img         folder.
    FINAL-Analyzinf-Data-Part-2.ipynb
        - This is the file where I do a linear regression classifier on the data set. I first needed to chnage some of the non-numerical columns           since it's easier to have numerical values when training data. Then, I train/test split the data (y = bags of coffee/x = "Aroma",                "Flavor", "Aftertaste", "Acidity", "Body", "Balance", "Uniformity"). After splitting the data, I should be ready to run   
        the classifier on the data.

CONTACT:
    
    granthughes636@gmail.com

RESOURCE:

https://www.kaggle.com/datasets/volpatto/coffee-quality-database-from-cqi?resource=download&select=merged_data_cleaned.csv
