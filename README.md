# A Multi-Class Text Classification Model with Naive Bayes

This project tackles a classic NLP task: using multi-class classification to predict which **scientific field** a research article belongs to based on its title and abstract. We use a Naive Bayes classifier — a fast, interpretable model that estimates the probability a piece of text belongs to each possible class. A key part of the pipeline is an **elegant for loop** that dynamically assigns each article’s label based on six possible domain columns — a flexible and scalable trick that ties the whole model together.

## The Roadmap
- Load and inspect the dataset
- Assign class labels using a loop across domain columns
- Clean and lemmatize the text
- Vectorize with CountVectorizer and n-grams
- Train the model using MultinomialNB
- Make predictions and evaluate the results

## Tools & Libraries Used
- **Jupyter Notebook** — for interactive coding and exploration  
- **Python 3.12.2**
- **pandas** — for data manipulation  
- **nltk** — for text preprocessing and lemmatization  
- **gensim** — for tokenization  
- **scikit-learn** — for vectorization, modeling, and evaluation tools 

## Acknowledgements

This project began with a notebook I was working on in my NLP course, taught by Michele Samorani, 
Associate Professor in the Department of Information Systems and Analytics at the Leavey School of Business at 
Santa Clara University.
