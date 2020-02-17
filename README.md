# Data Science 

What is given: a customized baseline of video user views(user_id, video_id), video information (video_id, user_id, likes, dislikes, comments, views) and user's information (user_id, country)

Question: Given a video, recommend another video. 

Using Baye's rule, and spell checking assumption given here: http://norvig.com/spell-correct.html, I am trying to demonstrate that it is likely to recommend the same videos, if their watch popularity remains the same. Thus, new videos/content are/is more difficult to join. 

KNN regression algorithm might not return a video of the same category.
