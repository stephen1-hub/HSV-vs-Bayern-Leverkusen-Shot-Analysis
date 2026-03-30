# HSV-vs-Bayern-Leverkusen-Shot-Analysis
# Objective

The goal of this project was to analyze shot patterns, efficiency, and player performance during the HSV vs Bayern Leverkusen Frauen-Bundesliga match. By visualizing and quantifying shot data, the aim was to identify key attacking and defensive trends, top performers, and tactical insights that can inform team strategy and player evaluation.

# Data Used
Source: Match event data from HSV vs Bayern Leverkusen
Columns: team_home, player, x, y, shot_type, situation, count, distance, avg_distance, shooting_accuracy
Sample Data Points:
Player shots and outcomes (goal, miss, save, block, post)
Shot coordinates (X-Y location on the pitch)
Average distance to goal per shot
Shooting accuracy per player
# Key Findings
# Shooting Efficiency:
Camilla Linberg had 100% shooting accuracy from 1 attempt.
HSV generated more total shots but converted fewer than Bayern Leverkusen.
# Player Contributions:
Most active shooters: Cornelia Kramer (5 shots), Katharina Piljić (4 shots), Vanessa Fudalla (4 shots).
# Top scorers: Camilla Linberg, Katharina Piljić, Julia Mickenhagen, Vanessa Fudalla.
# Shot Patterns & Situations:
Majority of Bayern Leverkusen’s shots came from assisted attacks and corners.
HSV relied on fast-breaks and set-pieces.
# Shot Locations:
Goals primarily came from inside the 20m range.
Right-foot shots dominated across both teams.
Several blocked or missed shots indicate defensive pressure and suboptimal positioning.
# Distance vs Accuracy Insight:
Players closer to goal generally had higher shooting accuracy.
Long-range attempts often resulted in misses or blocks.
# Visuals
Shot Map – Displays X-Y shot locations, color-coded by outcome, and annotated with distance to goal.
Goals per Player – Bar chart highlighting top scorers for each team.
Shooting Accuracy vs Average Distance – Scatter plot showing efficiency relative to shot distance.
Shot Situation Breakdown – Bar chart visualizing distribution of assisted, corner, fast-break, regular, and set-piece shots.

(All visuals generated using mplsoccer, matplotlib, and pandas.)

# Tactical Implications
Bayern Leverkusen should focus on shot quality over quantity, creating more high-probability scoring chances closer to goal.
HSV can capitalize on fast-break opportunities and set-piece strategies.
Defensive adjustments can be made based on blocked shot zones to minimize opponent efficiency.
Coaches can assess player performance using shooting accuracy and distance metrics to inform training and match strategy.

✅ Next Steps / Expansion:

Incorporate expected goals (xG) models to quantify shot quality.
Compare home vs away performance trends.
Expand analysis across multiple matches for season-level insights.
