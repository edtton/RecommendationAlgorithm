Overview and Assignment Goals:

The objectives of this assignment are the following:
Develop a Personalized Recommendation System that uses the rating information and/or side-information (i.e., additional content).
Think about using classification, clustering, or anything you learned this semester.
The Scoring Metric will be Root Mean Squared Error (RMSE) where the predictions are rating in the range 0-5. As such, you may want to switch to a regression setting since the output can be real-valued.

Detailed Description:

Recommendation Systems are all pervasive. The objective of this movie recommender system is to predict the 5-star rating a movie will get for a given user. You can use content features as well as the ratings to make your final predictions.
Data Description:

As part of the training I provide you several different files all zipped together as additional_files.tar.gz (Uploaded in the training portion of this assignment).

Once you unzip this file you will find a readme.txt with a listing of the files and useful information about them (replicated below).

* train.dat: This file contains the rating of a user for a given movie.

* test.dat: This file contains user-movie pairs but no rating (Your goal is to predict these ratings for user-movie pairs)

* movie_genres.dat: This file contains the genres of the movies.

* movie_directors.dat: This file contains the directors of the movies. .

* movie_actors.dat: This file contains the main actors and actresses of the movies. A ranking is given to the actors of each movie according to the order in which they appear on the movie IMDb cast web page. .

* tags.dat: This file contains the set of tags available in the dataset. .

* user_taggedmovies.dat: These files contain the tag assignments of the movies provided by each particular user. .

* movie_tags.dat: This file contains the tags assigned to the movies, and the number of times the tags were assigned to each movie. .

test.dat: Test set consisting of user-movie pairs for which you need to produce the ratings (also included in the zipped file described above)

example_entry.dat: A sample submission with 71299 entries in the range of 0-5.

Rules:
You are allowed to work in a group of 2, or by yourself.
Keep in mind that we are making personalized, not general recommendations. So a trivial approach like using global or movie averages alone would not be sufficient, though you could certainly use them as a baseline estimate and build on that, as described in the lecture. Your effort will be reflected in the Implementation part of your grade.
For this project, I will have two top-score (lowest RMSE) awards for extra credit: one for individual and one for group. As always, you are not eligible to compete if you submit late.
Discussion of broad level strategies are allowed but any copying of submission files and source codes will result in honor code violation. Similarly, it's never acceptable to copy code from the internet, even if you cite the source. Doing so will result in honor code violation.
Use Jupyter Notebook for this assignment.
While you can use (most) libraries and templates for dealing with this problem, you are not allowed to use the modules that do everything (or most of the work) for you (e.g. the surprise package in python). If you choose to use any existing libraries, you should be able to explain these methods and their choice in sufficient detail.
You are allowed 10 submissions in a 24 hour cycle.
Deliverables:
Valid Submissions to the Miner Website
Gradescope Submission of Source Code, Output and Report:
If you work in a group, make only one submission on Gradescope, but please make sure to select your partner's name in the submission.
Submit your Jupyter notebook (.ipynb file), as well as your .py files. You can download the source files from your Jupyter notebook. Important: Your Jupyter notebook should contain the code to print all the output (your predictions), as well as any figures or results you put in your report. This is for us to verify that your predictions and output did come from your code.
Submit your prediction file (the most recent one you submitted to Miner).
Submit your report in pdf. Your report should be 2-4 pages long, single-spaced describing details regarding the steps you followed for developing the recommender system. Be sure to include the following in the report:
Username registered on miner website.
RMSE score for your submission (at the time of writing the report).
Your Approach
The process of choosing your final approach (i.e. what did you try and what made you choose the final algorithm(s) to make your prediction, the content features you used (if any) and what worked, what did not?)
If you worked in a group, describe the contributions of both group members.
Grading:
Grading for the Assignment will be split on your implementation (40%), report (30%) and ranking results (30%).