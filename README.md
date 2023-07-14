# Cyber Security

<img src="p-1.jpg" alt="cyber_security" width="600">

## Problem Statement:

Book-My-Show is dedicated to enabling advertisements on their website while upholding user privacy and safeguarding their sensitive information. However, they are keenly aware of the potential risks associated with malicious URLs that may be present in these ads. These malicious URLs can pose threats such as malware installation, system freezing, or unauthorized access to user data. To ensure a secure browsing experience for their users, Book-My-Show aims to analyze URLs and determine whether they are susceptible to phishing attacks.

## Dataset Details: 

The input dataset consists of 11k URL samples. Each sample is described by 32 features, ranging from -1, 0, to 1.

- 1: Phishing
- 0: Suspicious
- 1: Legitimate

The samples can be classified as either legitimate or phishing URLs.

## Step 1

### Exploratory Data Analysis:

Perform exploratory data analysis on the dataset. Analyze the distribution of features using histograms and heatmaps. 

- Determine the number of samples in the dataset and identify unique elements in each feature. 

- Check for the presence of any null values in the features. 

## Step 2

### Correlation of Features and Feature Selection:

Explore the correlation between features and identify any correlated features in the dataset. Remove features that exhibit high correlation with a predefined threshold.

## Step 3 and 4

### Building Classification Model: 

Build a robust classification system to classify whether a given URL is a phishing site or not.

- Develop classification models using binary classifiers to detect malicious or phishing URLs.
