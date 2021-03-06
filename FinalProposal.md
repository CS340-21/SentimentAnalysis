# Twitter Analysis
# Team Members (Team Twitter)
    - Dereck Stewart II
    - Nick Mize
    - Anthony Sutherland
    - Chris Romanelli

# Introduction
This project is a sentiment analysis program. Social media, specifically Twitter, is where a lot of people go to express their opinions. There is valuable insight to be found online, where anonymity often promotes more honesty and a variety of opinions. This project resembles other software used for social media monitoring, however, unlike other software our application will be free to use. This software allows companies and business owners to monitor their brand reputation and their social media presence, giving insight to company growth and the effectiveness of marketing/business strategies. The members of the team have experience in object-oriented programming languages such as C++ and Python. Members of the team also have experience with machine learning practices, web APIs, and data wrangling.

# Customer Value
The primary customer is a business owner or a person with a social media presence online. The customer is someone looking for insight into the general sentiment on a certain topic. Business owners could be lacking insight into their social media presence, a valuable tool to grow/market a business. There is valuable insight on social media that a business owner can utilize to gauge the growth of the business online and to develop online marketing strategies. The project’s solution will provide data on positive/negative sentiment on a given topic and organize the data into various formats for insight on the percentage of positive/negative sentiment, the distribution of positive/negative sentiment, and location data on where sentiment is held. This project makes it easy to gather and represent sentiment data, giving insight to online, social media presence. Customer-centric measures of success will be complete gathering of data, accurate sentiment analysis of data, and accurate representation of data.

# Technology
The software will be a desktop application that gathers tweets via Twitter’s web APIs, organizes relevant data, performs sentiment analysis via machine learning libraries and algorithms, and presents data via data plotting and data graphing libraries.
The main components will be Python based and will include:

    - Twitter web API libraries for collecting tweets
    - Python machine learning library to perform sentiment analysis
    - Python data wrangling libraries to organize data
    - Python GUI libraries to present data plots and data graphs

# High-level architecture diagram
![alt text](https://github.com/CS340-21/SentimentAnalysis/blob/main/image.jpg)
# Technology
A minimal system would be one that presents data on 1200 recent tweets from the last 7 days based on a given query.Possible valuable enhancements include:

    - Larger data collection
    - Faster data collection
    - Older (more than 7 days) data collection
Testing would include:

    - Testing of individual components (Technical Testing)
    - Testing overall effectiveness (Customer Value Testing)
Technologies include:

    - Python 3.7
    - Tweepy (Twitter API wrapper library for Python)
    - TextBlob (Sentiment analysis machine learning library for Python)
    - Numpy & Pandas (Data wrangling libraries for Python)
    - PyGUI (GUI library for Python)

# Team
No one on the team has built a system like this.
Tools familiar to the team include:

    - Python/OOP (All members)
    - Tweepy/Twitter web APIs (Dereck and Nick)
    - Machine learning practices (Anthony)
    - Numpy & Pandas data wrangling libraries (Dereck and Anthony)
    - PyGUI graphic user interface library (Anthony)
Tools new to the team include:

    - TextBlob machine learning library
    
Leadership roles for the team include: (All team members will participate in all phases of development in some way)
Backend Development:

    - Twitter API setup and usage (Chris Romanelli)
    - ML library setup and usage (Anthony Sutherland)
    - Data parsing and wrangling (Dereck Stewart II)
Frontend Development:

    - Building GUI for graph and plot representation (Nick Mize)

# Project Managemnt
Our project is feasible and we plan to meet face-to-face two times a week
Weekly Schedule:
| Date              | Activity                                        | Goals                                                                    |
|-------------------|-------------------------------------------------|--------------------------------------------------------------------------|
| Thursday, Feb. 18 | Begin work on project.                          | Design minimal system to collect and analyze tweets               |
| Friday, Feb. 26   |                                    | Add location data and/or Google Trends data         |
| Thursday, Mar. 4  | Complete 1st iteration status report (1st sprint)              |                                                                          |
| Friday, Mar. 12   |                                   | Add GUI integration           |
| Thursday, Mar. 18 | Complete 2nd iteration status report (2nd sprint)           |                                                                          |
| Friday, Mar. 26   |                                   | Improve usability and make more user-friendly (help page?)  |
| Thursday, Apr. 1  | Complete 3nd iteration status report (3rd sprint)               |                                                                          |
| Friday, Apr. 9    |                                     | Final improvements and fixes |
| Thursday, Apr. 15 | Final project report/presentation (4th sprint) |                                                                          |

There are no regulatory or legal constraints nor ethical or social concerns. We will have access to data we need for the scope of our project.

Descoping to a useful system includes:

    - Reducing the overall system
    - ~500 tweets across a single day
