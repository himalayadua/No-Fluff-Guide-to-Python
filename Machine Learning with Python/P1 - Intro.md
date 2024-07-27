# Introduction to Machine Learning
Start with the basics

## What is ML:
- Machine Learning
    - Arthur Samuel 
        - coined the term in 1959
    - learn and behave like humans
    - algorithms that learn and perform based on the data exposed to it
    - based on the data
    - performance is based on the quality of data
- Deep Learning
    - layers of neural networks
    - built with ML algos
- AI
    - uses ML and DL to solve problems

**Example:**
- chess with computer
    - uses ML
        - classify the profile of person playing
        - based on the moves and comparing with data it has seen
            - based on data parameters used to train this model
        - classify
            - beginner
            - intermediate
            - advanced
    - uses DL
        - to make decisions
        - uses multi-layered neural networks

## Types
Depending on the nature of algo
- Supervised
    - uses data developed in supervised environments
    - input and outputs are known
    - example
        - new employee learns in presence of supervisor
    - implementation
        - temperature prediction - when year-wise temp increases are known
        - classification of waste items - when waste input and type of waste are known
    - helps two actions:
        - classification
        - regression
- Unsupervised
    - no supervisor required
    - outputs may not be known
    - find hidden patterns and recognize their relations
    - implementation
        - identifications of anamolies over geo landscapes
        - identification of user-groups based on commonalities
- Reinforcement
    - learns from previous errors
    - user
        - rewards correct results
        - no reward - if output is not proper
    - program reiterates to find better results in case of no reward
    - implementation
        - YouTube recommendation
            - user searches for a particular song
            - user selects and plays a song
            - system trains itself to remember and deliver similar future search
        - Spell check
        - games where players can play with bots

## Machine Learning pipeline
How do you automate series of steps to perform ML?
- ML implementation can have series of sequential steps
    - automate workflow
    - produce ML models
- Pipeline
    - end to end solution
    - includes
        - data extraction
        - raw data input
        - preprocessing
        - features
        - outputs
        - model parameters
        - model training
        - deployment
        - predicting outputs

- essential for efficiently managing 
    - complex and iterative process 
    - of developing, deploying, and maintaining ML models


**Real-World Use Cases**

|  | E-commerce Personalization | Healthcare Diagnostics | Financial Fraud Detection |
| --- | --- | --- | --- |
| Data Extraction | Collecting user behavior data from websites and apps | Gathering patient data from electronic health records (EHRs) | Collecting transaction data from financial systems |
| Raw Data Input | Feeding raw clickstream data into the pipeline | Inputting raw medical data, including lab results and imaging data | Feeding raw transaction logs into the pipeline |
| Preprocessing | Cleaning and normalizing data, extracting features like browsing history and purchase patterns | Cleaning data, handling missing values, and normalizing measurements | Cleaning data, detecting anomalies, and normalizing transaction amounts |
| Features | Identifying key features such as user preferences and product attributes | Extracting relevant features such as symptoms, medical history, and genetic information | Identifying features like transaction frequency, amount, and location |
| Outputs | Generating personalized product recommendations | Predicting disease risk or recommending treatment plans | Flagging suspicious transactions for further investigation |
| Model Parameters | Tuning parameters to optimize recommendation accuracy | Adjusting parameters to improve diagnostic accuracy | Tuning parameters to minimize false positives and false negatives |
| Model Training | Training models on historical data to predict user preferences | Training models on historical patient data to identify patterns | Training models on historical transaction data to detect fraud patterns |
| Deployment | Deploying the model to serve real-time recommendations | Deploying models in clinical settings to assist doctors | Deploying models to monitor transactions in real-time |
| Predicting Outputs | Continuously updating recommendations based on new user interactions | Providing real-time diagnostic support based on new patient data | Continuously updating fraud detection models based on new data |
