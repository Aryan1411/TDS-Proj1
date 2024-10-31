# TDS-Proj1
First project of TDS
Firstly I scrapped all the data of users and repositories using my token from git hub developers setting.
Fetched all users and their repositories for city beijing and having following greater then 500.
Then I saved users data in users.csv file and repositories data in repositories.csv
Then,
I read all the questions so that I can make a general idea what i want to find and how.
Que1 was about top 5 users- so i used pandas sort function to filter them in decending order according to following.
Que2  was about 5 earliest registered users-  so i used pandas sort function to filter them using pd.to_datetime order according to 'created_at'.
and similarly other questions.
