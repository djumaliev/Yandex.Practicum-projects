# YP_research_on_the_streamchik
Research on the "Streamchik" online game store's sales worldwide.
We have data on the sales of games from the "Streamchik" online store for several years. The data should include information on game sales, user and expert ratings, genres, and platforms (for example, Xbox or PlayStation). The dataset will include the abbreviation ESRB (Entertainment Software Rating Board) — an association that determines the age rating of computer games. ESRB evaluates game content and assigns it a suitable age category, such as "For Adults," "For Early Childhood," or "For Teens." Data description:

Name — game title
Platform — platform
Year_of_Release — year of release
Genre — game genre
NA_sales — sales in North America (millions of copies sold)
EU_sales — sales in Europe (millions of copies sold)
JP_sales — sales in Japan (millions of copies sold)
Other_sales — sales in other countries (millions of copies sold)
Critic_Score — critic score (maximum 100)
User_Score — user score (maximum 10)
Rating — rating from the ESRB organization. This association determines the rating of computer games and assigns them a suitable age category.
Main research hypotheses:

The average user ratings for Xbox One and PC platforms are the same;
The average user ratings for Action and Sports genres are different.
Research process:

Using data from the '/datasets/games.csv' file, the data quality will be determined first.
Data preprocessing, error correction, filling in missing values, or removing anomalous values.
Data merging for research purposes.
Data analysis and calculation of key parameters.
Testing the main hypotheses.
Conclusions based on the analysis.

Used Lybraries:

pandas, scipy, numpy, seaborn, matplotlib.pyplot
