# tmdb
TMDB data analysis

# DataSet used: TMDB movie data (https://www.google.com/url?q=https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd1c4c_tmdb-movies/tmdb-movies.csv&sa=D&ust=1535239413276000)

# Questions to be analyzed:
#1) Year profitability comparision.- this will identify the year we have maximum and least profitability
# 2) Run time (Average) of the movies
#3) Highest gross(Revenue) movie vs lowest
#4) Highest Budget vs lowest
#5) Plotting runtime of movies

#Documentation of any data wrangling:
 #Dataset Obsevations and initial cleansing:
#  Assuming columns (budget,revenue, budject_adj and revenue_adj) are dollar amounts, as unit of measurement is missing, I'm treating them as $$$$ amount
# Remove unused columns such as id, imdb_id, vote_count, production_company, keywords, homepage etc.
# remove data that appears duplciate or have zero budget.
# column data type formatting , ex: release date as time stamp.
# Changing format of budget and revenue column.

#Methodologies used: code has self explanatory comments to walk through the process of analyzing the data
