# Intro to NLP for AI

This repo contains Jupyter notebooks I worked through while completing the Intro to NLP for AI course by 365 Data Science from [**Lauren Newbould**](https://github.com/l-newbould).

Instead of forking the course repo, I uploaded my own version to track what I learned, from text preprocessing to transformers.

This is basically my learning journey.

## Files

**Section 2 – Text Preprocessing**

- `2.2_Lowercase.ipynb`  
- `2.3_Stopwords.ipynb`  
- `2.4_Regular_Expressions.ipynb`  
- `2.5_Tokenizing_Text.ipynb`  
- `2.6_Stemming.ipynb`  
- `2.7_Lemmatization.ipynb`  
- `2.8_N-grams.ipynb`  
- `2.9_Practical_Tripadvisor_Reviews.ipynb`  

**Section 3,4 – NLP Techniques**

- `3.2_POS_tagging.ipynb`  
- `3.3_NER.ipynb`  
- `3.4_Practical.ipynb`  
- `4_Sentiment_Analysis`  
- `4.2_Rule_Based_Sentiment.ipynb`  
- `4.3_Pre-trained_Transormer_Models.ipynb`  
- `4.4_Practical_Book_Reviews.ipynb`  

**Section 5 – Vectorization**

- `5.2_Bag_of_Words.ipynb`  
- `5.3_TF-IDF_in_python.ipynb`  

**Section 6 – Topic Modeling**

- `6.4_LDA.ipynb`  
- `6.6_LSA.ipynb`  

**Section 7 – Classification**

- `7.2_Custom_Classifier.ipynb`  

**Section 8 – Final Project**

- `8_Practical_Fake_News.ipynb`



## Learned about

- Practice on datasets (`.csv`, `.txt` files)
- Preprocessing: tokenization, stopwords, stemming, lemmatization, n-grams  
- POS tagging, Named Entity Recognition (NER)  
- Sentiment analysis (rule-based and transformer-based)  
- Bag of Words, TF-IDF  
- Topic modeling: LDA, LSA  
- Custom classifier  

## Environment Setup - based on the course instructions

Created with `conda` + Python 3.11. Key packages:
```bash
nltk==3.9.1
pandas==2.2.3
matplotlib==3.10.0
spacy==3.8.3
textblob==0.18.0.post0
vaderSentiment==3.3.2
transformers==4.47.1
scikit-learn==1.6.0
gensim==4.3.3
seaborn==0.13.2
torch==2.5.1
ipywidgets==8.1.5
```

```bash
conda create --name nlp_course_env python=3.11
conda activate nlp_course_env

pip install nltk==3.9.1 pandas==2.2.3 matplotlib==3.10.0 spacy==3.8.3 textblob==0.18.0.post0 vaderSentiment==3.3.2 transformers==4.47.1 scikit-learn==1.6.0 gensim==4.3.3 seaborn==0.13.2 torch==2.5.1 ipywidgets==8.1.5

python -m spacy download en_core_web_sm
pip install ipykernel jupyterlab notebook

python -m ipykernel install --user --name=nlp_course_env
```

Finally, set the kernel to `nlp_course_env` in Jupyter.

## Credits

Intro to NLP for AI course by 365 Data Science

Instructor: [**Lauren Newbould**](https://github.com/l-newbould)

Course: https://learn.365datascience.com/courses/intro-to-nlp-for-ai/

Original Repo: https://github.com/l-newbould/introtonlp-365

This repo reflects my own notes and learning.

