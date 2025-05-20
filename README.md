# Gemma_RecSys
A Large Language Model based Recommendation System. 

Significant efforts have been made towards combining traditional, hybrid recommendations with large language models. Recent large language models have demonstrated enhanced reasoning and logical abilities. Hence, it becomes increasingly relevant to investigate their effectiveness in recommendation tasks. So we can produce quality recommendations with just large language models (LLMs) and no additional complex models. In this project, we aim to evaluate light-weight LLM on a recommendation task. This is an explicit feedback based recommendation problem. 

The aim here is to fine-tune the LLM on predicting movie rating for users. 

## Model Used 
Gemma 2B instruction-tuned model ([Gemma Kaggle Model Card](https://www.kaggle.com/models/google/gemma-2/tfLite/gemma2-2b-it-gpu-int8))

## Dataset Used
MovieLens 100k [Link](https://grouplens.org/datasets/movielens/100k/)

## Model Set-up 
To get access to the Gemma model follow the instruction at [Gemma setup](https://ai.google.dev/gemma/docs/setup) and configure your API key. 
The follwing steps need to be performed.
1. Request Gemma Model access on Kaggle.
2. Configure your API key by uploading your Kaggle username and API Key.


