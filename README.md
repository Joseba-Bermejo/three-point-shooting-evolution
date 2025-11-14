# 3-Point shooting efficency evolution: NBA vs EuroLeague

### Introduction

Over the past decade, both the NBA and EuroLeague have seen a significant rise in the proportion of 3-point attempts relative to total shots. While it’s often assumed that greater reliance on 3-pointers might reduce overall shooting efficiency due to their difficulty, this project explores whether teams have managed to maintain (or even improve) their overall shooting accuracy despite this shift. The goal is to challenge traditional views on the trade-off between shot selection and scoring effectiveness in modern basketball.

### Glossary

- 3PA (3-Point Attempts): The average number of 3-point shots a player/team attempts per game.
- 3PM (3-Point Made): The average number of 3-point shots a player/team makes per game.
- 3P% (3-Point Percentage): The success rate of 3-point shots, calculated as the percentage of made 3-pointers out of total attempts.
- 2PA (2-Point Attempts): The average number of 2-point shots a player/team attempts per game.
- 2PM (2-Point Made): The average number of 3-point shots a player/team makes per game.
- 2P% (2-Point Percentage): The success rate of 2-point shots, calculated as the percentage of made 2-pointers out of total attempts.
- FGA (Field Goal Attempts): The total number of shots a player/team attempts per game, including both 2-point and 3-point shots.
- FG% (Field Goal Percentage): The overall shooting efficiency, calculated as the percentage of all field goals made (2PM + 3PM) out of total field goal attempts (2PA + 3PA).
- 3PA ratio: The percentage of total field goal attempts that are 3-point shots, calculated as (3PA ÷ FGA) × 100.

#### Key metrics for my analysis

- 3PA, 3PA ratio, FG%.


### Questions I want to answer

- What's the trend of 3PA per season in the last 10 years?
- How has the 3PA ratio evolved YoY in both leagues?
- Assuming an increase in 3PA ratio, how does that impact shooting efficiency overall (FG%)?

### Hypothesis

1. The NBA has seen a greater increase in the 3PA ratio than the EuroLeague over the past decade.
2. A higher 3PA ratio doesn't correlate to lower shooting efficiency in the NBA or EuroLeague.

### Data Sources

Data for this project has been sourced from:
- [NBA Stats API](https://pypi.org/project/nba_api)
- [EuroLeague API](https://pypi.org/project/euroleague-api)

### Methodology

1. Collect 10 years of NBA and EuroLeague team-level metrics mentioned in the glossary.
2. Data Wrangling: standardize datasets, create new metrics (e.g. 3PA ratio, FG% in the case of the Euroleague, etc.), drop unnecesary columns.
3. Normalize seasons and align date ranges for comparison
4. Analyze trends and create compelling visualizations
5. Observe correlations, answer the questions and test the hypothesis

### Conclusion

The final analysis challenges the assumption that increased 3-point volume comes at the cost of efficiency. Instead, it suggests that both leagues (particularly the NBA) have adapted to the modern game by improving accuracy alongside volume. 

### Other resources

- [Trello (Kanban Board)](https://trello.com/b/N9p2efYk/nba-vs-euroleague-defense)
- [Visualizations G-Sheet](https://docs.google.com/spreadsheets/d/1cTktLIg_FSRoOjIIciU5MrxEJ1mOyX0oeR2IvhNfUgM/edit)
- [Presentation Slides]([https://docs.google.com/presentation/d/1eIiYDLv2m5j2wnUbISQF_i6USvnNt7Gqxzgm4yg24f8/edit](https://docs.google.com/presentation/d/e/2PACX-1vS8J_TK7sEmG5_8CjSlquofyMC3oWLOADdxvdXToVIbizvt1pzebeoAwBVLidNZZvTmHTJI1qBWVp21/pub?start=false&loop=false&delayms=3000&slide=id.p1))

