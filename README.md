# NLP Analysis of UN Climate Change-Reports
This project utilizes Natural Language Processing (NLP) techniques to analyze vast amounts of textual data within UN Climate Change Reports. By applying NLP, the project aims to extract valuable insights that can shed light on critical aspects of climate change.

## 1. Data Extraction:

* Web scraping with [Beautifulsoup](https://beautiful-soup-4.readthedocs.io/en/latest/) used to extract data from the [IPCC website](https://www.ipcc.ch/report/ar6/wg2/)

2. Data Transformation:

* PDF files containing climate change reports are converted to text format.
* Text data is cleaned and pre-processed for NLP analysis.

## 3. NLP Analysis:

* [SpaCy](https://spacy.io/usage) NLP tools were used to analyze the text data, including:
    a. Keyword extraction: Identifying key terms and concepts related to climate change.
    b. Topic modeling: Identifying the main topics discussed in the reports.

## 4. Information Visualization:

The results of the NLP analysis are visualized using Worldcloud. This allows users to explore and understand the key findings of the climate change reports.

## 5. Input and Output Program

* The program allows users to input a specific keyword or phrase.
* The program then retrieves all paragraphs from the reports that contain the input keyword or phrase, this allows users to find specific information related to their interests quickly.
