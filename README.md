# Youtube_Comments_Bot_Analysis

## Overview

Goal and objective:

Steps to achieve:

Final outcome:

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
    - Scikit-learn (version)
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

This [folder]() contains the database which we will be using for our analysis. We used the NLP text preprocessing method to clean the Youtube comments in order to make it ready to feed into the machine learning model. We did this by;
- Importing in the file which contains the Youtube comments extracted using Youtube API
- Removing unnecessary columns, we only kept the columns which contained the comment text and class of 1 or 0. The dataframes which had the class columns is the one that we will be using on our machine learning model as our training data so that machine learns how to categorize the data as bot(1) or human(0).
- Removing extra characters such as emojis, urls, puncuations, numbers, trailing spaces, and special charaters
- Turning the text into all lowercase letters
- Finally, removing all the stop words

After all this, the database is cleaned up and ready to be fed into the machine learning model . 
 
## Contact 
If you want to contact us, you can reach us at

 zaraxkhan - [zxkhan.99@gmail.com](mailto:zxkhan.99@gmail.com)

 macdkw89 - email address

 justint42 - [tapiajustin42@gmail.com](mailto:tapiajustin42@gmail.com)

 SNEHALDD - snehaldesavle3@gmail.com

 

