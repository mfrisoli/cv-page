---
title: "Decision Maker"
date: 2020-08-10T22:41:15+01:00
draft: false
---
header:
  image: "static/media/DM.JPG"
  caption: "Image credit: [**Decision Maker**](http://decision-maker-2020.herokuapp.com/)"

Decision Maker is a dynamic web application made to help groups decide in what to do. 

This is done by creating a topic (a room) and putting together a couple of choices (options), sharing it with your group so they can vote on what they like best; after the voting is finish and the poll closes you can see the results.

The app is built in Flask microframework written in python. The application uses the advantages of Object Relation mapping (ORM) to handle the database using SQL Alchemy library.

SQlite3 was used originally as a Relational Database Management System (RDBMS) but then it was migrated to PostgreSQL to facilitate production deployment in Heroku.

HTML templates were written using Jinja, this enable the use of python logic allowing to dynamically update the HTML content.

JavaScript was used as part to validate input on the client side before submitting data via “Post” request.

For more details on the specifications of the app, please view README.md found at the repository.

* **Repository:** https://github.com/mfrisoli/decision-maker   
* **App site:** http://decision-maker-2020.herokuapp.com/
