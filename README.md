# Name: Prajapati Uday Mukesh
# Company: CODTECH IT SOLUTIONS 
# Id: CT6WDS2794
# Domain: Java Programming
# Duration: DECEMBER 12th, 2024 to JANUARY 27th, 2025.
# Mentor: Muzammil Ahmed

# Overview
The provided code implements a movie recommendation system using the Apache Mahout library. The system is based on user-based collaborative filtering, leveraging Pearson Correlation for similarity measurement. The program reads user-movie interaction data from a CSV file, calculates personalized movie recommendations for each user, and writes these recommendations to an output text file.

# Key Activities
# 1. Data Preparation:
Reads movie interaction data from data/moviedata.csv using Mahout's FileDataModel.
Ensures the output file data/output.txt is created to store results.

# 2. Similarity Calculation:
Computes user similarities using the Pearson Correlation method (PearsonCorrelationSimilarity).

# Technology Used:
# Programming Language: Java
# Library: Apache Mahout
FileDataModel for data input.
PearsonCorrelationSimilarity for computing user similarity.
ThresholdUserNeighborhood for filtering similar users.
GenericUserBasedRecommender for generating recommendations.
# File Handling: Java I/O for reading data and writing results.

# Key Insights
# 1. User-Centric Recommendations:
The system recommends items by analyzing the preferences of similar users within a specified similarity threshold.

# 2. Scalability:
The implementation efficiently iterates over all users (LongPrimitiveIterator) and provides personalized recommendations for each.

# 3. Customizable Threshold:
The similarity threshold (0.1 in this case) can be adjusted to tune the number of neighbors considered for recommendations.

# 4. Output Format:
The recommendations are well-structured and easy to interpret, providing both item IDs and recommendation scores.

# Data.csv
![image](https://github.com/user-attachments/assets/1165a5cc-f70c-431b-be6c-992191593482)

