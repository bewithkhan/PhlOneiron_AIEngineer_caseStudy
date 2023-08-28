
# Candidate-Vacancy Matching Algorithm

## Overview
This repository contains the code for a simple candidate-to-vacancy matching algorithm. The algorithm takes into consideration both the job description and the company's mission statement to find the best match for each vacancy.

## Case Study Objectives
1. **Understand the Data**: Load and examine candidates, companies, and vacancies datasets.
2. **Text Preprocessing**: Apply text preprocessing techniques to make the mission statements and job descriptions suitable for analysis.
3. **Feature Engineering**: Extract features from the preprocessed text using TF-IDF (Term Frequency-Inverse Document Frequency).
4. **Develop Matching Algorithm**: Create an algorithm to match candidates to job vacancies based on the feature vectors.
5. **Consider Constraints**: The algorithm should take into account both the job description and the company's mission statement.

## Prerequisites
- Python 3.x
- Pandas
- scikit-learn

## How to Run
1. Upload the code to a Google Colab notebook or run it in your local Python environment.
2. Replace the placeholders for loading the CSV files (`candidates.csv`, `companies.csv`, `vacancies.csv`) with the actual code to load your data.
3. Run the code to get the top 3 matching candidates for each vacancy.

## Files
- `case_study_matching_algorithm_colab.py`: Contains the main code for the matching algorithm.

## Methodology

### Text Preprocessing
The code applies a simplified text preprocessing method that includes:
- Lowercasing
- Tokenization
- Removal of non-alphanumeric tokens

### Feature Engineering
The TF-IDF technique is used to transform the preprocessed mission statements and job descriptions into feature vectors.

### Matching Algorithm
The algorithm calculates the cosine similarity between each candidate and each vacancy as well as each candidate and each company. It then uses these similarity scores to find the best matches.

## Output
The code outputs a dictionary containing the top 3 candidates for each vacancy based on the cosine similarity scores.

## Author
Muhammad Tufail Khan 
email: m.tufailkhan007@gmail.com 
linkedin: https://www.linkedin.com/in/bewithkhan/
