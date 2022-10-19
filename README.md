# Natural Language Processing - Repository main programming language predictor


## Project description:

- We were able to programatically scrape some of the most popular repositories on Github, and from them collect the repository name, main programming language used, and the content of the README file from each. 

- All the data collected was compiled into a DataFrame with the anticipation that we will be able to glean from it what the main programming language is of the repository via Natural Language Processing methods on the corresponding README file content.

- While the data we collected is static, the Github repositories are dynamic and ever-changing. Therefore is important to note the data was collected from these repositories on the morning of October 18, 2022.


## Project goal

- The stated goal of this project is to predict the main progamming language of a repository on Github based on the commensurate README file contents.

## Project plan

- data science across all domains can usually be generalized as the following steps. We used this as our framework to make our plan.

    - Planning- writing out a timeline of actionable items, when the MVP will be finished and how to know when it is complete, formulate initial questions to ask the data.

    - Acquisition- Gather data via programatically scraping README.md files from popular Github repositories and bring all necessary data into python enviroment.

    - Preparation- this is blended with acquisition where we clean and tidy the data to make it apropriate for natural language programming techniques, and split into train, validate, and test.

    - Exploration/Pre-processing- we create visualizations and answer the questions we initially set out to answer to select and engineer features that impact the target variable.

    - Modeling- based on what we learn in the exploration of the data I will select the useful features and feed into different  models with different hyperparameters and evaluate performance of each to select our best perfomoing model.

    - Delivery- create a final report and Google slides summary that succintly summarizes what we did, why we did it, what we learned,and any relavent conclusions.

## How to repeat this work

- You will need to pull down all files in this repository into the working directory in order for the workbook to run top down without issue.

- You will need all the libraries listed at the top of the final workbook installed. Simply PIP install whatever library you do not have as needed.


## Conclusions & Google slides summary link


