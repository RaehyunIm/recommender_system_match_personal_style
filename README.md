# Recommender_system_match_personal_style
The objective of this project is to build a recommender system algorithm to predict and offer the right product options for users.
The project focuses on product (mostly clothes) shuffle ratings. The dataset expresses the personal preferences on clothes and some of identifying features of the users.  

We will use Collaborative Filtering method to approach this recommender system modeling.
# What is Collaborative Filtering?
It is a popular Recommender System (RecSYs) technique that makes automatic predictions (filtering) about the interest of a user by collecting preferences or taste information from other users' previous experiences (collaborating). 
In the case of this project, the model makes predictions about a user's potentially preferable clothes based on other similar users' demonstration of taste throughout the quizzes. 
The underlying assumption of the collaborative filtering approach is that if Jonn has the same/similar taste as David on a set of items, John is more likely to have David's taste for a given item than that of other randomly chosen people randomly chosen person. 

# Data :
The dataset consists of product (cloth) Shuffle ratings from users on items. Users rate items in (multiple)
quizzes of 10 questions each. A quiz can either contain random questions, or “personalized
questions”. In the latter, the items shown in the quiz are chosen because we think the user will
like them, rather than selected at random from all available questions.

# Columns : 
● User_id: identifies the user
● Quiz_type: “random” or “personalized”
● Quiz_number: indicates the sequence number of the quiz shown to a user. Thus,
quiz_number = 1 indicates that this question is part of the first quiz the user rated.
● Question_number: indicates the sequence number of the question shown to a user
across all quizzes the user has rated. Thus, this is an increasing sequence for each user.
● Item_id: identifies the item rated 
● Rating: 1 indicates a Like, 0 indicates a Dislike 
