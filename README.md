# NLTK-Tutorial
NLTK tutorial for Tucson Python Meetup &amp; Tech Talk

iSpace Tech Talk slides:
https://docs.google.com/presentation/d/1A6_mwdm_Z81sBWSCaqLVUBaHylzTrd2KBaKQPV1o5oM/edit?usp=sharing

Tucson Python Meetup slides:
https://docs.google.com/presentation/d/1vHzt69TFYMV86cDGyi7kBlkpYcgmu6rRdqMuh90Lxfw/edit?usp=sharing

Tucson Python Meetup:
http://www.meetup.com/Tucson-Python-Meetup/events/234583718/


## Quick Start

### Step 1. Clone repository, and install requirements into a virtual environment

```bash
cd ~/Desktop
git clone https://github.com/hclent/NLTK-Tutorial.git
cd NLTK-Tutorial
sudo pip3 install virtualenv
virtualenv -p python3 env
source env/bin/activate
pip install -r requirements.txt
```

### Step 2. Install NLTK corpora used in this tutorial

```bash
ipython
```

```python
import nltk
nltk.download('brown')
nltk.download('punkt')
nltk.download('averaged_perceptron_tagger')
nltk.download('stopwords')
nltk.download('wordnet')
nltk.download('movie_reviews')
nltk.download('inaugural')
nltk.download('gutenberg')
nltk.download('webtext')
nltk.download('udhr')
nltk.download('reuters')
exit()
```

### Step 3. Start Jupyter Notebook

```bash
jupyter notebook
```
