# Twitter Analysis - Final Project Report
# Team Members (Team Twitter)
    - Dereck Stewart II
    - Nick Mize
    - Anthony Sutherland
    - Chris Romanelli

# Introduction
This project is a sentiment analysis program for Twitter. Social media is where a lot of people go to express their opinions. 
There is valuable insight to be found online, where anonymity often promotes more honesty and a variety of opinions. 
This project resembles other software used for social media monitoring, however, unlike other software our application will be free to use. 
This software allows companies and business owners to monitor their brand reputation and their social media presence, giving insight to company growth and the effectiveness of marketing/business strategies. 
Our approach to this project was to collect tweets from Twitter, perform sentiment analysis on them, and show the results of the sentiment analysis on the frontend via charts/graphs.
During our development of the project, there were no major changes to our approach or our development plans. 
We were able to complete the project as we intended to design it. There was no notable difficulties throughout the process.

# Customer Value
No Changes

# Technology
The software is a desktop application that gathers tweets via Twitter’s web APIs, organizes relevant data, performs sentiment analysis via machine learning libraries 
and algorithms, and presents data via data plotting and data graphing libraries.
The project's components and libraries are written in Python 3.7 and include:

    - Tweepy - A Python library for collecting tweets with Twitter's web API
    - Textblob - A Python machine learning library that perform sentiment analysis
    - Matplotlib & Numpy - Python data representation libraries that organize data into charts and graphs
    - Dearpygui - A Python GUI library to build the frontend of the application

# High-level architecture diagram
The diagram of the high-level architecture that we have implemented is the same as the diagram from the proposal\n

The diagram of the implemented high-level architecture is shown below:

![alt text](https://github.com/CS340-21/SentimentAnalysis/blob/main/image.jpg)

# Testing
Testing the application included running the software with various search queries. We tested to make sure we could run the applications with all selectable
tweet counts. We also tested the accuracy of the analysis by making sure the data was reasonable and varied across different search queries.
The results of our testing showed that our application works as it is designed.

# Technology cont.
Initially, we planned to build a minimal system that presents data on 1200 recent tweets from the last 7 days based on a given query. We decided to limit the collect of tweets 
to 1000 and allow users to select a lower number of tweets to collect from (250, 500, 750, or 1000). We made this change because of the rate limits of the free 
usage of Twitter's API. This change also allows for faster data collection.

# Team
The team members' roles remained static throughout development. All team members contributed equally
Throughout the development of the project, team members filled the following roles:

Backend Development:

    - Twitter API setup and usage (Chris Romanelli)
    - ML library setup and usage (Anthony Sutherland)
    - Data representation (Dereck Stewart II)
    
Frontend Development:

    - Building GUI for graph and plot representation (Nick Mize)

# Project Managemnt
We were able to complete all of our goals for the product on schedule.

# Reflection
Overall, the project went well. The planning aspect was straight forward and well organized. This allowed for development to be very streamline. All team members 
were able to complete their portions of the project on time. Testing went well and we did not run into any major issues with the project. Team management also went well. 
We were able to meet virtually (via Zoom) several times during each sprint and also communicated through GroupMe. There was no part of the project that did not go well.

Overall, we consider the project a success. All members contributed equally and all aspects such as planning, development, testing, and team management went smoothly
and successfully.
