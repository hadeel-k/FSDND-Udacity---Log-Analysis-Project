# Log-Analysis-Project

# About This Project:
This project is for Udacity's Full Stack Developer Nanodegree Program. 

# Project Overview:
> In this project, you'll work with data that could have come from a real-world web application, with fields representing information that a web server would record, such as HTTP status codes and URL paths. The web server and the reporting tool both connect to the same database, allowing information to flow from the web server into the report.

# The questions that should be answered by this project:
What are the most popular three articles of all time? Which articles have been accessed the most? Present this information as a sorted list with the most popular article at the top
Who are the most popular article authors of all time? That is, when you sum up all of the articles each author has written, which authors get the most page views? Present this as a sorted list with the most popular author at the top.
On which days did more than 1% of requests lead to errors? The log table includes a column status that indicates the HTTP status code that the news site sent to the user's browser.

# PreRequisites:
- Python3
- Vagrant
- VirtualBox

# How to run this Project:
- Clone/Download this repository
- Launch Vagrant VM by running vagrant up, you can the log in with vagrant ssh
- To load the data, use the command **psql -d news -f newsdata.sql** to connect a database and run the necessary SQL statements.
- To execute the program, run **python3 newsdata.py** from the command line.
