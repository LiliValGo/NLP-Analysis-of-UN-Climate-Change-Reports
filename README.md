# Web Scraping and NLP for IPCC Climate Reports
This project combines web scraping and Natural Language Processing (NLP) to extract and analyze climate reports from the IPCC. The notebook includes steps to download PDF reports, parse content, and apply NLP techniques to derive insights from the data.

## Project Overview
This repository focuses on:
1. **Web Scraping:** Automated extraction and downloading of multiple PDF reports from the IPCC website.
    
2. **Data Processing:** Conversion and management of large PDF files, including validation and file existence checks.
    
3. **Natural Language Processing (NLP):** Applying NLP to analyze textual content from climate reports, enabling data-driven insights.
   
# Steps and tools

## 1. Data Extraction:

* Web scraping with [Beautifulsoup](https://beautiful-soup-4.readthedocs.io/en/latest/) used to extract data from the [IPCC website](https://www.ipcc.ch/report/ar6/wg2/)

2. Data Transformation:

    - PDF files containing climate change reports are converted to text format.
    
    - Text data is cleaned and pre-processed for NLP analysis.

## 3. NLP Analysis:

* [SpaCy](https://spacy.io/usage) NLP tools were used to analyze the text data, including:
  
    a. Keyword extraction: Identifying key terms and concepts related to climate change.
  
    b. Topic modeling: Identifying the main topics discussed in the reports.

## 4. Information Visualization:

The results of the NLP analysis are visualized using Worldcloud. This allows users to explore and understand the key findings of the climate change reports.

## 5. Input and Output Program

* The program allows users to input a specific keyword or phrase.
* The program then retrieves all paragraphs from the reports that contain the input keyword or phrase, this allows users to find specific information related to their interests quickly.
