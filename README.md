🧩 Overview
This project focuses on analyzing customer reviews from an e-commerce platform to understand sentiment trends and product feedback. E-commerce companies often receive thousands of reviews daily, making manual analysis time-consuming and inefficient. I selected Flipkart as the sample e-commerce platform because the dataset contained rich, real-world customer reviews ideal for sentiment analysis.

Using natural language processing (NLP) and machine learning (ML), I developed a sentiment analysis model to classify customer reviews as positive, negative, or neutral. The goal is to automate sentiment interpretation and help businesses make better product or service decisions based on customer feedback.

🎯 Objective
To build an end-to-end sentiment analysis pipeline that:

Cleans and processes customer review data.

Classifies sentiments using supervised machine learning models.

Helps visualize overall customer satisfaction trends.

🗃️ Dataset
Source: Public dataset containing Flipkart product reviews.

Format: CSV file with columns like review, rating, and summary.

⚙️ Technologies Used
Language: Python

Libraries:

Pandas and NumPy – Data handling and preprocessing

NLTK, TextBlob, SpaCy – Text processing and sentiment tagging

Scikit-learn – Model building (Logistic Regression, Naïve Bayes)

Matplotlib, Seaborn, WordCloud – Data visualization

Jupyter Notebook – Development environment

🧪 What I Did
Data Cleaning: Removed punctuation, stopwords, and special characters from the review text.

Exploratory Data Analysis:

Visualized rating distributions.

Created word clouds for positive and negative reviews.

Text Preprocessing:

Tokenization, lemmatization, and polarity scoring using NLTK/TextBlob.

Labeled review sentiments based on polarity.

Model Building:

Used Logistic Regression and Naïve Bayes classifiers to train on labeled sentiment data.

Split data into training and testing sets for model validation.

Model Evaluation:

Evaluated accuracy, precision, recall, and confusion matrix.

Achieved approximately 80% accuracy using Logistic Regression.

Visualization:

Plotted sentiment counts and polarity distribution.

Displayed examples of classified reviews.

✅ Outcome
The final model can accurately classify customer reviews into positive, negative, or neutral categories. This approach allows businesses to:

Monitor customer satisfaction automatically.

Identify product/service issues faster.

Make data-driven improvements based on real user feedback.
