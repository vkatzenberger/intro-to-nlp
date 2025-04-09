# Intro to NLP for AI

This repo contains Jupyter notebooks I worked through while completing the Intro to NLP for AI course by 365 Data Science from [**Lauren Newbould**](https://github.com/l-newbould).

Instead of forking the course repo, I uploaded my own version to track what I learned, from text preprocessing to transformers.

This is basically my learning journey.

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

