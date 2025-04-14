# 🏨 dALrens Hotel Sentiment Analysis
💡 Inspiration
We wanted to support hotel owners in understanding customer feedback efficiently and at scale.

# 🔍 What It Does
This project classifies hotel reviews using Natural Language Processing (NLP) techniques to help hotel owners quickly:

Identify overall sentiment (positive/negative)

Gain high-level insights without reading each review individually

# 🛠️ How We Built It
We used:

NLTK for preprocessing and sentiment-related utilities

Gensim for word embeddings and topic modeling

Python and Jupyter Notebook for building and training the model

Amazon SageMaker for model deployment and training at scale

# ⚠️ Challenges Faced
Memory issues while training large models in constrained environments (e.g., running out of kernel memory)

# 🏆 Accomplishments
Successfully trained an accurate sentiment classification model

Learned to deploy and scale NLP solutions using Amazon SageMaker

# 📚 What We Learned
How to use Amazon SageMaker for NLP tasks

Practical implementation of sentiment analysis and topic modeling

# 🚀 What's Next
Build a full-fledged web application for real-time review classification

Expand capabilities to classify feedback by topic (e.g., food, cleanliness, service, amenities)

# 📁 Files Included
HotelSentimentAnalysis.ipynb: Complete Python code for data preprocessing, sentiment classification, and evaluation

# 🧪 Requirements
Make sure you have the following Python packages installed:

``` bash
nltk
gensim
pandas
numpy
matplotlib
scikit-learn
```

You can install everything in one go:

```bash
pip install nltk gensim pandas numpy matplotlib scikit-learn
```

Also, don’t forget to download necessary NLTK corpora:

```bash
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
```

# 🖥️ How to Run
Clone the repository or download the files manually.

Launch Jupyter Notebook:

```bash
jupyter notebook
Open HotelSentimentAnalysis.ipynb.
```

Run each cell in order to follow the data cleaning, model training, and evaluation steps.
