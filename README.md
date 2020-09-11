# binyo_moses_nlp

# Sentiment Classification for Amazon tweets

Our goal for this project is to apply Natural Language Processing techniques on a collection of tweets centered around Amazon Web Services. In doing so, one would be able to classify the sentiment of such tweets based on linguistic elements in order to gain various business insights such as main competitors, favorable features, and potential employees in the field.

# Data Resource

Data was collected from https://data.world/jacobfacer/twitter/workspace/file?filename=Twitter%2Bdata%2Bin%2Bsheets.xlsx, with very little contextual information provided with the data.

twitter.ipynb is the NLP EDA code
twitterdata.xlsx is the dataset
Untitled.ipynb is the modeling code

## Determine the sentiment of a tweet using nlp methods

Process:
1. Data collection and cleaning
2. Exploratory Data Analysis with descriptive statistics of the reviews
3. Preprocessing and feature engineering
4. Model Fitting
5. Model Evaluation
6. Conclusion

Packages used include:
    
packages for EDA

   - numpy
   - pandas
   - regex
   - string

packages for visualizations

   - matplotlib
   - seaborn

packages for preprocessing and modeling

   - sklearn
   - xgboost
   - nltk
   - gensim
   
# EDA

![sent0](/images/sent0.png)

![sent3](/images/sent3.png)

![sent-3](/images/sent-3.png)

![top20tri](/images/top20trigram.png)

![trigram3](/images/trigramsent3.png)

![trigram-2](/images/trigramsent-2.png)

# Hypothesis Testing

Chi-squared Test

Test 1
- Null Hypothesis: There is no association between whether it is the weekend or not, and tweet sentiment
- Alternative Hypothesis: There is an association between whether it is the weekend or not, and tweet sentiment
pval: 3.430597076590461e-05
Result: Reject the null. There is an association.

Test 2
- Null Hypothesis: There is no association between whether a tweet is retweeted, and tweet sentiment
- Alternative Hypothesis: There is an association between whether a tweet is retweeted, and tweet sentiment
pval: 7.284707252228614e-10
Result: Reject the null. There is an association.

# Models

# Conclusion
