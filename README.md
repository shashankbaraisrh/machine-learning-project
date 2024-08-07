hushHush Recruiter

Project Overview

hushHush Recruiter is an automated talent acquisition system for Doodle, using machine learning to identify and notify potential candidates from GitHub and Stack Overflow, and manage coding challenges for evaluation.

Features

Automated Candidate Selection: Analyzes GitHub and Stack Overflow data.
Secretive Notifications: Automatically notifies selected candidates.
Coding Challenge Interface: Manages coding challenges.
Automated Evaluation: Allows hiring managers to evaluate submissions and notify candidates.
Technical Approach
Data Collection
APIs Used:
GitHub API for contributions, repositories, stars, forks, etc.
Stack Overflow API for reputation, answers, questions, badges, etc.

Machine Learning Models

Unsupervised Learning:
K-Means Clustering to label candidates as 'good' or 'bad'.

Supervised Learning:
Random Forest Classifier, optimized with cross-validation and hyperparameter tuning.
Note: Various supervised and unsupervised models were tested to select the best-performing model.

Implementation
Language: Python
Key Libraries: pandas, numpy, scikit-learn, requests, flask, sqlalchemy
