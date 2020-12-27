# December ML Challenge

### Problem Statement

In an era where technology plays a significant role in people’s lives, one cannot deny that it changes the way people interact and communicate with others. Today, technology has caused some significant changes in the dating world as well. Online dating is a new trend that is influencing many people around the world.

As a data scientist, you are required to predict the match percentage between the users in a matrix format based on the attributes provided by the user on a dating website.

Based on the user’s sexual orientation, you are required to perform the following:

1. If a user is heterosexual (prefers the opposite sex), then the match percentage must be 0 for this user with respect to other users of the same gender if the other users have the same behavior.
2. If a user is a homosexual (prefers the same sex), then the match percentage must be 0 for this user with respect to other users of the opposite gender if the other users have the same behavior.
3. The match percentage of a user with her/himself must be zero.

### Dataset

The dataset folder contains a data.csv file that contains the following feature:

user_id	
username
age	
status
sex	
orientation
drinks
drugs	
height
job
location
pets	
smokes	
language
new_languages	
body_profile
education_level
dropped_out
bio	n
interests
other_interests	
location_preference	

### Submission file format

The submission file is required to be in a matrix format. For example, if the number of users in the dataset provided is 1000, then the submission.csv file must contain a matrix of size 1000 * 1000.  

You can refer to the 'sample submission.csv' file for the sample dataset provided in the dataset folder.

### Solution

[See this notebook](https://github.com/ishantjuyal/December-ML-Challenge/blob/main/Final%20Solution%20December%20Challenge.ipynb)

### Results

Secured rank 14 out of 2541 participants with final score = 98.12724/100

