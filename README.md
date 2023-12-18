# Random Walk DS Assessment Level 3
 
 Live Coding Assessment for Data Science Roles at Random Walk

## Instructions:

1) Please ensure that you are taking the assessment alone in an empty room with good internet connectivity.

   Internet Speedtest Link: https://www.speedtest.net/

2) Fork the github repo into your personal Github account and take a clone into your local system.

   Guide to Forking Github Repo: https://docs.github.com/en/github-ae@latest/get-started/quickstart/fork-a-repo

   Guide for cloning Github Repo: https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository

3) Intantiate a Jupyter Notebook instance in the local working directory and create a notebook which answers the following questions.

   Guide for installing Jupyter Notebook in Local system: https://test-jupyter.readthedocs.io/en/latest/install.html

4) Save the notebook and push it into forked Github github repo.

   Guide to pushing code into Github Repo: https://docs.github.com/en/migrations/importing-source-code/using-the-command-line-to-import-source-code/adding-locally-hosted-code-to-github
   
5) Share the repository link into the Google Form: https://forms.gle/xvvXnZdR8SQAGeQA9

## Questions:

Provided are 3 CSV files **books.csv**, **book_tags.csv** and **ratings.csv** for the assessment.

 Candidate must create a jupyter notebook which processes the data provided in the CSV files to solve the following questions within the time limit provided.


1) How many books do not have an original title [books.csv]?

2) How many unique books are present in the dataset ? Evaluate based on the 'book_id' after removing records containing null values for original_title column in [books.csv] and corresponding records in [book_tags.csv] and [ratings.csv]

3) How many unique users are present in the dataset [ratings.csv] ?

4) How many unique tags are there in the dataset [book_tags.csv] ?

5) Which tag_id  is the most frequently used ie. mapped with the highest number of books [book_tags.csv]  ? 
(In case of more than one tag, mention the tag id with the least numerical value)’.

6) Which book (title) has the most number of counts of tags given by the user [book_tags.csv,books.csv] .

7) Plot a bar chart with top 20 unique tags in descending order of ‘user records’ (the number of users tagged the given tag_id with the goodreads_book_id) [book_tags.csv]