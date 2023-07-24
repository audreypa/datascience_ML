This project is a Sentiment Analysis of Amazon reviews made during a professional DataScience and ML Certification at Paris Dauphine University.
It receives the best grade of the promotion. The certification lasts 75 hours, with less than one week for the project.
Note that students following this certification are professionals which have a job in parallele.



# Part 1 : Data's structure

This part consisted in  using paralellism with Spark and preprocessing method to split words in order to analyse them and make sql request on a large dataset.

# Part 2 : Machine Learning

The second part implemented differents machine learning method et scoring in order to select the best method regarding the **precision/recall** score.
In fact, I decided to optimize the precision in order to reduce the false positive results. In fact, the database was imbalanced and had much more positive than
negative reviews. I focused my analysis to correctly classify the negative reviews, which seem to be the most important reviews for me (we take
into account the negative reviews in a business to perform changes and improvments of a product).

## Using two differents vectorization method
The goal was to see if a more advanced vectorization technique like TF-IDF gives a better result for the reviews classification

**1) CountVectorizer**

**2) TF-IDFVectorizer**

## Using three classification models

**1) SVM**
**2) Logistic Regression**
**3) Bernouilli**

For each models, I used a pipeline with different n-grams and parameters in order to select the best model.

The last part is a deep learning part, to be improved and not used during the project.
