# Game Plan: Building a Predictive Model for Video Game Sales
The video game industry has grown exponentially over the last decade. In 2020 alone the gaming industry generated $155 Billion in revenue and it is projected that it will generate more than $260 Billion in revenue by 2025. One of the leading platforms which facilitates this industry is the Steam software by Valve corporation. This project aims to understand the relationship between the sales of video games on the Steam platform and the attributes which contribute to them. The analysis can give game developers and publishers an insight into what makes certain games popular and allow them to make games that will have a larger possibility to stand out in the market.

# Problem Statement
In order to survive in the playing field and create games that can be successful, it is important to understand the factors which affect the popularity and sale of the game. 

The question this project sets out to answer - “_Is it possible to predict how well the game will sell based on its characteristics_?”

Another question the analysis aims to answer - “_What are the common characteristics that define the best-selling games_?”

# Target Audience
Game developers and publishers are a strong group of consumers for our analysis. By understanding the factors that affect the sales of a video game, game developers and
publishers would be able to find ways to stimulate customers to make a purchase. The analysis will help video game developers to manage and maintain quality and at the same time remain relevant in the market. It will help them examine new games to be produced in terms of user reviews, users’ most preferred genre, top platforms preferred by gamers, etc.

Another set of target audience are the customers. The advent of digitalization has brought advantages and disadvantages for both developers and consumers; increased availability of games leads to bigger markets and potentially more consumers, however at the same time consumers face the potential of becoming overwhelmed by the sheer number of available games. This analysis can help customers to select games based on the most favoured genre of other players, top user reviews of a particular game, etc.

# Methodology
Step 1: Data Collection, Preparation, and Description
The analysis is based on the games available on steam platform, hence it was needed to collect the information available on games listed on the platform.
There are 3 main sources from which this information has been collected: 
1. Steam
2. Steamspy
3. Metacritic

Step 2: Data Cleaning
The following methods were used to clean the dataset and transform the variables- 
1. Remove unnecessary columns
2. Handle missing observations
3. Datatype conversion and content parsing
4. Handle duplicate games
5. Filter records based on condition

Step 3: Exploratory Data Analysis
I have performed EDA primarily to see what data can reveal beyond the formal modeling or hypothesis testing task and provide a better understanding of data set variables and the relationships between them. I have used the SweetViz library, an open-source Python library that generates beautiful, high-density visualizations to kickstart EDA with just two lines of code.

Step 4: Analysis and Results
The analysis was performed using K-means clustering, linear regression and ordinal regression to identify the elements that influence game sales.

# Conclusion
This project aims to identify the factors influencing the popularity of video games utilizing features that were collected from the Steam webpage. I performed K means clustering and ordinal regression and classified the video games into 3 categories - low(0), medium(1) and high(2) based on the number of owners. From the experiments performed, I can conclude that there is a correlation between features such as adventure genre, racing genre, sexual genre, the initial price of the video games, controller support, windows platform support, and the popularity of the video game. This information can be leveraged for game development reference to select appropriate genres and operating system support to make the games more popular. This analysis was limited  to those games available on Steam. Future studies could
consider utilizing games from multiple platforms to analyze whether the results are consistent or not.
