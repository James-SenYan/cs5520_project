---
layout: post
title: "Final Project Proposal: Adding features to Todo App"
---

# This is a proposal for my final project: Add fancy features to my Todo App

## Sorting/filtering tasks
I would say that sorting and filtering tasks are provided in various applications. Users are likely to sort tasks based on deadline of each task and filter tasks that are marked done already.

This would be implemented by adding an item in menu. Create a method called sortingByXXX in DAO and write sql queries. FilterByXXX methods are created in DAO and their respective sql queries.


## Searching
Chances are that users created hundreds of tasks without deleting any of them which makes them harder to locate the desired one. In order to elevate efficiency, I noticed that adding a search box at the top of my home page is necessary. 

What I'm expecting from this function is that tasks are filtered according to key words I typed in.

I'm wondering that this could also be implemented by using sql queries. Other than sql, regular expression might be useful.


## User account and logging authentication
Literally, all applications have logging authentication process and require users to create accounts.
For signing up for my Todo app, users are required to type into their username and password. When signing in next time, users are logged in until they input correct username and password. They should match the record in database.

## Google Assistant: lauch my app via voice

Google Assistant is the google voice assistant which is powerful so that it could connect home devices and build natural conversations. What I want to do with google assistant is that launching my todo app by simply saying "hey google, open Todo App"!

After searching solutions on google, I found this could be implemented by BII(built-in intents) which are created by google. The idea is to create a xml file and specify a shortcut in it.

However, I noticed that I could use google assistant only if I've published my todo app to google play console. I can not published my app to play console since I don't have a valid ID or driving license for authentication.
