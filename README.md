# Cyber Security

## Problem Statement:

Book-My-Show aims to enable ads on their website while prioritizing user privacy and protecting their information. However, they are concerned about the potential presence of malicious URLs in ads that can lead to harmful consequences such as malware installation, system freezing, or data breach. Book-My-Show wants to analyze whether a given URL is prone to phishing attacks or not.

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
