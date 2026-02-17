# Instagram-User-Analytics--SQL-Project

## PROJECT DESCRIPTION
The project focused on analyzing user interaction data to provide business insights. The primary goal is to use SQL to understand user behavior, identify potential issues like fake accounts, and deliver data-driven recommendations to a product team. The analysis is crucial for making informed decisions about the platform's future development and growth.

## PURPOSE OF THE PROJECT
The purpose of this project is to analyze Instagram user interaction data using SQL to understand user behavior and generate meaningful business insights. It aims to identify inactive users, detect potential fake accounts, and support data-driven decisions for platform growth and improvement.

## APPROACH USED
My approach was to first understand the schemas and what all provided in this project. Then I went through all the tables and identified what all provided in that like user, likes, photos, tags etc. Then I used different queries to perform all the task provided. 

## ABOUT DATASET
The dataset consists of Instagram user interaction data, including tables such as users, photos, likes, tags, and photo_tags. It captures user registrations, posting activity, engagement metrics, and hashtag usage for behavioral and business analysis.

Users Table 
| id | username      | created_at          |
| -- | ------------- | ------------------- |
| 1  | Aniya_Hackett | 2016-02-10 15:30:45 |
| 2  | Jaclyn81      | 2016-03-15 09:12:22 |
| 3  | Andre_Purdy85 | 2016-04-18 18:05:11 |

Photos Table  
| id | image_url          | user_id | created_at          |
| -- | ------------------ | ------- | ------------------- |
| 1  | beach_photo.jpg    | 3       | 2016-05-01 10:15:30 |
| 2  | sunset_view.png    | 1       | 2016-05-03 14:22:10 |
| 3  | concert_night.jpeg | 2       | 2016-05-05 19:40:55 |

Likes Table
| user_id | photo_id | created_at          |
| ------- | -------- | ------------------- |
| 1       | 1        | 2016-05-02 08:12:45 |
| 2       | 1        | 2016-05-02 09:15:33 |
| 3       | 2        | 2016-05-04 11:25:10 |

Tags Table 
| id | tag_name |
| -- | -------- |
| 1  | beach    |
| 2  | concert  |
| 3  | travel   |

Photo_tags Table 
| photo_id | tag_id |
| -------- | ------ |
| 1        | 1      |
| 2        | 3      |
| 3        | 2      |

## Questions to Answer

A) Marketing Analysis:

1.Loyal User Reward: The marketing team wants to reward the most loyal users, i.e., those who have been using the platform for the longest time.

Your Task: Identify the five oldest users on Instagram from the provided database.

2.Inactive User Engagement: The team wants to encourage inactive users to start posting by sending them promotional emails.

Your Task: Identify users who have never posted a single photo on Instagram.

3.Contest Winner Declaration: The team has organized a contest where the user with the most likes on a single photo wins.

Your Task: Determine the winner of the contest and provide their details to the team.

4.Hashtag Research: A partner brand wants to know the most popular hashtags to use in their posts to reach the most people.

Your Task: Identify and suggest the top five most commonly used hashtags on the platform.

5.Ad Campaign Launch: The team wants to know the best day of the week to launch ads.

Your Task: Determine the day of the week when most users register on Instagram. Provide insights on when to schedule an ad campaign.

B) Investor Metrics:

1.User Engagement: Investors want to know if users are still active and posting on Instagram or if they are making fewer posts.

Your Task: Calculate the average number of posts per user on Instagram. Also, provide the total number of photos on Instagram divided by the total number of users.

2.Bots & Fake Accounts: Investors want to know if the platform is crowded with fake and dummy accounts.

Your Task: Identify users (potential bots) who have liked every single photo on the site, as this is not typically possible for a normal user.

