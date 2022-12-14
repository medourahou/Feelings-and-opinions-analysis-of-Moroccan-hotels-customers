# Feelings-and-opinions-analysis-of-Moroccan-hotels-customers
<h2>1. Introduction</h2>
Sentiment analysis refers to the class of computational and natural language processing based techniques used to identify, extract or characterize subjective information, such as opinions, expressed in a given piece of text. The main purpose of sentiment analysis is to classify a writer’s attitude towards various topics into positive, negative or neutral categories. Sentiment analysis has many applications in different domains including, but not limited to, business intelligence, politics, sociology, etc. Recent years, on the other hand, have witnessed the advent of social networking websites, microblogs, wikis and Web applications and consequently, an unprecedented growth in user-generated data is poised for sentiment mining. Data such as web postings, Tweets, videos, etc., all express opinions on various topics and events, offer immense opportunities to study and analyze human opinions and sentiment.<br> In this project, we study the informations published in <b>Tripavisor</b> which is a U.S. website that offers tourists reviews and advices from visitors on hotels, restaurants, cities and regions, leisure facilities, etc., internationally.
<center><image src="screenshot.png"></image></center>

<h2>2. The project steps</h2>
The main objectif of this project is to analyse feelings and opinions through an amount of comments and reviews posted for some moroccan hotels (100 hotels), to do so, we proceed:
<ol>
<li>We scrap an amount of 100 hotel links using Selenium</li>
<li>For each hotel we scrap using Selenium a bunch of informations about the hotel (hotel name, hotel rank, localisation,	hotel link, phone number,	amenities,	room features,	room type	comments, comments rank and comments title) (<i>see the notebook scrapping.ipynb</i>)</li>

<li>Pre-process the data collected (<i>see data preprocessing.ipynb </i>)</li>
<li>Apply sentiment analysis techniques on the data (<i>see sentiment_analyisis.ipynb)</i></li>
<li>Vizualise and interpreter (<i>see sentiment_analyisis.ipynb)</li>
</ol>

