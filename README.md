# BB-numeric-analyzer
> ### Basketball Scores Numeric Analyzer

> ## Problem

> The goal of this project was to analyze a basketball dataset using NumPy. The dataset contains information about each match, including the match number, points scored by our team, points scored by the opponent, rebounds, and assists. The analysis was used to understand the team's performance and identify important statistics such as average scores, winning matches, and the best game.

> ## Approach

> The dataset was loaded into NumPy using a structured array. NumPy functions such as mean(), max(), min(), sum(), and argmax() were used to calculate statistics. Boolean masks were used to filter the data, such as finding matches where our team scored more points than the opponent and counting games where the team scored more than 100 points. the labels were used as well to create a comparison for each match (Win if points_allowed > points_scored, otherwise Loss).

> ## Results

> The team won 3 out of 12 matches based on the Win/Loss labels.
> The highest-scoring game was identified using argmax(), which returned the match with the maximum points scored.
> Boolean masks and labels made it easy to separate winning and losing matches and analyze the team's overall performance. As, the opponent team named as points_allowed suffered a major loss in comparison to points_scored team which won with high flying score.
