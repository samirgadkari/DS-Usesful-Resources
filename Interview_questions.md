### Week 1.1: 

1. What data would you love to acquire if there were no limitations?
2. What would you do with that data (projects, startups, apps)?
3. Bring something for “Show and Tell” (screenshare) that got you interested in this data or shows why it is interesting to you.

### Week 1.2:

1. Why are you at Lambda School?
2. What did you do before Lambda School?
3. What is something interesting about you?

### Week 2:

1. What is the difference between quantitative and qualitative data? What are a few examples of each?
2. What are numpy and pandas and what are they used for?
3. How might you plot time-series data in a clear way? What would be a bad way to visualize it and why?
4. What is data science to you?
5. What is the most confusing topic from week one of class?

### Week 3:
Biases in data visualization

There are numerous types/forms of biases, such as technical, language bias, biased data narrative, replication bias. Good article here: https://alshams.github.io/responsibledata/bias-in-data-viz/
Can you find an example where the chart or other data visualization is misrepresenting the actual research? 
1. How might a visualization appear different to viewers from different cultures?
2. What are apophenia and confirmation bias and how do they affect the creation of visualizations?
3. At what point could a misleading chart become unethical?

### Week 4:
1. What is the difference between descriptive statistics
  and inferential statistics?
2. How would you explain a 95% confidence interval
  to an executive with no statistics background?
3. What is a t-test?
4. What are some different types of distributions
  and what are their qualities?
5. What are null and alternative hypotheses?
  Give an example.
6. When is more data better? When is it worse?
7. How do you keep up with economic and
  business news? How about data science news?
  
### week 11:
1. How are you today?
2. How is object-oriented programming different from functional programming? What are some advantages or disadvantages of each?
3. What is the relationship between modules, packages, dependencies, and namespaces in Python?
4.  What are some differences between Bayesian statistics and frequentist statistics? When might you use one over the other?
5.  How does a confusion matrix help you understand your model better?
6.  What is the alignment problem in artificial intelligence?
7.  We offer great flexibility in our employees’ scheduling? What would your ideal work week look like?

### Week 12:
1. So far in this sprint you've used SQLite, PostgreSQL, and MongoDB. For each of these, consider the following questions:

- What was easy about using this technology?
- What was hard about using this technology?
- What more would you like to learn about it?

Write a summary in the style of a possible blog post, and bring the
questions/discussion to class. Bonus - later on, follow up and complete a real
blog post about different database technologies!

### week 13:

1. What about our company excites you the most? (_assume it is a company in a field you are *NOT* excited about_)
2. What is pipelining and how might you build one in Python?
3. What is the inverse of the squish function?
4. You are on a boat and throw a suitcase overboard. Does the water level increase?
5. What would you do if a teammate changed your work without consulting you first?
6. Whats your current biggest DS-related weakness and what are your plans on it?
7. You don’t have a Phd. or a degree in a requisite field.  Why should we hire you?

### Week 14:

1. What was your biggest achievement in your last job?
2. Do you prefer working in a team or alone? Why?
3. What are two or three specific applications of data science that get you most excited?
4. What are some key differences between Python and Scala?
5. What is a method for determining if statistics published in an article are either wrong or presented to support the author’s point of view?
6. Explain what resampling methods are and why they are useful. What are their limitations?
7. In late 2016, a new recruit at Facebook designed a new feature to improve click-through rates on ads for political ads. They deployed their feature on a representative sample of users from across the country. The feature did not improve rates significantly in the general population, but it DID improve click-throughs for two groups: Female Texan college graduates between the ages of 30 and 35 and Male Floridian high-school graduates between 18 and 25.  The recruit’s manager was reviewing this data and had to decide whether to invest more time into testing/deploying it further.  What is the first question the manager should ask?
8. What would make you quit a job you just started?

### Week 16:

1. Good morning! What do you think of our new offices here?
2. What is the difference between a deep and a shallow copy?
3. What the heck are *args and **kwargs and when are they used?
4. How do data scientists work with backend engineers?
5. Give an example of a time you would use a decision tree?
6. How many golf balls would fit into a Boeing 747?
7. What was the most difficult task you’ve faced in your last job and how did you overcome it?
8. If your manager asked you to do some task with data that you believed was unethical, how would you respond?

### Week 17:
1. What do you want to do by joining this position?
  - Make a good impact to the company bottom line
  - Grow myself in my technical role
2. What are the ML concepts covered at Lambda School?
  - Statistics: Descriptive, Predictive
  - Data Wrangling:
    - Handle Null values
    - Encode category variables
    - Noramalize numerical data
    - Split data into test/validate/train sets
  - Visualizations using libraries, and Storytelling:
    - Matplotlib
    - Seaborn
  - Machine Learning: 
    - Linear/Logistic Regression
    - Decision Trees
    - Random Forests
    - Gradient Boosting (XGBoost)
    - Ridge Regression
    - Survival Analysis
    - Quantile Regression
    - Model Validation
    - Hyperparameter optimization
  - Data Engineering
    - Python Modules, Packages, Environments: pipenv
    - Containers and reproducible builds: Docker
    - SQL: PostgreSQL
    - MongoDB
    - AWS: Sagemaker notebooks, Numba, Dask
    - Scala and Spark
  - Web application development with Flask
  - Natural Language Processing
    - Bag of words
    - Document classification
    - Word embeddings
  - Neural Networks
    - Backpropagation
    - Keras
    - Hyperparameter tuning and Model Evaluation
    - Deep Learning
3. What is a lambda function in Python?
  - The Lambda function is a short bit of code that is unnamed.
  - These functions are also called anonymous fun
  - They're used only within a code block. Reuse is not the point here.
  - Usually used for specific small computations.
4. What is ROC AUC?
  - ROC AUC stands for "Receiver Operator Characteristic Area Under Curve" score.
  - It is used to compare the True Positive Rate versus the False Positive Rate of a binary classifier.
  - A classifier that gives random predictions will give an ROC AUC score of 0.5
  - The best classifier will give a score of 1.0
5. What are sampling techniques and which ones have you used?
  - Sampling is used to:
    - Decrease the number of computations you need to do, so you can try different models in a short period of time.
      - Here you can use the Pnadas Dataframe sample() function to sample a fraction of the data.
    - To balance imbalanced classes
      - imbalanced-learn library is useful here. You can use SMOTE/ADASYN
    - Create train-validate-test datasets
      - Use function train_test_split()
6. Why is Python interpreted?
  - An interpreted language allows for quick test-changecode-test loops. This is very important for machine learning. The compile step is not needed, thus we don't need to test-changecode-compile-test. This saves one step from each iteration.
  - Compiled languages usually need your help to tell the compiler what type a variable is.  This is not needed for interpreted languages
7. What are the disadvantages of an interpreted language?
  - Since there is an interpreter that will always need to run before running the code, it is slower than compiled languages.
  - Some languages may allow improper computations that will get you into trouble without giving any error. This becomes a big problem because most of your time then is spent in debugging.
