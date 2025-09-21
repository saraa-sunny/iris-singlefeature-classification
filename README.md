# Project : Iris Single-feature Classification🌸

This project asks: 
### Can a single feature really tell us what species of flower we’re looking at?

## 🔍Why this matters??
Because real-world machine learning isn’t always about building the most complex models. Sometimes it’s about starting simple, but asking what the minimum information needed is to make a decision. This project explores that idea in the classic Iris dataset.


## 📖The Story
The Iris dataset is one of the most famous datasets in machine learning history. Collected by British biologist Ronald Fisher in 1936, it contains measurements of three Iris flower species:
* Iris setosa
* Iris versicolor
* Iris virginica

<img width="1275" height="477" alt="image" src="https://github.com/user-attachments/assets/aaea2925-76ac-4159-8dad-e62a8ea282c5" />


For each flower, we have four features:
* Sepal length
* Sepal width
* Petal length
* Petal width

This dataset is often called the “Hello World” of machine learning because it’s simple, small, and yet surprisingly rich.

## 🎯Goal
This project aims to find out if a single feature from the Iris dataset can be used to accurately classify flower species.

We'll test each of the four features - sepal length, sepal width, petal length, and petal width - individually. 
By building a simple model for each one, we'll see which feature is the most effective at predicting the flower's species. 

## 🛠️Process
* Load the dataset.
* Data preprocessing and EDA
* Split into train/test.
* Pick each feature and train a simple classifier.
* Evaluate the results.


## 📊Results
* Best single feature: Petal width
* Accuracy: 94%
  
  <img width="1053" height="518" alt="image" src="https://github.com/user-attachments/assets/2e6392eb-52c8-499d-9cbf-4aa6d9d596ba" />



## 💡Takeaway
The analysis confirms that a single feature can effectively classify Iris flower species.
Based on our model training and evaluation, the most effective feature was Petal Width, which achieved a classification accuracy of 94%.

## 🔍Next Steps
* Try different simple models, like a Decision Tree, to see if the results are consistent.
* Explore the predictive power of feature combinations (eg: Petal Length + Petal Width)
