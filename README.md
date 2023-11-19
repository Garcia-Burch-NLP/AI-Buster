# AI BUSTER

## Objective:

With the advance of AI chatbots like [OpenAi's ChatGPT](https://chat.openai.com/) concerns about a student's academic progression. Our goal is to create an ML model that is capable of identifying essays that are AI-generated. 



## Planning:

## Since this problem is asking to identify `AI` or `Not AI` we will be utilizing a classifier for modeling. Some initial hypotheses we have are outlined below:

* Project's Hypothesis:
Our initial assessment lead  us to believe an AI-generated essay will be structed and written within strict writing parameters.


H<SUB>0</SUB>: Part of speech usage will not differ in essays written by an AI when compared to an essay written by a student. <BK>
H<SUB>A</SUB>: Part of speech usage will differ in essays written by an AI when compared to an essay written by a student.

Directory Breakdown

DATA: Directory our data is held

- External Kaggle Database
    - Daigt_external_dataset: This is an [external dataset](https://www.kaggle.com/datasets/alejopaullier/daigt-external-dataset) from kaggle.
- Master Data: Contains the data after it was merged together, and will act as our working data.
- Prompts: Contains the files with the prompts CSVs. 
- Submissions Format: Contains submission format for input CSV into machine learning  model
- Train Data: Contains the data we were provide at the begin of this project

Fermin: Contains Fermin's Working Files 

Josh: Contains Josh's Working Files
