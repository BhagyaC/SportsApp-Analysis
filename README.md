# SportsApp-Analysis
A large scale android sports app analysis
This repository contains the replication package for the paper "A Large-Scale Empirical Study of Android Sports Apps in the Google Play Store".



## Introduction 

The replication package has been organised as follows, 
1. Data Collection: This directory contain all the code snippet used for data collection and preprocessing in this paper
2. Topic Modelling: Applying Mallet LDA and analysing code base on the reviews extracted
3. Analysis: Once topics are finalise we tried to analyse the data using sentiment to understand the factors the users are complaining about

### Data Collection

   a. keyword_extraction.py: Generating sports related keywords from known information for iterative search in google playstore
   
   b. app_details_extraction.py: Collecting metadata from google playstore for populating dataset for every keyword generated
   
   c. reviews_extraction.py: For all extractes sports apps get the reviews associated with them

### Topic Modelling

The given colab [Notebook](https://colab.research.google.com/drive/108V8KMsTeUH4knPBoCZ1dlWeLRUNSr16?usp=sharing) explains all the steps that we used for topic modelling on the reviews of the sports apps that we extracted and analysis that we did on the extracted topics and results
### Analysis

In this section we are adding some exporatory data analysis and the visuralisation for the dataset that we used/created in this study.

1. [Top rated US apps](https://datastudio.google.com/reporting/89dd54e3-f18d-438f-be62-651c7a572b6a): It compare and plots data from Appbrain and help us to conclude some hypothesis 
2. [Generic EDA on labelled Data](https://datastudio.google.com/reporting/d40a3824-b681-4560-915f-c52d79676b52): It evaluates the sample set generated and manually labelled in more intricated way
### Replicating Results

In this section we will conclude which script and data will help you to replicate all the RQs we have addressed in the given study 

1. RQ1: 
