# Salary Prediction Portfolio

# What's the Problem?

This project examines job posting salaries based on existing dataset, and make prediction for salaries of new job postings. An estimation of 
salary range across different industries offers people a rough idea of 


# Datasets

train_features.csv - Each observation represents an individual's job posting; each column represents unqiue information about this applicant
and the job applied to. This dataset is meant to be used in training models.

test_features.csv - Each observation represents an individual's job posting; each column represents unqiue information about this applicant 
and the job applied to. This dataset is meant to be used for evaluating models trained on train_features.csv.

train_salaries.csv - Each observation represents an individual's salary corresponding to their job posting in train_features.csv.

Features:
* jobId - the id of the job posting
* companyId - the id of the company posting the job
* jobType - the type of the job (e.g. CEO, CFO, senior, etc)
* degree - the highest degree obtained by the applicant (e.g. DOCTORAL, MASTERS, BACHELOR, etc)
* major - the major of this applicant in college (e.g. business, math, etc)
* industry - the industry this job belongs to (e.g. oil, finance, tech, etc)
* yearsExperience - years of experience required
* milesFromMetropolis - distance away from the metropolis in miles
* salary - the salary of the job posting 


# Feature Summary 

