# Developing a new iOS or Android App

Our aim in this project is to find mobile app profiles that are profitable for the App Store and Google Play markets. We're working as data analysts for a company that builds Android and iOS mobile apps, and our job is to enable our team of developers to make data-driven decisions with respect to the kind of apps they build.

At our company, we only build apps that are free to download and install, and our main source of revenue consists of in-app ads. This means that our revenue for any given app is mostly influenced by the number of users that use our app. Our goal for this project is to analyze data to help our developers understand what kinds of apps are likely to attract more users.

## Opening and Exploring the Data
As of September 2018, there were approximately 2 million iOS apps available on the App Store, and 2.1 million Android apps on Google Play.

Collecting data for over four million apps requires a significant amount of time and money, so we'll try to analyze a sample of data instead. To avoid spending resources with collecting new data ourselves, we should first try to see whether we can find any relevant existing data at no cost. We have in this project two data sets on thousands of apps on both the play store and apple store we will open and anazlyze.

## Method

We will start by cleaning the data of any duplicate apps we find in either data set, exclude non-free apps, and also exclude any apps that are not in English. Then we will classify the most popular apps by genre from that subset of free, English apps from both the play store and appstore to narrow down which apps are most commonly downloaded by users. Once we determine the most popular genre for either store, we can use the `downloads` feature as a scale of which app is the most downloaded and conclude from there which is the best app to develop next for iPhones and Androids.

## Conclusion 

In the end we find that recommending a book reference app is the most profitable app to develop for both the Google Play and the App Store markets. The markets are already full of libraries, so we need to add some special features besides the raw version of the book. This might include daily quotes from the book, an audio version of the book, quizzes on the book, a forum where people can discuss the book, etc.
