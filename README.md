# Twitter Hash Tag Monitor Using Amazon Lambda -Project
Monitoring hash-tags in Twitter via AWS Lambda.

Modules implemented: 

A user can search for latest tweets based on a specific hashtag. If he or she enters one for the first time, the Twitter API hits the database and gets the tweets pertaining to that hashtag. If the hashtag was already entered previously, the tweets is fetched in a way that it displays new tweets generated from the current time to the time previously it was entered. And also a feature, emailing the user with the latest hashtags trending presently in the country.

Thymeleaf and Bootstrap: A smooth and flawless UI with clear and legible buttons is shown. A home page, search/timeline page, contact page with emailing and calling functionality, home button that redirects user to the home page.

MongoLab: We used this for storing the values of the fetched tweets and its parameters in the database. We use Lambda function to do this. This is stored data is in the format of a json document.

AWS Lambda: All the computations are implemented in Lambda. The POST, GET and PUT of 
the data into the database, by using the twitter RESTful API is done. All of this code was written in Node.js.

Twitter APIs: We’ve used twitter API for getting user data like username, time of tweet and the 
tweet itself. Also we’ve used it for getting the trending hashtags in the USA.

Tools, Utilities and IDE’s: Intellij, Gradle, Twitter RESTful APIs, Node.js, AWS Lambda, AWS EC2, STS.

Future Enhancements:
Coming to the future implementations and enhancements, we would like to concentrate more about the dynamic page building. Like depicting graphs, charts, demographics, sources, topics, top sites, users and posts that were most influential are some of the things we’d like to implement.

Graphs can be plotted based on the number of tweets per hour on for a given hashtag. Also the regions or parts of the world that are tweeting about this and the top resources that generated this data. Also we can use this for social networking websites like Facebook, Youtube, Instagram and others. Also the share of retweets, favorites and posts can be depicted.

And also the tweets can be monitored via the Ajax calls from javascript, where we can stream data continuously to catch up with all the latest feed.

Also we can write an Android/iOS app for implementing the project, so that a user can get all the  latest information about the trending topics and the news feed on the go.
