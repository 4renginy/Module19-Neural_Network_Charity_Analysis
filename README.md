# Module19-Neural_Network_Charity_Analysis

## Purpose;
Alphabet Soup is a philantrhopic nonporfit foundation dedicated to heing organizations tha tportect the envornment, people's well being and unify the world. ALphabet has raised and donated over 10 billion $ in the past. This money used for lifesaving technologies adn orginazed defrostaions groups around the world. 

Our job is using the features in the provided dataset, creating a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Process
We have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization.  

[Link to CSv file]

We will preprocess the data for Neural Network Model, compile, train, evaluate the model and finally optimaze it. 

Right at the start we have decided to following;

Variable is considered the target(s) for our model

                IS_SUCCESS

Variable(s) are neither targets nor features, removed from the input data

                EIN and NAME—Identification columns
                

Variables are considered the feature(s) for our model,
                
                CLASSIFICATION—dropped for Deliverable 3
                APPLICATION_TYPE—Feature
                AFFILIATION—dropped for Deliverable 3
                CLASSIFICATION—Feature
                USE_CASE—dropped for Deliverable 3
                ORGANIZATION—dropped for Deliverable 3
                STATUS—dropped for Deliverable 3
                INCOME_AMT—dropped for Deliverable 3
                SPECIAL_CONSIDERATIONS—dropped for Deliverable 3
                ASK_AMT—Feature

During preprocessing, 
                dropped columns that are not useful, 
                grouped unique values, 
                encoded categorical varables with 
                one-hot encoding
                splitted the proprocessed data to future and target arrays
                created training and and testing datasets.
            
Neural Network Model..Tensorflow Keras

We started with  2 layers and 100 nodes for neural network model. As activation function we used relu and sigmoid

![picture]

The accuracy for this run was 72%

To improve the model, I have dropped more columns that are not very usefull,added ASK_AMT column to futures, played with node layers, activation functions and expoch numbers however I was not able to reach to 75% target.








