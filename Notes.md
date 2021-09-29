# What is machine learning?

Machine learning is about learning patterns not rules. For example we have a machine that can do typed arithmetic and we feed it "two plus two". The machine might give us the right answer, but it does not know the rules of arithmetic, it knows a common pattern.

When dealing with machine learning, do not reinvent the wheel. Use the pre-existing tools, examples, and libraries.

## Strategies

1. Just Watch
2. Tinker
3. Build something from the ground up



## The two different angles

- A subset of Artificial Intelligence.
- An extension of data science

# Data Science Ecosystem

1. Start with an interesting question.
2. import the data
3. clean it up
4. understand the data 
5. transform it
6. model it 
7. deploy and maintain the model.

## Takeaways

Data prep is time consuming.

Spending time getting familiar with the data is beneficial. 

Do not lose sight of the original question through development.

Keep your stakeholders in mind.

Deployment and maintenance is a challenge.

## Key questions 
- What are your goals?
    - To understand and trust the data.

- What techniques should you use?
    - Summary of statistics and visualization.

- Which tools should you use.
    -The python data science stack (Numpy, Pandas, Matplotlib)

## Exploratory data analysis

We usually sample the data, then we use probability models to make inferences.

When running into problems, it might be either a problem with the data or with the model itself.

### Summary statistics and vis tools

Summary statistics can only go so far as providing a general feel of the data.

visualization can help a lot!

sometimes statistics is not enough information.


### Techniques and recommendations.

1. Single Var Exploration: Start with a single variables. look at the distribution and chose appropriate summary statistics.
2. Pair-Wise Exploration: Identify a correlation, look at tables and scatter plots. compute linear fits.
3. Multivariate Analysis: If there is more relationships with the data then add variables and make a more complex model
4. Estimation and Hypothesis testing:

- How big is the effect?
- How much will it change when measured again?
- Is it possible that the effect is due to change?

5. Visualization: Good tool to show relationships.


### Examples of EDA 

https://github.com/fau-masters-collected-works-cgarbin/ieee-icmla-2019-data-science-tutorial


# Fundamentals of Machine Learning and Model Thinking

## Textbook Link

https://learning.oreilly.com/library/view/introduction-to-machine/9781449369880/

## Why Machine Learning? 

The difference between hardcoded rules vs learning by example. 

If something changes in the domain of the problem then the code to find the solution changes. 
machine learning tries to get rid of this problem.


## What are problems ML can solve

- Spam.
- Zip Code recognition.
- Detect fraud.

### Unsupervised Learning

Unorganized data hoping to get a pattern out of it called a clustering solution.

Think of a deck of cards and we ask for cluster solution to break down the deck onto their respective colors, or their values, or numbered cards against face cards, or organize by suite, etc.
    
- If we organize by color we would get two clusters: Black and red.
- If we organize by value we would get clusters of Aces, 2s, 3s, etc.
- If we organize by face vs numbered we would get two clusters
- If we organize by suite we would get four clusters. 

### Supervised Learning

Based on input and output. It comes in two types of problems:

- Classification: Predict a label, class, category, or group placement.
- Regression: Predictions with continuous value. 

## Example Questions.

1. A problem ML can solve.

- Classification problems.

2. An example of a problem ML cannot solve.

- Doing anything the first time. Emotional interpretation. Ethics.

3. What is learning in the context of machine learning.

- Pattern recognition.

4. dif between **supervised** and **unsupervised** learning.

- Supervised is training trough giving data and the answer to the problem (labeled data). Unsupervised is training by just feeding it the data.

5. Example of **supervised** learning.

- We want our AI to identify dogs in pictures so we trained it by providing labeled pictures with and without dogs. The AI will learn by example.

6. Example of **unsupervised** learning.

- We want our AI to recognize patterns in our costumer database so we feed it the data and see if it recognizes anything.

7. Diff between **tabular** data and **raw** data.

- Tabular is data is in tables. Raw data is more abstract: Think of machine vision trying to recognize patterns in pictures. Raw and tabular data are just the structures of the data.

8. What is a sample in the context of Data Science and Machine Learning.

- Having enough data of a population to be able to do something with it.

9. What is a feature? What are other names of features?

- Other names are properties, variables, columns, and attributes. Think of the columns of a table, each table is a feature of the data sample 

10. How do we decide which algorithm should we use?     


## More Questions!

1. Validation vs training sets.

- Training is to teach the model. Validation is to make sure the model works. Training

2. What is the diff between K-fold (cross) validation vs holdout validation.

- Hold out splits the data in such a way that is fixed. K-fold rotates trough different blocks of the data. 

3. What is the golden rule for evaluation two machine learning models?

- Do not use the same data to test and to train.

4. Which metrics can be used to evaluate the (prediction) res of a machine learning model?

- Accuracy, precision, specificity, F1, etc. The closer to 1 (100%) is better.

## Practical hints

- Machine learning is all about repetition. Have an idea write the code experiment repeat. Iteration is very important.

- If your dev set and metrics do not point to the right direction. Change them. Do not be afraid to change metric and add data if needed.

- Put time into error analysis. It does not need to be fancy mathematical formulas, eyeballing the results can give you a lot of information about your model. Is there a problem with the data? your model? the labels on the data?

## Recipes for machine learning

### Chollet

1. Def the problem.

2. Chose measure of success.

3. Decide evaluation protocol. 

4. Prep the data.

5. Develop model that does better than baseline.

6. Scale up: Dev a model that over-fits. 

7. Regularize your model, tune your hyperparameters. 

### Geron

1. look at the big picture.

2. Get data.

3. Discover and visualize data. 

4. Select a model to train.

5. Fine tune the model.

6. Present your solution.

7. Launch, monitor, and maintain your system. 

