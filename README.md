# Sentiment Analysis
Performed sentiment analysis on restaurant reviews using two different approaches: a traditional machine learning model (Naive Bayes) and a modern deep learning model (BERT). Provided an interactive visualization using Gradio for end-user interpretation.

## Dataset used
Restaurant review dataset (from Kaggle): 1000 records, 2 fields

## Concepts Covered
1. Naïve Bayesian
2. BERT (Bidirectional Encoder Representations from Transformers)
3. Gradio

![Transformers](/transformer.png)

## Implementation Steps
1. Data Pre-processing
2. Naïve Bayesian model for Sentiment Analysis
3. BERT model for Sentiment Analysis
4. Comparison of performance metrics
5. Gradio for Visual representation

## Results
### Naïve Bayesian
![Naive Bayesian Result](/naive_bayesian_result.png)

### BERT
![BERT Result](/bert_result.png)

BERT outperformed Naive Bayes in terms of accuracy and context understanding, especially in handling nuanced language.

### Gradio Visualization
![BERT Result](/gradio.png)

Developed an interactive Gradio app to visualize predictions. First implemented this for the pre-trained sentiment analysis model from Hugging Face (already pre-trained on a general dataset like IMDb). Then, implemented this for the model fine-tuned using our training set.

P.S. I have separately added a pdf file for the BERT implementation (along with an ipynb file) to this repo since the ipynb render was not clean due to interactive elements in it.
