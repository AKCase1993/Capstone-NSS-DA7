Tobacco: Lucrative or Lethal 
How much revenue does the Tobacco industry bring in to the country each year compared to the effects it has on the countries overall health and mortality rate?

This is the fundamental question to my Capstone Project. For decades, people in our nation have been using tobacco products with the knowledge that it is harmful to one’s health. Why is this and what is being done about it? 

Motivation
Since I left college, I have worked with people living in poverty. Many of these individuals struggle with substance abuse. Often these men and women do not receive a stable form of income. Despite all these factors, these men and women still find ways to obtain tobacco products. Addiction is a powerful thing that our country seemingly overlooks due to the revenue tobacco provides. 
Data Question
How often are tobacco products used in the US? How much is made from said products, and what would the economic impact be if these items were no longer in circulation? What are the current effects of the products on Americans’ health? Is our government doing enough to combat the negative outcomes?

Acquiring the Data
I began by researching tobacco usage on the website “Our World in Data”. Here, I was able to find several spreadsheets concerning tobacco usage per state, the amount of income each state was earning from tobacco sales, and more. 
Though useful, I was interested to find out where the United States ranked as far as tobacco prevention per country. This led me to the World Health Organization. 
Finally, I went to the CDC to take a deep dive into the harmful impact to people who use these products and the effect it had on their health. 

Smoking - Our World in Data

Smoking: How large of a global problem is it? And how can we make progress against it? - Our World in Data

Current Cigarette Smoking Among Adults in the United States | CDC

CDC - Fact Sheet - Tobacco-Related Mortality - Smoking & Tobacco Use (iiab.me)

Scorecard2014_2020_WHO.xlsx (live.com)

State Tobacco Revenues Compared with Tobacco Control Appropriations — United States, 1998–2010 (cdc.gov)
Cleaning the Data
When it was all said and done, I ended up with eight data sets that spanned from nearly three decades worth of statistics. For data cleaning and manipulation, I utilized Python. The most challenging portion of this was trying to find common threads to join the datasets. For example, When looking into data strictly broken up into state by state information, the joins were quite simple. However, when looking into which races and genders had more tobacco usage, I had to get creative, breaking tables down to their bare minimum to be able to correctly join the information. 
As I dove deeper into the cleaning and manipulation, I began sub-setting my data into the years I was interested in as well as separating what actually told the story I was hoping to get across. This allowed me to create baseline data frames.


