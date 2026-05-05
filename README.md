# NLP Fashion Trends Extraction

![Python](https://img.shields.io/badge/Python-3.6-blue)
![Scrapy](https://img.shields.io/badge/Scrapy-Web%20Scraping-green)
![Hive](https://img.shields.io/badge/Hive-Big%20Data-orange)
![NLP](https://img.shields.io/badge/NLP-Text%20Classification-purple)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

## Overview
An end-to-end NLP pipeline to extract and classify the latest fashion trends 
from unstructured web data. Built during a Data Science internship at 
GAPRO, Paris, France (Sep–Dec 2017).

## Problem Statement
Fashion trends change rapidly and manually tracking them is time consuming 
and inefficient. This project automates the extraction, processing, and 
classification of trending fashion keywords and categories from web sources 
using a scalable data pipeline.

## Technologies Used
| Technology | Purpose |
|------------|---------|
| Python | Core NLP processing and classification |
| Scrapy | Web scraping fashion data from online sources |
| Apache Hive | Big data querying and processing |
| Shell Scripts | Pipeline automation and orchestration |

## Project Structure

    NLP-Fashion-Trends-Extraction/
    ├── python/          # NLP processing and classification code
    ├── scrapy/          # Web scraping spiders and pipelines
    ├── hive code/       # Hive queries for big data processing
    ├── shell script/    # Automation and orchestration scripts
    └── README.md

## Approach
1. **Data Collection** — Scrapy spiders to scrape fashion trend data from web sources
2. **Data Storage** — Raw data stored and processed using Apache Hive
3. **Text Preprocessing** — Cleaning, tokenisation, and normalisation using Python
4. **Feature Extraction** — NLP techniques to extract meaningful fashion keywords
5. **Classification** — Categorising trends into fashion product categories
6. **Pipeline Automation** — Shell scripts to orchestrate the end-to-end workflow

## Key Outcomes
- Built a scalable, automated end-to-end NLP pipeline for fashion trend extraction
- Enabled automated classification of fashion products from unstructured web data
- Delivered actionable insights for fashion retail strategy at GAPRO, Paris

## About
Built during Data Science Internship at **GAPRO, Paris, France**
September 2017 – December 2017
