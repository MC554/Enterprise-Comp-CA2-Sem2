Group Members:Saleh,Rocky,Mercy,Josh

**1. Introduction**

Music Rankings such as “Greatest Albums of All Time” shows cultural impact, historical trends, and changes in genre popularity in the music industry.
Examining these rankings offers insight into how musical tastes have evolved over time and what genres have had the most significant long-term influence. 
This report analyses a dataset obtained from Kaggle about “The Rolling Stone’s 500 Greatest Albums of All Time”. We reduced the data set to the top 200 ranked albums, resulting in 200 records. Each row represents a single album included in the ranking.  

The dataset consists of six variables:  

1.Ranking position 
2.Release year 
3.Album title 
4.Artist name 
5.Genre 
6.Subgenre 

Ranking position & release year (Variables 1-2) are quantitative variables (numerical variables) while the other variables (Variables 3-6) are categorical variables. 
This analysis aims to identify patterns from the Top 200 albums to see how music trends over time influence which genres appear most often in the rankings. 

**2. Data Cleaning & Preparation** 

The original dataset from Kaggle contained 500 albums. But for the purpose of this project, only the rankings between 1-200 albums were selected to make it simpler. 
This was made to focus on the highest-rated entries and to maintain consistency in examining top-ranked music albums. 
After filtering the data, the dataset was checked for missing values, including release year, ranking number, album title, genre, artist and subgenre. 
There were no missing values as a result, no data needed to be filled in or removed, so everything remained complete and organized for descriptive statistical analysis.  

**3. Descriptive Statistics**

We used descriptive statistics to examine the release years of albums in the Top 200 ranking.The average (mean) release year is 1975, and the median is 1972. 
These numbers are close in value, which shows that most albums were released around the early to mid 1970s.The mode (the most common release year) is 1967, this means that more albums were released in that year than any other year in the dataset. 
The oldest album was released in 1955, and the newest in 2005, giving a total range of 50 years this might look a large time span but based on the standard deviation is around 10 years. 
Standard Deviation shows/measures how spread out the albums are. A high standard deviation means the data values are very spread, while a lower one shows that values are closer together and grouped near the mean, (JMP Statistical Discovery, 2026).
So a standard deviation of 10 years shows that most albums were released within a smaller period (around the 1970s), which means albums from that era make up a large part of the ranking.  

When we grouped it by decade, we saw that the 1970s had the highest number of albums (84 albums), followed by the 1960s (62 albums). 
When we add these two decades, it makes up 146/200 albums around 70% of the dataset. When we checked the 1990s which have 16 albums and 2000s which have 8 albums, we saw that there were fewer albums compared to the 1970s and 1960s. T
his big difference shows that the ranking favors older music.  

We can also see an imbalance from the genre distribution because “Rock” is the most common genre having 142/200 albums. Other genres like Funk (39), Pop (21), Blues (17), Jazz (11), Hip Hop (8), Electronic (110, Raggae (6), 
and Fold (13) show less often, once again showing an imbalance that the Top 200 ranking favors Rock compared to other genres. 

**4. Visual Analysis**

PIE CHART:
The pie chart shows Rock dominating the Top 200 with 142 albums (71%), nearly three times larger than all other genres combined. Funk/Soul follows at 19.5% and Pop at 10.5%, while genres like Hip Hop, Jazz, Electronic and Reggae barely register. This stark imbalance highlights a clear editorial bias toward Rock, likely reflecting the background and era of the critics who voted. The pie chart was the most effective choice for this data as it allows the viewer to instantly grasp how disproportionate the genre representation truly is.  

BAR CHART:
The bar chart illustrates how frequently individual artists appear across the Top 200. A small number of artists — such as The Beatles, Bob Dylan, and The Rolling Stones — have significantly more entries than the rest, while the majority of artists appear only once or twice. This is a classic long-tail distribution, where a small elite group holds a large share of representation. It raises an important question: does appearing multiple times reflect genuine artistic greatness, or does it simply reflect that these artists came from the era the ranking already favours most? Notably, no Hip Hop or Electronic artist comes close to the entry count of the leading Rock acts, further reinforcing the genre imbalance identified throughout the dataset. 

LINE CHART:
The line chart tracks the number of Top 200 albums per decade, rising steadily from the 1950s and peaking sharply in the 1970s at 84 albums. After that, it falls continuously — 16 albums in the 1990s and just 8 in the 2000s. This decline is particularly significant when you consider that genres like Hip Hop, Electronic, and Alternative Rock were at their commercial and cultural peak during the 1980s and 1990s, yet they barely appear. This can be explained through the concept of critical canon formation — older albums have had far more time to be reviewed, referenced, and appreciated across multiple generations, which naturally elevates them in retrospective rankings. The line chart therefore not only shows what music made the list, but also reveals the generational bias of those who compiled it.

 MACHINE LEARNING  

The basic machine learning method was applied to test whether simple features could predict album rankings in The Rolling Stone's 500 Greatest Albums of All Time Top 200 list. The ranking system used two categories where albums in the 1-100 range received a 1 rating and albums in the 101-200 range received a 0 rating. The prediction used release year and genre and subgenre information while album title and artist name details were excluded because they contained excessive name variations. The research team selected a basic logistic regression model because it provides straightforward operation and performs effectively with limited datasets. The data was divided into two parts to create a training set and a testing set which the researchers used to evaluate model performance. The study found that albums from the 1960s and 1970s had a higher probability of being included in the Top 100 list. The Rock genre also had a higher chance of ranking in the Top 100. The basic machine learning approach confirmed the previous findings which showed that older albums and Rock music achieve better ranking positions. 

 

Limitations & Ethical Considerations 

The research examined The Rolling Stone collection of 500 Greatest Albums of All Time to analyze music trends through its Top 200 albums. The research shows that older music from the 1960s and 1970s received more favorable ranking results than newer music. Rock music constitutes approximately 70% of the total albums, while all other genres make up the remaining portion. The artists who have multiple appearances in the study demonstrate their status as highly successful musicians. The basic model demonstrated that older albums had a 100% probability of becoming Top 100 entries while Rock music would reach only 50% probability. The dataset shows some level of bias because the rankings depend on subjective judgments which prevents it from presenting complete musical information. 

Conclusion  

The analysis of the Top 200 albums shows that albums from the 1960s and 1970s receive higher rankings than newer albums. The majority of the list contains rock music as its primary genre. Multiple appearances by certain artists demonstrate their strong popularity among listeners. The basic model revealed that both Rock music and older albums have a higher chance of reaching the Top 100 list. The rankings display distinct patterns, but they rely on subjective judgments and fail to represent all music genres and artists. 
