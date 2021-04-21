![cover](./images/analysis_cover.jpg)
# Microsoft Movie Analysis

**Author**: Jennifer Ha

## Overview

A one-paragraph overview of the project, including the business problem, data, methods, results and recommendations.
***

## Business Problem

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. 

In order to assist the stakeholders at Microsoft to make data-driven decision for their new business, we will be reviewing and analyzing datasets to provide a viable and profitable business option. The findings and recommendations will help the stakeholders with better understanding of movie industry, to decide when to release their movies and who to work with to drive a successful outcome.

***
Questions to consider:
* When is the best time of year to release a movie?
* Which genres are the most profitable and yield the highest ROI?
* Who are the top casts and directors in those genres that Microsoft should work with?
***

## Data
For this project, the following data sets from The Numbers and IMDb were used to answer the questions in the above.  

* `new_movie_budgets` & `tn_movie_budgets`: This data set from The Numbers contains movie production budget, domestic, and international revenue amount by movie, which will be used to conduct ROI anaylsis. 

* `imdb_name_basics`: This data set from IMDb contains general movie information with movie title, runtime, and genre(s). Every movie has a unique ID (`tconst`) assigned, which will be used as primary key to join other imdb data sets.

* `imdb_title_principals`: This data set from IMDb contains job titles for people who participated in a film with a unique ID (`nconst`) that can be used to identify individual participants. This dat set also includes a foreign key (`tconst`).

* `imdb_title_basics`: This dat set from IMDb contains names of individuals in the business with their profession title(s), movies they participated listed with the `tconst`, and their unique ID `nconst`.
***

## Methods
When cleaning the data, we will drop all columns that we don't need for this project.
We will clean up duplicates after we join the tables so that we can achieve the desirable output record at once.
***

## Results

Present your key results. For Phase 1, this will be findings from your descriptive analysis.
***

Here is an example of how to embed images from your sub-folder:

### Visual 1
![graph1](./images/viz1.png)
***

## Conclusions
This analysis leads to three recommendations for creating movies :

**1. Release movies in May, June, July, November, or December.** Our analysis shows that summertime and holiday seasons are the best time of year to release a movie. If Microsoft wants to release a movie across the world simultaneously, I recommend launching a movie in June or July. If different timeline can be applied, release a movie in the States in May first, then internationally in June.

**2. Produce a movie in Mystery, Horror, Animation genres.** Microsoft has the capability to run movie business in many countries as it has many locations worldwide. Therefore, I recommend producing a movie in Mystery, Horror, and Animation to target audience globally.

**3. Recuirt people with proven stats.** I provided lists of Top 10 actors and directors in Top 3 genres that generated the most profit. Microsoft should contact these individuals and try to recruit them to enter this competitive movie industry.
***

## For More Information

See the full analysis in the [Jupyter Notebook](https://github.com/jennifernha/Microsoft-Movie-Analysis/blob/main/Microsoft%20Movie%20Analysis.ipynb) or review this presentation.

For additional info, contact Jennifer Ha at jnha1119@gmail.com
***

## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── README.md                           <- The top-level README for reviewers of this project
├── dsc-phase1-project-template.ipynb   <- Narrative documentation of analysis in Jupyter notebook
├── DS_Project_Presentation.pdf         <- PDF version of project presentation
├── data                                <- Both sourced externally and generated from code
└── images                              <- Both sourced externally and generated from code
```
