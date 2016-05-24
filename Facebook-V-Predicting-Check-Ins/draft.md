# Problem Solving Drafts

Problem definited at [here](https://www.kaggle.com/c/facebook-v-predicting-check-ins/data)

The intuitive thought about predicting **bussiness_id** based on input (row_id, x, y, accuracy, timestamp)
is, this is a __classification problem__.

By looking at the sample_submission.csv, I found that it wants the top 3 bussiness_id as prediction result.
Therefore, we might use two ways to do it:

1. KNN classification
2. Multiclass classification, and return the result with highest 3 probability

### First Try

