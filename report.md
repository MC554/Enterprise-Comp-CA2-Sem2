**1. Introduction**

Music Rankings such as “Greatest Albums of All Time” shows cultural impact, historical trends, and changes in genre popularity in the music industry.
Examining these rankings offers insight into how musical tastes have evolved over time and what genres have had the most significant long-term influence. 
This report analyses a dataset obtained from Kaggle about “The Rolling Stone’s 500 Greatest Albums of All Time”. We reduced the data set to the top 200 ranked albums, resulting in 200 records. Each row represents a single album included in the ranking.  

The dataset consists of six variables:  

Ranking position 
Release year 
Album title 
Artist name 
Genre 
Subgenre 
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
The pie chart which represents Genres shows that “Rock” is more popular. Rock takes 142/200 which is around 70% of the dataset.  
The rest of the genres occupy smaller  propositions of the chart. This visual representation reinforces the genre imbalance in the ranking. 

BAR CHART:
This chart represents how many times an artist appears. From the chart we see that some artists are recognized more than others, which means they are very popular. 

LINE CHART:
The line chart shows that the number in albums increases in the 1960s and reaches its peaks in the 1970s. After the 1970s, the number starts to decrease lower and lower. 
This pattern aligns with the statistics and shows once again that older decades are more favored in the ranking.   
 

 
