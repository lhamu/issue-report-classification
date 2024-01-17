# issue-report-classification
Project repository for Machine Learning for Model-driven Engineering course

## Introduction:
The issue report classification project is based on the NLBSE 2024 Issue Report Classification competition. The competition involves building and testing a set of multi-class classification models to classify issue reports as belonging to one category representing the type of information they convey.

## Dataset:
The dataset for this project is from the NLBSE 2024 Issue Report Classification competition. The provided dataset contains 3000 labeled issue reports extracted from 5 real open-source GitHub projects which are as follows:
1. bitcoin/bitcoin
2. facebook/react
3. microsoft/vscode
4. opencv/opencv
5. tensorflow/tensorflow

Each issue report contains the following information:
* repo
* created_at
* label
* title
* body

Each issue report is assigned one out of three possible labels: **bug**, **feature**, and **question**.

## Important folders and files:
* **data**: This folder contains the training and test datasets provided by the NLBSE 2024 Issue Report Classification competition.
* **preprocessed_data**: This folder contains the  training and test datasets prepared after applying the preprocessing steps.
* **data_preprocessing_notebook.ipynb:** This notebook contains all of the code required to perform data exploration, cleaning and preprocessing.
* **simple_ml_for_issue_classification.ipynb:** This notebook contains the code for training with traditional ML approaches: Random Forest and XGBoost. 
* **finetuning_distilbert_for_issue_classification.ipynb:** This notebook contains the code for fine-tuning a DistilBERT language model.
* **sentence_transformer_for_issue_classification.ipynb:** This notebook contains the code for fine-tuning using the Few-shot learning approach on a sentence transformer.
* **output:** The output folder contains all of the JSON output files from the different techniques.
* **sota_results.json:** This JSON file contains the results from the baseline method.

Each of the notebook contains a comparison of the model outputs with the SOTA results. The report for the project is included in the report folder.
