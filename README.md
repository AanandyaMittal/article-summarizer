# Final Project: Article Summarizer

Complete the tasks in the Python Notebook in this repository.
Make sure to add and push the pkl or text file of your scraped html (this is specified in the notebook)

## Rubric

* (Question 1) Article html stored in separate file that is committed and pushed: 1 pt
* (Question 2) Polarity score printed with an appropriate label: 1 pt
* (Question 2) Number of sentences printed: 1 pt
* (Question 3) Correct (or equivalent in the case of multiple tokens with same frequency) tokens printed: 1 pt
* (Question 4) Correct (or equivalent in the case of multiple lemmas with same frequency) lemmas printed: 1 pt
* (Question 5) Histogram shown with appropriate labelling: 1 pt
* (Question 6) Histogram shown with appropriate labelling: 1 pt
* (Question 7) Cutoff score seems appropriate given histograms: 2 pts (1/score)
* (Question 8) Summary contains a shortened version of the article (less than half the number of sentences): 1 pt
* (Question 8) Summary sentences are in the same order as they appeared in the original article: 1 pt
* (Question 9) Polarity score printed with an appropriate label: 1 pt
* (Question 9) Number of sentences printed: 1 pt
* (Question 10) Summary contains a shortened version of the article (less than half the number of sentences): 1 pt
* (Question 10) Summary sentences are in the same order as they appeared in the original article: 1 pt
* (Question 11) Polarity score printed with an appropriate label: 1 pt
* (Question 11) Number of sentences printed: 1 pt
* (Question 12) Thoughtful answer based on reported polarity scores: 1 pt
* (Question 13) Thoughtful answer based on summaries: 1 pt

# article-summarizer
This project is used to apply web mining and NLP skills in a project

## How to Install and Run the Project

```shell
cd C:\Users\AanandyaMittal\Documents\
git clone https://github.com/AanandyaMittal/article-summarizer
```

## Virtual Environment Instructions for Creation and Activation

On Windows, create a project virtual environment in the .venv folder. 

```shell
py -m venv .venv
.venv\Scripts\Activate
```

## Install Requests

```shell
py -m pip install requests
```

## Freeze Requirements Instructions

```shell
py -m pip install -r requirements.txt
py -m pip freeze > requirements.txt
```


## Git Commands for Adding, Committing, and Pushing

```shell
git add .
git commit -m "insert commit"
git push -u origin main
```

## Install Jupyter and libraries

```shell
py -m pip install jupyterlab numpy pandas matplotlib seaborn
python -m pip install beautifulsoup4
python -m pip install html5lib
python -m pip install requests
python -m pip install spacy
python -m pip install spacytextblob
```
## To html

```shell
!jupyter nbconvert --to html web-scraping.ipynb
```
