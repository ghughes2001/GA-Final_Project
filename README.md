# GA-Final_Project
Summary:

    Have you ever been interested in coffee? I am a big coffee drinker and my final project idea is analying coffee. I found some data on Kaggle and want to see how many bags of coffee have the best charcateristics and the bags origin. My first goal is to read in the data and store it as a variable in it's own file. Then, I am going to read the file using file input/output and use a linear regression classifier from sklearn for analyzing.
    
    A brief summary of your solution to the problem. Make this readable so a person without a technical background could understand how you solvebthe problem! If you can, include why your solution matters. (Brief: somewhere around 4-6 sentences, but this isn't a hard rule.)
 FILES:
 
    FINAL-Reading-Data.ipynb
        - reads in the data and looks through it to see what is in the data and if information is all there. Then, I need to mess with the data. I will remove some of the unneccesary
        columns in dataframe. And save the new/updated version as a .csv file.
    FINAL-Reading-Data.ipynb
        - This is the file where I do a linear regression classifier on the data set. I first needed to chnage some of the non-numerical columns since it's easier to have numerical
        values when training data. Then, I train/test split the data (y = bags of coffee/x = characteristics I want to analyze). After splitting the data, I should be ready to run   
        the classifier on the data.

CONTACT: pending
RESOURCE: https://www.kaggle.com/datasets/volpatto/coffee-quality-database-from-cqi?resource=download&select=merged_data_cleaned.csv
