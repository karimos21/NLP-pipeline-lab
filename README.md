# Arabic NLP Pipeline

## Overview
This project aims to explore Arabic text scraping from web sources and implementing a comprehensive Natural Language Processing (NLP) pipeline for analysis. The pipeline includes various tasks such as text preprocessing, Part of Speech (POS) tagging, and Named Entity Recognition (NER).

## Features
- Text cleaning (removing special characters, punctuation, etc.)
- Tokenization
- Stop words removal
- Stemming and lemmatization
- Parts-of-speech (POS) tagging:
  - Rule-based approach
  - Machine learning approach using Flair
- Named entity recognition (NER) using Flair's pre-trained model for Arabic


## Setup
1. Clone the repository:  'git clone https://github.com/karimos21/arabic-text-nlp.git'
2. Install the required dependencies:  `pip install -r requirements.txt`


## Project Structure

### Directories
- **nlp_pipline_lab_.ipynb**: Contains code for each step of the project: one for scraping and preprocessing, one for POS tagging, and one for NER tagging.
- **requirements.txt**: Lists the required Python libraries.
- **README.md**: Documentation for the project.

## Getting Started

### Prerequisites
- Python 3
- Install required libraries by running `pip install -r requirements.txt`


### Usage
1. Run the notebook named `nlp_pipline_lab_.ipynb` which works in the following order:
   - Scraping_and_Preprocessing.ipynb
   - POS_Tagging.ipynb
   - NER_Tagging.ipynb


## Acknowledgments
- The project uses libraries like BeautifulSoup, NLTK, Flair, and Stanza for various NLP tasks.
- The Flair NER model for Arabic is provided by [megantosh/flair-arabic-multi-ner](https://huggingface.co/megantosh/flair-arabic-multi-ner).
- Special thanks to [Qalsadi](https://github.com/qalsadi/qalsadi) for the Arabic lemmatization library.
