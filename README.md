
## Overview
This repository contains the code and dataset used for my dissertation titled "Exploring Patient Perspectives on Methotrexate and DMARDs in Rheumatoid Arthritis Treatment: An Advanced Sentiment and Thematic Analysis."


## Dataset
The datasets used in this study are described as follows:
`scraped_data.csv`: The raw data scraped from the RA subreddit
`final2_predictions.csv`: The results from the sentiment prediction task before evaluation
`sampled_data_for_annotation.csv`: The sample data used for the manual annotation process comprising 360 samples
`Duplicate Annotation data.csv`: The manually annotated data that was used to train the model
`new_manual_validation2_sample.csv`: The second sample data with a 100 samples that was manually annotated to compare with some final predictions results

## Code files
- `Web Scraping.ipynb`: Code for scraping the data used for this study from the RA subbredit.
- `Model Initial Training.ipynb`: Code for the initial training and fine-tuning process of the model.
- `Model Evaluation & Sentiment Prediction Task.ipynb`: Code for evaluating the model and for the sentiment analysis prediction task using DistilBERT.
- `Sentiment Prediction Validation.ipynb`: Code for validating the results after the final sentiment prediction task.
- `Thematic Analysis.ipynb`: Code for thematic analysis using NMF and LDA.


