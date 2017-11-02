### Author: Urvesh Devani ###

Code in the notebook looks at the historical tweets from past.
Different limits can be set by using max_id and since_id each time running the program.

Explanation of Different Result files:

data :- All the data of unique users who wrote tweets with specific hashtags 
data_contact:- Data where email_ID of user is available in their bio
data_influencer:- Data of unique users with specific hashtags who have 1000-50000 followers

fields:

screen_name: twitter screen name of user
user_name: user name of user
follower_count: follower count of the user
friends_count: friend count of user
email: email fetched from bio of user(if not available then "NA")
is_verified: if user is verified by twitter (influencer account)
lang: primary language of the user

