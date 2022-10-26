# Youtube_Comments_Bot_Analysis

## Overview

Our goal is to create a machine learning model that will be trained on known, labeled datasets of social media posts classified as spam or not spam, then use the model on real-world data to determine which comments are spam, what percentage of comments are spam, when spam comments are typically posted, and what type of content is posted in spam posts. We will then create a tool for users to input their own link and see the results of the algorithm on their own dataset, as well as a dashboard that shows any statistics or metrics that we have gathered. 

## Contributors: 
1. zaraxkhan 

2. macdkw89

3. justint42

4. SNEHALDD

## Communication:

1. Slack - Created slack channel to share ideas, make decisions and move work forward.

2. Google Drive - Used google drive to keep necessary files and folders in organized manner. We also share next meeting's agenda on this.

3. Zoom - Use zoom to schedule group meeting outside the class.

## Resources

1. Dataset : [UCI Machine Learning Repository: Youtube Spam collection Dataset](https://archive.ics.uci.edu/ml/datasets/YouTube+Spam+Collection)

2. Software : 
    - Python 3.9.12
    - Scikit-learn 1.0
    - Numpy 1.21.5
    - pandas 1.4.2
      
3. Relational Database : PostgresSQL 11.

4. Tools / Software : Tableau public, git, pgAdmin, VS Code.

## Prerequisites

Before you begin, Please ensure you have met the following requirements:

You have installed updated version of Python, VS Code.   

You have PostgresSQL 11 installed. 

You have access to Tableau public. 

## Installation

## Machine Learning Model

## Database Integration

This [folder](https://github.com/SNEHALDD/Youtube_Comments_Bot_Analysis/tree/main/Clean_Data) contains the database which we will be using for our analysis. We used the NLP text preprocessing method to clean the Youtube comments in order to make it ready to feed into the machine learning model. We did this by;
- Importing in the file which contains the Youtube comments extracted using Youtube API
- Removing unnecessary columns, we only kept the columns which contained the comment text and class of 1 or 0. The dataframes which had the class columns is the one that we will be using on our machine learning model as our training data so that machine learns how to categorize the data as bot(1) or human(0).
- Removing extra characters such as emojis, urls, puncuations, numbers, trailing spaces, and special charaters
- Turning the text into all lowercase letters
- Finally, removing all the stop words

After all this, the dataframes are preprocessed to match natural language processing for machine learning. 

Due to the removal of emojis and special characters from these comments, some rows were left empty but VSCode could not catch that they were null rows. Because of this, we created tables in PostreSQL, imported the clean dataframe csv files, and deleted the null rows from there. This also ensured that these dataframes were converted and connected to as databases. Later, these databases were exported back as csv files, now without any null rows and ready for machine learning processing. 

To connect these databases outside of our local host in PostgreSQL, we used Heroku. We connected our PostgreSQL server to Heroku with the given information on their website. This ensures that our database is not just on a local host, but instead stored on the cloud. 
 
## Contact 
If you want to contact us, you can reach us at

 zaraxkhan - [zxkhan.99@gmail.com](mailto:zxkhan.99@gmail.com)

 macdkw89 - macdkw@gmail.com 

 justint42 - [tapiajustin42@gmail.com](mailto:tapiajustin42@gmail.com)

 SNEHALDD - snehaldesavle3@gmail.com

 

