
#### Project directory:
Project3
|__ code 
|   |__ 01_Webscrapping_Reddit.ipynb
|   |__ 02_ModelBuilding.ipynb   
|__ datasets
|   |__ eatcheap.csv
|   |__ supple.csv
|   |__ test_eatcheap.csv
|   |__ test_supple.csv 
|__ README.md



#### Data science process as follows:
- Define the problem.
- Obtain the data.
- Explore the data.
- Model the data.
- Evaluate the model.
- Answer the problem.



#### With the given sets of data , the following steps are done
- Problem Statements
- Data Import and cleaning
- Model preparation
- Exploratory Data Analysis 
- Modelling & Evaluating
- Conclusion



#### 1) Problem Statements
- A business man in the FF fitness industry wants to expand his business by venturing into new market sector. However, he cannot decide whether to venture into selling supplements or seting up resturants that sells healthy and afforable food. He wants his team to do some market study using post from subreddit since it is the sixth-most-popular website.

Reddit admins sent one big dataset without seperating the subreddit post. Being a data analysts in the FF fitness company, I was assigned to seperate the posts and send to the relevent marketing team for market studies.
    

#### 2) Data Import and cleaning
- Data collection was done by scrapping the subreddit posts. Cleaning was done like checking for null and removing duplicates. Unwanted characters were removed. Texts were also converted to lower case. Stopwords and Lemmatizing are also done


#### 3) Model preparation
- Data set are being split into train and test sets.


#### 4) Exploratory Data Analysis 
- EDA was done like doing wordcloud and looking as those most frequently appear words.


#### 5) Modelling & Evaluating
- 3 models were being buillt. Logistic regression, Naive Bayes and Random Forest. Model Naive Bayes was selected for the final testing using unseen test data set.


#### 6) Conclusion
Based on the result of the unseen test dataset on my model 2 selection, it did not score as good as I expected based on the training set result.So with every 100 posts , there are about 12 posts that my models would not classify correctly. 
I could probably do tuning on the MultinomialNB() hyperparameter to get a better result.


