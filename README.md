## Highlighted news

## By Peter Anami

## Description

- Highlighted news is a web appliction that displays a list of news sources from around the world. A user is able to click on a news source and view version of the news abreviation of a particular news article. when you Click the news article will then redirect you to the news article's web page.

## With the application, a user will be able to:

- See various news sources and select the ones they prefer.
- See all news sources from the source they selected.
- See Image description and time the news article was created.
- Click on an article and read it fully from the news source

## Specifications

- Display news sources	On page load	List of various news sources is displayed per category
- Display articles from a news source	Click a news source	Redirected to a page with a list of articles from the source
- Display the preview of an article	On page load	Each article displays an image, title, description and publication date
- Read an entire article	Click an article	Redirected to the news source's site to read the entire article
- Prerequisites

## You need the following to start working on the project on your local computer:

A computer running on either Windows, MacOS or Ubuntu operating system installed with the following:
- Python version 3.6
- Flask
- Pip
- virtualenv
- A text  Editor

## Getting Started
- Clone this repository to your local computer.
- Ensure you have python3.6 installed in your computer.
- From the terminal navigate to the cloned project folder.
- Create a virtual environment and access the folder via your virtual amchine.
- Visit https://newsapi.org/ and register for an API key.
- Create start.sh file and in it write the following lines:
- export NEWS_API_KEY='<Your-Api-Key>'
- python3.6 manage.py server
- Run chmod +x start.sh follwoed by ./start.sh while in the project folder to start the project.
- Once started, the project can be accessed on your localhost using the address: localhost:5000.
- Alternatively the application can be accessed by visiting 

## Technologies Used
- Python v3.6
- Boostrap
- Flask

# Lisence
- Copyright (c) 2021 Peter Anami

- Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files.

- The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

- THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED.