# Human-Activity-Recognition
Human Activity Recognition (HAR) Challenge: 18-Class Classification
## Overview ##
Welcome to the Human Activity Recognition (HAR) Challenge! In this competition, you'll be working with a diverse dataset of human activities captured through smartphone sensors. Your task is to develop a machine learning model that can accurately classify 18 different human activities based on accelerometer and gyroscope data.

Dataset Description
The dataset contains sensor readings from 90 participants (75 male and 15 female) performing 18 distinct activities. These activities range from simple static postures to complex dynamic movements, providing a comprehensive snapshot of human motion in various scenarios.

Activities/ Classes
| Label | Stand             | Description                                                      |
|-------|-------------------|------------------------------------------------------------------|
| 0     | Standing still    | Standing still for 1 min                                         |
| 1     | Sit               | Sitting still for 1 min                                          |
| 2     | Talk-sit          | Talking with hand movements while sitting (1 min)                |
| 3     | Talk-stand        | Talking with hand movements while standing (1 min)               |
| 4     | Stand-sit         | Repeatedly standing up and sitting down (5 times)                |
| 5     | Lay               | Laying still for 1 min                                           |
| 6     | Lay-stand         | Repeatedly standing up and laying down (5 times)                 |
| 7     | Pick              | Picking up an object from the floor (10 times)                   |
| 8     | Jump              | Jumping repeatedly (10 times)                                    |
| 9     | Push-up           | Performing full push-ups (5 times)                               |
| 10    | Sit-up            | Performing sit-ups (5 times)                                     |
| 11    | Walk              | Walking 20 meters (≈12 s)                                        |
| 12    | Walk-backward     | Walking backward for 20 meters (≈20 s)                           |
| 13    | Walk-circle       | Walking along a circular path (≈20 s)                            |
| 14    | Run               | Running 20 meters (≈7 s)                                         |
| 15    | Stair-up          | Ascending on a set of stairs (≈1 min)                            |
| 16    | Stair-down        | Descending from a set of stairs (≈50 s)                          |
| 17    | Table-tennis      | Playing table tennis (1 min)                                     |

## Description ##
กำหนดให้ Model ที่ใช้ในการสอบได้ จำนวน 4 โมเดลตามตาราง โดยให้ใช้แค่ Library sklearn เท่านั้น
| Supervised Learning Model         | Import Statement                                                    |
|-----------------------------------|---------------------------------------------------------------------|
| Logistic Regression               | `from sklearn.linear_model import LogisticRegression`                |
| K-Nearest Neighbors (KNN)         | `from sklearn.neighbors import KNeighborsClassifier`                |
| Decision Trees                    | `from sklearn.tree import DecisionTreeClassifier`                   |
| Random Forest                     | `from sklearn.ensemble import RandomForestClassifier`               |

## Evaluation ##
Metric<br>
`F1 Score`

You can access via: https://www.kaggle.com/competitions/ai-4-ba-ml-2024-har/overview