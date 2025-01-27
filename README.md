
# Spanish Political Alignment Classifier

## Project Intro/Objective
The purpose of this project is define a classification technique to assign a party to Spanish Parliamentary debate speeches. 

### Methods Used
* Machine Learning
* Data Visualization
* Binary Classification

### Technologies
* Python

## Project Description
We used ParlaMint data on Spanish parliamentary debates from 2015-2023. We then preprocessed and applied exploratory analysis techniques. Finally, we start with left vs right parties, People's Party (PP) and Spanish Socialist Workers' Party (PSOE),  then we expand our classifier to test its performance other party speeches. 

Below you can see the ability of the classifier to determine PP vs PSOE (main left and right parties respectively in Spain), and also the trained models ability to determine the difference between VOX and Podemos (two additional more extreme left vs right respectively parties). 

Here we can see the XGBoost classifier out of sample test data with PP and PSOE speech data with a clear separation of the parties. 
<img width="926" alt="Screenshot 2024-04-12 at 6 50 58 PM" src="https://github.com/agbennett-bse/catalan_political_alignment/assets/145025558/c66497d0-60c5-4c1c-abdd-63b6e58f2a84">

Here we can see the XGBoost classifier's predictive power with out of sample VOX and Podemos speech data showing clear distinction between the parties' speech. 
<img width="922" alt="Screenshot 2024-04-12 at 6 51 29 PM" src="https://github.com/agbennett-bse/catalan_political_alignment/assets/145025558/b5a0a91c-d72f-40f6-8c95-6b41dda2f403">

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
    
