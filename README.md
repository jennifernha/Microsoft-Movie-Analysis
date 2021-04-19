# Microsoft Movie Analysis

**Author**: Jennifer Ha

## Overview

A one-paragraph overview of the project, including the business problem, data, methods, results and recommendations.

## Business Problem

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. 

In order to assist the stakeholders at Microsoft to make data-driven decision for their new business, we will be reviewing and analyzing datasets to provide a viable and profitable business option. The findings and recommendations will help the stakeholders with better understanding in this industry, how to better spend their budget, and who to work with to drive a successful outcome.

***
Questions to consider:
* Which genres are the most profi`table and yield the highest ROI?
* What is the ideal budget range to yield the highest ROI?
* Who are the top casts and directors in those genres that Microsoft should work with?
***

## Data
For this project, the following data sets from The Numbers and IMDb were used to answer the questions in the above.  

* `tn_movie_budgets`: This data set from The Numbers contains movie production budget, domestic, and international revenue amount by movie, which will be used to conduct ROI anaylsis. 

* `imdb_name_basics`: This data set from IMDb contains general movie information with movie title, runtime, genre(s). Every movie has a unique ID (`tconst`) assigned, which will be used as primary key/foreign key to join other imdb data sets.

* `imdb_title_principals`: This data set from IMDb contains job title for people who participated in a film with a unique ID (`nconst`) that can be used to identify individual participants. This dat set also includes a foreign key (`tconst`).

* `imdb_title_basics`: This dat set from IMDb contains names of individuals in the business with their profession title(s), movies they participated listed with the `tconst`, and their unique ID `nconst`.
***

## Methods
When cleaning the data, we will drop all columns that we don't need for this project.
We will clean up duplicates after we join the tables so that we can achieve the desirable output record at once.
***

## Results

Present your key results. For Phase 1, this will be findings from your descriptive analysis.

***
Questions to consider:
* How do you interpret the results?
* How confident are you that your results would generalize beyond the data you have?
***

Here is an example of how to embed images from your sub-folder:

### Visual 1
![graph1](./images/viz1.png)

## Conclusions

Provide your conclusions about the work you've done, including any limitations or next steps.

***
Questions to consider:
* What would you recommend the business do as a result of this work?
* What are some reasons why your analysis might not fully solve the business problem?
* What else could you do in the future to improve this project?
***

## For More Information

Please review our full analysis in [our Jupyter Notebook](./dsc-phase1-project-template.ipynb) or our [presentation](./DS_Project_Presentation.pdf).

For any additional questions, please contact **name & email, name & email**

## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── README.md                           <- The top-level README for reviewers of this project
├── dsc-phase1-project-template.ipynb   <- Narrative documentation of analysis in Jupyter notebook
├── DS_Project_Presentation.pdf         <- PDF version of project presentation
├── data                                <- Both sourced externally and generated from code
└── images                              <- Both sourced externally and generated from code
```
