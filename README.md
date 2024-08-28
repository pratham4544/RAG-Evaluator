# RAG Evaluations App

[Girl Computer Research](assets/banner.jpeg)

## Overview

This Streamlit app evaluates the performance of a language model using various metrics such as BERT, Vectra, RAGAS, and Phoenix. It takes a CSV file containing questions and ground truths, and a reference PDF file as input.

## Usage

1. Upload a CSV file containing questions and ground truths in the required format.
2. Upload a reference PDF file.
3. Click the "Submit" button to start the evaluation process.
4. View the results of each evaluation metric.

## Requirements

* Streamlit
* Pandas
* src/helper (custom module)

## Functionality

* Upload CSV and PDF files
* Process CSV file to extract questions and ground truths
* Evaluate language model performance using various metrics
* Display results in dataframes

## Metrics

* BERT Evaluation
* Vectra Evaluation
* RAGAS Evaluation
* Phoenix Evaluation (requires OPENAI API key)

## Note

* Please ensure the CSV file contains 'questions' and 'ground_truths' columns.
* The reference PDF file is required for evaluation.
* Phoenix evaluation requires an OPENAI API key.