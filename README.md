# MM4_2401FTDS-Anime_Recommender_System_Project
## Building a Collaborative and Content-Based Recommender System for Anime

 ## Table of Contents
* [1. Project Overview](#project-description)
* [2. About Dataset](#dataset)
* [3. Packages](#packages)
* [4. Data Cleaning](#data-cleaning)
* [5. Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
* [6. Data Preprocessing](#data-preprocessing)
* [7. Unsupervised ML Models](#recommender-models)
* [8. Model Optimization](#model-optimization)
* [9. Deployment](#deployment)
* [10. Conclusion](#conclusion)
* [11. Recommendations](#recommendations)
* [12. Team Members](#team-members)

  ## 1. Project Overview
  #### 1.1. Introduction
Recommender systems are algorithms designed to suggest items to users based on various inputs, such as their past behavior and preferences. These systems are essential in many domains, including e-commerce, music, movies, and anime, as they enhance user experience by providing personalized recommendations.

**Importance in the Context of Anime**

The anime industry produces a vast and diverse array of content, making it challenging for users to find anime that align with their interests. A well-designed recommender system helps users navigate the extensive anime catalog, discovering titles they are likely to enjoy based on their unique tastes. By delivering personalized recommendations, these systems can increase user engagement and satisfaction, fostering a deeper connection with the platform.


#### 1.2. Objectives
The primary objective of this project is to develop a hybrid recommender system that combines collaborative and content-based filtering techniques. This system aims to predict how users will rate anime titles they have not yet seen, using their historical preferences and interactions. By accurately predicting user ratings, the recommender system will provide tailored anime suggestions, enhancing the user's discovery process and overall viewing experience.
<br>

## 2. About Dataset

This dataset contains information on user preference data from 570,355 users on 12,294 anime. It contains information about anime and user ratings, split across several CSV files. It's designed for a recommender systems project where we will predict user ratings for unseen anime for 633,686 users.

Data Summary:
- **Anime Information (anime.csv)**: Contains details about each anime, including title, genre, type (movie, TV, etc.), number of episodes, average rating, and member count.
- **User Ratings (train.csv)**: Records user ratings for specific anime entries. Includes user ID, anime ID, and the rating provided (or -1 if watched but not rated).
- **Test Set (test.csv)**: Contains user IDs and anime IDs for which we will predict ratings. No ratings are provided in this file.
- **Submission Format (submission.csv - *for reference*)**: Illustrates the expected format for our final predictions. It combines user ID and anime ID into a single ID and includes the predicted rating for each user-anime pair.

**Additional Information:**
- Original data comes from MyAnimeList.net. Source: Adapted open-source Kaggle dataset 
(https://www.kaggle.com/datasets/CooperUnion/anime-recommendations-database).

## 3. Packages <a class="anchor" id="packages"></a>

To carry out all the objectives for this repo, the following necessary dependencies were loaded:
+ `Pandas 2.2.2` and `Numpy 1.26`
+ `Matplotlib 3.8.4`
  
## 4. Data cleaning

Data cleaning is a crucial step in the data analysis process, involving the correction or removal of incorrect, corrupted, duplicate, or incomplete data within a dataset. Through various techniques such as filling missing values, removing outliers, and standardizing data formats, it ensures the accuracy and reliability of subsequent analyses and decision-making. This involves rectifying missing or erroneous values, removing duplicates, and resolving inconsistencies.

## 5. Exploratory Data Analysis (EDA)

Exploratory Data Analysis (EDA) serves as a foundational step in the data preprocessing phase, aimed at understanding the underlying patterns, relationships, and structure of the data. It involves various techniques such as visualizations, summary statistics, and correlation analysis to uncover insights and identify potential issues. EDA helps in forming hypotheses, guiding further analysis, and making informed decisions about data preprocessing and modeling.
  
## 6. Data Preprocessing

Data preprocessing is a crucial step in building any machine learning model. It involves transforming raw data into a clean, structured format that is suitable for analysis. This step includes various tasks such as encoding categorical variables, normalizing data, and feature extraction. Proper data preprocessing ensures that the data is of high quality, which in turn improves the performance of the machine learning models. This involves encoding categorical variables, ensuring uniformity and compatibility for subsequent analyses.

## 7. Unsupervised ML Models

Various models were trained and evaluated.
For Content-Based Filtering:
- **Cosine similarity & Sigmoid kernel**
For Collaborative Filtering:
- **Singular Value Decomposition (SVD)**
- **CoClustering**
- **BaselineOnly**
- **SlopeOne**
 
## 8. Model Optimization


## 9. Deployment


## 10. Conclusion


## 11. Recommendations

- Continuously update the model with new data to maintain accuracy.
- Explore advanced Unsupervised Machine Learning techniques like .... for improved performance.
- Integrate user feedback to refine and enhance the recommender system.

## 12. Team Members
   | Name                                                      |Email              
|--------------------------------------------------------------|--------------------             
| [Khululiwe Hlongwane]                                        |[khululiwe.hlongwane9966@gmail.com]      
| [Judith Kabongo]                                             |[jkabongo19@gmail.com]  
| [Ntembeko Mhlungu]                                           |[ntembekomhlungu1@gmail.com]
| [Tselane Moeti]                                              |[tsemoeti24@gmail.com]
| [Masixole Nondumo]                                           |[m.nondumo@gmail.com]
| [Nolwazi Vezi]                                               |[nolwazinvd@gmail.com]
                          
