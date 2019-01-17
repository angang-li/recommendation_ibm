# Recommendation Engine with IBM

This project created various types of recommendation systems to recommend articles to both new and returning users, based on real data from the IBM Watson Studio platform.

## What I did

1. Exploratory data analysis

    - Used descriptive statistics and visuals to understand the dataset
    - Clean up the dataset

2. Rank-based recommendation for new users

    - Created functions to recommend most popular articles

3. User-user based collaborative filtering for existing users

    - Created functions to recommend articles based on what similar users liked

4. User-item based collaborative filtering for existing users

    - Implemented singular value decoposition (SVD) to recommend articles based on the history of user-article interactions
    - Trained SVD on training set and evaluated performance on testing set.

## File structure

- `Recommendations_with_IBM.ipynb`: code and markdowns
- `data`
    - `articles_community.csv`: data of articles content
    - `user-item-interactions.csv`: data of user-article interactions

## Acknowledgement

Udacity Nanodegree program in partner with IBM Watson Studio.