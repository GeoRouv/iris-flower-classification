# Iris-Classification

The Iris Flowers dataset is a very well known and one of the oldest and simplest for machine learning projects for beginners to learn. With this project, learners have to figure out the basics of handling numeric values and data. Data points include the size of sepals and petals by length and width. Using machine learning, a successful project classified irises into one of three species.

## Tools  
- scipy  
- numpy  
- matplotlib  
- pandas  
- sklearn  
 
and make sure you have Python 2.7 or 3.6+

## Run

    python3 main.py

## Notes

- The dataset was split into training set (80%) and test set (20%). The dataset is
shuffled before splitting in order to eliminate the possibility of any initial structure
in the dataset.

- For every observation in the test set, its distance was calculated from all observations
in the training set. For this report, 3 dierent distances were used in this step, to
account for and report on the sensitivity of each distance metric:
 • Euclidean distance
 • Manhattan distance
 • Jaccard distance of sample sets
