# Flask-API-Grocery-List
A flask project using python to create a grocery list of items to get. 
Follows a tutorial from Jake Rieger following the steps in this video: https://www.youtube.com/watch?v=Z1RJmh_OqeA&ab_channel=freeCodeCamp.org
Or in this repository: https://github.com/jakerieger/FlaskIntroduction
Modified to get items from a grocery list as well as their quantities. 

Motivation: to create a list for items that run out from a household infrequently. Eventually for the program to find patterns in items and how frequently they are added to the list to make suggestions.

How To Run
1. Install virtualenv:
$ pip install virtualenv
2. Open a terminal in the project root directory and run:
$ virtualenv env
3. Then run the command:
$ virtualenv \path\to\env\Scripts\activate
4. Then install the dependencies:
$ (env) pip install -r requirements.txt
5. Finally start the web server:
$ (env) python app.py
