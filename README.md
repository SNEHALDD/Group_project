# Youtube_Comments_Bot_Analysis
# Database Integration
This folder contains the database which we will be using for our analysis. We used the NLP text preprocessing method to clean the Youtube comments in order to make it ready to feed into the machine learning model. We did this by;

Importing in the file which contains the Youtube comments extracted using Youtube API
Removing unnecessary columns, we only kept the columns which contained the comment text and class of 1 or 0. The dataframes which had the class columns is the one that we will be using on our machine learning model as our training data so that machine learns how to categorize the data as bot(1) or human(0).
Removing extra characters such as emojis, urls, puncuations, numbers, trailing spaces, and special charaters
Turning the text into all lowercase letters
Finally, removing all the stop words
After all this, the dataframes are preprocessed to match natural language processing for machine learning.

To connect these databases outside of our local host in PostgreSQL, we used Heroku. We connected our PostgreSQL server to Heroku with the given information on their website. This ensures that our database is not just on a local host, but instead stored on the cloud.

Due to the removal of emojis and special characters from these comments, some rows were left empty but VSCode could not catch that they were null rows. Because of this, we created tables in PostreSQL on our Heroku server, imported the clean dataframe csv files, and deleted the null rows from there. This also ensured that these dataframes were converted and connected to as databases. Later, these databases were exported back as csv files, now without any null rows and ready for machine learning processing.


