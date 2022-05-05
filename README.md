# SportsApp-Analysis
A large scale android sports app analysis
This repository contains the replication package for the paper "A Large-Scale Empirical Study of Android Sports Apps in the Google Play Store".



## Introduction 

The replication package has been organised as follows, 
1. Data Collection: This directory contain all the code snippet used for data collection and preprocessing in this paper
    a. keyword_extraction.py: Generating sports related keywords from known information for iterative search in google playstore
    b. app_details_extraction.py: Collecting metadata from google playstore for populating dataset for every keyword generated
2. Topic Modelling: Applying Mallet LDA and analysing code base
3. Analysis: Once topics are finalise we tried to analyse the data using sentiment to understand the factors the users are complaining about


