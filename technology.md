# Technologies Used

## Data Cleaning and Analysis

### Pandas 
Will be used to clean the data and perform an exploratory analysis.

### Python 
For further analysis.

## Database Storage

### PostGresSQL
Since we are dealing with social media comments, a relational database management system is ideal.
### Heroku
Will use this service to run Postgres in the cloud.
- Increasing our data management agility with Heroku should vastly assist our development process.


## Machine Learning
### SciKitLearn
For document-focused classification, we are using Naive Bayes - MultinomialNB.
 - Has a historical use in spam filtration and document categorization
 - Will look for probability of each class when comments are inputed
### Training and Testing Setup
 - Split data into training and testing sets
 - Use CountVectorizer to describe term frequencies from our comment collections (document-term matrices)
 - Use Naive Bayes to make predictions for testing set
 - Our initial goal is to create a preliminary model with an already-existing dataset, then will use API for actual implementation  

## Dashboard - Considerations 

### Tableau

Its high ease-of-implementation and visually-appealing visualizations make it an excellent candidate for dashboard creation

### Javascript/D3.js

We can use the D3.js library due its high interactability and its ability to easily load and transform data

### Streamlit

An open-source app framework in Python known for its compatibility with scikit-learn and pandas – an alternative to using HTML, CSS, or JavaScript for dashboard deployment.

