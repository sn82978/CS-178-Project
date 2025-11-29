# CS-178-Project

## Planning Spreadsheet
https://docs.google.com/spreadsheets/d/1cYd9hqx69cYW1G64fG0Rviz9qy-kVvSSSYaAkv2LLVg/edit?gid=0#gid=0

## Goal
Create a model to predict the toxicity of a comment across 5 different levels (toxic, severe-toxic, obscene, identity-hate, and insult)

## Steps

1. Pre-processing Step (Shreya)
    a. Looking at data (making graphs and visualization of features and pred. class)
    b. Vectorizing
        - Two vectorizers chosen: TF-IDF and Count Vectorization
        -> TF-IDF is better, based on Decision Tree results (3.MoreComplex/DecisionTree/dt.ipynb)
2. Baseline Model (Gaurav)
    a. This is a linear classifier/perceptron
    b. There will be two trained on each type of vectorized data
    c. The better performing model's vectorizer will be used for the rest of the more complex model
3. More Complex Models (Julian and Shreya)
    a. We will have three models: 
        - Clustering EM (Shreya) [http://www.kamalnigam.com/papers/emcat-mlj99.pdf]
        - Decision Tree (Shreya & Julian)
        - Neural Network (Julian)
    b. Each of these models will be trained on the vectorized data with the best performance.
4. Best Model (Gaurav or Shreya)
    a. Select the model that does the best from the prev. step and tune it.
