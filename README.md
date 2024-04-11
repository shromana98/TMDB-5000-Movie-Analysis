# TMDB-5000-Movie-Analysis-Prediction
# 🚀Objective: 
The objective of this project is to understand what variables define the success of films🎬, a successful movie being a movie with higher revenue and score. Let's unravel some intriguing findings from my analysis:

# 🔍 Data Cleaning: 
(Source: Kaggle) the first task was to browse all the data and replace the json character in string format using the json.loads() method.
Dealt with the null values, duplicates, zero values, data type of columns. 

 # 📊 Exploratory Data Analysis (EDA) :

# 💡 Insights:

-Profit and Popularity shows a positive but low correlation.
-Wednesday emerges as the day with the highest average profit and popularity, while Friday lags behind.
-Majority of movies the revenues increases when the rating increase
-The rating of movies increases especially when the number of actors is around 6 and 7 main actors and in most of the cases the revenue increases when the number of actors increases.
-Medium films steal the spotlight, consistently outperforming other categories in terms of average profits.
-Short films exhibit increasing profit trends, with 2015 and 2016 surpassing the overall profit mean.
-Long films garner the highest average vote ratings in 2009.
-Action genre reigns supreme in revenue generation, with iconic movies like Avatar setting the bar high.
-Warner Bros emerges as the top production company, leading the pack in the number of movies released.
-Despite the dominance of male-centric narratives, there's potential for diversification and inclusivity in the industry.

# 🤖 Model Training and Evaluation: 

# ⚙️ Data Preprocessing Steps:

1.Restriction of the actors and production companies features:
2.Creating dummy variables:
3.Standardization:

# 🤖 Model Selection:

Leveraging different regression techniques such as Ordinary Least Squares (OLS) regression, Ridge regression and XGboost, try to find the most suitable by evaluating their performance. I aim to predict revenue and average ratings. XGboost outperforms both Ridge Regression and OLS.
 
# 🚀Conclusions:
As a movie enthusiast or a key player in the film industry, understanding the dynamics of box office success and movie quality is paramount. 🌟 
