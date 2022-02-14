# Data Science Jobs
Analysis of Data Science Jobs using Glassdoor job posting data from the [Data Scientist jobs Kaggle dataset](https://www.kaggle.com/andrewmvd/data-scientist-jobs). This project is part of the Data Science Nanodegree from Udacity.

### Project Motivation
The motivation for this project is to find a dataset, come up with business questions, and use the dataset to answer these questions following the 
CRISP-DM methodology. 

For my project I selected a Kaggle dataset with job postings for Data Science from Glassdoor. The datset consists of 3900 data science job posts scraped from Glassdoor in July 2020. 

The questions I investigated in this analysis were the following:
1. Where are the data science jobs (by city and company)?
2. Which cities have the highest salary for data scientists?
3. Which sectors offer the most job opportunities for data scientists?
4. Is there a relationship between Glassdoor rating and salary?

### Results
Here is a summary of the results for the four questions in this analysis:  

**1. Where are the data science jobs (by city and company)?** 

The top 5 cities in the US for data science jobs were: Austin, Chicago, San Diego, New York, and Houston. The tope 5 companies in terms of most data science job postings were Apple, IBM, Amazon, Staffigo Technical Services LLC, and Facebook. 

**2. Which cities have the highest salary for data scientists?** 

The cities with the highest salaries were all located in California, with the majority in the San Francisco Bay Area. 

**3. Which sectors offer the most job opportunities for data scientists?** 

The top 5 sectors were: IT, Business Services, Biotech, Finance, and Healthcare.

**4. Is there a relationship between Glassdoor rating and salary?** 

In this dataset there was no clear relationship between Glassdoor company rating and data scientist salary. 

Please see the notebook file **DataScienceJobs.ipynb** for further details.

## Setup
Install dependencies:

  ```pip install -r requirements.txt```
  
Or with conda:

  ```conda create --name testenv --file requirements.txt```
  
To run the notebook, use the command```jupyter notebook``` and open the file **DataScienceJobs.ipynb**.

### Libraries Used
- pandas
- numpy
- matplotlib
- notebook
- scipy
- seaborn

### Files 
- **DataScienceJobs.ipynb** -- Jupyter notebook with project code and data visualizations
- **requirements.txt** -- file with the required Python packages to run this project
- **DataScientist.csv** -- [Kaggle dataset](https://www.kaggle.com/andrewmvd/data-scientist-jobs) used for this project

### Acknowledgements
Special thanks to the team at Udacity for creating the Data Science Nanodegree and project. I would especially like to thank the [dataset creator](https://github.com/picklesueat/data_jobs_data) for their work in preparing the dataset and sharing this resource with the Kaggle community.
