# Netflix Case Study using EDA Python

## Table of Contents
- [About the Dataset](#about-the-dataset)
- [Business Problem](#business-problem)
- [Libraries Used](#libraries-used)
- [Recommendations](#recommendations)

## About the Dataset
---
Netflix is one of the most popular media and video streaming platforms. They have over 10000 movies or tv shows available on their platform, as of mid-2021, they had over 222M Subscribers globally. This tabular dataset consists of listings of all the movies and tv shows available on Netflix, along with details such as - cast, directors, ratings, release year, duration, etc.

## Business Problem
---
Analyze the data and generate insights that could help Netflix in deciding which type of shows/movies to produce and how they can grow the business in different countries.

## Libraries Used
---
- [Numpy]
- [Pandas]
- [Matplotlib]
-  [Seaborn]

## Recommendations
1.We have 6131 Movies compared to 2676 TV Shows which is like 2.3x of TV Shows, But in recent years, the trend has changed. In the last 5 years, the Movies proportion has reduced from ~75% to ~47% while TV Show's share has increased from ~25% to ~53%. This reflects that over the period a smaller number of Movies are getting released while more and more TV Shows are getting aired.

2.Netflix is currently serving mostly Mature audiences or Children with parental guidance (around 80% of content on Netflix). It has scope to cater to other audiences as well such as family men, Senior citizens, kids of various ages, etc.

3.It is observed that shorter-duration content is on the rise in the last 10 years. (duration 75 to 150 minutes and seasons 1 to 3) . This can be considered while production of new content on Netflix.

4.Netflix has the majority of content which is released after the year 2000. It is observed that content older than the year 2000 is very scarce on Netflix. Senior Citizens could be the target audience for such content, which is almost missing currently.

5.Very limited genres are focussed in most of the countries except the US. It seems the currently available genres suit best for the US and a few countries but maximum countries need some more genres which are highly popular in the region. eg. Indian Mythological content is highly popular in India. We can create more country-specific genres and It might also be liked across the world just like Japanese Anime.

6.Country-specific insights - The content needs to be targetting the demographic of any country. Netflix can produce a higher number of content in a particular rating as per the demographic of the country. Eg. A country like India, which is highly populous, has maximum content available only in three ratings TV-MA, TV-14, and TV-PG. It is unlikely to serve the below 14 age and above 35 year age group with only these ratings being available.

7.Japan has only 3 ratings of content largely served - TV-MA, TV-14, and TV-PG. Japan has a high population of age above 60, and this can be served by increasing the content suitable for this age group.

8.Maximum content of Netflix which is around 75%, is coming from the top 10 countries. The United States is the highest contributor, followed by India and the United Kingdom. The rest of the world only contributes 25% of the content. More countries with suitable genres and ratings can be focussed on in the future to grow the business.

