# STA 220 Course Project: Clinical Trial Analysis

## Project Overview
This project focuses on analyzing clinical trial data and associated published research articles. The analysis involves collecting data from ClinicalTrials.gov and PubMed, conducting exploratory data analysis (EDA), and establishing connections between clinical trials and their corresponding published articles. Overall, the project examines inequalities in medical research by comparing five overlooked high-impact diseases (pancreatic cancer, Chagas disease, endometriosis, drug-resistant tuberculosis, and Duchenne muscular dystrophy) with five common diseases(Alzheimer's, breast cancer, influenza, hepatitis, and malaria). 

## Data Source
The data for this project is available at: [https://drive.google.com/drive/folders/1ksGs0jXUU8D_YdZh73o-EXPcKlT98hu-?usp=sharing]

## Project Structure
The project is organized into the following notebooks:

### 1. Data Collection and Preprocessing
**Filename:** `01_data_collection_and_preprocess.ipynb`

**Description:** This notebook handles the initial data acquisition and preparation phases:
- Extracts clinical trial data from ClinicalTrials.gov
- Collects research articles from PubMed
- Preprocesses the collected data for subsequent analysis

### 2. Exploratory Data Analysis - Clinical Trials
**Filename:** `02_eda_clinical_trial.ipynb`

**Description:** This notebook performs exploratory data analysis on the clinical trial dataset, including:
- Statistical summaries of trial characteristics
- Visualization of key metrics and trends
- Analysis of trial designs, populations, and outcomes

### 3. Exploratory Data Analysis - PubMed Articles
**Filename:** `02_eda_pubmed.ipynb`

**Description:** This notebook conducts exploratory data analysis on the PubMed article dataset, examining:
- Publication patterns and trends

### 4. Linking Clinical Trials with Research Articles
**Filename:** `03_linking_trials_with_articles.ipynb`

**Description:** This notebook establishes connections between clinical trials and their associated published articles by:
- Implementing matching algorithms to identify related publications
- Analyzing the relationship between trial characteristics and publication outcomes
- Evaluating the time lag between trial completion and publication

## Instructions for Use
1. Download the dataset from the provided link
2. Execute the notebooks in sequential order
3. Review the generated visualizations and analysis results