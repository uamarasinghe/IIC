# predicting_automatabiltiy_of_work_tasks

Can we predict the automatability of occupational tasks in the same way that we predict movie ratings? 

## What
To model the relationship between the text of an occupational task description in ONET and its  suitability for machine learning (SML) to predict the SML for an unseen task (a task not found in ONET). 


## Why
To predict the degree to which ML technologies will automate any given job based on the job’s description (e.g. as seen in an online job posting). To date, automation risk has been predicted for ONET occupations (bundles of jobs), but the literature has not commented on specific jobs as they appear in job postings, which are more familiar to both job seekers and employers.  


## How
Brynjolfsson, Mitchell, and Rock have produced a “suitability for machine learning” (SML) rubric to measure the degree to which tasks lend themselves to being performed by ML technologies rather than by people. Use word embeddings or sentence encoding to model the relationship between the words/n-grams of an occupational  task and their corresponding SML scores to predict the SML for an unseen task. 
