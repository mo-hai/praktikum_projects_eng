# Video Games Analisis

## Objective
Perform exploratory and statistical analysis of games sales, of users and experts scores, and identify patterns that determine the success of a game to generate insight for future decision-making.


## Data
- `Name` — The games name
- `Platform` — Platform of the games release (i.e. PC,PS4, etc.)
- `Year_of_Release` — Year of the game's release
- `Genre` — Genre of the game
- `NA_sales` — Sales in North America (millions of copies sold)
- `EU_sales` — Sales in Europe (millions of copies sold)
- `JP_sales` — Sales in Japan (millions of copies sold)
- `Other_sales` — Sales in the rest of the world (millions of copies sold)
- `Critic_Score` — Critics score (max 100)
- `User_Score` — Users score (max 10)
- `Rating` — The ESRB ratings (Entertainment Software Rating Board). This organization determines the rating of computer games and assigns them a suitable age category.

Data for 2016 may be incomplete.


## Stack
*pandas*, *numpy*, *scipy*, *matplotlib*, *seaborn*


## Summary
- The average life cycle of a platform is 10 years, so the best period for analysis, which will help to predict next year game sales, is 5 years.
- The main leaders in selected period are PS, XOne and DS3, which are likely to hold the leading position for another couple of years. At the same time, the positions of the top platforms change depending on the market. PC does not occupy the top positions, but it has a long life cycle.
- Based on the results of statistical analysis, we can say that with a probability of 98%, the average user score of XOne and PC is the same.
- The top genre in all analysed markets is Action. This genre has the most qty of games and the most colume of sales. Further, the first place differs depending on the market: North America and Europe - Shooter, Japan - Role-Playing. Based on the results of statistical tests, we rejected the hypothesis about the equality of the average user score for the Action and Sports genres.
