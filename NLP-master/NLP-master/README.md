# NLP
This repository contains the assignments and project done as part of enhancing the learning experience in the [CS6370-Natural Language Processing Course](https://www.cse.iitm.ac.in/course_details.php?arg=MjI=) offered in Indian Institute of Technology Madras by [Prof. Sutanu Chakraborti](https://www.cse.iitm.ac.in/~sutanuc/).

In this project we analyze the results of our current search engine which has been implemented using a simple Vector Space Model (VSM) where the document vectors are represented using the TF IDF scores (**More details in this repository**: https://github.com/vakadanaveen/NLP). We list the shortcoming(s) and explore improvisations to improve the search engine by addressing its current limitations.

## Dataset ##
The Cranfield dataset was used for the evaluation.

**About Cranfield dataset:**
Collected in the United Kingdom starting in the late 1950s, it contains 1398 abstracts of aerodynamics journal articles, a set of 225 queries, and exhaustive relevance judgments of all (query, document) pairs.
## Folder Structure ##
```
NLP
│-- README.md    
│   
└───Course_Project
   │-- NLP_Course_project_ppt.pdf
   │-- Project_Statement.pdf
   |-- Report.pdf
   │
   └───Code
   |   │-- cranfield
   |   │-- NLP_final_project.ipynb
   |   └-- NLP_final_project_custom_search_application.ipynb 
   |  
   └───Hypothesis testing data
   |   │-- BM25.csv
   |   │-- LSA+BM25.csv
   |   |-- LSA+QE.csv
   |   |-- LSA.csv
   |   |-- Tfidf.csv
   |   └-- a-values.csv
   |
   └───Project Proposal
       |-- Architecture_of_Proposed_Approach.png
       |-- CS20S012_CS20S016_Project_Proposal.pdf
       └-- CS20S012_CS20S016_Final_Presentation.pdf
```

## Set up and Installation: ##
To download the repository: 

`git clone https://github.com/ArupDas15/NLP.git`

We have used colab environment to develop the code and we made ipython notebooks for easy running. Please upload the ipython notebooks to Google Colab to run these notebooks.


The two notebooks present in the project are:


NLP_final_project.ipynb: 


[This notebook](https://github.com/ArupDas15/NLP/blob/master/Course_Project/Code/NLP_final_project.ipynb) contains the entire code for the project which creates various models and evaluates them using the metrics mentioned in the report.

NLP_final_project_custom_search_application.ipynb:

[This notebook](https://github.com/ArupDas15/NLP/blob/master/Course_Project/Code/NLP_final_project_custom_search_application.ipynb) contains the code for creating the custom search application to search for a query. It will take approximately 2 minutes to run this code.


# **NOTE** : 

Upload [cranfield dataset zip file](https://github.com/ArupDas15/NLP/tree/master/Course_Project/Code/cranfield) into your colab by clicking upload the file symbol present in the left panel prior to executing any other code cell. Change the path of the crandfield dataset zip file with your path instead of our google drive path.</br>
For example: `!unzip /content/cranfield.zip`

## Report ##
The final report can be found [here](https://github.com/ArupDas15/NLP/blob/master/Course_Project/Report.pdf).

## Video Presentation ##
The rigorous methodology used to arrive at the best IRS architecture is described in the video presentation [here](https://youtu.be/oQJjh6j2D18). 
## Contributors ##
1. Naveen Vakada
2. Arup Das
